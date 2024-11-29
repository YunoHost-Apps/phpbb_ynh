<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 phpBB

[![集成程度](https://apps.yunohost.org/badge/integration/phpbb)](https://ci-apps.yunohost.org/ci/apps/phpbb/)
![工作状态](https://apps.yunohost.org/badge/state/phpbb)
![维护状态](https://apps.yunohost.org/badge/maintained/phpbb)

[![使用 YunoHost 安装 phpBB](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=phpbb)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 phpBB。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

phpBB is a free flat-forum bulletin board software solution that can be used to stay in touch with a group of people or can power your entire website. With an extensive database of user-created extensions and styles database containing hundreds of style and image packages to customise your board, you can create a very unique forum in minutes.


**分发版本：** 3.3.11~ynh2

**演示：** <https://www.phpbb.com/demo/>

## 截图

![phpBB 的截图](./doc/screenshots/screenshot.png)

## 文档与资源

- 官方应用网站： <http://www.phpbb.com/>
- 官方管理文档： <https://www.phpbb.com/support/docs/>
- 上游应用代码库： <https://github.com/phpbb/phpbb>
- YunoHost 商店： <https://apps.yunohost.org/app/phpbb>
- 报告 bug： <https://github.com/YunoHost-Apps/phpbb_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
或
sudo yunohost app upgrade phpbb -u https://github.com/YunoHost-Apps/phpbb_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
