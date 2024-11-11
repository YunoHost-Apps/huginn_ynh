<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Huginn pour YunoHost

[![Niveau d’intégration](https://dash.yunohost.org/integration/huginn.svg)](https://ci-apps.yunohost.org/ci/apps/huginn/) ![Statut du fonctionnement](https://ci-apps.yunohost.org/ci/badges/huginn.status.svg) ![Statut de maintenance](https://ci-apps.yunohost.org/ci/badges/huginn.maintain.svg)

[![Installer Huginn avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=huginn)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Huginn rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

Huginn is a system for building agents that perform automated tasks for you online. They can read the web, watch for events, and take actions on your behalf. Huginn's Agents create and consume events, propagating them along a directed graph. Think of it as a hackable version of IFTTT or Zapier on your own server. You always know who has your data. You do.

**Version incluse :** 2024.11.09~ynh1

## Captures d’écran

![Capture d’écran de Huginn](./doc/screenshots/your-agents.png)

## Documentations et ressources

- Dépôt de code officiel de l’app : <https://github.com/huginn/huginn>
- YunoHost Store : <https://apps.yunohost.org/app/huginn>
- Signaler un bug : <https://github.com/YunoHost-Apps/huginn_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/huginn_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
ou
sudo yunohost app upgrade huginn -u https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
