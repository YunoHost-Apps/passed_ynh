<!--
注意：此 README 由 <https://github.com/YunoHost/apps/tree/master/tools/readme_generator> 自动生成
请勿手动编辑。
-->

# YunoHost 上的 PassED

[![集成程度](https://apps.yunohost.org/badge/integration/passed)](https://ci-apps.yunohost.org/ci/apps/passed/)
![工作状态](https://apps.yunohost.org/badge/state/passed)
![维护状态](https://apps.yunohost.org/badge/maintained/passed)

[![使用 YunoHost 安装 PassED](https://install-app.yunohost.org/install-with-yunohost.svg)](https://install-app.yunohost.org/?app=passed)

*[阅读此 README 的其它语言版本。](./ALL_README.md)*

> *通过此软件包，您可以在 YunoHost 服务器上快速、简单地安装 PassED。*  
> *如果您还没有 YunoHost，请参阅[指南](https://yunohost.org/install)了解如何安装它。*

## 概况

Share a password with someone securely by generating single-use URLs so that it doesn't get logged in a mailbox, shown in a messenger app's notification, etc. 

The password is contained in the URL itself as an encrypted string whereas the decryption key stored on the server is deleted after first use or selected timeframe. 


**分发版本：** 2024.12.29~ynh1

## 截图

![PassED 的截图](./doc/screenshots/passed_ynh.png)

## 文档与资源

- 官方用户文档： <https://git.1e99.eu/1e99/passed/src/branch/main/README.md#how-it-works>
- 上游应用代码库： <https://git.1e99.eu/1e99/passed>
- YunoHost 商店： <https://apps.yunohost.org/app/passed>
- 报告 bug： <https://github.com/YunoHost-Apps/passed_ynh/issues>

## 开发者信息

请向 [`testing` 分支](https://github.com/YunoHost-Apps/passed_ynh/tree/testing) 发送拉取请求。

如要尝试 `testing` 分支，请这样操作：

```bash
sudo yunohost app install https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
或
sudo yunohost app upgrade passed -u https://github.com/YunoHost-Apps/passed_ynh/tree/testing --debug
```

**有关应用打包的更多信息：** <https://yunohost.org/packaging_apps>
