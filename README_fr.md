<!--
Nota bene : ce README est automatiquement généré par <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Il NE doit PAS être modifié à la main.
-->

# Phanpy pour YunoHost

[![Niveau d’intégration](https://apps.yunohost.org/badge/integration/phanpy)](https://ci-apps.yunohost.org/ci/apps/phanpy/)
![Statut du fonctionnement](https://apps.yunohost.org/badge/state/phanpy)
![Statut de maintenance](https://apps.yunohost.org/badge/maintained/phanpy)

[![Installer Phanpy avec YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phanpy)

*[Lire le README dans d'autres langues.](./ALL_README.md)*

> *Ce package vous permet d’installer Phanpy rapidement et simplement sur un serveur YunoHost.*  
> *Si vous n’avez pas YunoHost, consultez [ce guide](https://yunohost.org/install) pour savoir comment l’installer et en profiter.*

## Vue d’ensemble

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



**Version incluse :** 20241208~ynh3

**Démo :** <https://phanpy.social/>
## Documentations et ressources

- Site officiel de l’app : <https://phanpy.social/>
- Dépôt de code officiel de l’app : <https://github.com/cheeaun/phanpy>
- YunoHost Store : <https://apps.yunohost.org/app/phanpy>
- Signaler un bug : <https://github.com/YunoHost-Apps/phanpy_ynh/issues>

## Informations pour les développeurs

Merci de faire vos pull request sur la [branche `testing`](https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing).

Pour essayer la branche `testing`, procédez comme suit :

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
ou
sudo yunohost app upgrade phanpy -u https://github.com/YunoHost-Apps/phanpy_ynh/tree/testing --debug
```

**Plus d’infos sur le packaging d’applications :** <https://yunohost.org/packaging_apps>
