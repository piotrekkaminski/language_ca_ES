# Catalan (català) Magento2 Language Pack (ca_ES)
This is a Language Pack generated from the [official Magento2 translations project](https://crowdin.com/project/magento-2) at [Crowdin](https://crowdin.com).
The Catalan (català) translations used can be found [here](https://crowdin.com/project/magento-2/ca).

# Version & progress
This translation is generated from the branch [Head](https://crowdin.com/project/magento-2/ca#/Head) at Crowdin and based on the Magento Head sourcefiles.
There have been  12595 strings translated of the 12595 strings in the Magento source.

Translation progress:![Progress](http://progressed.io/bar/100)

# Instalation
## Via composer
To install this translation package with composer you need access to the command line of your server and you need to have [Composer](https://getcomposer.org).
```
cd <your magento path>
composer require magento2translations/language_ca_es:dev-master
php bin/magento cache:clean
```
## Manually
To install this language package manually you need access to your server file system.
* Download the zip file [here](https://github.com/Magento2Translations/language_ca_es/archive/master.zip).
* Upload the contents to `<your magento path>/app/i18n/magento2translations/language_ca_es`.
* The composer files should then be located like this `<your magento path>/app/i18n/magento2translations/ca_ES/ca_ES.csv`.
* Go to your Magento admin panel and clear the caches.

#Usage
To use this language pack login to your admin panel and goto `Stores -> Configuration -> General > General -> Locale options` and set the '*locale*' option as '*Catalan (Spain)*'

# Contribute
To help move the '*Catalan (català) Magento2 Language Pack (ca_ES)*' forward please goto [this](https://crowdin.com/project/magento-2/ca) crowdin page and translate the untranslated string or propose better translations.

# Authors
The translations are done by the [official Magento2 translations project](https://crowdin.com/project/magento-2).

Composer package generation originally written by [Wijzijn.Guru](http://www.wijzijn.guru/).
