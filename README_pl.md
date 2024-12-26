<!--
To README zostało automatycznie wygenerowane przez <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Nie powinno być ono edytowane ręcznie.
-->

# Phanpy dla YunoHost

[![Poziom integracji](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Status działania](https://apps.yunohost.org/badge/state/phanpy)
![Status utrzymania](https://apps.yunohost.org/badge/maintained/phanpy)

[![Zainstaluj Phanpy z YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Przeczytaj plik README w innym języku.](./ALL_README.md)*

> *Ta aplikacja pozwala na szybką i prostą instalację Phanpy na serwerze YunoHost.*  
> *Jeżeli nie masz YunoHost zapoznaj się z [poradnikiem](https://yunohost.org/install) instalacji.*

## Przegląd

This Phanpy YunoHost App is built from uptream Phanpy stable branch source.
Phanpy is ans alternative frontend for Mastodon or Gotosocial servers which are alternatives to twitter or X.


## Difference

built with custom `.env`

* retire references to `phanpy.social` website
* change app name to «Phanpy for YunoHost»
* custom Privacy Policy

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

Inline (and live) translation feature connects to <https://lingva.phanpy.social>. It's optional for the user to activate this feature.

## YNH Forum

Comment *phanpy_ynh* on [YunoHost Forum Topic](https://forum.yunohost.org/t/phanpy-a-minimalistic-opinionated-fediverse-web-client/32095)



**Dostarczona wersja:** 20241208~ynh2

**Demo:** <https://phanpy.social/>
## Dokumentacja i zasoby

- Oficjalna strona aplikacji: <https://phanpy.social/>
- Repozytorium z kodem źródłowym: <https://github.com/cheeaun/phanpy>
- Sklep YunoHost: <https://apps.yunohost.org/app/phanpy>
- Zgłaszanie błędów: <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Informacje od twórców

Wyślij swój pull request do [gałęzi `testing`](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

Aby wypróbować gałąź `testing` postępuj zgodnie z instrukcjami:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
lub
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**Więcej informacji o tworzeniu paczek aplikacji:** <https://yunohost.org/packaging_apps>
