# LimeSurvey for YunoHost

[![Integration level](https://dash.yunohost.org/integration/limesurvey.svg)](https://dash.yunohost.org/appci/app/limesurvey) ![](https://ci-apps.yunohost.org/ci/badges/limesurvey.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/limesurvey.maintain.svg)  
[![Install LimeSurvey with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=limesurvey)

> *This package allow you to install LimeSurvey quickly and simply on a YunoHost server.  
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Overview
LimeSurvey is used to create advanced poll.

**Shipped version:** 4.3.21

**Categories:** Productivity, Poll

## Screenshots

![](https://www.limesurvey.org/images/news/LimeSurvey3Beta/generalsettings.PNG)

## Configuration

Before to run the install YunoHost ask you an admin user, you can use it to connecte you on `https://your_limesurvey_url/admin/`

## Documentation

* YunoHost documentation: There no other documentations, feel free to contribute.

## YunoHost specific features

* In private mode, only authorized YunoHost members can create poll, with the public mode, it's possible to create account to people with no YunoHost account. 
* SSO and LDAP are configured.
* Login secured by Fail2Ban

#### Multi-users support

Not supported.

#### Supported architectures

* x86-64 - [![Build Status](https://ci-apps.yunohost.org/ci/logs/limesurvey%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/limesurvey/)

* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/limesurvey%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/limesurvey/)

## Limitations

## Additionnal informations

## Links

 * Report a bug: https://github.com/YunoHost-Apps/limesurvey_ynh/issues
 * App website: https://www.limesurvey.org
 * Upstream app repository: https://github.com/LimeSurvey/LimeSurvey
 * YunoHost website: https://yunohost.org/

---

## Developers infos

**Package by:** ljf

**Patches author:** Shnoulle

Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing --verbose
or
sudo yunohost app upgrade limesurvey -u https://github.com/YunoHost-Apps/limesurvey_ynh/tree/testing --verbose
```
