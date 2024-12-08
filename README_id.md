<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Huginn untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/huginn)](https://ci-apps.yunohost.org/ci/apps/huginn/)
![Status kerja](https://apps.yunohost.org/badge/state/huginn)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/huginn)

[![Pasang Huginn dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=huginn)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Huginn secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

Huginn is a system for building agents that perform automated tasks for you online. They can read the web, watch for events, and take actions on your behalf. Huginn's Agents create and consume events, propagating them along a directed graph. Think of it as a hackable version of IFTTT or Zapier on your own server. You always know who has your data. You do.

**Versi terkirim:** 2024.12.05~ynh1

## Tangkapan Layar

![Tangkapan Layar pada Huginn](./doc/screenshots/your-agents.png)

## Dokumentasi dan sumber daya

- Depot kode aplikasi hulu: <https://github.com/huginn/huginn>
- Gudang YunoHost: <https://apps.yunohost.org/app/huginn>
- Laporkan bug: <https://github.com/YunoHost-Apps/huginn_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/huginn_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
atau
sudo yunohost app upgrade huginn -u https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
