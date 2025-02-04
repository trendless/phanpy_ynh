<!--
Este archivo README esta generado automaticamente<https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
No se debe editar a mano.
-->

# Phanpy para Yunohost

[![Nivel de integración](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Estado funcional](https://apps.yunohost.org/badge/state/phanpy)
![Estado En Mantención](https://apps.yunohost.org/badge/maintained/phanpy)

[![Instalar Phanpy con Yunhost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Leer este README en otros idiomas.](./ALL_README.md)*

> *Este paquete le permite instalarPhanpy rapidamente y simplement en un servidor YunoHost.*  
> *Si no tiene YunoHost, visita [the guide](https://yunohost.org/install) para aprender como instalarla.*

## Descripción general

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



<<<<<<< HEAD
**Versión actual:** 20241208~ynh1
=======
**Versión actual:** 20241228~ynh1
>>>>>>> testing

**Demo:** <https://phanpy.social/>
## Documentaciones y recursos

- Sitio web oficial: <https://phanpy.social/>
- Repositorio del código fuente oficial de la aplicación : <https://github.com/cheeaun/phanpy>
- Catálogo YunoHost: <https://apps.yunohost.org/app/phanpy>
- Reportar un error: <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Información para desarrolladores

Por favor enviar sus correcciones a la [rama `testing`](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

Para probar la rama `testing`, sigue asÍ:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
o
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**Mas informaciones sobre el empaquetado de aplicaciones:** <https://yunohost.org/packaging_apps>
