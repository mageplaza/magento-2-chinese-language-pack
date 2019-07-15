# How to contribute Chinese Language pack

In this tutorial, I will show you how to contribute Chinese language pack

## Step 1: Download 

First of all, you should fork the repo. In the top-right corner of the page, click **Fork**.
![fork](https://help.github.com/assets/images/help/repository/fork_button.jpg)


## Step 2: Update github_contributions.csv

Let's me explain the workflow:

- It will automatically pull translated strings from [Crowdin](https://crowdin.com/project/magento-2) daily.

- [github_contributions.csv](https://github.com/mageplaza/magento-2-chinese-language-pack/blob/master/github_contributions.csv) has been contributed by Mageplaza and Magento community.

- We will merge `github_contributions.csv` with [zh_Hans_CN.csv](https://github.com/mageplaza/magento-2-chinese-language-pack/blob/master/zh_Hans_CN.csv). Your Magento 2 store will use this csv file.

So, you should contribute to [github_contributions.csv](https://github.com/mageplaza/magento-2-chinese-language-pack/blob/master/github_contributions.csv) file.

### How to edit file github_contributions.csv

The `github_contributions.csv` is saparated **line by line**, see:

```
"Create Order","Crear pedido",module,Magento_AdvancedCheckout
```

- "Create Order": Original string
- "Crear pedido": Translated string
- module: declare module syntax
- Magento_AdvancedCheckout: module scope (only translate in this module)


Fom the begining, `github_contributions.csv` is empty, you guys should add more translations into it.

#### Suggestions
- You can copy any part of `zh_Hans_CN.csv` and paste to `github_contributions.csv` then translate it.
- Please do not copy all lines in `zh_Hans_CN.csv`, we will not approve it in this case.

## Step 3: Contribute

- Now time to contribute, **commit your work** to this repo.
- After committing, it will ask you to **create a pull request**, so please create a pull request, we will check and approve it.


You can [install this language package via composer](https://github.com/mageplaza/magento-2-chinese-language-pack#-method-1-composer-method-recommend) and other people can install / contribute this language pack.

[Contact us](https://www.mageplaza.com/contact.html) if we miss your pull request(s).

Happy translating!


