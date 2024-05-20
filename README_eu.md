<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Huginn YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/huginn.svg)](https://dash.yunohost.org/appci/app/huginn) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/huginn.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/huginn.maintain.svg)

[![Instalatu Huginn YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=huginn)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Huginn YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

Huginn is a system for building agents that perform automated tasks for you online. They can read the web, watch for events, and take actions on your behalf. Huginn's Agents create and consume events, propagating them along a directed graph. Think of it as a hackable version of IFTTT or Zapier on your own server. You always know who has your data. You do.

**Paketatutako bertsioa:** 2022.08.18~ynh1

## Pantaila-argazkiak

![Huginn(r)en pantaila-argazkia](./doc/screenshots/your-agents.png)

## Dokumentazioa eta baliabideak

- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/huginn/huginn>
- YunoHost Denda: <https://apps.yunohost.org/app/huginn>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/huginn_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/huginn_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
edo
sudo yunohost app upgrade huginn -u https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
