<!--
Важно: этот README был автоматически сгенерирован <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Он НЕ ДОЛЖЕН редактироваться вручную.
-->

# Phanpy для YunoHost

[![Уровень интеграции](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Состояние работы](https://apps.yunohost.org/badge/state/phanpy)
![Состояние сопровождения](https://apps.yunohost.org/badge/maintained/phanpy)

[![Установите Phanpy с YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Прочтите этот README на других языках.](./ALL_README.md)*

> *Этот пакет позволяет Вам установить Phanpy быстро и просто на YunoHost-сервер.*  
> *Если у Вас нет YunoHost, пожалуйста, посмотрите [инструкцию](https://yunohost.org/install), чтобы узнать, как установить его.*

## Обзор

**Phanpy YunoHost App** is built from upstream Phanpy `production` branch.

**Phanpy** is an alternative frontend for Mastodon or Gotosocial servers which are alternatives to X (twitter).


## Diferences from source

built with custom `.env`

* remove references to `phanpy.social` website
* change app name to «Phanpy for YunoHost»
* custom Privacy Policy ([in this repo](https://github.com/YunoHost-Apps/phanpy_ynh/blob/master/PRIVACY.md))
* default language *null* (browser's default)

## Features

    👪 Multiple accounts
    🪟 Compose window pop-out/in
    🌗 Light/dark/auto theme
    🔔 Grouped notifications
    🪺 Nested comments thread
    📬 Unsent draft recovery
    🎠 Boosts Carousel™️
    ⚡ Shortcuts™️ with view modes like multi-column or tab bar
    #️⃣ Multi-hashtag timeline

from <https://github.com/cheeaun/phanpy#features>

## Third-party services

Inline (and live) translation feature connects to <https://lingva.phanpy.social>. It's optional for the **user** to activate this feature.

## YNH Forum

Comment *phanpy_ynh* on [YunoHost Forum Topic](https://forum.yunohost.org/t/phanpy-a-minimalistic-opinionated-fediverse-web-client/32095)



**Поставляемая версия:** 20250126~ynh1

**Демо-версия:** <https://phanpy.social/>
## Документация и ресурсы

- Официальный веб-сайт приложения: <https://phanpy.social/>
- Репозиторий кода главной ветки приложения: <https://github.com/cheeaun/phanpy>
- Магазин YunoHost: <https://apps.yunohost.org/app/phanpy>
- Сообщите об ошибке: <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Информация для разработчиков

Пришлите Ваш запрос на слияние в [ветку `testing`](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

Чтобы попробовать ветку `testing`, пожалуйста, сделайте что-то вроде этого:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
или
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**Больше информации о пакетировании приложений:** <https://yunohost.org/packaging_apps>
