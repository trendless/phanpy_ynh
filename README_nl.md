<!--
NB: Deze README is automatisch gegenereerd door <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Hij mag NIET handmatig aangepast worden.
-->

# Phanpy voor Yunohost

[![Integratieniveau](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Mate van functioneren](https://apps.yunohost.org/badge/state/phanpy)
![Onderhoudsstatus](https://apps.yunohost.org/badge/maintained/phanpy)

[![Phanpy met Yunohost installeren](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Deze README in een andere taal lezen.](./ALL_README.md)*

> *Met dit pakket kun je Phanpy snel en eenvoudig op een YunoHost-server installeren.*  
> *Als je nog geen YunoHost hebt, lees dan [de installatiehandleiding](https://yunohost.org/install), om te zien hoe je 'm installeert.*

## Overzicht

**Phanpy YunoHost App** is built from upstream Phanpy stable branch source.

**Phanpy** is an alternative frontend for Mastodon or Gotosocial servers which are alternatives to X (twitter).


## Diferences from source

built with custom `.env`

* remove references to `phanpy.social` website
* change app name to «Phanpy for YunoHost»
* custom Privacy Policy (in this repo)

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



**Geleverde versie:** 20241208~ynh3

**Demo:** <https://phanpy.social/>
## Documentatie en bronnen

- Officiele website van de app: <https://phanpy.social/>
- Upstream app codedepot: <https://github.com/cheeaun/phanpy>
- YunoHost-store: <https://apps.yunohost.org/app/phanpy>
- Meld een bug: <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Ontwikkelaarsinformatie

Stuur je pull request alsjeblieft naar de [`testing`-branch](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

Om de `testing`-branch uit te proberen, ga als volgt te werk:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
of
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**Verdere informatie over app-packaging:** <https://yunohost.org/packaging_apps>
