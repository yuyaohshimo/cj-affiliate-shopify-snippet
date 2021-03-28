# cj-affiliate-shopify-snippet
Custom snippet for Shopify + CJ Affiliate

## Getting Started

1. Place the [`cj-affiliate.liquid`](/Snippets/cj-affiliate.liquid) on your snippets folder. You can see the instruction how to edit your theme on Shopify dashboard [here](https://help.shopify.com/en/manual/online-store/themes/theme-code#edit-your-theme-code). Your should replace `YOUR_TYPE` and `YOUR_CID` with yours.

2. Place the following code before `</body>` tag in `checkout.liquid`.

```liquid
{%- render 'cj-affiliate' -%}
```
