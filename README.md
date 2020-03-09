# Awesome Go

[Awesome]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.4.1/docs/awesome.svg "star > 2000"
[Green]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Green.svg "最近一周有更新"
[Yellow]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Yellow.svg "最近一年没有更新"
[CN]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Cn.svg "包含中文文档"
[Archived]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.2.1/docs/archived.svg "项目已归档"
[GoDoc]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.3.0/docs/DOC.svg "godoc文档地址"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2020-03-09 14:48:01(每隔1天同步一次)**

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
    - [动态域名](#动态域名)
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

* [Oto](https://github.com/hajimehoshi/oto) **star:546** 多平台的 low-level 声音播放库。   [![最近一周有更新][Green]](https://github.com/hajimehoshi/oto)   [![godoc][GoDoc]](https://godoc.org/github.com/hajimehoshi/oto)
* [PortAudio](https://github.com/gordonklaus/portaudio) **star:336** 基于 Go 的PortAudio audio I/O库。   [![最近一年没有更新][Yellow]](https://github.com/gordonklaus/portaudio)   [![godoc][GoDoc]](https://godoc.org/github.com/gordonklaus/portaudio)
* [music-theory](https://github.com/go-music-theory/music-theory) **star:284** 基于 Go 的音乐理论模型。   [![godoc][GoDoc]](https://godoc.org/github.com/go-music-theory/music-theory)
* [waveform](https://github.com/mdlayher/waveform) **star:276** 通过音频流生成波形图像的包。   [![最近一年没有更新][Yellow]](https://github.com/mdlayher/waveform)   [![godoc][GoDoc]](https://godoc.org/github.com/mdlayher/waveform)
* [portmidi](https://github.com/rakyll/portmidi) **star:226** PortMidi的 Go 语言实现接口.   [![godoc][GoDoc]](https://godoc.org/github.com/rakyll/portmidi)
* [id3v2](https://github.com/bogem/id3v2) **star:143** 快速稳定的 ID3 解析及写入Go库。   [![最近一周有更新][Green]](https://github.com/bogem/id3v2)   [![godoc][GoDoc]](https://godoc.org/github.com/bogem/id3v2)
* [flac](https://github.com/mewkiz/flac) **star:117** 原生 Go FLAC编码器/解码器，支持FLAC流。   [![godoc][GoDoc]](https://godoc.org/github.com/mewkiz/flac)
* [mix](https://github.com/go-mix/mix) **star:112** 基于序列的 Go 原生音乐混音器。   [![godoc][GoDoc]](https://godoc.org/github.com/go-mix/mix)
* [mp3](https://github.com/tcolgate/mp3) **star:107** 原生 Go MP3解码器。   [![最近一年没有更新][Yellow]](https://github.com/tcolgate/mp3)   [![godoc][GoDoc]](https://godoc.org/github.com/tcolgate/mp3)
* [go-sox](https://github.com/krig/go-sox) **star:105** libsox 的 Go 语言实现接口。   [![最近一年没有更新][Yellow]](https://github.com/krig/go-sox)   [![godoc][GoDoc]](https://godoc.org/github.com/krig/go-sox)
* [malgo](https://github.com/gen2brain/malgo) **star:96** 迷你音频库。   [![godoc][GoDoc]](https://godoc.org/github.com/gen2brain/malgo)
* [taglib](https://github.com/wtolson/go-taglib) **star:72** taglib 的 Go 语言实现接口.   [![最近一年没有更新][Yellow]](https://github.com/wtolson/go-taglib)   [![godoc][GoDoc]](https://godoc.org/github.com/wtolson/go-taglib)
* [gaad](https://github.com/Comcast/gaad) **star:68** 原生 Go AAC位流解析器。   [![godoc][GoDoc]](https://godoc.org/github.com/Comcast/gaad)
* [minimp3](https://github.com/tosone/minimp3) **star:38** 轻量级MP3解码器库。
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) **star:28** libmediainfo 的 Go 语言实现接口。   [![最近一年没有更新][Yellow]](https://github.com/zhulik/go_mediainfo)   [![godoc][GoDoc]](https://godoc.org/github.com/zhulik/go_mediainfo)
* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) **star:27** EasyMidi是一个简单可靠的库，用于处理标准midi文件(SMF)。   [![最近一年没有更新][Yellow]](https://github.com/algoGuy/EasyMIDI)   [![godoc][GoDoc]](https://godoc.org/github.com/algoGuy/EasyMIDI)
* [vorbis](https://github.com/mccoyst/vorbis) **star:25** “原生” Go Vorbis解码器(使用CGO，但没有依赖关系)。   [![godoc][GoDoc]](https://godoc.org/github.com/mccoyst/vorbis)
* [gosamplerate](https://github.com/dh1tw/gosamplerate) **star:9** libsamplerate 的 Go 语言实现接口。   [![godoc][GoDoc]](https://godoc.org/github.com/dh1tw/gosamplerate)

## 身份验证和OAuth

*用于实现验证方案的库。 (翻译出错了? 试试 [英文版](README_EN.md#authentication-and-oauth) 吧~)*

* [jwt-go](https://github.com/dgrijalva/jwt-go) **star:7168** JSON Web令牌(JWT)。   [![star > 2000][Awesome]](https://github.com/dgrijalva/jwt-go)   [![最近一周有更新][Green]](https://github.com/dgrijalva/jwt-go)   [![godoc][GoDoc]](https://godoc.org/github.com/dgrijalva/jwt-go)
* [casbin](https://github.com/hsluoyz/casbin) **star:6219** 支持ACL、RBAC、ABAC等访问控制模型的授权库。   [![star > 2000][Awesome]](https://github.com/hsluoyz/casbin)   [![最近一周有更新][Green]](https://github.com/hsluoyz/casbin)   [![godoc][GoDoc]](https://godoc.org/github.com/hsluoyz/casbin)
* [oauth2](https://github.com/golang/oauth2) **star:2763** goauth2的继任者。通用OAuth 2.0包，附带JWT、谷歌api、计算引擎和应用程序引擎支持。   [![star > 2000][Awesome]](https://github.com/golang/oauth2)   [![最近一周有更新][Green]](https://github.com/golang/oauth2)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/oauth2)
* [goth](https://github.com/markbates/goth) **star:2576** 提供了 OAuth 和 OAuth2 的简单清晰易用的方法。可开箱即用处理多个提供程序。   [![star > 2000][Awesome]](https://github.com/markbates/goth)   [![最近一周有更新][Green]](https://github.com/markbates/goth)   [![godoc][GoDoc]](https://godoc.org/github.com/markbates/goth)
* [authboss](https://github.com/volatiletech/authboss) **star:2163** web模块化认证系统。它试图删除尽可能多的模板文件和硬编码，以便每次新建一个新的web项目时，您都可以插入、配置并开始构建您的应用程序，而不必每次都构建一个身份验证系统。   [![star > 2000][Awesome]](https://github.com/volatiletech/authboss)   [![godoc][GoDoc]](https://godoc.org/github.com/volatiletech/authboss)
* [osin](https://github.com/openshift/osin) **star:1584** OAuth2服务器库。   [![godoc][GoDoc]](https://godoc.org/github.com/openshift/osin)
* [go-jose](https://github.com/square/go-jose) **star:1482** 相当完整地实现了JOSE工作组的JSON Web令牌、JSON Web签名和JSON Web加密规范。   [![最近一周有更新][Green]](https://github.com/square/go-jose)   [![godoc][GoDoc]](https://godoc.org/github.com/square/go-jose)
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) **star:1459** 用 Golang 编写的独立且符合规范的OAuth2服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/go-oauth2-server)
* [gologin](https://github.com/dghubble/gologin) **star:1167** 用于使用OAuth1和OAuth2身份验证提供者登录的可链处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/dghubble/gologin)
* [gorbac](https://github.com/mikespook/gorbac) **star:993** 轻量级的基于角色的访问控制(RBAC)实现。   [![godoc][GoDoc]](https://godoc.org/github.com/mikespook/gorbac)
* [loginsrv](https://github.com/tarent/loginsrv) **star:916** JWT登录微服务带有可插拔的后端服务，如OAuth2 (Github)、htpasswd、osiam。   [![godoc][GoDoc]](https://godoc.org/github.com/tarent/loginsrv)
* [scs](https://github.com/alexedwards/scs) **star:680** HTTP服务器的会话管理器。   [![godoc][GoDoc]](https://godoc.org/github.com/alexedwards/scs)
* [permissions2](https://github.com/xyproto/permissions2) **star:391** 用于跟踪用户、登录状态和权限的库。依赖于cookie安全和bcrypt。   [![godoc][GoDoc]](https://godoc.org/github.com/xyproto/permissions2)
* [paseto](https://github.com/o1egl/paseto) **star:317** 平台无关的安全令牌(PASETO)。   [![godoc][GoDoc]](https://godoc.org/github.com/o1egl/paseto)
* [jeff](https://github.com/abraithwaite/jeff) **star:190** 简单、灵活、安全和惯用的web会话管理，具有可配置化的后端。   [![godoc][GoDoc]](https://godoc.org/github.com/abraithwaite/jeff)
* [httpauth](https://github.com/goji/httpauth) **star:190** HTTP身份验证中间件。   [![最近一年没有更新][Yellow]](https://github.com/goji/httpauth)   [![godoc][GoDoc]](https://godoc.org/github.com/goji/httpauth)
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) **star:172** JWT中间件，可用于Golang http服务器，提供了许多配置选项。   [![最近一年没有更新][Yellow]](https://github.com/adam-hanna/jwt-auth)   [![godoc][GoDoc]](https://godoc.org/github.com/adam-hanna/jwt-auth)
* [jwt](https://github.com/pascaldekloe/jwt) **star:157** 轻量级JSON Web令牌库。   [![godoc][GoDoc]](https://godoc.org/github.com/pascaldekloe/jwt)
* [branca](https://github.com/hako/branca) **star:103** 基于 Go 实现Branca令牌。   [![godoc][GoDoc]](https://godoc.org/github.com/hako/branca)
* [session](https://github.com/icza/session) **star:99** web服务器会话管理(包括支持谷歌应用程序引擎 - GAE)。   [![godoc][GoDoc]](https://godoc.org/github.com/icza/session)
* [sessionup](https://github.com/swithek/sessionup) **star:81** 简单但有效的HTTP会话管理和标识包。   [![最近一周有更新][Green]](https://github.com/swithek/sessionup)   [![godoc][GoDoc]](https://godoc.org/github.com/swithek/sessionup)
* [jwt](https://github.com/robbert229/jwt) **star:78** 简单易用的JSON Web令牌实现(JWT)。   [![最近一年没有更新][Yellow]](https://github.com/robbert229/jwt)   [![godoc][GoDoc]](https://godoc.org/github.com/robbert229/jwt)
* [sjwt](https://github.com/brianvoe/sjwt) **star:59** 简单的jwt生成器和解析器。   [![godoc][GoDoc]](https://godoc.org/github.com/brianvoe/sjwt)
* [sessions](https://github.com/adam-hanna/sessions) **star:48** 非常简单，高性能，可深度定制的会话服务，主要用于的 go http 服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/adam-hanna/sessions)
* [rbac](https://github.com/zpatrick/rbac) **star:46** 最小的RBAC包。   [![最近一年没有更新][Yellow]](https://github.com/zpatrick/rbac)   [![godoc][GoDoc]](https://godoc.org/github.com/zpatrick/rbac)
* [securecookie](https://github.com/chmike/securecookie) **star:33** 高效安全的cookie编码/解码。   [![godoc][GoDoc]](https://godoc.org/github.com/chmike/securecookie)
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) **star:8** 使用SessionGate Redis模块进行会话管理。   [![最近一年没有更新][Yellow]](https://github.com/f0rmiga/sessiongate-go)   [![godoc][GoDoc]](https://godoc.org/github.com/f0rmiga/sessiongate-go)
* [signedvalue](https://github.com/sashka/signedvalue) **star:8** 与[Tornado's](https://github.com/tornadooweb/tornado) 完全兼容的签名和时间戳字符串实现。   [![godoc][GoDoc]](https://godoc.org/github.com/sashka/signedvalue)
* [scope](https://github.com/SonicRoshan/scope) **star:4** 在Go中轻松管理OAuth2范围。   [![godoc][GoDoc]](https://godoc.org/github.com/SonicRoshan/scope)
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) **star:2** 提供cookie .txt文件格式的解析器。   [![最近一年没有更新][Yellow]](https://github.com/mengzhuo/cookiestxt)   [![godoc][GoDoc]](https://godoc.org/github.com/mengzhuo/cookiestxt)

## Bot建设

*用于构建和使用机器人的库。 (翻译出错了? 试试 [英文版](README_EN.md#bot-building) 吧~)*

* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) **star:1965** 简单轻量级的Telegram bot客户端。   [![最近一周有更新][Green]](https://github.com/Syfaro/telegram-bot-api)   [![godoc][GoDoc]](https://godoc.org/github.com/Syfaro/telegram-bot-api)
* [telebot](https://github.com/tucnak/telebot) **star:1140** 用Go编写的Telegram bot框架。   [![godoc][GoDoc]](https://godoc.org/github.com/tucnak/telebot)
* [go-chat-bot](https://github.com/go-chat-bot/bot) **star:552** 用 Go 编写的IRC, Slack和电报机器人。   [![godoc][GoDoc]](https://godoc.org/github.com/go-chat-bot/bot)
* [go-joe](https://joe-bot.net)  一个通用的机器人库的灵感来自于Hubot，但写在围棋。
* [slacker](https://github.com/shomali11/slacker) **star:361** 可简单创建Slack机器人的框架。   [![godoc][GoDoc]](https://godoc.org/github.com/shomali11/slacker)
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) **star:288** 基于控制台的，用于加密货币交易所的的交易机器人。   [![最近一年没有更新][Yellow]](https://github.com/saniales/golang-crypto-trading-bot)   [![godoc][GoDoc]](https://godoc.org/github.com/saniales/golang-crypto-trading-bot)
* [Kelp](https://github.com/stellar/kelp) **star:266** 官方交易和做市机器人为[Stellar](https://www.stellar.org/) DEX。开箱即用的作品，用 Golang 编写，兼容集中交易和定制交易策略。   [![最近一周有更新][Green]](https://github.com/stellar/kelp)   [![godoc][GoDoc]](https://godoc.org/github.com/stellar/kelp)
* [tbot](https://github.com/yanzay/tbot) **star:251** 带有类似于net/http API的Telegram bot服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/yanzay/tbot)
* [Tenyks](https://github.com/kyleterry/tenyks) **star:167** 面向服务的IRC bot，使用Redis和JSON进行消息传递。   [![godoc][GoDoc]](https://godoc.org/github.com/kyleterry/tenyks)
* [go-sarah](https://github.com/oklahomer/go-sarah) **star:156** 此框架提供了聊天机器人相关的服务，包括LINE、Slack、Gitter等。   [![godoc][GoDoc]](https://godoc.org/github.com/oklahomer/go-sarah)
* [hanu](https://github.com/sbstjn/hanu) **star:119** 用于编写Slack机器人的框架。   [![godoc][GoDoc]](https://godoc.org/github.com/sbstjn/hanu)
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) **star:94** Libary为twitch编写机器人程序。电视聊天   [![最近一周有更新][Green]](https://github.com/gempir/go-twitch-irc)   [![godoc][GoDoc]](https://godoc.org/github.com/gempir/go-twitch-irc)
* [go-tgbot](https://github.com/olebedev/go-tgbot) **star:91** 由swagger文件、基于会话的路由器和中间件生成的纯Golang Telegram Bot API包装器。   [![最近一年没有更新][Yellow]](https://github.com/olebedev/go-tgbot)   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/go-tgbot)
* [margelet](https://github.com/zhulik/margelet) **star:60** 构建电报机器人的框架。   [![最近一年没有更新][Yellow]](https://github.com/zhulik/margelet)   [![godoc][GoDoc]](https://godoc.org/github.com/zhulik/margelet)
* [govkbot](https://github.com/nikepan/govkbot) **star:30** 简单的Go [VK](https://vk.com) bot库。   [![最近一周有更新][Green]](https://github.com/nikepan/govkbot)   [![godoc][GoDoc]](https://godoc.org/github.com/nikepan/govkbot)
* [slackscot](https://github.com/alexandre-normand/slackscot) **star:25** 另一个构建Slack机器人的框架。   [![godoc][GoDoc]](https://godoc.org/github.com/alexandre-normand/slackscot)
* [micha](https://github.com/onrik/micha) **star:12** 基于 GO 实现的Telegram 机器人API库。   [![godoc][GoDoc]](https://godoc.org/github.com/onrik/micha)

## 命令行

### 标准CLI

*用于构建标准或基本命令行应用程序的库。 (翻译出错了? 试试 [英文版](README_EN.md#standard-cli) 吧~)*

* [cobra](https://github.com/spf13/cobra) **star:16025** 现代Go CLI命令行交互工具。   [![star > 2000][Awesome]](https://github.com/spf13/cobra)   [![最近一周有更新][Green]](https://github.com/spf13/cobra)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/cobra)
* [urfave/cli](https://github.com/urfave/cli) **star:13242** 可让你简单、快速和愉快的构建命令行应用(之前是codegangsta/cli)。   [![star > 2000][Awesome]](https://github.com/urfave/cli)   [![最近一周有更新][Green]](https://github.com/urfave/cli)   [![godoc][GoDoc]](https://godoc.org/github.com/urfave/cli)
* [kingpin](https://github.com/alecthomas/kingpin) **star:2815** 支持子命令的命令行和标志解析器。   [![star > 2000][Awesome]](https://github.com/alecthomas/kingpin)   [![godoc][GoDoc]](https://godoc.org/github.com/alecthomas/kingpin)
* [go-flags](https://github.com/jessevdk/go-flags) **star:1646**  Go 命令行选项解析器。   [![godoc][GoDoc]](https://godoc.org/github.com/jessevdk/go-flags)
* [Dnote](https://github.com/dnote/dnote) **star:1517** 一个简单的命令行笔记本与多设备同步。   [![最近一周有更新][Green]](https://github.com/dnote/dnote)   [![godoc][GoDoc]](https://godoc.org/github.com/dnote/dnote)
* [readline](https://github.com/chzyer/readline) **star:1468** 纯golang实现，在MIT许可下提供了GNU-Readline的大部分特性。   [![godoc][GoDoc]](https://godoc.org/github.com/chzyer/readline)
* [docopt.go](https://github.com/docopt/docopt.go) **star:1226** 会让你满意的命令行参数解析器。   [![godoc][GoDoc]](https://godoc.org/github.com/docopt/docopt.go)
* [mitchellh/cli](https://github.com/mitchellh/cli) **star:1098** 用于实现命令行接口的Go库。   [![godoc][GoDoc]](https://godoc.org/github.com/mitchellh/cli)
* [pflag](https://github.com/spf13/pflag) **star:1014** 基于POSIX/GNU-style --flags实现的包，主要用于替换Go的falg包。   [![最近一周有更新][Green]](https://github.com/spf13/pflag)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/pflag)
* [cli-init](https://github.com/tcnksm/gcli) **star:894** 一个简单就可开启构建Golang命令行的应用程序。   [![最近一年没有更新][Yellow]](https://github.com/tcnksm/gcli)   [![godoc][GoDoc]](https://godoc.org/github.com/tcnksm/gcli)
* [climax](http://github.com/tucnak/climax)  Alternative CLI with "human face", in spirit of Go command.
* [go-arg](https://github.com/alexflint/go-arg) **star:844** 基于结构的参数解析。   [![godoc][GoDoc]](https://godoc.org/github.com/alexflint/go-arg)
* [complete](https://github.com/posener/complete) **star:669** 使用 Go 语言编写的 bash 命令补全工具以及 Go 命令补全工具.   [![godoc][GoDoc]](https://godoc.org/github.com/posener/complete)
* [liner](https://github.com/peterh/liner) **star:662** 类似readline-like的命令行接口库。   [![godoc][GoDoc]](https://godoc.org/github.com/peterh/liner)
* [mow.cli](https://github.com/jawher/mow.cli) **star:657** 用于构建具有复杂标志和参数解析和验证的CLI应用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/jawher/mow.cli)
* [flaggy](https://github.com/integrii/flaggy) **star:631** 一个健壮的、易用的标志包，具有出色的子命令支持。   [![最近一周有更新][Green]](https://github.com/integrii/flaggy)   [![godoc][GoDoc]](https://godoc.org/github.com/integrii/flaggy)
* [cli](https://github.com/mkideal/cli) **star:516** 基于golang结构标签，功能丰富易于使用的命令行包。   [![godoc][GoDoc]](https://godoc.org/github.com/mkideal/cli)
* [ops](https://github.com/nanovms/ops) **star:386** Unikernel 构建器/协调器。   [![最近一周有更新][Green]](https://github.com/nanovms/ops)   [![godoc][GoDoc]](https://godoc.org/github.com/nanovms/ops)
* [argparse](https://github.com/akamensky/argparse) **star:174** 命令行参数分析器，灵感来自Python的argparse模块。   [![最近一周有更新][Green]](https://github.com/akamensky/argparse)   [![godoc][GoDoc]](https://godoc.org/github.com/akamensky/argparse)
* [commandeer](https://github.com/jaffee/commandeer) **star:107** 开发友好的CLI应用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/jaffee/commandeer)
* [sflags](https://github.com/octago/sflags) **star:105** 基于结构的flag生成器，用于flag、urfave/cli、pflag、cobra、kingpin和其他库。   [![godoc][GoDoc]](https://godoc.org/github.com/octago/sflags)
* [flag](https://github.com/cosiner/flag) **star:103** 简单但功能强大的命令行选项解析库，用于支持Go子命令。   [![最近一年没有更新][Yellow]](https://github.com/cosiner/flag)   [![godoc][GoDoc]](https://godoc.org/github.com/cosiner/flag)
* [wmenu](https://github.com/dixonwille/wmenu) **star:102** 为cli程序提供了简单上手的菜单，可提示用户作出选择。   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/wmenu)
* [ukautz/clif](https://github.com/ukautz/clif) **star:101** 简小的命令行接口框架。   [![最近一年没有更新][Yellow]](https://github.com/ukautz/clif)   [![godoc][GoDoc]](https://godoc.org/github.com/ukautz/clif)
* [job](https://github.com/liujianping/job) **star:70** 工作，把你的短期指令当作长期任务。   [![godoc][GoDoc]](https://godoc.org/github.com/liujianping/job)
* [cli](https://github.com/teris-io/cli) **star:64** 为 Go 构建命令接口提供简单而完整的API。   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/cli)
* [1build](https://github.com/gopinath-langote/1build) **star:53** 命令行工具，以无摩擦地管理项目特定的命令。   [![godoc][GoDoc]](https://godoc.org/github.com/gopinath-langote/1build)
* [env](https://github.com/codingconcepts/env) **star:48** 基于标记的结构化的环境配置。   [![godoc][GoDoc]](https://godoc.org/github.com/codingconcepts/env)
* [wlog](https://github.com/dixonwille/wlog) **star:42** 支持跨平台和并发的简单日志记录接口。   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/wlog)
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli)  具有自动配置和依赖注入的cli应用程序框架。
* [gocmd](https://github.com/devfacet/gocmd) **star:37** 用于构建命令行应用程序。   [![最近一年没有更新][Yellow]](https://github.com/devfacet/gocmd)   [![godoc][GoDoc]](https://godoc.org/github.com/devfacet/gocmd)
* [strumt](https://github.com/antham/strumt) **star:34** 用于创建提示链。   [![godoc][GoDoc]](https://godoc.org/github.com/antham/strumt)
* [flagvar](https://github.com/sgreben/flagvar) **star:33** 符合 Go 标准的“flag”标志参数类型包。   [![godoc][GoDoc]](https://godoc.org/github.com/sgreben/flagvar)
* [cmdr](https://github.com/hedzr/cmdr) **star:30** 一个POSIX/GNU风格的、类似getopt的命令行UI Go库。   [![最近一周有更新][Green]](https://github.com/hedzr/cmdr)   [![godoc][GoDoc]](https://godoc.org/github.com/hedzr/cmdr)
* [clîr](https://github.com/leaanthony/clir) **star:21** 一个简单而清晰的CLI库。依赖免费的。   [![godoc][GoDoc]](https://godoc.org/github.com/leaanthony/clir)
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) **star:19**  Go 选择解析器，借鉴于Perl灵活性的GetOpt::Long。   [![godoc][GoDoc]](https://godoc.org/github.com/DavidGamba/go-getoptions)
* [argv](https://github.com/cosiner/argv) **star:19** 基于Base 语法，用于分隔命令行字符串并将其作为参数的 Go 语言库，   [![godoc][GoDoc]](https://godoc.org/github.com/cosiner/argv)
* [go-commander](https://github.com/yitsushi/go-commander) **star:15** 用于简化CLI工作流的 Go 库。   [![godoc][GoDoc]](https://godoc.org/github.com/yitsushi/go-commander)
* [sand](https://github.com/Zaba505/sand) **star:9** 用于创建解释器等的简单API。   [![最近一年没有更新][Yellow]](https://github.com/Zaba505/sand)   [![godoc][GoDoc]](https://godoc.org/github.com/Zaba505/sand)
* [ts](https://github.com/liujianping/ts) **star:8** 时间戳转换和比较工具。   [![godoc][GoDoc]](https://godoc.org/github.com/liujianping/ts)
* [cmd](https://github.com/posener/cmd) **star:5** 扩展标准的' flag '包，以支持子命令和更多的idomatic方式。   [![最近一周有更新][Green]](https://github.com/posener/cmd)   [![godoc][GoDoc]](https://godoc.org/github.com/posener/cmd)

### 高级控制台用户界面

*用于构建控制台应用程序和控制台用户界面的库。 (翻译出错了? 试试 [英文版](README_EN.md#advanced-console-uis) 吧~)*

* [termui](https://github.com/gizak/termui) **star:9586** 此库是基于**termbox-go**实现的，借鉴于[blessed-contrib](https://github.com/yaronn/blessed-contrib)。   [![star > 2000][Awesome]](https://github.com/gizak/termui)   [![godoc][GoDoc]](https://godoc.org/github.com/gizak/termui)
* [gommon/color](https://github.com/labstack/gommon/tree/master/color)  更换终端文本样式。
* [gocui](https://github.com/jroimartin/gocui) **star:6022** 旨在创建控制台用户界面的极简Go库。   [![star > 2000][Awesome]](https://github.com/jroimartin/gocui)   [![godoc][GoDoc]](https://godoc.org/github.com/jroimartin/gocui)
* [termbox-go](https://github.com/nsf/termbox-go) **star:3697** 基于文本的跨平台接口库。   [![star > 2000][Awesome]](https://github.com/nsf/termbox-go)   [![godoc][GoDoc]](https://godoc.org/github.com/nsf/termbox-go)
* [go-prompt](https://github.com/c-bata/go-prompt) **star:2862** 构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)   [![star > 2000][Awesome]](https://github.com/c-bata/go-prompt)   [![最近一周有更新][Green]](https://github.com/c-bata/go-prompt)   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/go-prompt)
* [uiprogress](https://github.com/gosuri/uiprogress) **star:1643** 在终端呈现进度条，可灵活配置的。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uiprogress)
* [asciigraph](https://github.com/guptarohit/asciigraph) **star:1310** 在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。   [![godoc][GoDoc]](https://godoc.org/github.com/guptarohit/asciigraph)
* [uilive](https://github.com/gosuri/uilive) **star:1104** 用于实时更新终端输出的库。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uilive)
* [termdash](https://github.com/mum4k/termdash) **star:955** 此库是基于**termbox-go**实现的，借鉴于[termui](https://github.com/gizak/termui)。   [![最近一周有更新][Green]](https://github.com/mum4k/termdash)   [![godoc][GoDoc]](https://godoc.org/github.com/mum4k/termdash)
* [progressbar](https://github.com/schollz/progressbar) **star:864** 基本线程安全的进度条，在每个操作系统工作。   [![godoc][GoDoc]](https://godoc.org/github.com/schollz/progressbar)
* [mpb](https://github.com/vbauerster/mpb) **star:846** 可在终端显示多进度条。   [![最近一周有更新][Green]](https://github.com/vbauerster/mpb)   [![godoc][GoDoc]](https://godoc.org/github.com/vbauerster/mpb)
* [aurora](https://github.com/logrusorgru/aurora) **star:785** 支持fmt.Printf/Sprintf的ANSI终端颜色。   [![godoc][GoDoc]](https://godoc.org/github.com/logrusorgru/aurora)
* [uitable](https://github.com/gosuri/uitable) **star:546** 改善终端应用程序中表格数据的可读性。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uitable)
* [go-colorable](https://github.com/mattn/go-colorable) **star:418** 适用于windows的颜色编写器。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-colorable)
* [go-isatty](https://github.com/mattn/go-isatty) **star:406** Go 实现的 isatty。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-isatty)
* [chalk](https://github.com/ttacon/chalk) **star:330** 美化终端/控制台输出。   [![godoc][GoDoc]](https://godoc.org/github.com/ttacon/chalk)
* [gookit/color](https://github.com/gookit/color) **star:323** 终端显色工具库，支持16种颜色，256种颜色，RGB显色输出，兼容Windows。   [![最近一周有更新][Green]](https://github.com/gookit/color)   [![godoc][GoDoc]](https://godoc.org/github.com/gookit/color)   [![包含中文文档][CN]](https://github.com/gookit/color)
* [tabby](https://github.com/cheynewallace/tabby) **star:263** 一个可在终端生成一个极简Golang表格轻量级库   [![godoc][GoDoc]](https://godoc.org/github.com/cheynewallace/tabby)
* [simpletable](https://github.com/alexeyco/simpletable) **star:213** 可在终端显示简易表格。   [![godoc][GoDoc]](https://godoc.org/github.com/alexeyco/simpletable)
* [go-colortext](https://github.com/daviddengcn/go-colortext) **star:201** 在终端中使用彩色文字。   [![最近一年没有更新][Yellow]](https://github.com/daviddengcn/go-colortext)   [![godoc][GoDoc]](https://godoc.org/github.com/daviddengcn/go-colortext)
* [cfmt](https://github.com/mingrammer/cfmt) **star:72** 提供上下文的fmt，灵感来自于bootstrap color classes。   [![最近一年没有更新][Yellow]](https://github.com/mingrammer/cfmt)   [![godoc][GoDoc]](https://godoc.org/github.com/mingrammer/cfmt)
* [tabular](https://github.com/InVisionApp/tabular) **star:36** 不需要向API传递大量参数就可从命令行实用程序中打印ASCII表。   [![最近一年没有更新][Yellow]](https://github.com/InVisionApp/tabular)   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/tabular)
* [ctc](https://github.com/wzshiming/ctc) **star:17** 不需要Print方法的非侵入性跨平台终端颜色库。   [![godoc][GoDoc]](https://godoc.org/github.com/wzshiming/ctc)   [![包含中文文档][CN]](https://github.com/wzshiming/ctc)
* [colourize](https://github.com/TreyBastian/colourize) **star:17** 在终端提供ANSI彩色文本。   [![最近一年没有更新][Yellow]](https://github.com/TreyBastian/colourize)   [![godoc][GoDoc]](https://godoc.org/github.com/TreyBastian/colourize)
* [go-ataman](https://github.com/workanator/go-ataman) **star:8** 在终端提供ANSI彩色文本模板。   [![最近一年没有更新][Yellow]](https://github.com/workanator/go-ataman)   [![godoc][GoDoc]](https://godoc.org/github.com/workanator/go-ataman)

## 配置

*配置解析的库。 (翻译出错了? 试试 [英文版](README_EN.md#configuration) 吧~)*

* [viper](https://github.com/spf13/viper) **star:11388** 配置管理。   [![star > 2000][Awesome]](https://github.com/spf13/viper)   [![最近一周有更新][Green]](https://github.com/spf13/viper)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/viper)
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) **star:2812** 管理来自环境变量的配置数据。   [![star > 2000][Awesome]](https://github.com/kelseyhightower/envconfig)   [![godoc][GoDoc]](https://godoc.org/github.com/kelseyhightower/envconfig)
* [godotenv](https://github.com/joho/godotenv) **star:2654** Ruby 的 dotenv 库的 Go移植版(从.env文件加载环境变量)。   [![star > 2000][Awesome]](https://github.com/joho/godotenv)   [![godoc][GoDoc]](https://godoc.org/github.com/joho/godotenv)
* [ini](https://github.com/go-ini/ini) **star:1943**  读和写INI文件。   [![最近一周有更新][Green]](https://github.com/go-ini/ini)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ini/ini)
* [env](https://github.com/caarlos0/env) **star:1440** 解析环境变量并赋值到struct中(默认值)。   [![godoc][GoDoc]](https://godoc.org/github.com/caarlos0/env)
* [konfig](https://github.com/lalamove/konfig) **star:547** 可组合、可观察和高性能的分布式配置管理。   [![godoc][GoDoc]](https://godoc.org/github.com/lalamove/konfig)
* [confita](https://github.com/heetch/confita) **star:295** 从多个后端级联加载配置到struct中。   [![godoc][GoDoc]](https://godoc.org/github.com/heetch/confita)
* [store](https://github.com/tucnak/store) **star:248** 轻量级配置管理器。   [![最近一年没有更新][Yellow]](https://github.com/tucnak/store)   [![godoc][GoDoc]](https://godoc.org/github.com/tucnak/store)
* [config](https://github.com/JeremyLoy/config) **star:228** 云本地应用程序配置。将ENV绑定到结构体仅需两行代码。   [![最近一周有更新][Green]](https://github.com/JeremyLoy/config)   [![godoc][GoDoc]](https://godoc.org/github.com/JeremyLoy/config)
* [config](https://github.com/olebedev/config) **star:225** 带有环境变量和标记解析的JSON或YAML配置包装器。   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/config)
* [joshbetz/config](https://github.com/joshbetz/config) **star:198** 一个可解析环境变量、JSON文件小巧的配置库，在SIGHUP时会自动重新加载。   [![godoc][GoDoc]](https://godoc.org/github.com/joshbetz/config)
* [hjson](https://github.com/hjson/hjson-go) **star:194** 更加人性化的JSON配置。轻松的语法，更少的错误，更多的注释。   [![godoc][GoDoc]](https://godoc.org/github.com/hjson/hjson-go)
* [envconfig](https://github.com/vrischmann/envconfig) **star:172** 从环境变量中读取配置。   [![godoc][GoDoc]](https://godoc.org/github.com/vrischmann/envconfig)
* [koanf](https://github.com/knadh/koanf) **star:170** 轻量级可扩展库，用于读取Go应用程序中的配置。内置支持JSON, TOML, YAML, env，命令行。   [![godoc][GoDoc]](https://godoc.org/github.com/knadh/koanf)
* [gookit/config](https://github.com/gookit/config) **star:138** 程序配置管理(load,get,set)。支持JSON, YAML, TOML, INI, HCL。支持多文件加载，数据覆盖合并。   [![godoc][GoDoc]](https://godoc.org/github.com/gookit/config)   [![包含中文文档][CN]](https://github.com/gookit/config)
* [gcfg](https://github.com/go-gcfg/gcfg) **star:127** 将ini的配置文件读入 Go structs中;支持用户定义的类型和子选项。   [![godoc][GoDoc]](https://godoc.org/github.com/go-gcfg/gcfg)
* [goConfig](https://github.com/crgimenes/goConfig) **star:124** 将结构体解析为输入，并用来自命令行、环境变量和配置文件的参数填充该结构体的字段。   [![godoc][GoDoc]](https://godoc.org/github.com/crgimenes/goConfig)
* [envh](https://github.com/antham/envh) **star:94** 协助管理环境变量的Helpers。   [![godoc][GoDoc]](https://godoc.org/github.com/antham/envh)
* [envcfg](https://github.com/tomazk/envcfg) **star:91** 对环境变量进行解析，并赋值到struct。   [![最近一年没有更新][Yellow]](https://github.com/tomazk/envcfg)   [![godoc][GoDoc]](https://godoc.org/github.com/tomazk/envcfg)
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf)  模块化的JSON配置。保持配置结构及其配置的代码，并将解析委托给子模块，而不牺牲配置的完整序列化。
* [gofigure](https://github.com/ian-kent/gofigure) **star:58** 让程序配置变得简单。   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/gofigure)
* [configure](https://github.com/paked/configure) **star:54** 通过多个源提供配置，包括JSON、flags和环境变量。   [![最近一年没有更新][Yellow]](https://github.com/paked/configure)   [![godoc][GoDoc]](https://godoc.org/github.com/paked/configure)
* [cleanenv](https://github.com/ilyakaznacheev/cleanenv) **star:52** 简约的配置阅读器(来自文件、环境，以及你想要的任何地方)。   [![godoc][GoDoc]](https://godoc.org/github.com/ilyakaznacheev/cleanenv)
* [harvester](https://github.com/beatlabs/harvester) **star:51** 一个易于使用的静态和动态配置包   [![godoc][GoDoc]](https://godoc.org/github.com/beatlabs/harvester)
* [config](https://github.com/golobby/config) **star:50** 一个轻量级但功能强大的配置包，用于Go项目。   [![godoc][GoDoc]](https://godoc.org/github.com/golobby/config)
* [xdg](https://github.com/OpenPeeDeeP/xdg) **star:48** 遵循[XDG标准](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html)的跨平台包。   [![godoc][GoDoc]](https://godoc.org/github.com/OpenPeeDeeP/xdg)
* [ingo](https://github.com/schachmat/ingo) **star:28** flag保存在类ini的配置文件中。   [![最近一年没有更新][Yellow]](https://github.com/schachmat/ingo)   [![godoc][GoDoc]](https://godoc.org/github.com/schachmat/ingo)
* [go-up](https://github.com/ufoscout/go-up) **star:26** 一个简单的配置库，具有递归占位符解析功能。   [![godoc][GoDoc]](https://godoc.org/github.com/ufoscout/go-up)
* [mini](https://github.com/sasbury/mini) **star:21** 用于解析ini类型的配置文件。   [![最近一年没有更新][Yellow]](https://github.com/sasbury/mini)   [![godoc][GoDoc]](https://godoc.org/github.com/sasbury/mini)
* [conflate](https://github.com/the4thamigo-uk/conflate) **star:13** 合并来自任意url的多个JSON/YAML/TOML文件、针对JSON模式的验证以及模式中定义的默认值的应用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/the4thamigo-uk/conflate)
* [genv](https://github.com/sakirsensoy/genv) **star:9** 使用dotenv支持轻松读取环境变量。   [![godoc][GoDoc]](https://godoc.org/github.com/sakirsensoy/genv)
* [envconf](https://github.com/ian-kent/envconf) **star:9** 从环境配置中读取配置。   [![最近一年没有更新][Yellow]](https://github.com/ian-kent/envconf)   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/envconf)
* [sprbox](https://github.com/oblq/sprbox) **star:5** 支持构建环境的工具箱工厂和其他不确定的配置解析器(如YAML、TOML、JSON和环境vars)。   [![godoc][GoDoc]](https://godoc.org/github.com/oblq/sprbox)
* [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) **star:3** 从AWS SSM(参数存储)加载配置参数的Go实用程序。   [![godoc][GoDoc]](https://godoc.org/github.com/ianlopshire/go-ssm-config)
* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) **star:2** 读取环境变量的简单有用的包。   [![godoc][GoDoc]](https://godoc.org/github.com/nasermirzaei89/env)
* [onion](http://github.com/goraz/onion)  基于层配置的Go，支持JSON, TOML, YAML，属性，etcd, env，和加密使用PGP。

## 持续集成

*用于帮助进行持续集成的工具。 (翻译出错了? 试试 [英文版](README_EN.md#continuous-integration) 吧~)*

* [drone](https://github.com/drone/drone) **star:20620** Drone 是一个基于 Docker 的持续集成平台，用 Go 编写。   [![star > 2000][Awesome]](https://github.com/drone/drone)   [![godoc][GoDoc]](https://godoc.org/github.com/drone/drone)
* [CDS](https://github.com/ovh/cds) **star:2711** 企业级CI/CD和DevOps自动化开源平台。   [![star > 2000][Awesome]](https://github.com/ovh/cds)   [![最近一周有更新][Green]](https://github.com/ovh/cds)   [![godoc][GoDoc]](https://godoc.org/github.com/ovh/cds)
* [goveralls](https://github.com/mattn/goveralls) **star:633** Coveralls.io 是一个用 Go 编写，可持续对代码覆盖率进行检测的系统。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/goveralls)
* [overalls](https://github.com/go-playground/overalls) **star:100** 针对多package 的 Go 语言项目，可为类似 goveralls 这样的工具生成覆盖率报告。   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/overalls)
* [duci](https://github.com/duck8823/duci) **star:53** 一个简单的 ci 服务。   [![godoc][GoDoc]](https://godoc.org/github.com/duck8823/duci)
* [gomason](https://github.com/nikogura/gomason) **star:43** 在一个干净的工作区中对你的 Go 二进制文件进行测试、构建、签名和发布。   [![最近一周有更新][Green]](https://github.com/nikogura/gomason)   [![godoc][GoDoc]](https://godoc.org/github.com/nikogura/gomason)
* [roveralls](https://github.com/LawrenceWoodman/roveralls) **star:12** 递归覆盖测试工具。   [![最近一年没有更新][Yellow]](https://github.com/LawrenceWoodman/roveralls)   [![godoc][GoDoc]](https://godoc.org/github.com/LawrenceWoodman/roveralls)

## CSS预处理器

*用于预处理CSS文件的库。 (翻译出错了? 试试 [英文版](README_EN.md#css-preprocessors) 吧~)*

* [gcss](https://github.com/yosssi/gcss) **star:431** 纯Go编写的 CSS 预处理器。   [![最近一年没有更新][Yellow]](https://github.com/yosssi/gcss)   [![godoc][GoDoc]](https://godoc.org/github.com/yosssi/gcss)
* [go-libsass](https://github.com/wellington/go-libsass) **star:155**  采用 Go封装，100% 与 Sass 兼容的 libsass 项目。   [![最近一年没有更新][Yellow]](https://github.com/wellington/go-libsass)

## 数据结构

*用 Go 实现的通用的数据结构和算法。 (翻译出错了? 试试 [英文版](README_EN.md#data-structures) 吧~)*

* [gods](https://github.com/emirpasic/gods) **star:7878** 数据结构。容器、集合、列表、堆栈、地图、BidiMaps、树、HashSet等。   [![star > 2000][Awesome]](https://github.com/emirpasic/gods)   [![godoc][GoDoc]](https://godoc.org/github.com/emirpasic/gods)
* [go-datastructures](https://github.com/Workiva/go-datastructures) **star:5464** 可靠的、高性能的和线程安全的数据结构的集合。   [![star > 2000][Awesome]](https://github.com/Workiva/go-datastructures)   [![最近一周有更新][Green]](https://github.com/Workiva/go-datastructures)   [![godoc][GoDoc]](https://godoc.org/github.com/Workiva/go-datastructures)
* [golang-set](https://github.com/deckarep/golang-set) **star:1413** 线程安全和非线程安全的高性能集。   [![godoc][GoDoc]](https://godoc.org/github.com/deckarep/golang-set)
* [boomfilters](https://github.com/tylertreat/BoomFilters) **star:1235** 用于处理连续的概率数据结构。   [![最近一年没有更新][Yellow]](https://github.com/tylertreat/BoomFilters)   [![godoc][GoDoc]](https://godoc.org/github.com/tylertreat/BoomFilters)
* [gota](https://github.com/kniren/gota) **star:1100** 实现了数据帧，序列以及数据噪音。   [![godoc][GoDoc]](https://godoc.org/github.com/kniren/gota)
* [roaring](https://github.com/RoaringBitmap/roaring) **star:792** 实现了压缩 bitsets 的Go包。   [![godoc][GoDoc]](https://godoc.org/github.com/RoaringBitmap/roaring)
* [willf/bloom](https://github.com/willf/bloom) **star:756** 实现Bloom过滤器。   [![godoc][GoDoc]](https://godoc.org/github.com/willf/bloom)
* [hyperloglog](https://github.com/axiomhq/hyperloglog) **star:691** HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.   [![godoc][GoDoc]](https://godoc.org/github.com/axiomhq/hyperloglog)
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) **star:589** 布谷鸟过滤器:一个用Go实现，可替代计数 bloom 过滤器。   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/cuckoofilter)
* [bitset](https://github.com/willf/bitset) **star:539** 实现了 bitsets 的 Go 包。   [![godoc][GoDoc]](https://godoc.org/github.com/willf/bitset)
* [trie](https://github.com/derekparker/trie) **star:461** 在Go中实现Trie。   [![godoc][GoDoc]](https://godoc.org/github.com/derekparker/trie)
* [gocache](https://github.com/eko/gocache) **star:370** 一个完整的Go缓存库，具有多个存储(内存，memcache, redis，…)，可链，可加载，指标缓存和更多。   [![最近一周有更新][Green]](https://github.com/eko/gocache)   [![godoc][GoDoc]](https://godoc.org/github.com/eko/gocache)
* [algorithms](https://github.com/shady831213/algorithms) **star:361** 算法和数据结构。来源于CLRS。   [![godoc][GoDoc]](https://godoc.org/github.com/shady831213/algorithms)
* [go-geoindex](https://github.com/hailocab/go-geoindex) **star:320** 基于内存的地理索引。   [![最近一年没有更新][Yellow]](https://github.com/hailocab/go-geoindex)   [![godoc][GoDoc]](https://godoc.org/github.com/hailocab/go-geoindex)
* [mafsa](https://github.com/smartystreets/mafsa) **star:281** 实现了 MA-FSA ，包含最小完美哈希。   [![godoc][GoDoc]](https://godoc.org/github.com/smartystreets/mafsa)   [![归档项目][Archived]](https://github.com/smartystreets/mafsa)
* [goskiplist](https://github.com/ryszard/goskiplist) **star:217** 基于 Go 的跳表实现。   [![godoc][GoDoc]](https://godoc.org/github.com/ryszard/goskiplist)
* [hilbert](https://github.com/google/hilbert) **star:196** 用于映射空间填充曲线（例如 Hilbert 曲线和 Peano 曲线）和数值。   [![最近一年没有更新][Yellow]](https://github.com/google/hilbert)   [![godoc][GoDoc]](https://godoc.org/github.com/google/hilbert)
* [merkletree](https://github.com/cbergoon/merkletree) **star:181** 实现了merkle树，提供了对数据结构内容的有效和安全的验证。   [![godoc][GoDoc]](https://godoc.org/github.com/cbergoon/merkletree)
* [binpacker](https://github.com/zhuangsirui/binpacker) **star:135** 帮助用户构建自定义二进制流的二进制封装器和解包器   [![最近一年没有更新][Yellow]](https://github.com/zhuangsirui/binpacker)   [![godoc][GoDoc]](https://godoc.org/github.com/zhuangsirui/binpacker)
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) **star:132** 自适应基数树。   [![godoc][GoDoc]](https://godoc.org/github.com/plar/go-adaptive-radix-tree)
* [bloom](https://github.com/zhenjl/bloom) **star:131** 在Go中实现了Bloom过滤器。   [![最近一年没有更新][Yellow]](https://github.com/zhenjl/bloom)   [![godoc][GoDoc]](https://godoc.org/github.com/zhenjl/bloom)
* [ttlcache](https://github.com/diegobernardes/ttlcache) **star:129** 基于内存的LRU算法实现。   [![godoc][GoDoc]](https://godoc.org/github.com/diegobernardes/ttlcache)
* [skiplist](https://github.com/MauriceGit/skiplist) **star:117** 高性能的 Go 跳表实现。   [![godoc][GoDoc]](https://godoc.org/github.com/MauriceGit/skiplist)
* [iter](https://github.com/disksing/iter) **star:116** Go实现的c++ STL迭代器和算法。   [![godoc][GoDoc]](https://godoc.org/github.com/disksing/iter)   [![包含中文文档][CN]](https://github.com/disksing/iter)
* [deque](https://github.com/gammazero/deque) **star:106** 快速环缓冲区deque(双端队列)。   [![godoc][GoDoc]](https://godoc.org/github.com/gammazero/deque)
* [ring](https://github.com/TheTannerRyan/ring) **star:105** 高性能、线程安全的bloom过滤器。   [![godoc][GoDoc]](https://godoc.org/github.com/TheTannerRyan/ring)
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) **star:101** 区域四叉树具有高效的点定位和邻域查找功能。   [![最近一年没有更新][Yellow]](https://github.com/aurelien-rainone/go-rquad)   [![godoc][GoDoc]](https://godoc.org/github.com/aurelien-rainone/go-rquad)
* [encoding](https://github.com/zhenjl/encoding) **star:99** 整形压缩库。   [![最近一年没有更新][Yellow]](https://github.com/zhenjl/encoding)   [![godoc][GoDoc]](https://godoc.org/github.com/zhenjl/encoding)
* [conjungo](https://github.com/InVisionApp/conjungo) **star:86** 一个小型、强大和灵活的合并库。   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/conjungo)
* [bit](https://github.com/yourbasic/bit) **star:83** Go 语言集合数据结构。提供了额外的位操作功能。   [![最近一年没有更新][Yellow]](https://github.com/yourbasic/bit)   [![godoc][GoDoc]](https://godoc.org/github.com/yourbasic/bit)
* [gostl](https://github.com/liyue201/gostl) **star:76** 用于go的数据结构和算法库，旨在提供类似c++ STL的函数。   [![godoc][GoDoc]](https://godoc.org/github.com/liyue201/gostl)
* [levenshtein](https://github.com/agnivade/levenshtein) **star:72** 实现在Go中计算levenshtein距离。   [![godoc][GoDoc]](https://godoc.org/github.com/agnivade/levenshtein)
* [skiplist](https://github.com/gansidui/skiplist) **star:68** 在Go中实现了跳表。   [![最近一年没有更新][Yellow]](https://github.com/gansidui/skiplist)   [![godoc][GoDoc]](https://godoc.org/github.com/gansidui/skiplist)
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) **star:63** 并行FIFO队列。   [![godoc][GoDoc]](https://godoc.org/github.com/enriquebris/goconcurrentqueue)
* [bloom](https://github.com/yourbasic/bloom) **star:49** Golang Bloom过滤器的实现。   [![最近一年没有更新][Yellow]](https://github.com/yourbasic/bloom)   [![godoc][GoDoc]](https://godoc.org/github.com/yourbasic/bloom)
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) **star:47** 基于内存的实现了高性能的key:value存储库。指针缓存。   [![godoc][GoDoc]](https://godoc.org/github.com/OrlovEvgeny/go-mcache)
* [count-min-log](https://github.com/seiflotfy/count-min-log) **star:46** Go实现Count-Min-log sketch的功能 : 使用近似计数器进行近似计数(类似Count-Min sketch，但使用更少内存)。   [![最近一年没有更新][Yellow]](https://github.com/seiflotfy/count-min-log)   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/count-min-log)
* [levenshtein](https://github.com/agext/levenshtein) **star:39** Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.   [![godoc][GoDoc]](https://godoc.org/github.com/agext/levenshtein)
* [remember-go](https://github.com/rocketlaunchr/remember-go) **star:36** 用于缓存慢速数据库查询的通用接口(支持redis、memcached、ristretto或in-memory)。   [![godoc][GoDoc]](https://godoc.org/github.com/rocketlaunchr/remember-go)
* [concurrent-writer](https://github.com/free/concurrent-writer) **star:27** 具备高并发能力，可替换 bufio.Writer。   [![最近一年没有更新][Yellow]](https://github.com/free/concurrent-writer)   [![godoc][GoDoc]](https://godoc.org/github.com/free/concurrent-writer)
* [crunch](https://github.com/superwhiskers/crunch) **star:23** 打包实现缓冲区，以便轻松处理各种数据类型。   [![godoc][GoDoc]](https://godoc.org/github.com/superwhiskers/crunch)
* [pipeline](https://github.com/hyfather/pipeline) **star:21** 实现了 fan-in 和 fan-out 的管道功能。   [![最近一年没有更新][Yellow]](https://github.com/hyfather/pipeline)   [![godoc][GoDoc]](https://godoc.org/github.com/hyfather/pipeline)
* [goset](https://github.com/zoumo/goset) **star:20** 一个有用的Go集合实现。   [![godoc][GoDoc]](https://godoc.org/github.com/zoumo/goset)
* [deque](https://github.com/edwingeng/deque) **star:15** 高度优化的双端队列。   [![最近一周有更新][Green]](https://github.com/edwingeng/deque)   [![godoc][GoDoc]](https://godoc.org/github.com/edwingeng/deque)
* [typ](https://github.com/gurukami/typ) **star:15** 从复杂结构中获取值，支持空类型、安全的类型转换。   [![godoc][GoDoc]](https://godoc.org/github.com/gurukami/typ)
* [hide](https://github.com/emvi/hide) **star:14** ID type with marshalling to/from hash to prevent sending IDs to clients.   [![最近一年没有更新][Yellow]](https://github.com/emvi/hide)   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/hide)
* [go-ef](https://github.com/amallia/go-ef) **star:11** 实现了 Elias-Fano 编码。   [![最近一年没有更新][Yellow]](https://github.com/amallia/go-ef)   [![godoc][GoDoc]](https://godoc.org/github.com/amallia/go-ef)
* [dict](https://github.com/srfrog/dict) **star:11** 实现类似 python dict的功能(dict)。   [![godoc][GoDoc]](https://godoc.org/github.com/srfrog/dict)
* [mspm](https://github.com/BlackRabbitt/mspm) **star:9** 用于信息检索的多字符串模式匹配算法。   [![最近一年没有更新][Yellow]](https://github.com/BlackRabbitt/mspm)   [![godoc][GoDoc]](https://godoc.org/github.com/BlackRabbitt/mspm)
* [null](https://github.com/emvi/null) **star:9** 对空的 Go 数据类型也可以进行JSON进行解析/反解析。   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/null)
* [set](https://github.com/StudioSol/set) **star:7** 使用LinkedHashMap在Go中实现简单的set数据结构。   [![godoc][GoDoc]](https://godoc.org/github.com/StudioSol/set)
* [ptrie](https://github.com/viant/ptrie) **star:7** 前缀树的一种实现。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/ptrie)
* [treap](https://github.com/perdata/treap) **star:7** 使用树堆进行持久、快速有序的映射。   [![godoc][GoDoc]](https://godoc.org/github.com/perdata/treap)
* [timedmap](https://github.com/zekroTJA/timedmap) **star:6** 实现了有生命周期的键值对Map。   [![godoc][GoDoc]](https://godoc.org/github.com/zekroTJA/timedmap)
* [gofal](https://github.com/xxjwxc/gofal) **star:6** 基于 Go 实现的分数计算。包含分子、分母运算    [![godoc][GoDoc]](https://godoc.org/github.com/xxjwxc/gofal)   [![包含中文文档][CN]](https://github.com/xxjwxc/gofal)
* [parsefields](https://github.com/MonaxGT/parsefields) **star:3** 用于解析类似json的日志的工具，用于收集惟一的字段和事件。   [![godoc][GoDoc]](https://godoc.org/github.com/MonaxGT/parsefields)

## 数据库

*数据库。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [prometheus](https://github.com/prometheus/prometheus) **star:29498** 用于监控系统和时序的数据库。   [![star > 2000][Awesome]](https://github.com/prometheus/prometheus)   [![最近一周有更新][Green]](https://github.com/prometheus/prometheus)   [![godoc][GoDoc]](https://godoc.org/github.com/prometheus/prometheus)
* [tidb](https://github.com/pingcap/tidb) **star:22728** TiDB是一个分布式SQL数据库。灵感来自谷歌F1的设计。   [![star > 2000][Awesome]](https://github.com/pingcap/tidb)   [![最近一周有更新][Green]](https://github.com/pingcap/tidb)   [![godoc][GoDoc]](https://godoc.org/github.com/pingcap/tidb)   [![包含中文文档][CN]](https://github.com/pingcap/tidb)
* [influxdb](https://github.com/influxdb/influxdb) **star:18449** 可伸缩的数据存储，用于指标衡量、事件和实时分析。   [![star > 2000][Awesome]](https://github.com/influxdb/influxdb)   [![最近一周有更新][Green]](https://github.com/influxdb/influxdb)   [![godoc][GoDoc]](https://godoc.org/github.com/influxdb/influxdb)
* [cockroach](https://github.com/cockroachdb/cockroach) **star:17876** 可伸缩、区域备份、事务性数据存储。   [![star > 2000][Awesome]](https://github.com/cockroachdb/cockroach)   [![最近一周有更新][Green]](https://github.com/cockroachdb/cockroach)   [![godoc][GoDoc]](https://godoc.org/github.com/cockroachdb/cockroach)
* [dgraph](https://github.com/dgraph-io/dgraph) **star:12605** 可伸缩、分布式、低延迟、高吞吐量的图形数据库。   [![star > 2000][Awesome]](https://github.com/dgraph-io/dgraph)   [![最近一周有更新][Green]](https://github.com/dgraph-io/dgraph)   [![godoc][GoDoc]](https://godoc.org/github.com/dgraph-io/dgraph)
* [groupcache](https://github.com/golang/groupcache) **star:8410** Groupcache是一个缓存和缓存填充库，在许多情况下，它是memcached的替代品。   [![star > 2000][Awesome]](https://github.com/golang/groupcache)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/groupcache)
* [badger](https://github.com/dgraph-io/badger) **star:7373** 快速 K/V 存储。   [![star > 2000][Awesome]](https://github.com/dgraph-io/badger)   [![最近一周有更新][Green]](https://github.com/dgraph-io/badger)   [![godoc][GoDoc]](https://godoc.org/github.com/dgraph-io/badger)
* [rqlite](https://github.com/rqlite/rqlite) **star:5700** 基于SQLite的轻量级分布式关系数据库。   [![star > 2000][Awesome]](https://github.com/rqlite/rqlite)   [![godoc][GoDoc]](https://godoc.org/github.com/rqlite/rqlite)
* [BigCache](https://github.com/allegro/bigcache) **star:3631** 高效的键/值缓存为千兆字节的数据。   [![star > 2000][Awesome]](https://github.com/allegro/bigcache)   [![godoc][GoDoc]](https://godoc.org/github.com/allegro/bigcache)
* [goleveldb](https://github.com/syndtr/goleveldb) **star:3589** 在Go中实现[LevelDB](https://github.com/google/leveldb) key/value数据库。   [![star > 2000][Awesome]](https://github.com/syndtr/goleveldb)   [![godoc][GoDoc]](https://godoc.org/github.com/syndtr/goleveldb)
* [go-cache](https://github.com/pmylund/go-cache) **star:3542** 基于内存的 K/V 存储/缓存 : (类似于Memcached)，适用于单机应用程序。   [![star > 2000][Awesome]](https://github.com/pmylund/go-cache)   [![godoc][GoDoc]](https://godoc.org/github.com/pmylund/go-cache)
* [ledisdb](https://github.com/siddontang/ledisdb) **star:3237** Ledisdb是一种高性能的NoSQL，类似于基于LevelDB的Redis。   [![star > 2000][Awesome]](https://github.com/siddontang/ledisdb)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/ledisdb)
* [bbolt](https://github.com/etcd-io/bbolt) **star:3024** 一个用于Go的嵌入式键/值数据库。   [![star > 2000][Awesome]](https://github.com/etcd-io/bbolt)   [![最近一周有更新][Green]](https://github.com/etcd-io/bbolt)   [![godoc][GoDoc]](https://godoc.org/github.com/etcd-io/bbolt)
* [buntdb](https://github.com/tidwall/buntdb) **star:2649** 基于内存的K/V，快速，可嵌入的数据库，可自定义索引和空间支持。   [![star > 2000][Awesome]](https://github.com/tidwall/buntdb)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/buntdb)
* [tiedot](https://github.com/HouzuoGuo/tiedot) **star:2460** 属于你的NoSQL数据库。   [![star > 2000][Awesome]](https://github.com/HouzuoGuo/tiedot)   [![godoc][GoDoc]](https://godoc.org/github.com/HouzuoGuo/tiedot)
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) **star:1898** 开源，快速，可伸缩的时间序列数据库。支持PromQL。   [![最近一周有更新][Green]](https://github.com/VictoriaMetrics/VictoriaMetrics)   [![godoc][GoDoc]](https://godoc.org/github.com/VictoriaMetrics/VictoriaMetrics)
* [cache2go](https://github.com/muesli/cache2go) **star:1222** 基于内存的 K/V 缓存，支持超时的自动失效。   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/cache2go)
* [nutsdb](https://github.com/xujiajun/nutsdb) **star:1100** Nutsdb是一个用纯Go编写的简单、快速、可嵌入、持久的键/值存储。它支持完全序列化的事务和许多数据结构，如列表、集合、排序集。   [![最近一周有更新][Green]](https://github.com/xujiajun/nutsdb)   [![godoc][GoDoc]](https://godoc.org/github.com/xujiajun/nutsdb)   [![包含中文文档][CN]](https://github.com/xujiajun/nutsdb)
* [GCache](https://github.com/bluele/gcache) **star:1067** 支持过期缓存、LFU、LRU和ARC的缓存库。   [![godoc][GoDoc]](https://godoc.org/github.com/bluele/gcache)
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) **star:1002** 区块链领域的一个SQL数据库。   [![godoc][GoDoc]](https://godoc.org/github.com/CovenantSQL/CovenantSQL)
* [diskv](https://github.com/peterbourgon/diskv) **star:860** 支持磁盘备份的可持久化 K/V 存储。   [![godoc][GoDoc]](https://godoc.org/github.com/peterbourgon/diskv)
* [moss](https://github.com/couchbase/moss) **star:755** Moss是一个用100% Go编写的简单LSM键值存储引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/moss)
* [fastcache](https://github.com/VictoriaMetrics/fastcache) **star:717** 基于内存的快速线程安全的缓存，可缓存大量的条目。最大限度地减少GC开销。   [![最近一周有更新][Green]](https://github.com/VictoriaMetrics/fastcache)   [![godoc][GoDoc]](https://godoc.org/github.com/VictoriaMetrics/fastcache)
* [eliasdb](https://github.com/krotik/eliasdb) **star:558** 无其他依赖项，支持REST API，短语搜索和sql类似的查询语言的事务图数据库。   [![最近一周有更新][Green]](https://github.com/krotik/eliasdb)   [![godoc][GoDoc]](https://godoc.org/github.com/krotik/eliasdb)
* [levigo](https://github.com/jmhodges/levigo) **star:378** 实现了对LevelDB封装。   [![godoc][GoDoc]](https://godoc.org/github.com/jmhodges/levigo)
* [Bitcask](https://github.com/prologic/bitcask) **star:300** Bitcask是一个可嵌入的、持久的、快速的键值(KV)数据库，使用纯Go编写，具有可预测的读写性能、低延迟和高吞吐量，这得益于Bitcask的磁盘布局(LSM+WAL)。   [![最近一周有更新][Green]](https://github.com/prologic/bitcask)   [![godoc][GoDoc]](https://godoc.org/github.com/prologic/bitcask)
* [pudge](https://github.com/recoilme/pudge) **star:247** 使用Go的标准库编写的快速和简单的键/值存储。   [![godoc][GoDoc]](https://godoc.org/github.com/recoilme/pudge)
* [piladb](https://github.com/fern4lvarez/piladb) **star:173** 基于堆栈数据结构的轻量级RESTful数据库引擎。   [![最近一年没有更新][Yellow]](https://github.com/fern4lvarez/piladb)   [![godoc][GoDoc]](https://godoc.org/github.com/fern4lvarez/piladb)
* [Vasto](https://github.com/chrislusf/vasto) **star:169** 分布式高性能键值存储。可做磁盘备份。最终一致。高可用。能够在不中断服务的情况下增长或收缩。   [![最近一年没有更新][Yellow]](https://github.com/chrislusf/vasto)   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/vasto)
* [Kivik](https://github.com/go-kivik/kivik) **star:155** Kivik为CouchDB、PouchDB和类似的数据库提供了一个通用的Go和GopherJS客户端库。   [![godoc][GoDoc]](https://godoc.org/github.com/go-kivik/kivik)
* [slowpoke](https://github.com/recoilme/slowpoke) **star:93** 具有持久性的键值存储。   [![godoc][GoDoc]](https://godoc.org/github.com/recoilme/slowpoke)
* [Scribble](https://github.com/nanobox-io/golang-scribble) **star:88** 小型平面文件JSON存储。   [![最近一年没有更新][Yellow]](https://github.com/nanobox-io/golang-scribble)   [![godoc][GoDoc]](https://godoc.org/github.com/nanobox-io/golang-scribble)
* [couchcache](https://github.com/codingsince1985/couchcache) **star:47** 由 Couchbase服务 支持的RESTful缓存微服务。   [![godoc][GoDoc]](https://godoc.org/github.com/codingsince1985/couchcache)
* [bcache](https://github.com/iwanbk/bcache) **star:43** 基于内存的最终一致的分布式缓存。   [![godoc][GoDoc]](https://godoc.org/github.com/iwanbk/bcache)
* [cache](https://github.com/akyoto/cache) **star:34** 基于内存的 K/V 存储:带生命周期的值存储，0个依赖项，<100 LoC, 100%覆盖率。   [![godoc][GoDoc]](https://godoc.org/github.com/akyoto/cache)
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) **star:33** BigCache 支持集群和独立且生命周期存储项。   [![最近一年没有更新][Yellow]](https://github.com/oaStuff/clusteredBigCache)   [![godoc][GoDoc]](https://godoc.org/github.com/oaStuff/clusteredBigCache)
* [Databunker](https://github.com/paranoidguy/databunker) **star:32** 个人身份信息(PII)存储服务符合GDPR和CCPA。   [![最近一周有更新][Green]](https://github.com/paranoidguy/databunker)   [![godoc][GoDoc]](https://godoc.org/github.com/paranoidguy/databunker)
* [Coffer](https://github.com/claygod/coffer) **star:20** 支持事务的简单ACID键值数据库。   [![godoc][GoDoc]](https://godoc.org/github.com/claygod/coffer)
* [tempdb](https://github.com/rafaeljesus/tempdb) **star:14** 用于临时数据存放的 K/V 存储。   [![最近一年没有更新][Yellow]](https://github.com/rafaeljesus/tempdb)   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/tempdb)
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) **star:12** 用 Go 对[RocksDB](https://rocksdb.org)实现了封装。   [![最近一年没有更新][Yellow]](https://github.com/kapitan-k/gorocksdb)   [![godoc][GoDoc]](https://godoc.org/github.com/kapitan-k/gorocksdb)
* [tracedb](https://github.com/unit-io/tracedb) **star:7** 快速timeseries数据库物联网，实时消息传递应用程序。使用pubsub通过tcp或websocket访问tracedb，使用github.com/unit-io/trace应用程序。   [![最近一周有更新][Green]](https://github.com/unit-io/tracedb)   [![godoc][GoDoc]](https://godoc.org/github.com/unit-io/tracedb)
* [gostore](https://github.com/twharmon/gostore) **star:3** Gostore是一个简单、持久的嵌入式键值存储引擎，用Go编写。   [![godoc][GoDoc]](https://godoc.org/github.com/twharmon/gostore)

*数据库迁移。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [migrate](https://github.com/golang-migrate/migrate) **star:3795** 基于CLI的数据库迁移库。   [![star > 2000][Awesome]](https://github.com/golang-migrate/migrate)   [![最近一周有更新][Green]](https://github.com/golang-migrate/migrate)   [![godoc][GoDoc]](https://godoc.org/github.com/golang-migrate/migrate)
* [sql-migrate](https://github.com/rubenv/sql-migrate) **star:1629** 数据库迁移工具。允许使用go-bindata将迁移嵌入到应用程序中。   [![godoc][GoDoc]](https://godoc.org/github.com/rubenv/sql-migrate)
* [skeema](https://github.com/skeema/skeema) **star:629** 用于MySQL的纯sql模式管理系统，支持分片和外部在线模式更改工具。   [![最近一周有更新][Green]](https://github.com/skeema/skeema)   [![godoc][GoDoc]](https://godoc.org/github.com/skeema/skeema)
* [soda](https://github.com/gobuffalo/pop/tree/master/soda)  数据库迁移、创建、ORM等。用于MySQL、PostgreSQL和SQLite。
* [gormigrate](https://github.com/go-gormigrate/gormigrate) **star:415** 面向Gorm ORM的数据库 schema 迁移辅助程序。   [![godoc][GoDoc]](https://godoc.org/github.com/go-gormigrate/gormigrate)
* [goose](https://github.com/steinbacher/goose) **star:135** 数据库迁移工具。您可以通过创建增量SQL或Go脚本来管理数据库的升级。   [![最近一年没有更新][Yellow]](https://github.com/steinbacher/goose)   [![godoc][GoDoc]](https://godoc.org/github.com/steinbacher/goose)
* [darwin](https://github.com/GuiaBolso/darwin) **star:99** 用于数据库 schema 升级的库。   [![godoc][GoDoc]](https://godoc.org/github.com/GuiaBolso/darwin)
* [migrator](https://github.com/lopezator/migrator) **star:89** 非常简单的 Go 数据库迁移库。   [![godoc][GoDoc]](https://godoc.org/github.com/lopezator/migrator)
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) **star:45** 用Go -pg/pg编写的迁移包。   [![godoc][GoDoc]](https://godoc.org/github.com/robinjoseph08/go-pg-migrations)
* [gondolier](https://github.com/emvi/gondolier) **star:28** 使用结构修饰的数据库迁移库。   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/gondolier)
* [pravasan](https://github.com/pravasan/pravasan) **star:24** 简易的迁移工具-目前只支持MySQL，但计划很快支持Postgres, SQLite, MongoDB等。   [![最近一年没有更新][Yellow]](https://github.com/pravasan/pravasan)
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) **star:23** 类似 Django fixture，用于 Go 建立内置数据库/sql库。   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/go-fixtures)
* [avro](https://github.com/khezen/avro) **star:11** 发现SQL schemas并将其转换为AVRO schemas。   [![最近一周有更新][Green]](https://github.com/khezen/avro)   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/avro)
* [schema](https://github.com/adlio/schema) **star:4** 库，用于将数据库/sql兼容数据库的模式迁移嵌入到Go二进制文件中。   [![godoc][GoDoc]](https://godoc.org/github.com/adlio/schema)

*数据库工具。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [vitess](https://github.com/youtube/vitess) **star:9642** vitess提供了可以为大规模web服务扩展MySQL数据库提供便利的服务和工具。   [![star > 2000][Awesome]](https://github.com/youtube/vitess)   [![最近一周有更新][Green]](https://github.com/youtube/vitess)   [![godoc][GoDoc]](https://godoc.org/github.com/youtube/vitess)
* [pgweb](https://github.com/sosedoff/pgweb) **star:6300** 基于web的PostgreSQL数据库浏览器。   [![star > 2000][Awesome]](https://github.com/sosedoff/pgweb)   [![godoc][GoDoc]](https://godoc.org/github.com/sosedoff/pgweb)
* [kingshard](https://github.com/flike/kingshard) **star:5031** kingshard 是基于 Golang 的MySQL高性能代理。   [![star > 2000][Awesome]](https://github.com/flike/kingshard)   [![godoc][GoDoc]](https://godoc.org/github.com/flike/kingshard)   [![包含中文文档][CN]](https://github.com/flike/kingshard)
* [orchestrator](https://github.com/github/orchestrator) **star:3407** MySQL复制拓扑管理器和可视化工具。   [![star > 2000][Awesome]](https://github.com/github/orchestrator)   [![最近一周有更新][Green]](https://github.com/github/orchestrator)   [![godoc][GoDoc]](https://godoc.org/github.com/github/orchestrator)
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) **star:2812** 自动将MySQL数据同步到Elasticsearch中。   [![star > 2000][Awesome]](https://github.com/siddontang/go-mysql-elasticsearch)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-mysql-elasticsearch)
* [go-mysql](https://github.com/siddontang/go-mysql) **star:2257**  Go 工具集，用于处理MySQL协议和复制。   [![star > 2000][Awesome]](https://github.com/siddontang/go-mysql)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-mysql)
* [pREST](https://github.com/nuveo/prest) **star:2214** 基于PostgreSQL database的RESTful API服务。   [![star > 2000][Awesome]](https://github.com/nuveo/prest)   [![godoc][GoDoc]](https://godoc.org/github.com/nuveo/prest)
* [chproxy](https://github.com/Vertamedia/chproxy) **star:374** ClickHouse数据库的HTTP代理。   [![godoc][GoDoc]](https://godoc.org/github.com/Vertamedia/chproxy)
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) **star:179** 收集小的 insterts 并向 ClickHouse 服务器发送大请求。   [![最近一周有更新][Green]](https://github.com/nikepan/clickhouse-bulk)   [![godoc][GoDoc]](https://godoc.org/github.com/nikepan/clickhouse-bulk)
* [myreplication](https://github.com/2tvenom/myreplication) **star:156** MySql二进制日志复制监听器。支持基于语句和行的复制。   [![最近一年没有更新][Yellow]](https://github.com/2tvenom/myreplication)   [![godoc][GoDoc]](https://godoc.org/github.com/2tvenom/myreplication)
* [octillery](https://github.com/knocknote/octillery) **star:74** 用于数据库分表(支持每个ORM或原生SQL)。   [![godoc][GoDoc]](https://godoc.org/github.com/knocknote/octillery)
* [dbbench](https://github.com/sj14/dbbench) **star:35** 数据库基准测试工具，支持多个数据库和脚本。   [![最近一周有更新][Green]](https://github.com/sj14/dbbench)   [![godoc][GoDoc]](https://godoc.org/github.com/sj14/dbbench)
* [prep](https://github.com/hexdigest/prep) **star:25** 在不更改代码的情况下使用准备好的SQL语句。   [![最近一年没有更新][Yellow]](https://github.com/hexdigest/prep)   [![godoc][GoDoc]](https://godoc.org/github.com/hexdigest/prep)
* [datagen](https://github.com/codingconcepts/datagen) **star:15** 一个快速的数据生成器，支持多表感知和多行DML。   [![最近一周有更新][Green]](https://github.com/codingconcepts/datagen)   [![godoc][GoDoc]](https://godoc.org/github.com/codingconcepts/datagen)
* [rwdb](https://github.com/andizzle/rwdb) **star:11** rwdb为多个数据库服务器的设置提供读取副本功能。   [![最近一年没有更新][Yellow]](https://github.com/andizzle/rwdb)   [![godoc][GoDoc]](https://godoc.org/github.com/andizzle/rwdb)
* [bucket](https://github.com/PumpkinSeed/bucket) **star:6** 优化的数据结构框架的Couchbase专门针对一个桶的使用。   [![godoc][GoDoc]](https://godoc.org/github.com/PumpkinSeed/bucket)

*SQL查询生成器，用于构建和使用SQL的库。 (翻译出错了? 试试 [英文版](README_EN.md#database) 吧~)*

* [Squirrel](https://github.com/Masterminds/squirrel) **star:2782** 帮助您构建SQL查询的Go库。   [![star > 2000][Awesome]](https://github.com/Masterminds/squirrel)   [![最近一周有更新][Green]](https://github.com/Masterminds/squirrel)   [![godoc][GoDoc]](https://godoc.org/github.com/Masterminds/squirrel)
* [xo](https://github.com/knq/xo) **star:2387** 基于现有的schema定义和自定义查询生成 Go 代码，基于支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server。   [![star > 2000][Awesome]](https://github.com/knq/xo)   [![godoc][GoDoc]](https://godoc.org/github.com/knq/xo)
* [gendry](https://github.com/didi/gendry) **star:952** 非入侵的SQL构建器和强大的数据绑定器。   [![最近一周有更新][Green]](https://github.com/didi/gendry)   [![godoc][GoDoc]](https://godoc.org/github.com/didi/gendry)   [![包含中文文档][CN]](https://github.com/didi/gendry)
* [goqu](https://github.com/doug-martin/goqu) **star:737** 常用的SQL生成器和查询库。   [![godoc][GoDoc]](https://godoc.org/github.com/doug-martin/goqu)
* [Dotsql](https://github.com/gchaincl/dotsql) **star:506** Go library帮助您将sql文件保存在一个地方，并轻松地使用它们。   [![godoc][GoDoc]](https://godoc.org/github.com/gchaincl/dotsql)
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) **star:460** Powerful data retrieval methods as well as DB-agnostic query building capabilities.   [![godoc][GoDoc]](https://godoc.org/github.com/go-ozzo/ozzo-dbx)
* [jet](https://github.com/go-jet/jet) **star:228** 用于在Go中编写类型安全的SQL查询的框架，能够轻松地将数据库查询结果转换为所需的任意对象结构。   [![最近一周有更新][Green]](https://github.com/go-jet/jet)   [![godoc][GoDoc]](https://godoc.org/github.com/go-jet/jet)
* [sqrl](https://github.com/elgris/sqrl) **star:201** SQL查询生成器，从Squirrel fork而来，并再此基础上对性能做了优化。   [![godoc][GoDoc]](https://godoc.org/github.com/elgris/sqrl)
* [Squalus](https://gitlab.com/qosenergy/squalus)  Go SQL中间层，能使得执行查询更加容易。
* [dbq](https://github.com/rocketlaunchr/dbq) **star:96** Zero boilerplate database operations for Go   [![最近一周有更新][Green]](https://github.com/rocketlaunchr/dbq)   [![godoc][GoDoc]](https://godoc.org/github.com/rocketlaunchr/dbq)
* [igor](https://github.com/galeone/igor) **star:81** PostgreSQL的抽象层，支持高级功能和类似gorm的语法。   [![godoc][GoDoc]](https://godoc.org/github.com/galeone/igor)
* [godbal](https://github.com/xujiajun/godbal) **star:50** 数据库抽象层(dbal)。支持SQL builder，轻松获取结果。   [![最近一年没有更新][Yellow]](https://github.com/xujiajun/godbal)   [![godoc][GoDoc]](https://godoc.org/github.com/xujiajun/godbal)
* [sqlf](https://github.com/leporo/sqlf) **star:7** 快速SQL查询生成器。   [![godoc][GoDoc]](https://godoc.org/github.com/leporo/sqlf)
* [qry](https://github.com/HnH/qry) **star:6** 该工具使用原始SQL查询从文件生成常量。   [![godoc][GoDoc]](https://godoc.org/github.com/HnH/qry)
* [mpath](https://github.com/spacetab-io/mpath-go) **star:5** MPTT(修改前序树遍历)包的SQL记录-物化路径实现。   [![godoc][GoDoc]](https://godoc.org/github.com/spacetab-io/mpath-go)
* [ormlite](https://github.com/pupizoid/ormlite)  包含一些类似orm的特性和sqlite数据库的辅助程序的轻量级包

## 数据库驱动程序

*用于连接和操作数据库的库。 (翻译出错了? 试试 [英文版](README_EN.md#database-drivers) 吧~)*

* Relational Databases
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) **star:9083** MySQL驱动程序。   [![star > 2000][Awesome]](https://github.com/go-sql-driver/mysql)   [![godoc][GoDoc]](https://godoc.org/github.com/go-sql-driver/mysql)
    * [pq](https://github.com/lib/pq) **star:5698** 纯 Go 的Postgres驱动。   [![star > 2000][Awesome]](https://github.com/lib/pq)   [![godoc][GoDoc]](https://godoc.org/github.com/lib/pq)
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) **star:3864** SQLite3驱动程序。   [![star > 2000][Awesome]](https://github.com/mattn/go-sqlite3)
    * [pgx](https://github.com/jackc/pgx) **star:2418** PostgreSQL驱动，支持比现有database/sql更多的特性。   [![star > 2000][Awesome]](https://github.com/jackc/pgx)   [![最近一周有更新][Green]](https://github.com/jackc/pgx)   [![godoc][GoDoc]](https://godoc.org/github.com/jackc/pgx)
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) **star:1152** 微软MSSQL驱动程序。   [![godoc][GoDoc]](https://godoc.org/github.com/denisenkom/go-mssqldb)
    * [go-oci8](https://github.com/mattn/go-oci8) **star:444** Oracle 驱动程序。   [![最近一周有更新][Green]](https://github.com/mattn/go-oci8)   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-oci8)
    * [goracle](https://github.com/go-goracle/goracle) **star:280** 基于 ODPI-C 的 Oracle 驱动程序
    * [firebirdsql](https://github.com/nakagami/firebirdsql) **star:119** Firebird RDBMS SQL驱动程序。   [![godoc][GoDoc]](https://godoc.org/github.com/nakagami/firebirdsql)
    * [go-adodb](https://github.com/mattn/go-adodb) **star:102** Microsoft ActiveX对象数据库驱动程序。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-adodb)
    * [gofreetds](https://github.com/minus5/gofreetds) **star:98** 基于[FreeTDS](http://www.freetds.org)封装的微软MSSQL Go 驱动。   [![最近一年没有更新][Yellow]](https://github.com/minus5/gofreetds)   [![godoc][GoDoc]](https://godoc.org/github.com/minus5/gofreetds)
    * [avatica](https://github.com/apache/calcite-avatica-go) **star:46** Apache Avatica/Phoenix SQL驱动程序。   [![godoc][GoDoc]](https://godoc.org/github.com/apache/calcite-avatica-go)
    * [bgc](https://github.com/viant/bgc) **star:13** BigQuery 的数据存储连接。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/bgc)

* NoSQL Databases
    * [redis](https://github.com/go-redis/redis) **star:8181** 基于 Go 的 Redis 客户端。   [![star > 2000][Awesome]](https://github.com/go-redis/redis)   [![最近一周有更新][Green]](https://github.com/go-redis/redis)   [![godoc][GoDoc]](https://godoc.org/github.com/go-redis/redis)
    * [redigo](https://github.com/gomodule/redigo) **star:7041** Redigo 是基于 Go 的Redis 客户端。   [![star > 2000][Awesome]](https://github.com/gomodule/redigo)   [![最近一周有更新][Green]](https://github.com/gomodule/redigo)   [![godoc][GoDoc]](https://godoc.org/github.com/gomodule/redigo)
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) **star:4093** 官方的 MongoDB 驱动。   [![star > 2000][Awesome]](https://github.com/mongodb/mongo-go-driver)   [![最近一周有更新][Green]](https://github.com/mongodb/mongo-go-driver)   [![godoc][GoDoc]](https://godoc.org/github.com/mongodb/mongo-go-driver)
    * [mgo](https://github.com/globalsign/mgo) **star:1754** (已停止维护) MongoDB驱动。   [![godoc][GoDoc]](https://godoc.org/github.com/globalsign/mgo)
    * [gorethink](https://github.com/dancannon/gorethink) **star:1499** RethinkDB 驱动。   [![最近一周有更新][Green]](https://github.com/dancannon/gorethink)   [![godoc][GoDoc]](https://godoc.org/github.com/dancannon/gorethink)
    * [redeo](https://github.com/bsm/redeo) **star:368** 与 redis 协议兼容的 TCP 服务器/服务。   [![godoc][GoDoc]](https://godoc.org/github.com/bsm/redeo)
    * [neoism](https://github.com/jmcvetta/neoism) **star:362** Golang 的 Neo4j 客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/jmcvetta/neoism)
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) **star:315** Aerospike 客户端。   [![最近一周有更新][Green]](https://github.com/aerospike/aerospike-client-go)   [![godoc][GoDoc]](https://godoc.org/github.com/aerospike/aerospike-client-go)
    * [gocb](https://github.com/couchbase/gocb) **star:307** 官方Couchbase Go SDK。   [![最近一周有更新][Green]](https://github.com/couchbase/gocb)   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/gocb)
    * [gocql](http://gocql.github.io)  Apache Cassandra 的 Go 驱动。
    * [go-couchbase](https://github.com/couchbase/go-couchbase) **star:298** Couchbase客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/go-couchbase)
    * [go-rejson](https://github.com/nitishm/go-rejson) **star:116** 实现了基于 Redigo 客户端的redislabs' ReJSON 模块。可简单地将结构体存储为JSON对象并对其进行操作。   [![godoc][GoDoc]](https://godoc.org/github.com/nitishm/go-rejson)
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) **star:74** Neo4j REST 客户端。   [![最近一年没有更新][Yellow]](https://github.com/davemeehan/Neo4j-GO)   [![godoc][GoDoc]](https://godoc.org/github.com/davemeehan/Neo4j-GO)
    * [godis](https://github.com/piaohao/godis) **star:72** 由GoLang实现的redis客户端，灵感来自jedis。   [![godoc][GoDoc]](https://godoc.org/github.com/piaohao/godis)
    * [arangolite](https://github.com/solher/arangolite) **star:66** 轻量级的 ArangoDB 驱动。   [![godoc][GoDoc]](https://godoc.org/github.com/solher/arangolite)
    * [dynago](https://github.com/underarmour/dynago) **star:66** 满足 principle of least surprise 的 DynamoDB 客户端。   [![最近一年没有更新][Yellow]](https://github.com/underarmour/dynago)   [![godoc][GoDoc]](https://godoc.org/github.com/underarmour/dynago)
    * [mgm](https://github.com/kamva/mgm) **star:60** 基于MongoDB模型的ODM for Go(基于官方MongoDB驱动)。   [![最近一周有更新][Green]](https://github.com/kamva/mgm)   [![godoc][GoDoc]](https://godoc.org/github.com/kamva/mgm)
    * [go-pilosa](https://github.com/pilosa/go-pilosa) **star:34**  Pilosa客户端。   [![最近一周有更新][Green]](https://github.com/pilosa/go-pilosa)   [![godoc][GoDoc]](https://godoc.org/github.com/pilosa/go-pilosa)
    * [forestdb](https://github.com/couchbase/goforestdb) **star:28** 基于 Go 的 ForestDB 接口实现。   [![最近一年没有更新][Yellow]](https://github.com/couchbase/goforestdb)   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/goforestdb)
    * [neo4j](https://github.com/cihangir/neo4j) **star:25** Neo4j Rest API实现。   [![最近一年没有更新][Yellow]](https://github.com/cihangir/neo4j)   [![godoc][GoDoc]](https://godoc.org/github.com/cihangir/neo4j)
    * [goriak](https://github.com/zegl/goriak) **star:24**  Riak KV 驱动。   [![最近一年没有更新][Yellow]](https://github.com/zegl/goriak)   [![godoc][GoDoc]](https://godoc.org/github.com/zegl/goriak)
    * [xredis](https://github.com/shomali11/xredis) **star:10** 类型安全，可定制，清晰和易用的Redis客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/shomali11/xredis)
    * [godscache](https://github.com/defcronyke/godscache) **star:7** 谷歌云平台Go Datastore包的封装，它采用了memcached添加缓存。   [![最近一年没有更新][Yellow]](https://github.com/defcronyke/godscache)   [![godoc][GoDoc]](https://godoc.org/github.com/defcronyke/godscache)
    * [gomemcache](https://github.com/bradfitz/gomemcache/)  memcache客户端库。
    * [asc](https://github.com/viant/asc) **star:4** Aerospike 的数据存储连接器。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/asc)

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) **star:6384** 基于 Go 的现代文本索引库。   [![star > 2000][Awesome]](https://github.com/blevesearch/bleve)   [![最近一周有更新][Green]](https://github.com/blevesearch/bleve)   [![godoc][GoDoc]](https://godoc.org/github.com/blevesearch/bleve)
    * [elastic](https://github.com/olivere/elastic) **star:4781** Elasticsearch 客户端。   [![star > 2000][Awesome]](https://github.com/olivere/elastic)   [![最近一周有更新][Green]](https://github.com/olivere/elastic)   [![godoc][GoDoc]](https://godoc.org/github.com/olivere/elastic)
    * [elastics
