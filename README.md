# plugin_customapi
Cartridge Demo as PoC for Salesforce Commerce APIs

This is a Demo Cartridge based on the Official Salesforce Commerce Documentation, the main idea was to test in an ODS environment the Custom API Extensibility.

Official Doc.: https://developer.salesforce.com/docs/commerce/commerce-api/guide/custom-apis.html

Request Sample: (fixed the official one which has a minor bug)

GET https://my-shortcode.api.commercecloud.salesforce.com/custom/loyalty-info/v1/organizations/my-org-id/customers?c_customer_id=customer1&siteId=MySite&locale=en-US

P.S.: Do not forget to add the new api scope (c_loyaltyInfo_r) to the assigned ClientId (SLAs Admin)
