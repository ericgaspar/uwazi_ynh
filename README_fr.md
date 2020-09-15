# Uwazi pour YunoHost

[![Niveau d'intégration](https://dash.yunohost.org/integration/uwazi.svg)](https://dash.yunohost.org/appci/app/uwazi) ![](https://ci-apps.yunohost.org/ci/badges/uwazi.status.svg) ![](https://ci-apps.yunohost.org/ci/badges/uwazi.maintain.svg)  
[![Installer Uwazi avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.png)](https://install-app.yunohost.org/?app=uwazi)

*[Read this readme in english.](./README.md)* 

> *Ce package vous permet d'installer Uwazi rapidement et simplement sur un serveur YunoHost.  
Si vous n'avez pas YunoHost, consultez [le guide](https://yunohost.org/#/install) pour apprendre comment l'installer.*

## Vue d'ensemble
CodiMD est un service web de traitement de texte collaboratif en temps réel. Il utilise le langage Markdown.

**Version incluse :** 1.6.0

## Captures d'écran

![]()

## Démo

* [Démo officielle](https://demo.uwazi.io/)

## Configuration


## Documentation

 * Documentation officielle : 
 * Documentation YunoHost : https://yunohost.org/#/app_uwazi_fr

## Caractéristiques spécifiques YunoHost

#### Support multi-utilisateur

* L'authentification LDAP est-elle prise en charge ? **Oui**
* L'application peut-elle être utilisée par plusieurs utilisateurs ? **Oui**

#### Architectures supportées

* x86-64b - [![Build Status](https://ci-apps.yunohost.org/ci/logs/uwazi%20%28Apps%29.svg)](https://ci-apps.yunohost.org/ci/apps/uwazi/)
* ARMv8-A - [![Build Status](https://ci-apps-arm.yunohost.org/ci/logs/uwazi%20%28Apps%29.svg)](https://ci-apps-arm.yunohost.org/ci/apps/uwazi/)

## Liens

 * Signaler un bug : https://github.com/YunoHost-Apps/uwazi_ynh/issues
 * Dépôt de l'application principale : 
 * Site web YunoHost : https://yunohost.org/

---

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche testing](https://github.com/YunoHost-Apps/uwazi_ynh/tree/testing).

Pour essayer la branche testing, procédez comme suit.
```
sudo yunohost app install https://github.com/YunoHost-Apps/uwazi_ynh/tree/testing --debug
ou
sudo yunohost app upgrade uwazi -u https://github.com/YunoHost-Apps/uwazi_ynh/tree/testing --debug
```
