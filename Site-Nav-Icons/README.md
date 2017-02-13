# Shopify Navigation Menu Icons
---
This liquid file will allow the use of "i" span element tags to denote icons in Shopify navigation menus.
![](https://raw.githubusercontent.com/dabit-industries/Shopify-Template-Snippets/master/Site-Nav-Icons/01.jpg)

This is a quick mod of the standard Shopify theme's site-nav liquid file, and is not guaranteed to work with all themes.

##Usage
---
This example is using FontAwesome

![](https://raw.githubusercontent.com/dabit-industries/Shopify-Template-Snippets/master/Site-Nav-Icons/02.jpg)

In your Shopify Admin page, navigate to Online Store / Navigation and edit or make a new menu.
Use the following format, and format it to your liking
```
<i>fa fa-github</i>GitHub
```

##Installation
---
- Place 'site-nav-icons.liquid' in your snippets folder
- In Sections/header.liquid
  - find all
    - include 'site-nav'
  - replace with
    - include 'site-nav-icons'

##Issues
---
- Due to the way Shopify links drop-down menus, you will need a drop-down menu with the same text.
- You also cannot use ">" and "<" in your actual menu text, currently.
- Also, you can probably remove the | escape from the link.title liquid code and put in your own HTML, potentially...

