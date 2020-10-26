## EasyiiCMS
Control panel and tools based on php framework Yii2. Easy cms for easy websites.

#### Requirements
The main requirement is PHP >= 5.4, Imagick extension. Other requirements you can see after download.

Direcotry Structure
```
app/                main application folder
    assets/         contains assets definition
    config/         contains application configurations
    commands/       contains Console controller classes
    controllers/    contains Web controller classes
    media/          contains css, images and js scripts
    views/          contains application configurations
assets/             contains published files
runtime/            contains files generated during runtime
uploads/            contains all uploaded files
vendor/             contains dependent 3rd-party packages
```

DOWNLOAD VIA COMPOSER
Installation of EasyiiCMS is very similar to Yii framework 2.0.

This is the preferred way of installing EasyiiCMS. If you do not have Composer yet, you may install it by following the instructions here.

After installing Composer, run the following command to install the Composer Asset Plugin:
php composer.phar global require "fxp/composer-asset-plugin:1.0.0"

To install EasyiiCMS shop application(includes examples of all modules), run the command below
php composer.phar create-project fighcell/easyii-shop shop dev-master

To install EasyiiCMS blank application, run the command below
php composer.phar create-project fighcell/easyii-start start dev-master


Open app/config/web.php and insert a secret random string in the cookieValidationKey parameter (line: 15).
You can generate random string on random.org.
Set the write permissions 0777 on assets, runtime and uploads folders.

INSTALLATION
Configure database connection at app/config/db.php
Set your language at app/config/web.php
Open in browser your website url. You will see EasyiiCMS Welcome page
Check the requirements.
Fill simple form and complete installation.


#### You can find full information in links bellow ####
* [Homepage](http://easyiicms.com)
* [Installation](http://easyiicms.com/docs/install)
* [Demo](http://demo.easyiicms.com/)

#### Contacts ####

Feel free to email me on noumohope@gmail.com
If you would like updated version please email me @ ah.faisal@gmail.com
