<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# phpBB YunoHost-erako

[![Integrazio maila](https://dash.yunohost.org/integration/phpbb.svg)](https://ci-apps.yunohost.org/ci/apps/phpbb/) ![Funtzionamendu egoera](https://ci-apps.yunohost.org/ci/badges/phpbb.status.svg) ![Mantentze egoera](https://ci-apps.yunohost.org/ci/badges/phpbb.maintain.svg)

[![Instalatu phpBB YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpbb)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek phpBB YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

phpBB is a free flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. With an extensive database of user-created extensions and styles database containing hundreds of style and image packages to customise your board, you can create a very unique forum in minutes.


**Paketatutako bertsioa:** 3.3.11~ynh1

**Demoa:** <https://www.phpbb.com/demo/>

## Pantaila-argazkiak

![phpBB(r)en pantaila-argazkia](./doc/screenshots/screenshot.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <http://www.phpbb.com/>
- Administratzaileen dokumentazio ofiziala: <https://www.phpbb.com/support/docs/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/phpbb/phpbb>
- YunoHost Denda: <https://apps.yunohost.org/app/phpbb>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/phpbb_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
edo
sudo yunohost app upgrade phpbb -u https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
