# Domoticz pour YunoHost

[![Integration level](https://dash.yunohost.org/integration/domoticz.svg)](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20%28Community%29/lastBuild/consoleFull)  
[![Install Domoticz with YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=domoticz)

> Ce paquet permet d'installer [Domoticz](https://domoticz.com) rapidement et facilement sur un serveur YunoHost.
Si vous n'avez pas YunoHost, [voir ici](https://yunohost.org/#/install) comment installer et en profiter.

> *This package allow you to install [Domoticz](https://domoticz.com) quickly and simply on a YunoHost server.
If you don't have YunoHost, please see [here](https://yunohost.org/#/install) to know how to install and enjoy it.*

:warning: App en cours de test
:warning: L'installation peut prendre plus de 30min (téléchargement des sources Domoticz (36Mo) puis compilation), installation depuis la ligne de commande recommandée.

:warning: *Work in progress*
:warning: *Installation duration may exceed 30min (download of Domoticz sources and compilation). Install from command line is recommanded.*

## Aperçu

Domoticz permet de gérer un système domotique :
- enregistrements, tracés de données capteurs (température, humidité, luminosité, ...)
- commander des actionneurs (lumières, volets, ...)
- créer des scénarii
De nombreux protocoles (RFLink, Zwave, MQTT, ...) et matériels sont [compatibles](https://www.domoticz.com/wiki/Hardware).

*Domoticz is a Home Automation System, allowing:
- to save, to plot sensors datas (temperature, humidity, brightness, ...)
- to command switchs (light, shutters, ...)
- to create screnarii
A lot of protocols (RFLink, Zwave, MQTT, ...) and hardware are [compatibles](https://www.domoticz.com/wiki/Hardware).*

**Version packagée :** Domoticz 4.9700 (version stable au 12/01/2019)
**Shipped version:** Domoticz 4.9700

## Captures d'écran

[Paramétrage](https://www.domoticz.com/wiki/Application_Settings)

## Demo

* (no demo site known)

## Configuration

(no specific configuration)

## Documentation

 * Official documentation: [wiki](https://www.domoticz.com/wiki/)
 * YunoHost documentation: If specific documentation is needed, feel free to contribute.

## Fonctionnalités YunoHost

#### Support multi-utilisateurs

Pas de gestion utilisateur et encore moins multi-utilisateur depuis Yunohost.
*no user management from YunoHost.*

#### Architectures supportées

Testé uniquement sur x86-64 (retours bienvenus pour les autres architectures)
*Tested only on x86-64 (feedback welcome for other architecture)*

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)/badge/icon)](https://ci-apps.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)%20(%7EARM%7E)/badge/icon)](https://ci-apps-arm.yunohost.org/jenkins/job/REPLACEBYYOURAPP%20(Community)%20(%7EARM%7E)/)
* Jessie x86-64b - [![Build Status](https://ci-stretch.nohost.me/jenkins/job/REPLACEBYYOURAPP%20(Community)/badge/icon)](https://ci-stretch.nohost.me/jenkins/job/REPLACEBYYOURAPP%20(Community)/)

## Limitations

* Version affichée : V4.5876 au lieu de V4.9700 (bug dans le paquet Domoticz ?)
*Displayed version is V4.5876 instead of V4.9700*
* Pas de configuration de la langue Domoticz et utilisateurs depuis YunoHost
*no language nor Domoticz users management from YunoHost*
* Pas de support HTTPS
*no HTTPS support*
* Pas de support OpenZWave, Telldus
*no OpenZWave nor Telldus support*

## Crédits
* Merci à kayou pour son aide pour réaliser cette app.

## Liens

 * Report a bug: https://github.com/anubister/domoticz_ynh/issues
   Discussion sur [](xmpp:apps@conference.yunohost.org?join)
 * App website: https://domoticz.com
 * YunoHost website: https://yunohost.org/

