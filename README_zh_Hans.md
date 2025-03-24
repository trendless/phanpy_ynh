<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 Phanpy

[![集成程度](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![工作状态](https://apps.yunohost.org/badge/state/phanpy)
![维护状态](https://apps.yunohost.org/badge/maintained/phanpy)

[![使用 YunoHost 安装 Phanpy](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 Phanpy。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

**Phanpy** is an alternative frontend for Mastodon or Gotosocial servers which are alternatives to X (twitter).

This YunoHost app is built from upstream Phanpy `production` branch.

### Differences from source

built with custom `.env`

* remove references to `phanpy.social` website
* change app name to «Phanpy for YunoHost»
* custom Privacy Policy ([in this repo](https://github.com/YunoHost-Apps/phanpy_ynh/blob/master/PRIVACY.md))
* default language *null* (browser's default)

### Features

* 👪 Multiple accounts
* 🪟 Compose window pop-out/in
* 🌗 Light/dark/auto theme
* 🔔 Grouped notifications
* 🪺 Nested comments thread
* 📬 Unsent draft recovery
* 🎠 Boosts Carousel™️
* ⚡ Shortcuts™️ with view modes like multi-column or tab bar
* #️⃣ Multi-hashtag timeline

from <https://github.com/cheeaun/phanpy#features>

### Third-party services

Inline (and live) translation feature connects to <https://lingva.phanpy.social>. It's optional for the **user** to activate this feature.

## YNH Forum

Comment *phanpy_ynh* on [YunoHost Forum Topic](https://forum.yunohost.org/t/phanpy-a-minimalistic-opinionated-fediverse-web-client/32095)



**分发版本：** 20250322~ynh1

**演示：** <https://phanpy.social/>
## 文档与资源

- 官方应用网站： <https://phanpy.social/>
- 上游应用代码库： <https://github.com/cheeaun/phanpy>
- YunoHost 商店： <https://apps.yunohost.org/app/phanpy>
- 报告 bug： <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
或
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
