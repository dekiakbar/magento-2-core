# Mage2 Module Deki Core
  ``deki/module-core``

## Main Functionalities
magento 2 core module

### Type 1: Zip file
 - Unzip the zip file in `app/code/Deki`
 - Enable the module by running `php bin/magento module:enable Deki_Core`
 - Apply database updates by running `php bin/magento setup:upgrade`
 - Flush the cache by running `php bin/magento cache:flush`

### Type 2: Composer
 - Install the module composer by running `composer require deki/module-core`
 - enable the module by running `php bin/magento module:enable Deki_Core`
 - apply database updates by running `php bin/magento setup:upgrade`
 - Flush the cache by running `php bin/magento cache:flush`