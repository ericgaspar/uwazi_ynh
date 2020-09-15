# Uwazi for YunoHost

[![Integration level](https://dash.yunohost.org/integration/uwazi.svg)](https://dash.yunohost.org/appci/app/uwazi) ![](https://ci-apps.yunohost.org/ci/badges/uwazi.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/uwazi.maintain.svg)  
[![Install Uwazi with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=uwazi)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Uwazi quickly and simply on a YunoHost server.  
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview


**Shipped version:** 1.8.0

## Screenshots

![]()

## Demo

* [Official demo](https://demo.uwazi.io/)

## Configuration

## Documentation

 * Official documentation: 
 * YunoHost documentation: https://yunohost.org/#/app_uwazi

## YunoHost specific features

#### Multi-user support

* Is LDAP supported? **Yes**
* Can the app be used by multiple users? **Yes**

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/uwazi%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/uwazi/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/uwazi%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/uwazi/)

## Links

 * Report a bug: https://github.com/YunoHost-Apps/uwazi_ynh/issues
 * Upstream app repository: https://github.com/huridocs/uwazi
 * YunoHost website: https://yunohost.org/

---

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/uwazi_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/uwazi_ynh/tree/testing --debug
or
sudo yunohost app upgrade uwazi -u https://github.com/YunoHost-Apps/uwazi_ynh/tree/testing --debug
```
