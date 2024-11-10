# phanpy_ynh

yunhost package for [Phanpy](https://phanpy.social), *A minimalistic opinionated Mastodon web client* you can use to access other Fediverse ⁂ servers too like GoToSocial, Pleroma, etc.

This app is a web **client**, you need an account in any of the compatible **servers**.

You **do not** need to install a server in your YNH, you can use your account from external servers (i.e. mastodon.social)

## Access

you can restrict access to this app to `all_users` in your server (they will need to log in to view the app) or `visitors`, so it will be publicly available to anyone to use it.

This app runs in the visitor's browser, no data is managed in/from your server.

## Install

`sudo yunohost app install https://github.com/xmgz/phanpy_ynh/tree/main --debug`
