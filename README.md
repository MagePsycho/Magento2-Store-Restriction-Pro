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
**Version 1.0.0 (2017-06-12)**
    
* Initial Release.
