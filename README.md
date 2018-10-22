# Laravel 学习图谱 [官网](https://laravel.com/)

[![知识共享协议（CC协议）](https://img.shields.io/badge/License-Creative%20Commons-DC3D24.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.zh)
[![GitHub stars](https://img.shields.io/github/stars/fanly/laravel-awesome.svg?style=flat&label=Star)](https://github.com/fanly/laravel-awesome/stargazers)
[![GitHub forks](https://img.shields.io/github/forks/fanly/laravel-awesome.svg?style=flat&label=Fork)](https://github.com/fanly/laravel-awesome/fork)
[![GitHub watchers](https://img.shields.io/github/watchers/fanly/laravel-awesome.svg?style=flat&label=Watch)](https://github.com/fanly/laravel-awesome/watchers)

**最后更新于20181019**
> 主要推荐：[fatedier/frp](https://github.com/fatedier/frp)，一个可用于内网穿透的高性能的反向代理应用，支持 tcp, udp, http, https 协议。

* [核心概念](https://github.com/fanly/laravel-awesome/blob/master/README.md#核心概念)
* [插件推荐](https://github.com/fanly/laravel-awesome/blob/master/README.md#插件推荐)
* [图书推荐](https://github.com/fanly/laravel-awesome/blob/master/README.md#图书推荐)
* [工具推荐](https://github.com/fanly/laravel-awesome/blob/master/README.md#工具推荐)
* [教程推荐](https://github.com/fanly/laravel-awesome/blob/master/README.md#教程推荐)
* [最佳实践](https://github.com/fanly/laravel-awesome/blob/master/README.md#最佳实践)
* [开源项目](https://github.com/fanly/laravel-awesome/blob/master/README.md#开源项目)
* [社区](https://github.com/fanly/laravel-awesome/blob/master/README.md#社区)
* [周边](https://github.com/fanly/laravel-awesome/blob/master/README.md#周边)


## 欢迎提交经典内容

欢迎提交 Pull Request, 或者 Github上面提交 Issue， 贴上您觉得 Laravel  相关内容 PPT/PDF 或者网页 URL 等。


## 核心概念

* [Laravel 服务容器介绍](https://www.insp.top/article/learn-laravel-container)，虽然文章有点老，但老而弥坚，从浅入深的分析和讲解，推荐看看 :star::star::star::star::star:
* [看 Lumen 源代码解析 Request 到 Response 过程](https://mp.weixin.qq.com/s/lWuVBW4lMOeQHs7FD-fDDQ) :star::star::star::star:

## 插件推荐

* :100: [EasyWeChat](https://www.easywechat.com/) 微信开发，从未如此简单。每一个功能设计，都经过精心打磨，只为了提供更好的开发体验。在国内的 Laravel 开源插件中，这个质量 No.1 :star::star::star::star::star:
* :100: [nikic/FastRoute](https://github.com/nikic/FastRoute) This library provides a fast implementation of a regular expression based router. Lumen 御用 Router。[![GitHub stars](https://img.shields.io/github/stars/nikic/FastRoute.svg?style=flat&label=Star)](https://github.com/nikic/FastRoute/stargazers)
* [barryvdh/laravel-ide-helper](https://github.com/barryvdh/laravel-ide-helper)  估计这个是开发 Laravel 项目的标配工具了吧。[![GitHub stars](https://img.shields.io/github/stars/barryvdh/laravel-ide-helper.svg?style=flat&label=Star)](https://github.com/barryvdh/laravel-ide-helper/stargazers)
* [barryvdh/laravel-debugbar](https://github.com/barryvdh/laravel-debugbar) 对 Laravel 开发者而言，Barry vd. Heuvel 发布的 Laravel Debugbar 是值得拥有的调试和追溯工具。它功能强大，安装便易。可以将应用程序中所发生的事情一览无余：经过的路由和控制器，数据库查询和执行时间，数据展示，异常，查看执行内容和执行过程时间线等等。尝试过使用这个包后，你将在之后的 Laravel 应用开发中对它爱不释手。[![GitHub stars](https://img.shields.io/github/stars/barryvdh/laravel-debugbar.svg?style=flat&label=Star)](https://github.com/barryvdh/laravel-debugbar/stargazers)
* [briannesbitt/Carbon](https://github.com/briannesbitt/Carbon) 时间处理器，我只认准这一家。[![GitHub stars](https://img.shields.io/github/stars/briannesbitt/Carbon.svg?style=flat&label=Star)](https://github.com/briannesbitt/Carbon/stargazers)
* [jenssegers/date](https://github.com/jenssegers/date) 日期处理工具（让 Carbon 支持多语言，中文用户的福音）[![GitHub stars](https://img.shields.io/github/stars/jenssegers/date.svg?style=flat&label=Star)](https://github.com/jenssegers/date/stargazers)
* [laravel-admin](http://laravel-admin.org/docs/#/zh/) 是一个可以快速帮你构建后台管理的工具，它提供的页面组件和表单元素等功能，能帮助你使用很少的代码就实现功能完善的后台管理功能。美中不足的就是怎么做 test？:star::star::star::star:
* [Guzzle](http://guzzle-cn.readthedocs.io/zh_CN/latest/quickstart.html) 网络请求，我推荐这个，好用。:star::star::star::star::star:
* [Faker](https://github.com/fzaninotto/Faker) 用于生成假数据的 PHP 类库。[![GitHub stars](https://img.shields.io/github/stars/fzaninotto/Faker.svg?style=flat&label=Star)](https://github.com/fzaninotto/Faker/stargazers)
* [Intervention/image](https://github.com/Intervention/image) Intervention Image is a PHP image handling and manipulation library providing an easier and expressive way to create, edit, and compose images. The package includes ServiceProviders and Facades for easy Laravel integration. 图片处理插件，我推荐用这个 [![GitHub stars](https://img.shields.io/github/stars/Intervention/image.svg?style=flat&label=Star)](https://github.com/Intervention/image/stargazers)
* [vinkla/laravel-hashids](https://github.com/vinkla/laravel-hashids) Hash ID 生成器，主要是用于生成相同的位数的 id，很有用，并且可以隐藏真正的表 id 值。[![GitHub stars](https://img.shields.io/github/stars/vinkla/laravel-hashids.svg?style=flat&label=Star)](https://github.com/vinkla/laravel-hashids/stargazers)
* [webpatser/laravel-uuid](https://github.com/webpatser/laravel-uuid) Laravel package to generate and to validate a UUID according to the RFC 4122 standard. [![GitHub stars](https://img.shields.io/github/stars/webpatser/laravel-uuid.svg?style=flat&label=Star)](https://github.com/webpatser/laravel-uuid/stargazers)
* 9️⃣0️⃣ [tightenco/collect](https://github.com/tightenco/collect) Import Laravel's Collections into non-Laravel packages easily, without needing to require the entire Illuminate\Support package. 刚好推荐的书《Refactoring to Collections》见：[图书推荐](https://github.com/fanly/laravel-awesome/blob/master/README.md#图书推荐)
* [spatie/laravel-activitylog](https://github.com/spatie/laravel-activitylog) 很多系统想记录用户的所有活跃记录。这个包可以很方便的记录你的用户何时何地的创建、更新实体的记录。:star::star::star:
* [medz/id-card-of-china](https://github.com/medz/id-card-of-china) 一个基于「公民身份号码」规则获取身份证号码中包含的基础信息组件（PHP）
* [ofcold/identity-card](https://github.com/ofcold/identity-card) A simple proof of identity card of the people's Republic of China. 其实这两个方法哪个好，哪个不好，没具体研究，但分享这两个的理由是：对国内独有的身份证验证做开发，是一件有意思的事情。
* [thephpleague/pipeline](https://github.com/thephpleague/pipeline) The pipeline pattern allows you to easily compose sequential stages by chaining stages. 源码分析可以看这篇文章：[推荐一个 PHP 管道插件 League\Pipeline](https://mp.weixin.qq.com/s/S02vFytG9fM98CoKTaH3HQ) [![GitHub stars](https://img.shields.io/github/stars/thephpleague/pipeline.svg?style=flat&label=Star)](https://github.com/thephpleague/pipeline/stargazers)
* [irazasyed/telegram-bot-sdk](https://github.com/irazasyed/telegram-bot-sdk) 🤖 Telegram Bot API PHP SDK. Lets you build Telegram Bots easily! Supports Laravel out of the box. [https://telegram-bot-sdk.readme.io/docs](https://telegram-bot-sdk.readme.io/docs)，刚好最近在做一个发送 Ebook 到 Kindle 的 Telegram Bot 工具，推荐使用这个。[![GitHub stars](https://img.shields.io/github/stars/irazasyed/telegram-bot-sdk.svg?style=flat&label=Star)](https://github.com/irazasyed/telegram-bot-sdk/stargazers)
* [Maatwebsite/Laravel-Excel](https://github.com/Maatwebsite/Laravel-Excel) 🚀 Supercharged Excel exports in Laravel，要操作 Excel，推荐这个工具了。具体文档看这里 [ https://laravel-excel.maatwebsite.nl/ ]( https://laravel-excel.maatwebsite.nl/ )。[![GitHub stars](https://img.shields.io/github/stars/Maatwebsite/Laravel-Excel.svg?style=flat&label=Star)](https://github.com/Maatwebsite/Laravel-Excel/stargazers)


## 图书推荐

* :100: [Refactoring to Collections/](https://adamwathan.me/refactoring-to-collections/) Never write another loop again. :star::star::star::star::star:
* [Laravel Collections Unraveled](https://leanpub.com/laravelcollectionsunraveled) Wondering why everyone keeps tweeting about "Amazing Laravel Collections!" Tired of reading about the function you could have used? "Laravel Collections Unraveled" is for you! Updated to cover Version 5.4. :star::star::star::star:
* [Building a Chatbot with Laravel and BotMan](https://laravel-news.com/chatbot) Learn how to build a chatbot from scratch using the framework you already know. 简短的一本书，学到的东西不少。:star::star::star:
* [rollbar](https://rollbar.com/) 异常监控系统，快速引入项目，实时反馈异常情况，可惜就是需要 money。:star::star::star:

## 工具推荐

* :100: [laradock/laradock](https://github.com/laradock/laradock) 利用 Docker 搭建开发环境，已经成为开发者必备技能了，「laradock」是首选，所以 Laravel 开发者，不知道这个，好像说不过去了。[![GitHub stars](https://img.shields.io/github/stars/laradock/laradock.svg?style=flat&label=Star)](https://github.com/laradock/laradock/stargazers)
* :100: [squizlabs/PHP_CodeSniffer](https://github.com/squizlabs/PHP_CodeSniffer) 每个公司都会有一套大家遵循的代码编写规范标准，这时候再辅于工具，那就完美了，所以推荐这个工具，几个主流的编辑器都支持。 [![GitHub stars](https://img.shields.io/github/stars/squizlabs/PHP_CodeSniffer.svg?style=flat&label=Star)](https://github.com/squizlabs/PHP_CodeSniffer/stargazers)
* :100: [fatedier/frp](https://github.com/fatedier/frp) A fast reverse proxy to help you expose a local server behind a NAT or firewall to the internet. frp 是一个可用于内网穿透的高性能的反向代理应用，支持 tcp, udp, http, https 协议。使用过花生壳、ngrok后，还是觉得这个好，对于需要内网联调微信开发功能，这个值得推荐使用。中文版使用说明：[看这里](https://github.com/fatedier/frp/blob/master/README_zh.md)。[![GitHub stars](https://img.shields.io/github/stars/fatedier/frp.svg?style=flat&label=Star)](https://github.com/fatedier/frp/stargazers)
* [phubb - PHP PubSubHubbub server](http://phubb.cweiske.de/) 自建 RSS 实时推送功能，这个工具强烈推荐。:star::star::star::star:
* [Travis-CI](https://travis-ci.org/) 如果你是用 Github 作为代码托管平台，那使用 Travis-CI 在线持续集成服务，自动化执行单元测试，或者部署任务等。:star::star::star::star:
* [rakyll/hey](https://github.com/rakyll/hey) 压测工具推荐一个，网友说：“用 ab 的话，有个小坑，如果测试的目标 Laravel 站点带 https，Requests per second 会永远保持在 15 左右 , 一度以为所有的优化策略都无效。。。”[![GitHub stars](https://img.shields.io/github/stars/rakyll/hey.svg?style=flat&label=Star)](https://github.com/rakyll/hey)
* [PHP Coding Standards Fixer](http://cs.sensiolabs.org/) 代码自动格式化工具，推荐试试这个工具。:star::star::star::star:
* [swooletw/laravel-swoole](https://github.com/swooletw/laravel-swoole) 使用 Swoole 来加速你的 Laravel 应用 :star::star::star::star:
* [Laragon](https://forum.laragon.org/topic/473/download-laragon)推荐的 Windows Laravel 集成环境，Windows 的朋友可以试试。:star::star::star:
* [Consul](https://www.consul.io/) Service Mesh Made Easy. Consul is a distributed service mesh to connect, secure, and configure services across any runtime platform and public or private cloud. 用 Consul 管理 Laravel 项目配置是个不错的选择。:star::star::star:
* [A modern backup solution for Laravel apps](https://github.com/spatie/laravel-backup) This Laravel package creates a backup of your application. The backup is a zipfile that contains all files in the directories you specify along with a dump of your database. The backup can be stored on any of the filesystems you have configured in Laravel 5. [![GitHub stars](https://img.shields.io/github/stars/spatie/laravel-backup.svg?style=flat&label=Star)](https://github.com/spatie/laravel-backup/stargazers)
* [getsentry/onpremise](https://github.com/getsentry/onpremise) Official bootstrap for running your own Sentry with Docker. 具体使用可以查看这篇文章 [利用 entry/onpremise 搭建一个 Sentry 异常汇总工具](https://mp.weixin.qq.com/s/wxVHXlloh8SSf5v8I7stJg) [![GitHub stars](https://img.shields.io/github/stars/getsentry/onpremise.svg?style=flat&label=Star)](https://github.com/getsentry/onpremise/stargazers)
* [Neilpang/acme.sh](https://github.com/Neilpang/acme.sh) 使用了很多提供商的免费证书，也尝试使用其他工具一键生成，但感觉不如这个来的好用，所以推荐给大家。[![GitHub stars](https://img.shields.io/github/stars/Neilpang/acme.sh.svg?style=flat&label=Star)](https://github.com/Neilpang/acme.sh/stargazers)
* [drone/drone](https://github.com/drone/drone). Drone is a Continuous Delivery platform built on Docker, written in Go [https://drone.io](https://drone.io)。和 `Jenkins` 相比，我更推荐小团队或者个人使用 `Drone`。[![GitHub stars](https://img.shields.io/github/stars/drone/drone.svg?style=flat&label=Star)](https://github.com/drone/drone/stargazers)

## 教程推荐

* [2017 版 Laravel 系列入门教程](https://github.com/johnlui/Learn-Laravel-5/) 关注 @johnlui 作者很久了，跟着他，学了不少东西，推荐初学者看看。:star::star::star::star:
* [Building a Vue SPA with Laravel](https://laravel-news.com/using-vue-router-laravel) Laravel + vue 这是目前「全栈」的标配。:star::star::star::star:
* [Laravel 深入浅出指南](https://github.com/xiaohuilam/laravel/wiki) Laravel 5.7 源代码解析，新手进阶指南。进阶版。

## 最佳实践

* [alexeymezenin/laravel-best-practices](https://github.com/alexeymezenin/laravel-best-practices). It's not a Laravel adaptation of SOLID principles, patterns etc. Here you'll find the best practices which are usually ignored in real life Laravel projects. [![GitHub stars](https://img.shields.io/github/stars/alexeymezenin/laravel-best-practices.svg?style=flat&label=Star)](https://github.com/alexeymezenin/laravel-best-practices/stargazers)
* 「翻译版看这个」[Laravel 的十八个最佳实践](https://laravel-china.org/articles/12762/eighteen-best-practices-of-laravel)

## 开源项目

* :100: [summerblue/laravel-shop](https://github.com/summerblue/laravel-shop) Laravel 电商实战教程的项目代码。Summer 推荐错不了。[![GitHub stars](https://img.shields.io/github/stars/summerblue/laravel-shop.svg?style=flat&label=Star)](https://github.com/summerblue/laravel-shop/stargazers)
* :100: [laravel/horizon](https://github.com/laravel/horizon) Horizon is developed by the core developers of the Laravel framework and provides a robust queue monitoring solution for Laravel's Redis queue. Horizon allows you to easily monitor key metrics of your queue system such as job throughput, runtime, and job failures.  [![GitHub stars](https://img.shields.io/github/stars/laravel/horizon.svg?style=flat&label=Star)](https://github.com/laravel/horizon/stargazers)
* [octobercms/october](http://octobercms.com/) Free, open-source, self-hosted CMS platform based on the Laravel PHP Framework. 值得一用，而且作者来头不小哦。:star::star::star::star::star:
* [jcc/blog](https://github.com/jcc/blog/) 🌟 这是一个由 Laravel 5.* 和 Vuejs 2.* 建立的开源博客系统。「PJ Blog is an open source blog built with Laravel and Vue.js.」 [![GitHub stars](https://img.shields.io/github/stars/jcc/blog.svg?style=flat&label=Star)](https://github.com/jcc/blog/stargazers)
* [caoym/phpboot](https://github.com/caoym/phpboot) 是为快速开发 微服务 / RESTful API 设计的PHP 框架。它可以帮助开发者更聚焦在业务本身, 而将原来开发中不得不做, 但又重复枯燥的事情丢给框架, 比如编写接口文档、参数校验和远程调用代码等。本人也再考虑是否做一款 PHP 框架，这个值得使用和参考。[中文说明](http://phpboot.org/zh/latest/)。[![GitHub stars](https://img.shields.io/github/stars/caoym/phpboot.svg?style=flat&label=Star)](https://github.com/caoym/phpboot/stargazers)
* [leocavalcante/siler](https://github.com/leocavalcante/siler) Siler is a PHP library powered with high-level abstractions to work with GraphQL. [使用文档可以看这里](https://siler.leocavalcante.com/) [![GitHub stars](https://img.shields.io/github/stars/leocavalcante/siler.svg?style=flat&label=Star)](https://github.com/leocavalcante/siler/stargazers)
* [https://github.com/Qsnh/meedu](https://github.com/Qsnh/meedu) 基于Laravel开发的在线点播系统。 https://meedu.app [![GitHub stars](https://img.shields.io/github/stars/Qsnh/meedu.svg?style=flat&label=Star)](https://github.com/Qsnh/meedu/stargazers)


## 社区

**国内：**

* :100: [LaravelChina](https://laravel-china.org/)
	 学习 Laravel，不知道这个网站，那就没法混了。:star::star::star::star::star:
* [Laravel 学院](http://laravelacademy.org) 上面不仅有各版本文档，还有很多不错的文章，和开源项目值得学习
  ​    

    
**国外：**

* [The League of Extraordinary Packages](http://thephpleague.com/) The League of Extraordinary Packages is a group of developers who have banded together to build solid, well tested PHP packages using modern coding standards. 高质量 packages 聚集地，强烈推荐大家看看 :star::star::star::star::star:
* [Laravel News](https://laravel-news.com/) The official Laravel news source. :star::star::star::star:
* [laracasts](https://laracasts.com/) The best PHP and Laravel screencasts on the web. 对于企业，推荐买一个账号供技术人员学习使用，确实不错。当然，个人买有点小贵。:star::star::star::star:

## 周边

> 我们除了要掌握核心技术外，对于周边的知识和工具，我们也要学习，所以也搜集了一些我经常使用和学习的高质量信息

* [geeeeeeeeek/git-recipes](https://github.com/geeeeeeeeek/git-recipes) Git recipes in Chinese by Zhongyi Tong. 高质量的 Git 中文教程. [文档也可以看这里](https://github.com/geeeeeeeeek/git-recipes/wiki) [![GitHub stars](https://img.shields.io/github/stars/geeeeeeeeek/git-recipes.svg?style=flat&label=Star)](https://github.com/geeeeeeeeek/git-recipes/stargazers)

## 关于我

- 加入「圈子」我们一起升级打怪

<img src="http://ow20g4tgj.bkt.clouddn.com/2018-06-21-15295424612882.jpg" height="400">


- 加我微信(**yemeishu**) or 如果觉得对你有用，不妨请我喝杯:coffee:~。

<img src="http://ow20g4tgj.bkt.clouddn.com/2018-05-07-15256949976757.jpg" height="400"><img src="http://ow20g4tgj.bkt.clouddn.com/2018-05-07-15256953039020.jpg" height="400">

