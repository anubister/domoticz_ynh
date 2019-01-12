# Usage of this package (REMOVE THIS SECTION BEFORE RELEASE)
- Copy this app before working on it.
- Edit `conf/nginx.conf` file to match application prerequisites.
- Edit `manifest.json` with application specific information.
- Edit the `install`, `upgrade`, `remove`, `backup`, and `restore` scripts.
- Add a `LICENSE` file for the package.
- Edit `README.md`.

# Domoticz pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/REPLACEBYYOURAPP.svg)](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20%28Community%29/lastBuild/consoleFull)  
[![Install REPLACEBYYOURAPP with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=REPLACEBYYOURAPP)

> *Ce paquet permet d'installer [Domoticz](https://domoticz.com) rapidement et facilement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, [voir ici](https://yunohost.org/#/install) comment installer et en profiter.*

> *This package allow you to install [Domoticz](https://domoticz.com) quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

## Aperçu
Domoticz permet de gérer un système domotique :
- enregistrements, tracés de données capteurs (température, humidité, luminosité, ...)
- commander des actionneurs (lumières, volets, ...)
- créer des scénarii
De nombreux protocoles (RFLink, Zwave, MQTT, ...) et matériels sont [compatibles](https://www.domoticz.com/wiki/Hardware).

**Version packagée :** Domoticz 4.9700 (version stable au 12/01/2019)
**Shipped version:** Domoticz 4.9700

## Captures d'écran

[Paramétrage](https://www.domoticz.com/wiki/Application_Settings)

## Demo

* [Official demo](Link to a demo site for this app)

## Configuration

How to configure this app: by an admin panel, a plain file with SSH, or any other way.

## Documentation

 * Official documentation: Link to the official documentation of this app
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## YunoHost specific features

#### Multi-users support

Are LDAP and HTTP auth supported?
Can the app be used by multiple users?

#### Supported architectures

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)%20(%7EARM%7E)/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/jenkins/job/REPLACEBYYOURAPP%20(Community)/badge/icon)](https://ci-stretch.nohost.me/jenkins/job/REPLACEBYYOURAPP%20(Community)/)

## Limitations

* Any known limitations.

## Additional information

* Other information you would add about this application

**More information on the documentation page:**  
https://yunohost.org/packaging_apps

## Links

 * Report a bug: https://github.com/anubister/domoticz_ynh/issues
 * App website: Link to the official website of this app
 * YunoHost website: https://yunohost.org/

---

Developers info
----------------

**Only if you want to use a testing branch for coding, instead of merging directly into master.**
Please do your pull request to the [testing branch](https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing).

To try the testing branch, please proceed like that.
```
sudo yunohost app install https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --debug
or
sudo yunohost app upgrade REPLACEBYYOURAPP -u https://github.com/YunoHost-Apps/REPLACEBYYOURAPP_ynh/tree/testing --debug
```
