# cj-affiliate-shopify-snippet
Custom snippet for Shopify + CJ Affiliate

## Getting Started

1. Place the [`cj-affiliate.liquid`](/Snippets/cj-affiliate.liquid) on your snippets folder. Your should replace `YOUR_TYPE` and `YOUR_CID` with yours.

2. Place the following code before `</body>` tag in `checkout.liquid`.

```liquid
{%- render 'cj-affiliate' -%}
```
