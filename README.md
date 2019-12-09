# Radarr for YunoHost

[![Integration level](https://dash.yunohost.org/integration/radarr.svg)](https://dash.yunohost.org/appci/app/radarr)
[![Install Radarr with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=radarr)

*[Lire ce readme en français.](./README_fr.md)*

> *This package allow you to install Radarr quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
Radarr is a PVR for Usenet and BitTorrent users. It can monitor multiple RSS feeds for new movies and will grab, sort and rename them. It can also be configured to automatically upgrade the quality of files already downloaded when a better quality format becomes available.

**Shipped version:** 0.2.0.1450

## Configuration

You can configure Radarr directly in the admin panel.

## Documentation

 * Official documentation: https://github.com/Radarr/Radarr/wiki

## YunoHost specific features

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/radarr%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/radarr/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/radarr%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/radarr/)

## Limitations

* Work only on port 7878.

## Links

 * Report a bug: https://github.com/YunoHost-Apps/radarr_ynh/issues
 * App website: https://radarr.video/
 * Upstream app repository: https://github.com/Radarr/Radarr
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/radarr_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/radarr_ynh/tree/testing --debug
or
sudo yunohost app upgrade radarr -u https://github.com/YunoHost-Apps/radarr_ynh/tree/testing --debug
```
