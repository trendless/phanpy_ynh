<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# Phanpy YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/phanpy)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/phanpy)

[![Instalatu Phanpy YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek Phanpy YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

This Phanpy YunoHost App is built from uptream Phanpy stable branch source.

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



**Paketatutako bertsioa:** 20241208~ynh2

**Demoa:** <https://phanpy.social/>
## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://phanpy.social/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/cheeaun/phanpy>
- YunoHost Denda: <https://apps.yunohost.org/app/phanpy>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
edo
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
