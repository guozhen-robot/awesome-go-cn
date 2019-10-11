# Awesome Go

[Awesome]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.4.1/docs/awesome.svg "star > 2000"
[Green]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Green.svg "最近一周有更新"
[Yellow]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Yellow.svg "最近一年没有更新"
[CN]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Cn.svg "包含中文文档"
[Archived]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.2.1/docs/archived.svg "项目已归档"
[GoDoc]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.3.0/docs/DOC.svg "godoc文档地址"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2019-10-11 10:27:41(每隔1天同步一次)**

[![chinese](https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.3.0/docs/english.svg)](README_EN.md) [![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) 为Awesome Go打赏~

精选了一系列很棒的Go框架、库和软件。灵感来自于[awesome-python](https://github.com/vinta/awesome-python)。

**小图标说明** :


小图标 | 说明  
:-:|-
![awesome][Awesome] | star > 2000
![最近一个周有更新][Green] | 最近一周有更新。可以基本判断当前库处于积极维护状态。
![最近一年未更新][Yellow] | 最近一年没有更新。反应了此库的维护积极性不高，使用时需谨慎。
![归档项目][Archived] | 此项目已归档，不再更新，使用时需谨慎。
![此项目有中文文档][CN] | 此项目有中文文档。
![godoc文档][GoDoc] | godoc文档地址。

### 说明

[中文](README.md)  | [English](README_EN.md) 
 

### 贡献

你可以快速浏览贡献者名单[contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md). 感谢所有为此项目付出的同学[contributors](https://github.com/avelino/awesome-go/graphs/contributors); 你真棒!

如果您在看到一个包或项目不再维护或不适合，请往awesome-go提交[Pull Request](https://github.com/avelino/awesome-go/pulls)，本项目每隔一天与英文文档同步。感谢!

### 内容

- [Awesome Go](#awesome-go)
    - [音频和音乐](#音频和音乐)
    - [身份验证和OAuth](#身份验证和oauth)
    - [Bot建设](#bot建设)
    - [命令行](#命令行)
    - [配置](#配置)
    - [持续集成](#持续集成)
    - [CSS预处理器](#css预处理器)
    - [数据结构](#数据结构)
    - [数据库](#数据库)
    - [数据库驱动程序](#数据库驱动程序)
    - [日期和时间](#日期和时间)
    - [分布式系统](#分布式系统)
    - [电子邮件](#电子邮件)
    - [可嵌入的脚本语言](#可嵌入的脚本语言)
    - [错误处理](#错误处理)
    - [文件](#文件)
    - [金融](#金融)
    - [表单](#表单)
    - [方法](#方法)
    - [游戏开发](#游戏开发)
    - [代码生成与泛型](#代码生成与泛型)
    - [地理](#地理)
    - [Go 编译器](#go-编译器)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [硬件](#硬件)
    - [图片](#图片)
    - [物联网](#物联网)
    - [作业调度器](#作业调度器)
    - [JSON](#json)
    - [日志记录](#日志记录)
    - [机器学习](#机器学习)
    - [消息](#消息)
    - [微软办公软件](#微软办公软件)
        - [Microsoft Excel](#microsoft-excel)
    - [杂项](#杂项)
        - [依赖注入](#依赖注入)
        - [项目布局](#项目布局)
        - [字符串](#字符串)
    - [自然语言处理](#自然语言处理)
    - [网络](#网络)
        - [HTTP客户端](#http客户端)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [包管理](#包管理)
    - [性能](#性能)
    - [查询语言](#查询语言)
    - [嵌入的资源](#嵌入的资源)
    - [科学与数据分析](#科学与数据分析)
    - [安全](#安全)
    - [序列化](#序列化)
    - [服务器应用程序](#服务器应用程序)
    - [流处理](#流处理)
    - [模板引擎](#模板引擎)
    - [测试](#测试)
    - [文本处理](#文本处理)
    - [Third-party APIs](#third-party-apis)
    - [公用事业公司](#公用事业公司)
    - [UUID](#uuid)
    - [验证](#验证)
    - [版本控制](#版本控制)
    - [视频](#视频)
    - [Web框架](#web框架)
        - [中间件](#中间件)
            - [仿真中间件](#仿真中间件)
            - [用于创建HTTP中间件的库](#用于创建http中间件的库)
        - [路由器](#路由器)
    - [Windows](#windows)
    - [XML](#xml)

- [工具](#工具)
    - [代码分析](#代码分析)
    - [编辑器插件](#编辑器插件)
    - [Go 生成工具](#go-生成工具)
    - [Go 工具](#go-工具)
    - [软件包](#软件包)
        - [DevOps 工具](#devops-工具)
        - [其他软件](#其他软件)

- [资源](#资源)
    - [基准](#基准)
    - [会议](#会议)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [聚会](#聚会)
    - [Twitter](#twitter)
    - [网站](#网站)
        - [教程](#教程)

## 音频和音乐

*用于操作音频的库。 (翻译出错了? 试试 [英文版](README_EN.md#audio-and-music) 吧~)*

* [Oto](https://github.com/hajimehoshi/oto) **star:458** 多平台的 low-level 声音播放库。   [![godoc][GoDoc]](https://godoc.org/github.com/hajimehoshi/oto)
* [PortAudio](https://github.com/gordonklaus/portaudio) **star:312** 基于 Go 的PortAudio audio I/O库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/gordonklaus/portaudio)
* [waveform](https://github.com/mdlayher/waveform) **star:259** 通过音频流生成波形图像的包。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mdlayher/waveform)
* [music-theory](https://github.com/go-music-theory/music-theory) **star:259** 基于 Go 的音乐理论模型。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-music-theory/music-theory)
* [portmidi](https://github.com/rakyll/portmidi) **star:211** PortMidi的 Go 语言实现接口.   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/rakyll/portmidi)
* [id3v2](https://github.com/bogem/id3v2) **star:116** 快速稳定的 ID3 解析及写入Go库。   [![godoc][GoDoc]](https://godoc.org/github.com/bogem/id3v2)
* [flac](https://github.com/mewkiz/flac) **star:104** 原生 Go FLAC编码器/解码器，支持FLAC流。   [![godoc][GoDoc]](https://godoc.org/github.com/mewkiz/flac)
* [mix](https://github.com/go-mix/mix) **star:99** 基于序列的 Go 原生音乐混音器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-mix/mix)
* [mp3](https://github.com/tcolgate/mp3) **star:98** 原生 Go MP3解码器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tcolgate/mp3)
* [go-sox](https://github.com/krig/go-sox) **star:94** libsox 的 Go 语言实现接口。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/krig/go-sox)
* [flac](https://github.com/eaburns/flac) **star:85** 原生 Go FLAC解码器，将FLAC文件解码为字节片。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/eaburns/flac)
* [malgo](https://github.com/gen2brain/malgo) **star:79** 迷你音频库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gen2brain/malgo)
* [taglib](https://github.com/wtolson/go-taglib) **star:69** taglib 的 Go 语言实现接口.   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/wtolson/go-taglib)
* [gaad](https://github.com/Comcast/gaad) **star:58** 原生 Go AAC位流解析器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/Comcast/gaad)
* [minimp3](https://github.com/tosone/minimp3) **star:29** 轻量级MP3解码器库。
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) **star:26** libmediainfo 的 Go 语言实现接口。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zhulik/go_mediainfo)
* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) **star:23** EasyMidi是一个简单可靠的库，用于处理标准midi文件(SMF)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/algoGuy/EasyMIDI)
* [vorbis](https://github.com/mccoyst/vorbis) **star:22** “原生” Go Vorbis解码器(使用CGO，但没有依赖关系)。   [![godoc][GoDoc]](https://godoc.org/github.com/mccoyst/vorbis)
* [gosamplerate](https://github.com/dh1tw/gosamplerate) **star:8** libsamplerate 的 Go 语言实现接口。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dh1tw/gosamplerate)

## 身份验证和OAuth

*用于实现验证方案的库。 (翻译出错了? 试试 [英文版](README_EN.md#authentication-and-oauth) 吧~)*

* [jwt-go](https://github.com/dgrijalva/jwt-go) **star:6343** JSON Web令牌(JWT)。   [![star > 2000][Awesome]](https://github.com/dgrijalva/jwt-go)   [![godoc][GoDoc]](https://godoc.org/github.com/dgrijalva/jwt-go)
* [casbin](https://github.com/hsluoyz/casbin) **star:5327** 支持ACL、RBAC、ABAC等访问控制模型的授权库。   [![star > 2000][Awesome]](https://github.com/hsluoyz/casbin)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/hsluoyz/casbin)
* [oauth2](https://github.com/golang/oauth2) **star:2482** goauth2的继任者。通用OAuth 2.0包，附带JWT、谷歌api、计算引擎和应用程序引擎支持。   [![star > 2000][Awesome]](https://github.com/golang/oauth2)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/golang/oauth2)
* [goth](https://github.com/markbates/goth) **star:2354** 提供了 OAuth 和 OAuth2 的简单清晰易用的方法。可开箱即用处理多个提供程序。   [![star > 2000][Awesome]](https://github.com/markbates/goth)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/markbates/goth)
* [authboss](https://github.com/volatiletech/authboss) **star:1997** web模块化认证系统。它试图删除尽可能多的模板文件和硬编码，以便每次新建一个新的web项目时，您都可以插入、配置并开始构建您的应用程序，而不必每次都构建一个身份验证系统。   [![godoc][GoDoc]](https://godoc.org/github.com/volatiletech/authboss)
* [osin](https://github.com/openshift/osin) **star:1554** OAuth2服务器库。   [![godoc][GoDoc]](https://godoc.org/github.com/openshift/osin)
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) **star:1331** 用 Golang 编写的独立且符合规范的OAuth2服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/go-oauth2-server)
* [go-jose](https://github.com/square/go-jose) **star:1174** 相当完整地实现了JOSE工作组的JSON Web令牌、JSON Web签名和JSON Web加密规范。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/square/go-jose)
* [gologin](https://github.com/dghubble/gologin) **star:1089** 用于使用OAuth1和OAuth2身份验证提供者登录的可链处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/dghubble/gologin)
* [gorbac](https://github.com/mikespook/gorbac) **star:940** 轻量级的基于角色的访问控制(RBAC)实现。   [![godoc][GoDoc]](https://godoc.org/github.com/mikespook/gorbac)
* [loginsrv](https://github.com/tarent/loginsrv) **star:839** JWT登录微服务带有可插拔的后端服务，如OAuth2 (Github)、htpasswd、osiam。   [![godoc][GoDoc]](https://godoc.org/github.com/tarent/loginsrv)
* [scs](https://github.com/alexedwards/scs) **star:606** HTTP服务器的会话管理器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/alexedwards/scs)
* [permissions2](https://github.com/xyproto/permissions2) **star:361** 用于跟踪用户、登录状态和权限的库。依赖于cookie安全和bcrypt。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/xyproto/permissions2)
* [paseto](https://github.com/o1egl/paseto) **star:248** 平台无关的安全令牌(PASETO)。   [![godoc][GoDoc]](https://godoc.org/github.com/o1egl/paseto)
* [httpauth](https://github.com/goji/httpauth) **star:187** HTTP身份验证中间件。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/goji/httpauth)
* [jeff](https://github.com/abraithwaite/jeff) **star:170** 简单、灵活、安全和惯用的web会话管理，具有可配置化的后端。   [![godoc][GoDoc]](https://godoc.org/github.com/abraithwaite/jeff)
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) **star:161** JWT中间件，可用于Golang http服务器，提供了许多配置选项。   [![godoc][GoDoc]](https://godoc.org/github.com/adam-hanna/jwt-auth)
* [jwt](https://github.com/pascaldekloe/jwt) **star:110** 轻量级JSON Web令牌库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/pascaldekloe/jwt)
* [session](https://github.com/icza/session) **star:92** web服务器会话管理(包括支持谷歌应用程序引擎 - GAE)。   [![godoc][GoDoc]](https://godoc.org/github.com/icza/session)
* [branca](https://github.com/hako/branca) **star:83** 基于 Go 实现Branca令牌。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/hako/branca)
* [jwt](https://github.com/robbert229/jwt) **star:75** 简单易用的JSON Web令牌实现(JWT)。   [![godoc][GoDoc]](https://godoc.org/github.com/robbert229/jwt)
* [sessions](https://github.com/adam-hanna/sessions) **star:47** 非常简单，高性能，可深度定制的会话服务，主要用于的 go http 服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/adam-hanna/sessions)
* [sjwt](https://github.com/brianvoe/sjwt) **star:38** 简单的jwt生成器和解析器。   [![godoc][GoDoc]](https://godoc.org/github.com/brianvoe/sjwt)
* [securecookie](https://github.com/chmike/securecookie) **star:34** 高效安全的cookie编码/解码。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/chmike/securecookie)
* [scope](https://github.com/SonicRoshan/scope)  在Go中轻松管理OAuth2范围。
* [rbac](https://github.com/zpatrick/rbac) **star:31** 最小的RBAC包。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zpatrick/rbac)
* [sessionup](https://github.com/swithek/sessionup) **star:26** 简单但有效的HTTP会话管理和标识包。   [![godoc][GoDoc]](https://godoc.org/github.com/swithek/sessionup)
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) **star:8** 使用SessionGate Redis模块进行会话管理。   [![godoc][GoDoc]](https://godoc.org/github.com/f0rmiga/sessiongate-go)
* [signedvalue](https://github.com/sashka/signedvalue) **star:8** 与[Tornado's](https://github.com/tornadooweb/tornado) 完全兼容的签名和时间戳字符串实现。   [![godoc][GoDoc]](https://godoc.org/github.com/sashka/signedvalue)
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) **star:2** 提供cookie .txt文件格式的解析器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mengzhuo/cookiestxt)

## Bot建设

*用于构建和使用机器人的库。 (翻译出错了? 试试 [英文版](README_EN.md#bot-building) 吧~)*

* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) **star:1726** 简单轻量级的Telegram bot客户端。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/Syfaro/telegram-bot-api)
* [telebot](https://github.com/tucnak/telebot) **star:986** 用Go编写的Telegram bot框架。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/tucnak/telebot)
* [go-chat-bot](https://github.com/go-chat-bot/bot) **star:495** 用 Go 编写的IRC, Slack和电报机器人。   [![godoc][GoDoc]](https://godoc.org/github.com/go-chat-bot/bot)
* [slacker](https://github.com/shomali11/slacker) **star:331** 可简单创建Slack机器人的框架。   [![godoc][GoDoc]](https://godoc.org/github.com/shomali11/slacker)
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) **star:242** 基于控制台的，用于加密货币交易所的的交易机器人。   [![godoc][GoDoc]](https://godoc.org/github.com/saniales/golang-crypto-trading-bot)
* [tbot](https://github.com/yanzay/tbot) **star:230** 带有类似于net/http API的Telegram bot服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/yanzay/tbot)
* [Kelp](https://github.com/stellar/kelp) **star:202** 官方交易和做市机器人为[Stellar](https://www.stellar.org/) DEX。开箱即用的作品，用 Golang 编写，兼容集中交易和定制交易策略。   [![godoc][GoDoc]](https://godoc.org/github.com/stellar/kelp)
* [Tenyks](https://github.com/kyleterry/tenyks) **star:168** 面向服务的IRC bot，使用Redis和JSON进行消息传递。   [![godoc][GoDoc]](https://godoc.org/github.com/kyleterry/tenyks)
* [go-sarah](https://github.com/oklahomer/go-sarah) **star:145** 此框架提供了聊天机器人相关的服务，包括LINE、Slack、Gitter等。   [![godoc][GoDoc]](https://godoc.org/github.com/oklahomer/go-sarah)
* [hanu](https://github.com/sbstjn/hanu) **star:112** 用于编写Slack机器人的框架。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sbstjn/hanu)
* [go-tgbot](https://github.com/olebedev/go-tgbot) **star:88** 由swagger文件、基于会话的路由器和中间件生成的纯Golang Telegram Bot API包装器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/go-tgbot)
* [margelet](https://github.com/zhulik/margelet) **star:60** 构建电报机器人的框架。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zhulik/margelet)
* [govkbot](https://github.com/nikepan/govkbot) **star:28** 简单的Go [VK](https://vk.com) bot库。   [![godoc][GoDoc]](https://godoc.org/github.com/nikepan/govkbot)
* [slackscot](https://github.com/alexandre-normand/slackscot) **star:15** 另一个构建Slack机器人的框架。   [![godoc][GoDoc]](https://godoc.org/github.com/alexandre-normand/slackscot)
* [micha](https://github.com/onrik/micha) **star:10** 基于 GO 实现的Telegram 机器人API库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/onrik/micha)

## 命令行

### 标准CLI

*用于构建标准或基本命令行应用程序的库。 (翻译出错了? 试试 [英文版](README_EN.md#standard-cli) 吧~)*

* [cobra](https://github.com/spf13/cobra) **star:14127** 现代Go CLI命令行交互工具。   [![star > 2000][Awesome]](https://github.com/spf13/cobra)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/cobra)
* [urfave/cli](https://github.com/urfave/cli) **star:12041** 可让你简单、快速和愉快的构建命令行应用(之前是codegangsta/cli)。   [![star > 2000][Awesome]](https://github.com/urfave/cli)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/urfave/cli)
* [kingpin](https://github.com/alecthomas/kingpin) **star:2656** 支持子命令的命令行和标志解析器。   [![star > 2000][Awesome]](https://github.com/alecthomas/kingpin)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/alecthomas/kingpin)
* [go-flags](https://github.com/jessevdk/go-flags) **star:1537**  Go 命令行选项解析器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jessevdk/go-flags)
* [readline](https://github.com/chzyer/readline) **star:1395** 纯golang实现，在MIT许可下提供了GNU-Readline的大部分特性。   [![godoc][GoDoc]](https://godoc.org/github.com/chzyer/readline)
* [docopt.go](https://github.com/docopt/docopt.go) **star:1189** 会让你满意的命令行参数解析器。   [![godoc][GoDoc]](https://godoc.org/github.com/docopt/docopt.go)
* [Dnote](https://github.com/dnote/dnote) **star:1134** 一个简单的端到端的加密笔记本程序。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/dnote/dnote)
* [mitchellh/cli](https://github.com/mitchellh/cli) **star:1019** 用于实现命令行接口的Go库。   [![godoc][GoDoc]](https://godoc.org/github.com/mitchellh/cli)
* [cli-init](https://github.com/tcnksm/gcli) **star:876** 一个简单就可开启构建Golang命令行的应用程序。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tcnksm/gcli)
* [climax](http://github.com/tucnak/climax)  Alternative CLI with "human face", in spirit of Go command.
* [pflag](https://github.com/spf13/pflag) **star:847** 基于POSIX/GNU-style --flags实现的包，主要用于替换Go的falg包。   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/pflag)
* [go-arg](https://github.com/alexflint/go-arg) **star:779** 基于结构的参数解析。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/alexflint/go-arg)
* [complete](https://github.com/posener/complete) **star:633** 使用 Go 语言编写的 bash 命令补全工具以及 Go 命令补全工具.   [![godoc][GoDoc]](https://godoc.org/github.com/posener/complete)
* [mow.cli](https://github.com/jawher/mow.cli) **star:625** 用于构建具有复杂标志和参数解析和验证的CLI应用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/jawher/mow.cli)
* [liner](https://github.com/peterh/liner) **star:599** 类似readline-like的命令行接口库。   [![godoc][GoDoc]](https://godoc.org/github.com/peterh/liner)
* [cli](https://github.com/mkideal/cli) **star:488** 基于golang结构标签，功能丰富易于使用的命令行包。   [![godoc][GoDoc]](https://godoc.org/github.com/mkideal/cli)
* [flaggy](https://github.com/integrii/flaggy) **star:463** 一个健壮的、易用的标志包，具有出色的子命令支持。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/integrii/flaggy)
* [ops](https://github.com/nanovms/ops) **star:283** Unikernel 构建器/协调器。   [![godoc][GoDoc]](https://godoc.org/github.com/nanovms/ops)
* [argparse](https://github.com/akamensky/argparse) **star:125** 命令行参数分析器，灵感来自Python的argparse模块。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/akamensky/argparse)
* [flag](https://github.com/cosiner/flag) **star:101** 简单但功能强大的命令行选项解析库，用于支持Go子命令。   [![godoc][GoDoc]](https://godoc.org/github.com/cosiner/flag)
* [ukautz/clif](https://github.com/ukautz/clif) **star:100** 简小的命令行接口框架。   [![godoc][GoDoc]](https://godoc.org/github.com/ukautz/clif)
* [sflags](https://github.com/octago/sflags) **star:96** 基于结构的flag生成器，用于flag、urfave/cli、pflag、cobra、kingpin和其他库。   [![godoc][GoDoc]](https://godoc.org/github.com/octago/sflags)
* [commandeer](https://github.com/jaffee/commandeer) **star:95** 开发友好的CLI应用程序。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jaffee/commandeer)
* [wmenu](https://github.com/dixonwille/wmenu) **star:91** 为cli程序提供了简单上手的菜单，可提示用户作出选择。   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/wmenu)
* [job](https://github.com/liujianping/job) **star:58** 工作，把你的短期指令当作长期任务。   [![godoc][GoDoc]](https://godoc.org/github.com/liujianping/job)
* [cli](https://github.com/teris-io/cli) **star:57** 为 Go 构建命令接口提供简单而完整的API。   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/cli)
* [env](https://github.com/codingconcepts/env) **star:42** 基于标记的结构化的环境配置。   [![godoc][GoDoc]](https://godoc.org/github.com/codingconcepts/env)
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli)  具有自动配置和依赖注入的cli应用程序框架。
* [gocmd](https://github.com/devfacet/gocmd) **star:36** 用于构建命令行应用程序。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/devfacet/gocmd)
* [wlog](https://github.com/dixonwille/wlog) **star:36** 支持跨平台和并发的简单日志记录接口。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/wlog)
* [flagvar](https://github.com/sgreben/flagvar) **star:31** 符合 Go 标准的“flag”标志参数类型包。   [![godoc][GoDoc]](https://godoc.org/github.com/sgreben/flagvar)
* [strumt](https://github.com/antham/strumt) **star:31** 用于创建提示链。   [![godoc][GoDoc]](https://godoc.org/github.com/antham/strumt)
* [cmdr](https://github.com/hedzr/cmdr) **star:21** 一个POSIX/GNU风格的、类似getopt的命令行UI Go库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/hedzr/cmdr)
* [argv](https://github.com/cosiner/argv) **star:18** 基于Base 语法，用于分隔命令行字符串并将其作为参数的 Go 语言库，   [![godoc][GoDoc]](https://godoc.org/github.com/cosiner/argv)
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) **star:16**  Go 选择解析器，借鉴于Perl灵活性的GetOpt::Long。   [![godoc][GoDoc]](https://godoc.org/github.com/DavidGamba/go-getoptions)
* [go-commander](https://github.com/yitsushi/go-commander) **star:15** 用于简化CLI工作流的 Go 库。   [![godoc][GoDoc]](https://godoc.org/github.com/yitsushi/go-commander)
* [sand](https://github.com/Zaba505/sand) **star:8** 用于创建解释器等的简单API。   [![godoc][GoDoc]](https://godoc.org/github.com/Zaba505/sand)
* [ts](https://github.com/liujianping/ts) **star:7** 时间戳转换和比较工具。   [![godoc][GoDoc]](https://godoc.org/github.com/liujianping/ts)

### 高级控制台用户界面

*用于构建控制台应用程序和控制台用户界面的库。 (翻译出错了? 试试 [英文版](README_EN.md#advanced-console-uis) 吧~)*

* [termui](https://github.com/gizak/termui) **star:9153** 此库是基于**termbox-go**实现的，借鉴于[blessed-contrib](https://github.com/yaronn/blessed-contrib)。   [![star > 2000][Awesome]](https://github.com/gizak/termui)   [![godoc][GoDoc]](https://godoc.org/github.com/gizak/termui)
* [gommon/color](https://github.com/labstack/gommon/tree/master/color)  更换终端文本样式。
* [gocui](https://github.com/jroimartin/gocui) **star:5598** 旨在创建控制台用户界面的极简Go库。   [![star > 2000][Awesome]](https://github.com/jroimartin/gocui)   [![godoc][GoDoc]](https://godoc.org/github.com/jroimartin/gocui)
* [termbox-go](https://github.com/nsf/termbox-go) **star:3534** 基于文本的跨平台接口库。   [![star > 2000][Awesome]](https://github.com/nsf/termbox-go)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/nsf/termbox-go)
* [color](https://github.com/fatih/color) **star:3096** 多功能包装，彩色终端输出。   [![star > 2000][Awesome]](https://github.com/fatih/color)   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/fatih/color)   ![归档项目][Archived]
* [go-prompt](https://github.com/c-bata/go-prompt) **star:2562** 构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)   [![star > 2000][Awesome]](https://github.com/c-bata/go-prompt)   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/go-prompt)
* [uiprogress](https://github.com/gosuri/uiprogress) **star:1574** 在终端呈现进度条，可灵活配置的。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uiprogress)
* [asciigraph](https://github.com/guptarohit/asciigraph) **star:1199** 在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/guptarohit/asciigraph)
* [uilive](https://github.com/gosuri/uilive) **star:991** 用于实时更新终端输出的库。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uilive)
* [termtables](https://github.com/apcera/termtables)  使用Ruby库[terminal-tables](https://github.com/tj/terminal-table)的端口生成简单的ASCII表，并提供标记和HTML输出。
* [termdash](https://github.com/mum4k/termdash) **star:849** 此库是基于**termbox-go**实现的，借鉴于[termui](https://github.com/gizak/termui)。   [![godoc][GoDoc]](https://godoc.org/github.com/mum4k/termdash)
* [mpb](https://github.com/vbauerster/mpb) **star:756** 可在终端显示多进度条。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/vbauerster/mpb)
* [aurora](https://github.com/logrusorgru/aurora) **star:680** 支持fmt.Printf/Sprintf的ANSI终端颜色。   [![godoc][GoDoc]](https://godoc.org/github.com/logrusorgru/aurora)
* [progressbar](https://github.com/schollz/progressbar) **star:678** 基本线程安全的进度条，在每个操作系统工作。   [![godoc][GoDoc]](https://godoc.org/github.com/schollz/progressbar)
* [uitable](https://github.com/gosuri/uitable) **star:512** 改善终端应用程序中表格数据的可读性。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uitable)
* [go-colorable](https://github.com/mattn/go-colorable) **star:391** 适用于windows的颜色编写器。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-colorable)
* [go-isatty](https://github.com/mattn/go-isatty) **star:360** Go 实现的 isatty。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-isatty)
* [chalk](https://github.com/ttacon/chalk) **star:314** 美化终端/控制台输出。   [![godoc][GoDoc]](https://godoc.org/github.com/ttacon/chalk)
* [tabby](https://github.com/cheynewallace/tabby) **star:253** 一个可在终端生成一个极简Golang表格轻量级库   [![godoc][GoDoc]](https://godoc.org/github.com/cheynewallace/tabby)
* [gookit/color](https://github.com/gookit/color) **star:236** 终端显色工具库，支持16种颜色，256种颜色，RGB显色输出，兼容Windows。   [![godoc][GoDoc]](https://godoc.org/github.com/gookit/color)   ![包含中文文档][CN]
* [go-colortext](https://github.com/daviddengcn/go-colortext) **star:197** 在终端中使用彩色文字。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/daviddengcn/go-colortext)
* [simpletable](https://github.com/alexeyco/simpletable) **star:173** 可在终端显示简易表格。   [![godoc][GoDoc]](https://godoc.org/github.com/alexeyco/simpletable)
* [cfmt](https://github.com/mingrammer/cfmt) **star:67** 提供上下文的fmt，灵感来自于bootstrap color classes。   [![godoc][GoDoc]](https://godoc.org/github.com/mingrammer/cfmt)
* [tabular](https://github.com/InVisionApp/tabular) **star:33** 不需要向API传递大量参数就可从命令行实用程序中打印ASCII表。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/tabular)
* [colourize](https://github.com/TreyBastian/colourize) **star:16** 在终端提供ANSI彩色文本。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/TreyBastian/colourize)
* [ctc](https://github.com/wzshiming/ctc) **star:10** 不需要Print方法的非侵入性跨平台终端颜色库。   [![godoc][GoDoc]](https://godoc.org/github.com/wzshiming/ctc)   ![包含中文文档][CN]
* [go-ataman](https://github.com/workanator/go-ataman) **star:8** 在终端提供ANSI彩色文本模板。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/workanator/go-ataman)

## 配置

*配置解析的库。 (翻译出错了? 试试 [英文版](README_EN.md#configuration) 吧~)*

* [viper](https://github.com/spf13/viper) **star:9888** 配置管理。   [![star > 2000][Awesome]](https://github.com/spf13/viper)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/viper)
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) **star:2501** 管理来自环境变量的配置数据。   [![star > 2000][Awesome]](https://github.com/kelseyhightower/envconfig)   [![godoc][GoDoc]](https://godoc.org/github.com/kelseyhightower/envconfig)
* [godotenv](https://github.com/joho/godotenv) **star:2280** Ruby 的 dotenv 库的 Go移植版(从.env文件加载环境变量)。   [![star > 2000][Awesome]](https://github.com/joho/godotenv)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/joho/godotenv)
* [ini](https://github.com/go-ini/ini) **star:1674**  读和写INI文件。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-ini/ini)
* [env](https://github.com/caarlos0/env) **star:1195** 解析环境变量并赋值到struct中(默认值)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/caarlos0/env)
* [konfig](https://github.com/lalamove/konfig) **star:520** 可组合、可观察和高性能的分布式配置管理。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/lalamove/konfig)
* [confita](https://github.com/heetch/confita) **star:260** 从多个后端级联加载配置到struct中。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/heetch/confita)
* [store](https://github.com/tucnak/store) **star:245** 轻量级配置管理器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tucnak/store)
* [config](https://github.com/olebedev/config) **star:216** 带有环境变量和标记解析的JSON或YAML配置包装器。   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/config)
* [joshbetz/config](https://github.com/joshbetz/config) **star:196** 一个可解析环境变量、JSON文件小巧的配置库，在SIGHUP时会自动重新加载。   [![godoc][GoDoc]](https://godoc.org/github.com/joshbetz/config)
* [config](https://github.com/JeremyLoy/config) **star:195** 云本地应用程序配置。将ENV绑定到结构体仅需两行代码。   [![godoc][GoDoc]](https://godoc.org/github.com/JeremyLoy/config)
* [hjson](https://github.com/hjson/hjson-go) **star:177** 更加人性化的JSON配置。轻松的语法，更少的错误，更多的注释。   [![godoc][GoDoc]](https://godoc.org/github.com/hjson/hjson-go)
* [envconfig](https://github.com/vrischmann/envconfig) **star:151** 从环境变量中读取配置。   [![godoc][GoDoc]](https://godoc.org/github.com/vrischmann/envconfig)
* [gcfg](https://github.com/go-gcfg/gcfg) **star:118** 将ini的配置文件读入 Go structs中;支持用户定义的类型和子选项。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-gcfg/gcfg)
* [goConfig](https://github.com/crgimenes/goConfig) **star:112** 将结构体解析为输入，并用来自命令行、环境变量和配置文件的参数填充该结构体的字段。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/crgimenes/goConfig)
* [gookit/config](https://github.com/gookit/config) **star:99** 程序配置管理(load,get,set)。支持JSON, YAML, TOML, INI, HCL。支持多文件加载，数据覆盖合并。   [![godoc][GoDoc]](https://godoc.org/github.com/gookit/config)   ![包含中文文档][CN]
* [koanf](https://github.com/knadh/koanf) **star:98** 轻量级可扩展库，用于读取Go应用程序中的配置。内置支持JSON, TOML, YAML, env，命令行。   [![godoc][GoDoc]](https://godoc.org/github.com/knadh/koanf)
* [envh](https://github.com/antham/envh) **star:92** 协助管理环境变量的Helpers。   [![godoc][GoDoc]](https://godoc.org/github.com/antham/envh)
* [envcfg](https://github.com/tomazk/envcfg) **star:89** 对环境变量进行解析，并赋值到struct。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tomazk/envcfg)
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf)  模块化的JSON配置。保持配置结构及其配置的代码，并将解析委托给子模块，而不牺牲配置的完整序列化。
* [gofigure](https://github.com/ian-kent/gofigure) **star:57** 让程序配置变得简单。   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/gofigure)
* [configure](https://github.com/paked/configure) **star:50** 通过多个源提供配置，包括JSON、flags和环境变量。   [![godoc][GoDoc]](https://godoc.org/github.com/paked/configure)
* [harvester](https://github.com/beatlabs/harvester) **star:44** 一个易于使用的静态和动态配置包   [![godoc][GoDoc]](https://godoc.org/github.com/beatlabs/harvester)
* [xdg](https://github.com/OpenPeeDeeP/xdg) **star:40** 遵循[XDG标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)的跨平台包。   [![godoc][GoDoc]](https://godoc.org/github.com/OpenPeeDeeP/xdg)
* [ingo](https://github.com/schachmat/ingo) **star:25** flag保存在类ini的配置文件中。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/schachmat/ingo)
* [go-up](https://github.com/ufoscout/go-up) **star:25** 一个简单的配置库，具有递归占位符解析功能。   [![godoc][GoDoc]](https://godoc.org/github.com/ufoscout/go-up)
* [mini](https://github.com/sasbury/mini) **star:20** 用于解析ini类型的配置文件。   [![godoc][GoDoc]](https://godoc.org/github.com/sasbury/mini)
* [conflate](https://github.com/the4thamigo-uk/conflate) **star:9** 合并来自任意url的多个JSON/YAML/TOML文件、针对JSON模式的验证以及模式中定义的默认值的应用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/the4thamigo-uk/conflate)
* [genv](https://github.com/sakirsensoy/genv) **star:7** 使用dotenv支持轻松读取环境变量。   [![godoc][GoDoc]](https://godoc.org/github.com/sakirsensoy/genv)
* [envconf](https://github.com/ian-kent/envconf) **star:7** 从环境配置中读取配置。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/envconf)
* [sprbox](https://github.com/oblq/sprbox) **star:4** 支持构建环境的工具箱工厂和其他不确定的配置解析器(如YAML、TOML、JSON和环境vars)。   [![godoc][GoDoc]](https://godoc.org/github.com/oblq/sprbox)
* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) **star:2** 读取环境变量的简单有用的包。   [![godoc][GoDoc]](https://godoc.org/github.com/nasermirzaei89/env)

## 持续集成

*用于帮助进行持续集成的工具。 (翻译出错了? 试试 [英文版](README_EN.md#continuous-integration) 吧~)*

* [drone](https://github.com/drone/drone) **star:19569** Drone 是一个基于 Docker 的持续集成平台，用 Go 编写。   [![star > 2000][Awesome]](https://github.com/drone/drone)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/drone/drone)
* [goveralls](https://github.com/mattn/goveralls) **star:593** Coveralls.io 是一个用 Go 编写，可持续对代码覆盖率进行检测的系统。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/goveralls)
* [overalls](https://github.com/go-playground/overalls) **star:98** 针对多package 的 Go 语言项目，可为类似 goveralls 这样的工具生成覆盖率报告。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/overalls)
* [duci](https://github.com/duck8823/duci) **star:46** 一个简单的 ci 服务。   [![godoc][GoDoc]](https://godoc.org/github.com/duck8823/duci)
* [gomason](https://github.com/nikogura/gomason) **star:35** 在一个干净的工作区中对你的 Go 二进制文件进行测试、构建、签名和发布。   [![godoc][GoDoc]](https://godoc.org/github.com/nikogura/gomason)
* [roveralls](https://github.com/LawrenceWoodman/roveralls) **star:12** 递归覆盖测试工具。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/LawrenceWoodman/roveralls)

## CSS预处理器

*用于预处理CSS文件的库。 (翻译出错了? 试试 [英文版](README_EN.md#css-preprocessors) 吧~)*

* [gcss](https://github.com/yosssi/gcss) **star:426** 纯Go编写的 CSS 预处理器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/yosssi/gcss)
* [go-libsass](https://github.com/wellington/go-libsass) **star:140**  采用 Go封装，100% 与 Sass 兼容的 libsass 项目。

## 数据结构

*用 Go 实现的通用的数据结构和算法。 (翻译出错了? 试试 [英文版](README_EN.md#data-structures) 吧~)*

* [gods](https://github.com/emirpasic/gods) **star:6794** 数据结构。容器、集合、列表、堆栈、地图、BidiMaps、树、HashSet等。   [![star > 2000][Awesome]](https://github.com/emirpasic/gods)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/emirpasic/gods)
* [go-datastructures](https://github.com/Workiva/go-datastructures) **star:5255** 可靠的、高性能的和线程安全的数据结构的集合。   [![star > 2000][Awesome]](https://github.com/Workiva/go-datastructures)   [![godoc][GoDoc]](https://godoc.org/github.com/Workiva/go-datastructures)
* [golang-set](https://github.com/deckarep/golang-set) **star:1240** 线程安全和非线程安全的高性能集。   [![godoc][GoDoc]](https://godoc.org/github.com/deckarep/golang-set)
* [boomfilters](https://github.com/tylertreat/BoomFilters) **star:1188** 用于处理连续的概率数据结构。   [![godoc][GoDoc]](https://godoc.org/github.com/tylertreat/BoomFilters)
* [gota](https://github.com/kniren/gota) **star:934** 实现了数据帧，序列以及数据噪音。   [![godoc][GoDoc]](https://godoc.org/github.com/kniren/gota)
* [roaring](https://github.com/RoaringBitmap/roaring) **star:715** 实现了压缩 bitsets 的Go包。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/RoaringBitmap/roaring)
* [willf/bloom](https://github.com/willf/bloom) **star:689** 实现Bloom过滤器。   [![godoc][GoDoc]](https://godoc.org/github.com/willf/bloom)
* [hyperloglog](https://github.com/axiomhq/hyperloglog) **star:667** HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.   [![godoc][GoDoc]](https://godoc.org/github.com/axiomhq/hyperloglog)
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) **star:531** 布谷鸟过滤器:一个用Go实现，可替代计数 bloom 过滤器。   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/cuckoofilter)
* [bitset](https://github.com/willf/bitset) **star:502** 实现了 bitsets 的 Go 包。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/willf/bitset)
* [trie](https://github.com/derekparker/trie) **star:436** 在Go中实现Trie。   [![godoc][GoDoc]](https://godoc.org/github.com/derekparker/trie)
* [go-geoindex](https://github.com/hailocab/go-geoindex) **star:314** 基于内存的地理索引。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/hailocab/go-geoindex)
* [mafsa](https://github.com/smartystreets/mafsa) **star:275** 实现了 MA-FSA ，包含最小完美哈希。   [![godoc][GoDoc]](https://godoc.org/github.com/smartystreets/mafsa)   ![归档项目][Archived]
* [algorithms](https://github.com/shady831213/algorithms) **star:273** 算法和数据结构。来源于CLRS。   [![godoc][GoDoc]](https://godoc.org/github.com/shady831213/algorithms)
* [goskiplist](https://github.com/ryszard/goskiplist) **star:199** 基于 Go 的跳表实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ryszard/goskiplist)
* [hilbert](https://github.com/google/hilbert) **star:187** 用于映射空间填充曲线（例如 Hilbert 曲线和 Peano 曲线）和数值。   [![godoc][GoDoc]](https://godoc.org/github.com/google/hilbert)
* [merkletree](https://github.com/cbergoon/merkletree) **star:159** 实现了merkle树，提供了对数据结构内容的有效和安全的验证。   [![godoc][GoDoc]](https://godoc.org/github.com/cbergoon/merkletree)
* [bloom](https://github.com/zhenjl/bloom) **star:130** 在Go中实现了Bloom过滤器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zhenjl/bloom)
* [binpacker](https://github.com/zhuangsirui/binpacker) **star:129** 帮助用户构建自定义二进制流的二进制封装器和解包器   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zhuangsirui/binpacker)
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) **star:109** 自适应基数树。   [![godoc][GoDoc]](https://godoc.org/github.com/plar/go-adaptive-radix-tree)
* [ttlcache](https://github.com/diegobernardes/ttlcache) **star:109** 基于内存的LRU算法实现。   [![godoc][GoDoc]](https://godoc.org/github.com/diegobernardes/ttlcache)
* [skiplist](https://github.com/MauriceGit/skiplist) **star:105** 高性能的 Go 跳表实现。   [![godoc][GoDoc]](https://godoc.org/github.com/MauriceGit/skiplist)
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) **star:102** 区域四叉树具有高效的点定位和邻域查找功能。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/aurelien-rainone/go-rquad)
* [encoding](https://github.com/zhenjl/encoding) **star:97** 整形压缩库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zhenjl/encoding)
* [ring](https://github.com/TheTannerRyan/ring) **star:91** 高性能、线程安全的bloom过滤器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/TheTannerRyan/ring)
* [conjungo](https://github.com/InVisionApp/conjungo) **star:84** 一个小型、强大和灵活的合并库。   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/conjungo)
* [deque](https://github.com/gammazero/deque) **star:79** 快速环缓冲区deque(双端队列)。   [![godoc][GoDoc]](https://godoc.org/github.com/gammazero/deque)
* [skiplist](https://github.com/gansidui/skiplist) **star:66** 在Go中实现了跳表。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/gansidui/skiplist)
* [bit](https://github.com/yourbasic/bit) **star:63** Go 语言集合数据结构。提供了额外的位操作功能。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/yourbasic/bit)
* [levenshtein](https://github.com/agnivade/levenshtein) **star:56** 实现在Go中计算levenshtein距离。   [![godoc][GoDoc]](https://godoc.org/github.com/agnivade/levenshtein)
* [bloom](https://github.com/yourbasic/bloom) **star:44** Golang Bloom过滤器的实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/yourbasic/bloom)
* [count-min-log](https://github.com/seiflotfy/count-min-log) **star:43** Go实现Count-Min-log sketch的功能 : 使用近似计数器进行近似计数(类似Count-Min sketch，但使用更少内存)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/count-min-log)
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) **star:39** 并行FIFO队列。   [![godoc][GoDoc]](https://godoc.org/github.com/enriquebris/goconcurrentqueue)
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) **star:37** 基于内存的实现了高性能的key:value存储库。指针缓存。   [![godoc][GoDoc]](https://godoc.org/github.com/OrlovEvgeny/go-mcache)
* [levenshtein](https://github.com/agext/levenshtein) **star:35** Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.   [![godoc][GoDoc]](https://godoc.org/github.com/agext/levenshtein)
* [concurrent-writer](https://github.com/free/concurrent-writer) **star:25** 具备高并发能力，可替换 bufio.Writer。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/free/concurrent-writer)
* [remember-go](https://github.com/rocketlaunchr/remember-go) **star:21** 用于缓存数据(redis、内存、memcached等)的通用接口。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/rocketlaunchr/remember-go)
* [crunch](https://github.com/superwhiskers/crunch) **star:19** 打包实现缓冲区，以便轻松处理各种数据类型。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/superwhiskers/crunch)
* [goset](https://github.com/zoumo/goset) **star:17** 一个有用的Go集合实现。   [![godoc][GoDoc]](https://godoc.org/github.com/zoumo/goset)
* [pipeline](https://github.com/hyfather/pipeline) **star:17** 实现了 fan-in 和 fan-out 的管道功能。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/hyfather/pipeline)
* [typ](https://github.com/gurukami/typ) **star:12** 从复杂结构中获取值，支持空类型、安全的类型转换。   [![godoc][GoDoc]](https://godoc.org/github.com/gurukami/typ)
* [go-ef](https://github.com/amallia/go-ef) **star:11** 实现了 Elias-Fano 编码。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/amallia/go-ef)
* [hide](https://github.com/emvi/hide) **star:10** ID type with marshalling to/from hash to prevent sending IDs to clients.   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/hide)
* [deque](https://github.com/edwingeng/deque) **star:9** 高度优化的双端队列。   [![godoc][GoDoc]](https://godoc.org/github.com/edwingeng/deque)
* [dict](https://github.com/srfrog/dict) **star:9** 实现类似 python dict的功能(dict)。   [![godoc][GoDoc]](https://godoc.org/github.com/srfrog/dict)
* [mspm](https://github.com/BlackRabbitt/mspm) **star:8** 用于信息检索的多字符串模式匹配算法。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/BlackRabbitt/mspm)
* [set](https://github.com/StudioSol/set) **star:7** 使用LinkedHashMap在Go中实现简单的set数据结构。   [![godoc][GoDoc]](https://godoc.org/github.com/StudioSol/set)
* [treap](https://github.com/perdata/treap) **star:7** 使用树堆进行持久、快速有序的映射。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/perdata/treap)
* [null](https://github.com/emvi/null) **star:6** 对空的 Go 数据类型也可以进行JSON进行解析/反解析。   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/null)
* [parsefields](https://github.com/MonaxGT/parsefields) **star:3** 用于解析类似json的日志的工具，用于收集惟一的字段和事件。   [![godoc][GoDoc]](https://godoc.org/github.com/MonaxGT/parsefields)
* [gofal](https://github.com/xxjwxc/gofal) **star:3** 部分api for Go。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/xxjwxc/gofal)   ![包含中文文档][CN]
* [timedmap](https://github.com/zekroTJA/timedmap) **star:3** 实现了有生命周期的键值对Map。   [![godoc][GoDoc]](https://godoc.org/github.com/zekroTJA/timedmap)
* [ptrie](https://github.com/viant/ptrie) **star:2** 前缀树的一种实现。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/ptrie)

## 数据库

*数据库。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [prometheus](https://github.com/prometheus/prometheus) **star:26859** 用于监控系统和时序的数据库。   [![star > 2000][Awesome]](https://github.com/prometheus/prometheus)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/prometheus/prometheus)
* [tidb](https://github.com/pingcap/tidb) **star:20843** TiDB是一个分布式SQL数据库。灵感来自谷歌F1的设计。   [![star > 2000][Awesome]](https://github.com/pingcap/tidb)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/pingcap/tidb)   ![包含中文文档][CN]
* [influxdb](https://github.com/influxdb/influxdb) **star:17486** 可伸缩的数据存储，用于指标衡量、事件和实时分析。   [![star > 2000][Awesome]](https://github.com/influxdb/influxdb)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/influxdb/influxdb)
* [cockroach](https://github.com/cockroachdb/cockroach) **star:17122** 可伸缩、区域备份、事务性数据存储。   [![star > 2000][Awesome]](https://github.com/cockroachdb/cockroach)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/cockroachdb/cockroach)
* [dgraph](https://github.com/dgraph-io/dgraph) **star:11277** 可伸缩、分布式、低延迟、高吞吐量的图形数据库。   [![star > 2000][Awesome]](https://github.com/dgraph-io/dgraph)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/dgraph-io/dgraph)
* [bolt](https://github.com/boltdb/bolt) **star:10157** K/V 数据库。   [![star > 2000][Awesome]](https://github.com/boltdb/bolt)   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/boltdb/bolt)   ![归档项目][Archived]
* [groupcache](https://github.com/golang/groupcache) **star:7855** Groupcache是一个缓存和缓存填充库，在许多情况下，它是memcached的替代品。   [![star > 2000][Awesome]](https://github.com/golang/groupcache)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/groupcache)
* [badger](https://github.com/dgraph-io/badger) **star:6627** 快速 K/V 存储。   [![star > 2000][Awesome]](https://github.com/dgraph-io/badger)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/dgraph-io/badger)
* [rqlite](https://github.com/rqlite/rqlite) **star:4860** 基于SQLite的轻量级分布式关系数据库。   [![star > 2000][Awesome]](https://github.com/rqlite/rqlite)   [![godoc][GoDoc]](https://godoc.org/github.com/rqlite/rqlite)
* [goleveldb](https://github.com/syndtr/goleveldb) **star:3288** 在Go中实现[LevelDB](https://github.com/google/leveldb) key/value数据库。   [![star > 2000][Awesome]](https://github.com/syndtr/goleveldb)   [![godoc][GoDoc]](https://godoc.org/github.com/syndtr/goleveldb)
* [ledisdb](https://github.com/siddontang/ledisdb) **star:3130** Ledisdb是一种高性能的NoSQL，类似于基于LevelDB的Redis。   [![star > 2000][Awesome]](https://github.com/siddontang/ledisdb)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/ledisdb)
* [go-cache](https://github.com/pmylund/go-cache) **star:3115** 基于内存的 K/V 存储/缓存 : (类似于Memcached)，适用于单机应用程序。   [![star > 2000][Awesome]](https://github.com/pmylund/go-cache)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/pmylund/go-cache)
* [BigCache](https://github.com/allegro/bigcache) **star:2585** 高效的键/值缓存为千兆字节的数据。   [![star > 2000][Awesome]](https://github.com/allegro/bigcache)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/allegro/bigcache)
* [buntdb](https://github.com/tidwall/buntdb) **star:2490** 基于内存的K/V，快速，可嵌入的数据库，可自定义索引和空间支持。   [![star > 2000][Awesome]](https://github.com/tidwall/buntdb)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/buntdb)
* [tiedot](https://github.com/HouzuoGuo/tiedot) **star:2395** 属于你的NoSQL数据库。   [![star > 2000][Awesome]](https://github.com/HouzuoGuo/tiedot)   [![godoc][GoDoc]](https://godoc.org/github.com/HouzuoGuo/tiedot)
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) **star:1238** 开源，快速，可伸缩的时间序列数据库。支持PromQL。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/VictoriaMetrics/VictoriaMetrics)
* [cache2go](https://github.com/muesli/cache2go) **star:1102** 基于内存的 K/V 缓存，支持超时的自动失效。   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/cache2go)
* [GCache](https://github.com/bluele/gcache) **star:961** 支持过期缓存、LFU、LRU和ARC的缓存库。   [![godoc][GoDoc]](https://godoc.org/github.com/bluele/gcache)
* [nutsdb](https://github.com/xujiajun/nutsdb) **star:919** Nutsdb是一个用纯Go编写的简单、快速、可嵌入、持久的键/值存储。它支持完全序列化的事务和许多数据结构，如列表、集合、排序集。   [![godoc][GoDoc]](https://godoc.org/github.com/xujiajun/nutsdb)   ![包含中文文档][CN]
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) **star:918** 区块链领域的一个SQL数据库。   [![godoc][GoDoc]](https://godoc.org/github.com/CovenantSQL/CovenantSQL)
* [diskv](https://github.com/peterbourgon/diskv) **star:787** 支持磁盘备份的可持久化 K/V 存储。   [![godoc][GoDoc]](https://godoc.org/github.com/peterbourgon/diskv)
* [moss](https://github.com/couchbase/moss) **star:734** Moss是一个用100% Go编写的简单LSM键值存储引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/moss)
* [eliasdb](https://github.com/krotik/eliasdb) **star:543** 无其他依赖项，支持REST API，短语搜索和sql类似的查询语言的事务图数据库。   [![godoc][GoDoc]](https://godoc.org/github.com/krotik/eliasdb)
* [fastcache](https://github.com/VictoriaMetrics/fastcache) **star:537** 基于内存的快速线程安全的缓存，可缓存大量的条目。最大限度地减少GC开销。   [![godoc][GoDoc]](https://godoc.org/github.com/VictoriaMetrics/fastcache)
* [levigo](https://github.com/jmhodges/levigo) **star:369** 实现了对LevelDB封装。   [![godoc][GoDoc]](https://godoc.org/github.com/jmhodges/levigo)
* [pudge](https://github.com/recoilme/pudge) **star:231** 使用Go的标准库编写的快速和简单的键/值存储。   [![godoc][GoDoc]](https://godoc.org/github.com/recoilme/pudge)
* [piladb](https://github.com/fern4lvarez/piladb) **star:170** 基于堆栈数据结构的轻量级RESTful数据库引擎。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/fern4lvarez/piladb)
* [Vasto](https://github.com/chrislusf/vasto) **star:161** 分布式高性能键值存储。可做磁盘备份。最终一致。高可用。能够在不中断服务的情况下增长或收缩。   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/vasto)
* [Kivik](https://github.com/go-kivik/kivik) **star:120** Kivik为CouchDB、PouchDB和类似的数据库提供了一个通用的Go和GopherJS客户端库。   [![godoc][GoDoc]](https://godoc.org/github.com/go-kivik/kivik)
* [slowpoke](https://github.com/recoilme/slowpoke) **star:89** 具有持久性的键值存储。   [![godoc][GoDoc]](https://godoc.org/github.com/recoilme/slowpoke)
* [Scribble](https://github.com/nanobox-io/golang-scribble) **star:73** 小型平面文件JSON存储。   [![godoc][GoDoc]](https://godoc.org/github.com/nanobox-io/golang-scribble)
* [couchcache](https://github.com/codingsince1985/couchcache) **star:43** 由 Couchbase服务 支持的RESTful缓存微服务。   [![godoc][GoDoc]](https://godoc.org/github.com/codingsince1985/couchcache)
* [bcache](https://github.com/iwanbk/bcache) **star:33** 基于内存的最终一致的分布式缓存。   [![godoc][GoDoc]](https://godoc.org/github.com/iwanbk/bcache)
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) **star:30** BigCache 支持集群和独立且生命周期存储项。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/oaStuff/clusteredBigCache)
* [cache](https://github.com/akyoto/cache) **star:23** 基于内存的 K/V 存储:带生命周期的值存储，0个依赖项，<100 LoC, 100%覆盖率。   [![godoc][GoDoc]](https://godoc.org/github.com/akyoto/cache)
* [tempdb](https://github.com/rafaeljesus/tempdb) **star:13** 用于临时数据存放的 K/V 存储。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/tempdb)
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) **star:10** 用 Go 对[RocksDB](https://rocksdb.org)实现了封装。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/kapitan-k/gorocksdb)

*数据库迁移。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [migrate](https://github.com/golang-migrate/migrate) **star:3026** 基于CLI的数据库迁移库。   [![star > 2000][Awesome]](https://github.com/golang-migrate/migrate)   [![godoc][GoDoc]](https://godoc.org/github.com/golang-migrate/migrate)
* [sql-migrate](https://github.com/rubenv/sql-migrate) **star:1463** 数据库迁移工具。允许使用go-bindata将迁移嵌入到应用程序中。   [![godoc][GoDoc]](https://godoc.org/github.com/rubenv/sql-migrate)
* [skeema](https://github.com/skeema/skeema) **star:442** 用于MySQL的纯sql模式管理系统，支持分片和外部在线模式更改工具。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/skeema/skeema)
* [soda](https://github.com/gobuffalo/pop/tree/master/soda)  数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。
* [gormigrate](https://github.com/go-gormigrate/gormigrate) **star:359** 面向Gorm ORM的数据库 schema 迁移辅助程序。   [![godoc][GoDoc]](https://godoc.org/github.com/go-gormigrate/gormigrate)
* [goose](https://github.com/steinbacher/goose) **star:121** 数据库迁移工具。您可以通过创建增量SQL或Go脚本来管理数据库的升级。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/steinbacher/goose)
* [darwin](https://github.com/GuiaBolso/darwin) **star:91** 用于数据库 schema 升级的库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/GuiaBolso/darwin)
* [migrator](https://github.com/lopezator/migrator) **star:77** 非常简单的 Go 数据库迁移库。   [![godoc][GoDoc]](https://godoc.org/github.com/lopezator/migrator)
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) **star:29** 用Go -pg/pg编写的迁移包。   [![godoc][GoDoc]](https://godoc.org/github.com/robinjoseph08/go-pg-migrations)
* [gondolier](https://github.com/emvi/gondolier) **star:26** 使用结构修饰的数据库迁移库。   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/gondolier)
* [pravasan](https://github.com/pravasan/pravasan) **star:24** 简易的迁移工具-目前只支持MySQL，但计划很快支持Postgres, SQLite, MongoDB等。
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) **star:20** 类似 Django fixture，用于 Go 建立内置数据库/sql库。   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/go-fixtures)
* [avro](https://github.com/khezen/avro) **star:7** 发现SQL schemas并将其转换为AVRO schemas。   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/avro)
* [schema](https://github.com/adlio/schema) **star:2** 库，用于将数据库/sql兼容数据库的模式迁移嵌入到Go二进制文件中。   [![godoc][GoDoc]](https://godoc.org/github.com/adlio/schema)

*数据库工具。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [vitess](https://github.com/youtube/vitess) **star:8697** vitess提供了可以为大规模web服务扩展MySQL数据库提供便利的服务和工具。   [![star > 2000][Awesome]](https://github.com/youtube/vitess)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/youtube/vitess)
* [pgweb](https://github.com/sosedoff/pgweb) **star:6085** 基于web的PostgreSQL数据库浏览器。   [![star > 2000][Awesome]](https://github.com/sosedoff/pgweb)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/sosedoff/pgweb)
* [kingshard](https://github.com/flike/kingshard) **star:4784** kingshard 是基于 Golang 的MySQL高性能代理。   [![star > 2000][Awesome]](https://github.com/flike/kingshard)   [![godoc][GoDoc]](https://godoc.org/github.com/flike/kingshard)   ![包含中文文档][CN]
* [orchestrator](https://github.com/github/orchestrator) **star:3147** MySQL复制拓扑管理器和可视化工具。   [![star > 2000][Awesome]](https://github.com/github/orchestrator)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/github/orchestrator)
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) **star:2542** 自动将MySQL数据同步到Elasticsearch中。   [![star > 2000][Awesome]](https://github.com/siddontang/go-mysql-elasticsearch)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-mysql-elasticsearch)
* [pREST](https://github.com/nuveo/prest) **star:2115** 基于PostgreSQL database的RESTful API服务。   [![star > 2000][Awesome]](https://github.com/nuveo/prest)   [![godoc][GoDoc]](https://godoc.org/github.com/nuveo/prest)
* [go-mysql](https://github.com/siddontang/go-mysql) **star:2003**  Go 工具集，用于处理MySQL协议和复制。   [![star > 2000][Awesome]](https://github.com/siddontang/go-mysql)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-mysql)
* [chproxy](https://github.com/Vertamedia/chproxy) **star:319** ClickHouse数据库的HTTP代理。   [![godoc][GoDoc]](https://godoc.org/github.com/Vertamedia/chproxy)
* [myreplication](https://github.com/2tvenom/myreplication) **star:144** MySql二进制日志复制监听器。支持基于语句和行的复制。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/2tvenom/myreplication)
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) **star:143** 收集小的 insterts 并向 ClickHouse 服务器发送大请求。   [![godoc][GoDoc]](https://godoc.org/github.com/nikepan/clickhouse-bulk)
* [octillery](https://github.com/knocknote/octillery) **star:63** 用于数据库分表(支持每个ORM或原生SQL)。   [![godoc][GoDoc]](https://godoc.org/github.com/knocknote/octillery)
* [dbbench](https://github.com/sj14/dbbench) **star:30** 数据库基准测试工具，支持多个数据库和脚本。   [![godoc][GoDoc]](https://godoc.org/github.com/sj14/dbbench)
* [prep](https://github.com/hexdigest/prep) **star:24** 在不更改代码的情况下使用准备好的SQL语句。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/hexdigest/prep)
* [datagen](https://github.com/codingconcepts/datagen) **star:10** 一个快速的数据生成器，支持多表感知和多行DML。   [![godoc][GoDoc]](https://godoc.org/github.com/codingconcepts/datagen)
* [rwdb](https://github.com/andizzle/rwdb) **star:10** rwdb为多个数据库服务器的设置提供读取副本功能。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/andizzle/rwdb)

*SQL查询生成器，用于构建和使用SQL的库。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [Squirrel](https://github.com/Masterminds/squirrel) **star:2443** 帮助您构建SQL查询的Go库。   [![star > 2000][Awesome]](https://github.com/Masterminds/squirrel)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/Masterminds/squirrel)
* [xo](https://github.com/knq/xo) **star:2231** 基于现有的schema定义和自定义查询生成 Go 代码，基于支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server。   [![star > 2000][Awesome]](https://github.com/knq/xo)   [![godoc][GoDoc]](https://godoc.org/github.com/knq/xo)
* [gendry](https://github.com/didi/gendry) **star:854** 非入侵的SQL构建器和强大的数据绑定器。   [![godoc][GoDoc]](https://godoc.org/github.com/didi/gendry)   ![包含中文文档][CN]
* [goqu](https://github.com/doug-martin/goqu) **star:681** 常用的SQL生成器和查询库。   [![godoc][GoDoc]](https://godoc.org/github.com/doug-martin/goqu)
* [Dotsql](https://github.com/gchaincl/dotsql) **star:456** Go library帮助您将sql文件保存在一个地方，并轻松地使用它们。   [![godoc][GoDoc]](https://godoc.org/github.com/gchaincl/dotsql)
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) **star:439** Powerful data retrieval methods as well as DB-agnostic query building capabilities.   [![godoc][GoDoc]](https://godoc.org/github.com/go-ozzo/ozzo-dbx)
* [scaneo](https://github.com/variadico/scaneo)  生成用于将数据库行转换为任意结构体的 Go 代码。
* [sqrl](https://github.com/elgris/sqrl) **star:185** SQL查询生成器，从Squirrel fork而来，并再此基础上对性能做了优化。   [![godoc][GoDoc]](https://godoc.org/github.com/elgris/sqrl)
* [Squalus](https://gitlab.com/qosenergy/squalus)  Go SQL中间层，能使得执行查询更加容易。
* [jet](https://github.com/go-jet/jet) **star:155** 用于在Go中编写类型安全的SQL查询的框架，能够轻松地将数据库查询结果转换为所需的任意对象结构。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-jet/jet)
* [ormlite](https://github.com/pupizoid/ormlite)  包含一些类似orm的特性和sqlite数据库的辅助程序的轻量级包
* [igor](https://github.com/galeone/igor) **star:78** PostgreSQL的抽象层，支持高级功能和类似gorm的语法。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/galeone/igor)
* [godbal](https://github.com/xujiajun/godbal) **star:48** 数据库抽象层(dbal)。支持SQL builder，轻松获取结果。   [![godoc][GoDoc]](https://godoc.org/github.com/xujiajun/godbal)
* [dbq](https://github.com/rocketlaunchr/dbq) **star:46** Zero boilerplate database operations for Go   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/rocketlaunchr/dbq)

## 数据库驱动程序

*用于连接和操作数据库的库。 (翻译出错了? 试试 [英文版](README_EN.md#database-drivers) 吧~)*

* Relational Databases
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) **star:8405** MySQL驱动程序。   [![star > 2000][Awesome]](https://github.com/go-sql-driver/mysql)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-sql-driver/mysql)
    * [pq](https://github.com/lib/pq) **star:5324** 纯 Go 的Postgres驱动。   [![star > 2000][Awesome]](https://github.com/lib/pq)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/lib/pq)
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) **star:3532** SQLite3驱动程序。   [![star > 2000][Awesome]](https://github.com/mattn/go-sqlite3)   ![最近一周有更新][Green]
    * [pgx](https://github.com/jackc/pgx) **star:2095** PostgreSQL驱动，支持比现有database/sql更多的特性。   [![star > 2000][Awesome]](https://github.com/jackc/pgx)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jackc/pgx)
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) **star:1061** 微软MSSQL驱动程序。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/denisenkom/go-mssqldb)
    * [go-oci8](https://github.com/mattn/go-oci8) **star:416** Oracle 驱动程序。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-oci8)
    * [goracle](https://github.com/go-goracle/goracle) **star:255** 基于 ODPI-C 的 Oracle 驱动程序   ![最近一周有更新][Green]
    * [firebirdsql](https://github.com/nakagami/firebirdsql) **star:105** Firebird RDBMS SQL驱动程序。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/nakagami/firebirdsql)
    * [gofreetds](https://github.com/minus5/gofreetds) **star:92** 基于[FreeTDS](http://www.freetds.org)封装的微软MSSQL Go 驱动。   [![godoc][GoDoc]](https://godoc.org/github.com/minus5/gofreetds)
    * [go-adodb](https://github.com/mattn/go-adodb) **star:91** Microsoft ActiveX对象数据库驱动程序。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-adodb)
    * [avatica](https://github.com/apache/calcite-avatica-go) **star:40** Apache Avatica/Phoenix SQL驱动程序。   [![godoc][GoDoc]](https://godoc.org/github.com/apache/calcite-avatica-go)
    * [bgc](https://github.com/viant/bgc) **star:12** BigQuery 的数据存储连接。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/bgc)

* NoSQL Databases
    * [redis](https://github.com/go-redis/redis) **star:6992** 基于 Go 的 Redis 客户端。   [![star > 2000][Awesome]](https://github.com/go-redis/redis)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-redis/redis)
    * [redigo](https://github.com/gomodule/redigo) **star:6537** Redigo 是基于 Go 的Redis 客户端。   [![star > 2000][Awesome]](https://github.com/gomodule/redigo)   [![godoc][GoDoc]](https://godoc.org/github.com/gomodule/redigo)
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) **star:3437** 官方的 MongoDB 驱动。   [![star > 2000][Awesome]](https://github.com/mongodb/mongo-go-driver)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mongodb/mongo-go-driver)
    * [mgo](https://github.com/globalsign/mgo) **star:1685** (已停止维护) MongoDB驱动。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/globalsign/mgo)
    * [gorethink](https://github.com/dancannon/gorethink) **star:1473** RethinkDB 驱动。   [![godoc][GoDoc]](https://godoc.org/github.com/dancannon/gorethink)
    * [neoism](https://github.com/jmcvetta/neoism) **star:361** Golang 的 Neo4j 客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/jmcvetta/neoism)
    * [redeo](https://github.com/bsm/redeo) **star:356** 与 redis 协议兼容的 TCP 服务器/服务。   [![godoc][GoDoc]](https://godoc.org/github.com/bsm/redeo)
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) **star:311** Aerospike 客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/aerospike/aerospike-client-go)
    * [gocb](https://github.com/couchbase/gocb) **star:300** 官方Couchbase Go SDK。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/gocb)
    * [gocql](http://gocql.github.io)  Apache Cassandra 的 Go 驱动。
    * [go-couchbase](https://github.com/couchbase/go-couchbase) **star:296** Couchbase客户端。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/go-couchbase)
    * [go-rejson](https://github.com/nitishm/go-rejson) **star:98** 实现了基于 Redigo 客户端的redislabs' ReJSON 模块。可简单地将结构体存储为JSON对象并对其进行操作。   [![godoc][GoDoc]](https://godoc.org/github.com/nitishm/go-rejson)
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) **star:72** Neo4j REST 客户端。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/davemeehan/Neo4j-GO)
    * [arangolite](https://github.com/solher/arangolite) **star:66** 轻量级的 ArangoDB 驱动。   [![godoc][GoDoc]](https://godoc.org/github.com/solher/arangolite)
    * [dynago](https://github.com/underarmour/dynago) **star:66** 满足 principle of least surprise 的 DynamoDB 客户端。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/underarmour/dynago)
    * [godis](https://github.com/piaohao/godis) **star:62** 由GoLang实现的redis客户端，灵感来自jedis。   [![godoc][GoDoc]](https://godoc.org/github.com/piaohao/godis)
    * [go-pilosa](https://github.com/pilosa/go-pilosa) **star:32**  Pilosa客户端。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/pilosa/go-pilosa)
    * [forestdb](https://github.com/couchbase/goforestdb) **star:29** 基于 Go 的 ForestDB 接口实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/goforestdb)
    * [goriak](https://github.com/zegl/goriak) **star:24**  Riak KV 驱动。   [![godoc][GoDoc]](https://godoc.org/github.com/zegl/goriak)
    * [neo4j](https://github.com/cihangir/neo4j) **star:24** Neo4j Rest API实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/cihangir/neo4j)
    * [xredis](https://github.com/shomali11/xredis) **star:9** 类型安全，可定制，清晰和易用的Redis客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/shomali11/xredis)
    * [godscache](https://github.com/defcronyke/godscache) **star:6** 谷歌云平台Go Datastore包的封装，它采用了memcached添加缓存。   [![godoc][GoDoc]](https://godoc.org/github.com/defcronyke/godscache)
    * [gomemcache](https://github.com/bradfitz/gomemcache/)  memcache客户端库。
    * [asc](https://github.com/viant/asc) **star:4** Aerospike 的数据存储连接器。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/asc)

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) **star:5956** 基于 Go 的现代文本索引库。   [![star > 2000][Awesome]](https://github.com/blevesearch/bleve)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/blevesearch/bleve)
    * [riot](https://github.com/go-ego/riot) **star:4828** 基于 Go 的 开源、分布式、简单高效的搜索引擎。   [![star > 2000][Awesome]](https://github.com/go-ego/riot)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ego/riot)   ![包含中文文档][CN]
    * [elastic](https://github.com/olivere/elastic) **star:4367** Elasticsearch 客户端。   [![star > 2000][Awesome]](https://github.com/olivere/elastic)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/olivere/elastic)
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) **star:1788** 官方 Elasticsearch 客户端。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/elastic/go-elasticsearch)
    * [elastigo](https://github.com/mattbaird/elastigo) **star:953** Elasticsearch 客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/mattbaird/elastigo)
    * [elasticsql](https://github.com/cch123/elasticsql) **star:434** 将 SQL 转换为 elasticsearch dsl。   [![godoc][GoDoc]](https://godoc.org/github.com/cch123/elasticsql)
    * [skizze](https://github.com/seiflotfy/skizze) **star:68** 面向概率数据结构的服务和存储。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/skizze)
    * [goes](https://github.com/OwnLocal/goes) **star:24** 实现了与 Elasticsearch 交互的库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/OwnLocal/goes)

* Multiple Backends.
    * [cayley](https://github.com/google/cayley) **star:12870** 图形数据库，支持多个后端。   [![star > 2000][Awesome]](https://github.com/google/cayley)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/google/cayley)
    * [cachego](https://github.com/fabiorphp/cachego) **star:110** 基于多个驱动程序的缓存组件。   [![godoc][GoDoc]](https://godoc.org/github.com/fabiorphp/cachego)
    * [gokv](https://github.com/philippgille/gokv) **star:103** 可扩展的简单的 K/V 存储(Redis、Consul、etcd、bbolt、BadgerDB、LevelDB、Memcached、DynamoDB、S3、PostgreSQL、MongoDB、CockroachDB等等)。   [![godoc][GoDoc]](https://godoc.org/github.com/philippgille/gokv)
    * [dsc](https://github.com/viant/dsc) **star:14** 面向 SQL、NoSQL、结构化文件的数据存储连接。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/dsc)

## 日期和时间

*用于处理日期和时间的库。 (翻译出错了? 试试 [英文版](README_EN.md#date-and-time) 吧~)*

* [now](https://github.com/jinzhu/now) **star:2241** now 是时间有关的工具类。   [![star > 2000][Awesome]](https://github.com/jinzhu/now)   [![godoc][GoDoc]](https://godoc.org/github.com/jinzhu/now)
* [dateparse](https://github.com/araddon/dateparse) **star:933** 可以解析很多格式不固定的日期字符串。   [![godoc][GoDoc]](https://godoc.org/github.com/araddon/dateparse)
* [carbon](https://github.com/uniplaces/carbon) **star:361** 简单的时间扩展，包含了许多使用方法，从 PHP Carbon 库移植的。   [![godoc][GoDoc]](https://godoc.org/github.com/uniplaces/carbon)
* [durafmt](https://github.com/hako/durafmt) **star:249** 轻量级、可让time.Duration更加易读的库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/hako/durafmt)
* [timeutil](https://github.com/leekchan/timeutil) **star:171** 面向 Golang 的时间库，集成了很多有用的扩展(Timedelta, Strftime, ...)。   [![godoc][GoDoc]](https://godoc.org/github.com/leekchan/timeutil)
* [iso8601](https://github.com/relvacode/iso8601) **star:69** 不用正则表达式有效解析 ISO8601 日期时间。   [![godoc][GoDoc]](https://godoc.org/github.com/relvacode/iso8601)
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) **star:67** 太阳历实现。   [![godoc][GoDoc]](https://godoc.org/github.com/yaa110/go-persian-calendar)
* [timespan](https://github.com/SaidinWoT/timespan) **star:64** 用于处理时间间隔相关的库，可定义开始时间和持续时间。   [![godoc][GoDoc]](https://godoc.org/github.com/SaidinWoT/timespan)
* [date](https://github.com/rickb777/date) **star:31** 增加处理日期、日期范围、时间跨度、时间段和time-of-day。   [![godoc][GoDoc]](https://godoc.org/github.com/rickb777/date)
* [feiertage](https://github.com/wlbr/feiertage) **star:23** 用于计算德国公共假期的函数，比如复活节、感恩节等   [![godoc][GoDoc]](https://godoc.org/github.com/wlbr/feiertage)
* [goweek](https://github.com/grsmv/goweek) **star:18** 用于处理以星期实体单位的库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/grsmv/goweek)
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) **star:14** 计算指定位置的日出和日落时间。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/nathan-osman/go-sunrise)
* [kair](https://github.com/GuilhermeCaruso/kair) **star:12** 用于处理日期和时间的 golang 库。   [![godoc][GoDoc]](https://godoc.org/github.com/GuilhermeCaruso/kair)
* [NullTime](https://github.com/kirillDanshin/nulltime) **star:9** 可以允许 time.Time 为null。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/kirillDanshin/nulltime)
* [tuesday](https://github.com/osteele/tuesday) **star:7** Ruby-compatible Strftime function。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/osteele/tuesday)
* [strftime](https://github.com/awoodbeck/strftime) **star:5** C99-compatible strftime formatter。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/awoodbeck/strftime)

## 分布式系统

*协助构建分布式系统的包。 (翻译出错了? 试试 [英文版](README_EN.md#distributed-systems) 吧~)*

* [go-kit](https://github.com/go-kit/kit) **star:15038** 支持服务发现、负载平衡、插件式传输、请求跟踪等功能的Microservice toolkit。   [![star > 2000][Awesome]](https://github.com/go-kit/kit)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-kit/kit)
* [grpc-go](https://github.com/grpc/grpc-go) **star:9623** gRPC的Go语言实现。   [![star > 2000][Awesome]](https://github.com/grpc/grpc-go)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/grpc/grpc-go)
* [micro](https://github.com/micro/micro) **star:6796** 可插拔的微服务 toolkit 和分布式系统平台。   [![star > 2000][Awesome]](https://github.com/micro/micro)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/micro/micro)
* [NATS](https://github.com/nats-io/gnatsd) **star:6629** 轻量级、高性能消息传递系统，可用于微服务、物联网(IoT)和云。   [![star > 2000][Awesome]](https://github.com/nats-io/gnatsd)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/nats-io/gnatsd)
* [rpcx](https://github.com/smallnest/rpcx) **star:4017** 分布式可插拔的RPC服务框架，如阿里巴巴Dubbo。   [![star > 2000][Awesome]](https://github.com/smallnest/rpcx)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/smallnest/rpcx)
* [tendermint](https://github.com/tendermint/tendermint) **star:3274** 一个高性能中间件，可将任何语言的状态机转换为 Byzantine Fault 状态机。使用 Tendermint 一致性及区块链协议。   [![star > 2000][Awesome]](https://github.com/tendermint/tendermint)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/tendermint/tendermint)
* [torrent](https://github.com/anacrolix/torrent) **star:3072** BitTorrent 客户端。   [![star > 2000][Awesome]](https://github.com/anacrolix/torrent)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/anacrolix/torrent)
* [raft](https://github.com/hashicorp/raft) **star:2964** Raft consensus协议的实现。 by HashiCorp。   [![star > 2000][Awesome]](https://github.com/hashicorp/raft)   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/raft)
* [raft](https://github.com/coreos/etcd/tree/master/raft)  Raft consensus协议的实现。 by CoreOS。
* [dragonboat](https://github.com/lni/dragonboat) **star:2651** 一个功能齐全，高性能的库集。   [![star > 2000][Awesome]](https://github.com/lni/dragonboat)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/lni/dragonboat)   ![包含中文文档][CN]
* [glow](https://github.com/chrislusf/glow) **star:2650** 全部用 Go 实现，易用、可伸缩，可用于分布式大数据处理，Map-Reduce, DAG执行。   [![star > 2000][Awesome]](https://github.com/chrislusf/glow)   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/glow)
* [gleam](https://github.com/chrislusf/gleam) **star:2209** 使用纯Go和Luajit编写的快速、可伸缩的分布式map/reduce系统，结合了Go的高并发性和Luajit的高性能，可以独立运行或分布式运行。   [![star > 2000][Awesome]](https://github.com/chrislusf/gleam)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/gleam)
* [emitter-io](https://github.com/emitter-io/emitter) **star:2040** 高性能、分布式、安全和低延迟的发布-订阅平台，使用MQTT、Websockets和love构建。   [![star > 2000][Awesome]](https://github.com/emitter-io/emitter)   [![godoc][GoDoc]](https://godoc.org/github.com/emitter-io/emitter)
* [KrakenD](https://github.com/devopsfaith/krakend) **star:1954** 具有中间件的高性能API网关框架。   [![godoc][GoDoc]](https://godoc.org/github.com/devopsfaith/krakend)
* [hprose](https://github.com/hprose/hprose-golang) **star:1034** 支持25+种语言RPC库。   [![godoc][GoDoc]](https://godoc.org/github.com/hprose/hprose-golang)   ![包含中文文档][CN]
* [ringpop-go](https://github.com/uber/ringpop-go) **star:579** 可伸缩的，容错、应用分层的的Go应用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/uber/ringpop-go)
* [gorpc](https://github.com/valyala/gorpc) **star:562** 简单、快速和可伸缩的RPC库。   [![godoc][GoDoc]](https://godoc.org/github.com/valyala/gorpc)
* [go-health](https://github.com/InVisionApp/go-health) **star:498** 用于在服务中启用异步依赖项健康检查的库。   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/go-health)
* [rain](https://github.com/cenkalti/rain) **star:341** BitTorrent客户端和库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/cenkalti/rain)
* [dot](https://github.com/dotchain/dot/)  基于 transformation/OT 的分布式同步。
* [digota](https://github.com/digota/digota) **star:310** 基于 grpc 的电子商务微服务。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/digota/digota)
* [sleuth](https://github.com/ursiform/sleuth) **star:302** 用于HTTP服务之间进行无中心p2p自动发现和RPC通信的库(使用[ZeroMQ](https://github.com/zeromq/libzmq))。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ursiform/sleuth)
* [go-jump](https://github.com/dgryski/go-jump) **star:260** 提供了谷歌的 “Jump” 一致哈希函数接口。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dgryski/go-jump)
* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) **star:259** 为支持为golang服务定义异步服务健康检查而构建的库。   [![godoc][GoDoc]](https://godoc.org/github.com/AppsFlyer/go-sundheit)
* [consistent](https://github.com/buraksezer/consistent) **star:215** Consistent hashing with bounded loads。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/buraksezer/consistent)
* [dht](https://github.com/anacrolix/dht) **star:133** BitTorrent Kademlia DHT的实现。   [![godoc][GoDoc]](https://godoc.org/github.com/anacrolix/dht)
* [jsonrpc](https://github.com/osamingo/jsonrpc) **star:115** jsonrpc 包，实现了 JSON-RPC 2.0。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/jsonrpc)
* [jsonrpc](https://github.com/ybbus/jsonrpc) **star:105** JSON-RPC 2.0 HTTP客户端。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/ybbus/jsonrpc)
* [celeriac](https://github.com/svcavallar/celeriac.v1) **star:55** 用于对 Celery worker、任务、事件进行交互和监控的库。   [![godoc][GoDoc]](https://godoc.org/github.com/svcavallar/celeriac.v1)
* [redis-lock](https://github.com/bsm/redislock) **star:46** 基于redis的分布式锁简易实现。   [![godoc][GoDoc]](https://godoc.org/github.com/bsm/redislock)
* [resgate](https://resgate.io/)  用于构建REST、实时和RPC API的实时API网关，其中所有客户端都是无缝同步的。
* [doublejump](https://github.com/edwingeng/doublejump) **star:41** 实现了谷歌的jump consistent hash。   [![godoc][GoDoc]](https://godoc.org/github.com/edwingeng/doublejump)
* [dynamolock](https://cirello.io/dynamolock)  DynamoDB-backed 分布式锁定实现。
* [drmaa](https://github.com/dgruber/drmaa) **star:25** 符合 DRMAA 标准的集群调度程序作业提交库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dgruber/drmaa)
* [flowgraph](https://github.com/vectaport/flowgraph) **star:21** flow-based programming package。   [![godoc][GoDoc]](https://godoc.org/github.com/vectaport/flowgraph)
* [pglock](https://cirello.io/pglock)  postgresql 的分布式锁定实现。
* [outboxer](https://github.com/italolelis/outboxer) **star:10** 实现了 outbox pattern Go 库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/italolelis/outboxer)
* [dynatomic](https://github.com/tylfin/dynatomic) **star:8** 基于 DynamoDB 的 原子计数器的库。   [![godoc][GoDoc]](https://godoc.org/github.com/tylfin/dynatomic)

## 电子邮件

*实现了电子邮件创建和发送。 (翻译出错了? 试试 [英文版](README_EN.md#email) 吧~)*

* [MailHog](https://github.com/mailhog/MailHog) **star:5385** 电子邮件和SMTP测试工具，对外提供了 web 和 API 接口。   [![star > 2000][Awesome]](https://github.com/mailhog/MailHog)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mailhog/MailHog)
* [chasquid](https://blitiri.com.ar/p/chasquid)  用Go编写的SMTP服务器。
* [hermes](https://github.com/matcornic/hermes) **star:1656** 可生成干净的、响应式的HTML电子邮件。   [![godoc][GoDoc]](https://godoc.org/github.com/matcornic/hermes)
* [email](https://github.com/jordan-wright/email) **star:1124** 一个强大和灵活的电子邮件库。   [![godoc][GoDoc]](https://godoc.org/github.com/jordan-wright/email)
* [go-imap](https://github.com/emersion/go-imap) **star:770** 用于客户端和服务器的IMAP库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/emersion/go-imap)
* [SendGrid](https://github.com/sendgrid/sendgrid-go) **star:535** SendGrid 的 Go语言库，用于发送电子邮件。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/sendgrid/sendgrid-go)
* [mailgun-go](https://github.com/mailgun/mailgun-go) **star:399** 使用Mailgun API去库发送邮件。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mailgun/mailgun-go)
* [Hectane](https://github.com/hectane/hectane) **star:169** 轻量级的SMTP客户机，提供了HTTP API。   [![godoc][GoDoc]](https://godoc.org/github.com/hectane/hectane)
* [douceur](https://github.com/aymerick/douceur) **star:163** 在HTML邮件中支持CSS内联。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/aymerick/douceur)
* [go-message](https://github.com/emersion/go-message) **star:123** 用于Internet消息格式化和邮件消息的流媒体库。   [![godoc][GoDoc]](https://godoc.org/github.com/emersion/go-message)
* [smtp](https://github.com/mailhog/smtp) **star:52** SMTP服务器协议状态机。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mailhog/smtp)
* [go-dkim](https://github.com/toorop/go-dkim) **star:49** DKIM库，用于签署 & 验证电子邮件。   [![godoc][GoDoc]](https://godoc.org/github.com/toorop/go-dkim)
* [go-premailer](https://github.com/vanng822/go-premailer) **star:37** 在HTML邮件中支持CSS内联。   [![godoc][GoDoc]](https://godoc.org/github.com/vanng822/go-premailer)
* [go-simple-mail](https://github.com/xhit/go-simple-mail) **star:4** 非常简单的包发送电子邮件与SMTP保持活动和两个超时:连接和发送。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/xhit/go-simple-mail)
* [Gomail](https://github.com/go-gomail/gomail/)  一个非常简单和强大的邮件发送库。

## 可嵌入的脚本语言

*在go代码中嵌入其他语言。 (翻译出错了? 试试 [英文版](README_EN.md#embeddable-scripting-languages) 吧~)*

* [otto](https://github.com/robertkrimen/otto) **star:4845** 用 Go 编写的 JavaScript 解释器。   [![star > 2000][Awesome]](https://github.com/robertkrimen/otto)   [![godoc][GoDoc]](https://godoc.org/github.com/robertkrimen/otto)
* [gopher-lua](https://github.com/yuin/gopher-lua) **star:3048** 用 Go 实现的 Lua 5.1 虚拟机和编译器。   [![star > 2000][Awesome]](https://github.com/yuin/gopher-lua)   [![godoc][GoDoc]](https://godoc.org/github.com/yuin/gopher-lua)
* [go-lua](https://github.com/Shopify/go-lua) **star:1707** 用 Go 实现的 Lua 5.2 VM接口。   [![godoc][GoDoc]](https://godoc.org/github.com/Shopify/go-lua)
* [tengo](https://github.com/d5/tengo) **star:1409** 字节码编译的脚本语言。   [![godoc][GoDoc]](https://godoc.org/github.com/d5/tengo)
* [anko](https://github.com/mattn/anko) **star:945** 用Go编写的解释器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/anko)
* [go-python](https://github.com/sbinet/go-python) **star:937** CPython C-API 的 Go 接口。   [![godoc][GoDoc]](https://godoc.org/github.com/sbinet/go-python)
* [expr](https://github.com/antonmedv/expr) **star:800** 一个可以计算表达式的引擎。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/antonmedv/expr)
* [go-php](https://github.com/deuill/go-php) **star:700** PHP 的 Go 接口。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/deuill/go-php)
* [go-duktape](https://github.com/olebedev/go-duktape) **star:660** 支持 Duktape JavaScript 引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/go-duktape)
* [golua](https://github.com/aarzilli/golua) **star:449** Lua C 的 Go 接口。
* [gisp](https://github.com/jcla1/gisp) **star:430** LISP 的 Go 接口。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/jcla1/gisp)
* [agora](https://github.com/PuerkitoBio/agora) **star:324** 基于 Go 的动态类型，可嵌入的编程语言。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/PuerkitoBio/agora)   ![归档项目][Archived]
* [gval](https://github.com/PaesslerAG/gval) **star:150** 一种用Go编写的高度可定制的表达式语言。   [![godoc][GoDoc]](https://godoc.org/github.com/PaesslerAG/gval)
* [gentee](https://github.com/gentee/gentee) **star:34** 嵌入式脚本编程语言。   [![godoc][GoDoc]](https://godoc.org/github.com/gentee/gentee)
* [binder](https://github.com/alexeyco/binder) **star:32** Lua接口，基于[gopher-lua](https://github.com/yuin/gopher-lua)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/alexeyco/binder)
* [purl](https://github.com/ian-kent/purl) **star:27** 嵌入 Go 的 Perl 5.18.2。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/purl)
* [ngaro](https://github.com/db47h/ngaro) **star:19** 嵌入式 Ngaro VM实现，支持在 Retro 中运行脚本。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/db47h/ngaro)

## 错误处理

*处理错误的库。 (翻译出错了? 试试 [英文版](README_EN.md#error-handling) 吧~)*

* [errors](https://github.com/pkg/errors) **star:5145** 可让你很简单的进行错误处理。   [![star > 2000][Awesome]](https://github.com/pkg/errors)   [![godoc][GoDoc]](https://godoc.org/github.com/pkg/errors)
* [go-multierror](https://github.com/hashicorp/go-multierror) **star:755** 可将一系列的错误作为一个整体来显示。   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/go-multierror)
* [errorx](https://github.com/joomcode/errorx) **star:596** 一个功能丰富的错误包，可进行堆栈跟踪、组装异常信息以及其他。   [![godoc][GoDoc]](https://godoc.org/github.com/joomcode/errorx)
* [tracerr](https://github.com/ztrue/tracerr) **star:511** 可展示错误的堆栈跟踪信息和源码片段。   [![godoc][GoDoc]](https://godoc.org/github.com/ztrue/tracerr)
* [errlog](https://github.com/snwfdhmp/errlog) **star:197** 用于定位抛出错误的源代码(以及一些其他快速调试特性)。可插入到任何 logger 的位置。   [![godoc][GoDoc]](https://godoc.org/github.com/snwfdhmp/errlog)
* [emperror](https://github.com/emperror/emperror) **star:71** 用于Go库和应用程序的错误处理工具和最佳实践。   [![godoc][GoDoc]](https://godoc.org/github.com/emperror/emperror)
* [werr](https://github.com/txgruppi/werr) **star:11** 对错误异常进行了捕获封装，封装信息包含了调用它的文件、行和堆栈。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/txgruppi/werr)
* [errors](https://github.com/emperror/errors) **star:10** 替换标准库错误包和github.com/pkg/errors。提供各种错误处理原语。   [![godoc][GoDoc]](https://godoc.org/github.com/emperror/errors)
* [errors](https://github.com/neuronlabs/errors) **star:2** 使用分类原语进行简单的golang错误处理。   [![godoc][GoDoc]](https://godoc.org/github.com/neuronlabs/errors)
* [Falcon](https://github.com/SonicRoshan/falcon) **star:2** 一个简单但功能强大的错误处理包。   [![godoc][GoDoc]](https://godoc.org/github.com/SonicRoshan/falcon)

## 文件

*处理文件和文件系统的库。 (翻译出错了? 试试 [英文版](README_EN.md#files) 吧~)*

* [afero](https://github.com/spf13/afero) **star:2342** 文件系统的抽象系统。   [![star > 2000][Awesome]](https://github.com/spf13/afero)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/afero)
* [pdfcpu](https://github.com/hhrutter/pdfcpu) **star:1131** PDF处理器。   [![godoc][GoDoc]](https://godoc.org/github.com/hhrutter/pdfcpu)
* [notify](https://github.com/rjeczalik/notify) **star:509** 文件系统事件通知库，具有类似于os/signal的简单API，。   [![godoc][GoDoc]](https://godoc.org/github.com/rjeczalik/notify)
* [bigfile](https://github.com/bigfile/bigfile) **star:73** 一个文件传输系统，支持管理文件与http api, rpc调用和ftp客户端。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/bigfile/bigfile)   ![包含中文文档][CN]
* [opc](https://github.com/qmuntal/opc) **star:62** 加载Open Packaging Conventions (OPC)文件。   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/opc)
* [go-csv-tag](https://github.com/artonge/go-csv-tag) **star:51** 使用 tag 加载 csv 文件。   [![godoc][GoDoc]](https://godoc.org/github.com/artonge/go-csv-tag)
* [skywalker](https://github.com/dixonwille/skywalker) **star:49** 可以轻松地并发地遍历文件系统。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/skywalker)
* [stl](https://gitlab.com/russoj88/stl)  采用并行读取算法的进行读取和写入STL(立体光刻)文件的模块。
* [tarfs](https://github.com/posener/tarfs) **star:37** tar文件的实现[ FileSystem 接口](https://godoc.org/github.com/kr/fs#FileSystem)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/posener/tarfs)
* [vfs](https://github.com/C2FO/vfs) **star:29** 一组可插拔的、可扩展的和自定义的文件系统功能，用于跨越许多文件系统类型，如os、S3和GCS。   [![godoc][GoDoc]](https://godoc.org/github.com/C2FO/vfs)
* [go-gtfs](https://github.com/artonge/go-gtfs) **star:15** 加载gtfs文件。   [![godoc][GoDoc]](https://godoc.org/github.com/artonge/go-gtfs)
* [checksum](https://github.com/codingsince1985/checksum) **star:11** 生成大型文件的消息摘要(如 MD5 和 SHA256)。   [![godoc][GoDoc]](https://godoc.org/github.com/codingsince1985/checksum)
* [flop](https://github.com/homedepot/flop) **star:11** 文件操作库，是[GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invoc.html)的镜像。   [![godoc][GoDoc]](https://godoc.org/github.com/homedepot/flop)
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) **star:11** 拷贝文件。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/hugocarreira/go-decent-copy)
* [afs](https://github.com/viant/afs) **star:8** 用于Go的抽象文件存储(mem、scp、zip、tar、cloud: s3、gs)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/viant/afs)
* [go-exiftool](https://github.com/barasher/go-exiftool) **star:7** ExifTool 的 Go 实现，这个著名的库用于从文件(图片、PDF、office，…)中提取尽可能多的元数据(EXIF、IPTC，…)。   [![godoc][GoDoc]](https://godoc.org/github.com/barasher/go-exiftool)

## 金融

*会计和财务软件包。 (翻译出错了? 试试 [英文版](README_EN.md#financial) 吧~)*

* [decimal](https://github.com/shopspring/decimal) **star:1702** 任意精度定点的十进制数。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/shopspring/decimal)
* [go-money](https://github.com/rhymond/go-money) **star:649** Fowler 货币模式的实现。   [![godoc][GoDoc]](https://godoc.org/github.com/rhymond/go-money)
* [go-finance](https://github.com/FlashBoys/go-finance) **star:538** 综合金融市场数据。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/FlashBoys/go-finance)
* [accounting](https://github.com/leekchan/accounting) **star:502** 货币和货币格式。   [![godoc][GoDoc]](https://godoc.org/github.com/leekchan/accounting)
* [techan](https://github.com/sdcoffey/techan) **star:187** 拥有先进的市场分析和交易策略的技术分析库。   [![godoc][GoDoc]](https://godoc.org/github.com/sdcoffey/techan)
* [orderbook](https://github.com/i25959341/orderbook) **star:87** 限购单匹配引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/i25959341/orderbook)
* [ofxgo](https://github.com/aclindsa/ofxgo) **star:68** 查询 OFX 服务器和/或解析响应。   [![godoc][GoDoc]](https://godoc.org/github.com/aclindsa/ofxgo)
* [vat](https://github.com/dannyvankooten/vat) **star:60** 增值税编号验证 & 欧盟增值税税率。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dannyvankooten/vat)
* [transaction](https://github.com/claygod/transaction) **star:56** 嵌入式事务数据库，可多线程模式运行。   [![godoc][GoDoc]](https://godoc.org/github.com/claygod/transaction)
* [go-finance](https://github.com/alpeb/go-finance) **star:45** 用于货币时间价值(年金)、现金流、利率转换、债券和折旧计算的金融函数库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/alpeb/go-finance)
* [currency](https://github.com/bnkamalesh/currency) **star:11** 高性能、准确的货币计算软件包。   [![godoc][GoDoc]](https://godoc.org/github.com/bnkamalesh/currency)

## 表单

*用于处理表单的库。 (翻译出错了? 试试 [英文版](README_EN.md#forms) 吧~)*

* [nosurf](https://github.com/justinas/nosurf) **star:994** CSRF保护中间件。   [![godoc][GoDoc]](https://godoc.org/github.com/justinas/nosurf)
* [binding](https://github.com/mholt/binding) **star:756** 将来自 net/HTTP 请求的表单、JSON 数据绑定到结构体。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mholt/binding)
* [gorilla/csrf](https://github.com/gorilla/csrf) **star:461** 用于Go web应用程序和服务的CSRF保护。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gorilla/csrf)
* [form](https://github.com/go-playground/form) **star:360**  将 url 中的数据解析到 Go 变量中，以及将 Go 语言变量编码进 url。支持 Dual Array 及 Full map。   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/form)
* [conform](https://github.com/leebenson/conform) **star:173** 控制用户输入。基于struct tags可对数据进行修剪、清理和擦除。   [![godoc][GoDoc]](https://godoc.org/github.com/leebenson/conform)
* [formam](https://github.com/monoculum/formam) **star:131** 将表单的值解码为 struct。   [![godoc][GoDoc]](https://godoc.org/github.com/monoculum/formam)
* [forms](https://github.com/albrow/forms) **star:105** 与框架无关的库，用于解析和验证支持多部分表单和文件的表单/JSON数据。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/albrow/forms)
* [bind](https://github.com/robfig/bind) **star:24** 将表单数据与任意 Go 变量进行绑定。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/robfig/bind)

## 方法

*在Go中支持函数式编程的包。 (翻译出错了? 试试 [英文版](README_EN.md#functional) 吧~)*

* [go-underscore](https://github.com/tobyhede/go-underscore) **star:1084** 常用辅助方法集合。   [![godoc][GoDoc]](https://godoc.org/github.com/tobyhede/go-underscore)
* [fpGo](https://github.com/TeaEntityLab/fpGo) **star:119** 提供函数式编程功能。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/TeaEntityLab/fpGo)
* [fuego](https://github.com/seborama/fuego) **star:51** Functional Experiment in Go。   [![godoc][GoDoc]](https://godoc.org/github.com/seborama/fuego)

## 游戏开发

*很棒的游戏开发库。 (翻译出错了? 试试 [英文版](README_EN.md#game-development) 吧~)*

* [Leaf](https://github.com/name5566/leaf) **star:3184** 轻量级游戏服务器框架。   [![star > 2000][Awesome]](https://github.com/name5566/leaf)   [![godoc][GoDoc]](https://godoc.org/github.com/name5566/leaf)   ![包含中文文档][CN]
* [Pixel](https://github.com/faiface/pixel) **star:2537** 手工制作的 2D 游戏库。   [![star > 2000][Awesome]](https://github.com/faiface/pixel)   [![godoc][GoDoc]](https://godoc.org/github.com/faiface/pixel)
* [Ebiten](https://github.com/hajimehoshi/ebiten) **star:2023** 很简单的 2D 游戏库。   [![star > 2000][Awesome]](https://github.com/hajimehoshi/ebiten)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/hajimehoshi/ebiten)
* [goworld](https://github.com/xiaonanln/goworld) **star:1259** 可伸缩的游戏服务器引擎，具有 space-entity 框架和 hot-swapping 功能。   [![godoc][GoDoc]](https://godoc.org/github.com/xiaonanln/goworld)   ![包含中文文档][CN]
* [go-sdl2](https://github.com/veandco/go-sdl2) **star:1189** 实现了[Simple DirectMedia Layer](https://www.libsdl.org/)。
* [engo](https://github.com/EngoEngine/engo) **star:1108** 开源 2D 游戏引擎。它遵循 Entity-Component-System 范式。   [![godoc][GoDoc]](https://godoc.org/github.com/EngoEngine/engo)
* [gonet](https://github.com/xtaci/gonet) **star:1065** 实现了游戏服务器骨架。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/xtaci/gonet)
* [nano](https://github.com/lonng/nano) **star:1060** 轻量级、方便、高性能的基于golang的游戏服务器框架。   [![godoc][GoDoc]](https://godoc.org/github.com/lonng/nano)   ![包含中文文档][CN]
* [termloop](https://github.com/JoelOtter/termloop) **star:1034** 基于终端的 Go 游戏引擎，建立在 Termbox 之上。   [![godoc][GoDoc]](https://godoc.org/github.com/JoelOtter/termloop)
* [g3n](https://github.com/g3n/engine) **star:811**  3D游戏引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/g3n/engine)
* [Oak](https://github.com/oakmound/oak) **star:669** 纯 Go 实现的游戏引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/oakmound/oak)
* [Azul3D](https://github.com/azul3d/engine) **star:428** 用Go编写的 3D 游戏引擎。   ![最近一年没有更新][Yellow]
* [raylib-go](https://github.com/gen2brain/raylib-go) **star:397** 实现了 [raylib](http://www.raylib.com/)，一个简单易用的库，用于学习视频游戏编程。   ![最近一周有更新][Green]
* [go-astar](https://github.com/beefsack/go-astar) **star:333** 实现了A\*路径查找算法。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/beefsack/go-astar)
* [Pitaya](https://github.com/topfreegames/pitaya) **star:324** 可伸缩的游戏服务器框架，支持集群和客户端库的iOS, Android, Unity。   [![godoc][GoDoc]](https://godoc.org/github.com/topfreegames/pitaya)
* [GarageEngine](https://github.com/vova616/GarageEngine) **star:314** 用 OpenGL 编写的 2D 游戏引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/vova616/GarageEngine)
* [go3d](https://github.com/ungerik/go3d) **star:167** 以性能为主的2D/3D数学相关包。   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/go3d)
* [glop](https://github.com/runningwild/glop) **star:77** Glop (Game Library Of Power) 是一个相当简单的跨平台游戏库。   ![最近一年没有更新][Yellow]
* [go-collada](https://github.com/GlenKelley/go-collada) **star:14** 处理Collada文件。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/GlenKelley/go-collada)

## 代码生成与泛型

*增强语言的工具，例如通过代码生成支持泛型。 (翻译出错了? 试试 [英文版](README_EN.md#generation-and-generics) 吧~)*

* [go-linq](https://github.com/ahmetalpbalkan/go-linq) **star:1839** 提供类似 .NET LINQ 的查询方法。   [![godoc][GoDoc]](https://godoc.org/github.com/ahmetalpbalkan/go-linq)
* [jennifer](https://github.com/dave/jennifer) **star:1338** 不使用模板生成任意 Go 代码。   [![godoc][GoDoc]](https://godoc.org/github.com/dave/jennifer)
* [gen](https://github.com/clipperhouse/gen) **star:1050** 用于生成泛型等类似方法的功能代码生成工具。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/clipperhouse/gen)
* [goderive](https://github.com/awalterschulze/goderive) **star:763** 从输入类型来派生函数。   [![godoc][GoDoc]](https://godoc.org/github.com/awalterschulze/goderive)
* [GoWrap](https://github.com/hexdigest/gowrap) **star:291** 使用简单模板为 Go 接口生成装饰器。   [![godoc][GoDoc]](https://godoc.org/github.com/hexdigest/gowrap)
* [interfaces](https://github.com/rjeczalik/interfaces) **star:190** 用于生成接口定义的命令行工具。   [![godoc][GoDoc]](https://godoc.org/github.com/rjeczalik/interfaces)
* [go-enum](https://github.com/abice/go-enum) **star:90** 从代码注释中生成枚举。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/abice/go-enum)
* [pkgreflect](https://github.com/ungerik/pkgreflect) **star:88** 用于包作用域反射的 Go 预处理器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/pkgreflect)
* [efaceconv](https://github.com/t0pep0/efaceconv) **star:44** 代码生成工具，可以不通过内存分配就可以高效的将interface{}转换为不可变类型，。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/t0pep0/efaceconv)
* [gotype](https://github.com/wzshiming/gotype) **star:23** Golang 源码解析，用法类似reflect(反射)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/wzshiming/gotype)   ![包含中文文档][CN]
* [generis](https://github.com/senselogic/GENERIS) **star:19** 提供泛型、free-form 宏、条件编译和HTML模板的代码生成工具。

## 地理

*地理工具和服务器 (翻译出错了? 试试 [英文版](README_EN.md#geographic) 吧~)*

* [Tile38](https://github.com/tidwall/tile38) **star:6451** 具有空间索引和实时地理定位功能的地理定位数据库。   [![star > 2000][Awesome]](https://github.com/tidwall/tile38)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/tile38)
* [S2 geometry](https://github.com/golang/geo) **star:928** S2 geometry 库。   [![godoc][GoDoc]](https://godoc.org/github.com/golang/geo)
* [geocache](https://github.com/melihmucuk/geocache) **star:113** 基于内存缓存的的地理位置的应用程序。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/melihmucuk/geocache)
* [osm](https://github.com/paulmach/osm) **star:78** 用于读取、写入和处理 OpenStreetMap 数据和 APIs。   [![godoc][GoDoc]](https://godoc.org/github.com/paulmach/osm)
* [geoserver](https://github.com/hishamkaram/geoserver) **star:25** 基于geoserver REST API的 geoserver 实例。   [![godoc][GoDoc]](https://godoc.org/github.com/hishamkaram/geoserver)
* [gismanager](https://github.com/hishamkaram/gismanager) **star:20** 将你的 GIS 数据(矢量数据)发布到 PostGIS 和 Geoserver。   [![godoc][GoDoc]](https://godoc.org/github.com/hishamkaram/gismanager)
* [pbf](https://github.com/maguro/pbf) **star:17** 基于Golang 的 OpenStreetMap PBF 编码器/解码器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/maguro/pbf)

## Go 编译器

*可将 Go 转换为其他语言的编译工具。 (翻译出错了? 试试 [英文版](README_EN.md#go-compilers) 吧~)*

* [gopherjs](https://github.com/gopherjs/gopherjs) **star:8741** 将 Go 编译成 JavaScript。   [![star > 2000][Awesome]](https://github.com/gopherjs/gopherjs)   [![godoc][GoDoc]](https://godoc.org/github.com/gopherjs/gopherjs)
* [llgo](https://github.com/go-llvm/llgo) **star:998** 基于 llvm 的编译器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-llvm/llgo)
* [tardisgo](https://github.com/tardisgo/tardisgo) **star:391** Golang 转换为 Haxe，再转换为 CPP/CSharp/Java/JavaScript 的编译器.   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tardisgo/tardisgo)
* [c4go](https://github.com/Konstantin8105/c4go) **star:174** 将 C 代码转换为 Go 代码。   [![godoc][GoDoc]](https://godoc.org/github.com/Konstantin8105/c4go)
* [f4go](https://github.com/Konstantin8105/f4go) **star:15** 将 FORTRAN 77 转换为 Go代码。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/Konstantin8105/f4go)

## Goroutines

*管理和处理 Goroutines 的工具。 (翻译出错了? 试试 [英文版](README_EN.md#goroutines) 吧~)*

* [ants](https://github.com/panjf2000/ants) **star:2304** 一个高性能的协程池。   [![star > 2000][Awesome]](https://github.com/panjf2000/ants)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/panjf2000/ants)   ![包含中文文档][CN]
* [goworker](https://github.com/benmanns/goworker) **star:2276** 基于 go 的后台 worker。   [![star > 2000][Awesome]](https://github.com/benmanns/goworker)   [![godoc][GoDoc]](https://godoc.org/github.com/benmanns/goworker)
* [tunny](https://github.com/Jeffail/tunny) **star:1405** golang 的协程池。   [![godoc][GoDoc]](https://godoc.org/github.com/Jeffail/tunny)
* [grpool](https://github.com/ivpusic/grpool) **star:522** 轻量级协程池。   [![godoc][GoDoc]](https://godoc.org/github.com/ivpusic/grpool)
* [pool](https://github.com/go-playground/pool) **star:503** 有限消费者协程或无限协程池，可用于更加简单的处理和取消协程   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/pool)
* [go-floc](https://github.com/workanator/go-floc) **star:171** 轻松编排 goroutines。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/workanator/go-floc)
* [workerpool](https://github.com/gammazero/workerpool) **star:159** 限制任务执行并发数，而不是队列中的任务数量的协程池，。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gammazero/workerpool)
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) **star:112** 控制 goroutines 的执行顺序。   [![godoc][GoDoc]](https://godoc.org/github.com/kamildrazkiewicz/go-flow)
* [GoSlaves](https://github.com/themester/GoSlaves) **star:88** 简单异步的协程池。   [![godoc][GoDoc]](https://godoc.org/github.com/themester/GoSlaves)
* [semaphore](https://github.com/marusama/semaphore) **star:77** 基于 CAS 的可快速调整的信号量实现(比基于通道的信号量实现更快)。   [![godoc][GoDoc]](https://godoc.org/github.com/marusama/semaphore)
* [semaphore](https://github.com/kamilsk/semaphore) **star:77** 信号量模式实现，可根据通道和上下文进行具备超时功能的锁定/解锁操作。   [![godoc][GoDoc]](https://godoc.org/github.com/kamilsk/semaphore)
* [gpool](https://github.com/Sherifabdlnaby/gpool) **star:57** manages a resizeable pool of context-aware goroutines to bound concurrency   [![godoc][GoDoc]](https://godoc.org/github.com/Sherifabdlnaby/gpool)
* [worker-pool](https://github.com/vardius/worker-pool) **star:49** 一个简单的 Go 异步工作池。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/worker-pool)
* [breaker](https://github.com/kamilsk/breaker) **star:42** 灵活的机制，可以使执行流可中断。   [![godoc][GoDoc]](https://godoc.org/github.com/kamilsk/breaker)
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) **star:40** 基于 Go 的 CyclicBarrier 实现。   [![godoc][GoDoc]](https://godoc.org/github.com/marusama/cyclicbarrier)
* [gollback](https://github.com/vardius/gollback) **star:28** 异步简单的函数实用程序，用于管理闭包和回调的执行。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/gollback)
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) **star:25** 并行运行函数。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/parallel-fn)
* [async](https://github.com/studiosol/async) **star:23** 一种异步执行函数的安全方法，在出现 panic 时恢复它们。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/studiosol/async)
* [threadpool](https://github.com/shettyh/threadpool) **star:21** Golang 的 threadpool 实现。   [![godoc][GoDoc]](https://godoc.org/github.com/shettyh/threadpool)
* [gowp](https://github.com/xxjwxc/gowp) **star:18** gowp是并发性限制goroutine池。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/xxjwxc/gowp)   ![包含中文文档][CN]
* [oversight](https://cirello.io/oversight)  完整的实现了Erlang supervision trees。
* [Hunch](https://github.com/AaronJan/Hunch) **star:16** Hunch 提供了诸如 All、First、Retry、Waterfall 等功能，这使得异步流控制更加直观。   [![godoc][GoDoc]](https://godoc.org/github.com/AaronJan/Hunch)
* [artifex](https://github.com/borderstech/artifex) **star:15** 简单的内存作业队列。   [![godoc][GoDoc]](https://godoc.org/github.com/borderstech/artifex)
* [stl](https://github.com/ssgreg/stl) **star:11** 基于软件事务内存(STM)并发控制机制的软件事务锁。   [![godoc][GoDoc]](https://godoc.org/github.com/ssgreg/stl)
* [gohive](https://github.com/loveleshsharma/gohive) **star:7** 一个高性能和易于使用的Goroutine池去。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/loveleshsharma/gohive)
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) **star:5** 轻量级的协程池库，可以通过简单的API来管理。   [![godoc][GoDoc]](https://godoc.org/github.com/nikhilsaraf/go-tools)
* [go-trylock](https://github.com/subchen/go-trylock) **star:4** 支持 read-write 锁。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/subchen/go-trylock)
* [routine](https://github.com/x-mod/routine) **star:4** go routine control with context, support: Main, Go, Pool and some useful Executors.   [![godoc][GoDoc]](https://godoc.org/github.com/x-mod/routine)
* [queue](https://github.com/AnikHasibul/queue) **star:2** 提供类似队列组可访问性 sync.WaitGroup 的功能。帮助你节流和限制协程、等待所有协程结束以及更多功能。   [![godoc][GoDoc]](https://godoc.org/github.com/AnikHasibul/queue)

## GUI

*用于构建GUI应用程序的库。 (翻译出错了? 试试 [英文版](README_EN.md#gui) 吧~)*

*工具包 (翻译出错了? 试试 [英文版](README_EN.md#gui) 吧~)*

* [ui](https://github.com/andlabs/ui) **star:7127** 跨平台的 Platform-native GUI 库。   [![star > 2000][Awesome]](https://github.com/andlabs/ui)   [![godoc][GoDoc]](https://godoc.org/github.com/andlabs/ui)
* [Wails](https://wails.app)  Mac, Windows, Linux桌面应用程序，主要基于含有内置的OS HTML渲染器的HTML UI。
* [fyne](https://github.com/fyne-io/fyne) **star:6675** 为 Go 而设计的跨平台的本地GUIs，使用EFL呈现。支持 : Linux, macOS, Windows。   [![star > 2000][Awesome]](https://github.com/fyne-io/fyne)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/fyne-io/fyne)
* [qt](https://github.com/therecipe/qt) **star:6329** 实现了 Qt 的 Go接口(支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi)。   [![star > 2000][Awesome]](https://github.com/therecipe/qt)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/therecipe/qt)
* [webview](https://github.com/zserge/webview) **star:4862** 跨平台webview窗口，具有简单的双向JavaScript绑定(Windows / macOS / Linux)。   [![star > 2000][Awesome]](https://github.com/zserge/webview)
* [walk](https://github.com/lxn/walk) **star:3825** Windows应用程序库。   [![star > 2000][Awesome]](https://github.com/lxn/walk)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/lxn/walk)
* [app](https://github.com/murlokswarm/app) **star:3082** 用于创建包含了 GO, HTML 和 CSS 的应用程序。支持 MacOS, Windows 正在开发中。   [![star > 2000][Awesome]](https://github.com/murlokswarm/app)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/murlokswarm/app)
* [go-astilectron](https://github.com/asticode/go-astilectron) **star:2777** 使用 GO 和 HTML/JS/CSS (电子驱动)进行构建跨平台 GUI 应用程序。   [![star > 2000][Awesome]](https://github.com/asticode/go-astilectron)   [![godoc][GoDoc]](https://godoc.org/github.com/asticode/go-astilectron)
* [go-gtk](http://mattn.github.io/go-gtk/)  实现了 GTK 的 Go接口。
* [go-sciter](https://github.com/sciter-sdk/go-sciter) **star:1499** 实现了 Sciter 的 Go 接口 : 用于现代桌面 UI 开发的可嵌入HTML/CSS/脚本引擎。可跨平台。   [![godoc][GoDoc]](https://godoc.org/github.com/sciter-sdk/go-sciter)
* [gotk3](https://github.com/gotk3/gotk3) **star:820** 实现了 GTK3 的 Go接口。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gotk3/gotk3)
* [gowd](https://github.com/dtylman/gowd) **star:219** 跨平台、快速、简单的桌面UI开发，采用了GO, HTML, CSS和NW.js实现。   [![godoc][GoDoc]](https://godoc.org/github.com/dtylman/gowd)

*交互 (翻译出错了? 试试 [英文版](README_EN.md#gui) 吧~)*

* [robotgo](https://github.com/go-vgo/robotgo) **star:4577** 实现跨平台的GUI系统自动化。包含了控制鼠标、键盘等功能。   [![star > 2000][Awesome]](https://github.com/go-vgo/robotgo)   ![最近一周有更新][Green]
* [systray](https://github.com/getlantern/systray) **star:837** 跨平台 Go 库，可在通知区放置图标和菜单。   [![godoc][GoDoc]](https://godoc.org/github.com/getlantern/systray)
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) **star:494** OSX 桌面通知库。   [![godoc][GoDoc]](https://godoc.org/github.com/deckarep/gosx-notifier)
* [trayhost](https://github.com/shurcooL/trayhost) **star:163** 跨平台 Go 库，可用于在主机操作系统的任务栏中放置图标。   [![godoc][GoDoc]](https://godoc.org/github.com/shurcooL/trayhost)
* [go-appindicator](https://github.com/dawidd6/go-appindicator) **star:4** 实现了 libappindicator3 C库 的 Go接口。   [![godoc][GoDoc]](https://godoc.org/github.com/dawidd6/go-appindicator)
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) **star:1** 用于通知计算机上的任何(可插入的)活动的 OSX 库。   [![godoc][GoDoc]](https://godoc.org/github.com/prashantgupta24/activity-tracker)
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) **star:1** OSX 睡眠/唤醒通知。   [![godoc][GoDoc]](https://godoc.org/github.com/prashantgupta24/mac-sleep-notifier)


## 硬件

*硬件交互相关的库、工具和教程。 (翻译出错了? 试试 [英文版](README_EN.md#hardware) 吧~)*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## 图片

*图像处理相关的库。 (翻译出错了? 试试 [英文版](README_EN.md#images) 吧~)*

* [imaging](https://github.com/disintegration/imaging) **star:2700** 简单的Go图像处理包。   [![star > 2000][Awesome]](https://github.com/disintegration/imaging)   [![godoc][GoDoc]](https://godoc.org/github.com/disintegration/imaging)
* [imaginary](https://github.com/h2non/imaginary) **star:2681** 用于图像大小调整的快速、简单的HTTP微服务。   [![star > 2000][Awesome]](https://github.com/h2non/imaginary)   [![godoc][GoDoc]](https://godoc.org/github.com/h2non/imaginary)
* [bild](https://github.com/anthonynsimon/bild) **star:2649** 纯Go语言实现的图像处理算法合集。   [![star > 2000][Awesome]](https://github.com/anthonynsimon/bild)   [![godoc][GoDoc]](https://godoc.org/github.com/anthonynsimon/bild)
* [gocv](https://github.com/hybridgroup/gocv) **star:2627** 使用OpenCV 3.3+实现的计算机视觉(ComputerVision)的Go语言包。   [![star > 2000][Awesome]](https://github.com/hybridgroup/gocv)   [![godoc][GoDoc]](https://godoc.org/github.com/hybridgroup/gocv)
* [ln](https://github.com/fogleman/ln) **star:2524** Go实现的3D线艺术（3D Line Art）渲染。   [![star > 2000][Awesome]](https://github.com/fogleman/ln)   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/ln)
* [resize](https://github.com/nfnt/resize) **star:2166** Go实现的使用常用的插值法（interpolation methods）调整图像大小的库。   [![star > 2000][Awesome]](https://github.com/nfnt/resize)   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/nfnt/resize)
* [gg](https://github.com/fogleman/gg) **star:1976** 纯Go语言实现的2D渲染。   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/gg)
* [pt](https://github.com/fogleman/pt) **star:1784** Go实现的路径跟踪（path tracing）引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/pt)
* [svgo](https://github.com/ajstarks/svgo) **star:1361**  Go实现的SVG生成库。   [![godoc][GoDoc]](https://godoc.org/github.com/ajstarks/svgo)
* [smartcrop](https://github.com/muesli/smartcrop) **star:1276** 为任意图片寻找合适的位置进行图片裁剪。   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/smartcrop)
* [gift](https://github.com/disintegration/gift) **star:1253** 图像处理包。   [![godoc][GoDoc]](https://godoc.org/github.com/disintegration/gift)
* [go-opencv](https://github.com/lazywei/go-opencv) **star:1116** OpenCV库的Go bindings。   [![godoc][GoDoc]](https://godoc.org/github.com/lazywei/go-opencv)
* [picfit](https://github.com/thoas/picfit) **star:1110** Go实现的图像调整服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/thoas/picfit)
* [geopattern](https://github.com/pravj/geopattern) **star:1016** 由字符串创建漂亮图案的图片生成器。   [![godoc][GoDoc]](https://godoc.org/github.com/pravj/geopattern)
* [imagick](https://github.com/gographics/imagick) **star:1013**  ImageMagick下MagickWand的C API的Go binding。   [![godoc][GoDoc]](https://godoc.org/github.com/gographics/imagick)
* [bimg](https://github.com/h2non/bimg) **star:832** 使用libvips实现的快速高效的图像处理包。   [![godoc][GoDoc]](https://godoc.org/github.com/h2non/bimg)
* [stegify](https://github.com/DimitarPetrov/stegify) **star:562**  Go实现的LSB隐写（LSB steganography），能够隐藏任何文件到一个图像中。   [![godoc][GoDoc]](https://godoc.org/github.com/DimitarPetrov/stegify)
* [mort](https://github.com/aldor007/mort) **star:371** Go语言实现的图像存储和处理服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/aldor007/mort)
* [canvas](https://github.com/tdewolff/canvas) **star:319** 矢量图形到PDF, SVG或光栅图像。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/tdewolff/canvas)
* [govatar](https://github.com/o1egl/govatar) **star:317** 生成有趣头像的库和CMD工具。   [![godoc][GoDoc]](https://godoc.org/github.com/o1egl/govatar)
* [image2ascii](https://github.com/qeesung/image2ascii) **star:311** 将图像转换为ASCII码。   [![godoc][GoDoc]](https://godoc.org/github.com/qeesung/image2ascii)
* [go-nude](https://github.com/koyachi/go-nude) **star:288** Go语言实现的裸照检测工具。   [![godoc][GoDoc]](https://godoc.org/github.com/koyachi/go-nude)
* [goimagehash](https://github.com/corona10/goimagehash) **star:241**  图像哈希处理的Go语言包。   [![godoc][GoDoc]](https://godoc.org/github.com/corona10/goimagehash)
* [rez](https://github.com/bamiaux/rez) **star:192** 纯Go语言和SIMD实现的图像大小调整。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/bamiaux/rez)
* [img](https://github.com/hawx/img) **star:130** 图像处理工具的集合。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/hawx/img)
* [darkroom](https://github.com/gojek/darkroom) **star:91** An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gojek/darkroom)
* [go-cairo](https://github.com/ungerik/go-cairo) **star:88**  cairo图形库的Go binding。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/go-cairo)
* [mergi](https://github.com/noelyahan/mergi) **star:81** 用于图像处理(合并、裁剪、调整大小、水印、动画)的工具和Go库。   [![godoc][GoDoc]](https://godoc.org/github.com/noelyahan/mergi)
* [go-gd](https://github.com/bolknote/go-gd) **star:51**  GD库的Go binding。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/bolknote/go-gd)
* [gltf](https://github.com/qmuntal/gltf) **star:45** 一个高效、健壮的glTF 2.0文件读取、写入和验证器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/gltf)
* [cameron](https://github.com/aofei/cameron) **star:35** 一个Go语言的头像生成器。   [![godoc][GoDoc]](https://godoc.org/github.com/aofei/cameron)
* [goimghdr](https://github.com/corona10/goimghdr) **star:31** Go语言实现的imghdr模块用于确定文件的图像类型。   [![godoc][GoDoc]](https://godoc.org/github.com/corona10/goimghdr)
* [steganography](https://github.com/auyer/steganography) **star:31** 纯Go实现的LSB隐写（LSB steganography）的库。   [![godoc][GoDoc]](https://godoc.org/github.com/auyer/steganography)
* [tga](https://github.com/ftrvxmtrx/tga) **star:25** tga包是一个TARGA图像的解码、编码器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ftrvxmtrx/tga)
* [go-webcolors](https://github.com/jyotiska/go-webcolors) **star:24** Python下webcolors库的Go语言调用。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/jyotiska/go-webcolors)
* [mpo](https://github.com/donatj/mpo) **star:6** MPO三维照片的解码和转换工具。   [![godoc][GoDoc]](https://godoc.org/github.com/donatj/mpo)

## 物联网

*物联网设备编程库。 (翻译出错了? 试试 [英文版](README_EN.md#iot-(internet-of-things)) 吧~)*

* [flogo](https://github.com/tibcosoftware/flogo) **star:1189** Flogo是一个面向物联网边缘应用和集成的开源框架。
* [gatt](https://github.com/paypal/gatt) **star:831** Gatt是一个用于构建低能耗蓝牙外围设备的Go语言包。   [![godoc][GoDoc]](https://godoc.org/github.com/paypal/gatt)
* [gobot](https://github.com/hybridgroup/gobot/)  Gobot是一个用于机器人、物理计算和物联网的框架。
* [mainflux](https://github.com/Mainflux/mainflux) **star:653** 工业物联网消息和设备管理服务器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/Mainflux/mainflux)
* [periph](https://periph.io/)  外围设备I/O与低级板(low-level board)设备接口。
* [devices](https://github.com/goiot/devices) **star:227** 一套用于物联网设备的库，实验性地用于x/exp/io。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/goiot/devices)
* [sensorbee](https://github.com/sensorbee/sensorbee) **star:184** 轻量级物联网流处理引擎。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sensorbee/sensorbee)
* [connectordb](https://github.com/connectordb/connectordb) **star:177** 自我量化和物联网的开源平台。   [![godoc][GoDoc]](https://godoc.org/github.com/connectordb/connectordb)
* [huego](https://github.com/amimof/huego) **star:116** 一个包含广泛的Philips Hue客户端的Go语言库。   [![godoc][GoDoc]](https://godoc.org/github.com/amimof/huego)
* [iot](https://github.com/vaelen/iot/)  IoT是一个实现谷歌物联网核心设备的简单框架。
* [eywa](https://github.com/xcodersun/eywa) **star:40** Eywa是一个用于跟踪连接的设备连接管理器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/xcodersun/eywa)

## 作业调度器

*用于作业调度的库。 (翻译出错了? 试试 [英文版](README_EN.md#job-scheduler) 吧~)*

* [gron](https://github.com/roylee0704/gron) **star:653** 使用简单的Go API定义基于时间的任务。 之后Gron的调度程序将运行它们。   [![godoc][GoDoc]](https://godoc.org/github.com/roylee0704/gron)
* [JobRunner](https://github.com/bamzi/jobrunner) **star:610** 智能和功能丰富的cron作业调度程序（包含任务队列和实时监控）。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/bamzi/jobrunner)
* [jobs](https://github.com/albrow/jobs) **star:456** 持久和灵活的后台作业库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/albrow/jobs)
* [scheduler](https://github.com/carlescere/scheduler) **star:301** Cronjobs让调度变得很简单。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/carlescere/scheduler)
* [clockwerk](http://github.com/onatm/clockwerk)  使用简单、流畅的语法调度作业的Go语言库。
* [go-cron](https://github.com/rk/go-cron) **star:177** 一个Go实现的简单的定时任务库。可以在不同的时间间隔（每秒一次到在每年在特定的日期执行）执行闭包或函数。主要用于web应用和长时间运行的守护进程。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/rk/go-cron)
* [clockwork](https://github.com/whiteShtef/clockwork) **star:88** Go实现的简单直观的作业调度库。   [![godoc][GoDoc]](https://godoc.org/github.com/whiteShtef/clockwork)
* [leprechaun](https://github.com/kilgaloon/leprechaun) **star:45** 支持webhook、crons和经典调度的作业调度程序。   [![godoc][GoDoc]](https://godoc.org/github.com/kilgaloon/leprechaun)

## JSON

*用于JSON处理的库。 (翻译出错了? 试试 [英文版](README_EN.md#json) 吧~)*

* [GJSON](https://github.com/tidwall/gjson) **star:5207** 使用一行代码获取JSON的值。   [![star > 2000][Awesome]](https://github.com/tidwall/gjson)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/gjson)
* [gojson](https://github.com/ChimeraCoder/gojson) **star:2075** 从JSON自动生成Go的结构（struct）定义。   [![star > 2000][Awesome]](https://github.com/ChimeraCoder/gojson)   [![godoc][GoDoc]](https://godoc.org/github.com/ChimeraCoder/gojson)
* [gojq](https://github.com/elgs/gojq) **star:140** Go语言实现的JSON请求。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/elgs/gojq)
* [kazaam](https://github.com/Qntfy/kazaam) **star:136** 用于任意JSON文档转换的API。   [![godoc][GoDoc]](https://godoc.org/github.com/Qntfy/kazaam)
* [jsongo](https://github.com/ricardolonga/jsongo) **star:93** 使用Fluent API来更容易地创建Json对象。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ricardolonga/jsongo)
* [gjo](https://github.com/skanehira/gjo) **star:63** 用于创建JSON对象的小工具。   [![godoc][GoDoc]](https://godoc.org/github.com/skanehira/gjo)
* [jsonf](https://github.com/miolini/jsonf) **star:56** 用于高亮展示和查询JSON的控制台工具。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/miolini/jsonf)
* [JayDiff](https://github.com/yazgazan/jaydiff) **star:55** 用Go编写的JSON比对工具。   [![godoc][GoDoc]](https://godoc.org/github.com/yazgazan/jaydiff)
* [jettison](https://github.com/wI2L/jettison) **star:36** 高性能，无反射的JSON编码器去。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/wI2L/jettison)
* [JSON-to-Go](https://mholt.github.io/json-to-go/)  将JSON转换为Go的结构（struct）。
* [mp](https://github.com/sanbornm/mp) **star:33** 简单的cli电子邮件解析器。它目前接受stdin并输出JSON。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sanbornm/mp)
* [go-respond](https://github.com/nicklaw5/go-respond) **star:26** 用于处理常见的HTTP JSON响应的Go语言库。   [![godoc][GoDoc]](https://godoc.org/github.com/nicklaw5/go-respond)
* [json2go](https://github.com/m-zajac/json2go) **star:24** 高级JSON去结构转换。提供一个包，该包可以解析多个JSON文档并创建结构体以适应所有这些文档。   [![godoc][GoDoc]](https://godoc.org/github.com/m-zajac/json2go)
* [ajson](https://github.com/spyzhov/ajson) **star:16** 为Go语言开发的包含JSONPath支持的抽象JSON。   [![godoc][GoDoc]](https://godoc.org/github.com/spyzhov/ajson)
* [jsonhal](https://github.com/RichardKnop/jsonhal) **star:9** 让自定义结构（struct）转化为JSON兼容的HAL（Hypertext Application Language）返回数据的简单Go包。   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/jsonhal)
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) **star:8** Go-JsonError允许我们轻松创建符合JsonApi规范的json响应错误。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/ddymko/go-jsonerror)
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) **star:6** 基于JSON API错误引用的Go bindings。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/AmuzaTkts/jsonapi-errors)

## 日志记录

*用于生成和处理日志文件的库。 (翻译出错了? 试试 [英文版](README_EN.md#logging) 吧~)*

* [logrus](https://github.com/Sirupsen/logrus) **star:12615** Go的结构化日志操作 。   [![star > 2000][Awesome]](https://github.com/Sirupsen/logrus)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/Sirupsen/logrus)
* [zap](https://github.com/uber-go/zap) **star:7881** 快速、结构化、多等级的日志记录。   [![star > 2000][Awesome]](https://github.com/uber-go/zap)   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/zap)
* [spew](https://github.com/davecgh/go-spew) **star:3421** 为Go数据结构实现一个漂亮的printer用于帮助调试。   [![star > 2000][Awesome]](https://github.com/davecgh/go-spew)   [![godoc][GoDoc]](https://godoc.org/github.com/davecgh/go-spew)
* [zerolog](https://github.com/rs/zerolog) **star:2440** Zero-allocation JSON日志记录。   [![star > 2000][Awesome]](https://github.com/rs/zerolog)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/rs/zerolog)
* [glog](https://github.com/golang/glog) **star:2382** 为Go提供了多等级日志记录。   [![star > 2000][Awesome]](https://github.com/golang/glog)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/glog)
* [tail](https://github.com/hpcloud/tail) **star:1597** 努力模拟实现BSD的tail的特性的Go包。   [![godoc][GoDoc]](https://godoc.org/github.com/hpcloud/tail)
* [lumberjack](https://github.com/natefinch/lumberjack) **star:1529** 简单的滚动日志，io.WriteCloser的实现。   [![godoc][GoDoc]](https://godoc.org/github.com/natefinch/lumberjack)
* [seelog](https://github.com/cihub/seelog) **star:1380** 具有灵活调度、过滤和格式化的日志功能。   [![godoc][GoDoc]](https://godoc.org/github.com/cihub/seelog)
* [log15](https://github.com/inconshreveable/log15) **star:932** 简单、强大的日志操作。   [![godoc][GoDoc]](https://godoc.org/github.com/inconshreveable/log15)
* [log](https://github.com/apex/log) **star:748** Go的结构化日志包。   [![godoc][GoDoc]](https://godoc.org/github.com/apex/log)
* [onelog](https://github.com/francoispqt/onelog) **star:339** Onelog是一个非常简单但非常高效的JSON日志程序。它是所有场景中速度最快的JSON日志程序。而且，它是配置要求最低的日志记录器之一。   [![godoc][GoDoc]](https://godoc.org/github.com/francoispqt/onelog)
* [logxi](https://github.com/mgutz/logxi) **star:338** 12-factor app的日志程序，快速且让人高兴地使用。   [![godoc][GoDoc]](https://godoc.org/github.com/mgutz/logxi)
* [log](https://github.com/go-playground/log) **star:269** Go的简单、可配置和可伸缩的结构化日志。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/log)
* [logutils](https://github.com/hashicorp/logutils) **star:258** Go的用于更好地进行日志操作的实用程序，继承了标准日志库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/logutils)
* [go-logger](https://github.com/apsdehal/go-logger) **star:239** 简单的日志程序的 Go 程序，与级别处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/apsdehal/go-logger)
* [logger](https://github.com/azer/logger) **star:134** Go的精简日志库。   [![godoc][GoDoc]](https://godoc.org/github.com/azer/logger)
* [xlog](https://github.com/rs/xlog) **star:128** 针对'net/context`实现的结构化的记录器，用于HTTP处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/rs/xlog)
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) **star:108** RollingWriter是一个自动循环的io.Writer的实现,带有多种策略以提供日志文件循环(rotation)。   [![godoc][GoDoc]](https://godoc.org/github.com/arthurkiller/rollingWriter)
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) **star:108** 支持日志多等级、分类和过滤的高性能日志记录。可以发送过滤后的日志消息到各种目标(如控制台，网络，邮件)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-ozzo/ozzo-log)   ![包含中文文档][CN]
* [log-voyage](https://github.com/firstrow/logvoyage) **star:83** 用Go编写的功能齐全的日志写入saas。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/firstrow/logvoyage)
* [glg](https://github.com/kpango/glg) **star:54** glg是一个简单而快速的Go日志库。   [![godoc][GoDoc]](https://godoc.org/github.com/kpango/glg)
* [stdlog](https://github.com/alexcesaro/log) **star:42** Stdlog是一个面向对象的库，提供了多等级日志记录。它对cron任务非常有用。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/alexcesaro/log)
* [gologger](https://github.com/sadlil/gologger) **star:39** 为Go提供方便简单的日志操作; 在彩色控制台，简单控制台，文件或Elasticsearch上。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sadlil/gologger)   ![归档项目][Archived]
* [go-log](https://github.com/ian-kent/go-log) **star:34** Log4j的Go语言。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/go-log)
* [logex](https://github.com/chzyer/logex) **star:32** 由标准日志库封装的Go日志库，支持跟踪和多等级。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/chzyer/logex)
* [logrusly](https://github.com/sebest/logrusly) **star:25** [logrus](https://github.com/sirupsen/logrus)的插件，将错误信息发送到[Loggly](https://www.loggly.com/)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sebest/logrusly)
* [go-log](https://github.com/siddontang/go-log) **star:23** 支持多等级和多处理程序的日志库。   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-log)
* [log](https://github.com/teris-io/log) **star:23** Go的结构化日志接口，清晰地将日志facade与其实现(implementation)分离开来。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/log)
* [journald](https://github.com/ssgreg/journald) **star:20**  Go实现systemd Journal的原生API用于日志记录。   [![godoc][GoDoc]](https://godoc.org/github.com/ssgreg/journald)
* [go-cronowriter](https://github.com/utahta/go-cronowriter) **star:20** 基于当前日期和时间的自动日志文件写入工具，类似cronolog。   [![godoc][GoDoc]](https://godoc.org/github.com/utahta/go-cronowriter)
* [distillog](https://github.com/amoghe/distillog) **star:20** distilled日志记录(可以将其视为stdlib +日志)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/amoghe/distillog)
* [mlog](https://github.com/jbrodriguez/mlog) **star:19** 简单的go日志模块，有5个级别，可选循环(rotation)日志文件记录功能和stdout/stderr输出。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/jbrodriguez/mlog)
* [gomol](https://github.com/aphistic/gomol) **star:15** 为Go实现可多方式输出、结构化日志, 并可扩展日志输出方式。   [![godoc][GoDoc]](https://godoc.org/github.com/aphistic/gomol)
* [gone/log](https://github.com/One-com/gone/tree/master/log)  快速、可扩展、功能齐全、std-lib源兼容的日志库。
* [go-log](https://github.com/subchen/go-log) **star:9** Go实现的简单且可配置的日志工具，并带有多等级、日志格式化和日志写入工具。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/subchen/go-log)
* [logdump](https://github.com/ewwwwwqm/logdump) **star:9** 用于多等级级日志记录的包。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ewwwwwqm/logdump)
* [glo](https://github.com/lajosbencz/glo) **star:8** 参照PHP的Monolog实现的具有相同日志等级的Go日志库。   [![godoc][GoDoc]](https://godoc.org/github.com/lajosbencz/glo)
* [logmatic](https://github.com/borderstech/logmatic) **star:6** Go的彩色日志记录器，带有可配置的日志级别。   [![godoc][GoDoc]](https://godoc.org/github.com/borderstech/logmatic)
* [xlog](https://github.com/xfxdev/xlog) **star:6** 插件架构和灵活的日志系统，带有多级别、多日志目标和自定义日志格式。   [![godoc][GoDoc]](https://godoc.org/github.com/xfxdev/xlog)
* [logo](https://github.com/mbndr/logo) **star:5** Go的日志工具，可配置的日志写入器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mbndr/logo)
* [log](https://github.com/aerogo/log) **star:5** 一个O(1)日志系统，允许您将一个日志连接到多个日志写入(例如stdout、文件和TCP连接)。   [![godoc][GoDoc]](https://godoc.org/github.com/aerogo/log)
* [logrusiowriter](https://github.com/cabify/logrusiowriter) **star:3** io。作者的实现使用[logrus](https://github.com/sirupsen/logrus) logger。   [![godoc][GoDoc]](https://godoc.org/github.com/cabify/logrusiowriter)

## 机器学习

*机器学习库。 (翻译出错了? 试试 [英文版](README_EN.md#machine-learning) 吧~)*

* [GoLearn](https://github.com/sjwhitworth/golearn) **star:6741** 通用机器学习库。   [![star > 2000][Awesome]](https://github.com/sjwhitworth/golearn)   [![godoc][GoDoc]](https://godoc.org/github.com/sjwhitworth/golearn)   ![包含中文文档][CN]
* [gorgonia](https://github.com/gorgonia/gorgonia) **star:2821** 基于图形（graph-based）的计算库，如Theano：它为构建各种机器学习和神经网络算法提供了基本框架。   [![star > 2000][Awesome]](https://github.com/gorgonia/gorgonia)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gorgonia/gorgonia)
* [tfgo](https://github.com/galeone/tfgo) **star:1225** 易于使用的Tensorflow bindings:简化了官方Tensorflow Go bindings的使用。在Go中定义计算图形，在Python中加载和执行训练的模型。   [![godoc][GoDoc]](https://godoc.org/github.com/galeone/tfgo)
* [goml](https://github.com/cdipaolo/goml) **star:1031** 在线机器学习。   [![godoc][GoDoc]](https://godoc.org/github.com/cdipaolo/goml)
* [gosseract](https://github.com/otiai10/gosseract) **star:931** 使用c++的Tesseract库实现的OCR。   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/gosseract)
* [CloudForest](https://github.com/ryanbressler/CloudForest) **star:651** 快速、灵活、多线程集成的决策树，用于机器学习。   [![godoc][GoDoc]](https://godoc.org/github.com/ryanbressler/CloudForest)
* [bayesian](https://github.com/jbrukh/bayesian) **star:637** Go的朴素贝叶斯分类。   [![godoc][GoDoc]](https://godoc.org/github.com/jbrukh/bayesian)
* [eaopt](https://github.com/MaxHalford/eaopt) **star:635** 一个进化优化（evolutionary optimization）库。   [![godoc][GoDoc]](https://godoc.org/github.com/MaxHalford/eaopt)
* [gorse](https://github.com/zhenghaoz/gorse) **star:560** 基于协同过滤（Collaborative Filtering ）的高性能推荐系统包。   [![godoc][GoDoc]](https://godoc.org/github.com/zhenghaoz/gorse)   ![包含中文文档][CN]
* [gobrain](https://github.com/goml/gobrain) **star:396** 用 Go 编写的神经网络库。   [![godoc][GoDoc]](https://godoc.org/github.com/goml/gobrain)
* [regommend](https://github.com/muesli/regommend) **star:253** 推荐和协同过滤引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/regommend)
* [ocrserver](https://github.com/otiai10/ocrserver) **star:240** 一个简单的OCR API服务器，非常容易地使用Docker和Heroku部署。   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/ocrserver)
* [go-deep](https://github.com/patrikeh/go-deep) **star:228** 一个功能丰富的神经网络库 。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/patrikeh/go-deep)
* [onnx-go](https://github.com/owulveryck/onnx-go) **star:199** Go Interface， 用于开放式神经网络交换(Open Neural Network Exchange)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/owulveryck/onnx-go)
* [go-galib](https://github.com/thoj/go-galib) **star:173** 用Go编写的遗传算法库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/thoj/go-galib)
* [goRecommend](https://github.com/timkaye11/goRecommend) **star:147** 用Go编写的推荐算法库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/timkaye11/goRecommend)
* [shield](https://github.com/eaigner/shield) **star:124** 贝叶斯文本分类器，具有灵活的tokenizers和存储后端。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/eaigner/shield)
* [go-fann](https://github.com/white-pony/go-fann) **star:101** 快速人工神经网络(FANN)库的Go bindings。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/white-pony/go-fann)
* [Goptuna](https://github.com/c-bata/goptuna) **star:91** Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/goptuna)
* [goga](https://github.com/tomcraven/goga) **star:77** Go的遗传算法库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tomcraven/goga)
* [libsvm](https://github.com/datastream/libsvm) **star:63** 基于LIBSVM 3.14实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/datastream/libsvm)
* [neural-go](https://github.com/schuyler/neural-go) **star:62** 多层感知器网络在Go中的实现，使用反向传播算法进行训练。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/schuyler/neural-go)
* [go-pr](https://github.com/daviddengcn/go-pr) **star:57** Go编写的模式识别包。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/daviddengcn/go-pr)
* [neat](https://github.com/jinyeom/neat) **star:55** 即插即用的并行Go框架，用于增强拓扑的神经进化(NeuroEvolution of Augmenting Topologies)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/jinyeom/neat)   ![归档项目][Archived]
* [golinear](https://github.com/danieldk/golinear) **star:39**  Go实现的liblinear bindings。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/danieldk/golinear)
* [goscore](https://github.com/asafschers/goscore) **star:38**  为预言模型标记语言（PMML）实现的评分API。   [![godoc][GoDoc]](https://godoc.org/github.com/asafschers/goscore)
* [fonet](https://github.com/Fontinalis/fonet) **star:33** 一个用Go编写的深度神经网络库。   [![godoc][GoDoc]](https://godoc.org/github.com/Fontinalis/fonet)
* [godist](https://github.com/e-dard/godist) **star:24** 各种概率分布，以及相关的method。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/e-dard/godist)
* [Varis](https://github.com/Xamber/Varis) **star:23** Go实现的神经网络。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/Xamber/Varis)
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) **star:22** Go实现的k-modes和k-prototypes聚类算法。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/e-XpertSolutions/go-cluster)
* [probab](https://github.com/ThePaw/probab) **star:10** 概率分布函数。贝叶斯推理。使用Go写的。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ThePaw/probab)
* [evoli](https://github.com/khezen/evoli) **star:8** 遗传算法（Genetic Algorithm）和粒子群优化（Particle Swarm Optimization）库。   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/evoli)
* [GoMind](https://github.com/surenderthakran/gomind) **star:6** 一个简单的神经网络库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/surenderthakran/gomind)

## 消息

*实现消息传递系统的库。 (翻译出错了? 试试 [英文版](README_EN.md#messaging) 吧~)*

* [sarama](https://github.com/Shopify/sarama) **star:4880**  Apache Kafka的Go库。   [![star > 2000][Awesome]](https://github.com/Shopify/sarama)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/Shopify/sarama)
* [gorush](https://github.com/appleboy/gorush) **star:3828** 使用[APNs2](https://github.com/sideshow/apns2)和谷歌[GCM](https://github.com/google/go-gcm)推送通知服务器。   [![star > 2000][Awesome]](https://github.com/appleboy/gorush)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/appleboy/gorush)
* [Centrifugo](https://github.com/centrifugal/centrifugo) **star:3803** 实时消息(Websockets或SockJS)服务器。   [![star > 2000][Awesome]](https://github.com/centrifugal/centrifugo)   [![godoc][GoDoc]](https://godoc.org/github.com/centrifugal/centrifugo)
* [machinery](https://github.com/RichardKnop/machinery) **star:3557** 基于分布式消息传递的异步任务/作业队列。   [![star > 2000][Awesome]](https://github.com/RichardKnop/machinery)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/machinery)
* [go-socket.io](https://github.com/googollee/go-socket.io) **star:3014** go的socket.io库，一个实时应用程序框架。   [![star > 2000][Awesome]](https://github.com/googollee/go-socket.io)
* [NATS Go Client](https://github.com/nats-io/nats) **star:2476** 轻量级和高性能的发布-订阅(publish-subscribe)和分布式队列消息传递系统——这是一个Go库。   [![star > 2000][Awesome]](https://github.com/nats-io/nats)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/nats-io/nats)
* [APNs2](https://github.com/sideshow/apns2) **star:2093** HTTP / 2苹果消息推送provider——发送推送消息到iOS, tvOS, Safari和OSX应用。   [![star > 2000][Awesome]](https://github.com/sideshow/apns2)   [![godoc][GoDoc]](https://godoc.org/github.com/sideshow/apns2)
* [Benthos](https://github.com/Jeffail/benthos) **star:2072** 一系列协议之间的消息流桥接。   [![star > 2000][Awesome]](https://github.com/Jeffail/benthos)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/Jeffail/benthos)
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) **star:1847** gopush-cluster是一个gopush服务器集群。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/Terry-Mao/gopush-cluster)   ![包含中文文档][CN]
* [Mercure](https://github.com/dunglas/mercure) **star:1619** 使用Mercure协议分派服务器发送(server-sent)更新的服务器和库(构建在服务器发送事件之上)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/dunglas/mercure)
* [melody](https://github.com/olahol/melody) **star:1619** 处理websocket session的极简框架，包括广播和自动ping/pong处理。   [![godoc][GoDoc]](https://godoc.org/github.com/olahol/melody)
* [mangos](https://github.com/go-mangos/mangos) **star:1544** Nanomsg(“可伸缩协议”)的纯go实现,具有传输互操作性。   [![godoc][GoDoc]](https://godoc.org/github.com/go-mangos/mangos)
* [go-nsq](https://github.com/nsqio/go-nsq) **star:1497** NSQ的官方Go包。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/nsqio/go-nsq)
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) **star:1106** Redis支持的统一推送服务, 用于服务端向移动设备的消息通知。   [![godoc][GoDoc]](https://godoc.org/github.com/uniqush/uniqush-push)
* [zmq4](https://github.com/pebbe/zmq4) **star:795** ZeroMQ的Go interface第4版。也可用于[第3版](https://github.com/pebbe/zmq3)和[第2版](https://github.com/pebbe/zmq2)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/pebbe/zmq4)
* [Gollum](https://github.com/trivago/gollum) **star:780** 一个n:m多路复用器(n:m multiplexer)，收集不同来源的消息并将其广播到一组目的地。   [![godoc][GoDoc]](https://godoc.org/github.com/trivago/gollum)
* [Beaver](https://github.com/Clivern/Beaver) **star:747** 一个实时消息服务器，可用于在web和手机app端构建一个可伸缩的应用内通知，多人游戏，聊天应用。   [![godoc][GoDoc]](https://godoc.org/github.com/Clivern/Beaver)
* [EventBus](https://github.com/asaskevich/EventBus) **star:586** 具有异步兼容性的轻量级事件总线。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/asaskevich/EventBus)
* [golongpoll](https://github.com/jcuga/golongpoll) **star:434** HTTP longpoll服务器库，使web发布-订阅变得简单。   [![godoc][GoDoc]](https://godoc.org/github.com/jcuga/golongpoll)
* [dbus](https://github.com/godbus/dbus) **star:372** D-Bus的Go bindings。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/godbus/dbus)
* [Glue](https://github.com/desertbit/glue) **star:321** 健壮的Go和Javascript Socket库(替代Socket.io)。   [![godoc][GoDoc]](https://godoc.org/github.com/desertbit/glue)
* [emitter](https://github.com/olebedev/emitter) **star:319** 使用Go的方式发出事件, 带有通配符、谓词、取消可能性和许多其他优点。   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/emitter)
* [pubsub](https://github.com/tuxychandru/pubsub) **star:291** 简单的pubsub的go包。   [![godoc][GoDoc]](https://godoc.org/github.com/tuxychandru/pubsub)
* [guble](https://github.com/smancke/guble) **star:140** 使用推送通知服务(谷歌Firebase云消息、苹果推送通知服务、SMS)的消息服务器, 支持websockets,REST API，并具有分布式操作和消息持久性。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/smancke/guble)
* [Bus](https://github.com/mustafaturan/bus) **star:120** 内部通信的最小消息总线实现。   [![godoc][GoDoc]](https://godoc.org/github.com/mustafaturan/bus)
* [oplog](https://github.com/dailymotion/oplog) **star:96** 用于REST api的通用oplog/replication系统。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dailymotion/oplog)
* [rabtap](https://github.com/jandelgado/rabtap) **star:83** RabbitMQ的瑞士军刀cli应用。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jandelgado/rabtap)
* [messagebus](https://github.com/vardius/message-bus) **star:69** messagebus是一个Go的简单异步消息总线，非常适合在执行事件sourcing、CQRS和DDD时用作事件总线。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/message-bus)
* [rabbus](https://github.com/rafaeljesus/rabbus) **star:65** amqp exchanges和队列上的一个小工具。   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/rabbus)
* [drone-line](https://github.com/appleboy/drone-line) **star:62** 使用二进制、docker或Drone CI发送[Line](https://at.line.me/en)通知。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/appleboy/drone-line)
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) **star:56** RapidMQ是用于管理本地消息队列的轻量且可靠的库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sybrexsys/RapidMQ)
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) **star:54** 一个围绕NSQ topic和channel的小工具。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/nsq-event-bus)
* [go-notify](https://github.com/TheCreeper/go-notify) **star:47** 原生的freedesktop通知规范实现。   [![godoc][GoDoc]](https://godoc.org/github.com/TheCreeper/go-notify)
* [goose](https://github.com/ian-kent/goose) **star:36** 服务器在Go中发送事件。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/goose)
* [Commander](https://github.com/jeroenrinzema/commander) **star:29** 高级事件驱动的消费者/生产者(consumer/producer)，支持各种“方言”，如Apache Kafka。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jeroenrinzema/commander)
* [event](https://github.com/agoalofalife/event) **star:28** 观察者模式的实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/agoalofalife/event)
* [hub](https://github.com/leandro-lugaresi/hub) **star:25** 适用于Go应用程序的消息/事件中心，使用publish/subscribe模式，并支持别名(类似rabbitMQ exchanges)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/leandro-lugaresi/hub)
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) **star:12** 用于Viessmann Vitotrol web服务的客户端库。   [![godoc][GoDoc]](https://godoc.org/github.com/maxatome/go-vitotrol)
* [gaurun-client](https://github.com/osamingo/gaurun-client) **star:8** 用Go编写的Gaurun客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/gaurun-client)
* [jazz](https://github.com/socifi/jazz) **star:6** 一个简单的RabbitMQ抽象层，用于队列管理和消息的发布和消费。   [![godoc][GoDoc]](https://godoc.org/github.com/socifi/jazz)
* [redisqueue](https://github.com/robinjoseph08/redisqueue) **star:4** 基于Redis streams的队列的生产者和消费者。   [![godoc][GoDoc]](https://godoc.org/github.com/robinjoseph08/redisqueue)
* [rmqconn](https://github.com/sbabiv/rmqconn)  RabbitMQ重新连接。amqp.Connection和amqp.Dial之上的Wrapper。允许在强制调用Close()方法关闭连接之前重新连接。

## 微软办公软件

* [unioffice](https://github.com/unidoc/unioffice) **star:1833** 用于创建和处理Office Word (.docx)、Excel (.xlsx)和Powerpoint (.pptx)文档的纯go库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/unidoc/unioffice)

### Microsoft Excel

*用于操作Microsoft Excel的库。 (翻译出错了? 试试 [英文版](README_EN.md#microsoft-excel) 吧~)*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) **star:4731** 用于读写Microsoft Excel™(XLSX)文件的Go语言库。   [![star > 2000][Awesome]](https://github.com/360EntSecGroup-Skylar/excelize)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/360EntSecGroup-Skylar/excelize)
* [xlsx](https://github.com/tealeg/xlsx) **star:3536** 用以简化在Go程序中读取使用最新版本Microsoft Excel的XML格式文件的库。   [![star > 2000][Awesome]](https://github.com/tealeg/xlsx)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/tealeg/xlsx)
* [xlsx](https://github.com/plandem/xlsx) **star:86** 在Go程序以快速和安全的方式读取/更新现有的Microsoft Excel文件。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/plandem/xlsx)
* [go-excel](https://github.com/szyhf/go-excel) **star:52** 一个简单轻便的阅读器，可以将类关系型数据库(relate-db-like)的excel作为表来读取。   [![godoc][GoDoc]](https://godoc.org/github.com/szyhf/go-excel)
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) **star:14** libxlsxwriter的Go binding, 用于编写XLSX (Microsoft Excel)文件。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/fterrag/goxlsxwriter)

## 杂项

### 依赖注入

*用于处理依赖项注入的库。 (翻译出错了? 试试 [英文版](README_EN.md#dependency-injection) 吧~)*

* [dig](https://github.com/uber-go/dig) **star:975** 一个基于反射的Go依赖注入工具包。   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/dig)
* [fx](https://github.com/uber-go/fx) **star:883** 基于依赖注入的Go应用程序框架(构建在dig之上)。   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/fx)
* [inject](https://github.com/defval/inject) **star:38** 一个基于反射的依赖注入容器，具有简单的接口。   [![godoc][GoDoc]](https://godoc.org/github.com/defval/inject)
* [alice](https://github.com/magic003/alice) **star:35** Go的外挂的依赖注入容器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/magic003/alice)
* [container](https://github.com/golobby/container) **star:35** 一个强大的IoC容器，具有流畅且易于使用的接口。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/golobby/container)
* [wire](https://github.com/Fs02/wire) **star:19** 适用于Go的严格运行时依赖注入(Strict Runtime Dependency Injection)。   [![godoc][GoDoc]](https://godoc.org/github.com/Fs02/wire)
* [gocontainer](https://github.com/vardius/gocontainer) **star:10** 简单的依赖注入容器。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/gocontainer)
* [linker](https://github.com/logrange/linker) **star:10** A reflection based dependency injection and inversion of control library with components lifecycle support.   [![godoc][GoDoc]](https://godoc.org/github.com/logrange/linker)

### 项目布局

*用于组织项目的非正式模式集。 (翻译出错了? 试试 [英文版](README_EN.md#project-layout) 吧~)*

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) **star:10493** Go生态系统中历史和新兴的项目布局模式集合。   [![star > 2000][Awesome]](https://github.com/golang-standards/project-layout)
* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) **star:368** 应用程序样板和应用现代实践的例子。   [![godoc][GoDoc]](https://godoc.org/github.com/sagikazarmark/modern-go-application)
* [scaffold](https://github.com/catchplay/scaffold) **star:33** 快速生成Go项目布局的脚手架。让您专注于已实现的业务逻辑。   [![godoc][GoDoc]](https://godoc.org/github.com/catchplay/scaffold)
* [go-sample](https://github.com/zitryss/go-sample) **star:32** 带有实际代码的Go应用程序项目的示例布局。   [![godoc][GoDoc]](https://godoc.org/github.com/zitryss/go-sample)

### 字符串

*处理字符串的库。 (翻译出错了? 试试 [英文版](README_EN.md#strings) 吧~)*

* [xstrings](https://github.com/huandu/xstrings) **star:629** 从其他语言移植的有用字符串函数合集。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/huandu/xstrings)
* [strutil](https://github.com/ozgio/strutil) **star:69** 字符串处理工具。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ozgio/strutil)

*这些库之所以放在这里，是因为不适合放在其他分类。 (翻译出错了? 试试 [英文版](README_EN.md#strings) 吧~)*

* [gopsutil](https://github.com/shirou/gopsutil) **star:4134** 用于检索进程和系统利用率(CPU、内存、磁盘等)的跨平台的库。   [![star > 2000][Awesome]](https://github.com/shirou/gopsutil)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/shirou/gopsutil)
* [archiver](https://github.com/mholt/archiver) **star:2550** 用于生成和解压.zip和.tar.gz文档的库和命令。   [![star > 2000][Awesome]](https://github.com/mholt/archiver)   [![godoc][GoDoc]](https://godoc.org/github.com/mholt/archiver)
* [gosms](https://github.com/haxpax/gosms) **star:1236** Go编写的私人的本地短信网关，可以用来发送短信。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/haxpax/gosms)
* [go-resiliency](https://github.com/eapache/go-resiliency) **star:893**  Go语言弹性模式(resiliency pattern)。   [![godoc][GoDoc]](https://godoc.org/github.com/eapache/go-resiliency)
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) **star:709** Go语言的通用对象池。   [![godoc][GoDoc]](https://godoc.org/github.com/jolestar/go-commons-pool)   ![包含中文文档][CN]
* [go-openapi](https://github.com/go-openapi)  用于解析和使用开放api模式(open-api schemas)的包的集合。
* [base64Captcha](https://github.com/mojocn/base64Captcha) **star:658** base64Captcha支持数字，字母，算术，音频和混合模式的验证码。   [![godoc][GoDoc]](https://godoc.org/github.com/mojocn/base64Captcha)   ![包含中文文档][CN]
* [shortid](https://github.com/teris-io/shortid) **star:469** 分布式地生成超短、唯一、非顺序、URL友好的id。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/shortid)
* [gofakeit](https://github.com/brianvoe/gofakeit) **star:467** 用go编写的随机数据生成器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/brianvoe/gofakeit)
* [llvm](https://github.com/llir/llvm) **star:441** 用于在纯Go中与LLVM IR交互的库。   [![godoc][GoDoc]](https://godoc.org/github.com/llir/llvm)
* [health](https://github.com/dimiro1/health) **star:365** 易于使用，可扩展的健康检查库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/dimiro1/health)
* [conv](https://github.com/cstockton/go-conv) **star:342** conv包提供了跨Go类型(Go types)的快速和直观的转换。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/cstockton/go-conv)
* [banner](https://github.com/dimiro1/banner) **star:235** 在Go应用程序中添加漂亮的横幅(banner)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/dimiro1/banner)
* [gountries](https://github.com/pariz/gountries) **star:218** 获取国家和细节数据的包。   [![godoc][GoDoc]](https://godoc.org/github.com/pariz/gountries)
* [antch](https://github.com/antchfx/antch) **star:155** 一个快速、强大和可扩展的web爬虫框架。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/antchfx/antch)   ![包含中文文档][CN]
* [battery](https://github.com/distatus/battery) **star:137** 跨平台、标准化的电池信息库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/distatus/battery)
* [ffmt](https://github.com/go-ffmt/ffmt) **star:128** 美化数据,使其更适合人查看。   [![godoc][GoDoc]](https://godoc.org/github.com/go-ffmt/ffmt)   ![包含中文文档][CN]
* [lk](https://github.com/hyperboloide/lk) **star:126** 一个简单的版权许可证库。   [![godoc][GoDoc]](https://godoc.org/github.com/hyperboloide/lk)
* [stats](https://github.com/go-playground/stats) **star:125** Monitors Go MemStats + 诸如如内存，Swap和CPU的系统状态统计，并通过UDP发送到任何你想记录的地方   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/stats)
* [stateless](https://github.com/qmuntal/stateless) **star:117** 用于创建状态机的流畅库。   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/stateless)
* [bitio](https://github.com/icza/bitio) **star:103** 高度优化的位级读写器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/icza/bitio)
* [healthcheck](https://github.com/etherlabsio/healthcheck) **star:90** 用于RESTful服务的强制的(opinionated)并发健康检查HTTP处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/etherlabsio/healthcheck)
* [gommit](https://github.com/antham/gommit) **star:78** 分析git提交消息，确保它们遵循已定义的格式。   [![godoc][GoDoc]](https://godoc.org/github.com/antham/gommit)
* [turtle](https://github.com/hackebrot/turtle) **star:78** Go的Emojis库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/hackebrot/turtle)
* [go-unarr](https://github.com/gen2brain/go-unarr) **star:72** 用于RAR、TAR、ZIP和7z文件的解压缩库。   [![godoc][GoDoc]](https://godoc.org/github.com/gen2brain/go-unarr)
* [indigo](https://github.com/osamingo/indigo) **star:56** 分布式唯一ID生成器, 使用Sonyflake并由Base58编码。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/indigo)
* [ghorg](https://github.com/gabrie30/ghorg) **star:55** 快速克隆整个org用户库到一个目录-支持GitHub, GitLab和Bitbucket。   [![godoc][GoDoc]](https://godoc.org/github.com/gabrie30/ghorg)
* [morse](https://github.com/alwindoss/morse) **star:51** 实现字符串与摩尔斯电码转换的库。   [![godoc][GoDoc]](https://godoc.org/github.com/alwindoss/morse)
* [captcha](https://github.com/steambap/captcha) **star:44** captcha包为验证码生成提供了一个易于使用的、unopinionated的API。   [![godoc][GoDoc]](https://godoc.org/github.com/steambap/captcha)
* [xkg](https://github.com/go-xkg/xkg) **star:43** X Keyboard Grabber(键盘事件捕获)   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-xkg/xkg)
* [pdfgen](https://github.com/hyperboloide/pdfgen) **star:34** 通过Json请求生成PDF的HTTP服务。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/hyperboloide/pdfgen)
* [persian](https://github.com/mavihq/persian) **star:33** 一些适用于波斯语的Go工具库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mavihq/persian)
* [browscap_go](https://github.com/digitalcrab/browscap_go) **star:30** 用于[Browser Capabilities Project](http://browscap.org/)的Go库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/digitalcrab/browscap_go)
* [datacounter](https://github.com/miolini/datacounter) **star:29** 用于readers/writer/http.ResponseWriter的计数器。   [![godoc][GoDoc]](https://godoc.org/github.com/miolini/datacounter)
* [autoflags](https://github.com/artyom/autoflags) **star:24** 从struct字段自动定义命令行flag的Go包。   [![godoc][GoDoc]](https://godoc.org/github.com/artyom/autoflags)
* [gotoprom](https://github.com/cabify/gotoprom) **star:22** 为Prometheus客户端提供类型安全的指标(metric)构建工具库。   [![godoc][GoDoc]](https://godoc.org/github.com/cabify/gotoprom)
* [xdg](https://github.com/rkoesters/xdg) **star:20** FreeDesktop.org (xdg)规范在Go中的实现。   [![godoc][GoDoc]](https://godoc.org/github.com/rkoesters/xdg)
* [url-shortener](https://github.com/pantrif/url-shortener) **star:18** 一个现代的、强大的、健壮的URL转短链接微服务，带有mysql支持。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/pantrif/url-shortener)
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler)  用于生成http输入和输出处理模板。
* [gosh](https://github.com/osamingo/gosh) **star:17** 提供Go统计处理程序，结构和测量方法。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/gosh)
* [sandid](https://github.com/aofei/sandid) **star:15** 能沟让地球上的每一粒沙子都有自己的ID。   [![godoc][GoDoc]](https://godoc.org/github.com/aofei/sandid)
* [anagent](https://github.com/mudler/anagent) **star:11** Go语言的最小化，可插入的evloop/timer处理程序, 带有依赖注入。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mudler/anagent)
* [avgRating](https://github.com/kirillDanshin/avgRating) **star:9** 根据威尔逊得分排序算法(Wilson Score Equation)计算平均分和评分。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/kirillDanshin/avgRating)
* [hostutils](https://github.com/Wing924/hostutils) **star:8** 一个用于打包和解包FQDNs列表的go语言库。   [![godoc][GoDoc]](https://godoc.org/github.com/Wing924/hostutils)
* [shellwords](https://github.com/Wing924/shellwords) **star:7** 一个Go库，实现了依照UNIX Bourne shell的关键词解析规则进行字符串操纵。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/Wing924/shellwords)
* [metrics](https://github.com/pascaldekloe/metrics) **star:4** 用于instrumentation和Prometheus exposition的库。   [![godoc][GoDoc]](https://godoc.org/github.com/pascaldekloe/metrics)
* [numa](https://github.com/lrita/numa) **star:2** NUMA是一个用go编写的实用程序库。它可以帮助我们编写一些NUMA-AWARED代码。   [![godoc][GoDoc]](https://godoc.org/github.com/lrita/numa)

## 自然语言处理

*用于处理人类语言的库。 (翻译出错了? 试试 [英文版](README_EN.md#natural-language-processing) 吧~)*

* [prose](https://github.com/jdkato/prose) **star:2334** 支持标记化、词性标记、命名实体提取等文本处理的库。只说英语。   [![star > 2000][Awesome]](https://github.com/jdkato/prose)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jdkato/prose)
* [gse](https://github.com/go-ego/gse) **star:1110** 高效的文本分割;支持英语、汉语、日语等。   [![godoc][GoDoc]](https://godoc.org/github.com/go-ego/gse)   ![包含中文文档][CN]
* [when](https://github.com/olebedev/when) **star:932** 带有可插入规则的自然EN和RU语言日期/时间解析器。   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/when)
* [gojieba](https://github.com/yanyiwu/gojieba) **star:855** 这是一个Go实现的[jieba](https://github.com/fxsjy/jieba)，这是一个中文分词算法。   [![godoc][GoDoc]](https://godoc.org/github.com/yanyiwu/gojieba)   ![包含中文文档][CN]
* [go-pinyin](https://github.com/mozillazg/go-pinyin) **star:555** 中文汉字到汉语拼音的转换。   [![godoc][GoDoc]](https://godoc.org/github.com/mozillazg/go-pinyin)
* [kagome](https://github.com/ikawaha/kagome) **star:442** JP形态学分析仪编写的纯Go。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/ikawaha/kagome)
* [whatlanggo](https://github.com/abadojack/whatlanggo) **star:361** Go的自然语言检测包。支持84种语言和24种脚本(书写系统，如拉丁语、西里尔语等)。   [![godoc][GoDoc]](https://godoc.org/github.com/abadojack/whatlanggo)
* [nlp](https://github.com/Shixzie/nlp) **star:355** 从字符串中提取值并用nlp填充结构。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/Shixzie/nlp)
* [sentences](https://github.com/neurosnap/sentences) **star:261** 句子标记器:将文本转换为句子列表。   [![godoc][GoDoc]](https://godoc.org/github.com/neurosnap/sentences)
* [nlp](https://github.com/james-bowman/nlp) **star:222** 支持LSA(潜在语义分析)的Go自然语言处理库。   [![godoc][GoDoc]](https://godoc.org/github.com/james-bowman/nlp)
* [go-nlp](https://github.com/nuance/go-nlp) **star:79** 用于处理离散概率分布的实用程序和用于进行NLP工作的其他工具。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/nuance/go-nlp)
* [go-i18n](https://github.com/nicksnyder/go-i18n/)  软件包和用于处理本地化文本的附带工具。
* [getlang](https://github.com/rylans/getlang) **star:77** 快速自然语言检测包。   [![godoc][GoDoc]](https://godoc.org/github.com/rylans/getlang)
* [gounidecode](https://github.com/fiam/gounidecode) **star:68** 用于Go的Unicode音译器(也称为unidecode)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/fiam/gounidecode)
* [go-unidecode](https://github.com/mozillazg/go-unidecode) **star:62** Unicode文本的ASCII音译。   [![godoc][GoDoc]](https://godoc.org/github.com/mozillazg/go-unidecode)
* [textcat](https://github.com/pebbe/textcat) **star:61** Go package支持基于n-gram的文本分类，支持utf-8和原始文本。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/pebbe/textcat)
* [MMSEGO](https://github.com/awsong/MMSEGO) **star:59** 这是一个 Go 实现的[MMSEG](http://technology.chtsai.org/mmseg/)，这是一个中文分词算法。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/awsong/MMSEGO)
* [go-stem](https://github.com/agonopol/go-stem) **star:52** 波特词干算法的实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/agonopol/go-stem)
* [stemmer](https://github.com/dchest/stemmer) **star:48** 用于Go编程语言的Stemmer包。包括英语和德语词根。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dchest/stemmer)
* [RAKE.go](https://github.com/Obaied/RAKE.go) **star:46** 快速自动关键字提取算法(RAKE)的Go端口。   [![godoc][GoDoc]](https://godoc.org/github.com/Obaied/RAKE.go)
* [segment](https://github.com/blevesearch/segment) **star:45** Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](http://www.unicode.org/reports/tr29/)   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/blevesearch/segment)
* [porter2](https://github.com/zhenjl/porter2) **star:34** 非常快的波特2史坦默。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zhenjl/porter2)
* [go2vec](https://github.com/danieldk/go2vec) **star:32** 用于word2vec嵌入式的阅读器和实用程序函数。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/danieldk/go2vec)
* [paicehusk](https://github.com/rookii/paicehusk) **star:25** Golang实现了Paice/外壳阻塞算法。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/rookii/paicehusk)
* [petrovich](https://github.com/striker2000/petrovich) **star:24** 彼得罗维奇是一个图书馆，它把俄语名字的词形变化成特定的语法格。   [![godoc][GoDoc]](https://godoc.org/github.com/striker2000/petrovich)
* [snowball](https://github.com/goodsign/snowball) **star:24** 滚雪球柄端口(cgo包装)为 Go 。提供词干提取功能[Snowball native](http://snowball.tartarus.org/)。   ![最近一年没有更新][Yellow]
* [go-mystem](https://github.com/dveselov/mystem) **star:23** CGo绑定到Yandex。Mystem -俄罗斯形态学分析仪。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/dveselov/mystem)
* [icu](https://github.com/goodsign/icu) **star:19** Cgo绑定用于icu4c C库的检测和转换功能。保证与版本50.1兼容。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/goodsign/icu)
* [golibstemmer](https://github.com/rjohnsondev/golibstemmer) **star:15**  Go 绑定斯诺鲍libstemmer库，包括波特2。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/rjohnsondev/golibstemmer)
* [shamoji](https://github.com/osamingo/shamoji) **star:10** shamoji是用Go编写的word过滤包。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/shamoji)
* [libtextcat](https://github.com/goodsign/libtextcat) **star:10** 用于libtextcat C库的Cgo绑定。保证与版本2.2兼容。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/goodsign/libtextcat)
* [porter](https://github.com/a2800276/porter) **star:8** 这是Martin Porter在C语言中实现的Porter词干分析算法的一个相当简单的移植。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/a2800276/porter)
* [gotokenizer](https://github.com/xujiajun/gotokenizer) **star:6** 一种基于字典和双字母格朗语言模型的记号赋予器。(现在只支持中文分割)   [![godoc][GoDoc]](https://godoc.org/github.com/xujiajun/gotokenizer)

## 网络

*用于处理各种网络层的库。 (翻译出错了? 试试 [英文版](README_EN.md#networking) 吧~)*

* [kcptun](https://github.com/xtaci/kcptun) **star:10972** 基于KCP协议的非常简单和快速udp隧道。   [![star > 2000][Awesome]](https://github.com/xtaci/kcptun)   [![godoc][GoDoc]](https://godoc.org/github.com/xtaci/kcptun)
* [fasthttp](https://github.com/valyala/fasthttp) **star:10162** 一个快速HTTP实现，比net/http快10倍。   [![star > 2000][Awesome]](https://github.com/valyala/fasthttp)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/valyala/fasthttp)
* [dns](https://github.com/miekg/dns) **star:3971** 用于 DNS 的库。   [![star > 2000][Awesome]](https://github.com/miekg/dns)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/miekg/dns)
* [HTTPLab](https://github.com/gchaincl/httplab) **star:3448** HTTPLabs 允许你检查 HTTP 请求和伪造响应。   [![star > 2000][Awesome]](https://github.com/gchaincl/httplab)   [![godoc][GoDoc]](https://godoc.org/github.com/gchaincl/httplab)
* [quic-go](https://github.com/lucas-clemente/quic-go) **star:3234** 在纯Go中实现了QUIC协议。   [![star > 2000][Awesome]](https://github.com/lucas-clemente/quic-go)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/lucas-clemente/quic-go)
* [gopacket](https://github.com/google/gopacket) **star:3011** Go library for packet processing with libpcap bindings.   [![star > 2000][Awesome]](https://github.com/google/gopacket)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/google/gopacket)
* [webrtc](https://github.com/pions/webrtc) **star:2526** WebRTC API的纯Go实现。   [![star > 2000][Awesome]](https://github.com/pions/webrtc)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/pions/webrtc)
* [kcp-go](https://github.com/xtaci/kcp-go) **star:2324** 快速可靠的ARQ协议。   [![star > 2000][Awesome]](https://github.com/xtaci/kcp-go)   [![godoc][GoDoc]](https://godoc.org/github.com/xtaci/kcp-go)
* [gobgp](https://github.com/osrg/gobgp) **star:1724** 基于 Go 的 BGP 实现。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/osrg/gobgp)
* [ssh](https://github.com/gliderlabs/ssh) **star:1153** 用于构建SSH服务器的高级API(封装密码/ SSH)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gliderlabs/ssh)
* [gnet](https://github.com/panjf2000/gnet) **star:1007** gnet是一个高性能、轻量级、非阻塞、事件循环的纯Go网络库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/panjf2000/gnet)   ![包含中文文档][CN]
* [fortio](https://github.com/fortio/fortio) **star:953** 负载测试库和命令行工具，高级的echo服务器和web UI。允许指定一组每秒查询的负载，并记录延迟直方图和其他有用的统计数据，并将它们作图。支持Tcp、Http、gRPC。   [![godoc][GoDoc]](https://godoc.org/github.com/fortio/fortio)
* [water](https://github.com/songgao/water) **star:878** 简单TUN / TAP图书馆。   [![godoc][GoDoc]](https://godoc.org/github.com/songgao/water)
* [sftp](https://github.com/pkg/sftp) **star:777** Package sftp implements the SSH File Transfer Protocol as described in https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt.   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/pkg/sftp)
* [go-getter](https://github.com/hashicorp/go-getter) **star:767**  通过URL来下载文件或目录。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/go-getter)
* [NFF-Go](https://github.com/intel-go/nff-go) **star:704** 用于快速开发云计算和裸机网络功能的框架(原YANFF)。   [![godoc][GoDoc]](https://godoc.org/github.com/intel-go/nff-go)
* [grab](https://github.com/cavaliercoder/grab) **star:570**  用于管理文件下载。   [![godoc][GoDoc]](https://godoc.org/github.com/cavaliercoder/grab)
* [mdns](https://github.com/hashicorp/mdns) **star:566** 简单mDNS(Multicast DNS)客户端/服务器库。   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/mdns)
* [mqttPaho](https://eclipse.org/paho/clients/golang/)  Paho Go客户端提供了一个 MQTT 客户端库，用于通过TCP、TLS或WebSockets连接到MQTT代理。
* [ftp](https://github.com/jlaffaye/ftp) **star:560** 实现了[RFC 959](http://tools.ietf.org/html/rfc959)中描述的ftp客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/jlaffaye/ftp)
* [lhttp](https://github.com/fanux/lhttp) **star:521** 强大的websocket框架，可以让你更容易的构建IM服务器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/fanux/lhttp)   ![包含中文文档][CN]
* [gosnmp](https://github.com/soniah/gosnmp) **star:451** 用于执行 SNMP 操作的原生 Go 库。   [![godoc][GoDoc]](https://godoc.org/github.com/soniah/gosnmp)
* [gotcp](https://github.com/gansidui/gotcp) **star:429** 用于快速编写 tcp 应用程序。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/gansidui/gotcp)
* [cidranger](https://github.com/yl2chen/cidranger) **star:398** 快速得 IP 到 CIDR 查找。   [![godoc][GoDoc]](https://godoc.org/github.com/yl2chen/cidranger)
* [peerdiscovery](https://github.com/schollz/peerdiscovery) **star:383** 基于UDP组播的跨平台本地对等点发现库。   [![godoc][GoDoc]](https://godoc.org/github.com/schollz/peerdiscovery)
* [gopcap](https://github.com/akrennmair/gopcap) **star:361**  用 Go 实现了对 libpcap 的封装。   [![godoc][GoDoc]](https://godoc.org/github.com/akrennmair/gopcap)
* [go-stun](https://github.com/ccding/go-stun) **star:336** 实现了 STUN 客户端(RFC 3489和RFC 5389)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ccding/go-stun)
* [raw](https://github.com/mdlayher/raw) **star:321** Package raw支持在设备驱动程序级别读取和写入网络接口的数据。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mdlayher/raw)
* [stun](https://github.com/go-rtc/stun) **star:303** Go实现的RFC 5389 STUN协议。   [![godoc][GoDoc]](https://godoc.org/github.com/go-rtc/stun)
* [tcp_server](https://github.com/firstrow/tcp_server) **star:294**  Go 图书馆建设tcp服务器更快。   [![godoc][GoDoc]](https://godoc.org/github.com/firstrow/tcp_server)
* [buffstreams](https://github.com/stabbycutyou/buffstreams) **star:233** 通过TCP传输协议缓冲区数据。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/stabbycutyou/buffstreams)
* [winrm](https://github.com/masterzen/winrm) **star:225**  Go WinRM客户端远程执行Windows机器上的命令。   [![godoc][GoDoc]](https://godoc.org/github.com/masterzen/winrm)
* [arp](https://github.com/mdlayher/arp) **star:201** 实现了arp协议，如RFC 826中所述。   [![godoc][GoDoc]](https://godoc.org/github.com/mdlayher/arp)
* [ethernet](https://github.com/mdlayher/ethernet) **star:189** 实现了对IEEE 802.3以太网II帧和IEEE 802.1Q VLAN标签的编组和解组。   [![godoc][GoDoc]](https://godoc.org/github.com/mdlayher/ethernet)
* [utp](https://github.com/anacrolix/utp) **star:149** Go uTP微传输协议的实现。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/anacrolix/utp)
* [canopus](https://github.com/zubairhamed/canopus) **star:135** CoAP客户端/服务器实现(RFC 7252)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/zubairhamed/canopus)
* [jazigo](https://github.com/udhos/jazigo) **star:132** Jazigo是一个用Go编写的工具，用于检索多个网络设备的配置。   [![godoc][GoDoc]](https://godoc.org/github.com/udhos/jazigo)
* [sslb](https://github.com/eduardonunesp/sslb) **star:115** 它是一个超级简单的负载平衡器，只是一个实现某种性能的小项目。   [![godoc][GoDoc]](https://godoc.org/github.com/eduardonunesp/sslb)
* [gNxI](https://github.com/google/gnxi) **star:109** 一组基于 gNMI 和 gNOI 协议的网络管理工具。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/google/gnxi)
* [gmqtt](https://github.com/DrmagicE/gmqtt) **star:107** Gmqtt是一个灵活、高性能的MQTT代理库，它完全实现了MQTT协议V3.1.1。   [![godoc][GoDoc]](https://godoc.org/github.com/DrmagicE/gmqtt)   ![包含中文文档][CN]
* [xtcp](https://github.com/xfxdev/xtcp) **star:88** TCP服务器框架具有同时全双工通信，优雅关机，自定义协议。   [![godoc][GoDoc]](https://godoc.org/github.com/xfxdev/xtcp)
* [dhcp6](https://github.com/mdlayher/dhcp6) **star:63** 实现了一个DHCPv6服务器，如RFC 3315所述。   [![godoc][GoDoc]](https://godoc.org/github.com/mdlayher/dhcp6)
* [ether](https://github.com/songgao/ether) **star:62** 一个用于发送和接收以太网帧的跨平台 Go 库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/songgao/ether)
* [linkio](https://github.com/ian-kent/linkio) **star:44** 网络链路速度模拟，主要用于接口的读/写。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/linkio)
* [portproxy](https://github.com/aybabtme/portproxy) **star:42** Simple TCP proxy which adds CORS support to API's which don't support it.   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/aybabtme/portproxy)
* [packet](https://github.com/aerogo/packet) **star:35** 通过TCP和UDP发送数据包。它可以缓冲消息和热交换连接。   [![godoc][GoDoc]](https://godoc.org/github.com/aerogo/packet)
* [iplib](https://github.com/c-robinson/iplib) **star:25** 用于处理IP地址的库(net)。借鉴于python 的 [ipaddress](https://docy-doc.org/3/library/ipaddress.html)和ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)   [![godoc][GoDoc]](https://godoc.org/github.com/c-robinson/iplib)
* [graval](https://github.com/koofr/graval) **star:24** FTP服务器框架。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/koofr/graval)
* [publicip](https://github.com/polera/publicip) **star:18** 包publicip返回面向公共的IPv4地址(internet出口)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/polera/publicip)
* [golibwireshark](https://github.com/sunwxg/golibwireshark) **star:16** 用于解码 pcap 文件和分析解剖数据。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sunwxg/golibwireshark)
* [goshark](https://github.com/sunwxg/goshark) **star:9** 用于解码IP包，创建用于分析的数据结构包。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/sunwxg/goshark)
* [llb](https://github.com/kirillDanshin/llb) **star:8** 一个非常简单、快速的代理服务器后端。可用于快速重定向到预定义域，具有零内存分配和快速响应。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/kirillDanshin/llb)
* [go-powerdns](https://github.com/joeig/go-powerdns) **star:8** Golang的PowerDNS API绑定。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/joeig/go-powerdns)
* [tspool](https://github.com/two/tspool) **star:5** TCP库使用工作池来提高性能并保护服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/two/tspool)

### HTTP客户端

*用于发出HTTP请求的库。 (翻译出错了? 试试 [英文版](README_EN.md#http-clients) 吧~)*

* [grequests](https://github.com/levigross/grequests) **star:1460** 一个 Go “克隆”的伟大和著名的请求库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/levigross/grequests)
* [heimdall](https://github.com/gojektech/heimdall) **star:1137** 具有重试和hystrix功能的增强http客户机。   [![godoc][GoDoc]](https://godoc.org/github.com/gojektech/heimdall)
* [sling](https://github.com/dghubble/sling) **star:1035** Sling是一个用于创建和发送API请求的Go HTTP客户端库。   [![godoc][GoDoc]](https://godoc.org/github.com/dghubble/sling)
* [gentleman](https://github.com/h2non/gentleman) **star:685** 功能齐全的插件驱动HTTP客户端库。   [![godoc][GoDoc]](https://godoc.org/github.com/h2non/gentleman)
* [pester](https://github.com/sethgrid/pester) **star:335** 使用重试、后退和并发执行HTTP客户机调用。   [![godoc][GoDoc]](https://godoc.org/github.com/sethgrid/pester)
* [goreq](https://github.com/smallnest/goreq) **star:100** 基于gorequest的增强简化HTTP客户机。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/smallnest/goreq)   ![归档项目][Archived]
* [rq](https://github.com/ddo/rq) **star:31** golang stdlib HTTP客户端更好的接口。   [![godoc][GoDoc]](https://godoc.org/github.com/ddo/rq)
* [sreq](https://github.com/winterssy/sreq) **star:17** 一个简单，用户友好和并发安全的HTTP请求库的Go。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/winterssy/sreq)   ![包含中文文档][CN]

## OpenGL

*用于在Go中使用OpenGL的库。 (翻译出错了? 试试 [英文版](README_EN.md#opengl) 吧~)*

* [glfw](https://github.com/go-gl/glfw) **star:769** GLFW 3 的 Go 接口实现。
* [gl](https://github.com/go-gl/gl) **star:656** OpenGL 的 Go 接口实现(通过glow生成)。   [![godoc][GoDoc]](https://godoc.org/github.com/go-gl/gl)
* [mathgl](https://github.com/go-gl/mathgl) **star:301** 完全基于 Go 实现的数学软件包，专门用于处理三维数学。借鉴于 GLM。   [![godoc][GoDoc]](https://godoc.org/github.com/go-gl/mathgl)
* [goxjs/gl](https://github.com/goxjs/gl) **star:130** 跨平台的OpenGL 接口实现(OS X, Linux, Windows，浏览器，iOS, Android)。   [![godoc][GoDoc]](https://godoc.org/github.com/goxjs/gl)
* [goxjs/glfw](https://github.com/goxjs/glfw) **star:58** 跨平台 glfw 库，可用于创建 OpenGL 上下文并接收事件。   [![godoc][GoDoc]](https://godoc.org/github.com/goxjs/glfw)

## ORM

*Libraries that implement Object-Relational Mapping or datamapping techniques. (翻译出错了? 试试 [英文版](README_EN.md#orm) 吧~)*

* [GORM](https://github.com/jinzhu/gorm) **star:15429** 一个出色的 ORM 库。主要目标是对开发人员友好。   [![star > 2000][Awesome]](https://github.com/jinzhu/gorm)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jinzhu/gorm)
* [Xorm](https://github.com/go-xorm/xorm) **star:5437** 基于 Go 的简单而强大的ORM。   [![star > 2000][Awesome]](https://github.com/go-xorm/xorm)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-xorm/xorm)   ![包含中文文档][CN]
* [go-pg](https://github.com/go-pg/pg) **star:3179** 用于 PostgreSQL 的ORM。侧重于 PostgreSQL 的特性和性能。   [![star > 2000][Awesome]](https://github.com/go-pg/pg)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-pg/pg)
* [gorp](https://github.com/go-gorp/gorp) **star:3145** 基于 Go 的关系持久性 ORM-ish 库。   [![star > 2000][Awesome]](https://github.com/go-gorp/gorp)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/go-gorp/gorp)
* [SQLBoiler](https://github.com/volatiletech/sqlboiler) **star:2380** ORM 生成器。根据数据库 schema 生成一个功能强大且运行速度快的ORM。   [![star > 2000][Awesome]](https://github.com/volatiletech/sqlboiler)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/volatiletech/sqlboiler)
* [upper.io/db](https://github.com/upper/db) **star:1948** 对外提供统一的接口用于访问不同的存储介质，例如PostgreSQL, MySQL, SQLite, MSSQL, QL、MongoDB.。   [![godoc][GoDoc]](https://godoc.org/github.com/upper/db)
* [reform](https://github.com/go-reform/reform) **star:822** 基于非空接口和代码生成的 ORM。   [![godoc][GoDoc]](https://godoc.org/github.com/go-reform/reform)
* [pop/soda](https://github.com/gobuffalo/pop) **star:713** 数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gobuffalo/pop)
* [QBS](https://github.com/coocood/qbs) **star:540** Stands for Query By Struct. A Go ORM.   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/coocood/qbs)   ![包含中文文档][CN]
* [go-queryset](https://github.com/jirfag/go-queryset) **star:458** 基于 GORM 100% 类型安全的 ORM。可支持 MySQL, PostgreSQL, Sqlite3, SQL Server。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jirfag/go-queryset)
* [beego orm](https://github.com/astaxie/beego/tree/master/orm)  强大的orm框架。支持: pq/mysql/sqlite3。
* [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) **star:259** 一个灵活而强大的SQL字符串构建器库。   [![godoc][GoDoc]](https://godoc.org/github.com/huandu/go-sqlbuilder)
* [Zoom](https://github.com/albrow/zoom) **star:244** 基于 Redis 的快速数据存储和查询引擎。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/albrow/zoom)
* [grimoire](https://github.com/Fs02/grimoire) **star:118** 基于 golang 的数据库访问层和验证库。(支持: MySQL, PostgreSQL和SQLite3)。   [![godoc][GoDoc]](https://godoc.org/github.com/Fs02/grimoire)
* [go-store](https://github.com/gosuri/go-store) **star:96** 简单且快速的 Redis 键值存储库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/go-store)
* [Marlow](https://github.com/dadleyy/marlow) **star:68** 从项目结构生成ORM。   [![godoc][GoDoc]](https://godoc.org/github.com/dadleyy/marlow)
* [lore](https://github.com/abrahambotros/lore) **star:5** Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/abrahambotros/lore)
* [go-firestorm](https://github.com/jschoedt/go-firestorm) **star:2** 一个轻量级的ORM。用于Google/Firebase Cloud Firestore。   [![godoc][GoDoc]](https://godoc.org/github.com/jschoedt/go-firestorm)

## 包管理

*用于管理依赖和包的官方工具 (翻译出错了? 试试 [英文版](README_EN.md#package-management) 吧~)*

* [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more)  Modules 是源码的版本控制和交换的单位。go命令直接支持处理模块，包括记录和解决对其他模块的依赖关系。

*包管理的官方实验工具 (翻译出错了? 试试 [英文版](README_EN.md#package-management) 吧~)*

* [dep](https://github.com/golang/dep) **star:12761**  Go 的依赖管理工具，需要 Go 1.9+   [![star > 2000][Awesome]](https://github.com/golang/dep)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/dep)
* [vgo](https://go.googlesource.com/vgo/)  Go 命令版本管理

*用于包和依赖项管理的非官方库。 (翻译出错了? 试试 [英文版](README_EN.md#package-management) 吧~)*

* [glide](https://github.com/Masterminds/glide) **star:7841** 轻松管理您的 golang 第三方包。受Maven、Bundler和Pip等工具的启发。   [![star > 2000][Awesome]](https://github.com/Masterminds/glide)   [![godoc][GoDoc]](https://godoc.org/github.com/Masterminds/glide)
* [godep](https://github.com/tools/godep) **star:5643** godep是go的依赖工具，它通过修复包的依赖关系来帮助构建可重复的包。   [![star > 2000][Awesome]](https://github.com/tools/godep)   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tools/godep)   ![归档项目][Archived]
* [govendor](https://github.com/kardianos/govendor) **star:4830** 包管理器。使用 vendor 文件的 Go vendor 工具。   [![star > 2000][Awesome]](https://github.com/kardianos/govendor)   [![godoc][GoDoc]](https://godoc.org/github.com/kardianos/govendor)
* [gopm](https://github.com/gpmgo/gopm) **star:2394** 包管理器。   [![star > 2000][Awesome]](https://github.com/gpmgo/gopm)   [![godoc][GoDoc]](https://godoc.org/github.com/gpmgo/gopm)   ![归档项目][Archived]
* [gom](https://github.com/mattn/gom) **star:1356** Go Manager - bundle for Go。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/gom)
* [gpm](https://github.com/pote/gpm) **star:1205** 基本的 Go 依赖管理器。   ![最近一年没有更新][Yellow]
* [goop](https://github.com/nitrous-io/goop) **star:777** Go 的简单依赖管理器，灵感来自Bundler。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/nitrous-io/goop)
* [nut](https://github.com/jingweno/nut) **star:245** vendor 依赖。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/jingweno/nut)
* [johnny-deps](https://github.com/VividCortex/johnny-deps) **star:214** 使用Git的最小依赖版本。   ![最近一年没有更新][Yellow]
* [gigo](https://github.com/LyricalSecurity/gigo) **star:197** 类似pip的golang依赖工具，支持私有存储库和散列。   [![godoc][GoDoc]](https://godoc.org/github.com/LyricalSecurity/gigo)
* [VenGO](https://github.com/DamnWidget/VenGO) **star:115** 创建和管理可导出的隔离go虚拟环境。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/DamnWidget/VenGO)
* [mvn-golang](https://github.com/raydac/mvn-golang) **star:90** 插件，为自动加载Golang SDK，依赖关系管理和启动Maven项目基础设施中的构建环境提供了方法。
* [gop](https://github.com/lunny/gop) **star:50** 在GOPATH之外构建和管理Go应用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/lunny/gop)   ![包含中文文档][CN]   ![归档项目][Archived]

## 性能

* [jaeger](https://github.com/jaegertracing/jaeger) **star:9151** 分布式跟踪系统。   [![star > 2000][Awesome]](https://github.com/jaegertracing/jaeger)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/jaegertracing/jaeger)
* [profile](https://github.com/pkg/profile) **star:1077** Go的简单分析支持包。   [![godoc][GoDoc]](https://godoc.org/github.com/pkg/profile)
* [tracer](https://github.com/kamilsk/tracer) **star:12** 简单、轻量级的跟踪。   [![godoc][GoDoc]](https://godoc.org/github.com/kamilsk/tracer)

## 查询语言

* [graphql-go](https://github.com/graphql-go/graphql) **star:5503** 为Go实现GraphQL。   [![star > 2000][Awesome]](https://github.com/graphql-go/graphql)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/graphql-go/graphql)
* [graphql](https://github.com/neelance/graphql-go) **star:2916** 关注易用性的GraphQL服务器。   [![star > 2000][Awesome]](https://github.com/neelance/graphql-go)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/neelance/graphql-go)
* [gojsonq](https://github.com/thedevsaddam/gojsonq) **star:1044** 一个用来查询JSON数据的Go包。   [![godoc][GoDoc]](https://godoc.org/github.com/thedevsaddam/gojsonq)
* [jsonql](https://github.com/elgs/jsonql) **star:204** Golang中的JSON查询表达式库。   [![godoc][GoDoc]](https://godoc.org/github.com/elgs/jsonql)
* [rql](https://github.com/a8m/rql) **star:117** 用于REST API的资源查询语言。   [![godoc][GoDoc]](https://godoc.org/github.com/a8m/rql)
* [graphql](https://github.com/tmc/graphql) **star:51** graphql解析器+工具集   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/tmc/graphql)
* [jsonslice](https://github.com/bhmj/jsonslice) **star:25** 使用高级过滤器查询Jsonpath。   [![godoc][GoDoc]](https://godoc.org/github.com/bhmj/jsonslice)
* [straf](https://github.com/SonicRoshan/straf) **star:1** 轻松地将Golang结构转换为GraphQL对象。   [![godoc][GoDoc]](https://godoc.org/github.com/SonicRoshan/straf)

## 嵌入的资源

* [packr](https://github.com/gobuffalo/packr) **star:2337** 将静态文件嵌入到Go二进制文件中的简单方法。   [![star > 2000][Awesome]](https://github.com/gobuffalo/packr)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gobuffalo/packr)
* [statik](https://github.com/rakyll/statik) **star:2264** 将静态文件嵌入到Go可执行文件中。   [![star > 2000][Awesome]](https://github.com/rakyll/statik)   [![godoc][GoDoc]](https://godoc.org/github.com/rakyll/statik)
* [go.rice](https://github.com/GeertJohan/go.rice) **star:1722** go.rice 是一个Go包，它使处理html、js、css、图像和模板等资源变得非常容易。   [![godoc][GoDoc]](https://godoc.org/github.com/GeertJohan/go.rice)
* [vfsgen](https://github.com/shurcooL/vfsgen) **star:697** 生成一个vfsdata。静态实现给定虚拟文件系统的go文件。   [![godoc][GoDoc]](https://godoc.org/github.com/shurcooL/vfsgen)
* [esc](https://github.com/mjibson/esc) **star:491** 将文件嵌入到Go程序中并提供http文件系统接口。   [![godoc][GoDoc]](https://godoc.org/github.com/mjibson/esc)
* [fileb0x](https://github.com/UnnoTed/fileb0x) **star:448** 一个可定制的工具用来在Go中嵌入文件   [![godoc][GoDoc]](https://godoc.org/github.com/UnnoTed/fileb0x)
* [go-resources](https://github.com/omeid/go-resources) **star:158** 嵌入到Go中的普通资源。   [![godoc][GoDoc]](https://godoc.org/github.com/omeid/go-resources)
* [statics](https://github.com/go-playground/statics) **star:54** 将静态资源嵌入到go文件中，用于单个二进制编译+使用http。文件系统+符号链接。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/statics)
* [templify](https://github.com/wlbr/templify) **star:22** 将外部模板文件嵌入到Go代码中，以创建单个文件二进制文件。   [![godoc][GoDoc]](https://godoc.org/github.com/wlbr/templify)
* [go-embed](https://github.com/pyros2097/go-embed) **star:17** 生成go代码，将资源文件嵌入到库或可执行文件中。   [![godoc][GoDoc]](https://godoc.org/github.com/pyros2097/go-embed)

## 科学与数据分析

*用于科学计算和数据分析的库。 (翻译出错了? 试试 [英文版](README_EN.md#science-and-data-analysis) 吧~)*

* [gonum](https://github.com/gonum/gonum) **star:3141** Gonum是一组用于Go编程语言的数字库。它包含用于矩阵、统计、优化等的库。   [![star > 2000][Awesome]](https://github.com/gonum/gonum)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gonum/gonum)
* [stats](https://github.com/montanaflynn/stats) **star:1379** 包含Golang标准库中缺少的公共函数的统计软件包。   [![godoc][GoDoc]](https://godoc.org/github.com/montanaflynn/stats)
* [gosl](https://github.com/cpmech/gosl) **star:1337** 提供线性代数，FFT，几何，NURBS，数值方法，概率，优化，微分方程，等等。   [![godoc][GoDoc]](https://godoc.org/github.com/cpmech/gosl)
* [streamtools](https://github.com/nytlabs/streamtools) **star:1314** 通用图形工具，用于处理数据流。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/nytlabs/streamtools)
* [gonum/plot](https://github.com/gonum/plot) **star:1267** gonum/plot提供了一个API，用于在Go中构建和绘制绘图。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gonum/plot)
* [go-dsp](https://github.com/mjibson/go-dsp) **star:636** Go数字信号处理。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/mjibson/go-dsp)
* [goraph](https://github.com/gyuho/goraph) **star:604** 纯Go图论库(数据结构，算法可视化)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/gyuho/goraph)
* [chart](https://github.com/vdobler/chart) **star:592** 简单的图表绘制库。支持多种图形类型。   [![godoc][GoDoc]](https://godoc.org/github.com/vdobler/chart)
* [ewma](https://github.com/VividCortex/ewma) **star:273** 提供指数加权移动平均算法。   [![godoc][GoDoc]](https://godoc.org/github.com/VividCortex/ewma)
* [graph](https://github.com/yourbasic/graph) **star:257** 基本图形算法库。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/yourbasic/graph)
* [orb](https://github.com/paulmach/orb) **star:219** 2D几何类型，支持剪切、GeoJSON和Mapbox矢量平铺。   [![godoc][GoDoc]](https://godoc.org/github.com/paulmach/orb)
* [gohistogram](https://github.com/VividCortex/gohistogram) **star:131** 数据流的近似直方图。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/VividCortex/gohistogram)
* [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) **star:95** 用于机器学习和统计的数据模型(类似于 pandas)。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/rocketlaunchr/dataframe-go)
* [sparse](https://github.com/james-bowman/sparse) **star:76**  Go 稀疏矩阵格式的线性代数支持科学和机器学习应用程序，兼容gonum矩阵库。   [![godoc][GoDoc]](https://godoc.org/github.com/james-bowman/sparse)
* [TextRank](https://github.com/DavidBelicza/TextRank) **star:74** TextRank在Golang中的实现，支持扩展特性(摘要、加权、短语提取)和多线程(goroutine)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/DavidBelicza/TextRank)
* [pagerank](https://github.com/alixaxel/pagerank) **star:52** 加权 PageRank 算法在Go中的实现。   [![godoc][GoDoc]](https://godoc.org/github.com/alixaxel/pagerank)
* [geom](https://github.com/skelterjohn/geom) **star:42**  Go 的二维几何。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/skelterjohn/geom)
* [evaler](https://github.com/soniah/evaler) **star:40** 简单的浮点算术表达式求值器。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/soniah/evaler)
* [goent](https://github.com/kzahedi/goent) **star:13**  Go 实现熵度量。   [![godoc][GoDoc]](https://godoc.org/github.com/kzahedi/goent)
* [triangolatte](https://github.com/tchayen/triangolatte) **star:12** 二维三角库。允许将线和多边形(都基于点)转换为gpu语言。   [![godoc][GoDoc]](https://godoc.org/github.com/tchayen/triangolatte)
* [ode](https://github.com/ChristopherRabotin/ode) **star:11** 常微分方程(ODE)求解器，支持扩展状态和基于信道的迭代停止条件。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ChristopherRabotin/ode)
* [GoStats](https://github.com/OGFris/GoStats) **star:10** GoStats是一个开放源码的GoLang库，主要用于机器学习领域的数学统计，它涵盖了大多数统计度量函数。   [![godoc][GoDoc]](https://godoc.org/github.com/OGFris/GoStats)
* [PiHex](https://github.com/claygod/PiHex) **star:9** 实现了针对16进制数 Pi 的“bailee - borwein - plouffe”算法。   [![godoc][GoDoc]](https://godoc.org/github.com/claygod/PiHex)
* [piecewiselinear](https://github.com/sgreben/piecewiselinear) **star:7** 微型线性插值库。   [![godoc][GoDoc]](https://godoc.org/github.com/sgreben/piecewiselinear)
* [go-gt](https://github.com/ThePaw/go-gt) **star:5** 用“Go”语言编写的图论算法。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/ThePaw/go-gt)
* [assocentity](https://github.com/ndabAP/assocentity) **star:4** assocentity 返回单词到给定实体的平均距离。   [![godoc][GoDoc]](https://godoc.org/github.com/ndabAP/assocentity)
* [rootfinding](https://github.com/khezen/rootfinding) **star:3** 二次函数求根算法库。   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/rootfinding)
* [bradleyterry](https://github.com/seanhagen/bradleyterry) **star:1** 为成对比较提供了一个 Bradley-Terry 模型。   [![godoc][GoDoc]](https://godoc.org/github.com/seanhagen/bradleyterry)

## 安全

*用于帮助您的应用程序更安全的库。 (翻译出错了? 试试 [英文版](README_EN.md#security) 吧~)*

* [lego](https://github.com/xenolf/lego) **star:3640** 纯 Go ACME 客户端库及命令行工具   [![star > 2000][Awesome]](https://github.com/xenolf/lego)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/xenolf/lego)
* [Cameradar](https://github.com/Ullaakut/cameradar) **star:1891** 工具和库，以远程入侵RTSP流从监控摄像头。   [![godoc][GoDoc]](https://godoc.org/github.com/Ullaakut/cameradar)
* [acmetool](https://github.com/hlandau/acme) **star:1701** ACME(让我们用自动更新加密)客户端工具。   [![godoc][GoDoc]](https://godoc.org/github.com/hlandau/acme)
* [memguard](https://github.com/awnumar/memguard) **star:1582** 一个用于处理内存中敏感值的纯Go库。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/awnumar/memguard)
* [secure](https://github.com/unrolled/secure) **star:1248** Go 语言 HTTP 中间件，为 Go 提供了一些安全功能   [![godoc][GoDoc]](https://godoc.org/github.com/unrolled/secure)
* [acra](https://github.com/cossacklabs/acra) **star:472** 网络加密代理保护基于数据库的应用程序免受数据泄漏:强选择性加密，SQL注入预防，入侵检测系统。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/cossacklabs/acra)
* [nacl](https://github.com/kevinburke/nacl) **star:456**  Go 实现NaCL API的集合。   [![godoc][GoDoc]](https://godoc.org/github.com/kevinburke/nacl)
* [BadActor](https://github.com/jaredfolkins/badactor) **star:251** 一个驻留在内存中的，应用驱动的监控程序，受 fail2ban 的启发   [![godoc][GoDoc]](https://godoc.org/github.com/jaredfolkins/badactor)
* [passlib](https://github.com/hlandau/passlib) **star:229** 不过时的密码哈希库。   [![godoc][GoDoc]](https://godoc.org/github.com/hlandau/passlib)
* [ssh-vault](https://github.com/ssh-vault/ssh-vault) **star:200** 使用ssh密钥加密/解密。   [![godoc][GoDoc]](https://godoc.org/github.com/ssh-vault/ssh-vault)
* [simple-scrypt](https://github.com/elithrar/simple-scrypt) **star:159** Scrypt 库，具有简单、易懂的 API，同时具有内置的自动校准功能   [![godoc][GoDoc]](https://godoc.org/github.com/elithrar/simple-scrypt)
* [go-yara](https://github.com/hillu/go-yara) **star:137** YARA的 Go 语言接口，号称是 “对于恶意软件研究者（以及其他人）来说是模式匹配的瑞士军刀”   [![godoc][GoDoc]](https://godoc.org/github.com/hillu/go-yara)
* [argon2pw](https://github.com/raja/argon2pw) **star:76** 使用常量时间密码比较生成Argon2密码散列。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/raja/argon2pw)
* [autocert](https://godoc.org/golang.org/x/crypto/acme/autocert)  让我们加密证书并启动TLS服务器。
* [Interpol](https://bitbucket.org/vahidi/interpol)  基于规则的数据生成器，用于模糊和渗透测试。
* [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) **star:32** 一个安全哈希和加密密码的偏执包。   [![godoc][GoDoc]](https://godoc.org/github.com/dwin/goSecretBoxPassword)
* [goArgonPass](https://github.com/dwin/goArgonPass) **star:11** Argon2密码散列和验证设计为与现有Python和PHP实现兼容。   [![godoc][GoDoc]](https://godoc.org/github.com/dwin/goArgonPass)
* [certificates](https://github.com/mvmaasakkers/certificates) **star:10** 用于生成tls证书的自定义工具。   [![godoc][GoDoc]](https://godoc.org/github.com/mvmaasakkers/certificates)
* [sslmgr](https://github.com/adrianosela/sslmgr) **star:7** 使用围绕acme/autocert的高级包装器，SSL证书变得很容易。   [![godoc][GoDoc]](https://godoc.org/github.com/adrianosela/sslmgr)
* [jwc](https://github.com/khezen/jwc) **star:5** JSON Web加密库。   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/jwc)   ![归档项目][Archived]

## 序列化

*用于二进制序列化的库和工具。 (翻译出错了? 试试 [英文版](README_EN.md#serialization) 吧~)*

* [jsoniter](https://github.com/json-iterator/go) **star:5902** 高性能，100% 兼容的“encoding/json” 替代品   [![star > 2000][Awesome]](https://github.com/json-iterator/go)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/json-iterator/go)
* [goprotobuf](https://github.com/golang/protobuf) **star:5459** 通过库和协议编译器插件使 Go 语言支持 Google的 protocol buffers.   [![star > 2000][Awesome]](https://github.com/golang/protobuf)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/golang/protobuf)
* [gogoprotobuf](https://github.com/gogo/protobuf) **star:3145** Go 语言的 Protocol Buffer 库。   [![star > 2000][Awesome]](https://github.com/gogo/protobuf)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/gogo/protobuf)
* [mapstructure](https://github.com/mitchellh/mapstructure) **star:2631** 用于对原生键值对进行解码生成 Go 语言结构体   [![star > 2000][Awesome]](https://github.com/mitchellh/mapstructure)   [![godoc][GoDoc]](https://godoc.org/github.com/mitchellh/mapstructure)
* [go-codec](https://github.com/ugorji/go) **star:1275** 高性能、多功能、规范化编码解码以及 rpc 库， 用于 msgpack, cbor 和 json，支持基于运行时的 OR 码生成   [![godoc][GoDoc]](https://godoc.org/github.com/ugorji/go)
* [colfer](https://github.com/pascaldekloe/colfer) **star:480** 为Colfer二进制格式生成代码。
* [csvutil](https://github.com/jszwec/csvutil) **star:314** 高性能、惯用的CSV记录编码和解码到本机Go结构。   [![godoc][GoDoc]](https://godoc.org/github.com/jszwec/csvutil)
* [go-capnproto](https://github.com/glycerine/go-capnproto) **star:273** Go 语言用的 Cap'n Proto 库及解析器   [![godoc][GoDoc]](https://godoc.org/github.com/glycerine/go-capnproto)
* [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) **star:125** 用于协同 PHP session 格式数据和 PHP 序列化／反序列化函数工作的go语言库   [![godoc][GoDoc]](https://godoc.org/github.com/yvasiyarov/php_session_decoder)
* [structomap](https://github.com/tuvistavie/structomap) **star:101** 用于从静态结构体简单、动态的生成键值对的库   [![godoc][GoDoc]](https://godoc.org/github.com/tuvistavie/structomap)
* [bambam](https://github.com/glycerine/bambam) **star:60** 用于 Go 语言生成 Cap'n Proto schemas 的生成器   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/glycerine/bambam)
* [asn1](https://github.com/PromonLogicalis/asn1) **star:41** 面向golang的BER和DER编码库。   [![godoc][GoDoc]](https://godoc.org/github.com/PromonLogicalis/asn1)   ![归档项目][Archived]
* [fwencoder](https://github.com/o1egl/fwencoder) **star:10** 用于Go的固定宽度文件解析器(编码和解码库)。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/o1egl/fwencoder)
* [binstruct](https://github.com/ghostiam/binstruct) **star:9** 用于将数据映射到结构中的Golang二进制解码器。   [![godoc][GoDoc]](https://godoc.org/github.com/ghostiam/binstruct)
* [bel](https://github.com/32leaves/bel) **star:6** 从Go structs/interface生成TypeScript接口。对JSON RPC很有用。   [![godoc][GoDoc]](https://godoc.org/github.com/32leaves/bel)
* [pletter](https://github.com/vimeda/pletter) **star:6** A standard way to wrap a proto message for message brokers.   [![godoc][GoDoc]](https://godoc.org/github.com/vimeda/pletter)

## 服务器应用程序

* [etcd](https://github.com/coreos/etcd) **star:27575** 为共享配置和服务发现提供高可用的键值存储。   [![star > 2000][Awesome]](https://github.com/coreos/etcd)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/coreos/etcd)
* [Caddy](https://github.com/mholt/caddy) **star:24326** Caddy是另一种HTTP/2 web服务器，易于配置和使用。   [![star > 2000][Awesome]](https://github.com/mholt/caddy)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mholt/caddy)
* [consul](https://www.consul.io/)  Consul 是一个用于服务发现、监控和配置的工具
* [minio](https://github.com/minio/minio) **star:18360** Minio是一个分布式对象存储服务器。   [![star > 2000][Awesome]](https://github.com/minio/minio)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/minio/minio)
* [RoadRunner](https://github.com/spiral/roadrunner) **star:3513** 高性能PHP应用服务器，负载平衡器和进程管理器。   [![star > 2000][Awesome]](https://github.com/spiral/roadrunner)   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/spiral/roadrunner)
* [devd](https://github.com/cortesi/devd) **star:2847** 为开发人员提供本地web服务器。   [![star > 2000][Awesome]](https://github.com/cortesi/devd)   [![godoc][GoDoc]](https://godoc.org/github.com/cortesi/devd)
* [algernon](https://github.com/xyproto/algernon) **star:1610** 内置支持Lua、Markdown、GCSS和Amber的HTTP/2 web服务器。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/xyproto/algernon)
* [SFTPGo](https://github.com/drakkan/sftpgo) **star:1070** 功能齐全，高度可配置的SFTP服务器软件。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/drakkan/sftpgo)
* [yakvs](https://git.sci4me.com/sci4me/yakvs)  小型化、网络化、基于内存的键值存储
* [flipt](https://github.com/markphelps/flipt) **star:1018** 一个用Go和Vue.js编写的自包含特性标志解决方案   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/markphelps/flipt)
* [Flagr](https://github.com/checkr/flagr) **star:893** Flagr是一个开源特性标记和A/B测试服务。   [![godoc][GoDoc]](https://godoc.org/github.com/checkr/flagr)
* [Fider](https://github.com/getfider/fider) **star:849** Fider是一个收集和组织客户反馈的开放平台。   [![godoc][GoDoc]](https://godoc.org/github.com/getfider/fider)
* [jackal](https://github.com/ortuman/jackal) **star:741** 用Go编写的XMPP服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/ortuman/jackal)
* [discovery](https://github.com/Bilibili/discovery) **star:719** 用于弹性中间层负载平衡和故障转移的注册表。   [![godoc][GoDoc]](https://godoc.org/github.com/Bilibili/discovery)
* [dudeldu](https://github.com/krotik/dudeldu) **star:97** 一个简单的SHOUTcast服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/krotik/dudeldu)
* [psql-streamer](https://github.com/blind-oracle/psql-streamer) **star:9** 从PostgreSQL到Kafka的流数据库事件。   [![godoc][GoDoc]](https://godoc.org/github.com/blind-oracle/psql-streamer)
* [riemann-relay](https://github.com/blind-oracle/riemann-relay)  传递到负载平衡Riemann事件并/或将其转换为 Carbon。
* [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) **star:6** Nginx日志解析器和Prometheus 导出。   [![godoc][GoDoc]](https://godoc.org/github.com/blind-oracle/nginx-prometheus)
* [nsq](http://nsq.io/)  一个实时分布式消息平台。

## 流处理

*用于流处理和响应式编程的库和工具。 (翻译出错了? 试试 [英文版](README_EN.md#stream-processing) 吧~)*

* [go-streams](https://github.com/reugn/go-streams) **star:212** 流处理库。   [![godoc][GoDoc]](https://godoc.org/github.com/reugn/go-streams)

## 模板引擎

*用于模板和词法分析的库和工具。 (翻译出错了? 试试 [英文版](README_EN.md#template-engines) 吧~)*

