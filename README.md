# CJ Affiliate Shopify Integration

This repository contains a custom snippet for integrating CJ Affiliate with Shopify.

## Prerequisites

You should have a valid CJ Affiliate account and know your `YOUR_TYPE` and `YOUR_CID` details.

## Setup Instructions

Follow these steps to integrate CJ Affiliate into your Shopify store:

1. Download the [`cj-affiliate.liquid`](/Snippets/cj-affiliate.liquid) snippet from this repository and place it in your Shopify store's snippets directory. If you're unsure about how to edit your Shopify theme to add this file, refer to the official Shopify guide [here](https://help.shopify.com/en/manual/online-store/themes/theme-code#edit-your-theme-code). 

    Please note that you will need to replace the placeholders `YOUR_TYPE` and `YOUR_CID` within the `cj-affiliate.liquid` file with your own CJ Affiliate details.

2. Next, insert the following code snippet just before the `</body>` tag in your `checkout.liquid` file:

    ```html
    <body>
      ...
      {%- render 'cj-affiliate' -%}
    </body>
    ```
By doing this, you're instructing Shopify to render the CJ Affiliate snippet when the checkout page is loaded.

And voila! You've successfully added CJ Affiliate to your Shopify store. If you encounter any issues during setup, please create an issue in this repository and we will do our best to assist you.
