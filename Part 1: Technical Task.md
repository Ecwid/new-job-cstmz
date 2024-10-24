# Technical Task

In this test task you will build a custom widget for an Ecwid online store that can be controlled from a separate
settings page. Also, the settings page should contain a block to select and export products to a CSV file.

## Part 1: Custom widget

Develop an application for the Ecwid online store that shows N of the recently updated products.

Embed an Ecwid online store into a regular website. A custom “Recently updated products” block is shown when visiting
the cart page of the store: [https://ecwid.d.pr/i/o3nTlW](https://ecwid.d.pr/i/o3nTlW)

Then, Add the functionality to enable/disable the “Recently updated products” block to the settings page of your app.

### Requirements

- The recently updated products list appears on the cart page below the checkout section.
  Example: https://ecwid.d.pr/i/o3nTlW
- The design of the custom products list replicates the default Ecwid products list styles
- Customers can add products to the cart right from the list (add “Buy now” or similar button)
- Customers can open the product details page by clicking on the product name or image in the product list
- Customers can change the number of recently updated products shown in the list.
- The store owner should know what products in the order were added from the “Recently updated products” block. (Hint:
  Use order extra fields)

## Part 2: Settings page and export

Create a separate settings page for your custom widget where:

- Store owner can enable/disable the custom widget
- Store owner can set the number of recently updated products to show in the custom widget
- Store owner can export the list of products to a CSV file

A store owner can visit a specific website page (provide a link to it) where they can see all store products and export
all or some of them into a readable CSV/XLSX file.

### Requirements

- The settings page for your application is based
  on [Ecwid CSS Framework](https://developers.ecwid.com/ecwid-css-framework/) components.
- The setting page includes feature description (what your application does) with on/off toggle to manage custom widget
  visibility
- Export products section should consist of a table-like list of store products with checkboxes and “Export selected
  products” button
- Store owner can choose the products for the export using checkboxes
- Products list should be exported in CSV format
- Export and CSV download starts automatically when a store owner clicks the “Export selected products” button.

## Part 3: Docker compose

The project must be buildable on any machine using Docker Compose. The project should be easy to understand and work
with.

### Requirements

- The project has a Git repo-like structure with a proper README.md file
- The whole project can be launched within a single entry point for building and running the app (use Docker compose).

## Data

Store data must be accessed using [Ecwid REST API](https://api-docs.ecwid.com/reference/rest-api)

The easiest way is to use the demo store. Here's the access info:

- StoreID: `101560752`
- Token: `public_eaBDuVmrse1hKZun4qaPF3LewugrnEgq`

## Useful links

- https://support.ecwid.com/hc/en-us/articles/115004678945-Ecwid-for-any-website
- https://api-docs.ecwid.com/reference/customize-behaviour
- https://api-docs.ecwid.com/reference/get-started-with-rest-api

## Technologies

- Typescript
- Vue.js 3 (composition API)
- HTML/CSS
- Node.js
- Docker (compose)
