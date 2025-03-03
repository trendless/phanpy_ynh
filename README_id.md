<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# Phanpy untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Status kerja](https://apps.yunohost.org/badge/state/phanpy)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/phanpy)

[![Pasang Phanpy dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang Phanpy secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

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



**Versi terkirim:** 20250126~ynh1

**Demo:** <https://phanpy.social/>
## Dokumentasi dan sumber daya

- Website aplikasi resmi: <https://phanpy.social/>
- Depot kode aplikasi hulu: <https://github.com/cheeaun/phanpy>
- Gudang YunoHost: <https://apps.yunohost.org/app/phanpy>
- Laporkan bug: <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
atau
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
