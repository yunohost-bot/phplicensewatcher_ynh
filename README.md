<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# PHPLicenseWatcher for YunoHost

[![Integration level](https://dash.yunohost.org/integration/phplicensewatcher.svg)](https://dash.yunohost.org/appci/app/phplicensewatcher) ![Working status](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/phplicensewatcher.maintain.svg)

[![Install PHPLicenseWatcher with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phplicensewatcher)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install PHPLicenseWatcher quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

phpLicenseWatcher is a simple Web frontend to the FlexLM lmstat and lmdiag commands that gives information about the status of FlexLM servers. You can also get information about features and number of licenses available on a particular server.

### Features

- Shows the health of a license server or a group of them
- Check which licenses are being used and who is currently using them
- Get a listing of licenses, their expiration days and number of days to expiration
- E-mail alert of licenses that will expire within certain time period ie. within next 10 days.
- Monitors server utilization
- Provides usage charts


**Shipped version:** 2.210916~ynh2

## Screenshots

![Screenshot of PHPLicenseWatcher](./doc/screenshots/screenshot1.png)

## Documentation and resources

* Official app website: <http://phplicensewatch.sourceforge.net>
* Official admin documentation: <https://phplicensewatch.sourceforge.io/index.html#Documentation>
* Upstream app code repository: <https://github.com/rpi-dotcio/phpLicenseWatcher>
* YunoHost Store: <https://apps.yunohost.org/app/phplicensewatcher>
* Report a bug: <https://github.com/YunoHost-Apps/phplicensewatcher_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
or
sudo yunohost app upgrade phplicensewatcher -u https://github.com/YunoHost-Apps/phplicensewatcher_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
