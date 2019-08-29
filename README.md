## Overview:
Magento 2 Store Restriction Pro provides you the complete functionality for restricting your store in many ways (disabling registration, restricting access to only logged-in customer of certain groups while allowing guest access to certain pages)

![Magento 2 Store Restriction Backend Demo](http://g.recordit.co/SR1aTD7d0l.gif)

## Features:
### 1. General

* Upgrade Proof Module(purely event-observer based, no any preferences/rewrites).
* Compatible with Magento CE 2.X & EE 2.X.
* Option to enable/disable the functionality as per store.
* Compatible with Magento 2 Custom Redirect Pro Extension.
* Essential Module for B2B/B2C, private sale, member only, invite only stores.

### 2. Customer Registration
* Provides option to disable the customer registration (with an optional custom message).
* Includes Magento 2 Customer Group Selector / Switcher extension for FREE, which allows customer group selection/automatic group switching from the registration page.

### 3. Store Restriction

Provides Store Restriction of two types
1. Non-Restricted
    * The store is accessible for all the users.
1. Restricted (Only configured pages accessible)
    * The store is restricted, requires login to be accessible.
    * Provides option to select which customer group(s) can access the restricted store.
    * Provides option to redirect the not allowed user to the custom page(Login, CMS or any custom page) with configured message.
    * Provides option to allow certain CMS, Category, Product & custom module pages for guest users.
1. Accessible (Only configured pages/sections restricted) - *coming soon*
    

## Installation
1. Download the extension .zip file and extract the files.
1. Copy the extension files from src/ folder to the {magento2-root-dir}/
1. Run the following series of command from SSH console of your server:
`php bin/magento module:enable MagePsycho_StoreRestrictionPro MagePsycho_GroupSwitcherPro --clear-static-content`
`php bin/magento setup:upgrade`
1. Flush the store cache
`php bin/magento cache:flush`
1. Go to Admin > Stores > Configuration > MagePsycho > Store Restriction Pro > Configure your settings here...

## Live Demo:
* [View Frontend Demo](http://m2-store-restriction-pro.mage-expo.com/customer/account/create/)  
* [View Backend Demo](http://m2-store-restriction-pro.mage-expo.com/admin_m2demo)

## Changelog
**Version 1.0.2 (2019-05-23)**
- Fixed redirection issue from homepage
- Fixed registration disabled case
- Compatibility tested with Magento v2.3.x

**Version 1.0.0 (2017-06-12)**
    
- Initial Release.

### People also search:

- magento 2 restriction
- magento 2 restriction module
- magento 2 restriction extension
- magento 2 restriction extension free
- magento 2 customer restriction
- magento 2 customer group restriction
- magento 2 restrict by customer group
- magento 2 cms restriction
- magento 2 page restriction
- magento 2 product restriction
- magento 2 category restriction
- magento 2 restrict category access
- magento 2 website restriction
- magento 2 cart restriction
- magento 2 shipping restriction
- magento 2 shipment restriction
- magento 2 payment restriction
- magento 2 restrict shipping method
- magento 2 restrict payment method
- magento 2 restrict cash on delivery
- magento 2 restrict zip codes
- magento 2 require customer approval
- magento 2 customer activation
- magento 2 b2c extension
- magento 2 b2b extension
- magento 2 b2b extension free
- magento 2 wholesale extension
- magento 2 call for price
- magento 2 hide price
- magento 2 hide product price
- magento 2 hide product price extension
- magento 2 hide product price extension free
- magento 2 hide add to cart
- magento 2 hide add to cart button
- magento 2 disable add to cart
- magento 2 disable add to cart button
- magento 2 customer group select
- magento 2 customer group switch
- magento 2 restricted access
- magento 2 login only store


### Other FREE Magento 2 Extensions on GitHub

- [Custom Shipping Module for Magento 2](https://github.com/MagePsycho/magento2-custom-shipping)
- [Magento 2 Easy Template Path Hints](https://github.com/MagePsycho/magento2-easy-template-path-hints)
- [Magento 2 Storefront Links Manager](https://github.com/MagePsycho/magento2-storefront-links-manager)
- [Magento 2 Custom Customer Address Attribute](https://github.com/MagePsycho/magento2-custom-customer-address-attribute)
- [Magento 2 Starter Theme](https://github.com/MagePsycho/magento2-starter-theme)
- [Magento 2 Bash Script Installer](https://github.com/MagePsycho/magento2-installer-bash-script)
- [Bash Script: Backup Magento2 Code + Database](https://github.com/MagePsycho/magento2-db-code-backup-bash-script)