<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Huginn for YunoHost

[![Integration level](https://dash.yunohost.org/integration/huginn.svg)](https://dash.yunohost.org/appci/app/huginn) ![Working status](https://ci-apps.yunohost.org/ci/badges/huginn.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/huginn.maintain.svg)

[![Install Huginn with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=huginn)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Huginn quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Huginn is a system for building agents that perform automated tasks for you online. They can read the web, watch for events, and take actions on your behalf. Huginn's Agents create and consume events, propagating them along a directed graph. Think of it as a hackable version of IFTTT or Zapier on your own server. You always know who has your data. You do.

**Shipped version:** 2022.03.24~ynh3

## Screenshots

![Screenshot of Huginn](./doc/screenshots/your-agents.png)

## Documentation and resources

* Upstream app code repository: <https://github.com/huginn/huginn>
* YunoHost documentation for this app: <https://yunohost.org/app_huginn>
* Report a bug: <https://github.com/YunoHost-Apps/huginn_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/huginn_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
or
sudo yunohost app upgrade huginn -u https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
