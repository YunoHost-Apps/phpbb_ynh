<!--
N.B.: README ini dibuat secara otomatis oleh <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>
Ini TIDAK boleh diedit dengan tangan.
-->

# phpBB untuk YunoHost

[![Tingkat integrasi](https://apps.yunohost.org/badge/integration/phpbb)](https://ci-apps.yunohost.org/ci/apps/phpbb/)
![Status kerja](https://apps.yunohost.org/badge/state/phpbb)
![Status pemeliharaan](https://apps.yunohost.org/badge/maintained/phpbb)

[![Pasang phpBB dengan YunoHost](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpbb)

*[Baca README ini dengan bahasa yang lain.](./ALL_README.md)*

> *Paket ini memperbolehkan Anda untuk memasang phpBB secara cepat dan mudah pada server YunoHost.*  
> *Bila Anda tidak mempunyai YunoHost, silakan berkonsultasi dengan [panduan](https://yunohost.org/install) untuk mempelajari bagaimana untuk memasangnya.*

## Ringkasan

phpBB is a free flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. With an extensive database of user-created extensions and styles database containing hundreds of style and image packages to customise your board, you can create a very unique forum in minutes.


**Versi terkirim:** 3.3.11~ynh2

**Demo:** <https://www.phpbb.com/demo/>

## Tangkapan Layar

![Tangkapan Layar pada phpBB](./doc/screenshots/screenshot.png)

## Dokumentasi dan sumber daya

- Website aplikasi resmi: <http://www.phpbb.com/>
- Dokumentasi admin resmi: <https://www.phpbb.com/support/docs/>
- Depot kode aplikasi hulu: <https://github.com/phpbb/phpbb>
- Gudang YunoHost: <https://apps.yunohost.org/app/phpbb>
- Laporkan bug: <https://github.com/YunoHost-Apps/phpbb_ynh/issues>

## Info developer

Silakan kirim pull request ke [`testing` branch](https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing).

Untuk mencoba branch `testing`, silakan dilanjutkan seperti:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
atau
sudo yunohost app upgrade phpbb -u https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
```

**Info lebih lanjut mengenai pemaketan aplikasi:** <https://yunohost.org/packaging_apps>
