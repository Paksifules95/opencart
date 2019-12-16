<p align="center">
  <br>
  <a href="https://vuefront.com">
    <img src="https://raw.githubusercontent.com/vuefront/vuefront-docs/master/.vuepress/public/img/github/vuefront-opencart.jpg" width="400"/>
  </a>
</p>
<h1 align="center">VueFront</h1>
<h3 align="center">CMS Connect App for OpenCart 2.x-3.x
</h3>

<p align="center">
  <a href="https://github.com/vuefront/vuefront"><img src="https://img.shields.io/badge/price-FREE-0098f7.svg" alt="Version"></a>
  <a href="https://discord.gg/C9vcTCQ"><img src="https://img.shields.io/badge/chat-on%20discord-7289da.svg" alt="Chat"></a>
</p>

<p align="center">
Show your :heart: - give us a :star: <br/> 
Help us grow this project to be the best it can be!
  </p>


__VueFront__ is a <a href="//vuejs.org">VueJS powered</a> CMS agnostic SPA & PWA frontend for your old-fashioned Blog and E-commerce site. 

__OpenCart__ - Open-source eCommerce platform built with MVC pattern.

__CMS Connect App__ - adds the connection between the OpenCart CMS and VueFront Web App via a GraphQL API.

## DEMO

[VueFront on OpenCart](https://opencart.vuefront.com/)

![VueFront CMS Connect App](http://joxi.net/krDlvPdfKO5P9r.jpg)

## OpenCart Versions
This repo stores the codebase for the CMS Connect App for OpenCart. Because of OpenCart's versioning, the branches are structured as follows 

| Repo Branch | OpenCart Versions  |
|--------|-------------|
| [master](https://github.com/vuefront/opencart) | 2.x-3.x     |
| [1.5x](https://github.com/vuefront/opencart/tree/1.5x)   | 1.5.x       |

### OpenCart Blog 
Since OpenCart does not have a built-in Blog, we use the [Free Blog Module](https://github.com/Dreamvention/2_d_blog_module) by Dreamvention for version 2.x-3.x

## How to install?
Php version required >= 5.5, <= 7.2 (this limitation will be removed in the future)

### Quick Install
1. [Download](https://github.com/vuefront/opencart/releases) the **compiled** Extensions from the latest releases. 
2. Upload via OpenCart Admin -> Extension Installer
3. Go to Extensions -> Modules -> VueFront and click install
4. Click edit to view copy the CMS Connect URL

You will need the CMS Connect URL to complete the [VueFront Web App installation](https://vuefront.com/guide/setup.html)

### Advanced Install
The official compiled version of the CMS Connect APP includes other supporting extensions such as d_opencart_patch and d_twig_manager. 

You can download the source code from the master branch directly and upload via ftp to your root folder. When activating the module, you should have the following extensions preinstalled: d_opencart_patch, d_twig_manager, d_twig (only for 2.x)

You can also install the d_blog_module to add blog features to VueFront. 

### Install via Shopunity
If you have shopunity module installed, you can use that for a super quick installation:
1. go to OpenCart admin -> shopunity -> marketplace tab
2. search for VueFront
3. Click install.

You can also install the d_blog_module via Shopunity as well. 

## Support
For support please contact us at [Discord](https://discord.gg/C9vcTCQ)

## Submit an issue
For submitting an issue, please create one in the [issues tab](https://github.com/vuefront/vuefront/issues). Remember to provide a detailed explanation of your case and a way to reproduce it. 

Enjoy!
