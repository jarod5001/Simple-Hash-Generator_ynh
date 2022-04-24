<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Simple-Hash-Generator for YunoHost

[![Integration level](https://dash.yunohost.org/integration/simple-hash-generator.svg)](https://dash.yunohost.org/appci/app/simple-hash-generator) ![](https://ci-apps.yunohost.org/ci/badges/simple-hash-generator.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/simple-hash-generator.maintain.svg)  
[![Install Simple-Hash-Generator with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=simple-hash-generator)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Simple-Hash-Generator quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A simple hash generator utilizing a collection of popular and useful hash functions


**Shipped version:** 1.0~ynh1

**Demo:** https://prizz.github.io/Simple-Hash-Generator/

## Screenshots

![](./doc/screenshots/example.jpg)

## Disclaimers / important information

# Disclaimer

All hashing is done directly in the browser. Your data is not sent to any server, ever. If you are skeptical, which I respect, I recommend [downloading the latest release here](https://github.com/pRizz/Simple-Hash-Generator/releases), turning off your internet, unzip the release, open index.html, check out the network debugger, and see that hashing still works. Or if you are a developer, you can audit the [source code here](https://github.com/pRizz/Simple-Hash-Generator).

# About the Author

This project was originally created by Peter Ryszkiewicz ([pRizz@GitHub](https://github.com/pRizz)), software engineer in Chicago, IL.

# About the Project

This project is hosted on GitHub at https://github.com/pRizz/Simple-Hash-Generator under the MIT license.

## Documentation and resources

* Official app website: https://prizz.github.io/Simple-Hash-Generator/
* Upstream app code repository: https://github.com/pRizz/Simple-Hash-Generator
* YunoHost documentation for this app: https://yunohost.org/app_simple-hash-generator
* Report a bug: https://github.com/YunoHost-Apps/simple-hash-generator_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/simple-hash-generator_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/simple-hash-generator_ynh/tree/testing --debug
or
sudo yunohost app upgrade simple-hash-generator -u https://github.com/YunoHost-Apps/simple-hash-generator_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps