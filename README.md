<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# phpMyAdmin for YunoHost

[![Integration level](https://dash.yunohost.org/integration/phpmyadmin.svg)](https://dash.yunohost.org/appci/app/phpmyadmin) ![](https://ci-apps.yunohost.org/ci/badges/phpmyadmin.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/phpmyadmin.maintain.svg)  
[![Install phpMyAdmin with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpmyadmin)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install phpMyAdmin quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

Manage MySQL databases over the web

**Shipped version:** 5.2.0~ynh1

**Demo:** https://demo.phpmyadmin.net/master-config

## Screenshots

![](./doc/screenshots/screenshot.png)

## Disclaimers / important information

## Overview

phpMyAdmin is a free software tool written in PHP, intended to handle the administration of MySQL over the Web. phpMyAdmin supports a wide range of operations on MySQL and MariaDB. Frequently used operations (managing databases, tables, columns, relations, indexes, users, permissions, etc) can be performed via the user interface, while you still have the ability to directly execute any SQL statement.
## Documentation and resources

* Official app website: http://www.phpmyadmin.net
* Official admin documentation: https://www.phpmyadmin.net/docs/
* Upstream app code repository: https://github.com/phpmyadmin/phpmyadmin
* YunoHost documentation for this app: https://yunohost.org/app_phpmyadmin
* Report a bug: https://github.com/YunoHost-Apps/phpmyadmin_ynh/issues

## Developer info

Please send your pull request to the [testing branch](https://github.com/7357-2022/hw2k_phpmyadmin_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/7357-2022/hw2k_phpmyadmin_ynh/tree/testing --debug
or
sudo yunohost app upgrade phpmyadmin -u https://github.com/7357-2022/hw2k_phpmyadmin_ynh/tree/testing --debug
```

**More info regarding app packaging:** https://yunohost.org/packaging_apps
