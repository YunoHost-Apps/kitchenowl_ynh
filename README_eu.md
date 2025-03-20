<!--
Ohart ongi: README hau automatikoki sortu da <https://github.com/YunoHost/apps/tree/master/tools/readme_generator>ri esker
EZ editatu eskuz.
-->

# KitchenOwl YunoHost-erako

[![Integrazio maila](https://apps.yunohost.org/badge/integration/kitchenowl)](https://ci-apps.yunohost.org/ci/apps/kitchenowl/)
![Funtzionamendu egoera](https://apps.yunohost.org/badge/state/kitchenowl)
![Mantentze egoera](https://apps.yunohost.org/badge/maintained/kitchenowl)

[![Instalatu KitchenOwl YunoHost-ekin](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kitchenowl)

*[Irakurri README hau beste hizkuntzatan.](./ALL_README.md)*

> *Pakete honek KitchenOwl YunoHost zerbitzari batean azkar eta zailtasunik gabe instalatzea ahalbidetzen dizu.*  
> *YunoHost ez baduzu, kontsultatu [gida](https://yunohost.org/install) nola instalatu ikasteko.*

## Aurreikuspena

KitchenOwl is a smart self-hosted grocery list and recipe manager. Easily add items to your shopping list before you go shopping. You can also create recipes and get suggestions on what you want to cook. Track your expenses so you know how much you've spent.

    Native Mobile/Web/Desktop apps with a great design
    Add items to your shopping list and sync them with multiple users
    Partial offline support, so you don't lose track of what to buy even when there is no signal
    Manage recipes and add them to your shopping list
    Create a meal plan to always know what you'll be eating
    Manage balances and track expenses of your household

Please keep in mind that this project is still in development.

For a full list check out the website. For a list of planned features, take a look at the Roadmap!

**Paketatutako bertsioa:** 0.4.7~ynh1

**Demoa:** <https://app.kitchenowl.org/>

## Pantaila-argazkiak

![KitchenOwl(r)en pantaila-argazkia](./doc/screenshots/kitchenowl.png)

## Dokumentazioa eta baliabideak

- Aplikazioaren webgune ofiziala: <https://kitchenowl.org/>
- Erabiltzaileen dokumentazio ofiziala: <https://docs.kitchenowl.org/getting-started/tips-and-tricks/>
- Administratzaileen dokumentazio ofiziala: <https://docs.kitchenowl.org/>
- Jatorrizko aplikazioaren kode-gordailua: <https://github.com/TomBursch/kitchenowl>
- YunoHost Denda: <https://apps.yunohost.org/app/kitchenowl>
- Eman errore baten berri: <https://github.com/YunoHost-Apps/kitchenowl_ynh/issues>

## Garatzaileentzako informazioa

Bidali `pull request`a [`testing` abarrera](https://github.com/YunoHost-Apps/kitchenowl_ynh/tree/testing).

`testing` abarra probatzeko, ondorengoa egin:

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kitchenowl_ynh/tree/testing --debug
edo
sudo yunohost app upgrade kitchenowl -u https://github.com/YunoHost-Apps/kitchenowl_ynh/tree/testing --debug
```

**Informazio gehiago aplikazioaren paketatzeari buruz:** <https://yunohost.org/packaging_apps>
