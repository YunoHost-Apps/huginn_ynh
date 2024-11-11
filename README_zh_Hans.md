<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Huginn

[![集成程度](https://dash.yunohost.org/integration/huginn.svg)](https://ci-apps.yunohost.org/ci/apps/huginn/) ![工作状态](https://ci-apps.yunohost.org/ci/badges/huginn.status.svg) ![维护状态](https://ci-apps.yunohost.org/ci/badges/huginn.maintain.svg)

[![使用 YunoHost 安装 Huginn](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=huginn)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Huginn。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Huginn is a system for building agents that perform automated tasks for you online. They can read the web, watch for events, and take actions on your behalf. Huginn's Agents create and consume events, propagating them along a directed graph. Think of it as a hackable version of IFTTT or Zapier on your own server. You always know who has your data. You do.

**分发版本：** 2024.11.09~ynh1

## 截图

![Huginn 的截图](./doc/screenshots/your-agents.png)

## 文档与资源

- 上游应用代码库： <https://github.com/huginn/huginn>
- YunoHost 商店： <https://apps.yunohost.org/app/huginn>
- 报告 bug： <https://github.com/YunoHost-Apps/huginn_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/huginn_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
或
sudo yunohost app upgrade huginn -u https://github.com/YunoHost-Apps/huginn_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
