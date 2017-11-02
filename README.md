# English (English) Magento2 Language Pack (en_ID)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The English (English) translations used can be found [here](https://crowdin.com/project/magento-2/en).
This translation is usefull for people living in the Indonesia (Indonesia).

For our other language packs look at the [Magento2Translations](http://magento2translations.github.io/) page.

# Version & progress
This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/en#/Head) at Crowdin and based on the Magento 2.2.0 sourcefiles.
There have been  1053 strings translated of the 8763 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/12)

# Installation
**Please select the git branch appropriate for your magento version from this repo.**
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_en_id:dev-Head
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_en_id/archive/Head.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_en_id`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/en_ID/en_ID.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*English (Indonesia)*'

# Contribute
To help push the '*English (English) Magento2 Language Pack (en_ID)*' forward please goto [this](https://crowdin.com/project/magento-2/en) crowdin page and translate the lines.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Code generation is sponsored by [Wijzijn.Guru](http://www.wijzijn.guru/).