# Hyvä Shipping Progress Bar

**Hyvä Shipping Progress Bar is a part of MageINIC Shipping Progress Bar extension that adds Hyvä features.** This extension extends Shipping Progress Bar definitions.

## 1. How to install

Run the following command in Magento 2 root folder:

```
composer require mageinic/hyva-shipping-progress-bar

php bin/magento maintenance:enable
php bin/magento setup:upgrade
php bin/magento setup:di:compile
php bin/magento setup:static-content:deploy
php bin/magento maintenance:disable
php bin/magento cache:flush
```

**Note:**
Magento 2 Product FAQ requires installing [Shipping Progress Bar](https://github.com/mageinic/shipping-progress-bar) in your Magento installation.

**Or Install via composer [Recommend]**
```
composer require mageinic/shipping-progress-bar
```

## 2. Get Support

- Feel free to [contact us](https://www.mageinic.com/contact.html) if you have any further questions.
- Like this project, Give us a **Star**
