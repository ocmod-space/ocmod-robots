# Robots

## Description
**Robots** is an OpenCart extension that adds the tag `<meta name="robots" content="noindex,follow">` on some pages to improve store SEO.
Based on the [Robots noindex](https://opencartforum.com/en/files/file/2839-robots-noindex/) extension.
Compatible with OpenCart 2.x-3.x versions.

## Features
* Adding <meta name="robots" content="noindex,follow">` into headers of pages with the following routes:
    - `account/login`, `account/register`, `account/forgotten`, `checkout/cart`, `checkout/checkout`, `information/information`, `product/compare`, `product/search`.
    - `product/category`, `product/manufacturer`,`product/special` only if they contain `sort`, `page`, `limit` GET-requests.
* Does not modify system files (OCMOD).

## Live demo
* [Demo Store](https://demo.ocmod.space/a/admin/index.php?route=extension/module/robots).

## License
* Licensed under the [MIT License](../LICENSE.txt).
