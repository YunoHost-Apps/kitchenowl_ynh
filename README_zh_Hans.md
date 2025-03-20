<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 KitchenOwl

[![集成程度](https://apps.yunohost.org/badge/integration/kitchenowl)](https://ci-apps.yunohost.org/ci/apps/kitchenowl/)
![工作状态](https://apps.yunohost.org/badge/state/kitchenowl)
![维护状态](https://apps.yunohost.org/badge/maintained/kitchenowl)

[![使用 YunoHost 安装 KitchenOwl](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=kitchenowl)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 KitchenOwl。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

KitchenOwl is a smart self-hosted grocery list and recipe manager. Easily add items to your shopping list before you go shopping. You can also create recipes and get suggestions on what you want to cook. Track your expenses so you know how much you've spent.

    Native Mobile/Web/Desktop apps with a great design
    Add items to your shopping list and sync them with multiple users
    Partial offline support, so you don't lose track of what to buy even when there is no signal
    Manage recipes and add them to your shopping list
    Create a meal plan to always know what you'll be eating
    Manage balances and track expenses of your household

Please keep in mind that this project is still in development.

For a full list check out the website. For a list of planned features, take a look at the Roadmap!

**分发版本：** 0.4.7~ynh1

**演示：** <https://app.kitchenowl.org/>

## 截图

![KitchenOwl 的截图](./doc/screenshots/kitchenowl.png)

## 文档与资源

- 官方应用网站： <https://kitchenowl.org/>
- 官方用户文档： <https://docs.kitchenowl.org/getting-started/tips-and-tricks/>
- 官方管理文档： <https://docs.kitchenowl.org/>
- 上游应用代码库： <https://github.com/TomBursch/kitchenowl>
- YunoHost 商店： <https://apps.yunohost.org/app/kitchenowl>
- 报告 bug： <https://github.com/YunoHost-Apps/kitchenowl_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/kitchenowl_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/kitchenowl_ynh/tree/testing --debug
或
sudo yunohost app upgrade kitchenowl -u https://github.com/YunoHost-Apps/kitchenowl_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
