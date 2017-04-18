## Magento 2 Chinese Language Pack

Today I will provide you another helpful document - **Magento 2 Chinese Simplified Language Pack**. With this knowledge base article, you can change the Magento 2 default language to Chinese Simplified Language with only two simple steps. After finishing, all labels on your storefront will be auto-converted to Chinese Simplified quickly.

Read more [Magento 2 Chinese Language Pack](https://www.mageplaza.com/magento-2-chinese-language-pack.html)


## Overview

- Download & Contribute
- Install Chinese Language Pack
- How to Install Chinese Language Pack

## Download & Contribute to Chinese Language Pack

Below are two active buttons which are required operations before installing the language package. Let's hit them to download and contribute Magento 2 Chinese Language Pack immediately!

**Download packages**:

- [Download .zip](https://github.com/mageplaza/magento-2-chinese-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-chinese-language-pack/tarball/master)
- [Copy & paste package](https://crowdin.com/project/magento-2/zh-CN.zip)


Find other [language packs here]({https://www.mageplaza.com/kb/magento-2-language-pack/)

## How to Install Chinese Language Pack

There are 3 different methods to install this language pack.

### #1. Composer method
Install the Chinese language pack via composer is never easier.

**Install Chinese pack**:

```
composer require mageplaza/magento-2-chinese-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy zh_CN
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```


**Update  Chinese pack**:

```
composer update mageplaza/magento-2-chinese-language-pack:dev-master
php bin/magento cache:clean
php bin/magento setup:static-content:deploy zh_CN
php bin/magento indexer:reindex
php bin/magento cache:clean
php bin/magento cache:flush

```

#### Authentication required (Optional)

[Authentication required](https://i.imgur.com/dmryiPk.png)

If you have not added this authentication, you can follow [this guide](http://devdocs.magento.com/guides/v2.0/install-gde/prereq/connect-auth.html)


### #2. Copy & Paste method

This method suitable for non-technical people such as merchants. Just download the package then flush cache.

**Overview**

- Step 1: Download the Chinese language pack
- Step 2: Unzip Chinese pack
- Step 3: Flush Magento 2 Cache

#### Step 1 : Download the Chinese language pack

You can download the language pack from above link

#### Step 2: Unzip Chinese pack

Unzip the Chinese language pack to Magento 2 root folder. In this guide, we extract to `/var/www/html/`
Your Magento 2 root folder can be: `/home/account_name/yourstore.com/public_html/`

```
unzip fr.zip /var/www/html/
```

You also can unzip locally and upload them to Magento 2 root folder.

#### Step 3: Flush Magento 2 Cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


### #3. Download and install manually

To download and install Chinese pack manually, you have to access to your server via FTP or SFTP.

#### Step 1: Download the package

- [Download .zip](https://github.com/mageplaza/magento-2-chinese-language-pack/archive/master.zip)
- [Download .tar.gz](https://github.com/mageplaza/magento-2-chinese-language-pack/tarball/master)

#### Step 1: Unzip and upload

Unzip the compressed file and upload file `zh_CN.zip` into `app/i18n/mageplaza/zh_CN/zh_CN.csv`

#### Step 2: Flush cache

Follow this guide to [Flush Cache on your Magento 2 store](https://www.mageplaza.com/kb/how-flush-enable-disable-cache.html)


## How to active language pack

Now time to active the language pack for your Magento 2 store. From Magento 2 admin panel, navigate to `Stores > Configuration > General > Locale Options`
![{{Magento 2 Chinese language pack}}](https://i.imgur.com/aPSUA0l.png)


## Translation process of Chinese Language Pack
![process](http://progressed.io/bar/80)

Contribute to this language at https://crowdin.com/project/magento-2/zh-CN

## Supported Magento versions

- Magento v2.0.0
- Magento v2.0.1
- Magento v2.0.2
- Magento v2.0.3
- Magento v2.0.4
- Magento v2.0.5
- Magento v2.0.6
- Magento v2.0.7
- Magento v2.0.8
- Magento v2.0.9
- Magento v2.0.10
- Magento v2.0.11
- Magento v2.0.12
- Magento v2.0.13
- Magento v2.1.0
- Magento v2.1.1
- Magento v2.1.2
- Magento v2.1.3
- Magento v2.1.4
- Magento v2.1.5
- Magento v2.1.6



## Language package authors

- [Magento official translations project for Magento 2](https://crowdin.com/project/magento-2)
- Language packages built by [Mageplaza team](https://www.mageplaza.com/)


References:
- https://www.mageplaza.com/magento-2-chinese-language-pack.html
- https://www.mageplaza.com/kb/magento-2-language-pack/