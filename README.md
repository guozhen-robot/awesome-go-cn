# Awesome Go

[Awesome]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.4.1/docs/awesome.svg "star > 2000"
[Green]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Green.svg "最近一周有更新"
[Yellow]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Yellow.svg "最近一年没有更新"
[CN]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Cn.svg "包含中文文档"
[Archived]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.2.1/docs/archived.svg "项目已归档"
[GoDoc]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.3.0/docs/DOC.svg "godoc文档地址"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2019-10-11 10:12:08(每隔1天同步一次)**

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

* [gocui](https://github.com/jroimartin/gocui) **star:5598** 旨在创建控制台用户界面的极简Go库。   [![star > 2000][Awesome]](https://github.com/jroimartin/gocui)   [![godoc][GoDoc]](https://godoc.org/github.com/jroimartin/gocui)
* [color](https://github.com/fatih/color) **star:3096** 多功能包装，彩色终端输出。   [![star > 2000][Awesome]](https://github.com/fatih/color)   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/fatih/color)   ![归档项目][Archived]
* [go-prompt](https://github.com/c-bata/go-prompt) **star:2562** 构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)   [![star > 2000][Awesome]](https://github.com/c-bata/go-prompt)   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/go-prompt)
* [asciigraph](https://github.com/guptarohit/asciigraph) **star:1199** 在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/guptarohit/asciigraph)
* [aurora](https://github.com/logrusorgru/aurora) **star:680** 支持fmt.Printf/Sprintf的ANSI终端颜色。   [![godoc][GoDoc]](https://godoc.org/github.com/logrusorgru/aurora)
* [go-colorable](https://github.com/mattn/go-colorable) **star:391** 适用于windows的颜色编写器。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-colorable)
* [go-isatty](https://github.com/mattn/go-isatty) **star:360** Go 实现的 isatty。   ![最近一周有更新][Green]   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-isatty)
* [chalk](https://github.com/ttacon/chalk) **star:314** 美化终端/控制台输出。   [![godoc][GoDoc]](https://godoc.org/github.com/ttacon/chalk)
* [go-colortext](https://github.com/daviddengcn/go-colortext) **star:197** 在终端中使用彩色文字。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/daviddengcn/go-colortext)
* [cfmt](https://github.com/mingrammer/cfmt) **star:67** 提供上下文的fmt，灵感来自于bootstrap color classes。   [![godoc][GoDoc]](https://godoc.org/github.com/mingrammer/cfmt)
* [colourize](https://github.com/TreyBastian/colourize) **star:16** 在终端提供ANSI彩色文本。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/TreyBastian/colourize)
* [ctc](https://github.com/wzshiming/ctc) **star:10** 不需要Print方法的非侵入性跨平台终端颜色库。   [![godoc][GoDoc]](https://godoc.org/github.com/wzshiming/ctc)   ![包含中文文档][CN]
* [go-ataman](https://github.com/workanator/go-ataman) **star:8** 在终端提供ANSI彩色文本模板。   ![最近一年没有更新][Yellow]   [![godoc][GoDoc]](https://godoc.org/github.com/workanator/go-ataman)
* [gommon/color](https://github.com/labstack/gommon/tree/m
