# 常见问题

### PaaS2.0 的应用可以直接部署在 PaaS3.0 开发者中心上吗

PaaS2.0 的应用代码需要做一些修改后才能部署到 PaaS3.0 开发者中心上，具体可以参考：[应用迁移介绍](../PaaS3.0/topics/paas/legacy_migration.md)

如果使用最新版的开发框架开发的话，可以同时部署在 PaaS2.0 和 PaaS3.0 开发者中心上。


### 开发框架的代码在哪里获取

创建完应用后，在应用概览页面的右上角，点击 "下载初始化模板代码" 即可下载最新版的开发框架代码。


### 无法访问后台管理后台

由于匿名用户没有访问管理后台的权限，所以没有登录态的情况下访问管理后台会返回 404 页面。

必须先打开并登录到 PaaS3.0 开发者中心后，才能正常打开访问后台管理后台。