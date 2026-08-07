# module-meta-hyva-beta
Commerce 365 for Magento (Hyva Support) - Magento 2 Extension - Beta Meta Data Module

This is the **beta** channel of the Hyvä metapackage. It pins the pre-release
(`2.1.0-beta`) versions of the Commerce 365 modules that contain the store-view
based configuration feature, so it can be installed side-by-side with the stable
line without affecting customers who use `nvision/commerce365-hyva`.

In order to install the beta package please run the following command
```
composer require nvision/commerce365-hyva-beta:2.1.0-beta
```

> Your project's root `composer.json` must allow pre-release packages, e.g.
> ```
> "minimum-stability": "dev",
> "prefer-stable": true
> ```
> Only the modules pinned to `2.1.0-beta` are installed as pre-release; every
> other dependency stays on its latest stable version.

For more information about Commerce 365 for Magento see:
https://n.vision/products/commerce-365-for-magento/
