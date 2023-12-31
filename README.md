<!--
N.B.: This README was automatically generated by https://github.com/YunoHost/apps/tree/master/tools/README-generator
It shall NOT be edited by hand.
-->

# Restic with S3 for YunoHost

[![Integration level](https://dash.yunohost.org/integration/restic-s3.svg)](https://dash.yunohost.org/appci/app/restic-s3) ![Working status](https://ci-apps.yunohost.org/ci/badges/restic-s3.status.svg) ![Maintenance status](https://ci-apps.yunohost.org/ci/badges/restic-s3.maintain.svg)

[![Install Restic with S3 with YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=restic-s3)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allows you to install Restic with S3 quickly and simply on a YunoHost server.
If you don't have YunoHost, please consult [the guide](https://yunohost.org/#/install) to learn how to install it.*

## Overview

A [Restic](https://restic.net/) package for YunoHost, using a S3 bucket to store the backup ! (heavily inspired by [the Restic package](https://github.com/YunoHost-Apps/restic_ynh), itself heavily inspired by [the Borg package](https://github.com/YunoHost-Apps/borg_ynh)).

Restic is a backup tool that can make local and remote backups.

This package uses restic to make backups to a S3 bucket.

The package does not handle local backups yet but you can work around that by using a local S3-compatible server as target, like [Garage](https://github.com/YunoHost-Apps/garage_ynh) or [Minio](https://github.com/YunoHost-Apps/minio_ynh).


**Shipped version:** 0.1.0~ynh1
## Documentation and resources

* YunoHost documentation for this app: <https://yunohost.org/app_restic-s3>
* Report a bug: <https://github.com/YunoHost-Apps/restic-s3_ynh/issues>

## Developer info

Please send your pull request to the [testing branch](https://github.com/YunoHost-Apps/restic-s3_ynh/tree/testing).

To try the testing branch, please proceed like that.

``` bash
sudo yunohost app install https://github.com/YunoHost-Apps/restic-s3_ynh/tree/testing --debug
or
sudo yunohost app upgrade restic-s3 -u https://github.com/YunoHost-Apps/restic-s3_ynh/tree/testing --debug
```

**More info regarding app packaging:** <https://yunohost.org/packaging_apps>
