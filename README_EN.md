# Awesome Go

[Awesome]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.4.1/docs/awesome.svg "star > 2000"
[Green]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Green.svg "There was an update last week"
[Yellow]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Yellow.svg "It hasn't been updated in the last year"
[CN]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.1/docs/Cn.svg "Contains Chinese documents"
[Archived]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.2.1/docs/archived.svg "The project has been archived"
[GoDoc]: https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.3.0/docs/DOC.svg "godoc document links"

**This project is [awesome-go](https://awesome-go.com/) Chinese version, last sync time : 2020-03-09 12:07:45(Synchronize every day)**

[![english](https://cdn.jsdelivr.net/gh/yinggaozhen/awesome-go-cn@1.3.0/docs/chinese.svg)](README.md) [![Build Status](https://travis-ci.org/avelino/awesome-go.svg?branch=master)](https://travis-ci.org/avelino/awesome-go) [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](http://gophers.slack.com/messages/awesome) [![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)

[![patreon avelino](https://c5.patreon.com/external/logo/become_a_patron_button@2x.png)](https://www.patreon.com/avelinosource) financial support to Awesome Go

A curated list of awesome Go frameworks, libraries and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python)。

**Icon** :


Icon | State  
:-:|-
![awesome][Awesome] | star > 2000
![There was an update last week][Green] | There was an update last week。You can basically determine that the current library is in an actively maintained state。
![Not updated in last year][Yellow] | Not updated in last year。Reflects that the maintenance of the library is not high enthusiasm, use should be careful。
![Archived][Archived] | The project has been archived。
![Contains Chinese documents][CN] | This project contains Chinese documents。
![godoc document][GoDoc] | godoc document links。

### Explain

[中文](README.md)  | [English](README_EN.md)
 

### Contributing

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/master/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

#### *If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!*

### Contents

- [Awesome Go](#awesome-go)
    - [Audio and Music](#audio-and-music)
    - [Authentication and OAuth](#authentication-and-oauth)
    - [Bot Building](#bot-building)
    - [Command Line](#command-line)
    - [Configuration](#configuration)
    - [Continuous Integration](#continuous-integration)
    - [CSS Preprocessors](#css-preprocessors)
    - [Data Structures](#data-structures)
    - [Database](#database)
    - [Database Drivers](#database-drivers)
    - [Date and Time](#date-and-time)
    - [Distributed Systems](#distributed-systems)
    - [Dynamic DNS](#dynamic-dns)
    - [Email](#email)
    - [Embeddable Scripting Languages](#embeddable-scripting-languages)
    - [Error Handling](#error-handling)
    - [Files](#files)
    - [Financial](#financial)
    - [Forms](#forms)
    - [Functional](#functional)
    - [Game Development](#game-development)
    - [Generation and Generics](#generation-and-generics)
    - [Geographic](#geographic)
    - [Go Compilers](#go-compilers)
    - [Goroutines](#goroutines)
    - [GUI](#gui)
    - [Hardware](#hardware)
    - [Images](#images)
    - [IoT](#iot)
    - [Job Scheduler](#job-scheduler)
    - [JSON](#json)
    - [Logging](#logging)
    - [Machine Learning](#machine-learning)
    - [Messaging](#messaging)
    - [Microsoft Office](#microsoft-office)
        - [Microsoft Excel](#microsoft-excel)
    - [Miscellaneous](#miscellaneous)
        - [Dependency Injection](#dependency-injection)
        - [Project Layout](#project-layout)
        - [Strings](#strings)
    - [Natural Language Processing](#natural-language-processing)
    - [Networking](#networking)
        - [HTTP Clients](#http-clients)
    - [OpenGL](#opengl)
    - [ORM](#orm)
    - [Package Management](#package-management)
    - [Performance](#performance)
    - [Query Language](#query-language)
    - [Resource Embedding](#resource-embedding)
    - [Science and Data Analysis](#science-and-data-analysis)
    - [Security](#security)
    - [Serialization](#serialization)
    - [Server Applications](#server-applications)
    - [Stream Processing](#stream-processing)
    - [Template Engines](#template-engines)
    - [Testing](#testing)
    - [Text Processing](#text-processing)
    - [Third-party APIs](#third-party-apis)
    - [Utilities](#utilities)
    - [UUID](#uuid)
    - [Validation](#validation)
    - [Version Control](#version-control)
    - [Video](#video)
    - [Web Frameworks](#web-frameworks)
        - [Middlewares](#middlewares)
            - [Actual middlewares](#actual-middlewares)
            - [Libraries for creating HTTP middlewares](#libraries-for-creating-http-middlewares)
        - [Routers](#routers)
    - [Windows](#windows)
    - [XML](#xml)

- [Tools](#tools)
    - [Code Analysis](#code-analysis)
    - [Editor Plugins](#editor-plugins)
    - [Go Generate Tools](#go-generate-tools)
    - [Go Tools](#go-tools)
    - [Software Packages](#software-packages)
        - [DevOps Tools](#devops-tools)
        - [Other Software](#other-software)

- [Resources](#resources)
    - [Benchmarks](#benchmarks)
    - [Conferences](#conferences)
    - [E-Books](#e-books)
    - [Gophers](#gophers)
    - [Meetups](#meetups)
    - [Twitter](#twitter)
    - [Websites](#websites)
        - [Tutorials](#tutorials)

## Audio and Music

*Libraries for manipulating audio.*

* [Oto](https://github.com/hajimehoshi/oto) **star:546** A low-level library to play sound on multiple platforms.   [![There was an update last week][Green]](https://github.com/hajimehoshi/oto)   [![godoc][GoDoc]](https://godoc.org/github.com/hajimehoshi/oto)
* [PortAudio](https://github.com/gordonklaus/portaudio) **star:336** Go bindings for the PortAudio audio I/O library.   [![It hasn't been updated in the last year][Yellow]](https://github.com/gordonklaus/portaudio)   [![godoc][GoDoc]](https://godoc.org/github.com/gordonklaus/portaudio)
* [music-theory](https://github.com/go-music-theory/music-theory) **star:284** Music theory models in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/go-music-theory/music-theory)
* [waveform](https://github.com/mdlayher/waveform) **star:276** Go package capable of generating waveform images from audio streams.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mdlayher/waveform)   [![godoc][GoDoc]](https://godoc.org/github.com/mdlayher/waveform)
* [portmidi](https://github.com/rakyll/portmidi) **star:226** Go bindings for PortMidi.   [![godoc][GoDoc]](https://godoc.org/github.com/rakyll/portmidi)
* [id3v2](https://github.com/bogem/id3v2) **star:143** Fast and stable ID3 parsing and writing library for Go.   [![There was an update last week][Green]](https://github.com/bogem/id3v2)   [![godoc][GoDoc]](https://godoc.org/github.com/bogem/id3v2)
* [flac](https://github.com/mewkiz/flac) **star:117** Native Go FLAC encoder/decoder with support for FLAC streams.   [![godoc][GoDoc]](https://godoc.org/github.com/mewkiz/flac)
* [mix](https://github.com/go-mix/mix) **star:112** Sequence-based Go-native audio mixer for music apps.   [![godoc][GoDoc]](https://godoc.org/github.com/go-mix/mix)
* [mp3](https://github.com/tcolgate/mp3) **star:107** Native Go MP3 decoder.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tcolgate/mp3)   [![godoc][GoDoc]](https://godoc.org/github.com/tcolgate/mp3)
* [go-sox](https://github.com/krig/go-sox) **star:105** libsox bindings for go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/krig/go-sox)   [![godoc][GoDoc]](https://godoc.org/github.com/krig/go-sox)
* [malgo](https://github.com/gen2brain/malgo) **star:96** Mini audio library.   [![godoc][GoDoc]](https://godoc.org/github.com/gen2brain/malgo)
* [taglib](https://github.com/wtolson/go-taglib) **star:72** Go bindings for taglib.   [![It hasn't been updated in the last year][Yellow]](https://github.com/wtolson/go-taglib)   [![godoc][GoDoc]](https://godoc.org/github.com/wtolson/go-taglib)
* [gaad](https://github.com/Comcast/gaad) **star:68** Native Go AAC bitstream parser.   [![godoc][GoDoc]](https://godoc.org/github.com/Comcast/gaad)
* [minimp3](https://github.com/tosone/minimp3) **star:38** Lightweight MP3 decoder library.
* [go_mediainfo](https://github.com/zhulik/go_mediainfo) **star:28** libmediainfo bindings for go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zhulik/go_mediainfo)   [![godoc][GoDoc]](https://godoc.org/github.com/zhulik/go_mediainfo)
* [EasyMIDI](https://github.com/algoGuy/EasyMIDI) **star:27** EasyMidi is a simple and reliable library for working with standard midi file (SMF).   [![It hasn't been updated in the last year][Yellow]](https://github.com/algoGuy/EasyMIDI)   [![godoc][GoDoc]](https://godoc.org/github.com/algoGuy/EasyMIDI)
* [vorbis](https://github.com/mccoyst/vorbis) **star:25** "Native" Go Vorbis decoder (uses CGO, but has no dependencies).   [![godoc][GoDoc]](https://godoc.org/github.com/mccoyst/vorbis)
* [gosamplerate](https://github.com/dh1tw/gosamplerate) **star:9** libsamplerate bindings for go.   [![godoc][GoDoc]](https://godoc.org/github.com/dh1tw/gosamplerate)

## Authentication and OAuth

*Libraries for implementing authentications schemes.*

* [jwt-go](https://github.com/dgrijalva/jwt-go) **star:7168** Golang implementation of JSON Web Tokens (JWT).   [![star > 2000][Awesome]](https://github.com/dgrijalva/jwt-go)   [![There was an update last week][Green]](https://github.com/dgrijalva/jwt-go)   [![godoc][GoDoc]](https://godoc.org/github.com/dgrijalva/jwt-go)
* [casbin](https://github.com/hsluoyz/casbin) **star:6219** Authorization library that supports access control models like ACL, RBAC, ABAC.   [![star > 2000][Awesome]](https://github.com/hsluoyz/casbin)   [![There was an update last week][Green]](https://github.com/hsluoyz/casbin)   [![godoc][GoDoc]](https://godoc.org/github.com/hsluoyz/casbin)
* [oauth2](https://github.com/golang/oauth2) **star:2763** Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine and App Engine support.   [![star > 2000][Awesome]](https://github.com/golang/oauth2)   [![There was an update last week][Green]](https://github.com/golang/oauth2)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/oauth2)
* [goth](https://github.com/markbates/goth) **star:2576** provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.   [![star > 2000][Awesome]](https://github.com/markbates/goth)   [![There was an update last week][Green]](https://github.com/markbates/goth)   [![godoc][GoDoc]](https://godoc.org/github.com/markbates/goth)
* [authboss](https://github.com/volatiletech/authboss) **star:2163** Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure, and start building your app without having to build an authentication system each time.   [![star > 2000][Awesome]](https://github.com/volatiletech/authboss)   [![godoc][GoDoc]](https://godoc.org/github.com/volatiletech/authboss)
* [osin](https://github.com/openshift/osin) **star:1584** Golang OAuth2 server library.   [![godoc][GoDoc]](https://godoc.org/github.com/openshift/osin)
* [go-jose](https://github.com/square/go-jose) **star:1482** Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.   [![There was an update last week][Green]](https://github.com/square/go-jose)   [![godoc][GoDoc]](https://godoc.org/github.com/square/go-jose)
* [go-oauth2-server](https://github.com/RichardKnop/go-oauth2-server) **star:1459** Standalone, specification-compliant,  OAuth2 server written in Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/go-oauth2-server)
* [gologin](https://github.com/dghubble/gologin) **star:1167** chainable handlers for login with OAuth1 and OAuth2 authentication providers.   [![godoc][GoDoc]](https://godoc.org/github.com/dghubble/gologin)
* [gorbac](https://github.com/mikespook/gorbac) **star:993** provides a lightweight role-based access control (RBAC) implementation in Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/mikespook/gorbac)
* [loginsrv](https://github.com/tarent/loginsrv) **star:916** JWT login microservice with plugable backends such as OAuth2 (Github), htpasswd, osiam.   [![godoc][GoDoc]](https://godoc.org/github.com/tarent/loginsrv)
* [scs](https://github.com/alexedwards/scs) **star:680** Session Manager for HTTP servers.   [![godoc][GoDoc]](https://godoc.org/github.com/alexedwards/scs)
* [permissions2](https://github.com/xyproto/permissions2) **star:391** Library for keeping track of users, login states and permissions. Uses secure cookies and bcrypt.   [![godoc][GoDoc]](https://godoc.org/github.com/xyproto/permissions2)
* [paseto](https://github.com/o1egl/paseto) **star:317** Golang implementation of Platform-Agnostic Security Tokens (PASETO).   [![godoc][GoDoc]](https://godoc.org/github.com/o1egl/paseto)
* [jeff](https://github.com/abraithwaite/jeff) **star:190** Simple, flexible, secure and idiomatic web session management with pluggable backends.   [![godoc][GoDoc]](https://godoc.org/github.com/abraithwaite/jeff)
* [httpauth](https://github.com/goji/httpauth) **star:190** HTTP Authentication middleware.   [![It hasn't been updated in the last year][Yellow]](https://github.com/goji/httpauth)   [![godoc][GoDoc]](https://godoc.org/github.com/goji/httpauth)
* [jwt-auth](https://github.com/adam-hanna/jwt-auth) **star:172** JWT middleware for Golang http servers with many configuration options.   [![It hasn't been updated in the last year][Yellow]](https://github.com/adam-hanna/jwt-auth)   [![godoc][GoDoc]](https://godoc.org/github.com/adam-hanna/jwt-auth)
* [jwt](https://github.com/pascaldekloe/jwt) **star:157** Lightweight JSON Web Token (JWT) library.   [![godoc][GoDoc]](https://godoc.org/github.com/pascaldekloe/jwt)
* [branca](https://github.com/hako/branca) **star:103** Golang implementation of Branca Tokens.   [![godoc][GoDoc]](https://godoc.org/github.com/hako/branca)
* [session](https://github.com/icza/session) **star:99** Go session management for web servers (including support for Google App Engine - GAE).   [![godoc][GoDoc]](https://godoc.org/github.com/icza/session)
* [sessionup](https://github.com/swithek/sessionup) **star:81** Simple, yet effective HTTP session management and identification package.   [![There was an update last week][Green]](https://github.com/swithek/sessionup)   [![godoc][GoDoc]](https://godoc.org/github.com/swithek/sessionup)
* [jwt](https://github.com/robbert229/jwt) **star:78** Clean and easy to use implementation of JSON Web Tokens (JWT).   [![It hasn't been updated in the last year][Yellow]](https://github.com/robbert229/jwt)   [![godoc][GoDoc]](https://godoc.org/github.com/robbert229/jwt)
* [sjwt](https://github.com/brianvoe/sjwt) **star:59** Simple jwt generator and parser.   [![godoc][GoDoc]](https://godoc.org/github.com/brianvoe/sjwt)
* [sessions](https://github.com/adam-hanna/sessions) **star:48** Dead simple, highly performant, highly customizable sessions service for go http servers.   [![godoc][GoDoc]](https://godoc.org/github.com/adam-hanna/sessions)
* [rbac](https://github.com/zpatrick/rbac) **star:46** Minimalistic RBAC package for Go applications.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zpatrick/rbac)   [![godoc][GoDoc]](https://godoc.org/github.com/zpatrick/rbac)
* [securecookie](https://github.com/chmike/securecookie) **star:33** Efficient secure cookie encoding/decoding.   [![godoc][GoDoc]](https://godoc.org/github.com/chmike/securecookie)
* [sessiongate-go](https://github.com/f0rmiga/sessiongate-go) **star:8** Go session management using the SessionGate Redis module.   [![It hasn't been updated in the last year][Yellow]](https://github.com/f0rmiga/sessiongate-go)   [![godoc][GoDoc]](https://godoc.org/github.com/f0rmiga/sessiongate-go)
* [signedvalue](https://github.com/sashka/signedvalue) **star:8** Signed and timestamped strings compatible with [Tornado's](https://github.com/tornadoweb/tornado) `create_signed_value`, `decode_signed_value`, and therefore `set_secure_cookie` and `get_secure_cookie`.   [![godoc][GoDoc]](https://godoc.org/github.com/sashka/signedvalue)
* [scope](https://github.com/SonicRoshan/scope) **star:4** Easily Manage OAuth2 Scopes In Go.   [![godoc][GoDoc]](https://godoc.org/github.com/SonicRoshan/scope)
* [cookiestxt](https://github.com/mengzhuo/cookiestxt) **star:2** provides parser of cookies.txt file format.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mengzhuo/cookiestxt)   [![godoc][GoDoc]](https://godoc.org/github.com/mengzhuo/cookiestxt)

## Bot Building

*Libraries for building and working with bots.*

* [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) **star:1965** Simple and clean Telegram bot client.   [![There was an update last week][Green]](https://github.com/Syfaro/telegram-bot-api)   [![godoc][GoDoc]](https://godoc.org/github.com/Syfaro/telegram-bot-api)
* [telebot](https://github.com/tucnak/telebot) **star:1140** Telegram bot framework written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/tucnak/telebot)
* [go-chat-bot](https://github.com/go-chat-bot/bot) **star:552** IRC, Slack & Telegram bot written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/go-chat-bot/bot)
* [go-joe](https://joe-bot.net)  A general-purpose bot library inspired by Hubot but written in Go.
* [slacker](https://github.com/shomali11/slacker) **star:361** Easy to use framework to create Slack bots.   [![godoc][GoDoc]](https://godoc.org/github.com/shomali11/slacker)
* [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) **star:288** A golang implementation of a console-based trading bot for cryptocurrency exchanges.   [![It hasn't been updated in the last year][Yellow]](https://github.com/saniales/golang-crypto-trading-bot)   [![godoc][GoDoc]](https://godoc.org/github.com/saniales/golang-crypto-trading-bot)
* [Kelp](https://github.com/stellar/kelp) **star:266** official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.   [![There was an update last week][Green]](https://github.com/stellar/kelp)   [![godoc][GoDoc]](https://godoc.org/github.com/stellar/kelp)
* [tbot](https://github.com/yanzay/tbot) **star:251** Telegram bot server with API similar to net/http.   [![godoc][GoDoc]](https://godoc.org/github.com/yanzay/tbot)
* [Tenyks](https://github.com/kyleterry/tenyks) **star:167** Service oriented IRC bot using Redis and JSON for messaging.   [![godoc][GoDoc]](https://godoc.org/github.com/kyleterry/tenyks)
* [go-sarah](https://github.com/oklahomer/go-sarah) **star:156** Framework to build bot for desired chat services including LINE, Slack, Gitter and more.   [![godoc][GoDoc]](https://godoc.org/github.com/oklahomer/go-sarah)
* [hanu](https://github.com/sbstjn/hanu) **star:119** Framework for writing Slack bots.   [![godoc][GoDoc]](https://godoc.org/github.com/sbstjn/hanu)
* [go-twitch-irc](https://github.com/gempir/go-twitch-irc) **star:94** Libary to write bots for twitch.tv chat   [![There was an update last week][Green]](https://github.com/gempir/go-twitch-irc)   [![godoc][GoDoc]](https://godoc.org/github.com/gempir/go-twitch-irc)
* [go-tgbot](https://github.com/olebedev/go-tgbot) **star:91** Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router and middleware.   [![It hasn't been updated in the last year][Yellow]](https://github.com/olebedev/go-tgbot)   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/go-tgbot)
* [margelet](https://github.com/zhulik/margelet) **star:60** Framework for building Telegram bots.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zhulik/margelet)   [![godoc][GoDoc]](https://godoc.org/github.com/zhulik/margelet)
* [govkbot](https://github.com/nikepan/govkbot) **star:30** Simple Go [VK](https://vk.com) bot library.   [![There was an update last week][Green]](https://github.com/nikepan/govkbot)   [![godoc][GoDoc]](https://godoc.org/github.com/nikepan/govkbot)
* [slackscot](https://github.com/alexandre-normand/slackscot) **star:25** Another framework for building Slack bots.   [![godoc][GoDoc]](https://godoc.org/github.com/alexandre-normand/slackscot)
* [micha](https://github.com/onrik/micha) **star:12** Go Library for Telegram bot api.   [![godoc][GoDoc]](https://godoc.org/github.com/onrik/micha)

## Command Line

### Standard CLI

*Libraries for building standard or basic Command Line applications.*

* [cobra](https://github.com/spf13/cobra) **star:16025** Commander for modern Go CLI interactions.   [![star > 2000][Awesome]](https://github.com/spf13/cobra)   [![There was an update last week][Green]](https://github.com/spf13/cobra)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/cobra)
* [urfave/cli](https://github.com/urfave/cli) **star:13242** Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).   [![star > 2000][Awesome]](https://github.com/urfave/cli)   [![There was an update last week][Green]](https://github.com/urfave/cli)   [![godoc][GoDoc]](https://godoc.org/github.com/urfave/cli)
* [kingpin](https://github.com/alecthomas/kingpin) **star:2815** Command line and flag parser supporting sub commands.   [![star > 2000][Awesome]](https://github.com/alecthomas/kingpin)   [![godoc][GoDoc]](https://godoc.org/github.com/alecthomas/kingpin)
* [go-flags](https://github.com/jessevdk/go-flags) **star:1646** go command line option parser.   [![godoc][GoDoc]](https://godoc.org/github.com/jessevdk/go-flags)
* [Dnote](https://github.com/dnote/dnote) **star:1517** A simple command line notebook with multi-device sync.   [![There was an update last week][Green]](https://github.com/dnote/dnote)   [![godoc][GoDoc]](https://godoc.org/github.com/dnote/dnote)
* [readline](https://github.com/chzyer/readline) **star:1468** Pure golang implementation that provides most features in GNU-Readline under MIT license.   [![godoc][GoDoc]](https://godoc.org/github.com/chzyer/readline)
* [docopt.go](https://github.com/docopt/docopt.go) **star:1226** Command-line arguments parser that will make you smile.   [![godoc][GoDoc]](https://godoc.org/github.com/docopt/docopt.go)
* [mitchellh/cli](https://github.com/mitchellh/cli) **star:1098** Go library for implementing command-line interfaces.   [![godoc][GoDoc]](https://godoc.org/github.com/mitchellh/cli)
* [pflag](https://github.com/spf13/pflag) **star:1014** Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.   [![There was an update last week][Green]](https://github.com/spf13/pflag)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/pflag)
* [cli-init](https://github.com/tcnksm/gcli) **star:894** The easy way to start building Golang command line applications.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tcnksm/gcli)   [![godoc][GoDoc]](https://godoc.org/github.com/tcnksm/gcli)
* [climax](http://github.com/tucnak/climax)  Alternative CLI with "human face", in spirit of Go command.
* [go-arg](https://github.com/alexflint/go-arg) **star:844** Struct-based argument parsing in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/alexflint/go-arg)
* [complete](https://github.com/posener/complete) **star:669** Write bash completions in Go + Go command bash completion.   [![godoc][GoDoc]](https://godoc.org/github.com/posener/complete)
* [liner](https://github.com/peterh/liner) **star:662** Go readline-like library for command-line interfaces.   [![godoc][GoDoc]](https://godoc.org/github.com/peterh/liner)
* [mow.cli](https://github.com/jawher/mow.cli) **star:657** Go library for building CLI applications with sophisticated flag and argument parsing and validation.   [![godoc][GoDoc]](https://godoc.org/github.com/jawher/mow.cli)
* [flaggy](https://github.com/integrii/flaggy) **star:631** A robust and idiomatic flags package with excellent subcommand support.   [![There was an update last week][Green]](https://github.com/integrii/flaggy)   [![godoc][GoDoc]](https://godoc.org/github.com/integrii/flaggy)
* [cli](https://github.com/mkideal/cli) **star:516** Feature-rich and easy to use command-line package based on golang struct tags.   [![godoc][GoDoc]](https://godoc.org/github.com/mkideal/cli)
* [ops](https://github.com/nanovms/ops) **star:386** Unikernel Builder/Orchestrator.   [![There was an update last week][Green]](https://github.com/nanovms/ops)   [![godoc][GoDoc]](https://godoc.org/github.com/nanovms/ops)
* [argparse](https://github.com/akamensky/argparse) **star:174** Command line argument parser inspired by Python's argparse module.   [![There was an update last week][Green]](https://github.com/akamensky/argparse)   [![godoc][GoDoc]](https://godoc.org/github.com/akamensky/argparse)
* [commandeer](https://github.com/jaffee/commandeer) **star:107** Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.   [![godoc][GoDoc]](https://godoc.org/github.com/jaffee/commandeer)
* [sflags](https://github.com/octago/sflags) **star:105** Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin and other libraries.   [![godoc][GoDoc]](https://godoc.org/github.com/octago/sflags)
* [flag](https://github.com/cosiner/flag) **star:103** Simple but powerful command line option parsing library for Go supporting subcommand.   [![It hasn't been updated in the last year][Yellow]](https://github.com/cosiner/flag)   [![godoc][GoDoc]](https://godoc.org/github.com/cosiner/flag)
* [wmenu](https://github.com/dixonwille/wmenu) **star:102** Easy to use menu structure for cli applications that prompts users to make choices.   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/wmenu)
* [ukautz/clif](https://github.com/ukautz/clif) **star:101** Small command line interface framework.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ukautz/clif)   [![godoc][GoDoc]](https://godoc.org/github.com/ukautz/clif)
* [job](https://github.com/liujianping/job) **star:70** JOB, make your short-term command as a long-term job.   [![godoc][GoDoc]](https://godoc.org/github.com/liujianping/job)
* [cli](https://github.com/teris-io/cli) **star:64** Simple and complete API for building command line interfaces in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/cli)
* [1build](https://github.com/gopinath-langote/1build) **star:53** Command line tool to frictionlessly manage project-specific commands.   [![godoc][GoDoc]](https://godoc.org/github.com/gopinath-langote/1build)
* [env](https://github.com/codingconcepts/env) **star:48** Tag-based environment configuration for structs.   [![godoc][GoDoc]](https://godoc.org/github.com/codingconcepts/env)
* [wlog](https://github.com/dixonwille/wlog) **star:42** Simple logging interface that supports cross-platform color and concurrency.   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/wlog)
* [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli)  cli application framework with auto configuration and dependency injection.
* [gocmd](https://github.com/devfacet/gocmd) **star:37** Go library for building command line applications.   [![It hasn't been updated in the last year][Yellow]](https://github.com/devfacet/gocmd)   [![godoc][GoDoc]](https://godoc.org/github.com/devfacet/gocmd)
* [strumt](https://github.com/antham/strumt) **star:34** Library to create prompt chain.   [![godoc][GoDoc]](https://godoc.org/github.com/antham/strumt)
* [flagvar](https://github.com/sgreben/flagvar) **star:33** A collection of flag argument types for Go's standard `flag` package.   [![godoc][GoDoc]](https://godoc.org/github.com/sgreben/flagvar)
* [cmdr](https://github.com/hedzr/cmdr) **star:30** A POSIX/GNU style, getopt-like command-line UI Go library.   [![There was an update last week][Green]](https://github.com/hedzr/cmdr)   [![godoc][GoDoc]](https://godoc.org/github.com/hedzr/cmdr)
* [clîr](https://github.com/leaanthony/clir) **star:21** A Simple and Clear CLI library. Dependency free.   [![godoc][GoDoc]](https://godoc.org/github.com/leaanthony/clir)
* [go-getoptions](https://github.com/DavidGamba/go-getoptions) **star:19** Go option parser inspired on the flexibility of Perl’s GetOpt::Long.   [![godoc][GoDoc]](https://godoc.org/github.com/DavidGamba/go-getoptions)
* [argv](https://github.com/cosiner/argv) **star:19** Go library to split command line string as arguments array using the bash syntax.   [![godoc][GoDoc]](https://godoc.org/github.com/cosiner/argv)
* [go-commander](https://github.com/yitsushi/go-commander) **star:15** Go library to simplify CLI workflow.   [![godoc][GoDoc]](https://godoc.org/github.com/yitsushi/go-commander)
* [sand](https://github.com/Zaba505/sand) **star:9** Simple API for creating interpreters and so much more.   [![It hasn't been updated in the last year][Yellow]](https://github.com/Zaba505/sand)   [![godoc][GoDoc]](https://godoc.org/github.com/Zaba505/sand)
* [ts](https://github.com/liujianping/ts) **star:8** Timestamp convert & compare tool.   [![godoc][GoDoc]](https://godoc.org/github.com/liujianping/ts)
* [cmd](https://github.com/posener/cmd) **star:5** Extends the standard `flag` package to support sub commands and more in idomatic way.   [![There was an update last week][Green]](https://github.com/posener/cmd)   [![godoc][GoDoc]](https://godoc.org/github.com/posener/cmd)

### Advanced Console UIs

*Libraries for building Console Applications and Console User Interfaces.*

* [termui](https://github.com/gizak/termui) **star:9567** Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib).   [![star > 2000][Awesome]](https://github.com/gizak/termui)   [![godoc][GoDoc]](https://godoc.org/github.com/gizak/termui)
* [gommon/color](https://github.com/labstack/gommon/tree/master/color)  Style terminal text.
* [gocui](https://github.com/jroimartin/gocui) **star:6022** Minimalist Go library aimed at creating Console User Interfaces.   [![star > 2000][Awesome]](https://github.com/jroimartin/gocui)   [![godoc][GoDoc]](https://godoc.org/github.com/jroimartin/gocui)
* [termbox-go](https://github.com/nsf/termbox-go) **star:3697** Termbox is a library for creating cross-platform text-based interfaces.   [![star > 2000][Awesome]](https://github.com/nsf/termbox-go)   [![godoc][GoDoc]](https://godoc.org/github.com/nsf/termbox-go)
* [go-prompt](https://github.com/c-bata/go-prompt) **star:2862** Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit).   [![star > 2000][Awesome]](https://github.com/c-bata/go-prompt)   [![There was an update last week][Green]](https://github.com/c-bata/go-prompt)   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/go-prompt)
* [uiprogress](https://github.com/gosuri/uiprogress) **star:1643** Flexible library to render progress bars in terminal applications.   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uiprogress)
* [asciigraph](https://github.com/guptarohit/asciigraph) **star:1310** Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.   [![godoc][GoDoc]](https://godoc.org/github.com/guptarohit/asciigraph)
* [uilive](https://github.com/gosuri/uilive) **star:1104** Library for updating terminal output in realtime.   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uilive)
* [termdash](https://github.com/mum4k/termdash) **star:955** Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui).   [![There was an update last week][Green]](https://github.com/mum4k/termdash)   [![godoc][GoDoc]](https://godoc.org/github.com/mum4k/termdash)
* [progressbar](https://github.com/schollz/progressbar) **star:859** Basic thread-safe progress bar that works in every OS.   [![godoc][GoDoc]](https://godoc.org/github.com/schollz/progressbar)
* [mpb](https://github.com/vbauerster/mpb) **star:846** Multi progress bar for terminal applications.   [![There was an update last week][Green]](https://github.com/vbauerster/mpb)   [![godoc][GoDoc]](https://godoc.org/github.com/vbauerster/mpb)
* [aurora](https://github.com/logrusorgru/aurora) **star:785** ANSI terminal colors that supports fmt.Printf/Sprintf.   [![godoc][GoDoc]](https://godoc.org/github.com/logrusorgru/aurora)
* [uitable](https://github.com/gosuri/uitable) **star:546** Library to improve readability in terminal apps using tabular data.   [![godoc][GoDoc]](https://godoc.org/github.com/gosuri/uitable)
* [go-colorable](https://github.com/mattn/go-colorable) **star:418** Colorable writer for windows.   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-colorable)
* [go-isatty](https://github.com/mattn/go-isatty) **star:406** isatty for golang.   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-isatty)
* [chalk](https://github.com/ttacon/chalk) **star:330** Intuitive package for prettifying terminal/console output.   [![godoc][GoDoc]](https://godoc.org/github.com/ttacon/chalk)
* [gookit/color](https://github.com/gookit/color) **star:323** Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.   [![There was an update last week][Green]](https://github.com/gookit/color)   [![godoc][GoDoc]](https://godoc.org/github.com/gookit/color)   [![Contains Chinese documents][CN]](https://github.com/gookit/color)
* [tabby](https://github.com/cheynewallace/tabby) **star:263** A tiny library for super simple Golang tables.   [![godoc][GoDoc]](https://godoc.org/github.com/cheynewallace/tabby)
* [simpletable](https://github.com/alexeyco/simpletable) **star:213** Simple tables in terminal with Go.   [![godoc][GoDoc]](https://godoc.org/github.com/alexeyco/simpletable)
* [go-colortext](https://github.com/daviddengcn/go-colortext) **star:201** Go library for color output in terminals.   [![It hasn't been updated in the last year][Yellow]](https://github.com/daviddengcn/go-colortext)   [![godoc][GoDoc]](https://godoc.org/github.com/daviddengcn/go-colortext)
* [cfmt](https://github.com/mingrammer/cfmt) **star:72** Contextual fmt inspired by bootstrap color classes.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mingrammer/cfmt)   [![godoc][GoDoc]](https://godoc.org/github.com/mingrammer/cfmt)
* [tabular](https://github.com/InVisionApp/tabular) **star:36** Print ASCII tables from command line utilities without the need to pass large sets of data to the API.   [![It hasn't been updated in the last year][Yellow]](https://github.com/InVisionApp/tabular)   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/tabular)
* [ctc](https://github.com/wzshiming/ctc) **star:17** The non-invasive cross-platform terminal color library does not need to modify the Print method.   [![godoc][GoDoc]](https://godoc.org/github.com/wzshiming/ctc)   [![Contains Chinese documents][CN]](https://github.com/wzshiming/ctc)
* [colourize](https://github.com/TreyBastian/colourize) **star:17** Go library for ANSI colour text in terminals.   [![It hasn't been updated in the last year][Yellow]](https://github.com/TreyBastian/colourize)   [![godoc][GoDoc]](https://godoc.org/github.com/TreyBastian/colourize)
* [go-ataman](https://github.com/workanator/go-ataman) **star:8** Go library for rendering ANSI colored text templates in terminals.   [![It hasn't been updated in the last year][Yellow]](https://github.com/workanator/go-ataman)   [![godoc][GoDoc]](https://godoc.org/github.com/workanator/go-ataman)

## Configuration

*Libraries for configuration parsing.*

* [viper](https://github.com/spf13/viper) **star:11388** Go configuration with fangs.   [![star > 2000][Awesome]](https://github.com/spf13/viper)   [![There was an update last week][Green]](https://github.com/spf13/viper)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/viper)
* [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) **star:2812** Go library for managing configuration data from environment variables.   [![star > 2000][Awesome]](https://github.com/kelseyhightower/envconfig)   [![godoc][GoDoc]](https://godoc.org/github.com/kelseyhightower/envconfig)
* [godotenv](https://github.com/joho/godotenv) **star:2644** Go port of Ruby's dotenv library (Loads environment variables from `.env`).   [![star > 2000][Awesome]](https://github.com/joho/godotenv)   [![godoc][GoDoc]](https://godoc.org/github.com/joho/godotenv)
* [ini](https://github.com/go-ini/ini) **star:1943** Go package to read and write INI files.   [![There was an update last week][Green]](https://github.com/go-ini/ini)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ini/ini)
* [env](https://github.com/caarlos0/env) **star:1440** Parse environment variables to Go structs (with defaults).   [![godoc][GoDoc]](https://godoc.org/github.com/caarlos0/env)
* [konfig](https://github.com/lalamove/konfig) **star:547** Composable, observable and performant config handling for Go for the distributed processing era.   [![godoc][GoDoc]](https://godoc.org/github.com/lalamove/konfig)
* [confita](https://github.com/heetch/confita) **star:295** Load configuration in cascade from multiple backends into a struct.   [![godoc][GoDoc]](https://godoc.org/github.com/heetch/confita)
* [store](https://github.com/tucnak/store) **star:248** Lightweight configuration manager for Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tucnak/store)   [![godoc][GoDoc]](https://godoc.org/github.com/tucnak/store)
* [config](https://github.com/JeremyLoy/config) **star:228** Cloud native application configuration. Bind ENV to structs in only two lines.   [![There was an update last week][Green]](https://github.com/JeremyLoy/config)   [![godoc][GoDoc]](https://godoc.org/github.com/JeremyLoy/config)
* [config](https://github.com/olebedev/config) **star:225** JSON or YAML configuration wrapper with environment variables and flags parsing.   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/config)
* [joshbetz/config](https://github.com/joshbetz/config) **star:198** Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.   [![godoc][GoDoc]](https://godoc.org/github.com/joshbetz/config)
* [hjson](https://github.com/hjson/hjson-go) **star:194** Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.   [![godoc][GoDoc]](https://godoc.org/github.com/hjson/hjson-go)
* [envconfig](https://github.com/vrischmann/envconfig) **star:172** Read your configuration from environment variables.   [![godoc][GoDoc]](https://godoc.org/github.com/vrischmann/envconfig)
* [koanf](https://github.com/knadh/koanf) **star:170** Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.   [![godoc][GoDoc]](https://godoc.org/github.com/knadh/koanf)
* [gookit/config](https://github.com/gookit/config) **star:138** application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.   [![godoc][GoDoc]](https://godoc.org/github.com/gookit/config)   [![Contains Chinese documents][CN]](https://github.com/gookit/config)
* [gcfg](https://github.com/go-gcfg/gcfg) **star:127** read INI-style configuration files into Go structs; supports user-defined types and subsections.   [![godoc][GoDoc]](https://godoc.org/github.com/go-gcfg/gcfg)
* [goConfig](https://github.com/crgimenes/goConfig) **star:124** Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.   [![godoc][GoDoc]](https://godoc.org/github.com/crgimenes/goConfig)
* [envh](https://github.com/antham/envh) **star:94** Helpers to manage environment variables.   [![godoc][GoDoc]](https://godoc.org/github.com/antham/envh)
* [envcfg](https://github.com/tomazk/envcfg) **star:91** Un-marshaling environment variables to Go structs.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tomazk/envcfg)   [![godoc][GoDoc]](https://godoc.org/github.com/tomazk/envcfg)
* [gone/jconf](https://github.com/One-com/gone/tree/master/jconf)  Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
* [gofigure](https://github.com/ian-kent/gofigure) **star:58** Go application configuration made easy.   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/gofigure)
* [configure](https://github.com/paked/configure) **star:54** Provides configuration through multiple sources, including JSON, flags and environment variables.   [![It hasn't been updated in the last year][Yellow]](https://github.com/paked/configure)   [![godoc][GoDoc]](https://godoc.org/github.com/paked/configure)
* [cleanenv](https://github.com/ilyakaznacheev/cleanenv) **star:52** Minimalistic configuration reader (from files, ENV, and wherever you want).   [![godoc][GoDoc]](https://godoc.org/github.com/ilyakaznacheev/cleanenv)
* [harvester](https://github.com/beatlabs/harvester) **star:51** Harvester, a easy to use static and dynamic configuration package supportig seeding, env vars and Consul integration.   [![godoc][GoDoc]](https://godoc.org/github.com/beatlabs/harvester)
* [config](https://github.com/golobby/config) **star:50** A lightweight yet powerful config package for Go projects.   [![godoc][GoDoc]](https://godoc.org/github.com/golobby/config)
* [xdg](https://github.com/OpenPeeDeeP/xdg) **star:48** Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).   [![godoc][GoDoc]](https://godoc.org/github.com/OpenPeeDeeP/xdg)
* [ingo](https://github.com/schachmat/ingo) **star:28** Flags persisted in an ini-like config file.   [![It hasn't been updated in the last year][Yellow]](https://github.com/schachmat/ingo)   [![godoc][GoDoc]](https://godoc.org/github.com/schachmat/ingo)
* [go-up](https://github.com/ufoscout/go-up) **star:26** A simple configuration library with recursive placeholders resolution and no magic.   [![godoc][GoDoc]](https://godoc.org/github.com/ufoscout/go-up)
* [mini](https://github.com/sasbury/mini) **star:21** Golang package for parsing ini-style configuration files.   [![It hasn't been updated in the last year][Yellow]](https://github.com/sasbury/mini)   [![godoc][GoDoc]](https://godoc.org/github.com/sasbury/mini)
* [conflate](https://github.com/the4thamigo-uk/conflate) **star:13** Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.   [![godoc][GoDoc]](https://godoc.org/github.com/the4thamigo-uk/conflate)
* [genv](https://github.com/sakirsensoy/genv) **star:9** Read environment variables easily with dotenv support.   [![godoc][GoDoc]](https://godoc.org/github.com/sakirsensoy/genv)
* [envconf](https://github.com/ian-kent/envconf) **star:9** Configuration from environment.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ian-kent/envconf)   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/envconf)
* [sprbox](https://github.com/oblq/sprbox) **star:5** Build-environment aware toolbox factory and agnostic config parser (YAML, TOML, JSON and Environment vars).   [![godoc][GoDoc]](https://godoc.org/github.com/oblq/sprbox)
* [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) **star:3** Go utility for loading configuration parameters from AWS SSM (Parameter Store).   [![godoc][GoDoc]](https://godoc.org/github.com/ianlopshire/go-ssm-config)
* [nasermirzaei89/env](https://github.com/nasermirzaei89/env) **star:2** Simple useful package for read environment variables.   [![godoc][GoDoc]](https://godoc.org/github.com/nasermirzaei89/env)
* [onion](http://github.com/goraz/onion)  Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.

## Continuous Integration

*Tools for help with continuous integration.*

* [drone](https://github.com/drone/drone) **star:20620** Drone is a Continuous Integration platform built on Docker, written in Go.   [![star > 2000][Awesome]](https://github.com/drone/drone)   [![godoc][GoDoc]](https://godoc.org/github.com/drone/drone)
* [CDS](https://github.com/ovh/cds) **star:2711** Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.   [![star > 2000][Awesome]](https://github.com/ovh/cds)   [![There was an update last week][Green]](https://github.com/ovh/cds)   [![godoc][GoDoc]](https://godoc.org/github.com/ovh/cds)
* [goveralls](https://github.com/mattn/goveralls) **star:633** Go integration for Coveralls.io continuous code coverage tracking system.   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/goveralls)
* [overalls](https://github.com/go-playground/overalls) **star:100** Multi-Package go project coverprofile for tools like goveralls.   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/overalls)
* [duci](https://github.com/duck8823/duci) **star:53** A simple ci server no needs domain specific languages.   [![godoc][GoDoc]](https://godoc.org/github.com/duck8823/duci)
* [gomason](https://github.com/nikogura/gomason) **star:43** Test, Build, Sign, and Publish your go binaries from a clean workspace.   [![There was an update last week][Green]](https://github.com/nikogura/gomason)   [![godoc][GoDoc]](https://godoc.org/github.com/nikogura/gomason)
* [roveralls](https://github.com/LawrenceWoodman/roveralls) **star:12** Recursive coverage testing tool.   [![It hasn't been updated in the last year][Yellow]](https://github.com/LawrenceWoodman/roveralls)   [![godoc][GoDoc]](https://godoc.org/github.com/LawrenceWoodman/roveralls)

## CSS Preprocessors

*Libraries for preprocessing CSS files.*

* [gcss](https://github.com/yosssi/gcss) **star:431** Pure Go CSS Preprocessor.   [![It hasn't been updated in the last year][Yellow]](https://github.com/yosssi/gcss)   [![godoc][GoDoc]](https://godoc.org/github.com/yosssi/gcss)
* [go-libsass](https://github.com/wellington/go-libsass) **star:155** Go wrapper to the 100% Sass compatible libsass project.   [![It hasn't been updated in the last year][Yellow]](https://github.com/wellington/go-libsass)

## Data Structures

*Generic datastructures and algorithms in Go.*

* [gods](https://github.com/emirpasic/gods) **star:7878** Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.   [![star > 2000][Awesome]](https://github.com/emirpasic/gods)   [![godoc][GoDoc]](https://godoc.org/github.com/emirpasic/gods)
* [go-datastructures](https://github.com/Workiva/go-datastructures) **star:5464** Collection of useful, performant, and thread-safe data structures.   [![star > 2000][Awesome]](https://github.com/Workiva/go-datastructures)   [![There was an update last week][Green]](https://github.com/Workiva/go-datastructures)   [![godoc][GoDoc]](https://godoc.org/github.com/Workiva/go-datastructures)
* [golang-set](https://github.com/deckarep/golang-set) **star:1413** Thread-Safe and Non-Thread-Safe high-performance sets for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/deckarep/golang-set)
* [boomfilters](https://github.com/tylertreat/BoomFilters) **star:1235** Probabilistic data structures for processing continuous, unbounded streams.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tylertreat/BoomFilters)   [![godoc][GoDoc]](https://godoc.org/github.com/tylertreat/BoomFilters)
* [gota](https://github.com/kniren/gota) **star:1100** Implementation of dataframes, series, and data wrangling methods for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/kniren/gota)
* [roaring](https://github.com/RoaringBitmap/roaring) **star:792** Go package implementing compressed bitsets.   [![godoc][GoDoc]](https://godoc.org/github.com/RoaringBitmap/roaring)
* [willf/bloom](https://github.com/willf/bloom) **star:756** Go package implementing Bloom filters.   [![godoc][GoDoc]](https://godoc.org/github.com/willf/bloom)
* [hyperloglog](https://github.com/axiomhq/hyperloglog) **star:691** HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.   [![godoc][GoDoc]](https://godoc.org/github.com/axiomhq/hyperloglog)
* [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) **star:589** Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/cuckoofilter)
* [bitset](https://github.com/willf/bitset) **star:539** Go package implementing bitsets.   [![godoc][GoDoc]](https://godoc.org/github.com/willf/bitset)
* [trie](https://github.com/derekparker/trie) **star:461** Trie implementation in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/derekparker/trie)
* [gocache](https://github.com/eko/gocache) **star:370** A complete Go cache library with mutiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.   [![There was an update last week][Green]](https://github.com/eko/gocache)   [![godoc][GoDoc]](https://godoc.org/github.com/eko/gocache)
* [algorithms](https://github.com/shady831213/algorithms) **star:361** Algorithms and data structures.CLRS study.   [![godoc][GoDoc]](https://godoc.org/github.com/shady831213/algorithms)
* [go-geoindex](https://github.com/hailocab/go-geoindex) **star:320** In-memory geo index.   [![It hasn't been updated in the last year][Yellow]](https://github.com/hailocab/go-geoindex)   [![godoc][GoDoc]](https://godoc.org/github.com/hailocab/go-geoindex)
* [mafsa](https://github.com/smartystreets/mafsa) **star:281** MA-FSA implementation with Minimal Perfect Hashing.   [![godoc][GoDoc]](https://godoc.org/github.com/smartystreets/mafsa)   [![Archived][Archived]](https://github.com/smartystreets/mafsa)
* [goskiplist](https://github.com/ryszard/goskiplist) **star:217** Skip list implementation in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/ryszard/goskiplist)
* [hilbert](https://github.com/google/hilbert) **star:196** Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.   [![It hasn't been updated in the last year][Yellow]](https://github.com/google/hilbert)   [![godoc][GoDoc]](https://godoc.org/github.com/google/hilbert)
* [merkletree](https://github.com/cbergoon/merkletree) **star:181** Implementation of a merkle tree providing an efficient and secure verification of the contents of data structures.   [![godoc][GoDoc]](https://godoc.org/github.com/cbergoon/merkletree)
* [binpacker](https://github.com/zhuangsirui/binpacker) **star:135** Binary packer and unpacker helps user build custom binary stream.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zhuangsirui/binpacker)   [![godoc][GoDoc]](https://godoc.org/github.com/zhuangsirui/binpacker)
* [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) **star:132** Go implementation of Adaptive Radix Tree.   [![godoc][GoDoc]](https://godoc.org/github.com/plar/go-adaptive-radix-tree)
* [bloom](https://github.com/zhenjl/bloom) **star:131** Bloom filters implemented in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zhenjl/bloom)   [![godoc][GoDoc]](https://godoc.org/github.com/zhenjl/bloom)
* [ttlcache](https://github.com/diegobernardes/ttlcache) **star:129** In-memory LRU string-interface{} map with expiration for golang.   [![godoc][GoDoc]](https://godoc.org/github.com/diegobernardes/ttlcache)
* [skiplist](https://github.com/MauriceGit/skiplist) **star:117** Very fast Go Skiplist implementation.   [![godoc][GoDoc]](https://godoc.org/github.com/MauriceGit/skiplist)
* [iter](https://github.com/disksing/iter) **star:116** Go implementation of C++ STL iterators and algorithms.   [![godoc][GoDoc]](https://godoc.org/github.com/disksing/iter)   [![Contains Chinese documents][CN]](https://github.com/disksing/iter)
* [deque](https://github.com/gammazero/deque) **star:106** Fast ring-buffer deque (double-ended queue).   [![godoc][GoDoc]](https://godoc.org/github.com/gammazero/deque)
* [ring](https://github.com/TheTannerRyan/ring) **star:105** Go implementation of a high performance, thread safe bloom filter.   [![godoc][GoDoc]](https://godoc.org/github.com/TheTannerRyan/ring)
* [go-rquad](https://github.com/aurelien-rainone/go-rquad) **star:101** Region quadtrees with efficient point location and neighbour finding.   [![It hasn't been updated in the last year][Yellow]](https://github.com/aurelien-rainone/go-rquad)   [![godoc][GoDoc]](https://godoc.org/github.com/aurelien-rainone/go-rquad)
* [encoding](https://github.com/zhenjl/encoding) **star:99** Integer Compression Libraries for Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zhenjl/encoding)   [![godoc][GoDoc]](https://godoc.org/github.com/zhenjl/encoding)
* [conjungo](https://github.com/InVisionApp/conjungo) **star:86** A small, powerful and flexible merge library.   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/conjungo)
* [bit](https://github.com/yourbasic/bit) **star:83** Golang set data structure with bonus bit-twiddling functions.   [![It hasn't been updated in the last year][Yellow]](https://github.com/yourbasic/bit)   [![godoc][GoDoc]](https://godoc.org/github.com/yourbasic/bit)
* [gostl](https://github.com/liyue201/gostl) **star:76** Data structure and algorithm library for go, designed to provide functions similar to C++ STL.   [![godoc][GoDoc]](https://godoc.org/github.com/liyue201/gostl)
* [levenshtein](https://github.com/agnivade/levenshtein) **star:72** Implementation to calculate levenshtein distance in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/agnivade/levenshtein)
* [skiplist](https://github.com/gansidui/skiplist) **star:68** Skiplist implementation in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/gansidui/skiplist)   [![godoc][GoDoc]](https://godoc.org/github.com/gansidui/skiplist)
* [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) **star:63** Concurrent FIFO queue.   [![godoc][GoDoc]](https://godoc.org/github.com/enriquebris/goconcurrentqueue)
* [bloom](https://github.com/yourbasic/bloom) **star:49** Golang Bloom filter implementation.   [![It hasn't been updated in the last year][Yellow]](https://github.com/yourbasic/bloom)   [![godoc][GoDoc]](https://godoc.org/github.com/yourbasic/bloom)
* [go-mcache](https://github.com/OrlovEvgeny/go-mcache) **star:47** Fast in-memory key:value store/cache library. Pointer caches.   [![godoc][GoDoc]](https://godoc.org/github.com/OrlovEvgeny/go-mcache)
* [count-min-log](https://github.com/seiflotfy/count-min-log) **star:46** Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).   [![It hasn't been updated in the last year][Yellow]](https://github.com/seiflotfy/count-min-log)   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/count-min-log)
* [levenshtein](https://github.com/agext/levenshtein) **star:39** Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.   [![godoc][GoDoc]](https://godoc.org/github.com/agext/levenshtein)
* [remember-go](https://github.com/rocketlaunchr/remember-go) **star:36** A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory).   [![godoc][GoDoc]](https://godoc.org/github.com/rocketlaunchr/remember-go)
* [concurrent-writer](https://github.com/free/concurrent-writer) **star:27** Highly concurrent drop-in replacement for `bufio.Writer`.   [![It hasn't been updated in the last year][Yellow]](https://github.com/free/concurrent-writer)   [![godoc][GoDoc]](https://godoc.org/github.com/free/concurrent-writer)
* [crunch](https://github.com/superwhiskers/crunch) **star:23** Go package implementing buffers for handling various datatypes easily.   [![godoc][GoDoc]](https://godoc.org/github.com/superwhiskers/crunch)
* [pipeline](https://github.com/hyfather/pipeline) **star:21** An implementation of pipelines with fan-in and fan-out.   [![It hasn't been updated in the last year][Yellow]](https://github.com/hyfather/pipeline)   [![godoc][GoDoc]](https://godoc.org/github.com/hyfather/pipeline)
* [goset](https://github.com/zoumo/goset) **star:20** A useful Set collection implementation for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/zoumo/goset)
* [deque](https://github.com/edwingeng/deque) **star:15** A highly optimized double-ended queue.   [![There was an update last week][Green]](https://github.com/edwingeng/deque)   [![godoc][GoDoc]](https://godoc.org/github.com/edwingeng/deque)
* [typ](https://github.com/gurukami/typ) **star:15** Null Types, Safe primitive type conversion and fetching value from complex structures.   [![godoc][GoDoc]](https://godoc.org/github.com/gurukami/typ)
* [hide](https://github.com/emvi/hide) **star:14** ID type with marshalling to/from hash to prevent sending IDs to clients.   [![It hasn't been updated in the last year][Yellow]](https://github.com/emvi/hide)   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/hide)
* [go-ef](https://github.com/amallia/go-ef) **star:11** A Go implementation of the Elias-Fano encoding.   [![It hasn't been updated in the last year][Yellow]](https://github.com/amallia/go-ef)   [![godoc][GoDoc]](https://godoc.org/github.com/amallia/go-ef)
* [dict](https://github.com/srfrog/dict) **star:11** Python-like dictionaries (dict) for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/srfrog/dict)
* [mspm](https://github.com/BlackRabbitt/mspm) **star:9** Multi-String Pattern Matching Algorithm for information retrieval.   [![It hasn't been updated in the last year][Yellow]](https://github.com/BlackRabbitt/mspm)   [![godoc][GoDoc]](https://godoc.org/github.com/BlackRabbitt/mspm)
* [null](https://github.com/emvi/null) **star:9** Nullable Go types that can be marshalled/unmarshalled to/from JSON.   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/null)
* [set](https://github.com/StudioSol/set) **star:7** Simple set data structure implementation in Go using LinkedHashMap.   [![godoc][GoDoc]](https://godoc.org/github.com/StudioSol/set)
* [ptrie](https://github.com/viant/ptrie) **star:7** An implementation of prefix tree.   [![godoc][GoDoc]](https://godoc.org/github.com/viant/ptrie)
* [treap](https://github.com/perdata/treap) **star:7** Persistent, fast ordered map using tree heaps.   [![godoc][GoDoc]](https://godoc.org/github.com/perdata/treap)
* [timedmap](https://github.com/zekroTJA/timedmap) **star:6** Map with expiring key-value pairs.   [![godoc][GoDoc]](https://godoc.org/github.com/zekroTJA/timedmap)
* [gofal](https://github.com/xxjwxc/gofal) **star:6** fractional api for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/xxjwxc/gofal)   [![Contains Chinese documents][CN]](https://github.com/xxjwxc/gofal)
* [parsefields](https://github.com/MonaxGT/parsefields) **star:3** Tools for parse JSON-like logs for collecting unique fields and events.   [![godoc][GoDoc]](https://godoc.org/github.com/MonaxGT/parsefields)

## Database

*Databases implemented in Go.*

* [prometheus](https://github.com/prometheus/prometheus) **star:29498** Monitoring system and time series database.   [![star > 2000][Awesome]](https://github.com/prometheus/prometheus)   [![There was an update last week][Green]](https://github.com/prometheus/prometheus)   [![godoc][GoDoc]](https://godoc.org/github.com/prometheus/prometheus)
* [tidb](https://github.com/pingcap/tidb) **star:22728** TiDB is a distributed SQL database. Inspired by the design of Google F1.   [![star > 2000][Awesome]](https://github.com/pingcap/tidb)   [![There was an update last week][Green]](https://github.com/pingcap/tidb)   [![godoc][GoDoc]](https://godoc.org/github.com/pingcap/tidb)   [![Contains Chinese documents][CN]](https://github.com/pingcap/tidb)
* [influxdb](https://github.com/influxdb/influxdb) **star:18449** Scalable datastore for metrics, events, and real-time analytics.   [![star > 2000][Awesome]](https://github.com/influxdb/influxdb)   [![There was an update last week][Green]](https://github.com/influxdb/influxdb)   [![godoc][GoDoc]](https://godoc.org/github.com/influxdb/influxdb)
* [cockroach](https://github.com/cockroachdb/cockroach) **star:17876** Scalable, Geo-Replicated, Transactional Datastore.   [![star > 2000][Awesome]](https://github.com/cockroachdb/cockroach)   [![There was an update last week][Green]](https://github.com/cockroachdb/cockroach)   [![godoc][GoDoc]](https://godoc.org/github.com/cockroachdb/cockroach)
* [dgraph](https://github.com/dgraph-io/dgraph) **star:12605** Scalable, Distributed, Low Latency, High Throughput Graph Database.   [![star > 2000][Awesome]](https://github.com/dgraph-io/dgraph)   [![There was an update last week][Green]](https://github.com/dgraph-io/dgraph)   [![godoc][GoDoc]](https://godoc.org/github.com/dgraph-io/dgraph)
* [groupcache](https://github.com/golang/groupcache) **star:8410** Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.   [![star > 2000][Awesome]](https://github.com/golang/groupcache)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/groupcache)
* [badger](https://github.com/dgraph-io/badger) **star:7373** Fast key-value store in Go.   [![star > 2000][Awesome]](https://github.com/dgraph-io/badger)   [![There was an update last week][Green]](https://github.com/dgraph-io/badger)   [![godoc][GoDoc]](https://godoc.org/github.com/dgraph-io/badger)
* [rqlite](https://github.com/rqlite/rqlite) **star:5700** The lightweight, distributed, relational database built on SQLite.   [![star > 2000][Awesome]](https://github.com/rqlite/rqlite)   [![godoc][GoDoc]](https://godoc.org/github.com/rqlite/rqlite)
* [BigCache](https://github.com/allegro/bigcache) **star:3631** Efficient key/value cache for gigabytes of data.   [![star > 2000][Awesome]](https://github.com/allegro/bigcache)   [![godoc][GoDoc]](https://godoc.org/github.com/allegro/bigcache)
* [goleveldb](https://github.com/syndtr/goleveldb) **star:3589** Implementation of the [LevelDB](https://github.com/google/leveldb) key/value database in Go.   [![star > 2000][Awesome]](https://github.com/syndtr/goleveldb)   [![godoc][GoDoc]](https://godoc.org/github.com/syndtr/goleveldb)
* [go-cache](https://github.com/pmylund/go-cache) **star:3542** In-memory key:value store/cache (similar to Memcached) library for Go, suitable for single-machine applications.   [![star > 2000][Awesome]](https://github.com/pmylund/go-cache)   [![godoc][GoDoc]](https://godoc.org/github.com/pmylund/go-cache)
* [ledisdb](https://github.com/siddontang/ledisdb) **star:3237** Ledisdb is a high performance NoSQL like Redis based on LevelDB.   [![star > 2000][Awesome]](https://github.com/siddontang/ledisdb)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/ledisdb)
* [bbolt](https://github.com/etcd-io/bbolt) **star:3024** An embedded key/value database for Go.   [![star > 2000][Awesome]](https://github.com/etcd-io/bbolt)   [![There was an update last week][Green]](https://github.com/etcd-io/bbolt)   [![godoc][GoDoc]](https://godoc.org/github.com/etcd-io/bbolt)
* [buntdb](https://github.com/tidwall/buntdb) **star:2649** Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.   [![star > 2000][Awesome]](https://github.com/tidwall/buntdb)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/buntdb)
* [tiedot](https://github.com/HouzuoGuo/tiedot) **star:2460** Your NoSQL database powered by Golang.   [![star > 2000][Awesome]](https://github.com/HouzuoGuo/tiedot)   [![godoc][GoDoc]](https://godoc.org/github.com/HouzuoGuo/tiedot)
* [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) **star:1898** fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.   [![There was an update last week][Green]](https://github.com/VictoriaMetrics/VictoriaMetrics)   [![godoc][GoDoc]](https://godoc.org/github.com/VictoriaMetrics/VictoriaMetrics)
* [cache2go](https://github.com/muesli/cache2go) **star:1222** In-memory key:value cache which supports automatic invalidation based on timeouts.   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/cache2go)
* [nutsdb](https://github.com/xujiajun/nutsdb) **star:1100** Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as  list, set, sorted set.   [![There was an update last week][Green]](https://github.com/xujiajun/nutsdb)   [![godoc][GoDoc]](https://godoc.org/github.com/xujiajun/nutsdb)   [![Contains Chinese documents][CN]](https://github.com/xujiajun/nutsdb)
* [GCache](https://github.com/bluele/gcache) **star:1067** Cache library with support for expirable Cache, LFU, LRU and ARC.   [![godoc][GoDoc]](https://godoc.org/github.com/bluele/gcache)
* [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) **star:1002** CovenantSQL is a SQL database on blockchain.   [![godoc][GoDoc]](https://godoc.org/github.com/CovenantSQL/CovenantSQL)
* [diskv](https://github.com/peterbourgon/diskv) **star:860** Home-grown disk-backed key-value store.   [![godoc][GoDoc]](https://godoc.org/github.com/peterbourgon/diskv)
* [moss](https://github.com/couchbase/moss) **star:755** Moss is a simple LSM key-value storage engine written in 100% Go.   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/moss)
* [fastcache](https://github.com/VictoriaMetrics/fastcache) **star:717** fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.   [![There was an update last week][Green]](https://github.com/VictoriaMetrics/fastcache)   [![godoc][GoDoc]](https://godoc.org/github.com/VictoriaMetrics/fastcache)
* [eliasdb](https://github.com/krotik/eliasdb) **star:558** Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.   [![There was an update last week][Green]](https://github.com/krotik/eliasdb)   [![godoc][GoDoc]](https://godoc.org/github.com/krotik/eliasdb)
* [levigo](https://github.com/jmhodges/levigo) **star:378** Levigo is a Go wrapper for LevelDB.   [![godoc][GoDoc]](https://godoc.org/github.com/jmhodges/levigo)
* [Bitcask](https://github.com/prologic/bitcask) **star:300** Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).   [![There was an update last week][Green]](https://github.com/prologic/bitcask)   [![godoc][GoDoc]](https://godoc.org/github.com/prologic/bitcask)
* [pudge](https://github.com/recoilme/pudge) **star:247** Fast and simple  key/value store written using Go's standard library.   [![godoc][GoDoc]](https://godoc.org/github.com/recoilme/pudge)
* [piladb](https://github.com/fern4lvarez/piladb) **star:173** Lightweight RESTful database engine based on stack data structures.   [![It hasn't been updated in the last year][Yellow]](https://github.com/fern4lvarez/piladb)   [![godoc][GoDoc]](https://godoc.org/github.com/fern4lvarez/piladb)
* [Vasto](https://github.com/chrislusf/vasto) **star:169** A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.   [![It hasn't been updated in the last year][Yellow]](https://github.com/chrislusf/vasto)   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/vasto)
* [Kivik](https://github.com/go-kivik/kivik) **star:155** Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.   [![godoc][GoDoc]](https://godoc.org/github.com/go-kivik/kivik)
* [slowpoke](https://github.com/recoilme/slowpoke) **star:93** Key-value store with persistence.   [![godoc][GoDoc]](https://godoc.org/github.com/recoilme/slowpoke)
* [Scribble](https://github.com/nanobox-io/golang-scribble) **star:88** Tiny flat file JSON store.   [![It hasn't been updated in the last year][Yellow]](https://github.com/nanobox-io/golang-scribble)   [![godoc][GoDoc]](https://godoc.org/github.com/nanobox-io/golang-scribble)
* [couchcache](https://github.com/codingsince1985/couchcache) **star:47** RESTful caching micro-service backed by Couchbase server.   [![godoc][GoDoc]](https://godoc.org/github.com/codingsince1985/couchcache)
* [bcache](https://github.com/iwanbk/bcache) **star:43** Eventually consistent distributed in-memory  cache Go library.   [![godoc][GoDoc]](https://godoc.org/github.com/iwanbk/bcache)
* [cache](https://github.com/akyoto/cache) **star:34** In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.   [![godoc][GoDoc]](https://godoc.org/github.com/akyoto/cache)
* [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) **star:33** BigCache with clustering support and individual item expiration.   [![It hasn't been updated in the last year][Yellow]](https://github.com/oaStuff/clusteredBigCache)   [![godoc][GoDoc]](https://godoc.org/github.com/oaStuff/clusteredBigCache)
* [Databunker](https://github.com/paranoidguy/databunker) **star:32** Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.   [![There was an update last week][Green]](https://github.com/paranoidguy/databunker)   [![godoc][GoDoc]](https://godoc.org/github.com/paranoidguy/databunker)
* [Coffer](https://github.com/claygod/coffer) **star:20** Simple ACID key-value database that supports transactions.   [![godoc][GoDoc]](https://godoc.org/github.com/claygod/coffer)
* [tempdb](https://github.com/rafaeljesus/tempdb) **star:14** Key-value store for temporary items.   [![It hasn't been updated in the last year][Yellow]](https://github.com/rafaeljesus/tempdb)   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/tempdb)
* [gorocksdb](https://github.com/kapitan-k/gorocksdb) **star:12** Gorocksdb is a wrapper for [RocksDB](https://rocksdb.org) written in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/kapitan-k/gorocksdb)   [![godoc][GoDoc]](https://godoc.org/github.com/kapitan-k/gorocksdb)
* [tracedb](https://github.com/unit-io/tracedb) **star:7** Fast timeseries database for IoT, realtime messaging  applications. Access tracedb with pubsub over tcp or websocket using github.com/unit-io/trace application.   [![There was an update last week][Green]](https://github.com/unit-io/tracedb)   [![godoc][GoDoc]](https://godoc.org/github.com/unit-io/tracedb)
* [gostore](https://github.com/twharmon/gostore) **star:3** Gostore is a simple, durable, embedded key-value storage engine written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/twharmon/gostore)

*Database schema migration.*

* [migrate](https://github.com/golang-migrate/migrate) **star:3795** Database migrations. CLI and Golang library.   [![star > 2000][Awesome]](https://github.com/golang-migrate/migrate)   [![There was an update last week][Green]](https://github.com/golang-migrate/migrate)   [![godoc][GoDoc]](https://godoc.org/github.com/golang-migrate/migrate)
* [sql-migrate](https://github.com/rubenv/sql-migrate) **star:1629** Database migration tool. Allows embedding migrations into the application using go-bindata.   [![godoc][GoDoc]](https://godoc.org/github.com/rubenv/sql-migrate)
* [skeema](https://github.com/skeema/skeema) **star:629** Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.   [![There was an update last week][Green]](https://github.com/skeema/skeema)   [![godoc][GoDoc]](https://godoc.org/github.com/skeema/skeema)
* [soda](https://github.com/gobuffalo/pop/tree/master/soda)  Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
* [gormigrate](https://github.com/go-gormigrate/gormigrate) **star:415** Database schema migration helper for Gorm ORM.   [![godoc][GoDoc]](https://godoc.org/github.com/go-gormigrate/gormigrate)
* [goose](https://github.com/steinbacher/goose) **star:135** Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.   [![It hasn't been updated in the last year][Yellow]](https://github.com/steinbacher/goose)   [![godoc][GoDoc]](https://godoc.org/github.com/steinbacher/goose)
* [darwin](https://github.com/GuiaBolso/darwin) **star:99** Database schema evolution library for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/GuiaBolso/darwin)
* [migrator](https://github.com/lopezator/migrator) **star:89** Dead simple Go database migration library.   [![godoc][GoDoc]](https://godoc.org/github.com/lopezator/migrator)
* [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) **star:45** A Go package to help write migrations with go-pg/pg.   [![godoc][GoDoc]](https://godoc.org/github.com/robinjoseph08/go-pg-migrations)
* [gondolier](https://github.com/emvi/gondolier) **star:28** Database migration library using struct decorators.   [![godoc][GoDoc]](https://godoc.org/github.com/emvi/gondolier)
* [pravasan](https://github.com/pravasan/pravasan) **star:24** Simple Migration tool - currently for MySQL but planning to soon support Postgres, SQLite, MongoDB, etc.   [![It hasn't been updated in the last year][Yellow]](https://github.com/pravasan/pravasan)
* [go-fixtures](https://github.com/RichardKnop/go-fixtures) **star:23** Django style fixtures for Golang's excellent built-in database/sql library.   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/go-fixtures)
* [avro](https://github.com/khezen/avro) **star:11** Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.   [![There was an update last week][Green]](https://github.com/khezen/avro)   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/avro)
* [schema](https://github.com/adlio/schema) **star:4** Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.   [![godoc][GoDoc]](https://godoc.org/github.com/adlio/schema)

*Database tools.*

* [vitess](https://github.com/youtube/vitess) **star:9642** vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.   [![star > 2000][Awesome]](https://github.com/youtube/vitess)   [![There was an update last week][Green]](https://github.com/youtube/vitess)   [![godoc][GoDoc]](https://godoc.org/github.com/youtube/vitess)
* [pgweb](https://github.com/sosedoff/pgweb) **star:6300** Web-based PostgreSQL database browser.   [![star > 2000][Awesome]](https://github.com/sosedoff/pgweb)   [![godoc][GoDoc]](https://godoc.org/github.com/sosedoff/pgweb)
* [kingshard](https://github.com/flike/kingshard) **star:5031** kingshard is a high performance proxy for MySQL powered by Golang.   [![star > 2000][Awesome]](https://github.com/flike/kingshard)   [![godoc][GoDoc]](https://godoc.org/github.com/flike/kingshard)   [![Contains Chinese documents][CN]](https://github.com/flike/kingshard)
* [orchestrator](https://github.com/github/orchestrator) **star:3407** MySQL replication topology manager & visualizer.   [![star > 2000][Awesome]](https://github.com/github/orchestrator)   [![There was an update last week][Green]](https://github.com/github/orchestrator)   [![godoc][GoDoc]](https://godoc.org/github.com/github/orchestrator)
* [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) **star:2812** Sync your MySQL data into Elasticsearch automatically.   [![star > 2000][Awesome]](https://github.com/siddontang/go-mysql-elasticsearch)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-mysql-elasticsearch)
* [go-mysql](https://github.com/siddontang/go-mysql) **star:2257** Go toolset to handle MySQL protocol and replication.   [![star > 2000][Awesome]](https://github.com/siddontang/go-mysql)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-mysql)
* [pREST](https://github.com/nuveo/prest) **star:2211** Serve a RESTful API from any PostgreSQL database.   [![star > 2000][Awesome]](https://github.com/nuveo/prest)   [![godoc][GoDoc]](https://godoc.org/github.com/nuveo/prest)
* [chproxy](https://github.com/Vertamedia/chproxy) **star:374** HTTP proxy for ClickHouse database.   [![godoc][GoDoc]](https://godoc.org/github.com/Vertamedia/chproxy)
* [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) **star:179** Collects small insterts and sends big requests to ClickHouse servers.   [![There was an update last week][Green]](https://github.com/nikepan/clickhouse-bulk)   [![godoc][GoDoc]](https://godoc.org/github.com/nikepan/clickhouse-bulk)
* [myreplication](https://github.com/2tvenom/myreplication) **star:156** MySql binary log replication listener. Supports statement and row based replication.   [![It hasn't been updated in the last year][Yellow]](https://github.com/2tvenom/myreplication)   [![godoc][GoDoc]](https://godoc.org/github.com/2tvenom/myreplication)
* [octillery](https://github.com/knocknote/octillery) **star:74** Go package for sharding databases ( Supports every ORM or raw SQL ).   [![godoc][GoDoc]](https://godoc.org/github.com/knocknote/octillery)
* [dbbench](https://github.com/sj14/dbbench) **star:35** Database benchmarking tool with support for several databases and scripts.   [![There was an update last week][Green]](https://github.com/sj14/dbbench)   [![godoc][GoDoc]](https://godoc.org/github.com/sj14/dbbench)
* [prep](https://github.com/hexdigest/prep) **star:25** Use prepared SQL statements without changing your code.   [![It hasn't been updated in the last year][Yellow]](https://github.com/hexdigest/prep)   [![godoc][GoDoc]](https://godoc.org/github.com/hexdigest/prep)
* [datagen](https://github.com/codingconcepts/datagen) **star:15** A fast data generator that's multi-table aware and supports multi-row DML.   [![There was an update last week][Green]](https://github.com/codingconcepts/datagen)   [![godoc][GoDoc]](https://godoc.org/github.com/codingconcepts/datagen)
* [rwdb](https://github.com/andizzle/rwdb) **star:11** rwdb provides read replica capability for multiple database servers setup.   [![It hasn't been updated in the last year][Yellow]](https://github.com/andizzle/rwdb)   [![godoc][GoDoc]](https://godoc.org/github.com/andizzle/rwdb)
* [bucket](https://github.com/PumpkinSeed/bucket) **star:6** Optimized data structure framework for Couchbase specialized on one bucket usage.   [![godoc][GoDoc]](https://godoc.org/github.com/PumpkinSeed/bucket)

*SQL query builder, libraries for building and using SQL.*

* [Squirrel](https://github.com/Masterminds/squirrel) **star:2782** Go library that helps you build SQL queries.   [![star > 2000][Awesome]](https://github.com/Masterminds/squirrel)   [![There was an update last week][Green]](https://github.com/Masterminds/squirrel)   [![godoc][GoDoc]](https://godoc.org/github.com/Masterminds/squirrel)
* [xo](https://github.com/knq/xo) **star:2387** Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.   [![star > 2000][Awesome]](https://github.com/knq/xo)   [![godoc][GoDoc]](https://godoc.org/github.com/knq/xo)
* [gendry](https://github.com/didi/gendry) **star:952** Non-invasive SQL builder and powerful data binder.   [![There was an update last week][Green]](https://github.com/didi/gendry)   [![godoc][GoDoc]](https://godoc.org/github.com/didi/gendry)   [![Contains Chinese documents][CN]](https://github.com/didi/gendry)
* [goqu](https://github.com/doug-martin/goqu) **star:737** Idiomatic SQL builder and query library.   [![godoc][GoDoc]](https://godoc.org/github.com/doug-martin/goqu)
* [Dotsql](https://github.com/gchaincl/dotsql) **star:506** Go library that helps you keep sql files in one place and use them with ease.   [![godoc][GoDoc]](https://godoc.org/github.com/gchaincl/dotsql)
* [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) **star:460** Powerful data retrieval methods as well as DB-agnostic query building capabilities.   [![godoc][GoDoc]](https://godoc.org/github.com/go-ozzo/ozzo-dbx)
* [jet](https://github.com/go-jet/jet) **star:228** Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.   [![There was an update last week][Green]](https://github.com/go-jet/jet)   [![godoc][GoDoc]](https://godoc.org/github.com/go-jet/jet)
* [sqrl](https://github.com/elgris/sqrl) **star:201** SQL query builder, fork of Squirrel with improved performance.   [![godoc][GoDoc]](https://godoc.org/github.com/elgris/sqrl)
* [Squalus](https://gitlab.com/qosenergy/squalus)  Thin layer over the Go SQL package that makes it easier to perform queries.
* [dbq](https://github.com/rocketlaunchr/dbq) **star:96** Zero boilerplate database operations for Go.   [![There was an update last week][Green]](https://github.com/rocketlaunchr/dbq)   [![godoc][GoDoc]](https://godoc.org/github.com/rocketlaunchr/dbq)
* [igor](https://github.com/galeone/igor) **star:81** Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.   [![godoc][GoDoc]](https://godoc.org/github.com/galeone/igor)
* [godbal](https://github.com/xujiajun/godbal) **star:50** Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.   [![It hasn't been updated in the last year][Yellow]](https://github.com/xujiajun/godbal)   [![godoc][GoDoc]](https://godoc.org/github.com/xujiajun/godbal)
* [sqlf](https://github.com/leporo/sqlf) **star:7** Fast SQL query builder.   [![godoc][GoDoc]](https://godoc.org/github.com/leporo/sqlf)
* [qry](https://github.com/HnH/qry) **star:6** Tool that generates constants from files with raw SQL queries.   [![godoc][GoDoc]](https://godoc.org/github.com/HnH/qry)
* [mpath](https://github.com/spacetab-io/mpath-go) **star:5** MPTT (Modified Preorder Tree Traversal) package for SQL records - materialized path realisation.   [![godoc][GoDoc]](https://godoc.org/github.com/spacetab-io/mpath-go)
* [ormlite](https://github.com/pupizoid/ormlite)  Lightweight package containing some ORM-like features and helpers for sqlite databases.

## Database Drivers

*Libraries for connecting and operating databases.*

* Relational Databases
    * [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) **star:9083** MySQL driver for Go.   [![star > 2000][Awesome]](https://github.com/go-sql-driver/mysql)   [![godoc][GoDoc]](https://godoc.org/github.com/go-sql-driver/mysql)
    * [pq](https://github.com/lib/pq) **star:5698** Pure Go Postgres driver for database/sql.   [![star > 2000][Awesome]](https://github.com/lib/pq)   [![godoc][GoDoc]](https://godoc.org/github.com/lib/pq)
    * [go-sqlite3](https://github.com/mattn/go-sqlite3) **star:3856** SQLite3 driver for go that uses database/sql.   [![star > 2000][Awesome]](https://github.com/mattn/go-sqlite3)
    * [pgx](https://github.com/jackc/pgx) **star:2418** PostgreSQL driver supporting features beyond those exposed by database/sql.   [![star > 2000][Awesome]](https://github.com/jackc/pgx)   [![There was an update last week][Green]](https://github.com/jackc/pgx)   [![godoc][GoDoc]](https://godoc.org/github.com/jackc/pgx)
    * [go-mssqldb](https://github.com/denisenkom/go-mssqldb) **star:1152** Microsoft MSSQL driver for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/denisenkom/go-mssqldb)
    * [go-oci8](https://github.com/mattn/go-oci8) **star:444** Oracle driver for go that uses database/sql.   [![There was an update last week][Green]](https://github.com/mattn/go-oci8)   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-oci8)
    * [goracle](https://github.com/go-goracle/goracle) **star:280** Oracle driver for Go, using the ODPI-C driver.
    * [firebirdsql](https://github.com/nakagami/firebirdsql) **star:119** Firebird RDBMS SQL driver for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/nakagami/firebirdsql)
    * [go-adodb](https://github.com/mattn/go-adodb) **star:102** Microsoft ActiveX Object DataBase driver for go that uses database/sql.   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/go-adodb)
    * [gofreetds](https://github.com/minus5/gofreetds) **star:98** Microsoft MSSQL driver. Go wrapper over [FreeTDS](http://www.freetds.org).   [![It hasn't been updated in the last year][Yellow]](https://github.com/minus5/gofreetds)   [![godoc][GoDoc]](https://godoc.org/github.com/minus5/gofreetds)
    * [avatica](https://github.com/apache/calcite-avatica-go) **star:46** Apache Avatica/Phoenix SQL driver for database/sql.   [![godoc][GoDoc]](https://godoc.org/github.com/apache/calcite-avatica-go)
    * [bgc](https://github.com/viant/bgc) **star:13** Datastore Connectivity for BigQuery for go.   [![godoc][GoDoc]](https://godoc.org/github.com/viant/bgc)

* NoSQL Databases
    * [redis](https://github.com/go-redis/redis) **star:8181** Redis client for Golang.   [![star > 2000][Awesome]](https://github.com/go-redis/redis)   [![There was an update last week][Green]](https://github.com/go-redis/redis)   [![godoc][GoDoc]](https://godoc.org/github.com/go-redis/redis)
    * [redigo](https://github.com/gomodule/redigo) **star:7041** Redigo is a Go client for the Redis database.   [![star > 2000][Awesome]](https://github.com/gomodule/redigo)   [![There was an update last week][Green]](https://github.com/gomodule/redigo)   [![godoc][GoDoc]](https://godoc.org/github.com/gomodule/redigo)
    * [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) **star:4093** Official MongoDB driver for the Go language.   [![star > 2000][Awesome]](https://github.com/mongodb/mongo-go-driver)   [![There was an update last week][Green]](https://github.com/mongodb/mongo-go-driver)   [![godoc][GoDoc]](https://godoc.org/github.com/mongodb/mongo-go-driver)
    * [mgo](https://github.com/globalsign/mgo) **star:1754** (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.   [![godoc][GoDoc]](https://godoc.org/github.com/globalsign/mgo)
    * [gorethink](https://github.com/dancannon/gorethink) **star:1499** Go language driver for RethinkDB.   [![There was an update last week][Green]](https://github.com/dancannon/gorethink)   [![godoc][GoDoc]](https://godoc.org/github.com/dancannon/gorethink)
    * [redeo](https://github.com/bsm/redeo) **star:368** Redis-protocol compatible TCP servers/services.   [![godoc][GoDoc]](https://godoc.org/github.com/bsm/redeo)
    * [neoism](https://github.com/jmcvetta/neoism) **star:362** Neo4j client for Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/jmcvetta/neoism)
    * [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) **star:315** Aerospike client in Go language.   [![There was an update last week][Green]](https://github.com/aerospike/aerospike-client-go)   [![godoc][GoDoc]](https://godoc.org/github.com/aerospike/aerospike-client-go)
    * [gocb](https://github.com/couchbase/gocb) **star:307** Official Couchbase Go SDK.   [![There was an update last week][Green]](https://github.com/couchbase/gocb)   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/gocb)
    * [gocql](http://gocql.github.io)  Go language driver for Apache Cassandra.
    * [go-couchbase](https://github.com/couchbase/go-couchbase) **star:298** Couchbase client in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/go-couchbase)
    * [go-rejson](https://github.com/nitishm/go-rejson) **star:116** Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.   [![godoc][GoDoc]](https://godoc.org/github.com/nitishm/go-rejson)
    * [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) **star:74** Neo4j REST Client in golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/davemeehan/Neo4j-GO)   [![godoc][GoDoc]](https://godoc.org/github.com/davemeehan/Neo4j-GO)
    * [godis](https://github.com/piaohao/godis) **star:72** redis client implement by golang, inspired by jedis.   [![godoc][GoDoc]](https://godoc.org/github.com/piaohao/godis)
    * [arangolite](https://github.com/solher/arangolite) **star:66** Lightweight golang driver for ArangoDB.   [![godoc][GoDoc]](https://godoc.org/github.com/solher/arangolite)
    * [dynago](https://github.com/underarmour/dynago) **star:66** Dynago is a principle of least surprise client for DynamoDB.   [![It hasn't been updated in the last year][Yellow]](https://github.com/underarmour/dynago)   [![godoc][GoDoc]](https://godoc.org/github.com/underarmour/dynago)
    * [mgm](https://github.com/kamva/mgm) **star:60** MongoDB model-based ODM for Go (based on official MongoDB driver).   [![There was an update last week][Green]](https://github.com/kamva/mgm)   [![godoc][GoDoc]](https://godoc.org/github.com/kamva/mgm)
    * [go-pilosa](https://github.com/pilosa/go-pilosa) **star:34** Go client library for Pilosa.   [![There was an update last week][Green]](https://github.com/pilosa/go-pilosa)   [![godoc][GoDoc]](https://godoc.org/github.com/pilosa/go-pilosa)
    * [forestdb](https://github.com/couchbase/goforestdb) **star:28** Go bindings for ForestDB.   [![It hasn't been updated in the last year][Yellow]](https://github.com/couchbase/goforestdb)   [![godoc][GoDoc]](https://godoc.org/github.com/couchbase/goforestdb)
    * [neo4j](https://github.com/cihangir/neo4j) **star:25** Neo4j Rest API Bindings for Golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/cihangir/neo4j)   [![godoc][GoDoc]](https://godoc.org/github.com/cihangir/neo4j)
    * [goriak](https://github.com/zegl/goriak) **star:24** Go language driver for Riak KV.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zegl/goriak)   [![godoc][GoDoc]](https://godoc.org/github.com/zegl/goriak)
    * [xredis](https://github.com/shomali11/xredis) **star:10** Typesafe, customizable, clean & easy to use Redis client.   [![godoc][GoDoc]](https://godoc.org/github.com/shomali11/xredis)
    * [godscache](https://github.com/defcronyke/godscache) **star:7** A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.   [![It hasn't been updated in the last year][Yellow]](https://github.com/defcronyke/godscache)   [![godoc][GoDoc]](https://godoc.org/github.com/defcronyke/godscache)
    * [gomemcache](https://github.com/bradfitz/gomemcache/)  memcache client library for the Go programming language.
    * [asc](https://github.com/viant/asc) **star:4** Datastore Connectivity for Aerospike for go.   [![godoc][GoDoc]](https://godoc.org/github.com/viant/asc)

* Search and Analytic Databases.
    * [bleve](https://github.com/blevesearch/bleve) **star:6384** Modern text indexing library for go.   [![star > 2000][Awesome]](https://github.com/blevesearch/bleve)   [![There was an update last week][Green]](https://github.com/blevesearch/bleve)   [![godoc][GoDoc]](https://godoc.org/github.com/blevesearch/bleve)
    * [riot](https://github.com/go-ego/riot) **star:5077** Go Open Source, Distributed, Simple and efficient Search Engine.   [![star > 2000][Awesome]](https://github.com/go-ego/riot)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ego/riot)   [![Contains Chinese documents][CN]](https://github.com/go-ego/riot)
    * [elastic](https://github.com/olivere/elastic) **star:4781** Elasticsearch client for Go.   [![star > 2000][Awesome]](https://github.com/olivere/elastic)   [![There was an update last week][Green]](https://github.com/olivere/elastic)   [![godoc][GoDoc]](https://godoc.org/github.com/olivere/elastic)
    * [go-elasticsearch](https://github.com/elastic/go-elasticsearch) **star:2218** Official Elasticsearch client for Go.   [![star > 2000][Awesome]](https://github.com/elastic/go-elasticsearch)   [![There was an update last week][Green]](https://github.com/elastic/go-elasticsearch)   [![godoc][GoDoc]](https://godoc.org/github.com/elastic/go-elasticsearch)
    * [elastigo](https://github.com/mattbaird/elastigo) **star:952** Elasticsearch client library.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mattbaird/elastigo)   [![godoc][GoDoc]](https://godoc.org/github.com/mattbaird/elastigo)
    * [elasticsql](https://github.com/cch123/elasticsql) **star:494** Convert sql to elasticsearch dsl in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/cch123/elasticsql)
    * [skizze](https://github.com/seiflotfy/skizze) **star:72** probabilistic data-structures service and storage.   [![It hasn't been updated in the last year][Yellow]](https://github.com/seiflotfy/skizze)   [![godoc][GoDoc]](https://godoc.org/github.com/seiflotfy/skizze)
    * [goes](https://github.com/OwnLocal/goes) **star:24** Library to interact with Elasticsearch.   [![It hasn't been updated in the last year][Yellow]](https://github.com/OwnLocal/goes)   [![godoc][GoDoc]](https://godoc.org/github.com/OwnLocal/goes)

* Multiple Backends.
    * [cayley](https://github.com/google/cayley) **star:13243** Graph database with support for multiple backends.   [![star > 2000][Awesome]](https://github.com/google/cayley)   [![godoc][GoDoc]](https://godoc.org/github.com/google/cayley)
    * [gokv](https://github.com/philippgille/gokv) **star:176** Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).   [![There was an update last week][Green]](https://github.com/philippgille/gokv)   [![godoc][GoDoc]](https://godoc.org/github.com/philippgille/gokv)
    * [cachego](https://github.com/fabiorphp/cachego) **star:116** Golang Cache component for multiple drivers.   [![There was an update last week][Green]](https://github.com/fabiorphp/cachego)   [![godoc][GoDoc]](https://godoc.org/github.com/fabiorphp/cachego)
    * [dsc](https://github.com/viant/dsc) **star:18** Datastore connectivity for SQL, NoSQL, structured files.   [![godoc][GoDoc]](https://godoc.org/github.com/viant/dsc)

## Date and Time

*Libraries for working with dates and times.*

* [now](https://github.com/jinzhu/now) **star:2425** Now is a time toolkit for golang.   [![star > 2000][Awesome]](https://github.com/jinzhu/now)   [![godoc][GoDoc]](https://godoc.org/github.com/jinzhu/now)
* [dateparse](https://github.com/araddon/dateparse) **star:989** Parse date's without knowing format in advance.   [![godoc][GoDoc]](https://godoc.org/github.com/araddon/dateparse)
* [carbon](https://github.com/uniplaces/carbon) **star:435** Simple Time extension with a lot of util methods, ported from PHP Carbon library.   [![It hasn't been updated in the last year][Yellow]](https://github.com/uniplaces/carbon)   [![godoc][GoDoc]](https://godoc.org/github.com/uniplaces/carbon)
* [durafmt](https://github.com/hako/durafmt) **star:287** Time duration formatting library for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/hako/durafmt)
* [timeutil](https://github.com/leekchan/timeutil) **star:176** Useful extensions (Timedelta, Strftime, ...) to the golang's time package.   [![It hasn't been updated in the last year][Yellow]](https://github.com/leekchan/timeutil)   [![godoc][GoDoc]](https://godoc.org/github.com/leekchan/timeutil)
* [iso8601](https://github.com/relvacode/iso8601) **star:70** Efficiently parse ISO8601 date-times without regex.   [![It hasn't been updated in the last year][Yellow]](https://github.com/relvacode/iso8601)   [![godoc][GoDoc]](https://godoc.org/github.com/relvacode/iso8601)
* [timespan](https://github.com/SaidinWoT/timespan) **star:68** For interacting with intervals of time, defined as a start time and a duration.   [![godoc][GoDoc]](https://godoc.org/github.com/SaidinWoT/timespan)
* [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) **star:68** The implementation of the Persian (Solar Hijri) Calendar in Go (golang).   [![godoc][GoDoc]](https://godoc.org/github.com/yaa110/go-persian-calendar)
* [date](https://github.com/rickb777/date) **star:34** Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.   [![godoc][GoDoc]](https://godoc.org/github.com/rickb777/date)
* [feiertage](https://github.com/wlbr/feiertage) **star:25** Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...   [![godoc][GoDoc]](https://godoc.org/github.com/wlbr/feiertage)
* [go-sunrise](https://github.com/nathan-osman/go-sunrise) **star:21** Calculate the sunrise and sunset times for a given location.   [![It hasn't been updated in the last year][Yellow]](https://github.com/nathan-osman/go-sunrise)   [![godoc][GoDoc]](https://godoc.org/github.com/nathan-osman/go-sunrise)
* [kair](https://github.com/GuilhermeCaruso/kair) **star:15** Date and Time - Golang Formatting Library.   [![godoc][GoDoc]](https://godoc.org/github.com/GuilhermeCaruso/kair)
* [cronrange](https://github.com/1set/cronrange) **star:13** Parses Cron-style time range expressions, checks if the given time is within any ranges.   [![godoc][GoDoc]](https://godoc.org/github.com/1set/cronrange)
* [NullTime](https://github.com/kirillDanshin/nulltime) **star:10** Nullable `time.Time`.   [![It hasn't been updated in the last year][Yellow]](https://github.com/kirillDanshin/nulltime)   [![godoc][GoDoc]](https://godoc.org/github.com/kirillDanshin/nulltime)
* [tuesday](https://github.com/osteele/tuesday) **star:8** Ruby-compatible Strftime function.   [![It hasn't been updated in the last year][Yellow]](https://github.com/osteele/tuesday)   [![godoc][GoDoc]](https://godoc.org/github.com/osteele/tuesday)
* [strftime](https://github.com/awoodbeck/strftime) **star:4** C99-compatible strftime formatter.   [![It hasn't been updated in the last year][Yellow]](https://github.com/awoodbeck/strftime)   [![godoc][GoDoc]](https://godoc.org/github.com/awoodbeck/strftime)
* [go-week](https://github.com/stoewer/go-week) **star:2** An efficient package to work with ISO8601 week dates.   [![godoc][GoDoc]](https://godoc.org/github.com/stoewer/go-week)
* [go-str2duration](https://github.com/xhit/go-str2duration) **star:1** Convert string to duration. Support time.Duration returned string and more.   [![godoc][GoDoc]](https://godoc.org/github.com/xhit/go-str2duration)

## Distributed Systems

*Packages that help with building Distributed Systems.*

* [go-kit](https://github.com/go-kit/kit) **star:16373** Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.   [![star > 2000][Awesome]](https://github.com/go-kit/kit)   [![There was an update last week][Green]](https://github.com/go-kit/kit)   [![godoc][GoDoc]](https://godoc.org/github.com/go-kit/kit)
* [grpc-go](https://github.com/grpc/grpc-go) **star:10765** The Go language implementation of gRPC. HTTP/2 based RPC.   [![star > 2000][Awesome]](https://github.com/grpc/grpc-go)   [![There was an update last week][Green]](https://github.com/grpc/grpc-go)   [![godoc][GoDoc]](https://godoc.org/github.com/grpc/grpc-go)
* [micro](https://github.com/micro/micro) **star:7711** Pluggable microservice toolkit and distributed systems platform.   [![star > 2000][Awesome]](https://github.com/micro/micro)   [![There was an update last week][Green]](https://github.com/micro/micro)   [![godoc][GoDoc]](https://godoc.org/github.com/micro/micro)
* [NATS](https://github.com/nats-io/gnatsd) **star:7362** Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.   [![star > 2000][Awesome]](https://github.com/nats-io/gnatsd)   [![There was an update last week][Green]](https://github.com/nats-io/gnatsd)   [![godoc][GoDoc]](https://godoc.org/github.com/nats-io/gnatsd)
* [rpcx](https://github.com/smallnest/rpcx) **star:4422** Distributed pluggable RPC service framework like alibaba Dubbo.   [![star > 2000][Awesome]](https://github.com/smallnest/rpcx)   [![There was an update last week][Green]](https://github.com/smallnest/rpcx)   [![godoc][GoDoc]](https://godoc.org/github.com/smallnest/rpcx)
* [tendermint](https://github.com/tendermint/tendermint) **star:3526** High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.   [![star > 2000][Awesome]](https://github.com/tendermint/tendermint)   [![There was an update last week][Green]](https://github.com/tendermint/tendermint)   [![godoc][GoDoc]](https://godoc.org/github.com/tendermint/tendermint)
* [torrent](https://github.com/anacrolix/torrent) **star:3368** BitTorrent client package.   [![star > 2000][Awesome]](https://github.com/anacrolix/torrent)   [![godoc][GoDoc]](https://godoc.org/github.com/anacrolix/torrent)
* [raft](https://github.com/hashicorp/raft) **star:3290** Golang implementation of the Raft consensus protocol, by HashiCorp.   [![star > 2000][Awesome]](https://github.com/hashicorp/raft)   [![There was an update last week][Green]](https://github.com/hashicorp/raft)   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/raft)
* [raft](https://github.com/coreos/etcd/tree/master/raft)  Go implementation of the Raft consensus protocol, by CoreOS.
* [dragonboat](https://github.com/lni/dragonboat) **star:2899** A feature complete and high performance multi-group Raft library in Go.   [![star > 2000][Awesome]](https://github.com/lni/dragonboat)   [![There was an update last week][Green]](https://github.com/lni/dragonboat)   [![godoc][GoDoc]](https://godoc.org/github.com/lni/dragonboat)   [![Contains Chinese documents][CN]](https://github.com/lni/dragonboat)
* [glow](https://github.com/chrislusf/glow) **star:2756** Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.   [![star > 2000][Awesome]](https://github.com/chrislusf/glow)   [![It hasn't been updated in the last year][Yellow]](https://github.com/chrislusf/glow)   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/glow)
* [KrakenD](https://github.com/devopsfaith/krakend) **star:2420** Ultra performant API Gateway framework with middlewares.   [![star > 2000][Awesome]](https://github.com/devopsfaith/krakend)   [![There was an update last week][Green]](https://github.com/devopsfaith/krakend)   [![godoc][GoDoc]](https://godoc.org/github.com/devopsfaith/krakend)
* [gleam](https://github.com/chrislusf/gleam) **star:2401** Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.   [![star > 2000][Awesome]](https://github.com/chrislusf/gleam)   [![godoc][GoDoc]](https://godoc.org/github.com/chrislusf/gleam)
* [emitter-io](https://github.com/emitter-io/emitter) **star:2260** High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.   [![star > 2000][Awesome]](https://github.com/emitter-io/emitter)   [![There was an update last week][Green]](https://github.com/emitter-io/emitter)   [![godoc][GoDoc]](https://godoc.org/github.com/emitter-io/emitter)
* [liftbridge](https://github.com/liftbridge-io/liftbridge) **star:1476** Lightweight, fault-tolerant message streams for NATS.   [![There was an update last week][Green]](https://github.com/liftbridge-io/liftbridge)   [![godoc][GoDoc]](https://godoc.org/github.com/liftbridge-io/liftbridge)
* [hprose](https://github.com/hprose/hprose-golang) **star:1080** Very newbility RPC Library, support 25+ languages now.   [![godoc][GoDoc]](https://godoc.org/github.com/hprose/hprose-golang)   [![Contains Chinese documents][CN]](https://github.com/hprose/hprose-golang)
* [ringpop-go](https://github.com/uber/ringpop-go) **star:604** Scalable, fault-tolerant application-layer sharding for Go applications.   [![It hasn't been updated in the last year][Yellow]](https://github.com/uber/ringpop-go)   [![godoc][GoDoc]](https://godoc.org/github.com/uber/ringpop-go)
* [gorpc](https://github.com/valyala/gorpc) **star:578** Simple, fast and scalable RPC library for high load.   [![godoc][GoDoc]](https://godoc.org/github.com/valyala/gorpc)
* [go-health](https://github.com/InVisionApp/go-health) **star:534** Library for enabling asynchronous dependency health checks in your service.   [![godoc][GoDoc]](https://godoc.org/github.com/InVisionApp/go-health)
* [rain](https://github.com/cenkalti/rain) **star:478** BitTorrent client and library.   [![godoc][GoDoc]](https://godoc.org/github.com/cenkalti/rain)
* [digota](https://github.com/digota/digota) **star:325** grpc ecommerce microservice.   [![It hasn't been updated in the last year][Yellow]](https://github.com/digota/digota)   [![godoc][GoDoc]](https://godoc.org/github.com/digota/digota)
* [dot](https://github.com/dotchain/dot/)  distributed sync using operational transformation/OT.
* [sleuth](https://github.com/ursiform/sleuth) **star:312** Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq)).   [![It hasn't been updated in the last year][Yellow]](https://github.com/ursiform/sleuth)   [![godoc][GoDoc]](https://godoc.org/github.com/ursiform/sleuth)
* [go-sundheit](https://github.com/AppsFlyer/go-sundheit) **star:291** A library built to provide support for defining async service health checks for golang services.   [![godoc][GoDoc]](https://godoc.org/github.com/AppsFlyer/go-sundheit)
* [go-jump](https://github.com/dgryski/go-jump) **star:281** Port of Google's "Jump" Consistent Hash function.   [![It hasn't been updated in the last year][Yellow]](https://github.com/dgryski/go-jump)   [![godoc][GoDoc]](https://godoc.org/github.com/dgryski/go-jump)
* [consistent](https://github.com/buraksezer/consistent) **star:266** Consistent hashing with bounded loads.   [![godoc][GoDoc]](https://godoc.org/github.com/buraksezer/consistent)
* [dht](https://github.com/anacrolix/dht) **star:150** BitTorrent Kademlia DHT implementation.   [![godoc][GoDoc]](https://godoc.org/github.com/anacrolix/dht)
* [jsonrpc](https://github.com/osamingo/jsonrpc) **star:125** The jsonrpc package helps implement of JSON-RPC 2.0.   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/jsonrpc)
* [jsonrpc](https://github.com/ybbus/jsonrpc) **star:118** JSON-RPC 2.0 HTTP client implementation.   [![godoc][GoDoc]](https://godoc.org/github.com/ybbus/jsonrpc)
* [resgate](https://resgate.io/)  Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
* [redis-lock](https://github.com/bsm/redislock) **star:96** Simplified distributed locking implementation using Redis.   [![godoc][GoDoc]](https://godoc.org/github.com/bsm/redislock)
* [celeriac](https://github.com/svcavallar/celeriac.v1) **star:60** Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/svcavallar/celeriac.v1)   [![godoc][GoDoc]](https://godoc.org/github.com/svcavallar/celeriac.v1)
* [doublejump](https://github.com/edwingeng/doublejump) **star:50** A revamped Google's jump consistent hash.   [![godoc][GoDoc]](https://godoc.org/github.com/edwingeng/doublejump)
* [dynamolock](https://cirello.io/dynamolock)  DynamoDB-backed distributed locking implementation.
* [drmaa](https://github.com/dgruber/drmaa) **star:29** Job submission library for cluster schedulers based on the DRMAA standard.   [![It hasn't been updated in the last year][Yellow]](https://github.com/dgruber/drmaa)   [![godoc][GoDoc]](https://godoc.org/github.com/dgruber/drmaa)
* [pglock](https://cirello.io/pglock)  PostgreSQL-backed distributed locking implementation.
* [outboxer](https://github.com/italolelis/outboxer) **star:27** Outboxer is a go library that implements the outbox pattern.   [![There was an update last week][Green]](https://github.com/italolelis/outboxer)   [![godoc][GoDoc]](https://godoc.org/github.com/italolelis/outboxer)
* [flowgraph](https://github.com/vectaport/flowgraph) **star:25** flow-based programming package.   [![godoc][GoDoc]](https://godoc.org/github.com/vectaport/flowgraph)
* [go-pdu](https://github.com/pdupub/go-pdu) **star:11** A decentralized identity-based social network.   [![There was an update last week][Green]](https://github.com/pdupub/go-pdu)   [![godoc][GoDoc]](https://godoc.org/github.com/pdupub/go-pdu)
* [dynatomic](https://github.com/tylfin/dynatomic) **star:10** A library for using DynamoDB as an atomic counter.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tylfin/dynatomic)   [![godoc][GoDoc]](https://godoc.org/github.com/tylfin/dynatomic)

## Dynamic DNS

*Tools for updating dynamic DNS records.*

* [GoDNS](https://github.com/timothyye/godns) **star:551** A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/timothyye/godns)
* [DDNS](https://github.com/skibish/ddns) **star:131** Personal DDNS client with Digital Ocean Networking DNS as backend.   [![godoc][GoDoc]](https://godoc.org/github.com/skibish/ddns)
* [dyndns](https://gitlab.com/alcastle/dyndns)  Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.

## Email

*Libraries and tools that implement email creation and sending.*

* [MailHog](https://github.com/mailhog/MailHog) **star:6047** Email and SMTP testing with web and API interface.   [![star > 2000][Awesome]](https://github.com/mailhog/MailHog)   [![There was an update last week][Green]](https://github.com/mailhog/MailHog)   [![godoc][GoDoc]](https://godoc.org/github.com/mailhog/MailHog)
* [hermes](https://github.com/matcornic/hermes) **star:1900** Golang package that generates clean, responsive HTML e-mails.   [![godoc][GoDoc]](https://godoc.org/github.com/matcornic/hermes)
* [email](https://github.com/jordan-wright/email) **star:1258** A robust and flexible email library for Go.   [![There was an update last week][Green]](https://github.com/jordan-wright/email)   [![godoc][GoDoc]](https://godoc.org/github.com/jordan-wright/email)
* [go-imap](https://github.com/emersion/go-imap) **star:913** IMAP library for clients and servers.   [![There was an update last week][Green]](https://github.com/emersion/go-imap)   [![godoc][GoDoc]](https://godoc.org/github.com/emersion/go-imap)
* [SendGrid](https://github.com/sendgrid/sendgrid-go) **star:568** SendGrid's Go library for sending email.   [![There was an update last week][Green]](https://github.com/sendgrid/sendgrid-go)   [![godoc][GoDoc]](https://godoc.org/github.com/sendgrid/sendgrid-go)
* [chasquid](https://blitiri.com.ar/p/chasquid)  SMTP server written in Go.
* [mailgun-go](https://github.com/mailgun/mailgun-go) **star:443** Go library for sending mail with the Mailgun API.   [![godoc][GoDoc]](https://godoc.org/github.com/mailgun/mailgun-go)
* [Hectane](https://github.com/hectane/hectane) **star:181** Lightweight SMTP client providing an HTTP API.   [![godoc][GoDoc]](https://godoc.org/github.com/hectane/hectane)
* [douceur](https://github.com/aymerick/douceur) **star:174** CSS inliner for your HTML emails.   [![It hasn't been updated in the last year][Yellow]](https://github.com/aymerick/douceur)   [![godoc][GoDoc]](https://godoc.org/github.com/aymerick/douceur)
* [go-message](https://github.com/emersion/go-message) **star:142** Streaming library for the Internet Message Format and mail messages.   [![godoc][GoDoc]](https://godoc.org/github.com/emersion/go-message)
* [smtp](https://github.com/mailhog/smtp) **star:54** SMTP server protocol state machine.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mailhog/smtp)   [![godoc][GoDoc]](https://godoc.org/github.com/mailhog/smtp)
* [go-dkim](https://github.com/toorop/go-dkim) **star:52** DKIM library, to sign & verify email.   [![godoc][GoDoc]](https://godoc.org/github.com/toorop/go-dkim)
* [go-premailer](https://github.com/vanng822/go-premailer) **star:45** Inline styling for HTML mail in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/vanng822/go-premailer)
* [mailchain](https://github.com/mailchain/mailchain) **star:40** Send encrypted emails to blockchain addresses written in Go.   [![There was an update last week][Green]](https://github.com/mailchain/mailchain)   [![godoc][GoDoc]](https://godoc.org/github.com/mailchain/mailchain)
* [go-simple-mail](https://github.com/xhit/go-simple-mail) **star:19** Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.   [![godoc][GoDoc]](https://godoc.org/github.com/xhit/go-simple-mail)

## Embeddable Scripting Languages

*Embedding other languages inside your go code.*

* [otto](https://github.com/robertkrimen/otto) **star:5161** JavaScript interpreter written in Go.   [![star > 2000][Awesome]](https://github.com/robertkrimen/otto)   [![godoc][GoDoc]](https://godoc.org/github.com/robertkrimen/otto)
* [gopher-lua](https://github.com/yuin/gopher-lua) **star:3322** Lua 5.1 VM and compiler written in Go.   [![star > 2000][Awesome]](https://github.com/yuin/gopher-lua)   [![godoc][GoDoc]](https://godoc.org/github.com/yuin/gopher-lua)
* [go-lua](https://github.com/Shopify/go-lua) **star:1791** Port of the Lua 5.2 VM to pure Go.   [![godoc][GoDoc]](https://godoc.org/github.com/Shopify/go-lua)
* [tengo](https://github.com/d5/tengo) **star:1568** Bytecode compiled script language for Go.   [![There was an update last week][Green]](https://github.com/d5/tengo)   [![godoc][GoDoc]](https://godoc.org/github.com/d5/tengo)
* [expr](https://github.com/antonmedv/expr) **star:1139** an engine that can evaluate expressions.   [![There was an update last week][Green]](https://github.com/antonmedv/expr)   [![godoc][GoDoc]](https://godoc.org/github.com/antonmedv/expr)
* [go-python](https://github.com/sbinet/go-python) **star:1007** naive go bindings to the CPython C-API.   [![godoc][GoDoc]](https://godoc.org/github.com/sbinet/go-python)
* [anko](https://github.com/mattn/anko) **star:982** Scriptable interpreter written in Go.   [![There was an update last week][Green]](https://github.com/mattn/anko)   [![godoc][GoDoc]](https://godoc.org/github.com/mattn/anko)
* [go-php](https://github.com/deuill/go-php) **star:728** PHP bindings for Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/deuill/go-php)   [![godoc][GoDoc]](https://godoc.org/github.com/deuill/go-php)
* [go-duktape](https://github.com/olebedev/go-duktape) **star:686** Duktape JavaScript engine bindings for Go.   [![There was an update last week][Green]](https://github.com/olebedev/go-duktape)   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/go-duktape)
* [golua](https://github.com/aarzilli/golua) **star:467** Go bindings for Lua C API.
* [gisp](https://github.com/jcla1/gisp) **star:435** Simple LISP in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/jcla1/gisp)   [![godoc][GoDoc]](https://godoc.org/github.com/jcla1/gisp)
* [cel-go](https://github.com/google/cel-go) **star:375** Fast, portable, non-Turing complete expression evaluation with gradual typing.   [![There was an update last week][Green]](https://github.com/google/cel-go)   [![godoc][GoDoc]](https://godoc.org/github.com/google/cel-go)
* [gval](https://github.com/PaesslerAG/gval) **star:181** A highly customizable expression language written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/PaesslerAG/gval)
* [gentee](https://github.com/gentee/gentee) **star:45** Embeddable scripting programming language.   [![godoc][GoDoc]](https://godoc.org/github.com/gentee/gentee)
* [binder](https://github.com/alexeyco/binder) **star:34** Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua).   [![It hasn't been updated in the last year][Yellow]](https://github.com/alexeyco/binder)   [![godoc][GoDoc]](https://godoc.org/github.com/alexeyco/binder)
* [purl](https://github.com/ian-kent/purl) **star:29** Perl 5.18.2 embedded in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ian-kent/purl)   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/purl)
* [ngaro](https://github.com/db47h/ngaro) **star:19** Embeddable Ngaro VM implementation enabling scripting in Retro.   [![It hasn't been updated in the last year][Yellow]](https://github.com/db47h/ngaro)   [![godoc][GoDoc]](https://godoc.org/github.com/db47h/ngaro)

## Error Handling

*Libraries for handling errors.*

* [errors](https://github.com/pkg/errors) **star:5572** Package that provides simple error handling primitives.   [![star > 2000][Awesome]](https://github.com/pkg/errors)   [![godoc][GoDoc]](https://godoc.org/github.com/pkg/errors)
* [go-multierror](https://github.com/hashicorp/go-multierror) **star:815** Go (golang) package for representing a list of errors as a single error.   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/go-multierror)
* [errorx](https://github.com/joomcode/errorx) **star:608** A feature rich error package with stack traces, composition of errors and more.   [![There was an update last week][Green]](https://github.com/joomcode/errorx)   [![godoc][GoDoc]](https://godoc.org/github.com/joomcode/errorx)
* [tracerr](https://github.com/ztrue/tracerr) **star:591** Golang errors with stack trace and source fragments.   [![godoc][GoDoc]](https://godoc.org/github.com/ztrue/tracerr)
* [eris](https://github.com/rotisserie/eris) **star:578** A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.   [![There was an update last week][Green]](https://github.com/rotisserie/eris)   [![godoc][GoDoc]](https://godoc.org/github.com/rotisserie/eris)
* [errlog](https://github.com/snwfdhmp/errlog) **star:302** Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.   [![godoc][GoDoc]](https://godoc.org/github.com/snwfdhmp/errlog)
* [emperror](https://github.com/emperror/emperror) **star:113** Error handling tools and best practices for Go libraries and applications.   [![godoc][GoDoc]](https://godoc.org/github.com/emperror/emperror)
* [errors](https://github.com/emperror/errors) **star:42** Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.   [![godoc][GoDoc]](https://godoc.org/github.com/emperror/errors)
* [werr](https://github.com/txgruppi/werr) **star:13** Error Wrapper creates an wrapper for the error type in Go which captures the File, Line and Stack of where it was called.   [![It hasn't been updated in the last year][Yellow]](https://github.com/txgruppi/werr)   [![godoc][GoDoc]](https://godoc.org/github.com/txgruppi/werr)
* [errors](https://github.com/neuronlabs/errors) **star:3** Simple golang error handling with classification primitives.   [![godoc][GoDoc]](https://godoc.org/github.com/neuronlabs/errors)
* [errors](https://github.com/PumpkinSeed/errors) **star:2** The most simple error wrapper with awesome performance and minimal memory overhead.   [![godoc][GoDoc]](https://godoc.org/github.com/PumpkinSeed/errors)
* [Falcon](https://github.com/SonicRoshan/falcon) **star:2** A Simple Yet Highly Powerful Package For Error Handling.   [![godoc][GoDoc]](https://godoc.org/github.com/SonicRoshan/falcon)

## Files

*Libraries for handling files and file systems.*

* [afero](https://github.com/spf13/afero) **star:2604** FileSystem Abstraction System for Go.   [![star > 2000][Awesome]](https://github.com/spf13/afero)   [![godoc][GoDoc]](https://godoc.org/github.com/spf13/afero)
* [pdfcpu](https://github.com/pdfcpu/pdfcpu) **star:1339** PDF processor.   [![godoc][GoDoc]](https://godoc.org/github.com/pdfcpu/pdfcpu)
* [notify](https://github.com/rjeczalik/notify) **star:544** File system event notification library with simple API, similar to os/signal.   [![godoc][GoDoc]](https://godoc.org/github.com/rjeczalik/notify)
* [copy](https://github.com/otiai10/copy) **star:140** Copy directory recursively.   [![There was an update last week][Green]](https://github.com/otiai10/copy)   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/copy)
* [bigfile](https://github.com/bigfile/bigfile) **star:115** A file transfer system, support to manage files with http api, rpc call and ftp client.   [![godoc][GoDoc]](https://godoc.org/github.com/bigfile/bigfile)   [![Contains Chinese documents][CN]](https://github.com/bigfile/bigfile)
* [go-csv-tag](https://github.com/artonge/go-csv-tag) **star:64** Load csv file using tag.   [![godoc][GoDoc]](https://godoc.org/github.com/artonge/go-csv-tag)
* [opc](https://github.com/qmuntal/opc) **star:63** Load Open Packaging Conventions (OPC) files for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/opc)
* [stl](https://gitlab.com/russoj88/stl)  Modules to read and write STL (stereolithography) files.  Concurrent algorithm for reading.
* [skywalker](https://github.com/dixonwille/skywalker) **star:55** Package to allow one to concurrently go through a filesystem with ease.   [![It hasn't been updated in the last year][Yellow]](https://github.com/dixonwille/skywalker)   [![godoc][GoDoc]](https://godoc.org/github.com/dixonwille/skywalker)
* [vfs](https://github.com/C2FO/vfs) **star:47** A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.   [![godoc][GoDoc]](https://godoc.org/github.com/C2FO/vfs)
* [afs](https://github.com/viant/afs) **star:40** Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.   [![There was an update last week][Green]](https://github.com/viant/afs)   [![godoc][GoDoc]](https://godoc.org/github.com/viant/afs)
* [tarfs](https://github.com/posener/tarfs) **star:39** Implementation of the [`FileSystem` interface](https://godoc.org/github.com/kr/fs#FileSystem) for tar files.   [![It hasn't been updated in the last year][Yellow]](https://github.com/posener/tarfs)   [![godoc][GoDoc]](https://godoc.org/github.com/posener/tarfs)
* [go-exiftool](https://github.com/barasher/go-exiftool) **star:22** Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).   [![godoc][GoDoc]](https://godoc.org/github.com/barasher/go-exiftool)
* [gut/yos](https://github.com/1set/gut) **star:20** Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.   [![godoc][GoDoc]](https://godoc.org/github.com/1set/gut)
* [go-gtfs](https://github.com/artonge/go-gtfs) **star:20** Load gtfs files in go.   [![godoc][GoDoc]](https://godoc.org/github.com/artonge/go-gtfs)
* [checksum](https://github.com/codingsince1985/checksum) **star:17** Compute message digest, like MD5 and SHA256, for large files.   [![godoc][GoDoc]](https://godoc.org/github.com/codingsince1985/checksum)
* [flop](https://github.com/homedepot/flop) **star:15** File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).   [![godoc][GoDoc]](https://godoc.org/github.com/homedepot/flop)
* [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) **star:14** Copy files for humans.   [![godoc][GoDoc]](https://godoc.org/github.com/hugocarreira/go-decent-copy)
* [parquet](https://github.com/parsyl/parquet) **star:5** Read and write [parquet](https://parquet.apache.org) files.   [![godoc][GoDoc]](https://godoc.org/github.com/parsyl/parquet)

## Financial

*Packages for accounting and finance.*

* [decimal](https://github.com/shopspring/decimal) **star:1968** Arbitrary-precision fixed-point decimal numbers.   [![godoc][GoDoc]](https://godoc.org/github.com/shopspring/decimal)
* [go-money](https://github.com/rhymond/go-money) **star:716** Implementation of Fowler's Money pattern.   [![There was an update last week][Green]](https://github.com/rhymond/go-money)   [![godoc][GoDoc]](https://godoc.org/github.com/rhymond/go-money)
* [accounting](https://github.com/leekchan/accounting) **star:540** money and currency formatting for golang.   [![godoc][GoDoc]](https://godoc.org/github.com/leekchan/accounting)
* [go-finance](https://github.com/FlashBoys/go-finance) **star:539** Comprehensive financial markets data in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/FlashBoys/go-finance)   [![godoc][GoDoc]](https://godoc.org/github.com/FlashBoys/go-finance)
* [techan](https://github.com/sdcoffey/techan) **star:234** Technical analysis library with advanced market analysis and trading strategies.   [![godoc][GoDoc]](https://godoc.org/github.com/sdcoffey/techan)
* [orderbook](https://github.com/i25959341/orderbook) **star:122** Matching Engine for Limit Order Book in Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/i25959341/orderbook)
* [ofxgo](https://github.com/aclindsa/ofxgo) **star:73** Query OFX servers and/or parse the responses (with example command-line client).   [![godoc][GoDoc]](https://godoc.org/github.com/aclindsa/ofxgo)
* [transaction](https://github.com/claygod/transaction) **star:65** Embedded transactional database of accounts, running in multithreaded mode.   [![godoc][GoDoc]](https://godoc.org/github.com/claygod/transaction)
* [vat](https://github.com/dannyvankooten/vat) **star:65** VAT number validation & EU VAT rates.   [![It hasn't been updated in the last year][Yellow]](https://github.com/dannyvankooten/vat)   [![godoc][GoDoc]](https://godoc.org/github.com/dannyvankooten/vat)
* [go-finance](https://github.com/alpeb/go-finance) **star:54** Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.   [![godoc][GoDoc]](https://godoc.org/github.com/alpeb/go-finance)
* [go-finnhub](https://github.com/m1/go-finnhub) **star:21** Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.   [![godoc][GoDoc]](https://godoc.org/github.com/m1/go-finnhub)
* [currency](https://github.com/bnkamalesh/currency) **star:19** High performant & accurate currency computation package.   [![godoc][GoDoc]](https://godoc.org/github.com/bnkamalesh/currency)
* [go-finance](https://github.com/pieterclaerhout/go-finance) **star:3** Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-finance)

## Forms

*Libraries for working with forms.*

* [nosurf](https://github.com/justinas/nosurf) **star:1036** CSRF protection middleware for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/justinas/nosurf)
* [binding](https://github.com/mholt/binding) **star:768** Binds form and JSON data from net/http Request to struct.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mholt/binding)   [![godoc][GoDoc]](https://godoc.org/github.com/mholt/binding)
* [gorilla/csrf](https://github.com/gorilla/csrf) **star:505** CSRF protection for Go web applications & services.   [![godoc][GoDoc]](https://godoc.org/github.com/gorilla/csrf)
* [form](https://github.com/go-playground/form) **star:398** Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/form)
* [conform](https://github.com/leebenson/conform) **star:184** Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.   [![godoc][GoDoc]](https://godoc.org/github.com/leebenson/conform)
* [formam](https://github.com/monoculum/formam) **star:139** decode form's values into a struct.   [![godoc][GoDoc]](https://godoc.org/github.com/monoculum/formam)
* [forms](https://github.com/albrow/forms) **star:104** Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.   [![It hasn't been updated in the last year][Yellow]](https://github.com/albrow/forms)   [![godoc][GoDoc]](https://godoc.org/github.com/albrow/forms)
* [bind](https://github.com/robfig/bind) **star:24** Bind form data to any Go values.   [![It hasn't been updated in the last year][Yellow]](https://github.com/robfig/bind)   [![godoc][GoDoc]](https://godoc.org/github.com/robfig/bind)
* [queryparam](https://github.com/tomwright/queryparam) **star:2** Decode `url.Values` into usable struct values of standard or custom types.   [![godoc][GoDoc]](https://godoc.org/github.com/tomwright/queryparam)

## Functional

*Packages to support functional programming in Go.*

* [go-underscore](https://github.com/tobyhede/go-underscore) **star:1128** Useful collection of helpfully functional Go collection utilities.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tobyhede/go-underscore)   [![godoc][GoDoc]](https://godoc.org/github.com/tobyhede/go-underscore)
* [fpGo](https://github.com/TeaEntityLab/fpGo) **star:137** Monad, Functional Programming features for Golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/TeaEntityLab/fpGo)   [![godoc][GoDoc]](https://godoc.org/github.com/TeaEntityLab/fpGo)
* [fuego](https://github.com/seborama/fuego) **star:64** Functional Experiment in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/seborama/fuego)

## Game Development

*Awesome game development libraries.*

* [Leaf](https://github.com/name5566/leaf) **star:3424** Lightweight game server framework.   [![star > 2000][Awesome]](https://github.com/name5566/leaf)   [![godoc][GoDoc]](https://godoc.org/github.com/name5566/leaf)   [![Contains Chinese documents][CN]](https://github.com/name5566/leaf)
* [Pixel](https://github.com/faiface/pixel) **star:2781** Hand-crafted 2D game library in Go.   [![star > 2000][Awesome]](https://github.com/faiface/pixel)   [![godoc][GoDoc]](https://godoc.org/github.com/faiface/pixel)
* [Ebiten](https://github.com/hajimehoshi/ebiten) **star:2544** dead simple 2D game library in Go.   [![star > 2000][Awesome]](https://github.com/hajimehoshi/ebiten)   [![There was an update last week][Green]](https://github.com/hajimehoshi/ebiten)   [![godoc][GoDoc]](https://godoc.org/github.com/hajimehoshi/ebiten)
* [goworld](https://github.com/xiaonanln/goworld) **star:1412** Scalable game server engine, featuring space-entity framework and hot-swapping.   [![godoc][GoDoc]](https://godoc.org/github.com/xiaonanln/goworld)   [![Contains Chinese documents][CN]](https://github.com/xiaonanln/goworld)
* [go-sdl2](https://github.com/veandco/go-sdl2) **star:1288** Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
* [nano](https://github.com/lonng/nano) **star:1209** Lightweight, facility, high performance golang based game server framework.   [![godoc][GoDoc]](https://godoc.org/github.com/lonng/nano)   [![Contains Chinese documents][CN]](https://github.com/lonng/nano)
* [engo](https://github.com/EngoEngine/engo) **star:1171** Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.   [![There was an update last week][Green]](https://github.com/EngoEngine/engo)   [![godoc][GoDoc]](https://godoc.org/github.com/EngoEngine/engo)
* [termloop](https://github.com/JoelOtter/termloop) **star:1110** Terminal-based game engine for Go, built on top of Termbox.   [![godoc][GoDoc]](https://godoc.org/github.com/JoelOtter/termloop)
* [gonet](https://github.com/xtaci/gonet) **star:1088** Game server skeleton implemented with golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/xtaci/gonet)   [![godoc][GoDoc]](https://godoc.org/github.com/xtaci/gonet)
* [g3n](https://github.com/g3n/engine) **star:957** Go 3D Game Engine.   [![godoc][GoDoc]](https://godoc.org/github.com/g3n/engine)
* [Oak](https://github.com/oakmound/oak) **star:714** Pure Go game engine.   [![There was an update last week][Green]](https://github.com/oakmound/oak)   [![godoc][GoDoc]](https://godoc.org/github.com/oakmound/oak)
* [Pitaya](https://github.com/topfreegames/pitaya) **star:485** Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.   [![godoc][GoDoc]](https://godoc.org/github.com/topfreegames/pitaya)
* [raylib-go](https://github.com/gen2brain/raylib-go) **star:443** Go bindings for [raylib](http://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
* [Azul3D](https://github.com/azul3d/engine) **star:442** 3D game engine written in Go.
* [go-astar](https://github.com/beefsack/go-astar) **star:352** Go implementation of the A\* path finding algorithm.   [![It hasn't been updated in the last year][Yellow]](https://github.com/beefsack/go-astar)   [![godoc][GoDoc]](https://godoc.org/github.com/beefsack/go-astar)
* [GarageEngine](https://github.com/vova616/GarageEngine) **star:319** 2d game engine written in Go working on OpenGL.   [![godoc][GoDoc]](https://godoc.org/github.com/vova616/GarageEngine)
* [go3d](https://github.com/ungerik/go3d) **star:173** Performance oriented 2D/3D math package for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/go3d)
* [glop](https://github.com/runningwild/glop) **star:77** Glop (Game Library Of Power) is a fairly simple cross-platform game library.   [![It hasn't been updated in the last year][Yellow]](https://github.com/runningwild/glop)
* [go-collada](https://github.com/GlenKelley/go-collada) **star:15** Go package for working with the Collada file format.   [![It hasn't been updated in the last year][Yellow]](https://github.com/GlenKelley/go-collada)   [![godoc][GoDoc]](https://godoc.org/github.com/GlenKelley/go-collada)

## Generation and Generics

*Tools to enhance the language with features like generics via code generation.*

* [go-linq](https://github.com/ahmetalpbalkan/go-linq) **star:1991** .NET LINQ-like query methods for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/ahmetalpbalkan/go-linq)
* [jennifer](https://github.com/dave/jennifer) **star:1463** Generate arbitrary Go code without templates.   [![godoc][GoDoc]](https://godoc.org/github.com/dave/jennifer)
* [gen](https://github.com/clipperhouse/gen) **star:1092** Code generation tool for ‘generics’-like functionality.   [![godoc][GoDoc]](https://godoc.org/github.com/clipperhouse/gen)
* [goderive](https://github.com/awalterschulze/goderive) **star:788** Derives functions from input types.   [![godoc][GoDoc]](https://godoc.org/github.com/awalterschulze/goderive)
* [GoWrap](https://github.com/hexdigest/gowrap) **star:330** Generate decorators for Go interfaces using simple templates.   [![There was an update last week][Green]](https://github.com/hexdigest/gowrap)   [![godoc][GoDoc]](https://godoc.org/github.com/hexdigest/gowrap)
* [interfaces](https://github.com/rjeczalik/interfaces) **star:206** Command line tool for generating interface definitions.   [![godoc][GoDoc]](https://godoc.org/github.com/rjeczalik/interfaces)
* [go-enum](https://github.com/abice/go-enum) **star:101** Code generation for enums from code comments.   [![godoc][GoDoc]](https://godoc.org/github.com/abice/go-enum)
* [pkgreflect](https://github.com/ungerik/pkgreflect) **star:92** Go preprocessor for package scoped reflection.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ungerik/pkgreflect)   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/pkgreflect)
* [efaceconv](https://github.com/t0pep0/efaceconv) **star:44** Code generation tool for high performance conversion from interface{} to immutable type without allocations.   [![It hasn't been updated in the last year][Yellow]](https://github.com/t0pep0/efaceconv)   [![godoc][GoDoc]](https://godoc.org/github.com/t0pep0/efaceconv)
* [gotype](https://github.com/wzshiming/gotype) **star:29** Golang source code parsing, usage like reflect package.   [![godoc][GoDoc]](https://godoc.org/github.com/wzshiming/gotype)   [![Contains Chinese documents][CN]](https://github.com/wzshiming/gotype)
* [generis](https://github.com/senselogic/GENERIS) **star:20** Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
* [go-xray](https://github.com/pieterclaerhout/go-xray) **star:6** Helpers for making the use of reflection easier.   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-xray)
* [typeregistry](https://github.com/xiaoxin01/typeregistry) **star:3** A library to create type dynamically.   [![godoc][GoDoc]](https://godoc.org/github.com/xiaoxin01/typeregistry)

## Geographic

*Geographic tools and servers*

* [Tile38](https://github.com/tidwall/tile38) **star:6716** Geolocation DB with spatial index and realtime geofencing.   [![star > 2000][Awesome]](https://github.com/tidwall/tile38)   [![There was an update last week][Green]](https://github.com/tidwall/tile38)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/tile38)
* [S2 geometry](https://github.com/golang/geo) **star:1012** S2 geometry library in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/golang/geo)
* [mbtileserver](https://github.com/consbio/mbtileserver) **star:130** A simple Go-based server for map tiles stored in mbtiles format.   [![godoc][GoDoc]](https://godoc.org/github.com/consbio/mbtileserver)
* [geocache](https://github.com/melihmucuk/geocache) **star:119** In-memory cache that is suitable for geolocation based applications.   [![It hasn't been updated in the last year][Yellow]](https://github.com/melihmucuk/geocache)   [![godoc][GoDoc]](https://godoc.org/github.com/melihmucuk/geocache)
* [osm](https://github.com/paulmach/osm) **star:101** Library for reading, writing and working with OpenStreetMap data and APIs.   [![godoc][GoDoc]](https://godoc.org/github.com/paulmach/osm)
* [WGS84](https://github.com/wroge/wgs84) **star:49** Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).   [![godoc][GoDoc]](https://godoc.org/github.com/wroge/wgs84)
* [geoserver](https://github.com/hishamkaram/geoserver) **star:33** geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.   [![godoc][GoDoc]](https://godoc.org/github.com/hishamkaram/geoserver)
* [gismanager](https://github.com/hishamkaram/gismanager) **star:26** Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.   [![It hasn't been updated in the last year][Yellow]](https://github.com/hishamkaram/gismanager)   [![godoc][GoDoc]](https://godoc.org/github.com/hishamkaram/gismanager)
* [pbf](https://github.com/maguro/pbf) **star:20** OpenStreetMap PBF golang encoder/decoder.   [![godoc][GoDoc]](https://godoc.org/github.com/maguro/pbf)

## Go Compilers

*Tools for compiling Go to other languages.*

* [gopherjs](https://github.com/gopherjs/gopherjs) **star:9211** Compiler from Go to JavaScript.   [![star > 2000][Awesome]](https://github.com/gopherjs/gopherjs)   [![godoc][GoDoc]](https://godoc.org/github.com/gopherjs/gopherjs)
* [llgo](https://github.com/go-llvm/llgo) **star:1041** LLVM-based compiler for Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/go-llvm/llgo)   [![godoc][GoDoc]](https://godoc.org/github.com/go-llvm/llgo)
* [tardisgo](https://github.com/tardisgo/tardisgo) **star:396** Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tardisgo/tardisgo)   [![godoc][GoDoc]](https://godoc.org/github.com/tardisgo/tardisgo)
* [c4go](https://github.com/Konstantin8105/c4go) **star:202** Transpile C code to Go code.   [![godoc][GoDoc]](https://godoc.org/github.com/Konstantin8105/c4go)
* [f4go](https://github.com/Konstantin8105/f4go) **star:23** Transpile FORTRAN 77 code to Go code.   [![godoc][GoDoc]](https://godoc.org/github.com/Konstantin8105/f4go)

## Goroutines

*Tools for managing and working with Goroutines.*

* [ants](https://github.com/panjf2000/ants) **star:3114** A high-performance and low-cost goroutine pool in Go.   [![star > 2000][Awesome]](https://github.com/panjf2000/ants)   [![godoc][GoDoc]](https://godoc.org/github.com/panjf2000/ants)   [![Contains Chinese documents][CN]](https://github.com/panjf2000/ants)
* [goworker](https://github.com/benmanns/goworker) **star:2351** goworker is a Go-based background worker.   [![star > 2000][Awesome]](https://github.com/benmanns/goworker)   [![godoc][GoDoc]](https://godoc.org/github.com/benmanns/goworker)
* [tunny](https://github.com/Jeffail/tunny) **star:1568** Goroutine pool for golang.   [![godoc][GoDoc]](https://godoc.org/github.com/Jeffail/tunny)
* [pool](https://github.com/go-playground/pool) **star:546** Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/pool)
* [grpool](https://github.com/ivpusic/grpool) **star:542** Lightweight Goroutine pool.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ivpusic/grpool)   [![godoc][GoDoc]](https://godoc.org/github.com/ivpusic/grpool)
* [workerpool](https://github.com/gammazero/workerpool) **star:265** Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.   [![godoc][GoDoc]](https://godoc.org/github.com/gammazero/workerpool)
* [go-floc](https://github.com/workanator/go-floc) **star:177** Orchestrate goroutines with ease.   [![It hasn't been updated in the last year][Yellow]](https://github.com/workanator/go-floc)   [![godoc][GoDoc]](https://godoc.org/github.com/workanator/go-floc)
* [gowp](https://github.com/xxjwxc/gowp) **star:163** gowp is concurrency limiting goroutine pool.   [![godoc][GoDoc]](https://godoc.org/github.com/xxjwxc/gowp)   [![Contains Chinese documents][CN]](https://github.com/xxjwxc/gowp)
* [go-flow](https://github.com/kamildrazkiewicz/go-flow) **star:127** Control goroutines execution order.   [![godoc][GoDoc]](https://godoc.org/github.com/kamildrazkiewicz/go-flow)
* [GoSlaves](https://github.com/themester/GoSlaves) **star:91** Simple and Asynchronous Goroutine pool library.   [![godoc][GoDoc]](https://godoc.org/github.com/themester/GoSlaves)
* [semaphore](https://github.com/kamilsk/semaphore) **star:82** Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.   [![godoc][GoDoc]](https://godoc.org/github.com/kamilsk/semaphore)
* [semaphore](https://github.com/marusama/semaphore) **star:80** Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).   [![It hasn't been updated in the last year][Yellow]](https://github.com/marusama/semaphore)   [![godoc][GoDoc]](https://godoc.org/github.com/marusama/semaphore)
* [gpool](https://github.com/Sherifabdlnaby/gpool) **star:65** manages a resizeable pool of context-aware goroutines to bound concurrency.   [![godoc][GoDoc]](https://godoc.org/github.com/Sherifabdlnaby/gpool)
* [breaker](https://github.com/kamilsk/breaker) **star:56** Flexible mechanism to make execution flow interruptible.   [![godoc][GoDoc]](https://godoc.org/github.com/kamilsk/breaker)
* [worker-pool](https://github.com/vardius/worker-pool) **star:53** goworker is a Go simple async worker pool.   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/worker-pool)
* [cyclicbarrier](https://github.com/marusama/cyclicbarrier) **star:44** CyclicBarrier for golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/marusama/cyclicbarrier)   [![godoc][GoDoc]](https://godoc.org/github.com/marusama/cyclicbarrier)
* [gollback](https://github.com/vardius/gollback) **star:31** asynchronous simple function utilities, for managing execution of closures and callbacks.   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/gollback)
* [async](https://github.com/studiosol/async) **star:30** A safe way to execute functions asynchronously, recovering them in case of panic.   [![godoc][GoDoc]](https://godoc.org/github.com/studiosol/async)
* [parallel-fn](https://github.com/rafaeljesus/parallel-fn) **star:26** Run functions in parallel.   [![It hasn't been updated in the last year][Yellow]](https://github.com/rafaeljesus/parallel-fn)   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/parallel-fn)
* [threadpool](https://github.com/shettyh/threadpool) **star:25** Golang threadpool implementation.   [![It hasn't been updated in the last year][Yellow]](https://github.com/shettyh/threadpool)   [![godoc][GoDoc]](https://godoc.org/github.com/shettyh/threadpool)
* [artifex](https://github.com/borderstech/artifex) **star:24** Simple in-memory job queue for Golang using worker-based dispatching.   [![godoc][GoDoc]](https://godoc.org/github.com/borderstech/artifex)
* [Hunch](https://github.com/AaronJan/Hunch) **star:23** Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.   [![godoc][GoDoc]](https://godoc.org/github.com/AaronJan/Hunch)
* [oversight](https://cirello.io/oversight)  Oversight is a complete implementation of the Erlang supervision trees.
* [kyoo](https://github.com/dirkaholic/kyoo) **star:22** Provides an unlimited job queue and concurrent worker pools.   [![godoc][GoDoc]](https://godoc.org/github.com/dirkaholic/kyoo)
* [stl](https://github.com/ssgreg/stl) **star:11** Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.   [![godoc][GoDoc]](https://godoc.org/github.com/ssgreg/stl)
* [gohive](https://github.com/loveleshsharma/gohive) **star:11** A highly performant and easy to use Goroutine pool for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/loveleshsharma/gohive)
* [routine](https://github.com/x-mod/routine) **star:9** go routine control with context, support: Main, Go, Pool and some useful Executors.   [![godoc][GoDoc]](https://godoc.org/github.com/x-mod/routine)
* [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) **star:5** Like `sync.WaitGroup` with error handling and concurrency control.   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-waitgroup)
* [go-trylock](https://github.com/subchen/go-trylock) **star:5** TryLock support on read-write lock for Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/subchen/go-trylock)
* [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) **star:5** Manage a pool of goroutines using this lightweight library with a simple API.   [![godoc][GoDoc]](https://godoc.org/github.com/nikhilsaraf/go-tools)
* [conexec](https://github.com/ITcathyh/conexec) **star:4** A concurrent toolkit to help execute funcs concurrently in an efficient and safe way.It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.   [![godoc][GoDoc]](https://godoc.org/github.com/ITcathyh/conexec)
* [queue](https://github.com/AnikHasibul/queue) **star:3** Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more.   [![godoc][GoDoc]](https://godoc.org/github.com/AnikHasibul/queue)

## GUI

*Libraries for building GUI Applications.*

*Toolkits*

* [fyne](https://github.com/fyne-io/fyne) **star:8929** Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.   [![star > 2000][Awesome]](https://github.com/fyne-io/fyne)   [![There was an update last week][Green]](https://github.com/fyne-io/fyne)   [![godoc][GoDoc]](https://godoc.org/github.com/fyne-io/fyne)
* [ui](https://github.com/andlabs/ui) **star:7374** Platform-native GUI library for Go. Cross platform.   [![star > 2000][Awesome]](https://github.com/andlabs/ui)   [![godoc][GoDoc]](https://godoc.org/github.com/andlabs/ui)
* [Wails](https://wails.app)  Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
* [qt](https://github.com/therecipe/qt) **star:7057** Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).   [![star > 2000][Awesome]](https://github.com/therecipe/qt)   [![godoc][GoDoc]](https://godoc.org/github.com/therecipe/qt)
* [webview](https://github.com/zserge/webview) **star:5542** Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).   [![star > 2000][Awesome]](https://github.com/zserge/webview)   [![There was an update last week][Green]](https://github.com/zserge/webview)
* [walk](https://github.com/lxn/walk) **star:4290** Windows application library kit for Go.   [![star > 2000][Awesome]](https://github.com/lxn/walk)   [![godoc][GoDoc]](https://godoc.org/github.com/lxn/walk)
* [app](https://github.com/murlokswarm/app) **star:3343** Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.   [![star > 2000][Awesome]](https://github.com/murlokswarm/app)   [![There was an update last week][Green]](https://github.com/murlokswarm/app)   [![godoc][GoDoc]](https://godoc.org/github.com/murlokswarm/app)
* [go-astilectron](https://github.com/asticode/go-astilectron) **star:3059** Build cross platform GUI apps with GO and HTML/JS/CSS (powered by Electron).   [![star > 2000][Awesome]](https://github.com/asticode/go-astilectron)   [![godoc][GoDoc]](https://godoc.org/github.com/asticode/go-astilectron)
* [go-gtk](http://mattn.github.io/go-gtk/)  Go bindings for GTK.
* [go-sciter](https://github.com/sciter-sdk/go-sciter) **star:1645** Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.   [![godoc][GoDoc]](https://godoc.org/github.com/sciter-sdk/go-sciter)
* [gotk3](https://github.com/gotk3/gotk3) **star:938** Go bindings for GTK3.   [![There was an update last week][Green]](https://github.com/gotk3/gotk3)   [![godoc][GoDoc]](https://godoc.org/github.com/gotk3/gotk3)
* [gowd](https://github.com/dtylman/gowd) **star:243** Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.   [![godoc][GoDoc]](https://godoc.org/github.com/dtylman/gowd)

*Interaction*

* [robotgo](https://github.com/go-vgo/robotgo) **star:4871** Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.   [![star > 2000][Awesome]](https://github.com/go-vgo/robotgo)   [![There was an update last week][Green]](https://github.com/go-vgo/robotgo)
* [systray](https://github.com/getlantern/systray) **star:1018** Cross platform Go library to place an icon and menu in the notification area.   [![godoc][GoDoc]](https://godoc.org/github.com/getlantern/systray)
* [gosx-notifier](https://github.com/deckarep/gosx-notifier) **star:511** OSX Desktop Notifications library for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/deckarep/gosx-notifier)
* [trayhost](https://github.com/shurcooL/trayhost) **star:174** Cross-platform Go library to place an icon in the host operating system's taskbar.   [![godoc][GoDoc]](https://godoc.org/github.com/shurcooL/trayhost)
* [go-appindicator](https://github.com/dawidd6/go-appindicator) **star:5** Go bindings for libappindicator3 C library.   [![godoc][GoDoc]](https://godoc.org/github.com/dawidd6/go-appindicator)
* [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) **star:5** OSX library to notify about any (pluggable) activity on your machine.   [![godoc][GoDoc]](https://godoc.org/github.com/prashantgupta24/activity-tracker)
* [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) **star:2** OSX Sleep/Wake notifications in golang.   [![godoc][GoDoc]](https://godoc.org/github.com/prashantgupta24/mac-sleep-notifier)


## Hardware

*Libraries, tools, and tutorials for interacting with hardware.*

See [go-hardware](https://github.com/rakyll/go-hardware) for a comprehensive list.

## Images

*Libraries for manipulating images.*

* [gocv](https://github.com/hybridgroup/gocv) **star:2993** Go package for computer vision using OpenCV 3.3+.   [![star > 2000][Awesome]](https://github.com/hybridgroup/gocv)   [![There was an update last week][Green]](https://github.com/hybridgroup/gocv)   [![godoc][GoDoc]](https://godoc.org/github.com/hybridgroup/gocv)
* [imaging](https://github.com/disintegration/imaging) **star:2957** Simple Go image processing package.   [![star > 2000][Awesome]](https://github.com/disintegration/imaging)   [![godoc][GoDoc]](https://godoc.org/github.com/disintegration/imaging)
* [imaginary](https://github.com/h2non/imaginary) **star:2898** Fast and simple HTTP microservice for image resizing.   [![star > 2000][Awesome]](https://github.com/h2non/imaginary)   [![godoc][GoDoc]](https://godoc.org/github.com/h2non/imaginary)
* [bild](https://github.com/anthonynsimon/bild) **star:2794** Collection of image processing algorithms in pure Go.   [![star > 2000][Awesome]](https://github.com/anthonynsimon/bild)   [![godoc][GoDoc]](https://godoc.org/github.com/anthonynsimon/bild)
* [ln](https://github.com/fogleman/ln) **star:2628** 3D line art rendering in Go.   [![star > 2000][Awesome]](https://github.com/fogleman/ln)   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/ln)
* [resize](https://github.com/nfnt/resize) **star:2296** Image resizing for Go with common interpolation methods.   [![star > 2000][Awesome]](https://github.com/nfnt/resize)   [![It hasn't been updated in the last year][Yellow]](https://github.com/nfnt/resize)   [![godoc][GoDoc]](https://godoc.org/github.com/nfnt/resize)
* [gg](https://github.com/fogleman/gg) **star:2168** 2D rendering in pure Go.   [![star > 2000][Awesome]](https://github.com/fogleman/gg)   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/gg)
* [pt](https://github.com/fogleman/pt) **star:1838** Path tracing engine written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/fogleman/pt)
* [svgo](https://github.com/ajstarks/svgo) **star:1435** Go Language Library for SVG generation.   [![godoc][GoDoc]](https://godoc.org/github.com/ajstarks/svgo)
* [smartcrop](https://github.com/muesli/smartcrop) **star:1337** Finds good crops for arbitrary images and crop sizes.   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/smartcrop)
* [gift](https://github.com/disintegration/gift) **star:1302** Package of image processing filters.   [![godoc][GoDoc]](https://godoc.org/github.com/disintegration/gift)
* [picfit](https://github.com/thoas/picfit) **star:1199** An image resizing server written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/thoas/picfit)
* [go-opencv](https://github.com/lazywei/go-opencv) **star:1158** Go bindings for OpenCV.   [![godoc][GoDoc]](https://godoc.org/github.com/lazywei/go-opencv)
* [imagick](https://github.com/gographics/imagick) **star:1121** Go binding to ImageMagick's MagickWand C API.   [![godoc][GoDoc]](https://godoc.org/github.com/gographics/imagick)
* [geopattern](https://github.com/pravj/geopattern) **star:1053** Create beautiful generative image patterns from a string.   [![It hasn't been updated in the last year][Yellow]](https://github.com/pravj/geopattern)   [![godoc][GoDoc]](https://godoc.org/github.com/pravj/geopattern)
* [bimg](https://github.com/h2non/bimg) **star:896** Small package for fast and efficient image processing using libvips.   [![godoc][GoDoc]](https://godoc.org/github.com/h2non/bimg)
* [stegify](https://github.com/DimitarPetrov/stegify) **star:774** Go tool for LSB steganography, capable of hiding any file within an image.   [![There was an update last week][Green]](https://github.com/DimitarPetrov/stegify)   [![godoc][GoDoc]](https://godoc.org/github.com/DimitarPetrov/stegify)
* [canvas](https://github.com/tdewolff/canvas) **star:413** Vector graphics to PDF, SVG or rasterized image.   [![godoc][GoDoc]](https://godoc.org/github.com/tdewolff/canvas)
* [mort](https://github.com/aldor007/mort) **star:388** Storage and image processing server written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/aldor007/mort)
* [image2ascii](https://github.com/qeesung/image2ascii) **star:374** Convert image to ASCII.   [![It hasn't been updated in the last year][Yellow]](https://github.com/qeesung/image2ascii)   [![godoc][GoDoc]](https://godoc.org/github.com/qeesung/image2ascii)
* [govatar](https://github.com/o1egl/govatar) **star:343** Library and CMD tool for generating funny avatars.   [![godoc][GoDoc]](https://godoc.org/github.com/o1egl/govatar)
* [go-nude](https://github.com/koyachi/go-nude) **star:300** Nudity detection with Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/koyachi/go-nude)   [![godoc][GoDoc]](https://godoc.org/github.com/koyachi/go-nude)
* [goimagehash](https://github.com/corona10/goimagehash) **star:271** Go Perceptual image hashing package.   [![godoc][GoDoc]](https://godoc.org/github.com/corona10/goimagehash)
* [rez](https://github.com/bamiaux/rez) **star:200** Image resizing in pure Go and SIMD.   [![It hasn't been updated in the last year][Yellow]](https://github.com/bamiaux/rez)   [![godoc][GoDoc]](https://godoc.org/github.com/bamiaux/rez)
* [img](https://github.com/hawx/img) **star:133** Selection of image manipulation tools.   [![It hasn't been updated in the last year][Yellow]](https://github.com/hawx/img)   [![godoc][GoDoc]](https://godoc.org/github.com/hawx/img)
* [darkroom](https://github.com/gojek/darkroom) **star:119** An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.   [![There was an update last week][Green]](https://github.com/gojek/darkroom)   [![godoc][GoDoc]](https://godoc.org/github.com/gojek/darkroom)
* [go-cairo](https://github.com/ungerik/go-cairo) **star:92** Go binding for the cairo graphics library.   [![godoc][GoDoc]](https://godoc.org/github.com/ungerik/go-cairo)
* [mergi](https://github.com/noelyahan/mergi) **star:88** Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).   [![godoc][GoDoc]](https://godoc.org/github.com/noelyahan/mergi)
* [gltf](https://github.com/qmuntal/gltf) **star:61** Efficient and robust glTF 2.0 reader, writer and validator.   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/gltf)
* [go-gd](https://github.com/bolknote/go-gd) **star:52** Go binding for GD library.   [![It hasn't been updated in the last year][Yellow]](https://github.com/bolknote/go-gd)   [![godoc][GoDoc]](https://godoc.org/github.com/bolknote/go-gd)
* [steganography](https://github.com/auyer/steganography) **star:44** Pure Go Library for LSB steganography.   [![godoc][GoDoc]](https://godoc.org/github.com/auyer/steganography)
* [cameron](https://github.com/aofei/cameron) **star:40** An avatar generator for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/aofei/cameron)
* [goimghdr](https://github.com/corona10/goimghdr) **star:33** The imghdr module determines the type of image contained in a file for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/corona10/goimghdr)
* [tga](https://github.com/ftrvxmtrx/tga) **star:26** Package tga is a TARGA image format decoder/encoder.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ftrvxmtrx/tga)   [![godoc][GoDoc]](https://godoc.org/github.com/ftrvxmtrx/tga)
* [go-webcolors](https://github.com/jyotiska/go-webcolors) **star:24** Port of webcolors library from Python to Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/jyotiska/go-webcolors)   [![godoc][GoDoc]](https://godoc.org/github.com/jyotiska/go-webcolors)
* [mpo](https://github.com/donatj/mpo) **star:6** Decoder and conversion tool for MPO 3D Photos.   [![It hasn't been updated in the last year][Yellow]](https://github.com/donatj/mpo)   [![godoc][GoDoc]](https://godoc.org/github.com/donatj/mpo)

## IoT (Internet of Things)

*Libraries for programming devices of the IoT.*

* [flogo](https://github.com/tibcosoftware/flogo) **star:1370** Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
* [gatt](https://github.com/paypal/gatt) **star:884** Gatt is a Go package for building Bluetooth Low Energy peripherals.   [![godoc][GoDoc]](https://godoc.org/github.com/paypal/gatt)
* [gobot](https://github.com/hybridgroup/gobot/)  Gobot is a framework for robotics, physical computing, and the Internet of Things.
* [mainflux](https://github.com/Mainflux/mainflux) **star:809** Industrial IoT Messaging and Device Management Server.   [![There was an update last week][Green]](https://github.com/Mainflux/mainflux)   [![godoc][GoDoc]](https://godoc.org/github.com/Mainflux/mainflux)
* [periph](https://periph.io/)  Peripherals I/O to interface with low-level board facilities.
* [devices](https://github.com/goiot/devices) **star:229** Suite of libraries for IoT devices, experimental for x/exp/io.   [![It hasn't been updated in the last year][Yellow]](https://github.com/goiot/devices)   [![godoc][GoDoc]](https://godoc.org/github.com/goiot/devices)
* [connectordb](https://github.com/connectordb/connectordb) **star:200** Open-Source Platform for Quantified Self & IoT.   [![There was an update last week][Green]](https://github.com/connectordb/connectordb)   [![godoc][GoDoc]](https://godoc.org/github.com/connectordb/connectordb)
* [sensorbee](https://github.com/sensorbee/sensorbee) **star:191** Lightweight stream processing engine for IoT.   [![godoc][GoDoc]](https://godoc.org/github.com/sensorbee/sensorbee)
* [huego](https://github.com/amimof/huego) **star:136** An extensive Philips Hue client library for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/amimof/huego)
* [iot](https://github.com/vaelen/iot/)  IoT is a simple framework for implementing a Google IoT Core device.
* [eywa](https://github.com/xcodersun/eywa) **star:44** Project Eywa is essentially a connection manager that keeps track of connected devices.   [![It hasn't been updated in the last year][Yellow]](https://github.com/xcodersun/eywa)   [![godoc][GoDoc]](https://godoc.org/github.com/xcodersun/eywa)

## Job Scheduler

*Libraries for scheduling jobs.*

* [gron](https://github.com/roylee0704/gron) **star:692** Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.   [![It hasn't been updated in the last year][Yellow]](https://github.com/roylee0704/gron)   [![godoc][GoDoc]](https://godoc.org/github.com/roylee0704/gron)
* [JobRunner](https://github.com/bamzi/jobrunner) **star:659** Smart and featureful cron job scheduler with job queuing and live monitoring built in.   [![godoc][GoDoc]](https://godoc.org/github.com/bamzi/jobrunner)
* [jobs](https://github.com/albrow/jobs) **star:466** Persistent and flexible background jobs library.   [![It hasn't been updated in the last year][Yellow]](https://github.com/albrow/jobs)   [![godoc][GoDoc]](https://godoc.org/github.com/albrow/jobs)
* [scheduler](https://github.com/carlescere/scheduler) **star:319** Cronjobs scheduling made easy.   [![It hasn't been updated in the last year][Yellow]](https://github.com/carlescere/scheduler)   [![godoc][GoDoc]](https://godoc.org/github.com/carlescere/scheduler)
* [clockwerk](http://github.com/onatm/clockwerk)  Go package to schedule periodic jobs using a simple, fluent syntax.
* [go-cron](https://github.com/rk/go-cron) **star:183** Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.   [![godoc][GoDoc]](https://godoc.org/github.com/rk/go-cron)
* [clockwork](https://github.com/whiteShtef/clockwork) **star:97** Simple and intuitive job scheduling library in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/whiteShtef/clockwork)
* [leprechaun](https://github.com/kilgaloon/leprechaun) **star:61** Job scheduler that supports webhooks, crons and classic scheduling.   [![godoc][GoDoc]](https://godoc.org/github.com/kilgaloon/leprechaun)

## JSON

*Libraries for working with JSON.*

* [GJSON](https://github.com/tidwall/gjson) **star:5975** Get a JSON value with one line of code.   [![star > 2000][Awesome]](https://github.com/tidwall/gjson)   [![godoc][GoDoc]](https://godoc.org/github.com/tidwall/gjson)
* [gojson](https://github.com/ChimeraCoder/gojson) **star:2152** Automatically generate Go (golang) struct definitions from example JSON.   [![star > 2000][Awesome]](https://github.com/ChimeraCoder/gojson)   [![godoc][GoDoc]](https://godoc.org/github.com/ChimeraCoder/gojson)
* [kazaam](https://github.com/Qntfy/kazaam) **star:145** API for arbitrary transformation of JSON documents.   [![godoc][GoDoc]](https://godoc.org/github.com/Qntfy/kazaam)
* [gojq](https://github.com/elgs/gojq) **star:142** JSON query in Golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/elgs/gojq)   [![godoc][GoDoc]](https://godoc.org/github.com/elgs/gojq)
* [jsongo](https://github.com/ricardolonga/jsongo) **star:94** Fluent API to make it easier to create Json objects.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ricardolonga/jsongo)   [![godoc][GoDoc]](https://godoc.org/github.com/ricardolonga/jsongo)
* [jettison](https://github.com/wI2L/jettison) **star:74** High performance, reflection-less JSON encoder for Go.   [![There was an update last week][Green]](https://github.com/wI2L/jettison)   [![godoc][GoDoc]](https://godoc.org/github.com/wI2L/jettison)
* [JSON-to-Go](https://mholt.github.io/json-to-go/)  Convert JSON to Go struct.
* [gjo](https://github.com/skanehira/gjo) **star:71** Small utility to create JSON objects.   [![godoc][GoDoc]](https://godoc.org/github.com/skanehira/gjo)
* [JayDiff](https://github.com/yazgazan/jaydiff) **star:63** JSON diff utility written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/yazgazan/jaydiff)
* [jsonf](https://github.com/miolini/jsonf) **star:54** Console tool for highlighted formatting and struct query fetching JSON.   [![It hasn't been updated in the last year][Yellow]](https://github.com/miolini/jsonf)   [![godoc][GoDoc]](https://godoc.org/github.com/miolini/jsonf)
* [mp](https://github.com/sanbornm/mp) **star:38** Simple cli email parser. It currently takes stdin and outputs JSON.   [![It hasn't been updated in the last year][Yellow]](https://github.com/sanbornm/mp)   [![godoc][GoDoc]](https://godoc.org/github.com/sanbornm/mp)
* [json2go](https://github.com/m-zajac/json2go) **star:32** Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.   [![godoc][GoDoc]](https://godoc.org/github.com/m-zajac/json2go)
* [go-respond](https://github.com/nicklaw5/go-respond) **star:30** Go package for handling common HTTP JSON responses.   [![godoc][GoDoc]](https://godoc.org/github.com/nicklaw5/go-respond)
* [ajson](https://github.com/spyzhov/ajson) **star:26** Abstract JSON for golang with JSONPath support.   [![godoc][GoDoc]](https://godoc.org/github.com/spyzhov/ajson)
* [jsonhal](https://github.com/RichardKnop/jsonhal) **star:9** Simple Go package to make custom structs marshal into HAL compatible JSON responses.   [![It hasn't been updated in the last year][Yellow]](https://github.com/RichardKnop/jsonhal)   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/jsonhal)
* [go-jsonerror](https://github.com/ddymko/go-jsonerror) **star:9** Go-JsonError is ment to allow us to easily create json response errors that follow the JsonApi spec.   [![godoc][GoDoc]](https://godoc.org/github.com/ddymko/go-jsonerror)
* [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) **star:8** Go bindings based on the JSON API errors reference.   [![It hasn't been updated in the last year][Yellow]](https://github.com/AmuzaTkts/jsonapi-errors)   [![godoc][GoDoc]](https://godoc.org/github.com/AmuzaTkts/jsonapi-errors)
* [ej](https://github.com/lucassscaravelli/ej) **star:3** Write and read JSON from different sources succinctly.   [![godoc][GoDoc]](https://godoc.org/github.com/lucassscaravelli/ej)
* [mapslice-json](https://github.com/mickep76/mapslice-json) **star:1** Go MapSlice for ordered marshal/ unmarshal of maps in JSON.   [![godoc][GoDoc]](https://godoc.org/github.com/mickep76/mapslice-json)

## Logging

*Libraries for generating and working with log files.*

* [logrus](https://github.com/Sirupsen/logrus) **star:14074** Structured logger for Go.   [![star > 2000][Awesome]](https://github.com/Sirupsen/logrus)   [![There was an update last week][Green]](https://github.com/Sirupsen/logrus)   [![godoc][GoDoc]](https://godoc.org/github.com/Sirupsen/logrus)
* [zap](https://github.com/uber-go/zap) **star:9129** Fast, structured, leveled logging in Go.   [![star > 2000][Awesome]](https://github.com/uber-go/zap)   [![There was an update last week][Green]](https://github.com/uber-go/zap)   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/zap)
* [spew](https://github.com/davecgh/go-spew) **star:3756** Implements a deep pretty printer for Go data structures to aid in debugging.   [![star > 2000][Awesome]](https://github.com/davecgh/go-spew)   [![godoc][GoDoc]](https://godoc.org/github.com/davecgh/go-spew)
* [zerolog](https://github.com/rs/zerolog) **star:2998** Zero-allocation JSON logger.   [![star > 2000][Awesome]](https://github.com/rs/zerolog)   [![godoc][GoDoc]](https://godoc.org/github.com/rs/zerolog)
* [glog](https://github.com/golang/glog) **star:2484** Leveled execution logs for Go.   [![star > 2000][Awesome]](https://github.com/golang/glog)   [![godoc][GoDoc]](https://godoc.org/github.com/golang/glog)
* [lumberjack](https://github.com/natefinch/lumberjack) **star:1802** Simple rolling logger, implements io.WriteCloser.   [![godoc][GoDoc]](https://godoc.org/github.com/natefinch/lumberjack)
* [tail](https://github.com/hpcloud/tail) **star:1727** Go package striving to emulate the features of the BSD tail program.   [![godoc][GoDoc]](https://godoc.org/github.com/hpcloud/tail)
* [seelog](https://github.com/cihub/seelog) **star:1438** Logging functionality with flexible dispatching, filtering, and formatting.   [![It hasn't been updated in the last year][Yellow]](https://github.com/cihub/seelog)   [![godoc][GoDoc]](https://godoc.org/github.com/cihub/seelog)
* [log15](https://github.com/inconshreveable/log15) **star:951** Simple, powerful logging for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/inconshreveable/log15)
* [log](https://github.com/apex/log) **star:802** Structured logging package for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/apex/log)
* [onelog](https://github.com/francoispqt/onelog) **star:364** Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenario. Also, it is one of the logger with the lowest allocation.   [![It hasn't been updated in the last year][Yellow]](https://github.com/francoispqt/onelog)   [![godoc][GoDoc]](https://godoc.org/github.com/francoispqt/onelog)
* [logxi](https://github.com/mgutz/logxi) **star:343** 12-factor app logger that is fast and makes you happy.   [![godoc][GoDoc]](https://godoc.org/github.com/mgutz/logxi)
* [log](https://github.com/go-playground/log) **star:273** Simple, configurable and scalable Structured Logging for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/log)
* [logutils](https://github.com/hashicorp/logutils) **star:270** Utilities for slightly better logging in Go (Golang) extending the standard logger.   [![godoc][GoDoc]](https://godoc.org/github.com/hashicorp/logutils)
* [go-logger](https://github.com/apsdehal/go-logger) **star:248** Simple logger of Go Programs, with level handlers.   [![godoc][GoDoc]](https://godoc.org/github.com/apsdehal/go-logger)
* [logger](https://github.com/azer/logger) **star:138** Minimalistic logging library for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/azer/logger)
* [xlog](https://github.com/rs/xlog) **star:133** Structured logger for `net/context` aware HTTP handlers with flexible dispatching.   [![godoc][GoDoc]](https://godoc.org/github.com/rs/xlog)
* [rollingwriter](https://github.com/arthurkiller/rollingWriter) **star:128** RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.   [![godoc][GoDoc]](https://godoc.org/github.com/arthurkiller/rollingWriter)
* [ozzo-log](https://github.com/go-ozzo/ozzo-log) **star:112** High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).   [![It hasn't been updated in the last year][Yellow]](https://github.com/go-ozzo/ozzo-log)   [![godoc][GoDoc]](https://godoc.org/github.com/go-ozzo/ozzo-log)   [![Contains Chinese documents][CN]](https://github.com/go-ozzo/ozzo-log)
* [log-voyage](https://github.com/firstrow/logvoyage) **star:84** Full-featured logging saas written in golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/firstrow/logvoyage)   [![godoc][GoDoc]](https://godoc.org/github.com/firstrow/logvoyage)
* [glg](https://github.com/kpango/glg) **star:67** glg is simple and fast leveled logging library for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/kpango/glg)
* [stdlog](https://github.com/alexcesaro/log) **star:42** Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.   [![It hasn't been updated in the last year][Yellow]](https://github.com/alexcesaro/log)   [![godoc][GoDoc]](https://godoc.org/github.com/alexcesaro/log)
* [gologger](https://github.com/sadlil/gologger) **star:38** Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.   [![It hasn't been updated in the last year][Yellow]](https://github.com/sadlil/gologger)   [![godoc][GoDoc]](https://godoc.org/github.com/sadlil/gologger)   [![Archived][Archived]](https://github.com/sadlil/gologger)
* [logex](https://github.com/chzyer/logex) **star:35** Golang log lib, supports tracking and level, wrap by standard log lib.   [![It hasn't been updated in the last year][Yellow]](https://github.com/chzyer/logex)   [![godoc][GoDoc]](https://godoc.org/github.com/chzyer/logex)
* [go-log](https://github.com/ian-kent/go-log) **star:34** Log4j implementation in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ian-kent/go-log)   [![godoc][GoDoc]](https://godoc.org/github.com/ian-kent/go-log)
* [go-cronowriter](https://github.com/utahta/go-cronowriter) **star:26** Simple writer that rotate log files automatically based on current date and time, like cronolog.   [![godoc][GoDoc]](https://godoc.org/github.com/utahta/go-cronowriter)
* [go-log](https://github.com/siddontang/go-log) **star:26** Log lib supports level and multi handlers.   [![It hasn't been updated in the last year][Yellow]](https://github.com/siddontang/go-log)   [![godoc][GoDoc]](https://godoc.org/github.com/siddontang/go-log)
* [logrusly](https://github.com/sebest/logrusly) **star:25** [logrus](https://github.com/sirupsen/logrus) plug-in to send errors to a [Loggly](https://www.loggly.com/).   [![It hasn't been updated in the last year][Yellow]](https://github.com/sebest/logrusly)   [![godoc][GoDoc]](https://godoc.org/github.com/sebest/logrusly)
* [log](https://github.com/teris-io/log) **star:23** Structured log interface for Go cleanly separates logging facade from its implementation.   [![It hasn't been updated in the last year][Yellow]](https://github.com/teris-io/log)   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/log)
* [distillog](https://github.com/amoghe/distillog) **star:22** distilled levelled logging (think of it as stdlib + log levels).   [![It hasn't been updated in the last year][Yellow]](https://github.com/amoghe/distillog)   [![godoc][GoDoc]](https://godoc.org/github.com/amoghe/distillog)
* [journald](https://github.com/ssgreg/journald) **star:22** Go implementation of systemd Journal's native API for logging.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ssgreg/journald)   [![godoc][GoDoc]](https://godoc.org/github.com/ssgreg/journald)
* [mlog](https://github.com/jbrodriguez/mlog) **star:19** Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.   [![It hasn't been updated in the last year][Yellow]](https://github.com/jbrodriguez/mlog)   [![godoc][GoDoc]](https://godoc.org/github.com/jbrodriguez/mlog)
* [gomol](https://github.com/aphistic/gomol) **star:16** Multiple-output, structured logging for Go with extensible logging outputs.   [![It hasn't been updated in the last year][Yellow]](https://github.com/aphistic/gomol)   [![godoc][GoDoc]](https://godoc.org/github.com/aphistic/gomol)
* [gone/log](https://github.com/One-com/gone/tree/master/log)  Fast, extendable, full-featured, std-lib source compatible log library.
* [logdump](https://github.com/ewwwwwqm/logdump) **star:9** Package for multi-level logging.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ewwwwwqm/logdump)   [![godoc][GoDoc]](https://godoc.org/github.com/ewwwwwqm/logdump)
* [go-log](https://github.com/subchen/go-log) **star:9** Simple and configurable Logging in Go, with level, formatters and writers.   [![It hasn't been updated in the last year][Yellow]](https://github.com/subchen/go-log)   [![godoc][GoDoc]](https://godoc.org/github.com/subchen/go-log)
* [glo](https://github.com/lajosbencz/glo) **star:9** PHP Monolog inspired logging facility with identical severity levels.   [![It hasn't been updated in the last year][Yellow]](https://github.com/lajosbencz/glo)   [![godoc][GoDoc]](https://godoc.org/github.com/lajosbencz/glo)
* [logrusiowriter](https://github.com/cabify/logrusiowriter) **star:8** `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) logger.   [![godoc][GoDoc]](https://godoc.org/github.com/cabify/logrusiowriter)
* [logmatic](https://github.com/borderstech/logmatic) **star:6** Colorized logger for Golang with dynamic log level configuration.   [![It hasn't been updated in the last year][Yellow]](https://github.com/borderstech/logmatic)   [![godoc][GoDoc]](https://godoc.org/github.com/borderstech/logmatic)
* [log](https://github.com/aerogo/log) **star:6** An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).   [![godoc][GoDoc]](https://godoc.org/github.com/aerogo/log)
* [xlog](https://github.com/xfxdev/xlog) **star:6** Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.   [![It hasn't been updated in the last year][Yellow]](https://github.com/xfxdev/xlog)   [![godoc][GoDoc]](https://godoc.org/github.com/xfxdev/xlog)
* [logo](https://github.com/mbndr/logo) **star:5** Golang logger to different configurable writers.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mbndr/logo)   [![godoc][GoDoc]](https://godoc.org/github.com/mbndr/logo)
* [go-log](https://github.com/pieterclaerhout/go-log) **star:3** A logging library with strack traces, object dumping and optional timestamps.   [![godoc][GoDoc]](https://godoc.org/github.com/pieterclaerhout/go-log)

## Machine Learning

*Libraries for Machine Learning.*

* [GoLearn](https://github.com/sjwhitworth/golearn) **star:7031** General Machine Learning library for Go.   [![star > 2000][Awesome]](https://github.com/sjwhitworth/golearn)   [![godoc][GoDoc]](https://godoc.org/github.com/sjwhitworth/golearn)   [![Contains Chinese documents][CN]](https://github.com/sjwhitworth/golearn)
* [gorgonia](https://github.com/gorgonia/gorgonia) **star:3193** graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.   [![star > 2000][Awesome]](https://github.com/gorgonia/gorgonia)   [![godoc][GoDoc]](https://godoc.org/github.com/gorgonia/gorgonia)
* [tfgo](https://github.com/galeone/tfgo) **star:1317** Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.   [![godoc][GoDoc]](https://godoc.org/github.com/galeone/tfgo)
* [goml](https://github.com/cdipaolo/goml) **star:1080** On-line Machine Learning in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/cdipaolo/goml)
* [gosseract](https://github.com/otiai10/gosseract) **star:1071** Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/gosseract)
* [gorse](https://github.com/zhenghaoz/gorse) **star:927** An offline recommender system backend based on collaborative filtering written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/zhenghaoz/gorse)   [![Contains Chinese documents][CN]](https://github.com/zhenghaoz/gorse)
* [CloudForest](https://github.com/ryanbressler/CloudForest) **star:667** Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ryanbressler/CloudForest)   [![godoc][GoDoc]](https://godoc.org/github.com/ryanbressler/CloudForest)
* [eaopt](https://github.com/MaxHalford/eaopt) **star:665** An evolutionary optimization library.   [![godoc][GoDoc]](https://godoc.org/github.com/MaxHalford/eaopt)
* [bayesian](https://github.com/jbrukh/bayesian) **star:654** Naive Bayesian Classification for Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/jbrukh/bayesian)
* [gobrain](https://github.com/goml/gobrain) **star:433** Neural Networks written in go.   [![godoc][GoDoc]](https://godoc.org/github.com/goml/gobrain)
* [ocrserver](https://github.com/otiai10/ocrserver) **star:271** A simple OCR API server, seriously easy to be deployed by Docker and Heroku.   [![godoc][GoDoc]](https://godoc.org/github.com/otiai10/ocrserver)
* [regommend](https://github.com/muesli/regommend) **star:265** Recommendation & collaborative filtering engine.   [![godoc][GoDoc]](https://godoc.org/github.com/muesli/regommend)
* [go-deep](https://github.com/patrikeh/go-deep) **star:255** A feature-rich neural network library in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/patrikeh/go-deep)
* [onnx-go](https://github.com/owulveryck/onnx-go) **star:247** Go Interface to Open Neural Network Exchange (ONNX).   [![godoc][GoDoc]](https://godoc.org/github.com/owulveryck/onnx-go)
* [go-galib](https://github.com/thoj/go-galib) **star:177** Genetic Algorithms library written in Go / golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/thoj/go-galib)   [![godoc][GoDoc]](https://godoc.org/github.com/thoj/go-galib)
* [goRecommend](https://github.com/timkaye11/goRecommend) **star:155** Recommendation Algorithms library written in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/timkaye11/goRecommend)   [![godoc][GoDoc]](https://godoc.org/github.com/timkaye11/goRecommend)
* [shield](https://github.com/eaigner/shield) **star:129** Bayesian text classifier with flexible tokenizers and storage backends for Go.   [![There was an update last week][Green]](https://github.com/eaigner/shield)   [![godoc][GoDoc]](https://godoc.org/github.com/eaigner/shield)
* [Goptuna](https://github.com/c-bata/goptuna) **star:118** Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.   [![godoc][GoDoc]](https://godoc.org/github.com/c-bata/goptuna)
* [go-fann](https://github.com/white-pony/go-fann) **star:103** Go bindings for Fast Artificial Neural Networks(FANN) library.   [![It hasn't been updated in the last year][Yellow]](https://github.com/white-pony/go-fann)   [![godoc][GoDoc]](https://godoc.org/github.com/white-pony/go-fann)
* [goga](https://github.com/tomcraven/goga) **star:86** Genetic algorithm library for Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/tomcraven/goga)   [![godoc][GoDoc]](https://godoc.org/github.com/tomcraven/goga)
* [libsvm](https://github.com/datastream/libsvm) **star:64** libsvm golang version derived work based on LIBSVM 3.14.   [![It hasn't been updated in the last year][Yellow]](https://github.com/datastream/libsvm)   [![godoc][GoDoc]](https://godoc.org/github.com/datastream/libsvm)
* [neural-go](https://github.com/schuyler/neural-go) **star:61** Multilayer perceptron network implemented in Go, with training via backpropagation.   [![It hasn't been updated in the last year][Yellow]](https://github.com/schuyler/neural-go)   [![godoc][GoDoc]](https://godoc.org/github.com/schuyler/neural-go)
* [go-pr](https://github.com/daviddengcn/go-pr) **star:59** Pattern recognition package in Go lang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/daviddengcn/go-pr)   [![godoc][GoDoc]](https://godoc.org/github.com/daviddengcn/go-pr)
* [gonet](https://github.com/dathoangnd/gonet) **star:57** Neural Network for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/dathoangnd/gonet)
* [neat](https://github.com/jinyeom/neat) **star:56** Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).   [![It hasn't been updated in the last year][Yellow]](https://github.com/jinyeom/neat)   [![godoc][GoDoc]](https://godoc.org/github.com/jinyeom/neat)   [![Archived][Archived]](https://github.com/jinyeom/neat)
* [goscore](https://github.com/asafschers/goscore) **star:45** Go Scoring API for PMML.   [![godoc][GoDoc]](https://godoc.org/github.com/asafschers/goscore)
* [golinear](https://github.com/danieldk/golinear) **star:39** liblinear bindings for Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/danieldk/golinear)   [![godoc][GoDoc]](https://godoc.org/github.com/danieldk/golinear)
* [fonet](https://github.com/Fontinalis/fonet) **star:36** A Deep Neural Network library written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/Fontinalis/fonet)
* [Varis](https://github.com/Xamber/Varis) **star:28** Golang Neural Network.   [![It hasn't been updated in the last year][Yellow]](https://github.com/Xamber/Varis)   [![godoc][GoDoc]](https://godoc.org/github.com/Xamber/Varis)
* [godist](https://github.com/e-dard/godist) **star:25** Various probability distributions, and associated methods.   [![It hasn't been updated in the last year][Yellow]](https://github.com/e-dard/godist)   [![godoc][GoDoc]](https://godoc.org/github.com/e-dard/godist)
* [go-cluster](https://github.com/e-XpertSolutions/go-cluster) **star:22** Go implementation of the k-modes and k-prototypes clustering algorithms.   [![It hasn't been updated in the last year][Yellow]](https://github.com/e-XpertSolutions/go-cluster)   [![godoc][GoDoc]](https://godoc.org/github.com/e-XpertSolutions/go-cluster)
* [probab](https://github.com/ThePaw/probab) **star:12** Probability distribution functions. Bayesian inference. Written in pure Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/ThePaw/probab)   [![godoc][GoDoc]](https://godoc.org/github.com/ThePaw/probab)
* [evoli](https://github.com/khezen/evoli) **star:9** Genetic Algorithm and Particle Swarm Optimization library.   [![godoc][GoDoc]](https://godoc.org/github.com/khezen/evoli)
* [GoMind](https://github.com/surenderthakran/gomind) **star:7** A simplistic Neural Network Library in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/surenderthakran/gomind)   [![godoc][GoDoc]](https://godoc.org/github.com/surenderthakran/gomind)
* [randomforest](https://github.com/malaschitz/randomForest) **star:3** Easy to use Random Forest library for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/malaschitz/randomForest)

## Messaging

*Libraries that implement messaging systems.*

* [sarama](https://github.com/Shopify/sarama) **star:5460** Go library for Apache Kafka.   [![star > 2000][Awesome]](https://github.com/Shopify/sarama)   [![There was an update last week][Green]](https://github.com/Shopify/sarama)   [![godoc][GoDoc]](https://godoc.org/github.com/Shopify/sarama)
* [gorush](https://github.com/appleboy/gorush) **star:4209** Push notification server using [APNs2](https://github.com/sideshow/apns2) and google [GCM](https://github.com/google/go-gcm).   [![star > 2000][Awesome]](https://github.com/appleboy/gorush)   [![There was an update last week][Green]](https://github.com/appleboy/gorush)   [![godoc][GoDoc]](https://godoc.org/github.com/appleboy/gorush)
* [Centrifugo](https://github.com/centrifugal/centrifugo) **star:4104** Real-time messaging (Websockets or SockJS) server in Go.   [![star > 2000][Awesome]](https://github.com/centrifugal/centrifugo)   [![There was an update last week][Green]](https://github.com/centrifugal/centrifugo)   [![godoc][GoDoc]](https://godoc.org/github.com/centrifugal/centrifugo)
* [machinery](https://github.com/RichardKnop/machinery) **star:3880** Asynchronous task queue/job queue based on distributed message passing.   [![star > 2000][Awesome]](https://github.com/RichardKnop/machinery)   [![There was an update last week][Green]](https://github.com/RichardKnop/machinery)   [![godoc][GoDoc]](https://godoc.org/github.com/RichardKnop/machinery)
* [go-socket.io](https://github.com/googollee/go-socket.io) **star:3281** socket.io library for golang, a realtime application framework.   [![star > 2000][Awesome]](https://github.com/googollee/go-socket.io)   [![There was an update last week][Green]](https://github.com/googollee/go-socket.io)   [![godoc][GoDoc]](https://godoc.org/github.com/googollee/go-socket.io)
* [NATS Go Client](https://github.com/nats-io/nats) **star:2700** Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.   [![star > 2000][Awesome]](https://github.com/nats-io/nats)   [![godoc][GoDoc]](https://godoc.org/github.com/nats-io/nats)
* [APNs2](https://github.com/sideshow/apns2) **star:2263** HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.   [![star > 2000][Awesome]](https://github.com/sideshow/apns2)   [![godoc][GoDoc]](https://godoc.org/github.com/sideshow/apns2)
* [Benthos](https://github.com/Jeffail/benthos) **star:2244** A message streaming bridge between a range of protocols.   [![star > 2000][Awesome]](https://github.com/Jeffail/benthos)   [![There was an update last week][Green]](https://github.com/Jeffail/benthos)   [![godoc][GoDoc]](https://godoc.org/github.com/Jeffail/benthos)
* [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) **star:1893** gopush-cluster is a go push server cluster.   [![It hasn't been updated in the last year][Yellow]](https://github.com/Terry-Mao/gopush-cluster)   [![godoc][GoDoc]](https://godoc.org/github.com/Terry-Mao/gopush-cluster)   [![Contains Chinese documents][CN]](https://github.com/Terry-Mao/gopush-cluster)
* [Mercure](https://github.com/dunglas/mercure) **star:1882** Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).   [![godoc][GoDoc]](https://godoc.org/github.com/dunglas/mercure)
* [melody](https://github.com/olahol/melody) **star:1758** Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.   [![godoc][GoDoc]](https://godoc.org/github.com/olahol/melody)
* [go-nsq](https://github.com/nsqio/go-nsq) **star:1598** the official Go package for NSQ.   [![godoc][GoDoc]](https://godoc.org/github.com/nsqio/go-nsq)
* [mangos](https://github.com/go-mangos/mangos) **star:1538** Pure go implementation of the Nanomsg ("Scalable Protocols") with transport interoperability.   [![godoc][GoDoc]](https://godoc.org/github.com/go-mangos/mangos)   [![Archived][Archived]](https://github.com/go-mangos/mangos)
* [Uniqush-Push](https://github.com/uniqush/uniqush-push) **star:1141** Redis backed unified push service for server-side notifications to mobile devices.   [![godoc][GoDoc]](https://godoc.org/github.com/uniqush/uniqush-push)
* [zmq4](https://github.com/pebbe/zmq4) **star:836** Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) and [version 2](https://github.com/pebbe/zmq2).   [![godoc][GoDoc]](https://godoc.org/github.com/pebbe/zmq4)
* [Gollum](https://github.com/trivago/gollum) **star:834** A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.   [![godoc][GoDoc]](https://godoc.org/github.com/trivago/gollum)
* [Beaver](https://github.com/Clivern/Beaver) **star:814** A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.   [![There was an update last week][Green]](https://github.com/Clivern/Beaver)   [![godoc][GoDoc]](https://godoc.org/github.com/Clivern/Beaver)
* [EventBus](https://github.com/asaskevich/EventBus) **star:651** The lightweight event bus with async compatibility.   [![godoc][GoDoc]](https://godoc.org/github.com/asaskevich/EventBus)
* [golongpoll](https://github.com/jcuga/golongpoll) **star:446** HTTP longpoll server library that makes web pub-sub simple.   [![There was an update last week][Green]](https://github.com/jcuga/golongpoll)   [![godoc][GoDoc]](https://godoc.org/github.com/jcuga/golongpoll)
* [dbus](https://github.com/godbus/dbus) **star:428** Native Go bindings for D-Bus.   [![godoc][GoDoc]](https://godoc.org/github.com/godbus/dbus)
* [emitter](https://github.com/olebedev/emitter) **star:344** Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.   [![godoc][GoDoc]](https://godoc.org/github.com/olebedev/emitter)
* [Glue](https://github.com/desertbit/glue) **star:333** Robust Go and Javascript Socket Library (Alternative to Socket.io).   [![godoc][GoDoc]](https://godoc.org/github.com/desertbit/glue)
* [pubsub](https://github.com/tuxychandru/pubsub) **star:309** Simple pubsub package for go.   [![godoc][GoDoc]](https://godoc.org/github.com/tuxychandru/pubsub)
* [guble](https://github.com/smancke/guble) **star:142** Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.   [![It hasn't been updated in the last year][Yellow]](https://github.com/smancke/guble)   [![godoc][GoDoc]](https://godoc.org/github.com/smancke/guble)
* [Bus](https://github.com/mustafaturan/bus) **star:140** Minimalist message bus implementation for internal communication.   [![godoc][GoDoc]](https://godoc.org/github.com/mustafaturan/bus)
* [rabtap](https://github.com/jandelgado/rabtap) **star:109** RabbitMQ swiss army knife cli app.   [![godoc][GoDoc]](https://godoc.org/github.com/jandelgado/rabtap)
* [oplog](https://github.com/dailymotion/oplog) **star:102** Generic oplog/replication system for REST APIs.   [![It hasn't been updated in the last year][Yellow]](https://github.com/dailymotion/oplog)   [![godoc][GoDoc]](https://godoc.org/github.com/dailymotion/oplog)
* [messagebus](https://github.com/vardius/message-bus) **star:98** messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/message-bus)
* [rabbus](https://github.com/rafaeljesus/rabbus) **star:69** A tiny wrapper over amqp exchanges and queues.   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/rabbus)
* [drone-line](https://github.com/appleboy/drone-line) **star:67** Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.   [![godoc][GoDoc]](https://godoc.org/github.com/appleboy/drone-line)
* [RapidMQ](https://github.com/sybrexsys/RapidMQ) **star:58** RapidMQ is a lightweight and reliable library for managing of the local messages queue.   [![It hasn't been updated in the last year][Yellow]](https://github.com/sybrexsys/RapidMQ)   [![godoc][GoDoc]](https://godoc.org/github.com/sybrexsys/RapidMQ)
* [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) **star:57** A tiny wrapper around NSQ topic and channel.   [![It hasn't been updated in the last year][Yellow]](https://github.com/rafaeljesus/nsq-event-bus)   [![godoc][GoDoc]](https://godoc.org/github.com/rafaeljesus/nsq-event-bus)
* [go-notify](https://github.com/TheCreeper/go-notify) **star:48** Native implementation of the freedesktop notification spec.   [![It hasn't been updated in the last year][Yellow]](https://github.com/TheCreeper/go-notify)   [![godoc][GoDoc]](https://godoc.org/github.com/TheCreeper/go-notify)
* [hub](https://github.com/leandro-lugaresi/hub) **star:48** A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.   [![godoc][GoDoc]](https://godoc.org/github.com/leandro-lugaresi/hub)
* [Commander](https://github.com/jeroenrinzema/commander) **star:40** A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.   [![godoc][GoDoc]](https://godoc.org/github.com/jeroenrinzema/commander)
* [event](https://github.com/agoalofalife/event) **star:33** Implementation of the pattern observer.   [![It hasn't been updated in the last year][Yellow]](https://github.com/agoalofalife/event)   [![godoc][GoDoc]](https://godoc.org/github.com/agoalofalife/event)
* [go-vitotrol](https://github.com/maxatome/go-vitotrol) **star:13** Client library to Viessmann Vitotrol web service.   [![godoc][GoDoc]](https://godoc.org/github.com/maxatome/go-vitotrol)
* [redisqueue](https://github.com/robinjoseph08/redisqueue) **star:11** redisqueue provides a producer and consumer of a queue that uses Redis streams.   [![godoc][GoDoc]](https://godoc.org/github.com/robinjoseph08/redisqueue)
* [jazz](https://github.com/socifi/jazz) **star:9** A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.   [![godoc][GoDoc]](https://godoc.org/github.com/socifi/jazz)
* [gaurun-client](https://github.com/osamingo/gaurun-client) **star:8** Gaurun Client written in Go.   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/gaurun-client)
* [ami](https://github.com/kak-tus/ami) **star:6** Go client to reliable queues based on Redis Cluster Streams.   [![There was an update last week][Green]](https://github.com/kak-tus/ami)   [![godoc][GoDoc]](https://godoc.org/github.com/kak-tus/ami)
* [rmqconn](https://github.com/sbabiv/rmqconn) **star:3** RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.   [![godoc][GoDoc]](https://godoc.org/github.com/sbabiv/rmqconn)

## Microsoft Office

* [unioffice](https://github.com/unidoc/unioffice) **star:2127** Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.   [![star > 2000][Awesome]](https://github.com/unidoc/unioffice)   [![There was an update last week][Green]](https://github.com/unidoc/unioffice)   [![godoc][GoDoc]](https://godoc.org/github.com/unidoc/unioffice)

### Microsoft Excel

*Libraries for working with Microsoft Excel.*

* [excelize](https://github.com/360EntSecGroup-Skylar/excelize) **star:5788** Golang library for reading and writing Microsoft Excel™ (XLSX) files.   [![star > 2000][Awesome]](https://github.com/360EntSecGroup-Skylar/excelize)   [![There was an update last week][Green]](https://github.com/360EntSecGroup-Skylar/excelize)   [![godoc][GoDoc]](https://godoc.org/github.com/360EntSecGroup-Skylar/excelize)
* [xlsx](https://github.com/tealeg/xlsx) **star:3928** Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.   [![star > 2000][Awesome]](https://github.com/tealeg/xlsx)   [![There was an update last week][Green]](https://github.com/tealeg/xlsx)   [![godoc][GoDoc]](https://godoc.org/github.com/tealeg/xlsx)
* [xlsx](https://github.com/plandem/xlsx) **star:106** Fast and safe way to read/update your existing Microsoft Excel files in Go programs.   [![godoc][GoDoc]](https://godoc.org/github.com/plandem/xlsx)
* [go-excel](https://github.com/szyhf/go-excel) **star:70** A simple and light reader to read a relate-db-like excel as a table.   [![godoc][GoDoc]](https://godoc.org/github.com/szyhf/go-excel)
* [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) **star:15** Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.   [![It hasn't been updated in the last year][Yellow]](https://github.com/fterrag/goxlsxwriter)   [![godoc][GoDoc]](https://godoc.org/github.com/fterrag/goxlsxwriter)

## Miscellaneous

### Dependency Injection

*Libraries for working with dependency injection.*

* [dig](https://github.com/uber-go/dig) **star:1294** A reflection based dependency injection toolkit for Go.   [![There was an update last week][Green]](https://github.com/uber-go/dig)   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/dig)
* [fx](https://github.com/uber-go/fx) **star:1188** A dependency injection based application framework for Go (built on top of dig).   [![godoc][GoDoc]](https://godoc.org/github.com/uber-go/fx)
* [container](https://github.com/golobby/container) **star:77** A powerful IoC Container with fluent and easy-to-use interface.   [![godoc][GoDoc]](https://godoc.org/github.com/golobby/container)
* [inject](https://github.com/defval/inject) **star:53** A reflection based dependency injection container with simple interface.   [![godoc][GoDoc]](https://godoc.org/github.com/defval/inject)   [![Archived][Archived]](https://github.com/defval/inject)
* [dingo](https://github.com/i-love-flamingo/dingo) **star:41** A dependency injection toolkit for Go, based on Guice.   [![godoc][GoDoc]](https://godoc.org/github.com/i-love-flamingo/dingo)
* [alice](https://github.com/magic003/alice) **star:38** Additive dependency injection container for Golang.   [![It hasn't been updated in the last year][Yellow]](https://github.com/magic003/alice)   [![godoc][GoDoc]](https://godoc.org/github.com/magic003/alice)
* [wire](https://github.com/Fs02/wire) **star:29** Strict Runtime Dependency Injection for Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/Fs02/wire)
* [linker](https://github.com/logrange/linker) **star:21** A reflection based dependency injection and inversion of control library with components lifecycle support.   [![godoc][GoDoc]](https://godoc.org/github.com/logrange/linker)
* [gocontainer](https://github.com/vardius/gocontainer) **star:12** Simple Dependency Injection Container.   [![godoc][GoDoc]](https://godoc.org/github.com/vardius/gocontainer)

### Project Layout

*Unofficial set of patterns for structuring projects.*

* [golang-standards/project-layout](https://github.com/golang-standards/project-layout) **star:13531** Set of common historical and emerging project layout patterns in the Go ecosystem.   [![star > 2000][Awesome]](https://github.com/golang-standards/project-layout)
* [modern-go-application](https://github.com/sagikazarmark/modern-go-application) **star:559** Go application boilerplate and example applying modern practices.   [![godoc][GoDoc]](https://godoc.org/github.com/sagikazarmark/modern-go-application)
* [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) **star:323** A Go application boilerplate template for quick starting projects following production best practices.   [![There was an update last week][Green]](https://github.com/lacion/cookiecutter-golang)   [![godoc][GoDoc]](https://godoc.org/github.com/lacion/cookiecutter-golang)
* [scaffold](https://github.com/catchplay/scaffold) **star:58** Scaffold generates starter Go project layout. Lets you focus on business logic implemeted.   [![It hasn't been updated in the last year][Yellow]](https://github.com/catchplay/scaffold)   [![godoc][GoDoc]](https://godoc.org/github.com/catchplay/scaffold)
* [go-sample](https://github.com/zitryss/go-sample) **star:45** A sample layout for Go application projects with the real code.   [![It hasn't been updated in the last year][Yellow]](https://github.com/zitryss/go-sample)   [![godoc][GoDoc]](https://godoc.org/github.com/zitryss/go-sample)

### Strings

*Libraries for working with strings.*

* [xstrings](https://github.com/huandu/xstrings) **star:718** Collection of useful string functions ported from other languages.   [![godoc][GoDoc]](https://godoc.org/github.com/huandu/xstrings)
* [strutil](https://github.com/ozgio/strutil) **star:85** String utilities.   [![godoc][GoDoc]](https://godoc.org/github.com/ozgio/strutil)

*These libraries were placed here because none of the other categories seemed to fit.*

* [gopsutil](https://github.com/shirou/gopsutil) **star:4610** Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).   [![star > 2000][Awesome]](https://github.com/shirou/gopsutil)   [![There was an update last week][Green]](https://github.com/shirou/gopsutil)   [![godoc][GoDoc]](https://godoc.org/github.com/shirou/gopsutil)
* [archiver](https://github.com/mholt/archiver) **star:2741** Library and command for making and extracting .zip and .tar.gz archives.   [![star > 2000][Awesome]](https://github.com/mholt/archiver)   [![godoc][GoDoc]](https://godoc.org/github.com/mholt/archiver)
* [gosms](https://github.com/haxpax/gosms) **star:1271** Your own local SMS gateway in Go that can be used to send SMS.   [![It hasn't been updated in the last year][Yellow]](https://github.com/haxpax/gosms)   [![godoc][GoDoc]](https://godoc.org/github.com/haxpax/gosms)
* [go-resiliency](https://github.com/eapache/go-resiliency) **star:978** Resiliency patterns for golang.   [![godoc][GoDoc]](https://godoc.org/github.com/eapache/go-resiliency)
* [gofakeit](https://github.com/brianvoe/gofakeit) **star:833** Random data generator written in go.   [![godoc][GoDoc]](https://godoc.org/github.com/brianvoe/gofakeit)
* [base64Captcha](https://github.com/mojocn/base64Captcha) **star:779** Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.   [![There was an update last week][Green]](https://github.com/mojocn/base64Captcha)   [![godoc][GoDoc]](https://godoc.org/github.com/mojocn/base64Captcha)   [![Contains Chinese documents][CN]](https://github.com/mojocn/base64Captcha)
* [go-openapi](https://github.com/go-openapi)  Collection of packages to parse and utilize open-api schemas.
* [go-commons-pool](https://github.com/jolestar/go-commons-pool) **star:774** Generic object pool for Golang.   [![godoc][GoDoc]](https://godoc.org/github.com/jolestar/go-commons-pool)   [![Contains Chinese documents][CN]](https://github.com/jolestar/go-commons-pool)
* [shortid](https://github.com/teris-io/shortid) **star:529** Distributed generation of super short, unique, non-sequential, URL friendly IDs.   [![It hasn't been updated in the last year][Yellow]](https://github.com/teris-io/shortid)   [![godoc][GoDoc]](https://godoc.org/github.com/teris-io/shortid)
* [llvm](https://github.com/llir/llvm) **star:502** Library for interacting with LLVM IR in pure Go.   [![godoc][GoDoc]](https://godoc.org/github.com/llir/llvm)
* [health](https://github.com/dimiro1/health) **star:380** Easy to use, extensible health check library.   [![godoc][GoDoc]](https://godoc.org/github.com/dimiro1/health)
* [conv](https://github.com/cstockton/go-conv) **star:350** Package conv provides fast and intuitive conversions across Go types.   [![It hasn't been updated in the last year][Yellow]](https://github.com/cstockton/go-conv)   [![godoc][GoDoc]](https://godoc.org/github.com/cstockton/go-conv)
* [banner](https://github.com/dimiro1/banner) **star:255** Add beautiful banners into your Go applications.   [![godoc][GoDoc]](https://godoc.org/github.com/dimiro1/banner)
* [gountries](https://github.com/pariz/gountries) **star:235** Package that exposes country and subdivision data.   [![godoc][GoDoc]](https://godoc.org/github.com/pariz/gountries)
* [antch](https://github.com/antchfx/antch) **star:169** A fast, powerful and extensible web crawling & scraping framework.   [![It hasn't been updated in the last year][Yellow]](https://github.com/antchfx/antch)   [![godoc][GoDoc]](https://godoc.org/github.com/antchfx/antch)   [![Contains Chinese documents][CN]](https://github.com/antchfx/antch)
* [ffmt](https://github.com/go-ffmt/ffmt) **star:155** Beautify data display for Humans.   [![godoc][GoDoc]](https://godoc.org/github.com/go-ffmt/ffmt)   [![Contains Chinese documents][CN]](https://github.com/go-ffmt/ffmt)
* [stateless](https://github.com/qmuntal/stateless) **star:148** A fluent library for creating state machines.   [![godoc][GoDoc]](https://godoc.org/github.com/qmuntal/stateless)
* [lk](https://github.com/hyperboloide/lk) **star:143** A simple licensing library for golang.   [![godoc][GoDoc]](https://godoc.org/github.com/hyperboloide/lk)
* [battery](https://github.com/distatus/battery) **star:143** Cross-platform, normalized battery information library.   [![godoc][GoDoc]](https://godoc.org/github.com/distatus/battery)
* [ghorg](https://github.com/gabrie30/ghorg) **star:136** Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, and Bitbucket.   [![There was an update last week][Green]](https://github.com/gabrie30/ghorg)   [![godoc][GoDoc]](https://godoc.org/github.com/gabrie30/ghorg)
* [stats](https://github.com/go-playground/stats) **star:131** Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...   [![It hasn't been updated in the last year][Yellow]](https://github.com/go-playground/stats)   [![godoc][GoDoc]](https://godoc.org/github.com/go-playground/stats)
* [bitio](https://github.com/icza/bitio) **star:116** Highly optimized bit-level Reader and Writer for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/icza/bitio)
* [healthcheck](https://github.com/etherlabsio/healthcheck) **star:104** An opinionated and concurrent health-check HTTP handler for RESTful services.   [![godoc][GoDoc]](https://godoc.org/github.com/etherlabsio/healthcheck)
* [turtle](https://github.com/hackebrot/turtle) **star:94** Emojis for Go.   [![godoc][GoDoc]](https://godoc.org/github.com/hackebrot/turtle)
* [go-unarr](https://github.com/gen2brain/go-unarr) **star:86** Decompression library for RAR, TAR, ZIP and 7z archives.   [![godoc][GoDoc]](https://godoc.org/github.com/gen2brain/go-unarr)
* [gommit](https://github.com/antham/gommit) **star:85** Analyze git commit messages to ensure they follow defined patterns.   [![godoc][GoDoc]](https://godoc.org/github.com/antham/gommit)
* [gotoprom](https://github.com/cabify/gotoprom) **star:80** Type-safe metrics builder wrapper library for the official Prometheus client.   [![godoc][GoDoc]](https://godoc.org/github.com/cabify/gotoprom)
* [indigo](https://github.com/osamingo/indigo) **star:58** Distributed unique ID generator of using Sonyflake and encoded by Base58.   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/indigo)
* [morse](https://github.com/alwindoss/morse) **star:57** Library to convert to and from morse code.   [![It hasn't been updated in the last year][Yellow]](https://github.com/alwindoss/morse)   [![godoc][GoDoc]](https://godoc.org/github.com/alwindoss/morse)
* [captcha](https://github.com/steambap/captcha) **star:54** Package captcha provides an easy to use, unopinionated API for captcha generation.   [![godoc][GoDoc]](https://godoc.org/github.com/steambap/captcha)
* [xkg](https://github.com/go-xkg/xkg) **star:48** X Keyboard Grabber.   [![It hasn't been updated in the last year][Yellow]](https://github.com/go-xkg/xkg)   [![godoc][GoDoc]](https://godoc.org/github.com/go-xkg/xkg)
* [persian](https://github.com/mavihq/persian) **star:40** Some utilities for Persian language in go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mavihq/persian)   [![godoc][GoDoc]](https://godoc.org/github.com/mavihq/persian)
* [pdfgen](https://github.com/hyperboloide/pdfgen) **star:39** HTTP service to generate PDF from Json requests.   [![It hasn't been updated in the last year][Yellow]](https://github.com/hyperboloide/pdfgen)   [![godoc][GoDoc]](https://godoc.org/github.com/hyperboloide/pdfgen)
* [datacounter](https://github.com/miolini/datacounter) **star:31** Go counters for readers/writer/http.ResponseWriter.   [![godoc][GoDoc]](https://godoc.org/github.com/miolini/datacounter)
* [browscap_go](https://github.com/digitalcrab/browscap_go) **star:31** GoLang Library for [Browser Capabilities Project](http://browscap.org/).   [![godoc][GoDoc]](https://godoc.org/github.com/digitalcrab/browscap_go)
* [autoflags](https://github.com/artyom/autoflags) **star:26** Go package to automatically define command line flags from struct fields.   [![It hasn't been updated in the last year][Yellow]](https://github.com/artyom/autoflags)   [![godoc][GoDoc]](https://godoc.org/github.com/artyom/autoflags)
* [xdg](https://github.com/rkoesters/xdg) **star:21** FreeDesktop.org (xdg) Specs implemented in Go.   [![It hasn't been updated in the last year][Yellow]](https://github.com/rkoesters/xdg)   [![godoc][GoDoc]](https://godoc.org/github.com/rkoesters/xdg)
* [gosh](https://github.com/osamingo/gosh) **star:20** Provide Go Statistics Handler, Struct, Measure Method.   [![godoc][GoDoc]](https://godoc.org/github.com/osamingo/gosh)
* [url-shortener](https://github.com/pantrif/url-shortener) **star:19** A modern, powerful, and robust URL shortener microservice with mysql support.   [![It hasn't been updated in the last year][Yellow]](https://github.com/pantrif/url-shortener)   [![godoc][GoDoc]](https://godoc.org/github.com/pantrif/url-shortener)
* [VarHandler](https://github.com/azr/generators/tree/master/varhandler)  Generate boilerplate http input and output handling.
* [sandid](https://github.com/aofei/sandid) **star:15** Every grain of sand on earth has its own ID.   [![godoc][GoDoc]](https://godoc.org/github.com/aofei/sandid)
* [anagent](https://github.com/mudler/anagent) **star:11** Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.   [![It hasn't been updated in the last year][Yellow]](https://github.com/mudler/anagent)   [![godoc][GoDoc]](https://godoc.org/github.com/mudler/anagent)
* [avgRating](https://github.com/kirillDanshin/avgRating) **star:10** Calculate average score and rating based on Wilson Score Equation.   [![It hasn't been updated in the last year][Yellow]](https://github.com/kirillDanshin/avgRating)   [![godoc][GoDoc]](https://godoc.org/github.com/kirillDanshin/avgRating)
* [hostutils](https://github.com/Wing924/hostutils) **star:8** A golang library for packing and unpacking FQDNs list.   [![It hasn't been updated in the last year][Yellow]](https://github.com/Wing924/hostutils)   [![godoc][GoDoc]](https://godoc.org/github.com/Wing924/hostutils)
* [shellwords](https://github.com/Wing924/shellwords) **star:8** A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.   [![It hasn't been updated in the last year][Yellow]](https://github.com/Wing924/shellwords)   [![godoc][GoDoc]](https://godoc.org/github.com/Wing924/shellwords)
* [metrics](https://github.com/pascaldekloe/metrics) **star:6** Library for metrics instrumentation and Prometheus exposition.   [![godoc][GoDoc]](https://godoc.org/github.com/pascaldekloe/metrics)
* [numa](https://github.com/lrita/numa) **star:2** NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.   [![godoc][GoDoc]](https://godoc.org/github.com/lrita/numa)

## Natural Language Processing

*Libraries for working with human languages.*

