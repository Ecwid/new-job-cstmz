# Writing Task

When working as a developer in our Customizations department, you will often face the need to write technical
descriptions for new features or integrations requested by Project Managers and clients. This description includes
information on how the feature would
communicate with an Ecwid store to provide the desired functionality.

In this test task, you will need to write a technical description on how to develop a "Discount vouchers" feature. It
would
allow customers to receive a discount for future
purchases by placing an order that fits certain criteria. Online storefront should have a promo area where customers can
see the promo and learn more about it.

### Feature requirements

**Basic workflow**

- Customer sees promo information on the store
- Customer places an order
- Conditions for the voucher are checked
- If the conditions are met, a voucher is sent to the customer's email
- The voucher can be used for the next purchase at checkout

**Voucher limits**

- The voucher is a unique code that can be used only once
- The voucher is sent to new customers only
- The voucher is valid for a certain period of time
- The voucher discount can be either applied as a discount coupon or a custom discount

**Feature settings**

- Store admin should be able to enable/disable the feature in its settings
- Store admin should be able to manage the validity period for newly created vouchers
- Store admin should be able to see the list of all vouchers sent and their status
- The email template with new vouchers should be editable from the feature settings

## Writing Task Requirements

- The description is written in English or Russian
- The description must be based on the [Ecwid API Documentation](https://api-docs.ecwid.com/reference/)
- The description should have a clear structure so it's easy to navigate through it, i.e.: Storefront, Settings page,
  Emails, etc.
- The description should cover surface-level technical implementation details, like API features you plan to use and how
  you plan to use them
- The description should include an approximate time a developer would spend on each part of the implementation
- The description should cover edge cases and potential issues that might arise during the implementation
