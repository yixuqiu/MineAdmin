中文 | [English](./README-en.md)
# 项目介绍

<p align="center">
    <img src="https://doc.mineadmin.com/logo.svg" width="120" />
</p>
<p align="center">
    <a href="https://www.mineadmin.com" target="_blank">官网</a> |
    <a href="https://doc.mineadmin.com" target="_blank">文档</a> | 
    <a href="https://demo.mineadmin.com" target="_blank">演示</a> |
    <a href="https://hyperf.wiki/3.0/#/" target="_blank">Hyperf官方文档</a> 
</p>

<p align="center">
    <img src="https://gitee.com/xmo/MineAdmin/badge/star.svg?theme=dark" />
    <img src="https://gitee.com/xmo/MineAdmin/badge/fork.svg?theme=dark" />
    <img src="https://svg.hamm.cn/badge.svg?key=License&value=Apache-2.0&color=da4a00" />
    <img src="https://svg.hamm.cn/badge.svg?key=MineAdmin&value=v2.0 LTS" />
</p>

## 项目介绍

PHP有很多优秀的后台管理系统，但基于Swoole的后台管理系统没找到合适我自己的。
所以就开发了一套后台管理系统。系统可以用于网站管理后台、CMS、CRM、OA、ERP等。

后台系统基于 Hyperf 框架开发。企业级架构分层，轻松支撑创业公司及个人前期发展使用，使用少量的服务器资源媲美静态语言的性能。
前端使用Vue3 + Vite4 + Pinia + Arco，一端适配PC、移动端、平板

如果觉着还不错的话，就请点个 ⭐star 支持一下吧，这将是对我最大的支持和鼓励！
在使用 MineAdmin 前请认真阅读[《免责声明》](https://doc.mineadmin.com/guide/start/declaration.html)并同意该声明。

- 腾讯云特惠专场：[点击进入](http://txy.mineadmin.com)
- 阿里云特惠专场：[点击进入](http://aly.mineadmin.com)

## 前端仓库地址
移步前端仓库

- [Github MineAdmin-Vue](https://github.com/mineadmin/MineAdmin-Vue)
- [Gitee MineAdmin-Vue](https://gitee.com/mineadmin/MineAdmin-vue)

## 官方交流群
> QQ群用于交流学习，请勿水群

<img src="https://svg.hamm.cn/badge.svg?key=QQ群&value=150105478" />

## 内置功能

1.  用户管理，完成用户添加、修改、删除配置，支持不同用户登录后台看到不同的首页
2.  部门管理，部门组织机构（公司、部门、小组），树结构展现支持数据权限
3.  岗位管理，可以给用户配置所担任职务
4.  角色管理，角色菜单权限分配、角色数据权限分配
5.  菜单管理，配置系统菜单和按钮等
6.  字典管理，对系统中经常使用并且固定的数据可以重复使用和维护
7.  系统配置，系统的一些常用设置管理
8.  操作日志，用户对系统的一些正常操作的查询
9.  登录日志，用户登录系统的记录查询
10. 在线用户，查看当前登录的用户
11. 服务监控，查看当前服务器状态和PHP环境等信息
12. 附件管理，管理当前系统上传的文件及图片等信息
13. 数据表维护，对系统的数据表可以进行清理碎片和优化
14. 模块管理，管理系统当前所有模块
15. 定时任务，在线（添加、修改、删除)任务调度包含执行结果日志
16. 代码生成，前后端代码的生成（php、vue、js、sql），支持下载和生成到模块
17. 缓存监控，查看Redis信息和系统所使用key的信息
18. API管理，对应用和接口管理、接口授权等功能。接口文档自动生成，输入、输出参数检查等
19. 队列管理，消息队列管理功能、消息管理、消息发送。使用ws方式即时消息提醒（需安装rabbitMQ）
20. 应用市场，可下载各种基础应用、插件、前端组件等等（开发中...）

## 环境需求

- Swoole >= 5.0 并关闭 `Short Name`
- PHP >= 8.1 并开启以下扩展：
  - mbstring
  - json
  - pdo
  - openssl
  - redis
  - pcntl
- [x] Mysql >= 5.7
- [x] Pgsql >= 10
- [x] Sql Server Latest
- Sqlsrv is Latest
- Redis >= 4.0
- Git >= 2.x


## 下载项目
- MineAdmin没有使用SQL文件导入安装，系统使用Migrates迁移文件形式安装和填充数据，请知悉。

- 项目下载，请确保已经安装了 `Composer`
```shell
composer create-project mineadmin/mineadmin --keep-vcs
```

## 项目安装

配置 `.env` 填写 `redis` `db` 相关信息，保存关闭。

打开终端，执行安装命令，执行Migrates数据迁移文件和SQL数据填充，完成安装。
```shell
php bin/hyperf.php mine:install
```

[点这里 -> 查看常见问题](https://doc.mineadmin.com/faqs/)

## 免责声明
[《免责声明》](https://doc.mineadmin.com/guide/start/declaration.html)

使用本软件不得用于开发违反国家有关政策的相关软件和应用，若因使用本软件造成的一切法律责任均与 `MineAdmin` 无关

## 体验地址

[体验地址](https://demo.mineadmin.com)
- 账号：superAdmin
- 密码：admin123

> 请勿添加脏数据

## 鸣谢

> 以下排名不分先后

[Hyperf 一款高性能企业级协程框架](https://hyperf.io/)

[Arco 字节跳动出品的企业级设计系统](https://arco.design/)

[Swoole PHP协程框架](https://www.swoole.com)

[Vue](https://vuejs.org/)

[Vite](https://vitejs.cn/)

[Jetbrains 生产力工具](https://www.jetbrains.com/)

## 通过 OSCS 安全认证
[![OSCS Status](https://www.oscs1024.com/platform/badge/kanyxmo/MineAdmin.svg?size=large)](https://www.murphysec.com/dr/9ztZvuSN6OLFjCDGVo)

## star 趋势

[![Stargazers over time](https://starchart.cc/mineadmin/mineadmin.svg)](https://starchart.cc/mineadmin/mineadmin.svg)

## 贡献者

> 感谢所有参与 MineAdmin 开发的代码贡献者。 [[contributors](https://github.com/mineadmin/minedmin/graphs/contributors)]
<a href="https://github.com/mineadmin/mineadmin/graphs/contributors">
<img src="https://contrib.rocks/image?repo=mineadmin/mineadmin" />
</a>

[![贡献者趋势](https://contributor-overtime-api.apiseven.com/contributors-svg?chart=contributorOverTime&repo=mineadmin/mineadmin)](https://www.apiseven.com/en/contributor-graph?chart=contributorOverTime&repo=mineadmin/mineadmin)

## 演示图片
<img src="https://s1.ax1x.com/2022/07/31/vklKzR.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vkl8eK.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vkl1L6.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vklNJH.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vklJoD.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vkllsx.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vklZoF.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vklUWd.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vkl0yt.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vkltFe.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vkluW9.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vklnJJ.jpg" />
<img src="https://s1.ax1x.com/2022/07/31/vklmi4.jpg" />
