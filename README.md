# Awesome Go

[Awesome]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.4.1/docs/awesome.svg "star > 2000"
[Green]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Green.svg "最近一周有更新"
[Yellow]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Yellow.svg "最近一年没有更新"
[CN]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Cn.svg "包含中文文档"
[Archived]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.2.1/docs/archived.svg "项目已归档"
[GoDoc]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.3.0/docs/DOC.svg "godoc文档地址"

**此项目是 [awesome-go](https://awesome-go.com/) 中文版，最后一次同步时间 : 2020-03-09 11:47:44(每隔1天同步一次)**

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
* [Tenyks](https://github.com/kyleterry/tenyks) **star:168** 面向服务的IRC bot，使用Redis和JSON进行消息传递。   [![godoc][GoDoc]](https://godoc.org/github.com/kyleterry/tenyks)
* [go-sarah](https://github.com/oklahomer/go-sarah) **star:156** 此框架提供了聊天机器人相关的服务，包括LINE、Slack、Gitter等。   [![godoc][GoDoc]](https://godoc.org/github.com/oklahomer/go-sarah)
* [hanu](https://github.com/sbstjn/hanu) **star:119** 用于编写Slack机器人的框架。   [![godoc][GoDoc]](https://godoc.org/github.com/sbstjn/hanu)
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) **star:94** Libary为twitch编写机器人程序。电视聊天   [![godoc][GoDoc]](https://godoc.org/github.com/gempir/go-twitch-irc)
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
* [go-arg](https://github.com/alexflint/go-arg) **star:841** 基于结构的参数解析。   [![godoc][GoDoc]](https://godoc.org/github.com/alexflint/go-arg)
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
* [wmenu](https://github.com/dixonwille/wmenu) **star:101** 为cli程序提供了简单上手的菜单，可提示用户作出选择。   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/wmenu)
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

* [termui](https://github.com/gizak/termui) **star:9567** 此库是基于**termbox-go**实现的，借鉴于[blessed-contrib](https://github.com/yaronn/blessed-contrib)。   [![star > 2000][Awesome]](https://github.com/gizak/termui)   [![godoc][GoDoc]](https://godoc.org/github.com/gizak/termui)
* [gommon/color](https://github.com/labstack/gommon/tree/master/color)  更换终端文本样式。
* [gocui](https://github.com/jroimartin/gocui) **star:6022** 旨在创建控制台用户界面的极简Go库。   [![star > 2000][Awesome]](https://github.com/jroimartin/gocui)   [![godoc][GoDoc]](https://godoc.org/github.com/jroimartin/gocui)
* [termbox-go](https://github.com/nsf/termbox-go) **star:3697** 基于文本的跨平台接口库。   [![star > 2000][Awesome]](https://github.com/nsf/termbox-go)   [![godoc][GoDoc]](https://godoc.org/github.com/nsf/termbox-go)
* [go-prompt](https://github.com/c-bata/go-prompt) **star:2862** 构建一个强大的交互式提示，借鉴于[python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit)   [![star > 2000][Awesome]](https://github.com/c-bata/go-prompt)   [![最近一周有更新][Green]](https://github.com/c-bata/go-prompt)   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/go-prompt)
* [uiprogress](https://github.com/gosuri/uiprogress) **star:1643** 在终端呈现进度条，可灵活配置的。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uiprogress)
* [asciigraph](https://github.com/guptarohit/asciigraph) **star:1310** 在命令行中构建轻量级ASCII线图╭┈╯，应用程序中没有其他依赖项。   [![godoc][GoDoc]](https://godoc.org/github.com/guptarohit/asciigraph)
* [uilive](https://github.com/gosuri/uilive) **star:1104** 用于实时更新终端输出的库。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uilive)
* [termdash](https://github.com/mum4k/termdash) **star:955** 此库是基于**termbox-go**实现的，借鉴于[termui](https://github.com/gizak/termui)。   [![最近一周有更新][Green]](https://github.com/mum4k/termdash)   [![godoc][GoDoc]](https://godoc.org/github.com/mum4k/termdash)
* [progressbar](https://github.com/schollz/progressbar) **star:859** 基本线程安全的进度条，在每个操作系统工作。   [![godoc][GoDoc]](https://godoc.org/github.com/schollz/progressbar)
* [mpb](https://github.com/vbauerster/mpb) **star:846** 可在终端显示多进度条。   [![最近一周有更新][Green]](https://github.com/vbauerster/mpb)   [![godoc][GoDoc]](https://godoc.org/github.com/vbauerster/mpb)
* [aurora](https://github.com/logrusorgru/aurora) **star:785** 支持fmt.Printf/Sprintf的ANSI终端颜色。   [![godoc][GoDoc]](https://godoc.org/github.com/logrusorgru/aurora)
* [uitable](https://github.com/gosuri/uitable) **star:546** 改善终端应用程序中表格数据的可读性。   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uitable)
* [go-colorable](https://github.com/mattn/go-colorable) **star:418** 适用于windows的颜色编写器。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-colorable)
* [go-isatty](https://github.com/mattn/go-isatty) **star:404** Go 实现的 isatty。   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-isatty)
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
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) **star:2807** 管理来自环境变量的配置数据。   [![star > 2000][Awesome]](https://github.com/kelseyhightower/envconfig)   [![godoc][GoDoc]](https://godoc.org/github.com/kelseyhightower/envconfig)
* [godotenv](https://github.com/joho/godotenv) **star:2644** Ruby 的 dotenv 库的 Go移植版(从.env文件加载环境变量)。   [![star > 2000][Awesome]](https://github.com/joho/godotenv)   [![godoc][GoDoc]](https://godoc.org/github.com/joho/godotenv)
* [ini](https://github.com/go-ini/ini) **star:1943**  读和写INI文件。   [![最近一周有更新][Green]](https://github.com/go-ini/ini)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ini/ini)
* [env](https://github.com/caarlos0/env) **star:1440** 解析环境变量并赋值到struct中(默认值)。   [![godoc][GoDoc]](https://godoc.org/github.com/caarlos0/env)
* [konfig](https://github.com/lalamove/konfig) **star:547** 可组合、可观察和高性能的分布式配置管理。   [![godoc][GoDoc]](https://godoc.org/github.com/lalamove/konfig)
* [confita](https://github.com/heetch/confita) **star:294** 从多个后端级联加载配置到struct中。   [![godoc][GoDoc]](https://godoc.org/github.com/heetch/confita)
* [store](https://github.com/tucnak/store) **star:248** 轻量级配置管理器。   [![最近一年没有更新][Yellow]](https://github.com/tucnak/store)   [![godoc][GoDoc]](https://godoc.org/github.com/tucnak/store)
* [config](https://github.com/JeremyLoy/config) **star:228** 云本地应用程序配置。将ENV绑定到结构体仅需两行代码。   [![godoc][GoDoc]](https://godoc.org/github.com/JeremyLoy/config)
* [config](https://github.com/olebedev/config) **star:225** 带有环境变量和标记解析的JSON或YAML配置包装器。   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/config)
* [joshbetz/config](https://github.com/joshbetz/config) **star:198** 一个可解析环境变量、JSON文件小巧的配置库，在SIGHUP时会自动重新加载。   [![godoc][GoDoc]](https://godoc.org/github.com/joshbetz/config)
* [hjson](https://github.com/hjson/hjson-go) **star:194** 更加人性化的JSON配置。轻松的语法，更少的错误，更多的注释。   [![godoc][GoDoc]](https://godoc.org/github.com/hjson/hjson-go)
* [envconfig](https://github.com/vrischmann/envconfig) **star:172** 从环境变量中读取配置。   [![godoc][GoDoc]](https://godoc.org/github.com/vrischmann/envconfig)
* [koanf](https://github.com/knadh/koanf) **star:167** 轻量级可扩展库，用于读取Go应用程序中的配置。内置支持JSON, TOML, YAML, env，命令行。   [![godoc][GoDoc]](https://godoc.org/github.com/knadh/koanf)
* [gookit/config](https://github.com/gookit/config) **star:137** 程序配置管理(load,get,set)。支持JSON, YAML, TOML, INI, HCL。支持多文件加载，数据覆盖合并。   [![godoc][GoDoc]](https://godoc.org/github.com/gookit/config)   [![包含中文文档][CN]](https://github.com/gookit/config)
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

* [drone](https://github.com/drone/drone) **star:20605** Drone 是一个基于 Docker 的持续集成平台，用 Go 编写。   [![star > 2000][Awesome]](https://github.com/drone/drone)   [![godoc][GoDoc]](https://godoc.org/github.com/drone/drone)
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
* [pREST](https://github.com/nuveo/prest) **star:2211** 基于PostgreSQL database的RESTful API服务。   [![star > 2000][Awesome]](https://github.com/nuveo/prest)   [![godoc][GoDoc]](https://godoc.org/github.com/nuveo/prest)
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
* [xo](https://github.com/knq/xo) **star:2388** 基于现有的schema定义和自定义查询生成 Go 代码，基于支持PostgreSQL、MySQL、SQLite、Oracle和Microsoft SQL Server。   [![star > 2000][Awesome]](https://github.com/knq/xo)   [![godoc][GoDoc]](https://godoc.org/github.com/knq/xo)
* [gendry](https://github.com/didi/gendry) **star:952** 非入侵的SQL构建器和强大的数据绑定器。   [![最近一周有更新][Green]](https://github.com/didi/gendry)   [![godoc][GoDoc]](https://godoc.org/github.com/didi/gendry)   [![包含中文文档][CN]](https://github.com/didi/gendry)
* [goqu](https://github.com/doug-martin/goqu) **star:737** 常用的SQL生成器和查询库。   [![godoc][GoDoc]](https://godoc.org/github.com/doug-martin/goqu)
* [Dotsql](https://github.com/gchaincl/dotsql) **star:506** Go library帮助您将sql文件保存在一个地方，并轻松地使用它们。   [![godoc][GoDoc]](https://godoc.org/github.com/gchaincl/dotsql)
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) **star:460** Powerful data retrieval methods as well as DB-agnostic query building capabilities.   [![godoc][GoDoc]](https://godoc.org/github.com/go-ozzo/ozzo-dbx)
* [jet](https://github.com/go-jet/jet) **star:227** 用于在Go中编写类型安全的SQL查询的框架，能够轻松地将数据库查询结果转换为所需的任意对象结构。   [![最近一周有更新][Green]](https://github.com/go-jet/jet)   [![godoc][GoDoc]](https://godoc.org/github.com/go-jet/jet)
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
    * [pq](https://github.com/lib/pq) **star:5694** 纯 Go 的Postgres驱动。   [![star > 2000][Awesome]](https://github.com/lib/pq)   [![godoc][GoDoc]](https://godoc.org/github.com/lib/pq)
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) **star:3856** SQLite3驱动程序。   [![star > 2000][Awesome]](https://github.com/mattn/go-sqlite3)
    * [pgx](https://github.com/jackc/pgx) **star:2410** PostgreSQL驱动，支持比现有database/sql更多的特性。   [![star > 2000][Awesome]](https://github.com/jackc/pgx)   [![godoc][GoDoc]](https://godoc.org/github.com/jackc/pgx)
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
    * [gorethink](https://github.com/dancannon/gorethink) **star:1500** RethinkDB 驱动。   [![最近一周有更新][Green]](https://github.com/dancannon/gorethink)   [![godoc][GoDoc]](https://godoc.org/github.com/dancannon/gorethink)
    * [redeo](https://github.com/bsm/redeo) **star:368** 与 redis 协议兼容的 TCP 服务器/服务。   [![godoc][GoDoc]](https://godoc.org/github.com/bsm/redeo)
    * [neoism](https://github.com/jmcvetta/neoism) **star:362** Golang 的 Neo4j 客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/jmcvetta/neoism)
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) **star:315** Aerospike 客户端。   [![最近一周有更新][Green]](https://github.com/aerospike/aerospike-client-go)   [![godoc][GoDoc]](https://godoc.org/github.com/aerospike/aerospike-client-go)
    * [gocb](https://github.com/couchbase/gocb) **star:307** 官方Couchbase Go SDK。   [![最近一周有更新][Green]](https://github.com/couchbase/gocb)   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/gocb)
    * [gocql](http://gocql.github.io)  Apache Cassandra 的 Go 驱动。
    * [go-couchbase](https://github.com/couchbase/go-couchbase) **star:297** Couchbase客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/go-couchbase)
    * [go-rejson](https://github.com/nitishm/go-rejson) **star:116** 实现了基于 Redigo 客户端的redislabs' ReJSON 模块。可简单地将结构体存储为JSON对象并对其进行操作。   [![godoc][GoDoc]](https://godoc.org/github.com/nitishm/go-rejson)
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) **star:74** Neo4j REST 客户端。   [![最近一年没有更新][Yellow]](https://github.com/davemeehan/Neo4j-GO)   [![godoc][GoDoc]](https://godoc.org/github.com/davemeehan/Neo4j-GO)
    * [godis](https://github.com/piaohao/godis) **star:71** 由GoLang实现的redis客户端，灵感来自jedis。   [![godoc][GoDoc]](https://godoc.org/github.com/piaohao/godis)
    * [arangolite](https://github.com/solher/arangolite) **star:66** 轻量级的 ArangoDB 驱动。   [![godoc][GoDoc]](https://godoc.org/github.com/solher/arangolite)
    * [dynago](https://github.com/underarmour/dynago) **star:66** 满足 principle of least surprise 的 DynamoDB 客户端。   [![最近一年没有更新][Yellow]](https://github.com/underarmour/dynago)   [![godoc][GoDoc]](https://godoc.org/github.com/underarmour/dynago)
    * [mgm](https://github.com/kamva/mgm) **star:59** 基于MongoDB模型的ODM for Go(基于官方MongoDB驱动)。   [![最近一周有更新][Green]](https://github.com/kamva/mgm)   [![godoc][GoDoc]](https://godoc.org/github.com/kamva/mgm)
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
    * [riot](https://github.com/go-ego/riot) **star:5077** 基于 Go 的 开源、分布式、简单高效的搜索引擎。   [![star > 2000][Awesome]](https://github.com/go-ego/riot)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ego/riot)   [![包含中文文档][CN]](https://github.com/go-ego/riot)
    * [elastic](https://github.com/olivere/elastic) **star:4781** Elasticsearch 客户端。   [![star > 2000][Awesome]](https://github.com/olivere/elastic)   [![最近一周有更新][Green]](https://github.com/olivere/elastic)   [![godoc][GoDoc]](https://godoc.org/github.com/olivere/elastic)
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) **star:2218** 官方 Elasticsearch 客户端。   [![star > 2000][Awesome]](https://github.com/elastic/go-elasticsearch)   [![最近一周有更新][Green]](https://github.com/elastic/go-elasticsearch)   [![godoc][GoDoc]](https://godoc.org/github.com/elastic/go-elasticsearch)
    * [elastigo](https://github.com/mattbaird/elastigo) **star:952** Elasticsearch 客户端。   [![最近一年没有更新][Yellow]](https://github.com/mattbaird/elastigo)   [![godoc][GoDoc]](https://godoc.org/github.com/mattbaird/elastigo)
    * [elasticsql](https://github.com/cch123/elasticsql) **star:494** 将 SQL 转换为 elasticsearch dsl。   [![godoc][GoDoc]](https://godoc.org/github.com/cch123/elasticsql)
    * [skizze](https://github.com/seiflotfy/skizze) **star:72** 面向概率数据结构的服务和存储。   [![最近一年没有更新][Yellow]](https://github.com/seiflotfy/skizze)   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/skizze)
    * [goes](https://github.com/OwnLocal/goes) **star:24** 实现了与 Elasticsearch 交互的库。   [![最近一年没有更新][Yellow]](https://github.com/OwnLocal/goes)   [![godoc][GoDoc]](https://godoc.org/github.com/OwnLocal/goes)

* Multiple Backends.
    * [cayley](https://github.com/google/cayley) **star:13221** 图形数据库，支持多个后端。   [![star > 2000][Awesome]](https://github.com/google/cayley)   [![godoc][GoDoc]](https://godoc.org/github.com/google/cayley)
    * [gokv](https://github.com/philippgille/gokv) **star:176** 可扩展的简单的 K/V 存储(Redis、Consul、etcd、bbolt、BadgerDB、LevelDB、Memcached、DynamoDB、S3、PostgreSQL、MongoDB、CockroachDB等等)。   [![最近一周有更新][Green]](https://github.com/philippgille/gokv)   [![godoc][GoDoc]](https://godoc.org/github.com/philippgille/gokv)
    * [cachego](https://github.com/fabiorphp/cachego) **star:115** 基于多个驱动程序的缓存组件。   [![godoc][GoDoc]](https://godoc.org/github.com/fabiorphp/cachego)
    * [dsc](https://github.com/viant/dsc) **star:18** 面向 SQL、NoSQL、结构化文件的数据存储连接。   [![godoc][GoDoc]](https://godoc.org/github.com/viant/dsc)

## 日期和时间

*用于处理日期和时间的库。 (翻译出错了? 试试 [英文版](README_EN.md#date-and-time) 吧~)*

* [now](https://github.com/jinzhu/now) **star:2425** now 是时间有关的工具类。   [![star > 2000][Awesome]](https://github.com/jinzhu/now)   [![godoc][GoDoc]](https://godoc.org/github.com/jinzhu/now)
* [dateparse](https://github.com/araddon/dateparse) **star:989** 可以解析很多格式不固定的日期字符串。   [![godoc][GoDoc]](https://godoc.org/github.com/araddon/dateparse)
* [carbon](https://github.com/uniplaces/carbon) **star:435** 简单的时间扩展，包含了许多使用方法，从 PHP Carbon 库移植的。   [![最近一年没有更新][Yellow]](https://github.com/uniplaces/carbon)   [![godoc][GoDoc]](https://godoc.org/github.com/uniplaces/carbon)
* [durafmt](https://github.com/hako/durafmt) **star:287** 轻量级、可让time.Duration更加易读的库。   [![godoc][GoDoc]](https://godoc.org/github.com/hako/durafmt)
* [timeutil](https://github.com/leekchan/timeutil) **star:176** 面向 Golang 的时间库，集成了很多有用的扩展(Timedelta, Strftime, ...)。   [![最近一年没有更新][Yellow]](https://github.com/leekchan/timeutil)   [![godoc][GoDoc]](https://godoc.org/github.com/leekchan/timeutil)
* [iso8601](https://github.com/relvacode/iso8601) **star:70** 不用正则表达式有效解析 ISO8601 日期时间。   [![最近一年没有更新][Yellow]](https://github.com/relvacode/iso8601)   [![godoc][GoDoc]](https://godoc.org/github.com/relvacode/iso8601)
* [timespan](https://github.com/SaidinWoT/timespan) **star:68** 用于处理时间间隔相关的库，可定义开始时间和持续时间。   [![godoc][GoDoc]](https://godoc.org/github.com/SaidinWoT/timespan)
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) **star:68** 太阳历实现。   [![godoc][GoDoc]](https://godoc.org/github.com/yaa110/go-persian-calendar)
* [date](https://github.com/rickb777/date) **star:34** 增加处理日期、日期范围、时间跨度、时间段和time-of-day。   [![godoc][GoDoc]](https://godoc.org/github.com/rickb777/date)
* [feiertage](https://github.com/wlbr/feiertage) **star:25** 用于计算德国公共假期的函数，比如复活节、感恩节等   [![godoc][GoDoc]](https://godoc.org/github.com/wlbr/feiertage)
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) **star:21** 计算指定位置的日出和日落时间。   [![最近一年没有更新][Yellow]](https://github.com/nathan-osman/go-sunrise)   [![godoc][GoDoc]](https://godoc.org/github.com/nathan-osman/go-sunrise)
* [kair](https://github.com/GuilhermeCaruso/kair) **star:15** 用于处理日期和时间的 golang 库。   [![godoc][GoDoc]](https://godoc.org/github.com/GuilhermeCaruso/kair)
* [cronrange](https://github.com/1set/cronrange) **star:13** 解析cron风格的时间范围表达式，检查给定的时间是否在任何范围内。   [![godoc][GoDoc]](https://godoc.org/github.com/1set/cronrange)
* [NullTime](https://github.com/kirillDanshin/nulltime) **star:10** 可以允许 time.Time 为null。   [![最近一年没有更新][Yellow]](https://github.com/kirillDanshin/nulltime)   [![godoc][GoDoc]](https://godoc.org/github.com/kirillDanshin/nulltime)
* [tuesday](https://github.com/osteele/tuesday) **star:8** Ruby-compatible Strftime function。   [![最近一年没有更新][Yellow]](https://github.com/osteele/tuesday)   [![godoc][GoDoc]](https://godoc.org/github.com/osteele/tuesday)
* [strftime](https://github.com/awoodbeck/strftime) **star:4** C99-compatible strftime formatter。   [![最近一年没有更新][Yellow]](https://github.com/awoodbeck/strftime)   [![godoc][GoDoc]](https://godoc.org/github.com/awoodbeck/strftime)
* [go-week](https://github.com/stoewer/go-week) **star:2** 一个有效的软件包，以配合ISO8601周日期。   [![godoc][GoDoc]](https://godoc.org/github.com/stoewer/go-week)
* [go-str2duration](https://github.com/xhit/go-str2duration) **star:1** 将字符串转换为持续时间。支持的时间。持续时间返回字符串等。   [![godoc][GoDoc]](https://godoc.org/github.com/xhit/go-str2duration)

## 分布式系统

*协助构建分布式系统的包。 (翻译出错了? 试试 [英文版](README_EN.md#distributed-systems) 吧~)*

* [go-kit](https://github.com/go-kit/kit) **star:16373** 支持服务发现、负载平衡、插件式传输、请求跟踪等功能的Microservice toolkit。   [![star > 2000][Awesome]](https://github.com/go-kit/kit)   [![最近一周有更新][Green]](https://github.com/go-kit/kit)   [![godoc][GoDoc]](https://godoc.org/github.com/go-kit/kit)
* [grpc-go](https://github.com/grpc/grpc-go) **star:10750** gRPC的Go语言实现。   [![star > 2000][Awesome]](https://github.com/grpc/grpc-go)   [![最近一周有更新][Green]](https://github.com/grpc/grpc-go)   [![godoc][GoDoc]](https://godoc.org/github.com/grpc/grpc-go)
* [micro](https://github.com/micro/micro) **star:7710** 可插拔的微服务 toolkit 和分布式系统平台。   [![star > 2000][Awesome]](https://github.com/micro/micro)   [![最近一周有更新][Green]](https://github.com/micro/micro)   [![godoc][GoDoc]](https://godoc.org/github.com/micro/micro)
* [NATS](https://github.com/nats-io/gnatsd) **star:7349** 轻量级、高性能消息传递系统，可用于微服务、物联网(IoT)和云。   [![star > 2000][Awesome]](https://github.com/nats-io/gnatsd)   [![最近一周有更新][Green]](https://github.com/nats-io/gnatsd)   [![godoc][GoDoc]](https://godoc.org/github.com/nats-io/gnatsd)
* [rpcx](https://github.com/smallnest/rpcx) **star:4422** 分布式可插拔的RPC服务框架，如阿里巴巴Dubbo。   [![star > 2000][Awesome]](https://github.com/smallnest/rpcx)   [![最近一周有更新][Green]](https://github.com/smallnest/rpcx)   [![godoc][GoDoc]](https://godoc.org/github.com/smallnest/rpcx)
* [tendermint](https://github.com/tendermint/tendermint) **star:3526** 一个高性能中间件，可将任何语言的状态机转换为 Byzantine Fault 状态机。使用 Tendermint 一致性及区块链协议。   [![star > 2000][Awesome]](https://github.com/tendermint/tendermint)   [![最近一周有更新][Green]](https://github.com/tendermint/tendermint)   [![godoc][GoDoc]](https://godoc.org/github.com/tendermint/tendermint)
* [torrent](https://github.com/anacrolix/torrent) **star:3368** BitTorrent 客户端。   [![star > 2000][Awesome]](https://github.com/anacrolix/torrent)   [![godoc][GoDoc]](https://godoc.org/github.com/anacrolix/torrent)
* [raft](https://github.com/hashicorp/raft) **star:3290** Raft consensus协议的实现。 by HashiCorp。   [![star > 2000][Awesome]](https://github.com/hashicorp/raft)   [![最近一周有更新][Green]](https://github.com/hashicorp/raft)   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/raft)
* [raft](https://github.com/coreos/etcd/tree/master/raft)  Raft consensus协议的实现。 by CoreOS。
* [dragonboat](https://github.com/lni/dragonboat) **star:2899** 一个功能齐全，高性能的库集。   [![star > 2000][Awesome]](https://github.com/lni/dragonboat)   [![最近一周有更新][Green]](https://github.com/lni/dragonboat)   [![godoc][GoDoc]](https://godoc.org/github.com/lni/dragonboat)   [![包含中文文档][CN]](https://github.com/lni/dragonboat)
* [glow](https://github.com/chrislusf/glow) **star:2756** 全部用 Go 实现，易用、可伸缩，可用于分布式大数据处理，Map-Reduce, DAG执行。   [![star > 2000][Awesome]](https://github.com/chrislusf/glow)   [![最近一年没有更新][Yellow]](https://github.com/chrislusf/glow)   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/glow)
* [KrakenD](https://github.com/devopsfaith/krakend) **star:2420** 具有中间件的高性能API网关框架。   [![star > 2000][Awesome]](https://github.com/devopsfaith/krakend)   [![最近一周有更新][Green]](https://github.com/devopsfaith/krakend)   [![godoc][GoDoc]](https://godoc.org/github.com/devopsfaith/krakend)
* [gleam](https://github.com/chrislusf/gleam) **star:2401** 使用纯Go和Luajit编写的快速、可伸缩的分布式map/reduce系统，结合了Go的高并发性和Luajit的高性能，可以独立运行或分布式运行。   [![star > 2000][Awesome]](https://github.com/chrislusf/gleam)   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/gleam)
* [emitter-io](https://github.com/emitter-io/emitter) **star:2260** 高性能、分布式、安全和低延迟的发布-订阅平台，使用MQTT、Websockets和love构建。   [![star > 2000][Awesome]](https://github.com/emitter-io/emitter)   [![最近一周有更新][Green]](https://github.com/emitter-io/emitter)   [![godoc][GoDoc]](https://godoc.org/github.com/emitter-io/emitter)
* [liftbridge](https://github.com/liftbridge-io/liftbridge) **star:1476** 用于nat的轻量级、容错的消息流。   [![最近一周有更新][Green]](https://github.com/liftbridge-io/liftbridge)   [![godoc][GoDoc]](https://godoc.org/github.com/liftbridge-io/liftbridge)
* [hprose](https://github.com/hprose/hprose-golang) **star:1080** 支持25+种语言RPC库。   [![godoc][GoDoc]](https://godoc.org/github.com/hprose/hprose-golang)   [![包含中文文档][CN]](https://github.com/hprose/hprose-golang)
* [ringpop-go](https://github.com/uber/ringpop-go) **star:604** 可伸缩的，容错、应用分层的的Go应用程序。   [![最近一年没有更新][Yellow]](https://github.com/uber/ringpop-go)   [![godoc][GoDoc]](https://godoc.org/github.com/uber/ringpop-go)
* [gorpc](https://github.com/valyala/gorpc) **star:578** 简单、快速和可伸缩的RPC库。   [![godoc][GoDoc]](https://godoc.org/github.com/valyala/gorpc)
* [go-health](https://github.com/InVisionApp/go-health) **star:534** 用于在服务中启用异步依赖项健康检查的库。   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/go-health)
* [rain](https://github.com/cenkalti/rain) **star:478** BitTorrent客户端和库。   [![godoc][GoDoc]](https://godoc.org/github.com/cenkalti/rain)
* [digota](https://github.com/digota/digota) **star:325** 基于 grpc 的电子商务微服务。   [![最近一年没有更新][Yellow]](https://github.com/digota/digota)   [![godoc][GoDoc]](https://godoc.org/github.com/digota/digota)
* [dot](https://github.com/dotchain/dot/)  基于 transformation/OT 的分布式同步。
* [sleuth](https://github.com/ursiform/sleuth) **star:312** 用于HTTP服务之间进行无中心p2p自动发现和RPC通信的库(使用[ZeroMQ](https://github.com/zeromq/libzmq))。   [![最近一年没有更新][Yellow]](https://github.com/ursiform/sleuth)   [![godoc][GoDoc]](https://godoc.org/github.com/ursiform/sleuth)
* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) **star:291** 为支持为golang服务定义异步服务健康检查而构建的库。   [![godoc][GoDoc]](https://godoc.org/github.com/AppsFlyer/go-sundheit)
* [go-jump](https://github.com/dgryski/go-jump) **star:281** 提供了谷歌的 “Jump” 一致哈希函数接口。   [![最近一年没有更新][Yellow]](https://github.com/dgryski/go-jump)   [![godoc][GoDoc]](https://godoc.org/github.com/dgryski/go-jump)
* [consistent](https://github.com/buraksezer/consistent) **star:266** Consistent hashing with bounded loads。   [![godoc][GoDoc]](https://godoc.org/github.com/buraksezer/consistent)
* [dht](https://github.com/anacrolix/dht) **star:150** BitTorrent Kademlia DHT的实现。   [![godoc][GoDoc]](https://godoc.org/github.com/anacrolix/dht)
* [jsonrpc](https://github.com/osamingo/jsonrpc) **star:125** jsonrpc 包，实现了 JSON-RPC 2.0。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/jsonrpc)
* [jsonrpc](https://github.com/ybbus/jsonrpc) **star:118** JSON-RPC 2.0 HTTP客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/ybbus/jsonrpc)
* [resgate](https://resgate.io/)  用于构建REST、实时和RPC API的实时API网关，其中所有客户端都是无缝同步的。
* [redis-lock](https://github.com/bsm/redislock) **star:96** 基于redis的分布式锁简易实现。   [![godoc][GoDoc]](https://godoc.org/github.com/bsm/redislock)
* [celeriac](https://github.com/svcavallar/celeriac.v1) **star:60** 用于对 Celery worker、任务、事件进行交互和监控的库。   [![最近一年没有更新][Yellow]](https://github.com/svcavallar/celeriac.v1)   [![godoc][GoDoc]](https://godoc.org/github.com/svcavallar/celeriac.v1)
* [doublejump](https://github.com/edwingeng/doublejump) **star:50** 实现了谷歌的jump consistent hash。   [![godoc][GoDoc]](https://godoc.org/github.com/edwingeng/doublejump)
* [dynamolock](https://cirello.io/dynamolock)  DynamoDB-backed 分布式锁定实现。
* [drmaa](https://github.com/dgruber/drmaa) **star:29** 符合 DRMAA 标准的集群调度程序作业提交库。   [![最近一年没有更新][Yellow]](https://github.com/dgruber/drmaa)   [![godoc][GoDoc]](https://godoc.org/github.com/dgruber/drmaa)
* [pglock](https://cirello.io/pglock)  postgresql 的分布式锁定实现。
* [outboxer](https://github.com/italolelis/outboxer) **star:27** 实现了 outbox pattern Go 库。   [![最近一周有更新][Green]](https://github.com/italolelis/outboxer)   [![godoc][GoDoc]](https://godoc.org/github.com/italolelis/outboxer)
* [flowgraph](https://github.com/vectaport/flowgraph) **star:25** flow-based programming package。   [![godoc][GoDoc]](https://godoc.org/github.com/vectaport/flowgraph)
* [go-pdu](https://github.com/pdupub/go-pdu) **star:11** 一个去中心化的基于身份的社交网络。   [![最近一周有更新][Green]](https://github.com/pdupub/go-pdu)   [![godoc][GoDoc]](https://godoc.org/github.com/pdupub/go-pdu)
* [dynatomic](https://github.com/tylfin/dynatomic) **star:10** 基于 DynamoDB 的 原子计数器的库。   [![最近一年没有更新][Yellow]](https://github.com/tylfin/dynatomic)   [![godoc][GoDoc]](https://godoc.org/github.com/tylfin/dynatomic)

## 动态域名

*更新动态DNS记录的工具。 (翻译出错了? 试试 [英文版](README_EN.md#dynamic-dns) 吧~)*

* [GoDNS](https://github.com/timothyye/godns) **star:551** 一个动态DNS客户端工具，支持DNSPod & HE.net。   [![godoc][GoDoc]](https://godoc.org/github.com/timothyye/godns)
* [DDNS](https://github.com/skibish/ddns) **star:131** 个人 DDNS 客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/skibish/ddns)
* [dyndns](https://gitlab.com/alcastle/dyndns)  后台去处理定期和自动检查您的IP地址，并作出更新(一个或多个)动态DNS记录，为谷歌域，每当您的地址变化。

## 电子邮件

*实现了电子邮件创建和发送。 (翻译出错了? 试试 [英文版](README_EN.md#email) 吧~)*

* [MailHog](https://github.com/mailhog/MailHog) **star:6047** 电子邮件和SMTP测试工具，对外提供了 web 和 API 接口。   [![star > 2000][Awesome]](https://github.com/mailhog/MailHog)   [![最近一周有更新][Green]](https://github.com/mailhog/MailHog)   [![godoc][GoDoc]](https://godoc.org/github.com/mailhog/MailHog)
* [hermes](https://github.com/matcornic/hermes) **star:1900** 可生成干净的、响应式的HTML电子邮件。   [![godoc][GoDoc]](https://godoc.org/github.com/matcornic/hermes)
* [email](https://github.com/jordan-wright/email) **star:1258** 一个强大和灵活的电子邮件库。   [![最近一周有更新][Green]](https://github.com/jordan-wright/email)   [![godoc][GoDoc]](https://godoc.org/github.com/jordan-wright/email)
* [go-imap](https://github.com/emersion/go-imap) **star:913** 用于客户端和服务器的IMAP库。   [![最近一周有更新][Green]](https://github.com/emersion/go-imap)   [![godoc][GoDoc]](https://godoc.org/github.com/emersion/go-imap)
* [SendGrid](https://github.com/sendgrid/sendgrid-go) **star:568** SendGrid 的 Go语言库，用于发送电子邮件。   [![最近一周有更新][Green]](https://github.com/sendgrid/sendgrid-go)   [![godoc][GoDoc]](https://godoc.org/github.com/sendgrid/sendgrid-go)
* [chasquid](https://blitiri.com.ar/p/chasquid)  用Go编写的SMTP服务器。
* [mailgun-go](https://github.com/mailgun/mailgun-go) **star:443** 使用Mailgun API去库发送邮件。   [![godoc][GoDoc]](https://godoc.org/github.com/mailgun/mailgun-go)
* [Hectane](https://github.com/hectane/hectane) **star:181** 轻量级的SMTP客户机，提供了HTTP API。   [![godoc][GoDoc]](https://godoc.org/github.com/hectane/hectane)
* [douceur](https://github.com/aymerick/douceur) **star:174** 在HTML邮件中支持CSS内联。   [![最近一年没有更新][Yellow]](https://github.com/aymerick/douceur)   [![godoc][GoDoc]](https://godoc.org/github.com/aymerick/douceur)
* [go-message](https://github.com/emersion/go-message) **star:142** 用于Internet消息格式化和邮件消息的流媒体库。   [![godoc][GoDoc]](https://godoc.org/github.com/emersion/go-message)
* [smtp](https://github.com/mailhog/smtp) **star:54** SMTP服务器协议状态机。   [![最近一年没有更新][Yellow]](https://github.com/mailhog/smtp)   [![godoc][GoDoc]](https://godoc.org/github.com/mailhog/smtp)
* [go-dkim](https://github.com/toorop/go-dkim) **star:52** DKIM库，用于签署 & 验证电子邮件。   [![godoc][GoDoc]](https://godoc.org/github.com/toorop/go-dkim)
* [go-premailer](https://github.com/vanng822/go-premailer) **star:45** 在HTML邮件中支持CSS内联。   [![godoc][GoDoc]](https://godoc.org/github.com/vanng822/go-premailer)
* [mailchain](https://github.com/mailchain/mailchain) **star:40** 发送加密的电子邮件到区块链地址写在Go。   [![最近一周有更新][Green]](https://github.com/mailchain/mailchain)   [![godoc][GoDoc]](https://godoc.org/github.com/mailchain/mailchain)
* [go-simple-mail](https://github.com/xhit/go-simple-mail) **star:19** 非常简单的包发送电子邮件与SMTP保持活动和两个超时:连接和发送。   [![godoc][GoDoc]](https://godoc.org/github.com/xhit/go-simple-mail)

## 可嵌入的脚本语言

*在go代码中嵌入其他语言。 (翻译出错了? 试试 [英文版](README_EN.md#embeddable-scripting-languages) 吧~)*

* [otto](https://github.com/robertkrimen/otto) **star:5161** 用 Go 编写的 JavaScript 解释器。   [![star > 2000][Awesome]](https://github.com/robertkrimen/otto)   [![godoc][GoDoc]](https://godoc.org/github.com/robertkrimen/otto)
* [gopher-lua](https://github.com/yuin/gopher-lua) **star:3322** 用 Go 实现的 Lua 5.1 虚拟机和编译器。   [![star > 2000][Awesome]](https://github.com/yuin/gopher-lua)   [![godoc][GoDoc]](https://godoc.org/github.com/yuin/gopher-lua)
* [go-lua](https://github.com/Shopify/go-lua) **star:1791** 用 Go 实现的 Lua 5.2 VM接口。   [![godoc][GoDoc]](https://godoc.org/github.com/Shopify/go-lua)
* [tengo](https://github.com/d5/tengo) **star:1568** 字节码编译的脚本语言。   [![最近一周有更新][Green]](https://github.com/d5/tengo)   [![godoc][GoDoc]](https://godoc.org/github.com/d5/tengo)
* [expr](https://github.com/antonmedv/expr) **star:1139** 一个可以计算表达式的引擎。   [![最近一周有更新][Green]](https://github.com/antonmedv/expr)   [![godoc][GoDoc]](https://godoc.org/github.com/antonmedv/expr)
* [go-python](https://github.com/sbinet/go-python) **star:1007** CPython C-API 的 Go 接口。   [![godoc][GoDoc]](https://godoc.org/github.com/sbinet/go-python)
* [anko](https://github.com/mattn/anko) **star:982** 用Go编写的解释器。   [![最近一周有更新][Green]](https://github.com/mattn/anko)   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/anko)
* [go-php](https://github.com/deuill/go-php) **star:728** PHP 的 Go 接口。   [![最近一年没有更新][Yellow]](https://github.com/deuill/go-php)   [![godoc][GoDoc]](https://godoc.org/github.com/deuill/go-php)
* [go-duktape](https://github.com/olebedev/go-duktape) **star:686** 支持 Duktape JavaScript 引擎。   [![最近一周有更新][Green]](https://github.com/olebedev/go-duktape)   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/go-duktape)
* [golua](https://github.com/aarzilli/golua) **star:467** Lua C 的 Go 接口。
* [gisp](https://github.com/jcla1/gisp) **star:435** LISP 的 Go 接口。   [![最近一年没有更新][Yellow]](https://github.com/jcla1/gisp)   [![godoc][GoDoc]](https://godoc.org/github.com/jcla1/gisp)
* [cel-go](https://github.com/google/cel-go) **star:375** 快速，可移植，非图灵完整的表达评估与渐进分型。   [![最近一周有更新][Green]](https://github.com/google/cel-go)   [![godoc][GoDoc]](https://godoc.org/github.com/google/cel-go)
* [gval](https://github.com/PaesslerAG/gval) **star:181** 一种用Go编写的高度可定制的表达式语言。   [![godoc][GoDoc]](https://godoc.org/github.com/PaesslerAG/gval)
* [gentee](https://github.com/gentee/gentee) **star:45** 嵌入式脚本编程语言。   [![godoc][GoDoc]](https://godoc.org/github.com/gentee/gentee)
* [binder](https://github.com/alexeyco/binder) **star:34** Lua接口，基于[gopher-lua](https://github.com/yuin/gopher-lua)。   [![最近一年没有更新][Yellow]](https://github.com/alexeyco/binder)   [![godoc][GoDoc]](https://godoc.org/github.com/alexeyco/binder)
* [purl](https://github.com/ian-kent/purl) **star:29** 嵌入 Go 的 Perl 5.18.2。   [![最近一年没有更新][Yellow]](https://github.com/ian-kent/purl)   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/purl)
* [ngaro](https://github.com/db47h/ngaro) **star:19** 嵌入式 Ngaro VM实现，支持在 Retro 中运行脚本。   [![最近一年没有更新][Yellow]](https://github.com/db47h/ngaro)   [![godoc][GoDoc]](https://godoc.org/github.com/db47h/ngaro)

## 错误处理

*处理错误的库。 (翻译出错了? 试试 [英文版](README_EN.md#error-handling) 吧~)*

* [errors](https://github.com/pkg/errors) **star:5572** 可让你很简单的进行错误处理。   [![star > 2000][Awesome]](https://github.com/pkg/errors)   [![godoc][GoDoc]](https://godoc.org/github.com/pkg/errors)
* [go-multierror](https://github.com/hashicorp/go-multierror) **star:815** 可将一系列的错误作为一个整体来显示。   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/go-multierror)
* [errorx](https://github.com/joomcode/errorx) **star:608** 一个功能丰富的错误包，可进行堆栈跟踪、组装异常信息以及其他。   [![最近一周有更新][Green]](https://github.com/joomcode/errorx)   [![godoc][GoDoc]](https://godoc.org/github.com/joomcode/errorx)
* [tracerr](https://github.com/ztrue/tracerr) **star:591** 可展示错误的堆栈跟踪信息和源码片段。   [![godoc][GoDoc]](https://godoc.org/github.com/ztrue/tracerr)
* [eris](https://github.com/rotisserie/eris) **star:578** 在Go中处理、跟踪和记录错误的更好方法。兼容标准错误库和github.com/pkg/errors。   [![最近一周有更新][Green]](https://github.com/rotisserie/eris)   [![godoc][GoDoc]](https://godoc.org/github.com/rotisserie/eris)
* [errlog](https://github.com/snwfdhmp/errlog) **star:302** 用于定位抛出错误的源代码(以及一些其他快速调试特性)。可插入到任何 logger 的位置。   [![godoc][GoDoc]](https://godoc.org/github.com/snwfdhmp/errlog)
* [emperror](https://github.com/emperror/emperror) **star:113** 用于Go库和应用程序的错误处理工具和最佳实践。   [![godoc][GoDoc]](https://godoc.org/github.com/emperror/emperror)
* [errors](https://github.com/emperror/errors) **star:42** 替换标准库错误包和github.com/pkg/errors。提供各种错误处理原语。   [![godoc][GoDoc]](https://godoc.org/github.com/emperror/errors)
* [werr](https://github.com/txgruppi/werr) **star:13** 对错误异常进行了捕获封装，封装信息包含了调用它的文件、行和堆栈。   [![最近一年没有更新][Yellow]](https://github.com/txgruppi/werr)   [![godoc][GoDoc]](https://godoc.org/github.com/txgruppi/werr)
* [errors](https://github.com/neuronlabs/errors) **star:3** 使用分类原语进行简单的golang错误处理。   [![godoc][GoDoc]](https://godoc.org/github.com/neuronlabs/errors)
* [errors](https://github.com/PumpkinSeed/errors) **star:2** 最简单的错误包装器，具有出色的性能和最小的内存开销。   [![godoc][GoDoc]](https://godoc.org/github.com/PumpkinSeed/errors)
* [Falcon](https://github.com/SonicRoshan/falcon) **star:2** 一个简单但功能强大的错误处理包。   [![godoc][GoDoc]](https://godoc.org/github.com/SonicRoshan/falcon)

## 文件

*处理文件和文件系统的库。 (翻译出错了? 试试 [英文版](README_EN.md#files) 吧~)*

* [afero](https://github.com/spf13/afero) **star:2604** 文件系统的抽象系统。   [![star > 2000][Awesome]](https://github.com/spf13/afero)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/afero)
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) **star:1339** PDF处理器。   [![godoc][GoDoc]](https://godoc.org/github.com/pdfcpu/pdfcpu)
* [notify](https://github.com/rjeczalik/notify) **star:544** 文件系统事件通知库，具有类似于os/signal的简单API，。   [![godoc][GoDoc]](https://godoc.org/github.com/rjeczalik/notify)
* [copy](https://github.com/otiai10/copy) **star:140** 递归地复制目录。   [![最近一周有更新][Green]](https://github.com/otiai10/copy)   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/copy)
* [bigfile](https://github.com/bigfile/bigfile) **star:115** 一个文件传输系统，支持管理文件与http api, rpc调用和ftp客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/bigfile/bigfile)   [![包含中文文档][CN]](https://github.com/bigfile/bigfile)
* [go-csv-tag](https://github.com/artonge/go-csv-tag) **star:64** 使用 tag 加载 csv 文件。   [![godoc][GoDoc]](https://godoc.org/github.com/artonge/go-csv-tag)
* [opc](https://github.com/qmuntal/opc) **star:63** 加载Open Packaging Conventions (OPC)文件。   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/opc)
* [stl](https://gitlab.com/russoj88/stl)  采用并行读取算法的进行读取和写入STL(立体光刻)文件的模块。
* [skywalker](https://github.com/dixonwille/skywalker) **star:55** 可以轻松地并发地遍历文件系统。   [![最近一年没有更新][Yellow]](https://github.com/dixonwille/skywalker)   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/skywalker)
* [vfs](https://github.com/C2FO/vfs) **star:47** 一组可插拔的、可扩展的和自定义的文件系统功能，用于跨越许多文件系统类型，如os、S3和GCS。   [![godoc][GoDoc]](https://godoc.org/github.com/C2FO/vfs)
* [afs](https://github.com/viant/afs) **star:40** 用于Go的抽象文件存储(mem、scp、zip、tar、cloud: s3、gs)。   [![最近一周有更新][Green]](https://github.com/viant/afs)   [![godoc][GoDoc]](https://godoc.org/github.com/viant/afs)
* [tarfs](https://github.com/posener/tarfs) **star:39** tar文件的实现[ FileSystem 接口](https://godoc.org/github.com/kr/fs#FileSystem)。   [![最近一年没有更新][Yellow]](https://github.com/posener/tarfs)   [![godoc][GoDoc]](https://godoc.org/github.com/posener/tarfs)
* [go-exiftool](https://github.com/barasher/go-exiftool) **star:22** ExifTool 的 Go 实现，这个著名的库用于从文件(图片、PDF、office，…)中提取尽可能多的元数据(EXIF、IPTC，…)。   [![godoc][GoDoc]](https://godoc.org/github.com/barasher/go-exiftool)
* [gut/yos](https://github.com/1set/gut) **star:20** 简单和可靠的包文件操作，如复制/移动/diff/列表的文件，目录和符号链接。   [![godoc][GoDoc]](https://godoc.org/github.com/1set/gut)
* [go-gtfs](https://github.com/artonge/go-gtfs) **star:20** 加载gtfs文件。   [![godoc][GoDoc]](https://godoc.org/github.com/artonge/go-gtfs)
* [checksum](https://github.com/codingsince1985/checksum) **star:17** 生成大型文件的消息摘要(如 MD5 和 SHA256)。   [![godoc][GoDoc]](https://godoc.org/github.com/codingsince1985/checksum)
* [flop](https://github.com/homedepot/flop) **star:15** 文件操作库，是[GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invoc.html)的镜像。   [![godoc][GoDoc]](https://godoc.org/github.com/homedepot/flop)
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) **star:14** 拷贝文件。   [![godoc][GoDoc]](https://godoc.org/github.com/hugocarreira/go-decent-copy)
* [parquet](https://github.com/parsyl/parquet) **star:5** 读写[parquet](https://parquet.apache.org)文件。   [![godoc][GoDoc]](https://godoc.org/github.com/parsyl/parquet)

## 金融

*会计和财务软件包。 (翻译出错了? 试试 [英文版](README_EN.md#financial) 吧~)*

* [decimal](https://github.com/shopspring/decimal) **star:1968** 任意精度定点的十进制数。   [![godoc][GoDoc]](https://godoc.org/github.com/shopspring/decimal)
* [go-money](https://github.com/rhymond/go-money) **star:716** Fowler 货币模式的实现。   [![最近一周有更新][Green]](https://github.com/rhymond/go-money)   [![godoc][GoDoc]](https://godoc.org/github.com/rhymond/go-money)
* [accounting](https://github.com/leekchan/accounting) **star:540** 货币和货币格式。   [![godoc][GoDoc]](https://godoc.org/github.com/leekchan/accounting)
* [go-finance](https://github.com/FlashBoys/go-finance) **star:539** 综合金融市场数据。   [![最近一年没有更新][Yellow]](https://github.com/FlashBoys/go-finance)   [![godoc][GoDoc]](https://godoc.org/github.com/FlashBoys/go-finance)
* [techan](https://github.com/sdcoffey/techan) **star:234** 拥有先进的市场分析和交易策略的技术分析库。   [![godoc][GoDoc]](https://godoc.org/github.com/sdcoffey/techan)
* [orderbook](https://github.com/i25959341/orderbook) **star:122** 限购单匹配引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/i25959341/orderbook)
* [ofxgo](https://github.com/aclindsa/ofxgo) **star:73** 查询 OFX 服务器和/或解析响应。   [![godoc][GoDoc]](https://godoc.org/github.com/aclindsa/ofxgo)
* [transaction](https://github.com/claygod/transaction) **star:65** 嵌入式事务数据库，可多线程模式运行。   [![godoc][GoDoc]](https://godoc.org/github.com/claygod/transaction)
* [vat](https://github.com/dannyvankooten/vat) **star:65** 增值税编号验证 & 欧盟增值税税率。   [![最近一年没有更新][Yellow]](https://github.com/dannyvankooten/vat)   [![godoc][GoDoc]](https://godoc.org/github.com/dannyvankooten/vat)
* [go-finance](https://github.com/alpeb/go-finance) **star:54** 用于货币时间价值(年金)、现金流、利率转换、债券和折旧计算的金融函数库。   [![godoc][GoDoc]](https://godoc.org/github.com/alpeb/go-finance)
* [go-finnhub](https://github.com/m1/go-finnhub) **star:21** 来自finnhu .io的股票市场、外汇和密码数据客户。从60多个证券交易所、10个外汇经纪人和15多个密码交易所获取实时金融市场数据。   [![godoc][GoDoc]](https://godoc.org/github.com/m1/go-finnhub)
* [currency](https://github.com/bnkamalesh/currency) **star:19** 高性能、准确的货币计算软件包。   [![godoc][GoDoc]](https://godoc.org/github.com/bnkamalesh/currency)
* [go-finance](https://github.com/pieterclaerhout/go-finance) **star:3** 模块获取汇率，通过VIES检查增值税号码，检查IBAN银行账号。   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-finance)

## 表单

*用于处理表单的库。 (翻译出错了? 试试 [英文版](README_EN.md#forms) 吧~)*

* [nosurf](https://github.com/justinas/nosurf) **star:1036** CSRF保护中间件。   [![godoc][GoDoc]](https://godoc.org/github.com/justinas/nosurf)
* [binding](https://github.com/mholt/binding) **star:768** 将来自 net/HTTP 请求的表单、JSON 数据绑定到结构体。   [![最近一年没有更新][Yellow]](https://github.com/mholt/binding)   [![godoc][GoDoc]](https://godoc.org/github.com/mholt/binding)
* [gorilla/csrf](https://github.com/gorilla/csrf) **star:505** 用于Go web应用程序和服务的CSRF保护。   [![godoc][GoDoc]](https://godoc.org/github.com/gorilla/csrf)
* [form](https://github.com/go-playground/form) **star:398**  将 url 中的数据解析到 Go 变量中，以及将 Go 语言变量编码进 url。支持 Dual Array 及 Full map。   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/form)
* [conform](https://github.com/leebenson/conform) **star:184** 控制用户输入。基于struct tags可对数据进行修剪、清理和擦除。   [![godoc][GoDoc]](https://godoc.org/github.com/leebenson/conform)
* [formam](https://github.com/monoculum/formam) **star:139** 将表单的值解码为 struct。   [![godoc][GoDoc]](https://godoc.org/github.com/monoculum/formam)
* [forms](https://github.com/albrow/forms) **star:104** 与框架无关的库，用于解析和验证支持多部分表单和文件的表单/JSON数据。   [![最近一年没有更新][Yellow]](https://github.com/albrow/forms)   [![godoc][GoDoc]](https://godoc.org/github.com/albrow/forms)
* [bind](https://github.com/robfig/bind) **star:24** 将表单数据与任意 Go 变量进行绑定。   [![最近一年没有更新][Yellow]](https://github.com/robfig/bind)   [![godoc][GoDoc]](https://godoc.org/github.com/robfig/bind)
* [queryparam](https://github.com/tomwright/queryparam) **star:2** 解码的url。值转换为标准或自定义类型的可用结构值。   [![godoc][GoDoc]](https://godoc.org/github.com/tomwright/queryparam)

## 方法

*在Go中支持函数式编程的包。 (翻译出错了? 试试 [英文版](README_EN.md#functional) 吧~)*

* [go-underscore](https://github.com/tobyhede/go-underscore) **star:1127** 常用辅助方法集合。   [![最近一年没有更新][Yellow]](https://github.com/tobyhede/go-underscore)   [![godoc][GoDoc]](https://godoc.org/github.com/tobyhede/go-underscore)
* [fpGo](https://github.com/TeaEntityLab/fpGo) **star:137** 提供函数式编程功能。   [![最近一年没有更新][Yellow]](https://github.com/TeaEntityLab/fpGo)   [![godoc][GoDoc]](https://godoc.org/github.com/TeaEntityLab/fpGo)
* [fuego](https://github.com/seborama/fuego) **star:64** Functional Experiment in Go。   [![godoc][GoDoc]](https://godoc.org/github.com/seborama/fuego)

## 游戏开发

*很棒的游戏开发库。 (翻译出错了? 试试 [英文版](README_EN.md#game-development) 吧~)*

* [Leaf](https://github.com/name5566/leaf) **star:3424** 轻量级游戏服务器框架。   [![star > 2000][Awesome]](https://github.com/name5566/leaf)   [![godoc][GoDoc]](https://godoc.org/github.com/name5566/leaf)   [![包含中文文档][CN]](https://github.com/name5566/leaf)
* [Pixel](https://github.com/faiface/pixel) **star:2776** 手工制作的 2D 游戏库。   [![star > 2000][Awesome]](https://github.com/faiface/pixel)   [![godoc][GoDoc]](https://godoc.org/github.com/faiface/pixel)
* [Ebiten](https://github.com/hajimehoshi/ebiten) **star:2544** 很简单的 2D 游戏库。   [![star > 2000][Awesome]](https://github.com/hajimehoshi/ebiten)   [![最近一周有更新][Green]](https://github.com/hajimehoshi/ebiten)   [![godoc][GoDoc]](https://godoc.org/github.com/hajimehoshi/ebiten)
* [goworld](https://github.com/xiaonanln/goworld) **star:1413** 可伸缩的游戏服务器引擎，具有 space-entity 框架和 hot-swapping 功能。   [![godoc][GoDoc]](https://godoc.org/github.com/xiaonanln/goworld)   [![包含中文文档][CN]](https://github.com/xiaonanln/goworld)
* [go-sdl2](https://github.com/veandco/go-sdl2) **star:1288** 实现了[Simple DirectMedia Layer](https://www.libsdl.org/)。
* [nano](https://github.com/lonng/nano) **star:1209** 轻量级、方便、高性能的基于golang的游戏服务器框架。   [![godoc][GoDoc]](https://godoc.org/github.com/lonng/nano)   [![包含中文文档][CN]](https://github.com/lonng/nano)
* [engo](https://github.com/EngoEngine/engo) **star:1166** 开源 2D 游戏引擎。它遵循 Entity-Component-System 范式。   [![最近一周有更新][Green]](https://github.com/EngoEngine/engo)   [![godoc][GoDoc]](https://godoc.org/github.com/EngoEngine/engo)
* [termloop](https://github.com/JoelOtter/termloop) **star:1110** 基于终端的 Go 游戏引擎，建立在 Termbox 之上。   [![godoc][GoDoc]](https://godoc.org/github.com/JoelOtter/termloop)
* [gonet](https://github.com/xtaci/gonet) **star:1088** 实现了游戏服务器骨架。   [![最近一年没有更新][Yellow]](https://github.com/xtaci/gonet)   [![godoc][GoDoc]](https://godoc.org/github.com/xtaci/gonet)
* [g3n](https://github.com/g3n/engine) **star:957**  3D游戏引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/g3n/engine)
* [Oak](https://github.com/oakmound/oak) **star:713** 纯 Go 实现的游戏引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/oakmound/oak)
* [Pitaya](https://github.com/topfreegames/pitaya) **star:485** 可伸缩的游戏服务器框架，支持集群和客户端库的iOS, Android, Unity。   [![godoc][GoDoc]](https://godoc.org/github.com/topfreegames/pitaya)
* [raylib-go](https://github.com/gen2brain/raylib-go) **star:443** 实现了 [raylib](http://www.raylib.com/)，一个简单易用的库，用于学习视频游戏编程。
* [Azul3D](https://github.com/azul3d/engine) **star:442** 用Go编写的 3D 游戏引擎。
* [go-astar](https://github.com/beefsack/go-astar) **star:352** 实现了A\*路径查找算法。   [![最近一年没有更新][Yellow]](https://github.com/beefsack/go-astar)   [![godoc][GoDoc]](https://godoc.org/github.com/beefsack/go-astar)
* [GarageEngine](https://github.com/vova616/GarageEngine) **star:319** 用 OpenGL 编写的 2D 游戏引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/vova616/GarageEngine)
* [go3d](https://github.com/ungerik/go3d) **star:173** 以性能为主的2D/3D数学相关包。   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/go3d)
* [glop](https://github.com/runningwild/glop) **star:77** Glop (Game Library Of Power) 是一个相当简单的跨平台游戏库。   [![最近一年没有更新][Yellow]](https://github.com/runningwild/glop)
* [go-collada](https://github.com/GlenKelley/go-collada) **star:15** 处理Collada文件。   [![最近一年没有更新][Yellow]](https://github.com/GlenKelley/go-collada)   [![godoc][GoDoc]](https://godoc.org/github.com/GlenKelley/go-collada)

## 代码生成与泛型

*增强语言的工具，例如通过代码生成支持泛型。 (翻译出错了? 试试 [英文版](README_EN.md#generation-and-generics) 吧~)*

* [go-linq](https://github.com/ahmetalpbalkan/go-linq) **star:1991** 提供类似 .NET LINQ 的查询方法。   [![godoc][GoDoc]](https://godoc.org/github.com/ahmetalpbalkan/go-linq)
* [jennifer](https://github.com/dave/jennifer) **star:1463** 不使用模板生成任意 Go 代码。   [![godoc][GoDoc]](https://godoc.org/github.com/dave/jennifer)
* [gen](https://github.com/clipperhouse/gen) **star:1092** 用于生成泛型等类似方法的功能代码生成工具。   [![godoc][GoDoc]](https://godoc.org/github.com/clipperhouse/gen)
* [goderive](https://github.com/awalterschulze/goderive) **star:788** 从输入类型来派生函数。   [![godoc][GoDoc]](https://godoc.org/github.com/awalterschulze/goderive)
* [GoWrap](https://github.com/hexdigest/gowrap) **star:330** 使用简单模板为 Go 接口生成装饰器。   [![最近一周有更新][Green]](https://github.com/hexdigest/gowrap)   [![godoc][GoDoc]](https://godoc.org/github.com/hexdigest/gowrap)
* [interfaces](https://github.com/rjeczalik/interfaces) **star:206** 用于生成接口定义的命令行工具。   [![godoc][GoDoc]](https://godoc.org/github.com/rjeczalik/interfaces)
* [go-enum](https://github.com/abice/go-enum) **star:101** 从代码注释中生成枚举。   [![godoc][GoDoc]](https://godoc.org/github.com/abice/go-enum)
* [pkgreflect](https://github.com/ungerik/pkgreflect) **star:92** 用于包作用域反射的 Go 预处理器。   [![最近一年没有更新][Yellow]](https://github.com/ungerik/pkgreflect)   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/pkgreflect)
* [efaceconv](https://github.com/t0pep0/efaceconv) **star:44** 代码生成工具，可以不通过内存分配就可以高效的将interface{}转换为不可变类型，。   [![最近一年没有更新][Yellow]](https://github.com/t0pep0/efaceconv)   [![godoc][GoDoc]](https://godoc.org/github.com/t0pep0/efaceconv)
* [gotype](https://github.com/wzshiming/gotype) **star:29** Golang 源码解析，用法类似reflect(反射)。   [![godoc][GoDoc]](https://godoc.org/github.com/wzshiming/gotype)   [![包含中文文档][CN]](https://github.com/wzshiming/gotype)
* [generis](https://github.com/senselogic/GENERIS) **star:20** 提供泛型、free-form 宏、条件编译和HTML模板的代码生成工具。
* [go-xray](https://github.com/pieterclaerhout/go-xray) **star:6** 帮助更容易地使用反射。   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-xray)
* [typeregistry](https://github.com/xiaoxin01/typeregistry) **star:3** 动态创建类型的库。   [![godoc][GoDoc]](https://godoc.org/github.com/xiaoxin01/typeregistry)

## 地理

*地理工具和服务器 (翻译出错了? 试试 [英文版](README_EN.md#geographic) 吧~)*

* [Tile38](https://github.com/tidwall/tile38) **star:6716** 具有空间索引和实时地理定位功能的地理定位数据库。   [![star > 2000][Awesome]](https://github.com/tidwall/tile38)   [![最近一周有更新][Green]](https://github.com/tidwall/tile38)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/tile38)
* [S2 geometry](https://github.com/golang/geo) **star:1012** S2 geometry 库。   [![godoc][GoDoc]](https://godoc.org/github.com/golang/geo)
* [mbtileserver](https://github.com/consbio/mbtileserver) **star:130** 一个简单的基于go的服务器，用于存储mbtiles格式的地图块。   [![godoc][GoDoc]](https://godoc.org/github.com/consbio/mbtileserver)
* [geocache](https://github.com/melihmucuk/geocache) **star:119** 基于内存缓存的的地理位置的应用程序。   [![最近一年没有更新][Yellow]](https://github.com/melihmucuk/geocache)   [![godoc][GoDoc]](https://godoc.org/github.com/melihmucuk/geocache)
* [osm](https://github.com/paulmach/osm) **star:101** 用于读取、写入和处理 OpenStreetMap 数据和 APIs。   [![godoc][GoDoc]](https://godoc.org/github.com/paulmach/osm)
* [WGS84](https://github.com/wroge/wgs84) **star:49** 坐标转换和转换库(ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM)。   [![godoc][GoDoc]](https://godoc.org/github.com/wroge/wgs84)
* [geoserver](https://github.com/hishamkaram/geoserver) **star:33** 基于geoserver REST API的 geoserver 实例。   [![godoc][GoDoc]](https://godoc.org/github.com/hishamkaram/geoserver)
* [gismanager](https://github.com/hishamkaram/gismanager) **star:26** 将你的 GIS 数据(矢量数据)发布到 PostGIS 和 Geoserver。   [![最近一年没有更新][Yellow]](https://github.com/hishamkaram/gismanager)   [![godoc][GoDoc]](https://godoc.org/github.com/hishamkaram/gismanager)
* [pbf](https://github.com/maguro/pbf) **star:20** 基于Golang 的 OpenStreetMap PBF 编码器/解码器。   [![godoc][GoDoc]](https://godoc.org/github.com/maguro/pbf)

## Go 编译器

*可将 Go 转换为其他语言的编译工具。 (翻译出错了? 试试 [英文版](README_EN.md#go-compilers) 吧~)*

* [gopherjs](https://github.com/gopherjs/gopherjs) **star:9211** 将 Go 编译成 JavaScript。   [![star > 2000][Awesome]](https://github.com/gopherjs/gopherjs)   [![godoc][GoDoc]](https://godoc.org/github.com/gopherjs/gopherjs)
* [llgo](https://github.com/go-llvm/llgo) **star:1041** 基于 llvm 的编译器。   [![最近一年没有更新][Yellow]](https://github.com/go-llvm/llgo)   [![godoc][GoDoc]](https://godoc.org/github.com/go-llvm/llgo)
* [tardisgo](https://github.com/tardisgo/tardisgo) **star:396** Golang 转换为 Haxe，再转换为 CPP/CSharp/Java/JavaScript 的编译器.   [![最近一年没有更新][Yellow]](https://github.com/tardisgo/tardisgo)   [![godoc][GoDoc]](https://godoc.org/github.com/tardisgo/tardisgo)
* [c4go](https://github.com/Konstantin8105/c4go) **star:202** 将 C 代码转换为 Go 代码。   [![godoc][GoDoc]](https://godoc.org/github.com/Konstantin8105/c4go)
* [f4go](https://github.com/Konstantin8105/f4go) **star:23** 将 FORTRAN 77 转换为 Go代码。   [![godoc][GoDoc]](https://godoc.org/github.com/Konstantin8105/f4go)

## Goroutines

*管理和处理 Goroutines 的工具。 (翻译出错了? 试试 [英文版](README_EN.md#goroutines) 吧~)*

* [ants](https://github.com/panjf2000/ants) **star:3114** 一个高性能和低成本的goroutine池在围棋。   [![star > 2000][Awesome]](https://github.com/panjf2000/ants)   [![godoc][GoDoc]](https://godoc.org/github.com/panjf2000/ants)   [![包含中文文档][CN]](https://github.com/panjf2000/ants)
* [goworker](https://github.com/benmanns/goworker) **star:2351** 基于 go 的后台 worker。   [![star > 2000][Awesome]](https://github.com/benmanns/goworker)   [![godoc][GoDoc]](https://godoc.org/github.com/benmanns/goworker)
* [tunny](https://github.com/Jeffail/tunny) **star:1568** golang 的协程池。   [![godoc][GoDoc]](https://godoc.org/github.com/Jeffail/tunny)
* [pool](https://github.com/go-playground/pool) **star:546** 有限消费者协程或无限协程池，可用于更加简单的处理和取消协程   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/pool)
* [grpool](https://github.com/ivpusic/grpool) **star:542** 轻量级协程池。   [![最近一年没有更新][Yellow]](https://github.com/ivpusic/grpool)   [![godoc][GoDoc]](https://godoc.org/github.com/ivpusic/grpool)
* [workerpool](https://github.com/gammazero/workerpool) **star:265** 限制任务执行并发数，而不是队列中的任务数量的协程池，。   [![godoc][GoDoc]](https://godoc.org/github.com/gammazero/workerpool)
* [go-floc](https://github.com/workanator/go-floc) **star:177** 轻松编排 goroutines。   [![最近一年没有更新][Yellow]](https://github.com/workanator/go-floc)   [![godoc][GoDoc]](https://godoc.org/github.com/workanator/go-floc)
* [gowp](https://github.com/xxjwxc/gowp) **star:163** gowp是高并发性限制异步工作池。   [![godoc][GoDoc]](https://godoc.org/github.com/xxjwxc/gowp)   [![包含中文文档][CN]](https://github.com/xxjwxc/gowp)
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) **star:127** 控制 goroutines 的执行顺序。   [![godoc][GoDoc]](https://godoc.org/github.com/kamildrazkiewicz/go-flow)
* [GoSlaves](https://github.com/themester/GoSlaves) **star:91** 简单异步的协程池。   [![godoc][GoDoc]](https://godoc.org/github.com/themester/GoSlaves)
* [semaphore](https://github.com/kamilsk/semaphore) **star:82** 信号量模式实现，可根据通道和上下文进行具备超时功能的锁定/解锁操作。   [![godoc][GoDoc]](https://godoc.org/github.com/kamilsk/semaphore)
* [semaphore](https://github.com/marusama/semaphore) **star:80** 基于 CAS 的可快速调整的信号量实现(比基于通道的信号量实现更快)。   [![最近一年没有更新][Yellow]](https://github.com/marusama/semaphore)   [![godoc][GoDoc]](https://godoc.org/github.com/marusama/semaphore)
* [gpool](https://github.com/Sherifabdlnaby/gpool) **star:65** manages a resizeable pool of context-aware goroutines to bound concurrency   [![godoc][GoDoc]](https://godoc.org/github.com/Sherifabdlnaby/gpool)
* [breaker](https://github.com/kamilsk/breaker) **star:56** 灵活的机制，可以使执行流可中断。   [![godoc][GoDoc]](https://godoc.org/github.com/kamilsk/breaker)
* [worker-pool](https://github.com/vardius/worker-pool) **star:53** 一个简单的 Go 异步工作池。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/worker-pool)
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) **star:44** 基于 Go 的 CyclicBarrier 实现。   [![最近一年没有更新][Yellow]](https://github.com/marusama/cyclicbarrier)   [![godoc][GoDoc]](https://godoc.org/github.com/marusama/cyclicbarrier)
* [gollback](https://github.com/vardius/gollback) **star:31** 异步简单的函数实用程序，用于管理闭包和回调的执行。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/gollback)
* [async](https://github.com/studiosol/async) **star:30** 一种异步执行函数的安全方法，在出现 panic 时恢复它们。   [![godoc][GoDoc]](https://godoc.org/github.com/studiosol/async)
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) **star:26** 并行运行函数。   [![最近一年没有更新][Yellow]](https://github.com/rafaeljesus/parallel-fn)   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/parallel-fn)
* [threadpool](https://github.com/shettyh/threadpool) **star:25** Golang 的 threadpool 实现。   [![最近一年没有更新][Yellow]](https://github.com/shettyh/threadpool)   [![godoc][GoDoc]](https://godoc.org/github.com/shettyh/threadpool)
* [artifex](https://github.com/borderstech/artifex) **star:24** 简单的内存作业队列。   [![godoc][GoDoc]](https://godoc.org/github.com/borderstech/artifex)
* [Hunch](https://github.com/AaronJan/Hunch) **star:23** Hunch 提供了诸如 All、First、Retry、Waterfall 等功能，这使得异步流控制更加直观。   [![godoc][GoDoc]](https://godoc.org/github.com/AaronJan/Hunch)
* [oversight](https://cirello.io/oversight)  完整的实现了Erlang supervision trees。
* [kyoo](https://github.com/dirkaholic/kyoo) **star:22** 提供无限的作业队列和并发工作池。   [![godoc][GoDoc]](https://godoc.org/github.com/dirkaholic/kyoo)
* [stl](https://github.com/ssgreg/stl) **star:11** 基于软件事务内存(STM)并发控制机制的软件事务锁。   [![godoc][GoDoc]](https://godoc.org/github.com/ssgreg/stl)
* [gohive](https://github.com/loveleshsharma/gohive) **star:11** 一个高性能和易于使用的Goroutine池去。   [![godoc][GoDoc]](https://godoc.org/github.com/loveleshsharma/gohive)
* [routine](https://github.com/x-mod/routine) **star:9** go routine control with context, support: Main, Go, Pool and some useful Executors.   [![godoc][GoDoc]](https://godoc.org/github.com/x-mod/routine)
* [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) **star:5** 像“同步。有错误处理和并发控制。   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-waitgroup)
* [go-trylock](https://github.com/subchen/go-trylock) **star:5** 支持 read-write 锁。   [![godoc][GoDoc]](https://godoc.org/github.com/subchen/go-trylock)
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) **star:5** 轻量级的协程池库，可以通过简单的API来管理。   [![godoc][GoDoc]](https://godoc.org/github.com/nikhilsaraf/go-tools)
* [conexec](https://github.com/ITcathyh/conexec) **star:4** 一个并发工具包，帮助以高效和安全的方式并发执行函数。它支持指定总的超时来避免阻塞，并使用goroutine池来提高效率。   [![godoc][GoDoc]](https://godoc.org/github.com/ITcathyh/conexec)
* [queue](https://github.com/AnikHasibul/queue) **star:3** 提供类似队列组可访问性 sync.WaitGroup 的功能。帮助你节流和限制协程、等待所有协程结束以及更多功能。   [![godoc][GoDoc]](https://godoc.org/github.com/AnikHasibul/queue)

## GUI

*用于构建GUI应用程序的库。 (翻译出错了? 试试 [英文版](README_EN.md#gui) 吧~)*

*工具包 (翻译出错了? 试试 [英文版](README_EN.md#gui) 吧~)*

* [fyne](https://github.com/fyne-io/fyne) **star:8929** 基于材料设计的Go跨平台本机gui设计。支持:Linux, macOS, Windows, BSD, iOS和Android。   [![star > 2000][Awesome]](https://github.com/fyne-io/fyne)   [![最近一周有更新][Green]](https://github.com/fyne-io/fyne)   [![godoc][GoDoc]](https://godoc.org/github.com/fyne-io/fyne)
* [ui](https://github.com/andlabs/ui) **star:7374** 跨平台的 Platform-native GUI 库。   [![star > 2000][Awesome]](https://github.com/andlabs/ui)   [![godoc][GoDoc]](https://godoc.org/github.com/andlabs/ui)
* [Wails](https://wails.app)  Mac, Windows, Linux桌面应用程序，主要基于含有内置的OS HTML渲染器的HTML UI。
* [qt](https://github.com/therecipe/qt) **star:7057** 实现了 Qt 的 Go接口(支持Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi)。   [![star > 2000][Awesome]](https://github.com/therecipe/qt)   [![godoc][GoDoc]](https://godoc.org/github.com/therecipe/qt)
* [webview](https://github.com/zserge/webview) **star:5542** 跨平台webview窗口，具有简单的双向JavaScript绑定(Windows / macOS / Linux)。   [![star > 2000][Awesome]](https://github.com/zserge/webview)   [![最近一周有更新][Green]](https://github.com/zserge/webview)
* [walk](https://github.com/lxn/walk) **star:4290** Windows应用程序库。   [![star > 2000][Awesome]](https://github.com/lxn/walk)   [![godoc][GoDoc]](https://godoc.org/github.com/lxn/walk)
* [app](https://github.com/murlokswarm/app) **star:3343** 用于创建包含了 GO, HTML 和 CSS 的应用程序。支持 MacOS, Windows 正在开发中。   [![star > 2000][Awesome]](https://github.com/murlokswarm/app)   [![最近一周有更新][Green]](https://github.com/murlokswarm/app)   [![godoc][GoDoc]](https://godoc.org/github.com/murlokswarm/app)
* [go-astilectron](https://github.com/asticode/go-astilectron) **star:3059** 使用 GO 和 HTML/JS/CSS (电子驱动)进行构建跨平台 GUI 应用程序。   [![star > 2000][Awesome]](https://github.com/asticode/go-astilectron)   [![godoc][GoDoc]](https://godoc.org/github.com/asticode/go-astilectron)
* [go-gtk](http://mattn.github.io/go-gtk/)  实现了 GTK 的 Go接口。
* [go-sciter](https://github.com/sciter-sdk/go-sciter) **star:1645** 实现了 Sciter 的 Go 接口 : 用于现代桌面 UI 开发的可嵌入HTML/CSS/脚本引擎。可跨平台。   [![godoc][GoDoc]](https://godoc.org/github.com/sciter-sdk/go-sciter)
* [gotk3](https://github.com/gotk3/gotk3) **star:938** 实现了 GTK3 的 Go接口。   [![最近一周有更新][Green]](https://github.com/gotk3/gotk3)   [![godoc][GoDoc]](https://godoc.org/github.com/gotk3/gotk3)
* [gowd](https://github.com/dtylman/gowd) **star:243** 跨平台、快速、简单的桌面UI开发，采用了GO, HTML, CSS和NW.js实现。   [![godoc][GoDoc]](https://godoc.org/github.com/dtylman/gowd)

*交互 (翻译出错了? 试试 [英文版](README_EN.md#gui) 吧~)*

* [robotgo](https://github.com/go-vgo/robotgo) **star:4871** 实现跨平台的GUI系统自动化。包含了控制鼠标、键盘等功能。   [![star > 2000][Awesome]](https://github.com/go-vgo/robotgo)   [![最近一周有更新][Green]](https://github.com/go-vgo/robotgo)
* [systray](https://github.com/getlantern/systray) **star:1018** 跨平台 Go 库，可在通知区放置图标和菜单。   [![godoc][GoDoc]](https://godoc.org/github.com/getlantern/systray)
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) **star:511** OSX 桌面通知库。   [![godoc][GoDoc]](https://godoc.org/github.com/deckarep/gosx-notifier)
* [trayhost](https://github.com/shurcooL/trayhost) **star:174** 跨平台 Go 库，可用于在主机操作系统的任务栏中放置图标。   [![godoc][GoDoc]](https://godoc.org/github.com/shurcooL/trayhost)
* [go-appindicator](https://github.com/dawidd6/go-appindicator) **star:5** 实现了 libappindicator3 C库 的 Go接口。   [![godoc][GoDoc]](https://godoc.org/github.com/dawidd6/go-appindicator)
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) **star:5** 用于通知计算机上的任何(可插入的)活动的 OSX 库。   [![godoc][GoDoc]](https://godoc.org/github.com/prashantgupta24/activity-tracker)
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) **star:2** OSX 睡眠/唤醒通知。   [![godoc][GoDoc]](https://godoc.org/github.com/prashantgupta24/mac-sleep-notifier)


## 硬件

*硬件交互相关的库、工具和教程。 (翻译出错了? 试试 [英文版](README_EN.md#hardware) 吧~)*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## 图片

*图像处理相关的库。 (翻译出错了? 试试 [英文版](README_EN.md#images) 吧~)*

* [gocv](https://github.com/hybridgroup/gocv) **star:2993** 使用OpenCV 3.3+实现的计算机视觉(ComputerVision)的Go语言包。   [![star > 2000][Awesome]](https://github.com/hybridgroup/gocv)   [![最近一周有更新][Green]](https://github.com/hybridgroup/gocv)   [![godoc][GoDoc]](https://godoc.org/github.com/hybridgroup/gocv)
* [imaging](https://github.com/disintegration/imaging) **star:2957** 简单的Go图像处理包。   [![star > 2000][Awesome]](https://github.com/disintegration/imaging)   [![godoc][GoDoc]](https://godoc.org/github.com/disintegration/imaging)
* [imaginary](https://github.com/h2non/imaginary) **star:2898** 用于图像大小调整的快速、简单的HTTP微服务。   [![star > 2000][Awesome]](https://github.com/h2non/imaginary)   [![godoc][GoDoc]](https://godoc.org/github.com/h2non/imaginary)
* [bild](https://github.com/anthonynsimon/bild) **star:2794** 纯Go语言实现的图像处理算法合集。   [![star > 2000][Awesome]](https://github.com/anthonynsimon/bild)   [![godoc][GoDoc]](https://godoc.org/github.com/anthonynsimon/bild)
* [ln](https://github.com/fogleman/ln) **star:2628** Go实现的3D线艺术（3D Line Art）渲染。   [![star > 2000][Awesome]](https://github.com/fogleman/ln)   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/ln)
* [resize](https://github.com/nfnt/resize) **star:2296** Go实现的使用常用的插值法（interpolation methods）调整图像大小的库。   [![star > 2000][Awesome]](https://github.com/nfnt/resize)   [![最近一年没有更新][Yellow]](https://github.com/nfnt/resize)   [![godoc][GoDoc]](https://godoc.org/github.com/nfnt/resize)
* [gg](https://github.com/fogleman/gg) **star:2168** 纯Go语言实现的2D渲染。   [![star > 2000][Awesome]](https://github.com/fogleman/gg)   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/gg)
* [pt](https://github.com/fogleman/pt) **star:1838** Go实现的路径跟踪（path tracing）引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/pt)
* [svgo](https://github.com/ajstarks/svgo) **star:1435**  Go实现的SVG生成库。   [![godoc][GoDoc]](https://godoc.org/github.com/ajstarks/svgo)
* [smartcrop](https://github.com/muesli/smartcrop) **star:1337** 为任意图片寻找合适的位置进行图片裁剪。   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/smartcrop)
* [gift](https://github.com/disintegration/gift) **star:1302** 图像处理包。   [![godoc][GoDoc]](https://godoc.org/github.com/disintegration/gift)
* [picfit](https://github.com/thoas/picfit) **star:1199** Go实现的图像调整服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/thoas/picfit)
* [go-opencv](https://github.com/lazywei/go-opencv) **star:1158** OpenCV库的Go bindings。   [![godoc][GoDoc]](https://godoc.org/github.com/lazywei/go-opencv)
* [imagick](https://github.com/gographics/imagick) **star:1120**  ImageMagick下MagickWand的C API的Go binding。   [![godoc][GoDoc]](https://godoc.org/github.com/gographics/imagick)
* [geopattern](https://github.com/pravj/geopattern) **star:1053** 由字符串创建漂亮图案的图片生成器。   [![最近一年没有更新][Yellow]](https://github.com/pravj/geopattern)   [![godoc][GoDoc]](https://godoc.org/github.com/pravj/geopattern)
* [bimg](https://github.com/h2non/bimg) **star:896** 使用libvips实现的快速高效的图像处理包。   [![godoc][GoDoc]](https://godoc.org/github.com/h2non/bimg)
* [stegify](https://github.com/DimitarPetrov/stegify) **star:716**  Go实现的LSB隐写（LSB steganography），能够隐藏任何文件到一个图像中。   [![最近一周有更新][Green]](https://github.com/DimitarPetrov/stegify)   [![godoc][GoDoc]](https://godoc.org/github.com/DimitarPetrov/stegify)
* [canvas](https://github.com/tdewolff/canvas) **star:413** 矢量图形到PDF, SVG或光栅图像。   [![godoc][GoDoc]](https://godoc.org/github.com/tdewolff/canvas)
* [mort](https://github.com/aldor007/mort) **star:388** Go语言实现的图像存储和处理服务器。   [![godoc][GoDoc]](https://godoc.org/github.com/aldor007/mort)
* [image2ascii](https://github.com/qeesung/image2ascii) **star:374** 将图像转换为ASCII码。   [![最近一年没有更新][Yellow]](https://github.com/qeesung/image2ascii)   [![godoc][GoDoc]](https://godoc.org/github.com/qeesung/image2ascii)
* [govatar](https://github.com/o1egl/govatar) **star:343** 生成有趣头像的库和CMD工具。   [![godoc][GoDoc]](https://godoc.org/github.com/o1egl/govatar)
* [go-nude](https://github.com/koyachi/go-nude) **star:300** Go语言实现的裸照检测工具。   [![最近一年没有更新][Yellow]](https://github.com/koyachi/go-nude)   [![godoc][GoDoc]](https://godoc.org/github.com/koyachi/go-nude)
* [goimagehash](https://github.com/corona10/goimagehash) **star:271**  图像哈希处理的Go语言包。   [![godoc][GoDoc]](https://godoc.org/github.com/corona10/goimagehash)
* [rez](https://github.com/bamiaux/rez) **star:200** 纯Go语言和SIMD实现的图像大小调整。   [![最近一年没有更新][Yellow]](https://github.com/bamiaux/rez)   [![godoc][GoDoc]](https://godoc.org/github.com/bamiaux/rez)
* [img](https://github.com/hawx/img) **star:133** 图像处理工具的集合。   [![最近一年没有更新][Yellow]](https://github.com/hawx/img)   [![godoc][GoDoc]](https://godoc.org/github.com/hawx/img)
* [darkroom](https://github.com/gojek/darkroom) **star:119** An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.   [![最近一周有更新][Green]](https://github.com/gojek/darkroom)   [![godoc][GoDoc]](https://godoc.org/github.com/gojek/darkroom)
* [go-cairo](https://github.com/ungerik/go-cairo) **star:92**  cairo图形库的Go binding。   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/go-cairo)
* [mergi](https://github.com/noelyahan/mergi) **star:88** 用于图像处理(合并、裁剪、调整大小、水印、动画)的工具和Go库。   [![godoc][GoDoc]](https://godoc.org/github.com/noelyahan/mergi)
* [gltf](https://github.com/qmuntal/gltf) **star:61** 一个高效、健壮的glTF 2.0文件读取、写入和验证器。   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/gltf)
* [go-gd](https://github.com/bolknote/go-gd) **star:52**  GD库的Go binding。   [![最近一年没有更新][Yellow]](https://github.com/bolknote/go-gd)   [![godoc][GoDoc]](https://godoc.org/github.com/bolknote/go-gd)
* [steganography](https://github.com/auyer/steganography) **star:44** 纯Go实现的LSB隐写（LSB steganography）的库。   [![godoc][GoDoc]](https://godoc.org/github.com/auyer/steganography)
* [cameron](https://github.com/aofei/cameron) **star:40** 一个Go语言的头像生成器。   [![godoc][GoDoc]](https://godoc.org/github.com/aofei/cameron)
* [goimghdr](https://github.com/corona10/goimghdr) **star:33** Go语言实现的imghdr模块用于确定文件的图像类型。   [![godoc][GoDoc]](https://godoc.org/github.com/corona10/goimghdr)
* [tga](https://github.com/ftrvxmtrx/tga) **star:26** tga包是一个TARGA图像的解码、编码器。   [![最近一年没有更新][Yellow]](https://github.com/ftrvxmtrx/tga)   [![godoc][GoDoc]](https://godoc.org/github.com/ftrvxmtrx/tga)
* [go-webcolors](https://github.com/jyotiska/go-webcolors) **star:24** Python下webcolors库的Go语言调用。   [![最近一年没有更新][Yellow]](https://github.com/jyotiska/go-webcolors)   [![godoc][GoDoc]](https://godoc.org/github.com/jyotiska/go-webcolors)
* [mpo](https://github.com/donatj/mpo) **star:6** MPO三维照片的解码和转换工具。   [![最近一年没有更新][Yellow]](https://github.com/donatj/mpo)   [![godoc][GoDoc]](https://godoc.org/github.com/donatj/mpo)

## 物联网

*物联网设备编程库。 (翻译出错了? 试试 [英文版](README_EN.md#iot-(internet-of-things)) 吧~)*

* [flogo](https://github.com/tibcosoftware/flogo) **star:1366** Flogo是一个面向物联网边缘应用和集成的开源框架。
* [gatt](https://github.com/paypal/gatt) **star:884** Gatt是一个用于构建低能耗蓝牙外围设备的Go语言包。   [![godoc][GoDoc]](https://godoc.org/github.com/paypal/gatt)
* [gobot](https://github.com/hybridgroup/gobot/)  Gobot是一个用于机器人、物理计算和物联网的框架。
* [mainflux](https://github.com/Mainflux/mainflux) **star:809** 工业物联网消息和设备管理服务器。   [![最近一周有更新][Green]](https://github.com/Mainflux/mainflux)   [![godoc][GoDoc]](https://godoc.org/github.com/Mainflux/mainflux)
* [periph](https://periph.io/)  外围设备I/O与低级板(low-level board)设备接口。
* [devices](https://github.com/goiot/devices) **star:229** 一套用于物联网设备的库，实验性地用于x/exp/io。   [![最近一年没有更新][Yellow]](https://github.com/goiot/devices)   [![godoc][GoDoc]](https://godoc.org/github.com/goiot/devices)
* [connectordb](https://github.com/connectordb/connectordb) **star:200** 自我量化和物联网的开源平台。   [![最近一周有更新][Green]](https://github.com/connectordb/connectordb)   [![godoc][GoDoc]](https://godoc.org/github.com/connectordb/connectordb)
* [sensorbee](https://github.com/sensorbee/sensorbee) **star:191** 轻量级物联网流处理引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/sensorbee/sensorbee)
* [huego](https://github.com/amimof/huego) **star:136** 一个包含广泛的Philips Hue客户端的Go语言库。   [![godoc][GoDoc]](https://godoc.org/github.com/amimof/huego)
* [iot](https://github.com/vaelen/iot/)  IoT是一个实现谷歌物联网核心设备的简单框架。
* [eywa](https://github.com/xcodersun/eywa) **star:44** Eywa是一个用于跟踪连接的设备连接管理器。   [![最近一年没有更新][Yellow]](https://github.com/xcodersun/eywa)   [![godoc][GoDoc]](https://godoc.org/github.com/xcodersun/eywa)

## 作业调度器

*用于作业调度的库。 (翻译出错了? 试试 [英文版](README_EN.md#job-scheduler) 吧~)*

* [gron](https://github.com/roylee0704/gron) **star:692** 使用简单的Go API定义基于时间的任务。 之后Gron的调度程序将运行它们。   [![最近一年没有更新][Yellow]](https://github.com/roylee0704/gron)   [![godoc][GoDoc]](https://godoc.org/github.com/roylee0704/gron)
* [JobRunner](https://github.com/bamzi/jobrunner) **star:659** 智能和功能丰富的cron作业调度程序（包含任务队列和实时监控）。   [![godoc][GoDoc]](https://godoc.org/github.com/bamzi/jobrunner)
* [jobs](https://github.com/albrow/jobs) **star:466** 持久和灵活的后台作业库。   [![最近一年没有更新][Yellow]](https://github.com/albrow/jobs)   [![godoc][GoDoc]](https://godoc.org/github.com/albrow/jobs)
* [scheduler](https://github.com/carlescere/scheduler) **star:319** Cronjobs让调度变得很简单。   [![最近一年没有更新][Yellow]](https://github.com/carlescere/scheduler)   [![godoc][GoDoc]](https://godoc.org/github.com/carlescere/scheduler)
* [clockwerk](http://github.com/onatm/clockwerk)  使用简单、流畅的语法调度作业的Go语言库。
* [go-cron](https://github.com/rk/go-cron) **star:183** 一个Go实现的简单的定时任务库。可以在不同的时间间隔（每秒一次到在每年在特定的日期执行）执行闭包或函数。主要用于web应用和长时间运行的守护进程。   [![godoc][GoDoc]](https://godoc.org/github.com/rk/go-cron)
* [clockwork](https://github.com/whiteShtef/clockwork) **star:97** Go实现的简单直观的作业调度库。   [![godoc][GoDoc]](https://godoc.org/github.com/whiteShtef/clockwork)
* [leprechaun](https://github.com/kilgaloon/leprechaun) **star:61** 支持webhook、crons和经典调度的作业调度程序。   [![godoc][GoDoc]](https://godoc.org/github.com/kilgaloon/leprechaun)

## JSON

*用于JSON处理的库。 (翻译出错了? 试试 [英文版](README_EN.md#json) 吧~)*

* [GJSON](https://github.com/tidwall/gjson) **star:5975** 使用一行代码获取JSON的值。   [![star > 2000][Awesome]](https://github.com/tidwall/gjson)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/gjson)
* [gojson](https://github.com/ChimeraCoder/gojson) **star:2152** 从JSON自动生成Go的结构（struct）定义。   [![star > 2000][Awesome]](https://github.com/ChimeraCoder/gojson)   [![godoc][GoDoc]](https://godoc.org/github.com/ChimeraCoder/gojson)
* [kazaam](https://github.com/Qntfy/kazaam) **star:145** 用于任意JSON文档转换的API。   [![godoc][GoDoc]](https://godoc.org/github.com/Qntfy/kazaam)
* [gojq](https://github.com/elgs/gojq) **star:142** Go语言实现的JSON请求。   [![最近一年没有更新][Yellow]](https://github.com/elgs/gojq)   [![godoc][GoDoc]](https://godoc.org/github.com/elgs/gojq)
* [jsongo](https://github.com/ricardolonga/jsongo) **star:94** 使用Fluent API来更容易地创建Json对象。   [![最近一年没有更新][Yellow]](https://github.com/ricardolonga/jsongo)   [![godoc][GoDoc]](https://godoc.org/github.com/ricardolonga/jsongo)
* [jettison](https://github.com/wI2L/jettison) **star:74** 高性能，无反射的JSON编码器去。   [![最近一周有更新][Green]](https://github.com/wI2L/jettison)   [![godoc][GoDoc]](https://godoc.org/github.com/wI2L/jettison)
* [JSON-to-Go](https://mholt.github.io/json-to-go/)  将JSON转换为Go的结构（struct）。
* [gjo](https://github.com/skanehira/gjo) **star:71** 用于创建JSON对象的小工具。   [![godoc][GoDoc]](https://godoc.org/github.com/skanehira/gjo)
* [JayDiff](https://github.com/yazgazan/jaydiff) **star:63** 用Go编写的JSON比对工具。   [![godoc][GoDoc]](https://godoc.org/github.com/yazgazan/jaydiff)
* [jsonf](https://github.com/miolini/jsonf) **star:54** 用于高亮展示和查询JSON的控制台工具。   [![最近一年没有更新][Yellow]](https://github.com/miolini/jsonf)   [![godoc][GoDoc]](https://godoc.org/github.com/miolini/jsonf)
* [mp](https://github.com/sanbornm/mp) **star:38** 简单的cli电子邮件解析器。它目前接受stdin并输出JSON。   [![最近一年没有更新][Yellow]](https://github.com/sanbornm/mp)   [![godoc][GoDoc]](https://godoc.org/github.com/sanbornm/mp)
* [json2go](https://github.com/m-zajac/json2go) **star:32** 高级JSON去结构转换。提供一个包，该包可以解析多个JSON文档并创建结构体以适应所有这些文档。   [![godoc][GoDoc]](https://godoc.org/github.com/m-zajac/json2go)
* [go-respond](https://github.com/nicklaw5/go-respond) **star:30** 用于处理常见的HTTP JSON响应的Go语言库。   [![godoc][GoDoc]](https://godoc.org/github.com/nicklaw5/go-respond)
* [ajson](https://github.com/spyzhov/ajson) **star:26** 为Go语言开发的包含JSONPath支持的抽象JSON。   [![godoc][GoDoc]](https://godoc.org/github.com/spyzhov/ajson)
* [jsonhal](https://github.com/RichardKnop/jsonhal) **star:9** 让自定义结构（struct）转化为JSON兼容的HAL（Hypertext Application Language）返回数据的简单Go包。   [![最近一年没有更新][Yellow]](https://github.com/RichardKnop/jsonhal)   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/jsonhal)
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) **star:9** Go-JsonError允许我们轻松创建符合JsonApi规范的json响应错误。   [![godoc][GoDoc]](https://godoc.org/github.com/ddymko/go-jsonerror)
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) **star:8** 基于JSON API错误引用的Go bindings。   [![最近一年没有更新][Yellow]](https://github.com/AmuzaTkts/jsonapi-errors)   [![godoc][GoDoc]](https://godoc.org/github.com/AmuzaTkts/jsonapi-errors)
* [ej](https://github.com/lucassscaravelli/ej) **star:3** 简洁地编写和读取来自不同来源的JSON。   [![godoc][GoDoc]](https://godoc.org/github.com/lucassscaravelli/ej)
* [mapslice-json](https://github.com/mickep76/mapslice-json) **star:1** 去MapSlice的有序封送/解封的JSON地图。   [![godoc][GoDoc]](https://godoc.org/github.com/mickep76/mapslice-json)

## 日志记录

*用于生成和处理日志文件的库。 (翻译出错了? 试试 [英文版](README_EN.md#logging) 吧~)*

* [logrus](https://github.com/Sirupsen/logrus) **star:14074** Go的结构化日志操作 。   [![star > 2000][Awesome]](https://github.com/Sirupsen/logrus)   [![最近一周有更新][Green]](https://github.com/Sirupsen/logrus)   [![godoc][GoDoc]](https://godoc.org/github.com/Sirupsen/logrus)
* [zap](https://github.com/uber-go/zap) **star:9129** 快速、结构化、多等级的日志记录。   [![star > 2000][Awesome]](https://github.com/uber-go/zap)   [![最近一周有更新][Green]](https://github.com/uber-go/zap)   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/zap)
* [spew](https://github.com/davecgh/go-spew) **star:3756** 为Go数据结构实现一个漂亮的printer用于帮助调试。   [![star > 2000][Awesome]](https://github.com/davecgh/go-spew)   [![godoc][GoDoc]](https://godoc.org/github.com/davecgh/go-spew)
* [zerolog](https://github.com/rs/zerolog) **star:2998** Zero-allocation JSON日志记录。   [![star > 2000][Awesome]](https://github.com/rs/zerolog)   [![godoc][GoDoc]](https://godoc.org/github.com/rs/zerolog)
* [glog](https://github.com/golang/glog) **star:2484** 为Go提供了多等级日志记录。   [![star > 2000][Awesome]](https://github.com/golang/glog)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/glog)
* [lumberjack](https://github.com/natefinch/lumberjack) **star:1802** 简单的滚动日志，io.WriteCloser的实现。   [![godoc][GoDoc]](https://godoc.org/github.com/natefinch/lumberjack)
* [tail](https://github.com/hpcloud/tail) **star:1727** 努力模拟实现BSD的tail的特性的Go包。   [![godoc][GoDoc]](https://godoc.org/github.com/hpcloud/tail)
* [seelog](https://github.com/cihub/seelog) **star:1438** 具有灵活调度、过滤和格式化的日志功能。   [![最近一年没有更新][Yellow]](https://github.com/cihub/seelog)   [![godoc][GoDoc]](https://godoc.org/github.com/cihub/seelog)
* [log15](https://github.com/inconshreveable/log15) **star:951** 简单、强大的日志操作。   [![godoc][GoDoc]](https://godoc.org/github.com/inconshreveable/log15)
* [log](https://github.com/apex/log) **star:802** Go的结构化日志包。   [![godoc][GoDoc]](https://godoc.org/github.com/apex/log)
* [onelog](https://github.com/francoispqt/onelog) **star:364** Onelog是一个非常简单但非常高效的JSON日志程序。它是所有场景中速度最快的JSON日志程序。而且，它是配置要求最低的日志记录器之一。   [![最近一年没有更新][Yellow]](https://github.com/francoispqt/onelog)   [![godoc][GoDoc]](https://godoc.org/github.com/francoispqt/onelog)
* [logxi](https://github.com/mgutz/logxi) **star:343** 12-factor app的日志程序，快速且让人高兴地使用。   [![godoc][GoDoc]](https://godoc.org/github.com/mgutz/logxi)
* [log](https://github.com/go-playground/log) **star:273** Go的简单、可配置和可伸缩的结构化日志。   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/log)
* [logutils](https://github.com/hashicorp/logutils) **star:270** Go的用于更好地进行日志操作的实用程序，继承了标准日志库。   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/logutils)
* [go-logger](https://github.com/apsdehal/go-logger) **star:248** 简单的日志程序的 Go 程序，与级别处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/apsdehal/go-logger)
* [logger](https://github.com/azer/logger) **star:138** Go的精简日志库。   [![godoc][GoDoc]](https://godoc.org/github.com/azer/logger)
* [xlog](https://github.com/rs/xlog) **star:133** 针对'net/context`实现的结构化的记录器，用于HTTP处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/rs/xlog)
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) **star:128** RollingWriter是一个自动循环的io.Writer的实现,带有多种策略以提供日志文件循环(rotation)。   [![godoc][GoDoc]](https://godoc.org/github.com/arthurkiller/rollingWriter)
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) **star:112** 支持日志多等级、分类和过滤的高性能日志记录。可以发送过滤后的日志消息到各种目标(如控制台，网络，邮件)。   [![最近一年没有更新][Yellow]](https://github.com/go-ozzo/ozzo-log)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ozzo/ozzo-log)   [![包含中文文档][CN]](https://github.com/go-ozzo/ozzo-log)
* [log-voyage](https://github.com/firstrow/logvoyage) **star:84** 用Go编写的功能齐全的日志写入saas。   [![最近一年没有更新][Yellow]](https://github.com/firstrow/logvoyage)   [![godoc][GoDoc]](https://godoc.org/github.com/firstrow/logvoyage)
* [glg](https://github.com/kpango/glg) **star:67** glg是一个简单而快速的Go日志库。   [![godoc][GoDoc]](https://godoc.org/github.com/kpango/glg)
* [stdlog](https://github.com/alexcesaro/log) **star:42** Stdlog是一个面向对象的库，提供了多等级日志记录。它对cron任务非常有用。   [![最近一年没有更新][Yellow]](https://github.com/alexcesaro/log)   [![godoc][GoDoc]](https://godoc.org/github.com/alexcesaro/log)
* [gologger](https://github.com/sadlil/gologger) **star:38** 为Go提供方便简单的日志操作; 在彩色控制台，简单控制台，文件或Elasticsearch上。   [![最近一年没有更新][Yellow]](https://github.com/sadlil/gologger)   [![godoc][GoDoc]](https://godoc.org/github.com/sadlil/gologger)   [![归档项目][Archived]](https://github.com/sadlil/gologger)
* [logex](https://github.com/chzyer/logex) **star:35** 由标准日志库封装的Go日志库，支持跟踪和多等级。   [![最近一年没有更新][Yellow]](https://github.com/chzyer/logex)   [![godoc][GoDoc]](https://godoc.org/github.com/chzyer/logex)
* [go-log](https://github.com/ian-kent/go-log) **star:34** Log4j的Go语言。   [![最近一年没有更新][Yellow]](https://github.com/ian-kent/go-log)   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/go-log)
* [go-cronowriter](https://github.com/utahta/go-cronowriter) **star:26** 基于当前日期和时间的自动日志文件写入工具，类似cronolog。   [![godoc][GoDoc]](https://godoc.org/github.com/utahta/go-cronowriter)
* [go-log](https://github.com/siddontang/go-log) **star:26** 支持多等级和多处理程序的日志库。   [![最近一年没有更新][Yellow]](https://github.com/siddontang/go-log)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-log)
* [logrusly](https://github.com/sebest/logrusly) **star:25** [logrus](https://github.com/sirupsen/logrus)的插件，将错误信息发送到[Loggly](https://www.loggly.com/)。   [![最近一年没有更新][Yellow]](https://github.com/sebest/logrusly)   [![godoc][GoDoc]](https://godoc.org/github.com/sebest/logrusly)
* [log](https://github.com/teris-io/log) **star:23** Go的结构化日志接口，清晰地将日志facade与其实现(implementation)分离开来。   [![最近一年没有更新][Yellow]](https://github.com/teris-io/log)   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/log)
* [distillog](https://github.com/amoghe/distillog) **star:22** distilled日志记录(可以将其视为stdlib +日志)。   [![最近一年没有更新][Yellow]](https://github.com/amoghe/distillog)   [![godoc][GoDoc]](https://godoc.org/github.com/amoghe/distillog)
* [journald](https://github.com/ssgreg/journald) **star:22**  Go实现systemd Journal的原生API用于日志记录。   [![最近一年没有更新][Yellow]](https://github.com/ssgreg/journald)   [![godoc][GoDoc]](https://godoc.org/github.com/ssgreg/journald)
* [mlog](https://github.com/jbrodriguez/mlog) **star:19** 简单的go日志模块，有5个级别，可选循环(rotation)日志文件记录功能和stdout/stderr输出。   [![最近一年没有更新][Yellow]](https://github.com/jbrodriguez/mlog)   [![godoc][GoDoc]](https://godoc.org/github.com/jbrodriguez/mlog)
* [gomol](https://github.com/aphistic/gomol) **star:16** 为Go实现可多方式输出、结构化日志, 并可扩展日志输出方式。   [![最近一年没有更新][Yellow]](https://github.com/aphistic/gomol)   [![godoc][GoDoc]](https://godoc.org/github.com/aphistic/gomol)
* [gone/log](https://github.com/One-com/gone/tree/master/log)  快速、可扩展、功能齐全、std-lib源兼容的日志库。
* [logdump](https://github.com/ewwwwwqm/logdump) **star:9** 用于多等级级日志记录的包。   [![最近一年没有更新][Yellow]](https://github.com/ewwwwwqm/logdump)   [![godoc][GoDoc]](https://godoc.org/github.com/ewwwwwqm/logdump)
* [go-log](https://github.com/subchen/go-log) **star:9** Go实现的简单且可配置的日志工具，并带有多等级、日志格式化和日志写入工具。   [![最近一年没有更新][Yellow]](https://github.com/subchen/go-log)   [![godoc][GoDoc]](https://godoc.org/github.com/subchen/go-log)
* [glo](https://github.com/lajosbencz/glo) **star:9** 参照PHP的Monolog实现的具有相同日志等级的Go日志库。   [![最近一年没有更新][Yellow]](https://github.com/lajosbencz/glo)   [![godoc][GoDoc]](https://godoc.org/github.com/lajosbencz/glo)
* [logrusiowriter](https://github.com/cabify/logrusiowriter) **star:8** io。作者的实现使用[logrus](https://github.com/sirupsen/logrus) logger。   [![godoc][GoDoc]](https://godoc.org/github.com/cabify/logrusiowriter)
* [logmatic](https://github.com/borderstech/logmatic) **star:6** Go的彩色日志记录器，带有可配置的日志级别。   [![最近一年没有更新][Yellow]](https://github.com/borderstech/logmatic)   [![godoc][GoDoc]](https://godoc.org/github.com/borderstech/logmatic)
* [log](https://github.com/aerogo/log) **star:6** 一个O(1)日志系统，允许您将一个日志连接到多个日志写入(例如stdout、文件和TCP连接)。   [![godoc][GoDoc]](https://godoc.org/github.com/aerogo/log)
* [xlog](https://github.com/xfxdev/xlog) **star:6** 插件架构和灵活的日志系统，带有多级别、多日志目标和自定义日志格式。   [![最近一年没有更新][Yellow]](https://github.com/xfxdev/xlog)   [![godoc][GoDoc]](https://godoc.org/github.com/xfxdev/xlog)
* [logo](https://github.com/mbndr/logo) **star:5** Go的日志工具，可配置的日志写入器。   [![最近一年没有更新][Yellow]](https://github.com/mbndr/logo)   [![godoc][GoDoc]](https://godoc.org/github.com/mbndr/logo)
* [go-log](https://github.com/pieterclaerhout/go-log) **star:3** 具有strack跟踪、对象转储和可选时间戳的日志记录库。   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-log)

## 机器学习

*机器学习库。 (翻译出错了? 试试 [英文版](README_EN.md#machine-learning) 吧~)*

* [GoLearn](https://github.com/sjwhitworth/golearn) **star:7031** 通用机器学习库。   [![star > 2000][Awesome]](https://github.com/sjwhitworth/golearn)   [![godoc][GoDoc]](https://godoc.org/github.com/sjwhitworth/golearn)   [![包含中文文档][CN]](https://github.com/sjwhitworth/golearn)
* [gorgonia](https://github.com/gorgonia/gorgonia) **star:3193** 基于图形（graph-based）的计算库，如Theano：它为构建各种机器学习和神经网络算法提供了基本框架。   [![star > 2000][Awesome]](https://github.com/gorgonia/gorgonia)   [![godoc][GoDoc]](https://godoc.org/github.com/gorgonia/gorgonia)
* [tfgo](https://github.com/galeone/tfgo) **star:1317** 易于使用的Tensorflow bindings:简化了官方Tensorflow Go bindings的使用。在Go中定义计算图形，在Python中加载和执行训练的模型。   [![godoc][GoDoc]](https://godoc.org/github.com/galeone/tfgo)
* [goml](https://github.com/cdipaolo/goml) **star:1080** 在线机器学习。   [![godoc][GoDoc]](https://godoc.org/github.com/cdipaolo/goml)
* [gosseract](https://github.com/otiai10/gosseract) **star:1071** 使用c++的Tesseract库实现的OCR。   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/gosseract)
* [gorse](https://github.com/zhenghaoz/gorse) **star:927** 基于协同过滤的离线推荐系统后端。   [![godoc][GoDoc]](https://godoc.org/github.com/zhenghaoz/gorse)   [![包含中文文档][CN]](https://github.com/zhenghaoz/gorse)
* [CloudForest](https://github.com/ryanbressler/CloudForest) **star:667** 快速、灵活、多线程集成的决策树，用于机器学习。   [![最近一年没有更新][Yellow]](https://github.com/ryanbressler/CloudForest)   [![godoc][GoDoc]](https://godoc.org/github.com/ryanbressler/CloudForest)
* [eaopt](https://github.com/MaxHalford/eaopt) **star:665** 一个进化优化（evolutionary optimization）库。   [![godoc][GoDoc]](https://godoc.org/github.com/MaxHalford/eaopt)
* [bayesian](https://github.com/jbrukh/bayesian) **star:654** Go的朴素贝叶斯分类。   [![godoc][GoDoc]](https://godoc.org/github.com/jbrukh/bayesian)
* [gobrain](https://github.com/goml/gobrain) **star:433** 用 Go 编写的神经网络库。   [![godoc][GoDoc]](https://godoc.org/github.com/goml/gobrain)
* [ocrserver](https://github.com/otiai10/ocrserver) **star:271** 一个简单的OCR API服务器，非常容易地使用Docker和Heroku部署。   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/ocrserver)
* [regommend](https://github.com/muesli/regommend) **star:265** 推荐和协同过滤引擎。   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/regommend)
* [go-deep](https://github.com/patrikeh/go-deep) **star:255** 一个功能丰富的神经网络库 。   [![godoc][GoDoc]](https://godoc.org/github.com/patrikeh/go-deep)
* [onnx-go](https://github.com/owulveryck/onnx-go) **star:247** Go Interface， 用于开放式神经网络交换(Open Neural Network Exchange)。   [![godoc][GoDoc]](https://godoc.org/github.com/owulveryck/onnx-go)
* [go-galib](https://github.com/thoj/go-galib) **star:177** 用Go编写的遗传算法库。   [![最近一年没有更新][Yellow]](https://github.com/thoj/go-galib)   [![godoc][GoDoc]](https://godoc.org/github.com/thoj/go-galib)
* [goRecommend](https://github.com/timkaye11/goRecommend) **star:155** 用Go编写的推荐算法库。   [![最近一年没有更新][Yellow]](https://github.com/timkaye11/goRecommend)   [![godoc][GoDoc]](https://godoc.org/github.com/timkaye11/goRecommend)
* [shield](https://github.com/eaigner/shield) **star:129** 贝叶斯文本分类器，具有灵活的tokenizers和存储后端。   [![最近一周有更新][Green]](https://github.com/eaigner/shield)   [![godoc][GoDoc]](https://godoc.org/github.com/eaigner/shield)
* [Goptuna](https://github.com/c-bata/goptuna) **star:118** Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/goptuna)
* [go-fann](https://github.com/white-pony/go-fann) **star:103** 快速人工神经网络(FANN)库的Go bindings。   [![最近一年没有更新][Yellow]](https://github.com/white-pony/go-fann)   [![godoc][GoDoc]](https://godoc.org/github.com/white-pony/go-fann)
* [goga](https://github.com/tomcraven/goga) **star:86** Go的遗传算法库。   [![最近一年没有更新][Yellow]](https://github.com/tomcraven/goga)   [![godoc][GoDoc]](https://godoc.org/github.com/tomcraven/goga)
* [libsvm](https://github.com/datastream/libsvm) **star:64** 基于LIBSVM 3.14实现。   [![最近一年没有更新][Yellow]](https://github.com/datastream/libsvm)   [![godoc][GoDoc]](https://godoc.org/github.com/datastream/libsvm)
* [neural-go](https://github.com/schuyler/neural-go) **star:61** 多层感知器网络在Go中的实现，使用反向传播算法进行训练。   [![最近一年没有更新][Yellow]](https://github.com/schuyler/neural-go)   [![godoc][GoDoc]](https://godoc.org/github.com/schuyler/neural-go)
* [go-pr](https://github.com/daviddengcn/go-pr) **star:59** Go编写的模式识别包。   [![最近一年没有更新][Yellow]](https://github.com/daviddengcn/go-pr)   [![godoc][GoDoc]](https://godoc.org/github.com/daviddengcn/go-pr)
* [gonet](https://github.com/dathoangnd/gonet) **star:57** 用于围棋的神经网络。   [![godoc][GoDoc]](https://godoc.org/github.com/dathoangnd/gonet)
* [neat](https://github.com/jinyeom/neat) **star:56** 即插即用的并行Go框架，用于增强拓扑的神经进化(NeuroEvolution of Augmenting Topologies)。   [![最近一年没有更新][Yellow]](https://github.com/jinyeom/neat)   [![godoc][GoDoc]](https://godoc.org/github.com/jinyeom/neat)   [![归档项目][Archived]](https://github.com/jinyeom/neat)
* [goscore](https://github.com/asafschers/goscore) **star:45**  为预言模型标记语言（PMML）实现的评分API。   [![godoc][GoDoc]](https://godoc.org/github.com/asafschers/goscore)
* [golinear](https://github.com/danieldk/golinear) **star:39**  Go实现的liblinear bindings。   [![最近一年没有更新][Yellow]](https://github.com/danieldk/golinear)   [![godoc][GoDoc]](https://godoc.org/github.com/danieldk/golinear)
* [fonet](https://github.com/Fontinalis/fonet) **star:36** 一个用Go编写的深度神经网络库。   [![godoc][GoDoc]](https://godoc.org/github.com/Fontinalis/fonet)
* [Varis](https://github.com/Xamber/Varis) **star:28** Go实现的神经网络。   [![最近一年没有更新][Yellow]](https://github.com/Xamber/Varis)   [![godoc][GoDoc]](https://godoc.org/github.com/Xamber/Varis)
* [godist](https://github.com/e-dard/godist) **star:25** 各种概率分布，以及相关的method。   [![最近一年没有更新][Yellow]](https://github.com/e-dard/godist)   [![godoc][GoDoc]](https://godoc.org/github.com/e-dard/godist)
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) **star:22** Go实现的k-modes和k-prototypes聚类算法。   [![最近一年没有更新][Yellow]](https://github.com/e-XpertSolutions/go-cluster)   [![godoc][GoDoc]](https://godoc.org/github.com/e-XpertSolutions/go-cluster)
* [probab](https://github.com/ThePaw/probab) **star:12** 概率分布函数。贝叶斯推理。使用Go写的。   [![最近一年没有更新][Yellow]](https://github.com/ThePaw/probab)   [![godoc][GoDoc]](https://godoc.org/github.com/ThePaw/probab)
* [evoli](https://github.com/khezen/evoli) **star:9** 遗传算法（Genetic Algorithm）和粒子群优化（Particle Swarm Optimization）库。   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/evoli)
* [GoMind](https://github.com/surenderthakran/gomind) **star:7** 一个简单的神经网络库。   [![最近一年没有更新][Yellow]](https://github.com/surenderthakran/gomind)   [![godoc][GoDoc]](https://godoc.org/github.com/surenderthakran/gomind)
* [randomforest](https://github.com/malaschitz/randomForest) **star:3** 容易使用随机森林库去。   [![godoc][GoDoc]](https://godoc.org/github.com/malaschitz/randomForest)

## 消息

*实现消息传递系统的库。 (翻译出错了? 试试 [英文版](README_EN.md#messaging) 吧~)*

* [sarama](https://github.com/Shopify/sarama) **star:5460**  Apache Kafka的Go库。   [![star > 2000][Awesome]](https://github.com/Shopify/sarama)   [![最近一周有更新][Green]](https://github.com/Shopify/sarama)   [![godoc][GoDoc]](https://godoc.org/github.com/Shopify/sarama)
* [gorush](https://github.com/appleboy/gorush) **star:4209** 使用[APNs2](https://github.com/sideshow/apns2)和谷歌[GCM](https://github.com/google/go-gcm)推送通知服务器。   [![star > 2000][Awesome]](https://github.com/appleboy/gorush)   [![最近一周有更新][Green]](https://github.com/appleboy/gorush)   [![godoc][GoDoc]](https://godoc.org/github.com/appleboy/gorush)
* [Centrifugo](https://github.com/centrifugal/centrifugo) **star:4104** 实时消息(Websockets或SockJS)服务器。   [![star > 2000][Awesome]](https://github.com/centrifugal/centrifugo)   [![最近一周有更新][Green]](https://github.com/centrifugal/centrifugo)   [![godoc][GoDoc]](https://godoc.org/github.com/centrifugal/centrifugo)
* [machinery](https://github.com/RichardKnop/machinery) **star:3880** 基于分布式消息传递的异步任务/作业队列。   [![star > 2000][Awesome]](https://github.com/RichardKnop/machinery)   [![最近一周有更新][Green]](https://github.com/RichardKnop/machinery)   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/machinery)
* [go-socket.io](https://github.com/googollee/go-socket.io) **star:3281** go的socket.io库，一个实时应用程序框架。   [![star > 2000][Awesome]](https://github.com/googollee/go-socket.io)   [![最近一周有更新][Green]](https://github.com/googollee/go-socket.io)   [![godoc][GoDoc]](https://godoc.org/github.com/googollee/go-socket.io)
* [NATS Go Client](https://github.com/nats-io/nats) **star:2700** 轻量级和高性能的发布-订阅(publish-subscribe)和分布式队列消息传递系统——这是一个Go库。   [![star > 2000][Awesome]](https://github.com/nats-io/nats)   [![godoc][GoDoc]](https://godoc.org/github.com/nats-io/nats)
* [APNs2](https://github.com/sideshow/apns2) **star:2263** HTTP / 2苹果消息推送provider——发送推送消息到iOS, tvOS, Safari和OSX应用。   [![star > 2000][Awesome]](https://github.com/sideshow/apns2)   [![godoc][GoDoc]](https://godoc.org/github.com/sideshow/apns2)
* [Benthos](https://github.com/Jeffail/benthos) **star:2244** 一系列协议之间的消息流桥接。   [![star > 2000][Awesome]](https://github.com/Jeffail/benthos)   [![最近一周有更新][Green]](https://github.com/Jeffail/benthos)   [![godoc][GoDoc]](https://godoc.org/github.com/Jeffail/benthos)
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) **star:1893** gopush-cluster是一个gopush服务器集群。   [![最近一年没有更新][Yellow]](https://github.com/Terry-Mao/gopush-cluster)   [![godoc][GoDoc]](https://godoc.org/github.com/Terry-Mao/gopush-cluster)   [![包含中文文档][CN]](https://github.com/Terry-Mao/gopush-cluster)
* [Mercure](https://github.com/dunglas/mercure) **star:1882** 使用Mercure协议分派服务器发送(server-sent)更新的服务器和库(构建在服务器发送事件之上)。   [![godoc][GoDoc]](https://godoc.org/github.com/dunglas/mercure)
* [melody](https://github.com/olahol/melody) **star:1758** 处理websocket session的极简框架，包括广播和自动ping/pong处理。   [![godoc][GoDoc]](https://godoc.org/github.com/olahol/melody)
* [go-nsq](https://github.com/nsqio/go-nsq) **star:1598** NSQ的官方Go包。   [![godoc][GoDoc]](https://godoc.org/github.com/nsqio/go-nsq)
* [mangos](https://github.com/go-mangos/mangos) **star:1538** Nanomsg(“可伸缩协议”)的纯go实现,具有传输互操作性。   [![godoc][GoDoc]](https://godoc.org/github.com/go-mangos/mangos)   [![归档项目][Archived]](https://github.com/go-mangos/mangos)
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) **star:1141** Redis支持的统一推送服务, 用于服务端向移动设备的消息通知。   [![godoc][GoDoc]](https://godoc.org/github.com/uniqush/uniqush-push)
* [zmq4](https://github.com/pebbe/zmq4) **star:836** ZeroMQ的Go interface第4版。也可用于[第3版](https://github.com/pebbe/zmq3)和[第2版](https://github.com/pebbe/zmq2)。   [![godoc][GoDoc]](https://godoc.org/github.com/pebbe/zmq4)
* [Gollum](https://github.com/trivago/gollum) **star:834** 一个n:m多路复用器(n:m multiplexer)，收集不同来源的消息并将其广播到一组目的地。   [![godoc][GoDoc]](https://godoc.org/github.com/trivago/gollum)
* [Beaver](https://github.com/Clivern/Beaver) **star:814** 一个实时消息服务器，可用于在web和手机app端构建一个可伸缩的应用内通知，多人游戏，聊天应用。   [![最近一周有更新][Green]](https://github.com/Clivern/Beaver)   [![godoc][GoDoc]](https://godoc.org/github.com/Clivern/Beaver)
* [EventBus](https://github.com/asaskevich/EventBus) **star:651** 具有异步兼容性的轻量级事件总线。   [![godoc][GoDoc]](https://godoc.org/github.com/asaskevich/EventBus)
* [golongpoll](https://github.com/jcuga/golongpoll) **star:446** HTTP longpoll服务器库，使web发布-订阅变得简单。   [![最近一周有更新][Green]](https://github.com/jcuga/golongpoll)   [![godoc][GoDoc]](https://godoc.org/github.com/jcuga/golongpoll)
* [dbus](https://github.com/godbus/dbus) **star:428** D-Bus的Go bindings。   [![godoc][GoDoc]](https://godoc.org/github.com/godbus/dbus)
* [emitter](https://github.com/olebedev/emitter) **star:344** 使用Go的方式发出事件, 带有通配符、谓词、取消可能性和许多其他优点。   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/emitter)
* [Glue](https://github.com/desertbit/glue) **star:333** 健壮的Go和Javascript Socket库(替代Socket.io)。   [![godoc][GoDoc]](https://godoc.org/github.com/desertbit/glue)
* [pubsub](https://github.com/tuxychandru/pubsub) **star:309** 简单的pubsub的go包。   [![godoc][GoDoc]](https://godoc.org/github.com/tuxychandru/pubsub)
* [guble](https://github.com/smancke/guble) **star:142** 使用推送通知服务(谷歌Firebase云消息、苹果推送通知服务、SMS)的消息服务器, 支持websockets,REST API，并具有分布式操作和消息持久性。   [![最近一年没有更新][Yellow]](https://github.com/smancke/guble)   [![godoc][GoDoc]](https://godoc.org/github.com/smancke/guble)
* [Bus](https://github.com/mustafaturan/bus) **star:140** 内部通信的最小消息总线实现。   [![godoc][GoDoc]](https://godoc.org/github.com/mustafaturan/bus)
* [rabtap](https://github.com/jandelgado/rabtap) **star:109** RabbitMQ的瑞士军刀cli应用。   [![godoc][GoDoc]](https://godoc.org/github.com/jandelgado/rabtap)
* [oplog](https://github.com/dailymotion/oplog) **star:102** 用于REST api的通用oplog/replication系统。   [![最近一年没有更新][Yellow]](https://github.com/dailymotion/oplog)   [![godoc][GoDoc]](https://godoc.org/github.com/dailymotion/oplog)
* [messagebus](https://github.com/vardius/message-bus) **star:98** messagebus是一个Go的简单异步消息总线，非常适合在执行事件sourcing、CQRS和DDD时用作事件总线。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/message-bus)
* [rabbus](https://github.com/rafaeljesus/rabbus) **star:69** amqp exchanges和队列上的一个小工具。   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/rabbus)
* [drone-line](https://github.com/appleboy/drone-line) **star:67** 使用二进制、docker或Drone CI发送[Line](https://at.line.me/en)通知。   [![godoc][GoDoc]](https://godoc.org/github.com/appleboy/drone-line)
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) **star:58** RapidMQ是用于管理本地消息队列的轻量且可靠的库。   [![最近一年没有更新][Yellow]](https://github.com/sybrexsys/RapidMQ)   [![godoc][GoDoc]](https://godoc.org/github.com/sybrexsys/RapidMQ)
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) **star:57** 一个围绕NSQ topic和channel的小工具。   [![最近一年没有更新][Yellow]](https://github.com/rafaeljesus/nsq-event-bus)   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/nsq-event-bus)
* [go-notify](https://github.com/TheCreeper/go-notify) **star:48** 原生的freedesktop通知规范实现。   [![最近一年没有更新][Yellow]](https://github.com/TheCreeper/go-notify)   [![godoc][GoDoc]](https://godoc.org/github.com/TheCreeper/go-notify)
* [hub](https://github.com/leandro-lugaresi/hub) **star:48** 适用于Go应用程序的消息/事件中心，使用publish/subscribe模式，并支持别名(类似rabbitMQ exchanges)。   [![godoc][GoDoc]](https://godoc.org/github.com/leandro-lugaresi/hub)
* [Commander](https://github.com/jeroenrinzema/commander) **star:40** 高级事件驱动的消费者/生产者(consumer/producer)，支持各种“方言”，如Apache Kafka。   [![godoc][GoDoc]](https://godoc.org/github.com/jeroenrinzema/commander)
* [event](https://github.com/agoalofalife/event) **star:33** 观察者模式的实现。   [![最近一年没有更新][Yellow]](https://github.com/agoalofalife/event)   [![godoc][GoDoc]](https://godoc.org/github.com/agoalofalife/event)
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) **star:13** 用于Viessmann Vitotrol web服务的客户端库。   [![godoc][GoDoc]](https://godoc.org/github.com/maxatome/go-vitotrol)
* [redisqueue](https://github.com/robinjoseph08/redisqueue) **star:11** 基于Redis streams的队列的生产者和消费者。   [![godoc][GoDoc]](https://godoc.org/github.com/robinjoseph08/redisqueue)
* [jazz](https://github.com/socifi/jazz) **star:9** 一个简单的RabbitMQ抽象层，用于队列管理和消息的发布和消费。   [![godoc][GoDoc]](https://godoc.org/github.com/socifi/jazz)
* [gaurun-client](https://github.com/osamingo/gaurun-client) **star:8** 用Go编写的Gaurun客户端。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/gaurun-client)
* [ami](https://github.com/kak-tus/ami) **star:6** 基于Redis集群流的客户端到可靠队列。   [![最近一周有更新][Green]](https://github.com/kak-tus/ami)   [![godoc][GoDoc]](https://godoc.org/github.com/kak-tus/ami)
* [rmqconn](https://github.com/sbabiv/rmqconn) **star:3** RabbitMQ重新连接。amqp.Connection和amqp.Dial之上的Wrapper。允许在强制调用Close()方法关闭连接之前重新连接。   [![godoc][GoDoc]](https://godoc.org/github.com/sbabiv/rmqconn)

## 微软办公软件

* [unioffice](https://github.com/unidoc/unioffice) **star:2127** 用于创建和处理Office Word (.docx)、Excel (.xlsx)和Powerpoint (.pptx)文档的纯go库。   [![star > 2000][Awesome]](https://github.com/unidoc/unioffice)   [![最近一周有更新][Green]](https://github.com/unidoc/unioffice)   [![godoc][GoDoc]](https://godoc.org/github.com/unidoc/unioffice)

### Microsoft Excel

*用于操作Microsoft Excel的库。 (翻译出错了? 试试 [英文版](README_EN.md#microsoft-excel) 吧~)*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) **star:5788** 用于读写Microsoft Excel™(XLSX)文件的Go语言库。   [![star > 2000][Awesome]](https://github.com/360EntSecGroup-Skylar/excelize)   [![最近一周有更新][Green]](https://github.com/360EntSecGroup-Skylar/excelize)   [![godoc][GoDoc]](https://godoc.org/github.com/360EntSecGroup-Skylar/excelize)
* [xlsx](https://github.com/tealeg/xlsx) **star:3928** 用以简化在Go程序中读取使用最新版本Microsoft Excel的XML格式文件的库。   [![star > 2000][Awesome]](https://github.com/tealeg/xlsx)   [![最近一周有更新][Green]](https://github.com/tealeg/xlsx)   [![godoc][GoDoc]](https://godoc.org/github.com/tealeg/xlsx)
* [xlsx](https://github.com/plandem/xlsx) **star:106** 在Go程序以快速和安全的方式读取/更新现有的Microsoft Excel文件。   [![godoc][GoDoc]](https://godoc.org/github.com/plandem/xlsx)
* [go-excel](https://github.com/szyhf/go-excel) **star:70** 一个简单轻便的阅读器，可以将类关系型数据库(relate-db-like)的excel作为表来读取。   [![godoc][GoDoc]](https://godoc.org/github.com/szyhf/go-excel)
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) **star:15** libxlsxwriter的Go binding, 用于编写XLSX (Microsoft Excel)文件。   [![最近一年没有更新][Yellow]](https://github.com/fterrag/goxlsxwriter)   [![godoc][GoDoc]](https://godoc.org/github.com/fterrag/goxlsxwriter)

## 杂项

### 依赖注入

*用于处理依赖项注入的库。 (翻译出错了? 试试 [英文版](README_EN.md#dependency-injection) 吧~)*

* [dig](https://github.com/uber-go/dig) **star:1294** 一个基于反射的Go依赖注入工具包。   [![最近一周有更新][Green]](https://github.com/uber-go/dig)   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/dig)
* [fx](https://github.com/uber-go/fx) **star:1188** 基于依赖注入的Go应用程序框架(构建在dig之上)。   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/fx)
* [container](https://github.com/golobby/container) **star:77** 一个强大的IoC容器，具有流畅且易于使用的接口。   [![godoc][GoDoc]](https://godoc.org/github.com/golobby/container)
* [inject](https://github.com/defval/inject) **star:53** 一个基于反射的依赖注入容器，具有简单的接口。   [![godoc][GoDoc]](https://godoc.org/github.com/defval/inject)   [![归档项目][Archived]](https://github.com/defval/inject)
* [dingo](https://github.com/i-love-flamingo/dingo) **star:41** 基于Guice的Go依赖注入工具包。   [![godoc][GoDoc]](https://godoc.org/github.com/i-love-flamingo/dingo)
* [alice](https://github.com/magic003/alice) **star:38** Go的外挂的依赖注入容器。   [![最近一年没有更新][Yellow]](https://github.com/magic003/alice)   [![godoc][GoDoc]](https://godoc.org/github.com/magic003/alice)
* [wire](https://github.com/Fs02/wire) **star:29** 适用于Go的严格运行时依赖注入(Strict Runtime Dependency Injection)。   [![godoc][GoDoc]](https://godoc.org/github.com/Fs02/wire)
* [linker](https://github.com/logrange/linker) **star:21** A reflection based dependency injection and inversion of control library with components lifecycle support.   [![godoc][GoDoc]](https://godoc.org/github.com/logrange/linker)
* [gocontainer](https://github.com/vardius/gocontainer) **star:12** 简单的依赖注入容器。   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/gocontainer)

### 项目布局

*用于组织项目的非正式模式集。 (翻译出错了? 试试 [英文版](README_EN.md#project-layout) 吧~)*

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) **star:13531** Go生态系统中历史和新兴的项目布局模式集合。   [![star > 2000][Awesome]](https://github.com/golang-standards/project-layout)
* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) **star:559** 应用程序样板和应用现代实践的例子。   [![godoc][GoDoc]](https://godoc.org/github.com/sagikazarmark/modern-go-application)
* [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) **star:323** 遵循生产最佳实践快速启动项目的Go应用程序样板模板。   [![最近一周有更新][Green]](https://github.com/lacion/cookiecutter-golang)   [![godoc][GoDoc]](https://godoc.org/github.com/lacion/cookiecutter-golang)
* [scaffold](https://github.com/catchplay/scaffold) **star:58** 快速生成Go项目布局的脚手架。让您专注于已实现的业务逻辑。   [![最近一年没有更新][Yellow]](https://github.com/catchplay/scaffold)   [![godoc][GoDoc]](https://godoc.org/github.com/catchplay/scaffold)
* [go-sample](https://github.com/zitryss/go-sample) **star:45** 带有实际代码的Go应用程序项目的示例布局。   [![最近一年没有更新][Yellow]](https://github.com/zitryss/go-sample)   [![godoc][GoDoc]](https://godoc.org/github.com/zitryss/go-sample)

### 字符串

*处理字符串的库。 (翻译出错了? 试试 [英文版](README_EN.md#strings) 吧~)*

* [xstrings](https://github.com/huandu/xstrings) **star:718** 从其他语言移植的有用字符串函数合集。   [![godoc][GoDoc]](https://godoc.org/github.com/huandu/xstrings)
* [strutil](https://github.com/ozgio/strutil) **star:85** 字符串处理工具。   [![godoc][GoDoc]](https://godoc.org/github.com/ozgio/strutil)

*这些库之所以放在这里，是因为不适合放在其他分类。 (翻译出错了? 试试 [英文版](README_EN.md#strings) 吧~)*

* [gopsutil](https://github.com/shirou/gopsutil) **star:4610** 用于检索进程和系统利用率(CPU、内存、磁盘等)的跨平台的库。   [![star > 2000][Awesome]](https://github.com/shirou/gopsutil)   [![最近一周有更新][Green]](https://github.com/shirou/gopsutil)   [![godoc][GoDoc]](https://godoc.org/github.com/shirou/gopsutil)
* [archiver](https://github.com/mholt/archiver) **star:2741** 用于生成和解压.zip和.tar.gz文档的库和命令。   [![star > 2000][Awesome]](https://github.com/mholt/archiver)   [![godoc][GoDoc]](https://godoc.org/github.com/mholt/archiver)
* [gosms](https://github.com/haxpax/gosms) **star:1271** Go编写的私人的本地短信网关，可以用来发送短信。   [![最近一年没有更新][Yellow]](https://github.com/haxpax/gosms)   [![godoc][GoDoc]](https://godoc.org/github.com/haxpax/gosms)
* [go-resiliency](https://github.com/eapache/go-resiliency) **star:978**  Go语言弹性模式(resiliency pattern)。   [![godoc][GoDoc]](https://godoc.org/github.com/eapache/go-resiliency)
* [gofakeit](https://github.com/brianvoe/gofakeit) **star:833** 用go编写的随机数据生成器。   [![godoc][GoDoc]](https://godoc.org/github.com/brianvoe/gofakeit)
* [base64Captcha](https://github.com/mojocn/base64Captcha) **star:779** base64Captcha支持数字，字母，算术，音频和混合模式的验证码。   [![最近一周有更新][Green]](https://github.com/mojocn/base64Captcha)   [![godoc][GoDoc]](https://godoc.org/github.com/mojocn/base64Captcha)   [![包含中文文档][CN]](https://github.com/mojocn/base64Captcha)
* [go-openapi](https://github.com/go-openapi)  用于解析和使用开放api模式(open-api schemas)的包的集合。
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) **star:774** Go语言的通用对象池。   [![godoc][GoDoc]](https://godoc.org/github.com/jolestar/go-commons-pool)   [![包含中文文档][CN]](https://github.com/jolestar/go-commons-pool)
* [shortid](https://github.com/teris-io/shortid) **star:528** 分布式地生成超短、唯一、非顺序、URL友好的id。   [![最近一年没有更新][Yellow]](https://github.com/teris-io/shortid)   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/shortid)
* [llvm](https://github.com/llir/llvm) **star:502** 用于在纯Go中与LLVM IR交互的库。   [![godoc][GoDoc]](https://godoc.org/github.com/llir/llvm)
* [health](https://github.com/dimiro1/health) **star:380** 易于使用，可扩展的健康检查库。   [![godoc][GoDoc]](https://godoc.org/github.com/dimiro1/health)
* [conv](https://github.com/cstockton/go-conv) **star:350** conv包提供了跨Go类型(Go types)的快速和直观的转换。   [![最近一年没有更新][Yellow]](https://github.com/cstockton/go-conv)   [![godoc][GoDoc]](https://godoc.org/github.com/cstockton/go-conv)
* [banner](https://github.com/dimiro1/banner) **star:255** 在Go应用程序中添加漂亮的横幅(banner)。   [![godoc][GoDoc]](https://godoc.org/github.com/dimiro1/banner)
* [gountries](https://github.com/pariz/gountries) **star:235** 获取国家和细节数据的包。   [![godoc][GoDoc]](https://godoc.org/github.com/pariz/gountries)
* [antch](https://github.com/antchfx/antch) **star:169** 一个快速、强大和可扩展的web爬虫框架。   [![最近一年没有更新][Yellow]](https://github.com/antchfx/antch)   [![godoc][GoDoc]](https://godoc.org/github.com/antchfx/antch)   [![包含中文文档][CN]](https://github.com/antchfx/antch)
* [ffmt](https://github.com/go-ffmt/ffmt) **star:155** 美化数据,使其更适合人查看。   [![godoc][GoDoc]](https://godoc.org/github.com/go-ffmt/ffmt)   [![包含中文文档][CN]](https://github.com/go-ffmt/ffmt)
* [stateless](https://github.com/qmuntal/stateless) **star:148** 用于创建状态机的流畅库。   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/stateless)
* [lk](https://github.com/hyperboloide/lk) **star:143** 一个简单的版权许可证库。   [![godoc][GoDoc]](https://godoc.org/github.com/hyperboloide/lk)
* [battery](https://github.com/distatus/battery) **star:143** 跨平台、标准化的电池信息库。   [![godoc][GoDoc]](https://godoc.org/github.com/distatus/battery)
* [ghorg](https://github.com/gabrie30/ghorg) **star:136** 快速克隆整个org用户库到一个目录-支持GitHub, GitLab和Bitbucket。   [![最近一周有更新][Green]](https://github.com/gabrie30/ghorg)   [![godoc][GoDoc]](https://godoc.org/github.com/gabrie30/ghorg)
* [stats](https://github.com/go-playground/stats) **star:131** Monitors Go MemStats + 诸如如内存，Swap和CPU的系统状态统计，并通过UDP发送到任何你想记录的地方   [![最近一年没有更新][Yellow]](https://github.com/go-playground/stats)   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/stats)
* [bitio](https://github.com/icza/bitio) **star:116** 高度优化的位级读写器。   [![godoc][GoDoc]](https://godoc.org/github.com/icza/bitio)
* [healthcheck](https://github.com/etherlabsio/healthcheck) **star:104** 用于RESTful服务的强制的(opinionated)并发健康检查HTTP处理程序。   [![godoc][GoDoc]](https://godoc.org/github.com/etherlabsio/healthcheck)
* [turtle](https://github.com/hackebrot/turtle) **star:94** Go的Emojis库。   [![godoc][GoDoc]](https://godoc.org/github.com/hackebrot/turtle)
* [go-unarr](https://github.com/gen2brain/go-unarr) **star:86** 用于RAR、TAR、ZIP和7z文件的解压缩库。   [![godoc][GoDoc]](https://godoc.org/github.com/gen2brain/go-unarr)
* [gommit](https://github.com/antham/gommit) **star:85** 分析git提交消息，确保它们遵循已定义的格式。   [![godoc][GoDoc]](https://godoc.org/github.com/antham/gommit)
* [gotoprom](https://github.com/cabify/gotoprom) **star:80** 为Prometheus客户端提供类型安全的指标(metric)构建工具库。   [![godoc][GoDoc]](https://godoc.org/github.com/cabify/gotoprom)
* [indigo](https://github.com/osamingo/indigo) **star:58** 分布式唯一ID生成器, 使用Sonyflake并由Base58编码。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/indigo)
* [morse](https://github.com/alwindoss/morse) **star:57** 实现字符串与摩尔斯电码转换的库。   [![最近一年没有更新][Yellow]](https://github.com/alwindoss/morse)   [![godoc][GoDoc]](https://godoc.org/github.com/alwindoss/morse)
* [captcha](https://github.com/steambap/captcha) **star:54** captcha包为验证码生成提供了一个易于使用的、unopinionated的API。   [![godoc][GoDoc]](https://godoc.org/github.com/steambap/captcha)
* [xkg](https://github.com/go-xkg/xkg) **star:48** X Keyboard Grabber(键盘事件捕获)   [![最近一年没有更新][Yellow]](https://github.com/go-xkg/xkg)   [![godoc][GoDoc]](https://godoc.org/github.com/go-xkg/xkg)
* [persian](https://github.com/mavihq/persian) **star:40** 一些适用于波斯语的Go工具库。   [![最近一年没有更新][Yellow]](https://github.com/mavihq/persian)   [![godoc][GoDoc]](https://godoc.org/github.com/mavihq/persian)
* [pdfgen](https://github.com/hyperboloide/pdfgen) **star:39** 通过Json请求生成PDF的HTTP服务。   [![最近一年没有更新][Yellow]](https://github.com/hyperboloide/pdfgen)   [![godoc][GoDoc]](https://godoc.org/github.com/hyperboloide/pdfgen)
* [datacounter](https://github.com/miolini/datacounter) **star:31** 用于readers/writer/http.ResponseWriter的计数器。   [![godoc][GoDoc]](https://godoc.org/github.com/miolini/datacounter)
* [browscap_go](https://github.com/digitalcrab/browscap_go) **star:31** 用于[Browser Capabilities Project](http://browscap.org/)的Go库。   [![godoc][GoDoc]](https://godoc.org/github.com/digitalcrab/browscap_go)
* [autoflags](https://github.com/artyom/autoflags) **star:26** 从struct字段自动定义命令行flag的Go包。   [![最近一年没有更新][Yellow]](https://github.com/artyom/autoflags)   [![godoc][GoDoc]](https://godoc.org/github.com/artyom/autoflags)
* [xdg](https://github.com/rkoesters/xdg) **star:21** FreeDesktop.org (xdg)规范在Go中的实现。   [![最近一年没有更新][Yellow]](https://github.com/rkoesters/xdg)   [![godoc][GoDoc]](https://godoc.org/github.com/rkoesters/xdg)
* [gosh](https://github.com/osamingo/gosh) **star:20** 提供Go统计处理程序，结构和测量方法。   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/gosh)
* [url-shortener](https://github.com/pantrif/url-shortener) **star:19** 一个现代的、强大的、健壮的URL转短链接微服务，带有mysql支持。   [![最近一年没有更新][Yellow]](https://github.com/pantrif/url-shortener)   [![godoc][GoDoc]](https://godoc.org/github.com/pantrif/url-shortener)
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler)  用于生成http输入和输出处理模板。
* [sandid](https://github.com/aofei/sandid) **star:15** 能沟让地球上的每一粒沙子都有自己的ID。   [![godoc][GoDoc]](https://godoc.org/github.com/aofei/sandid)
* [anagent](https://github.com/mudler/anagent) **star:11** Go语言的最小化，可插入的evloop/timer处理程序, 带有依赖注入。   [![最近一年没有更新][Yellow]](https://github.com/mudler/anagent)   [![godoc][GoDoc]](https://godoc.org/github.com/mudler/anagent)
* [avgRating](https://github.com/kirillDanshin/avgRating) **star:10** 根据威尔逊得分排序算法(Wilson Score Equation)计算平均分和评分。   [![最近一年没有更新][Yellow]](https://github.com/kirillDanshin/avgRating)   [![godoc][GoDoc]](https://godoc.org/github.com/kirillDanshin/avgRating)
* [hostutils](https://github.com/Wing924/hostutils) **star:8** 一个用于打包和解包FQDNs列表的go语言库。   [![最近一年没有更新][Yellow]](https://github.com/Wing924/hostutils)   [![godoc][GoDoc]](https://godoc.org/github.com/Wing924/hostutils)
* [shellwords](https://github.com/Wing924/shellwords) **star:8** 一个Go库，实现了依照UNIX Bourne shell的关键词解析规则进行字符串操纵。   [![最近一年没有更新][Yellow]](https://github.com/Wing924/shellwords)   [![godoc][GoDoc]](https://godoc.org/github.com/Wing924/shellwords)
* [metrics](https://github.com/pascaldekloe/metrics) **star:6** 用于instrumentation和Prometheus exposition的库。   [![godoc][GoDoc]](https://godoc.org/github.com/pascaldekloe/metrics)
* [numa](https://github.com/lrita/numa) **star:2** NUMA是一个用go编写的实用程序库。它可以帮助我们编写一些NUMA-AWARED代码。   [![godoc][GoDoc]](https://godoc.org/github.com/lrita/numa)

## 自然语言处理

*用于处理人类语言的库。 (翻译出错了? 试试 [英文版](README_EN.md#natural-language-processing) 吧~)*

