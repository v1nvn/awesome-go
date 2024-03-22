# Awesome Go

<a href="https://awesome-go.com/"><img align="right" src="https://github.com/avelino/awesome-go/raw/main/tmpl/assets/logo.png" alt="awesome-go" title="awesome-go" /></a>

[![Build Status](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml/badge.svg?branch=main)](https://github.com/avelino/awesome-go/actions/workflows/tests.yaml?query=branch%3Amain)
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 294,926 📅 2024-02-14
[![Slack Widget](https://img.shields.io/badge/join-us%20on%20slack-gray.svg?longCache=true&logo=slack&colorB=red)](https://gophers.slack.com/messages/awesome)
[![Netlify Status](https://api.netlify.com/api/v1/badges/83a6dcbe-0da6-433e-b586-f68109286bd5/deploy-status)](https://app.netlify.com/sites/awesome-go/deploys)
[![Track Awesome List](https://www.trackawesomelist.com/badge.svg)](https://www.trackawesomelist.com/avelino/awesome-go/)

We use the _[Golang Bridge](https://github.com/gobridge/about-us/blob/master/README.md)_ community Slack for instant communication, follow the [form here to join](https://invite.slack.golangbridge.org/).

<a href="https://www.producthunt.com/posts/awesome-go?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-awesome-go" target="_blank"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=291535&theme=light" alt="awesome-go - Curated list awesome Go frameworks, libraries and software | Product Hunt" style="width: 250px; height: 54px;" width="250" height="54" /></a>

**Sponsorships:**

_Special thanks to_

<div align="center">
<table cellpadding="5">
<tbody align="center">
<tr>
<td>
<a href="https://bit.ly/awesome-go-workos">
<img src="https://avelino.run/sponsors/workos-logo-white-bg.svg" width="200" alt="WorkOS"><br/>
<b>Your app, enterprise-ready.</b><br/>
<sub>Start selling to enterprise customers with just a few lines of code.</sub><br/>
<sup>Add Single Sign-On (and more) in minutes instead of months.</sup>
</a>
</td>
<td>
<a href="https://bit.ly/awesome-go-keygen">
<img src="https://avelino.run/sponsors/keygen-logo.png" width="200" alt="keygen"><br/>
<b>An open, source-available software licensing and distribution API.</b><br/>
<sub>Securely license and distribute Go applications with a single API.</sub><br>
<sup>Add auto updates with only a few lines of code.</sup>
</a>
</td>
</tr>
<tr>
<td colspan="2">
<a href="https://bit.ly/awesome-go-digitalocean">
<img src="https://avelino.run/sponsors/do_logo_horizontal_blue-210.png" width="200" alt="Digital Ocean">
</a>
</td>
</tr>
</tbody>
</table>
</div>

**Awesome Go has no monthly fee**_, but we have employees who **work hard** to keep it running. With money raised, we can repay the effort of each person involved! You can see how we calculate our billing and distribution as it is open to the entire community. Want to be a supporter of the project click [here](mailto:avelinorun+oss@gmail.com?subject=awesome-go%3A%20project%20support)._

> A curated list of awesome Go frameworks, libraries, and software. Inspired by [awesome-python](https://github.com/vinta/awesome-python) ⭐ 201,658 📅 2024-02-22.

**Contributing:**

Please take a quick gander at the [contribution guidelines](https://github.com/avelino/awesome-go/blob/main/CONTRIBUTING.md) first. Thanks to all [contributors](https://github.com/avelino/awesome-go/graphs/contributors); you rock!

> _If you see a package or project here that is no longer maintained or is not a good fit, please submit a pull request to improve this file. Thank you!_

## Contents

- [Awesome Go](#awesome-go)
  - [Contents](#contents)
  - [Artificial Intelligence](#artificial-intelligence)
  - [Audio and Music](#audio-and-music)
  - [Authentication and OAuth](#authentication-and-oauth)
  - [Blockchain](#blockchain)
  - [Bot Building](#bot-building)
  - [Build Automation](#build-automation)
  - [Command Line](#command-line)
    - [Advanced Console UIs](#advanced-console-uis)
    - [Standard CLI](#standard-cli)
  - [Configuration](#configuration)
  - [Continuous Integration](#continuous-integration)
  - [CSS Preprocessors](#css-preprocessors)
  - [Data Structures and Algorithms](#data-structures-and-algorithms)
    - [Bit-packing and Compression](#bit-packing-and-compression)
    - [Bit Sets](#bit-sets)
    - [Bloom and Cuckoo Filters](#bloom-and-cuckoo-filters)
    - [Data Structure and Algorithm Collections](#data-structure-and-algorithm-collections)
    - [Iterators](#iterators)
    - [Maps](#maps)
    - [Miscellaneous Data Structures and Algorithms](#miscellaneous-data-structures-and-algorithms)
    - [Nullable Types](#nullable-types)
    - [Queues](#queues)
    - [Sets](#sets)
    - [Text Analysis](#text-analysis)
    - [Trees](#trees)
    - [Pipes](#pipes)
  - [Database](#database)
    - [Caches](#caches)
    - [Databases Implemented in Go](#databases-implemented-in-go)
    - [Database Schema Migration](#database-schema-migration)
    - [Database Tools](#database-tools)
    - [SQL Query Builders](#sql-query-builders)
  - [Database Drivers](#database-drivers)
    - [Interfaces to Multiple Backends](#interfaces-to-multiple-backends)
    - [Relational Database Drivers](#relational-database-drivers)
    - [NoSQL Database Drivers](#nosql-database-drivers)
    - [Search and Analytic Databases](#search-and-analytic-databases)
  - [Date and Time](#date-and-time)
  - [Distributed Systems](#distributed-systems)
  - [Dynamic DNS](#dynamic-dns)
  - [Email](#email)
  - [Embeddable Scripting Languages](#embeddable-scripting-languages)
  - [Error Handling](#error-handling)
  - [File Handling](#file-handling)
  - [Financial](#financial)
  - [Forms](#forms)
  - [Functional](#functional)
  - [Game Development](#game-development)
  - [Generators](#generators)
  - [Geographic](#geographic)
  - [Go Compilers](#go-compilers)
  - [Goroutines](#goroutines)
  - [GUI](#gui)
  - [Hardware](#hardware)
  - [Images](#images)
  - [IoT (Internet of Things)](#iot-internet-of-things)
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
    - [Uncategorized](#uncategorized)
  - [Natural Language Processing](#natural-language-processing)
    - [Language Detection](#language-detection)
    - [Morphological Analyzers](#morphological-analyzers)
    - [Slugifiers](#slugifiers)
    - [Tokenizers](#tokenizers)
    - [Translation](#translation)
    - [Transliteration](#transliteration)
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
    - [Formatters](#formatters)
    - [Markup Languages](#markup-languages)
    - [Parsers/Encoders/Decoders](#parsersencodersdecoders)
    - [Regular Expressions](#regular-expressions)
    - [Sanitation](#sanitation)
    - [Scrapers](#scrapers)
    - [RSS](#rss)
    - [Utility/Miscellaneous](#utilitymiscellaneous)
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
  - [WebAssembly](#webassembly)
  - [Windows](#windows)
  - [XML](#xml)
  - [Zero Trust](#zero-trust)
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
    - [E-books for purchase](#e-books-for-purchase)
    - [Free e-books](#free-e-books)
  - [Gophers](#gophers)
  - [Meetups](#meetups)
  - [Style Guides](#style-guides)
  - [Social Media](#social-media)
    - [Twitter](#twitter)
    - [Reddit](#reddit)
  - [Websites](#websites)
    - [Tutorials](#tutorials)
    - [Guided Learning](#guided-learning)

**[⬆ back to top](#contents)**

## Artificial Intelligence

_Libraries for building programs that leverage AI._

- [langchaingo](https://github.com/tmc/langchaingo) ⭐ 2,582 📅 2024-03-21 - LangChainGo is a framework for developing applications powered by language models.
- [LocalAI](https://github.com/mudler/LocalAI) ⭐ 17,910 📅 2024-03-21 - Open Source OpenAI alternative, self-host AI models.
- [Ollama](https://github.com/jmorganca/ollama) ⭐ 49,517 📅 2024-03-21 - Run large language models locally.

**[⬆ back to top](#contents)**

## Audio and Music

_Libraries for manipulating audio._

- [flac](https://github.com/mewkiz/flac) ⭐ 286 📅 2023-11-18 - Native Go FLAC encoder/decoder with support for FLAC streams.
- [gaad](https://github.com/Comcast/gaad) ⭐ 120 📅 2023-01-25 - Native Go AAC bitstream parser.
- [GoAudio](https://github.com/DylanMeeus/GoAudio) ⭐ 321 📅 2022-02-05 - Native Go Audio Processing Library.
- [gosamplerate](https://github.com/dh1tw/gosamplerate) ⭐ 32 📅 2024-01-28 - libsamplerate bindings for go.
- [id3v2](https://github.com/bogem/id3v2) ⭐ 322 📅 2023-05-09 - ID3 decoding and encoding library for Go.
- [malgo](https://github.com/gen2brain/malgo) ⭐ 256 📅 2023-12-25 - Mini audio library.
- [minimp3](https://github.com/tosone/minimp3) ⭐ 116 📅 2023-08-01 - Lightweight MP3 decoder library.
- [Oto](https://github.com/hajimehoshi/oto) ⭐ 1,456 📅 2024-02-14 - A low-level library to play sound on multiple platforms.
- [PortAudio](https://github.com/gordonklaus/portaudio) ⭐ 660 📅 2023-07-09 - Go bindings for the PortAudio audio I/O library.

**[⬆ back to top](#contents)**

## Authentication and OAuth

_Libraries for implementing authentication schemes._

- [authboss](https://github.com/volatiletech/authboss) ⭐ 3,621 📅 2023-12-30 - Modular authentication system for the web. It tries to remove as much boilerplate and "hard things" as possible so that each time you start a new web project in Go, you can plug it in, configure it, and start building your app without having to build an authentication system each time.
- [branca](https://github.com/essentialkaos/branca) ⭐ 74 📅 2024-01-09 - branca token [specification implementation](https://github.com/tuupola/branca-spec) ⭐ 215 📅 2021-08-30 for Golang 1.15+.
- [casbin](https://github.com/hsluoyz/casbin) ⭐ 16,703 📅 2024-03-18 - Authorization library that supports access control models like ACL, RBAC, and ABAC.
- [cookiestxt](https://github.com/mengzhuo/cookiestxt) ⭐ 13 📅 2024-03-12 - provides a parser of cookies.txt file format.
- [go-guardian](https://github.com/shaj13/go-guardian) ⭐ 523 📅 2023-03-02 - Go-Guardian is a golang library that provides a simple, clean, and idiomatic way to create powerful modern API and web authentication that supports LDAP, Basic, Bearer token, and Certificate based authentication.
- [go-jose](https://github.com/go-jose/go-jose) ⭐ 231 📅 2024-03-07 - Fairly complete implementation of the JOSE working group's JSON Web Token, JSON Web Signatures, and JSON Web Encryption specs.
- [gologin](https://github.com/dghubble/gologin) ⭐ 1,757 📅 2024-03-15 - chainable handlers for login with OAuth1 and OAuth2 authentication providers.
- [gorbac](https://github.com/mikespook/gorbac) ⭐ 1,543 📅 2023-01-10 - provides a lightweight role-based access control (RBAC) implementation in Golang.
- [gosession](http://github.com/Kwynto/gosession) ⭐ 143 📅 2023-07-31 - This is quick session for net/http in GoLang. This package is perhaps the best implementation of the session mechanism, or at least it tries to become one.
- [goth](https://github.com/markbates/goth) ⭐ 4,861 📅 2024-03-11 - provides a simple, clean, and idiomatic way to use OAuth and OAuth2. Handles multiple providers out of the box.
- [jeff](https://github.com/abraithwaite/jeff) ⭐ 260 📅 2021-06-23 - Simple, flexible, secure, and idiomatic web session management with pluggable backends.
- [jwt](https://github.com/pascaldekloe/jwt) ⭐ 347 📅 2023-04-29 - Lightweight JSON Web Token (JWT) library.
- [jwt](https://github.com/cristalhq/jwt) ⭐ 638 📅 2024-03-03 - Safe, simple, and fast JSON Web Tokens for Go.
- [jwt-auth](https://github.com/adam-hanna/jwt-auth) ⭐ 231 📅 2021-08-01 - JWT middleware for Golang http servers with many configuration options.
- [jwt-go](https://github.com/golang-jwt/jwt) ⭐ 6,215 📅 2024-03-16 - A full featured implementation of JSON Web Tokens (JWT). This library supports the parsing and verification as well as the generation and signing of JWTs.
- [keto](https://github.com/ory/keto) ⭐ 4,557 📅 2024-03-05 - Open Source (Go) implementation of "Zanzibar: Google's Consistent, Global Authorization System". Ships gRPC, REST APIs, newSQL, and an easy and granular permission language. Supports ACL, RBAC, and other access models.
- [loginsrv](https://github.com/tarent/loginsrv) ⭐ 1,911 📅 2021-02-11 - JWT login microservice with pluggable backends such as OAuth2 (Github), htpasswd, osiam.
- [oauth2](https://github.com/golang/oauth2) ⭐ 5,100 📅 2024-03-11 - Successor of goauth2. Generic OAuth 2.0 package that comes with JWT, Google APIs, Compute Engine, and App Engine support.
- [oidc](https://github.com/zitadel/oidc) ⭐ 1,151 📅 2024-03-18 - Easy to use OpenID Connect client and server library written for Go and certified by the OpenID Foundation
- [openfga](https://github.com/openfga/openfga) ⭐ 2,121 📅 2024-03-21 - Implementation of fine-grained authorization based on the "Zanzibar: Google's Consistent, Global Authorization System" paper. Backed by [CNCF](https://www.cncf.io/).
- [osin](https://github.com/openshift/osin) ⭐ 1,880 📅 2022-03-17 - Golang OAuth2 server library.
- [otpgen](https://github.com/grijul/otpgen) ⭐ 133 📅 2021-08-06 - Library to generate TOTP/HOTP codes.
- [otpgo](https://github.com/jltorresm/otpgo) ⭐ 65 📅 2021-02-27 - Time-Based One-Time Password (TOTP) and HMAC-Based One-Time Password (HOTP) library for Go.
- [paseto](https://github.com/o1egl/paseto) ⭐ 797 📅 2022-09-05 - Golang implementation of Platform-Agnostic Security Tokens (PASETO).
- [permissions2](https://github.com/xyproto/permissions2) ⭐ 501 📅 2024-03-13 - Library for keeping track of users, login states, and permissions. Uses secure cookies and bcrypt.
- [scope](https://github.com/SonicRoshan/scope) ⭐ 35 📅 2021-05-25 - Easily Manage OAuth2 Scopes In Go.
- [scs](https://github.com/alexedwards/scs) ⭐ 1,897 📅 2024-03-16 - Session Manager for HTTP servers.
- [securecookie](https://github.com/chmike/securecookie) ⭐ 74 📅 2023-02-18 - Efficient secure cookie encoding/decoding.
- [session](https://github.com/icza/session) ⭐ 114 📅 2022-08-12 - Go session management for web servers (including support for Google App Engine - GAE).
- [sessions](https://github.com/adam-hanna/sessions) ⭐ 76 📅 2020-04-15 - Dead simple, highly performant, highly customizable sessions service for go http servers.
- [sessionup](https://github.com/swithek/sessionup) ⭐ 125 📅 2022-04-21 - Simple, yet effective HTTP session management and identification package.
- [sjwt](https://github.com/brianvoe/sjwt) ⭐ 116 📅 2024-02-01 - Simple jwt generator and parser.

**[⬆ back to top](#contents)**

## Blockchain

_Tools for building blockchains._

- [cometbft](https://github.com/cometbft/cometbft) ⭐ 512 📅 2024-03-20 - A distributed, Byzantine fault-tolerant, deterministic state machine replication engine. It is a fork of Tendermint Core and implements the Tendermint consensus algorithm.
- [cosmos-sdk](https://github.com/cosmos/cosmos-sdk) ⭐ 5,839 📅 2024-03-21 - A Framework for Building Public Blockchains in the Cosmos Ecosystem.
- [go-ethereum](https://github.com/ethereum/go-ethereum) ⭐ 45,503 📅 2024-03-21 - Official Go implementation of the Ethereum protocol.
- [gosemble](https://github.com/LimeChain/gosemble) ⭐ 6 📅 2024-03-15 - A Go-based framework for building Polkadot/Substrate-compatible runtimes.
- [gossamer](https://github.com/ChainSafe/gossamer) ⭐ 412 📅 2024-03-12 - A Go implementation of the Polkadot Host.
- [kubo](https://github.com/ipfs/kubo) ⭐ 15,710 📅 2024-03-19 - A blockchain framework implemented in Go. It provides content-addressable storage which can be used for decentralized storage in DApps. It is based on the IPFS protocol.
- [solana-go](https://github.com/gagliardetto/solana-go) ⭐ 568 📅 2024-03-15 - Go library to interface with Solana JSON RPC and WebSocket interfaces.
- [tendermint](https://github.com/tendermint/tendermint) ⭐ 5,629 📅 2023-02-02 - High-performance middleware for transforming a state machine written in any programming language into a Byzantine Fault Tolerant replicated state machine using the Tendermint consensus and blockchain protocols.

**[⬆ back to top](#contents)**

## Bot Building

_Libraries for building and working with bots._

- [bot](https://github.com/go-telegram/bot) ⭐ 339 📅 2024-03-11 - Zero-dependencies Telegram Bot library with additional UI components
- [echotron](https://github.com/NicoNex/echotron) ⭐ 318 📅 2024-02-17 - An elegant and concurrent library for Telegram Bots in Go.
- [ephemeral-roles](https://github.com/ewohltman/ephemeral-roles) ⭐ 85 📅 2024-03-13 - A Discord bot for managing ephemeral roles based upon voice channel member presence.
- [go-chat-bot](https://github.com/go-chat-bot/bot) ⭐ 813 📅 2022-01-27 - IRC, Slack & Telegram bot written in Go.
- [go-joe](https://joe-bot.net) - A general-purpose bot library inspired by Hubot but written in Go.
- [go-sarah](https://github.com/oklahomer/go-sarah) ⭐ 261 📅 2023-07-03 - Framework to build a bot for desired chat services including LINE, Slack, Gitter, and more.
- [go-tg](https://github.com/mr-linch/go-tg) ⭐ 61 📅 2024-03-13 - Generated from official docs Go client library for accessing Telegram Bot API, with batteries for building complex bots included.
- [go-tgbot](https://github.com/olebedev/go-tgbot) ⭐ 118 📅 2018-06-25 - Pure Golang Telegram Bot API wrapper, generated from swagger file, session-based router, and middleware.
- [go-twitch-irc](https://github.com/gempir/go-twitch-irc) ⭐ 335 📅 2024-03-02 - Library to write bots for twitch.tv chat
- [Golang CryptoTrading Bot](https://github.com/saniales/golang-crypto-trading-bot) ⭐ 997 📅 2024-01-08 - A golang implementation of a console-based trading bot for cryptocurrency exchanges.
- [govkbot](https://github.com/nikepan/govkbot) ⭐ 47 📅 2023-10-31 - Simple Go [VK](https://vk.com) bot library.
- [hanu](https://github.com/sbstjn/hanu) ⭐ 153 📅 2018-09-04 - Framework for writing Slack bots.
- [Kelp](https://github.com/stellar/kelp) ⭐ 1,067 📅 2021-11-26 - official trading and market-making bot for the [Stellar](https://www.stellar.org/) DEX. Works out-of-the-box, written in Golang, compatible with centralized exchanges and custom trading strategies.
- [larry](https://github.com/ezeoleaf/larry) ⭐ 156 📅 2023-11-28 - Larry 🐦 is a really simple Twitter bot generator that tweets random repositories from Github built in Go.
- [margelet](https://github.com/zhulik/margelet) ⭐ 83 📅 2016-09-18 - Framework for building Telegram bots.
- [micha](https://github.com/onrik/micha) ⭐ 26 📅 2023-06-27 - Go Library for Telegram bot api.
- [olivia](https://github.com/olivia-ai/olivia) ⭐ 3,647 📅 2021-07-17 - A chatbot built with an artificial neural network.
- [slack-bot](https://github.com/innogames/slack-bot) ⭐ 162 📅 2024-03-17 - Ready to use Slack Bot for lazy developers: Custom commands, Jenkins, Jira, Bitbucket, Github...
- [slacker](https://github.com/shomali11/slacker) ⭐ 808 📅 2023-11-20 - Easy to use framework to create Slack bots.
- [slackscot](https://github.com/alexandre-normand/slackscot) ⭐ 56 📅 2021-11-22 - Another framework for building Slack bots.
- [tbot](https://github.com/yanzay/tbot) ⭐ 349 📅 2023-10-20 - Telegram bot server with API similar to net/http.
- [telebot](https://github.com/tucnak/telebot) ⭐ 3,568 📅 2024-03-18 - Telegram bot framework is written in Go.
- [telego](https://github.com/mymmrac/telego) ⭐ 353 📅 2024-03-18 - Telegram Bot API library for Golang with full one-to-one API implementation.
- [telegram-bot-api](https://github.com/Syfaro/telegram-bot-api) ⭐ 5,343 📅 2022-10-20 - Simple and clean Telegram bot client.
- [teleterm](https://github.com/alfiankan/teleterm) ⭐ 33 📅 2023-07-02 - Telegram Bot Exec Terminal Command.
- [Tenyks](https://github.com/kyleterry/tenyks) ⭐ 176 📅 2019-09-11 - Service oriented IRC bot using Redis and JSON for messaging.
- [wayback](https://github.com/wabarc/wayback) ⭐ 1,607 📅 2024-03-01 - A bot for Telegram, Mastodon, Slack, and other messaging platforms archives webpages.

**[⬆ back to top](#contents)**

## Build Automation

_Libraries and tools help with build automation._

- [1build](https://github.com/gopinath-langote/1build) ⭐ 221 📅 2021-05-16 - Command line tool to frictionlessly manage project-specific commands.
- [anko](https://github.com/GuilhermeCaruso/anko) ⭐ 36 📅 2021-03-28 - Simple application watcher for multiple programming languages.
- [gaper](https://github.com/maxcnunes/gaper) ⭐ 80 📅 2023-04-27 - Builds and restarts a Go project when it crashes or some watched file changes.
- [gilbert](https://go-gilbert.github.io) - Build system and task runner for Go projects.
- [gob](https://github.com/kcmvp/gob) ⭐ 7 📅 2024-02-19 - [Gradle](https://docs.gradle.org/)/[Maven](https://maven.apache.org/) like build tool for Go projects.
- [goyek](https://github.com/goyek/goyek) ⭐ 494 📅 2024-03-18 - Create build pipelines in Go.
- [mage](https://github.com/magefile/mage) ⭐ 3,869 📅 2023-11-18 - Mage is a make/rake-like build tool using Go.
- [mmake](https://github.com/tj/mmake) ⭐ 1,698 📅 2020-03-02 - Modern Make.
- [realize](https://github.com/tockins/realize) ⭐ 4,438 📅 2020-05-04 - Go build a system with file watchers and live to reload. Run, build and watch file changes with custom paths.
- [Task](https://github.com/go-task/task) ⭐ 9,808 📅 2024-03-21 - simple "Make" alternative.
- [taskctl](https://github.com/taskctl/taskctl) ⭐ 276 📅 2022-03-06 - Concurrent task runner.
- [xc](https://github.com/joerdav/xc) ⭐ 971 📅 2024-02-27 - Task runner with README.md defined tasks, executable markdown.

**[⬆ back to top](#contents)**

## Command Line

### Advanced Console UIs

_Libraries for building Console Applications and Console User Interfaces._

- [asciigraph](https://github.com/guptarohit/asciigraph) ⭐ 2,427 📅 2024-03-15 - Go package to make lightweight ASCII line graph ╭┈╯ in command line apps with no other dependencies.
- [aurora](https://github.com/logrusorgru/aurora) ⭐ 1,387 📅 2022-10-08 - ANSI terminal colors that support fmt.Printf/Sprintf.
- [box-cli-maker](https://github.com/Delta456/box-cli-maker) ⭐ 447 📅 2023-12-13 - Make Highly Customized Boxes for your CLI.
- [bubble-table](https://github.com/Evertras/bubble-table) ⭐ 301 📅 2024-02-25 - An interactive table component for bubbletea.
- [bubbles](https://github.com/charmbracelet/bubbles) ⭐ 4,519 📅 2024-03-14 - TUI components for bubbletea.
- [bubbletea](https://github.com/charmbracelet/bubbletea) ⭐ 23,275 📅 2024-03-19 - Go framework to build terminal apps, based on The Elm Architecture.
- [cfmt](https://github.com/mingrammer/cfmt) ⭐ 102 📅 2018-12-07 - Contextual fmt inspired by bootstrap color classes.
- [cfmt](https://github.com/i582/cfmt) ⭐ 63 📅 2021-06-24 - Simple and convenient formatted stylized output fully compatible with fmt library.
- [chalk](https://github.com/ttacon/chalk) ⭐ 442 📅 2016-06-26 - Intuitive package for prettifying terminal/console output.
- [colourize](https://github.com/TreyBastian/colourize) ⭐ 26 📅 2022-07-18 - Go library for ANSI colour text in terminals.
- [crab-config-files-templating](https://github.com/alfiankan/crab-config-files-templating) ⭐ 7 📅 2022-07-21 - Dynamic configuration file templating tool for kubernetes manifest or general configuration files.
- [ctc](https://github.com/wzshiming/ctc) ⭐ 46 📅 2020-07-15 - The non-invasive cross-platform terminal color library does not need to modify the Print method.
- [go-ataman](https://github.com/workanator/go-ataman) ⭐ 16 📅 2020-12-23 - Go library for rendering ANSI colored text templates in terminals.
- [go-colorable](https://github.com/mattn/go-colorable) ⭐ 736 📅 2023-03-22 - Colorable writer for windows.
- [go-colortext](https://github.com/daviddengcn/go-colortext) ⭐ 214 📅 2020-03-29 - Go library for color output in terminals.
- [go-isatty](https://github.com/mattn/go-isatty) ⭐ 791 📅 2023-10-17 - isatty for golang.
- [go-palette](https://github.com/abusomani/go-palette) ⭐ 14 📅 2023-03-09 - Go library that provides elegant and convenient style definitions using ANSI colors. Fully compatible & wraps the [fmt library](https://pkg.go.dev/fmt) for nice terminal layouts.
- [go-prompt](https://github.com/c-bata/go-prompt) ⭐ 5,164 📅 2021-03-03 - Library for building a powerful interactive prompt, inspired by [python-prompt-toolkit](https://github.com/jonathanslenders/python-prompt-toolkit) ⭐ 8,892 📅 2023-12-19.
- [gocui](https://github.com/jroimartin/gocui) ⭐ 9,619 📅 2021-08-14 - Minimalist Go library aimed at creating Console User Interfaces.
- [gommon/color](https://github.com/labstack/gommon/tree/master/color) - Style terminal text.
- [gookit/color](https://github.com/gookit/color) ⭐ 1,442 📅 2024-03-11 - Terminal color rendering tool library, support 16 colors, 256 colors, RGB color rendering output, compatible with Windows.
- [lipgloss](https://github.com/charmbracelet/lipgloss) ⭐ 7,096 📅 2024-03-19 - Declaratively define styles for color, format and layout in the terminal.
- [marker](https://github.com/cyucelen/marker) ⭐ 46 📅 2022-06-28 - Easiest way to match and mark strings for colorful terminal outputs.
- [mpb](https://github.com/vbauerster/mpb) ⭐ 2,209 📅 2024-01-08 - Multi progress bar for terminal applications.
- [progressbar](https://github.com/schollz/progressbar) ⭐ 3,777 📅 2024-02-26 - Basic thread-safe progress bar that works in every OS.
- [pterm](https://github.com/pterm/pterm) ⭐ 4,500 📅 2024-02-09 - A library to beautify console output on every platform with many combinable components.
- [simpletable](https://github.com/alexeyco/simpletable) ⭐ 507 📅 2021-04-02 - Simple tables in a terminal with Go.
- [spinner](https://github.com/briandowns/spinner) ⭐ 2,258 📅 2024-01-21 - Go package to easily provide a terminal spinner with options.
- [tabby](https://github.com/cheynewallace/tabby) ⭐ 345 📅 2020-12-23 - A tiny library for super simple Golang tables.
- [table](https://github.com/tomlazar/table) ⭐ 49 📅 2022-09-20 - Small library for terminal color based tables .
- [tabular](https://github.com/InVisionApp/tabular) ⭐ 76 📅 2023-05-12 - Print ASCII tables from command line utilities without the need to pass large sets of data to the API.
- [termbox-go](https://github.com/nsf/termbox-go) ⭐ 4,630 📅 2022-02-08 - Termbox is a library for creating cross-platform text-based interfaces.
- [termdash](https://github.com/mum4k/termdash) ⭐ 2,558 📅 2024-03-10 - Go terminal dashboard based on **termbox-go** and inspired by [termui](https://github.com/gizak/termui) ⭐ 12,888 📅 2024-01-30 ⭐ 12,888 📅 2024-01-30.
- [termenv](https://github.com/muesli/termenv) ⭐ 1,613 📅 2024-01-25 - Advanced ANSI style & color support for your terminal applications.
- [termui](https://github.com/gizak/termui) ⭐ 12,888 📅 2024-01-30 ⭐ 12,888 📅 2024-01-30 - Go terminal dashboard based on **termbox-go** and inspired by [blessed-contrib](https://github.com/yaronn/blessed-contrib) ⭐ 15,367 📅 2022-02-17.
- [uilive](https://github.com/gosuri/uilive) ⭐ 1,656 📅 2020-01-03 - Library for updating terminal output in real time.
- [uiprogress](https://github.com/gosuri/uiprogress) ⭐ 2,066 📅 2021-03-17 - Flexible library to render progress bars in terminal applications.
- [uitable](https://github.com/gosuri/uitable) ⭐ 724 📅 2022-08-26 - Library to improve readability in terminal apps using tabular data.
- [yacspin](https://github.com/theckman/yacspin) ⭐ 430 📅 2022-01-03 - Yet Another CLi Spinner package, for working with terminal spinners.

**[⬆ back to top](#contents)**

### Standard CLI

_Libraries for building standard or basic Command Line applications._

- [acmd](https://github.com/cristalhq/acmd) ⭐ 108 📅 2024-03-08 - Simple, useful, and opinionated CLI package in Go.
- [argparse](https://github.com/akamensky/argparse) ⭐ 586 📅 2022-08-11 - Command line argument parser inspired by Python's argparse module.
- [argv](https://github.com/cosiner/argv) ⭐ 40 📅 2020-04-16 - Go library to split command line string as arguments array using the bash syntax.
- [carapace](https://github.com/rsteube/carapace) ⭐ 178 📅 2024-03-12 - Command argument completion generator for spf13/cobra.
- [carapace-bin](https://github.com/rsteube/carapace-bin) ⭐ 588 📅 2024-03-20 - Multi-shell multi-command argument completer.
- [carapace-spec](https://github.com/rsteube/carapace-spec) ⭐ 15 📅 2024-03-12 - Define simple completions using a spec file.
- [cli](https://github.com/mkideal/cli) ⭐ 716 📅 2023-03-07 - Feature-rich and easy to use command-line package based on golang struct tags.
- [cli](https://github.com/teris-io/cli) ⭐ 126 📅 2021-05-09 - Simple and complete API for building command line interfaces in Go.
- [climax](https://github.com/tucnak/climax) ⭐ 214 📅 2020-09-05 - Alternative CLI with "human face", in spirit of Go command.
- [clîr](https://github.com/leaanthony/clir) ⭐ 166 📅 2023-01-25 - A Simple and Clear CLI library. Dependency free.
- [cmd](https://github.com/posener/cmd) ⭐ 41 📅 2020-09-27 - Extends the standard `flag` package to support sub commands and more in idiomatic way.
- [cmdr](https://github.com/hedzr/cmdr) ⭐ 129 📅 2023-12-20 - A POSIX/GNU style, getopt-like command-line UI Go library.
- [cobra](https://github.com/spf13/cobra) ⭐ 35,587 📅 2024-03-12 - Commander for modern Go CLI interactions.
- [command-chain](https://github.com/rainu/go-command-chain) ⭐ 57 📅 2023-05-03 - A go library for configure and run command chains - such as pipelining in unix shells.
- [commandeer](https://github.com/jaffee/commandeer) ⭐ 172 📅 2022-09-20 - Dev-friendly CLI apps: sets up flags, defaults, and usage based on struct fields and tags.
- [complete](https://github.com/posener/complete) ⭐ 910 📅 2020-12-08 - Write bash completions in Go + Go command bash completion.
- [Dnote](https://github.com/dnote/dnote) ⭐ 2,658 📅 2024-02-03 - A simple command line notebook with multi-device sync.
- [elvish](https://github.com/elves/elvish) ⭐ 5,286 📅 2024-03-20 - An expressive programming language and a versatile interactive shell.
- [env](https://github.com/codingconcepts/env) ⭐ 109 📅 2020-08-21 - Tag-based environment configuration for structs.
- [flag](https://github.com/cosiner/flag) ⭐ 130 📅 2020-12-27 - Simple but powerful command line option parsing library for Go supporting subcommand.
- [flaggy](https://github.com/integrii/flaggy) ⭐ 846 📅 2022-05-28 - A robust and idiomatic flags package with excellent subcommand support.
- [flagvar](https://github.com/sgreben/flagvar) ⭐ 43 📅 2020-07-11 - A collection of flag argument types for Go's standard `flag` package.
- [go-andotp](https://github.com/grijul/go-andotp) ⭐ 27 📅 2023-04-02 - A CLI program to encrypt/decrypt [andOTP](https://github.com/andOTP/andOTP) ⭐ 3,743 📅 2022-06-14 files. Can be used as a library as well.
- [go-arg](https://github.com/alexflint/go-arg) ⭐ 1,846 📅 2023-10-10 - Struct-based argument parsing in Go.
- [go-commander](https://github.com/yitsushi/go-commander) ⭐ 35 📅 2020-05-24 - Go library to simplify CLI workflow.
- [go-flags](https://github.com/jessevdk/go-flags) ⭐ 2,496 📅 2021-06-07 - go command line option parser.
- [go-getoptions](https://github.com/DavidGamba/go-getoptions) ⭐ 55 📅 2024-02-22 - Go option parser inspired by the flexibility of Perl’s GetOpt::Long.
- [gocmd](https://github.com/devfacet/gocmd) ⭐ 66 📅 2023-04-04 - Go library for building command line applications.
- [hiboot cli](https://github.com/hidevopsio/hiboot/tree/master/pkg/app/cli) - cli application framework with auto configuration and dependency injection.
- [job](https://github.com/liujianping/job) ⭐ 140 📅 2020-06-30 - JOB, make your short-term command as a long-term job.
- [kingpin](https://github.com/alecthomas/kingpin) ⭐ 3,424 📅 2024-02-12 - Command line and flag parser supporting sub commands (superseded by `kong`; see below).
- [liner](https://github.com/peterh/liner) ⭐ 1,031 📅 2021-11-19 - Go readline-like library for command-line interfaces.
- [mcli](https://github.com/jxskiss/mcli) ⭐ 24 📅 2024-01-23 - A minimal but very powerful cli library for Go.
- [mitchellh/cli](https://github.com/mitchellh/cli) ⭐ 1,718 📅 2022-09-30 - Go library for implementing command-line interfaces.
- [mow.cli](https://github.com/jawher/mow.cli) - Go library for building CLI applications with sophisticated flag and argument parsing and validation.
- [ops](https://github.com/nanovms/ops) ⭐ 1,184 📅 2024-03-17 - Unikernel Builder/Orchestrator.
- [pflag](https://github.com/spf13/pflag) ⭐ 2,292 📅 2021-06-04 - Drop-in replacement for Go's flag package, implementing POSIX/GNU-style --flags.
- [readline](https://github.com/reeflective/readline) ⭐ 69 📅 2024-01-30 Shell library with modern and easy to use UI features.
- [sand](https://github.com/Zaba505/sand) ⭐ 24 📅 2018-11-21 - Simple API for creating interpreters and so much more.
- [sflags](https://github.com/octago/sflags) ⭐ 148 📅 2021-07-26 - Struct based flags generator for flag, urfave/cli, pflag, cobra, kingpin, and other libraries.
- [strumt](https://github.com/antham/strumt) ⭐ 57 📅 2023-02-27 - Library to create prompt chain.
- [subcmd](https://github.com/bobg/subcmd) ⭐ 8 📅 2023-11-27 - Another approach to parsing and running subcommands. Works alongside the standard `flag` package.
- [survey](https://github.com/go-survey/survey) ⭐ 4,018 📅 2023-09-24 - Build interactive and accessible prompts with full support for windows and posix terminals.
- [ts](https://github.com/liujianping/ts) ⭐ 20 📅 2019-07-02 - Timestamp convert & compare tool.
- [ukautz/clif](https://github.com/ukautz/clif) ⭐ 124 📅 2019-02-18 - Small command line interface framework.
- [urfave/cli](https://github.com/urfave/cli) ⭐ 21,470 📅 2024-03-15 - Simple, fast, and fun package for building command line apps in Go (formerly codegangsta/cli).
- [version](https://github.com/mszostok/version) ⭐ 87 📅 2023-05-06 - Collects and displays CLI version information in multiple formats along with upgrade notice.
- [wlog](https://github.com/dixonwille/wlog) ⭐ 64 📅 2024-03-05 - Simple logging interface that supports cross-platform color and concurrency.
- [wmenu](https://github.com/dixonwille/wmenu) ⭐ 211 📅 2024-03-05 - Easy to use menu structure for cli applications that prompt users to make choices.

**[⬆ back to top](#contents)**

## Configuration

_Libraries for configuration parsing._

- [aconfig](https://github.com/cristalhq/aconfig) ⭐ 515 📅 2024-03-08 - Simple, useful and opinionated config loader.
- [cleanenv](https://github.com/ilyakaznacheev/cleanenv) ⭐ 1,400 📅 2023-09-04 - Minimalistic configuration reader (from files, ENV, and wherever you want).
- [config](https://github.com/JeremyLoy/config) ⭐ 335 📅 2021-11-18 - Cloud native application configuration. Bind ENV to structs in only two lines.
- [config](https://github.com/num30/config) ⭐ 46 📅 2023-12-01 - configure you app using file, environment variables, or flags in two lines of code
- [config](https://github.com/olebedev/config) ⭐ 268 📅 2022-08-22 - JSON or YAML configuration wrapper with environment variables and flags parsing.
- [configuration](https://github.com/BoRuDar/configuration) ⭐ 92 📅 2024-03-11 - Library for initializing configuration structs from env variables, files, flags and 'default' tag.
- [configure](https://github.com/paked/configure) ⭐ 56 📅 2019-02-18 - Provides configuration through multiple sources, including JSON, flags and environment variables.
- [configuro](https://github.com/sherifabdlnaby/configuro) ⭐ 92 📅 2022-09-25 - opinionated configuration loading & validation framework from ENV and Files focused towards 12-Factor compliant applications.
- [confita](https://github.com/heetch/confita) ⭐ 485 📅 2021-06-23 - Load configuration in cascade from multiple backends into a struct.
- [conflate](https://github.com/the4thamigo-uk/conflate) ⭐ 32 📅 2023-07-26 - Library/tool to merge multiple JSON/YAML/TOML files from arbitrary URLs, validation against a JSON schema, and application of default values defined in the schema.
- [env](https://github.com/caarlos0/env) ⭐ 4,264 📅 2024-03-16 - Parse environment variables to Go structs (with defaults).
- [env](https://github.com/junk1tm/env) ⭐ 49 📅 2024-03-14 - A lightweight package for loading environment variables into structs.
- [envcfg](https://github.com/tomazk/envcfg) ⭐ 103 📅 2017-06-19 - Un-marshaling environment variables to Go structs.
- [envconf](https://github.com/ian-kent/envconf) ⭐ 11 📅 2014-10-26 - Configuration from environment.
- [envconfig](https://github.com/vrischmann/envconfig) ⭐ 236 📅 2020-12-28 - Read your configuration from environment variables.
- [envh](https://github.com/antham/envh) ⭐ 98 📅 2024-03-04 - Helpers to manage environment variables.
- [fig](https://github.com/kkyr/fig) ⭐ 343 📅 2023-12-12 - Tiny library for reading configuration from a file and from environment variables (with validation & defaults).
- [gcfg](https://github.com/go-gcfg/gcfg) ⭐ 166 📅 2020-07-13 - read INI-style configuration files into Go structs; supports user-defined types and subsections.
- [genv](https://github.com/sakirsensoy/genv) ⭐ 36 📅 2019-07-27 - Read environment variables easily with dotenv support.
- [go-aws-ssm](https://github.com/PaddleHQ/go-aws-ssm) ⭐ 54 📅 2023-12-08 - Go package that fetches parameters from AWS System Manager - Parameter Store.
- [go-conf](https://github.com/ThomasObenaus/go-conf) ⭐ 11 📅 2021-10-19 - Simple library for application configuration based on annotated structs. It supports reading the configuration from environment variables, config files and command line parameters.
- [go-ini](https://github.com/subpop/go-ini) ⭐ 11 📅 2024-02-28 - A Go package that marshals and unmarshals INI-files.
- [go-ssm-config](https://github.com/ianlopshire/go-ssm-config) ⭐ 19 📅 2023-09-29 - Go utility for loading configuration parameters from AWS SSM (Parameter Store).
- [go-up](https://github.com/ufoscout/go-up) ⭐ 43 📅 2020-01-14 - A simple configuration library with recursive placeholders resolution and no magic.
- [goConfig](https://github.com/crgimenes/goConfig) ⭐ 3 📅 2023-08-09 - Parses a struct as input and populates the fields of this struct with parameters from command line, environment variables and configuration file.
- [godotenv](https://github.com/joho/godotenv) ⭐ 7,382 📅 2024-01-13 - Go port of Ruby's dotenv library (Loads environment variables from `.env`).
- [gofigure](https://github.com/ian-kent/gofigure) ⭐ 67 📅 2017-05-02 - Go application configuration made easy.
- [GoLobby/Config](https://github.com/golobby/config) ⭐ 357 📅 2023-01-05 - GoLobby Config is a lightweight yet powerful configuration manager for the Go programming language.
- [gone/jconf](https://github.com/One-com/gone/tree/master/jconf) - Modular JSON configuration. Keep you config structs along with the code they configure and delegate parsing to submodules without sacrificing full config serialization.
- [gonfig](https://github.com/milad-abbasi/gonfig) ⭐ 7 📅 2021-08-02 - Tag-based configuration parser which loads values from different providers into typesafe struct.
- [gookit/config](https://github.com/gookit/config) ⭐ 519 📅 2024-03-09 - application config manage(load,get,set). support JSON, YAML, TOML, INI, HCL. multi file load, data override merge.
- [harvester](https://github.com/beatlabs/harvester) ⭐ 130 📅 2024-03-11 - Harvester, a easy to use static and dynamic configuration package supporting seeding, env vars and Consul integration.
- [hjson](https://github.com/hjson/hjson-go) ⭐ 317 📅 2023-12-07 - Human JSON, a configuration file format for humans. Relaxed syntax, fewer mistakes, more comments.
- [hocon](https://github.com/gurkankaymak/hocon) ⭐ 70 📅 2023-12-24 - Configuration library for working with the HOCON(a human-friendly JSON superset) format, supports features like environment variables, referencing other values, comments and multiple files.
- [ingo](https://github.com/schachmat/ingo) ⭐ 36 📅 2017-04-03 - Flags persisted in an ini-like config file.
- [ini](https://github.com/go-ini/ini) ⭐ 3,395 📅 2022-08-08 - Go package to read and write INI files.
- [ini](https://github.com/wlevene/ini) ⭐ 14 📅 2023-07-14 - INI Parser & Write Library, Unmarshal to Struct,Marshal to Json,Write File,watch file.
- [joshbetz/config](https://github.com/joshbetz/config) ⭐ 216 📅 2019-10-25 - Small configuration library for Go that parses environment variables, JSON files, and reloads automatically on SIGHUP.
- [kelseyhightower/envconfig](https://github.com/kelseyhightower/envconfig) ⭐ 4,865 📅 2019-07-23 - Go library for managing configuration data from environment variables.
- [koanf](https://github.com/knadh/koanf) ⭐ 2,289 📅 2024-03-07 - Light weight, extensible library for reading config in Go applications. Built in support for JSON, TOML, YAML, env, command line.
- [konf](https://github.com/nil-go/konf) ⭐ 68 📅 2024-03-20 - The simplest API for reading/watching config from file, env, flag and clouds (e.g. AWS, Azure, GCP).
- [konfig](https://github.com/lalamove/konfig) ⭐ 648 📅 2020-05-13 - Composable, observable and performant config handling for Go for the distributed processing era.
- [kong](https://github.com/alecthomas/kong) ⭐ 1,780 📅 2024-03-14 - Command-line parser with support for arbitrarily complex command-line structures and additional sources of configuration such as YAML, JSON, TOML, etc (successor to `kingpin`).
- [mini](https://github.com/sasbury/mini) ⭐ 35 📅 2018-12-26 - Golang package for parsing ini-style configuration files.
- [nasermirzaei89/env](https://github.com/nasermirzaei89/env) ⭐ 16 📅 2024-02-24 - Simple useful package for read environment variables.
- [nfigure](https://github.com/muir/nfigure) ⭐ 7 📅 2024-03-14 - Per-library struct-tag based configuration from command lines (Posix & Go-style); environment, JSON, YAML
- [onion](https://github.com/goraz/onion) ⭐ 115 📅 2021-08-22 - Layer based configuration for Go, Supports JSON, TOML, YAML, properties, etcd, env, and encryption using PGP.
- [piper](https://github.com/Yiling-J/piper) ⭐ 7 📅 2021-12-03 - Viper wrapper with config inheritance and key generation.
- [store](https://github.com/tucnak/store) ⭐ 276 📅 2017-09-05 - Lightweight configuration manager for Go.
- [swap](https://github.com/oblq/swap) ⭐ 8 📅 2021-02-25 - Instantiate/configure structs recursively, based on build environment. (YAML, TOML, JSON and env).
- [typenv](https://github.com/diegomarangoni/typenv) ⭐ 9 📅 2020-07-22 - Minimalistic, zero dependency, typed environment variables library.
- [uConfig](https://github.com/omeid/uconfig) ⭐ 70 📅 2024-03-15 - Lightweight, zero-dependency, and extendable configuration management.
- [viper](https://github.com/spf13/viper) ⭐ 25,501 📅 2024-02-21 - Go configuration with fangs.
- [xdg](https://github.com/adrg/xdg) ⭐ 555 📅 2024-03-21 - Go implementation of the [XDG Base Directory Specification](https://specifications.freedesktop.org/basedir-spec/basedir-spec-latest.html) and [XDG user directories](https://wiki.archlinux.org/index.php/XDG_user_directories).
- [xdg](https://github.com/OpenPeeDeeP/xdg) ⭐ 80 📅 2020-10-19 - Cross platform package that follows the [XDG Standard](https://standards.freedesktop.org/basedir-spec/basedir-spec-latest.html).

**[⬆ back to top](#contents)**

## Continuous Integration

_Tools for help with continuous integration._

- [CDS](https://github.com/ovh/cds) ⭐ 4,407 📅 2024-03-20 - Enterprise-Grade CI/CD and DevOps Automation Open Source Platform.
- [dot](https://github.com/opnlabs/dot) ⭐ 7 📅 2024-03-20 - A minimal, local first continuous integration system that uses Docker to run jobs concurrently in stages. 
- [drone](https://github.com/drone/drone) ⭐ 31,277 📅 2024-03-22 - Drone is a Continuous Integration platform built on Docker, written in Go.
- [duci](https://github.com/duck8823/duci) ⭐ 74 📅 2023-02-27 - A simple ci server no needs domain specific languages.
- [go-fuzz-action](https://github.com/jidicula/go-fuzz-action) ⭐ 11 📅 2024-03-09 - Use Go 1.18's built-in fuzz testing in GitHub Actions.
- [go-test-coverage](https://github.com/vladopajic/go-test-coverage) ⭐ 44 📅 2024-03-21 - Tool and GitHub action which reports issues when test coverage is below set threshold.
- [gomason](https://github.com/nikogura/gomason) ⭐ 62 📅 2023-09-15 - Test, Build, Sign, and Publish your go binaries from a clean workspace.
- [gotestfmt](https://github.com/GoTestTools/gotestfmt) ⭐ 459 📅 2023-06-05 - go test output for humans.
- [goveralls](https://github.com/mattn/goveralls) ⭐ 779 📅 2023-04-26 - Go integration for Coveralls.io continuous code coverage tracking system.
- [overalls](https://github.com/go-playground/overalls) ⭐ 114 📅 2019-12-18 - Multi-Package go project coverprofile for tools like goveralls.
- [roveralls](https://github.com/LawrenceWoodman/roveralls) ⭐ 20 📅 2017-11-19 - Recursive coverage testing tool.
- [woodpecker](https://github.com/woodpecker-ci/woodpecker) ⭐ 3,583 📅 2024-03-21 - Woodpecker is a community fork of the Drone CI system.

**[⬆ back to top](#contents)**

## CSS Preprocessors

_Libraries for preprocessing CSS files._

- [gcss](https://github.com/yosssi/gcss) ⭐ 491 📅 2014-10-12 - Pure Go CSS Preprocessor.
- [go-libsass](https://github.com/wellington/go-libsass) ⭐ 203 📅 2023-02-26 - Go wrapper to the 100% Sass compatible libsass project.

**[⬆ back to top](#contents)**

## Data Structures and Algorithms

### Bit-packing and Compression

- [bingo](https://github.com/iancmcc/bingo) ⭐ 32 📅 2024-03-13 - Fast, zero-allocation, lexicographical-order-preserving packing of native types to bytes.
- [binpacker](https://github.com/zhuangsirui/binpacker) ⭐ 218 📅 2021-07-13 - Binary packer and unpacker helps user build custom binary stream.
- [bit](https://github.com/yourbasic/bit) ⭐ 155 📅 2018-03-13 - Golang set data structure with bonus bit-twiddling functions.
- [crunch](https://github.com/superwhiskers/crunch) ⭐ 90 📅 2023-01-14 - Go package implementing buffers for handling various datatypes easily.
- [go-ef](https://github.com/amallia/go-ef) ⭐ 31 📅 2017-09-25 - A Go implementation of the Elias-Fano encoding.
- [roaring](https://github.com/RoaringBitmap/roaring) ⭐ 2,326 📅 2024-03-22 - Go package implementing compressed bitsets.

### Bit Sets

- [bitmap](https://github.com/kelindar/bitmap) ⭐ 271 📅 2023-11-06 - Dense, zero-allocation, SIMD-enabled bitmap/bitset in Go.
- [bitset](https://github.com/bits-and-blooms/bitset) ⭐ 1,249 📅 2023-12-25 - Go package implementing bitsets.

### Bloom and Cuckoo Filters

- [bloom](https://github.com/bits-and-blooms/bloom) ⭐ 2,256 📅 2024-03-16 - Go package implementing Bloom filters.
- [bloom](https://github.com/zhenjl/bloom) ⭐ 148 📅 2015-10-26 - Bloom filters implemented in Go.
- [bloom](https://github.com/yourbasic/bloom) ⭐ 84 📅 2017-06-02 - Golang Bloom filter implementation.
- [bloomfilter](https://github.com/OldPanda/bloomfilter) ⭐ 16 📅 2023-02-16 - Yet another Bloomfilter implementation in Go, compatible with Java's Guava library.
- [boomfilters](https://github.com/tylertreat/BoomFilters) ⭐ 1,576 📅 2021-03-15 - Probabilistic data structures for processing continuous, unbounded streams.
- [cuckoo-filter](https://github.com/linvon/cuckoo-filter) ⭐ 276 📅 2021-10-09 - Cuckoo filter: a comprehensive cuckoo filter, which is configurable and space optimized compared with other implements, and all features mentioned in original paper is available.
- [cuckoofilter](https://github.com/seiflotfy/cuckoofilter) ⭐ 1,054 📅 2022-04-11 - Cuckoo filter: a good alternative to a counting bloom filter implemented in Go.
- [ring](https://github.com/TheTannerRyan/ring) ⭐ 137 📅 2020-09-05 - Go implementation of a high performance, thread safe bloom filter.

### Data Structure and Algorithm Collections

- [algorithms](https://github.com/shady831213/algorithms) ⭐ 765 📅 2019-04-03 - Algorithms and data structures.CLRS study.
- [go-datastructures](https://github.com/Workiva/go-datastructures) ⭐ 7,291 📅 2023-09-13 - Collection of useful, performant, and thread-safe data structures.
- [gods](https://github.com/emirpasic/gods) ⭐ 15,246 📅 2024-01-07 - Go Data Structures. Containers, Sets, Lists, Stacks, Maps, BidiMaps, Trees, HashSet etc.
- [gostl](https://github.com/liyue201/gostl) ⭐ 978 📅 2023-09-06 - Data structure and algorithm library for go, designed to provide functions similar to C++ STL.

### Iterators

- [goterator](https://github.com/yaa110/goterator) ⭐ 16 📅 2020-12-02 - Iterator implementation to provide map and reduce functionalities.
- [iter](https://github.com/disksing/iter) ⭐ 186 📅 2022-03-16 - Go implementation of C++ STL iterators and algorithms.

### Maps

See also [Database](#database) for more complex key-value stores, and [Trees](#trees) for
additional ordered map implementations.

- [cmap](https://github.com/lrita/cmap) ⭐ 87 📅 2023-11-08 - a thread-safe concurrent map for go, support using `interface{}` as key and auto scale up shards.
- [dict](https://github.com/srfrog/dict) ⭐ 44 📅 2020-10-25 - Python-like dictionaries (dict) for Go.
- [goradd/maps](https://github.com/goradd/maps) ⭐ 34 📅 2023-09-16 - Go 1.18+ generic map interface for maps; safe maps; ordered maps; ordered, safe maps; etc.

### Miscellaneous Data Structures and Algorithms

- [concurrent-writer](https://github.com/free/concurrent-writer) ⭐ 54 📅 2017-11-17 - Highly concurrent drop-in replacement for `bufio.Writer`.
- [conjungo](https://github.com/InVisionApp/conjungo) ⭐ 124 📅 2023-05-08 - A small, powerful and flexible merge library.
- [count-min-log](https://github.com/seiflotfy/count-min-log) ⭐ 66 📅 2017-02-12 - Go implementation Count-Min-Log sketch: Approximately counting with approximate counters (Like Count-Min sketch but using less memory).
- [fsm](https://github.com/cocoonspace/fsm) ⭐ 58 📅 2021-10-12 - Finite-State Machine package.
- [genfuncs](https://github.com/nwillc/genfuncs) ⭐ 48 📅 2022-08-07 - Go 1.18+ generics package inspired by Kotlin's Sequence and Map.
- [go-generics](https://github.com/bobg/go-generics) ⭐ 54 📅 2024-02-09 - Generic slice, map, set, iterator, and goroutine utilities.
- [go-geoindex](https://github.com/hailocab/go-geoindex) ⭐ 354 📅 2016-01-27 - In-memory geo index.
- [go-rampart](https://github.com/francesconi/go-rampart) ⭐ 95 📅 2022-06-16 - Determine how intervals relate to each other.
- [go-rquad](https://github.com/aurelien-rainone/go-rquad) ⭐ 129 📅 2022-06-22 - Region quadtrees with efficient point location and neighbour finding.
- [go-tuple](https://github.com/barweiss/go-tuple) ⭐ 74 📅 2023-09-01 - Generic tuple implementation for Go 1.18+.
- [go18ds](https://github.com/daichi-m/go18ds) ⭐ 42 📅 2022-03-22 - Go Data Structures using Go 1.18 generics.
- [gofal](https://github.com/xxjwxc/gofal) ⭐ 18 📅 2019-10-08 - fractional api for Go.
- [gogu](https://github.com/esimov/gogu) ⭐ 93 📅 2023-03-04 - A comprehensive, reusable and efficient concurrent-safe generics utility functions and data structures library.
- [gota](https://github.com/kniren/gota) ⭐ 2,894 📅 2021-10-10 - Implementation of dataframes, series, and data wrangling methods for Go.
- [hide](https://github.com/emvi/hide) ⭐ 59 📅 2021-11-09 - ID type with marshalling to/from hash to prevent sending IDs to clients.
- [hilbert](https://github.com/google/hilbert) ⭐ 274 📅 2018-11-22 - Go package for mapping values to and from space-filling curves, such as Hilbert and Peano curves.
- [hyperloglog](https://github.com/axiomhq/hyperloglog) ⭐ 905 📅 2024-03-19 - HyperLogLog implementation with Sparse, LogLog-Beta bias correction and TailCut space reduction.
- [plinko](https://github.com/shipt/plinko) ⭐ 170 📅 2023-07-13 - A finite state machine and workflow orchestrator that compiles for fast execution, easy debugging, auto-generated documentation. Includes advanced features such as side-effect hooks. 
- [quadtree](https://github.com/s0rg/quadtree) ⭐ 33 📅 2023-08-02 - Generic, zero-alloc, 100%-test covered quadtree.
- [slices](https://github.com/srfrog/slices) ⭐ 16 📅 2020-11-09 - Functions that operate on slices; like `package strings` but adapted to work with slices.
- [slices](https://github.com/twharmon/slices) ⭐ 15 📅 2022-07-08 - Pure, generic functions for slices.

### Nullable Types

- [nan](https://github.com/kak-tus/nan) ⭐ 84 📅 2023-07-06 - Zero allocation Nullable structures in one library with handy conversion functions, marshallers and unmarshallers.
- [null](https://github.com/emvi/null) ⭐ 35 📅 2021-11-09 - Nullable Go types that can be marshalled/unmarshalled to/from JSON.
- [typ](https://github.com/gurukami/typ) ⭐ 45 📅 2021-10-15 - Null Types, Safe primitive type conversion and fetching value from complex structures.

### Queues

- [deque](https://github.com/edwingeng/deque) ⭐ 175 📅 2023-09-14 - A highly optimized double-ended queue.
- [deque](https://github.com/gammazero/deque) ⭐ 532 📅 2022-10-19 - Fast ring-buffer deque (double-ended queue).
- [goconcurrentqueue](https://github.com/enriquebris/goconcurrentqueue) ⭐ 352 📅 2022-11-17 - Concurrent FIFO queue.
- [memlog](https://github.com/embano1/memlog) ⭐ 111 📅 2024-02-20 - An easy to use, lightweight, thread-safe and append-only in-memory data structure inspired by Apache Kafka.
- [queue](https://github.com/adrianbrad/queue) ⭐ 235 📅 2024-03-11 - Multiple thread-safe, generic queue implementations for Go.

### Sets

- [dsu](https://github.com/ihebu/dsu) ⭐ 14 📅 2022-01-29 - Disjoint Set data structure implementation in Go.
- [golang-set](https://github.com/deckarep/golang-set) ⭐ 3,871 📅 2023-12-26 - Thread-Safe and Non-Thread-Safe high-performance sets for Go.
- [goset](https://github.com/zoumo/goset) ⭐ 52 📅 2020-12-11 - A useful Set collection implementation for Go.
- [set](https://github.com/StudioSol/set) ⭐ 26 📅 2022-09-08 - Simple set data structure implementation in Go using LinkedHashMap.

### Text Analysis

- [bleve](https://github.com/blevesearch/bleve) ⭐ 9,551 📅 2024-03-21 - Modern text indexing library for go.
- [go-adaptive-radix-tree](https://github.com/plar/go-adaptive-radix-tree) ⭐ 332 📅 2023-01-12 - Go implementation of Adaptive Radix Tree.
- [go-edlib](https://github.com/hbollon/go-edlib) ⭐ 443 📅 2022-07-03 - Go string comparison and edit distance algorithms library (Levenshtein, LCS, Hamming, Damerau levenshtein, Jaro-Winkler, etc.) compatible with Unicode.
- [levenshtein](https://github.com/agext/levenshtein) ⭐ 84 📅 2020-10-15 - Levenshtein distance and similarity metrics with customizable edit costs and Winkler-like bonus for common prefix.
- [levenshtein](https://github.com/agnivade/levenshtein) ⭐ 324 📅 2023-02-02 - Implementation to calculate levenshtein distance in Go.
- [mspm](https://github.com/BlackRabbitt/mspm) ⭐ 24 📅 2018-05-19 - Multi-String Pattern Matching Algorithm for information retrieval.
- [parsefields](https://github.com/MonaxGT/parsefields) ⭐ 8 📅 2019-05-05 - Tools for parse JSON-like logs for collecting unique fields and events.
- [ptrie](https://github.com/viant/ptrie) ⭐ 37 📅 2024-03-09 - An implementation of prefix tree.
- [trie](https://github.com/derekparker/trie) ⭐ 722 📅 2023-09-29 - Trie implementation in Go.

### Trees

- [hashsplit](http://github.com/bobg/hashsplit) ⭐ 28 📅 2021-08-19 - Split byte streams into chunks, and arrange chunks into trees, with boundaries determined by content, not position.
- [merkle](https://github.com/bobg/merkle) ⭐ 14 📅 2022-05-08 - Space-efficient computation of Merkle root hashes and inclusion proofs.
- [skiplist](https://github.com/MauriceGit/skiplist) ⭐ 271 📅 2021-11-05 - Very fast Go Skiplist implementation.
- [skiplist](https://github.com/gansidui/skiplist) ⭐ 83 📅 2014-11-21 - Skiplist implementation in Go.
- [treap](https://github.com/perdata/treap) ⭐ 26 📅 2019-12-18 - Persistent, fast ordered map using tree heaps.
- [treemap](https://github.com/igrmk/treemap) ⭐ 54 📅 2022-03-22 - Generic key-sorted map using a red-black tree under the hood.

### Pipes

- [ordered-concurrently](https://github.com/tejzpr/ordered-concurrently) ⭐ 36 📅 2023-04-24 - Go module that processes work concurrently and returns output in a channel in the order of input.
- [parapipe](https://github.com/nazar256/parapipe) ⭐ 27 📅 2021-06-07 - FIFO Pipeline which parallels execution on each stage while maintaining the order of messages and results.
- [pipeline](https://github.com/hyfather/pipeline) ⭐ 55 📅 2018-08-31 - An implementation of pipelines with fan-in and fan-out.

**[⬆ back to top](#contents)**

## Database

### Caches

_Data stores with expiring records, in-memory distributed data stores, or in-memory subsets of file-based databases._

- [2q](https://github.com/floatdrop/2q) ⭐ 38 📅 2022-03-30 - 2Q in-memory cache implementation.
- [bcache](https://github.com/iwanbk/bcache) ⭐ 144 📅 2019-04-30 - Eventually consistent distributed in-memory cache Go library.
- [BigCache](https://github.com/allegro/bigcache) ⭐ 7,143 📅 2024-02-29 - Efficient key/value cache for gigabytes of data.
- [cache](https://github.com/akyoto/cache) ⭐ 169 📅 2022-08-10 - In-memory key:value store with expiration time, 0 dependencies, <100 LoC, 100% coverage.
- [cache2go](https://github.com/muesli/cache2go) ⭐ 2,049 📅 2022-10-11 - In-memory key:value cache which supports automatic invalidation based on timeouts.
- [cachego](https://github.com/faabiosr/cachego) ⭐ 348 📅 2023-06-23 - Golang Cache component for multiple drivers.
- [clusteredBigCache](https://github.com/oaStuff/clusteredBigCache) ⭐ 44 📅 2018-01-22 - BigCache with clustering support and individual item expiration.
- [coherence-go-client](https://github.com/oracle/coherence-go-client) ⭐ 7 📅 2024-03-15 - Full implementation of Oracle Coherence cache API for Go applications using gRPC as network transport.
- [couchcache](https://github.com/codingsince1985/couchcache) ⭐ 60 📅 2022-12-17 - RESTful caching micro-service backed by Couchbase server.
- [fastcache](https://github.com/VictoriaMetrics/fastcache) ⭐ 1,961 📅 2023-11-24 - fast thread-safe inmemory cache for big number of entries. Minimizes GC overhead.
- [GCache](https://github.com/bluele/gcache) ⭐ 2,520 📅 2022-01-05 - Cache library with support for expirable Cache, LFU, LRU and ARC.
- [gdcache](https://github.com/ulovecode/gdcache) ⭐ 12 📅 2021-10-14 - A pure non-intrusive cache library implemented by golang, you can use it to implement your own distributed cache.
- [go-cache](https://github.com/viney-shih/go-cache) ⭐ 124 📅 2023-01-26 - A flexible multi-layer Go caching library to deal with in-memory and shared cache by adopting Cache-Aside pattern.
- [go-freelru](https://github.com/elastic/go-freelru) ⭐ 89 📅 2024-03-20 A GC-less, fast and generic LRU hashmap library with optional locking, sharding, eviction and expiration.
- [go-mcache](https://github.com/OrlovEvgeny/go-mcache) ⭐ 93 📅 2020-01-21 - Fast in-memory key:value store/cache library. Pointer caches.
- [gocache](https://github.com/eko/gocache) ⭐ 2,183 📅 2024-03-16 - A complete Go cache library with multiple stores (memory, memcache, redis, ...), chainable, loadable, metrics cache and more.
- [gocache](https://github.com/yuseferi/gocache) ⭐ 5 📅 2023-12-20 - A data race free Go ache library with high performance and auto pruge functionality
- [groupcache](https://github.com/golang/groupcache) ⭐ 12,665 📅 2021-03-31 - Groupcache is a caching and cache-filling library, intended as a replacement for memcached in many cases.
- [imcache](https://github.com/erni27/imcache) ⭐ 113 📅 2024-01-17 - A generic in-memory cache Go library. It supports expiration, sliding expiration, max entries limit, eviction callbacks and sharding.
- [nscache](https://github.com/no-src/nscache) ⭐ 9 📅 2024-03-14 - A Go caching framework that supports multiple data source drivers.
- [otter](https://github.com/maypok86/otter) ⭐ 1,104 📅 2024-03-12 - A high performance lockless cache for Go. Many times faster than Ristretto and friends.
- [remember-go](https://github.com/rocketlaunchr/remember-go) ⭐ 137 📅 2021-04-19 - A universal interface for caching slow database queries (backed by redis, memcached, ristretto, or in-memory).
- [theine](https://github.com/Yiling-J/theine-go) ⭐ 213 📅 2024-02-27 - High performance, near optimal in-memory cache with proactive TTL expiration and generics.
- [timedmap](https://github.com/zekroTJA/timedmap) ⭐ 69 📅 2023-11-29 - Map with expiring key-value pairs.
- [ttlcache](https://github.com/jellydator/ttlcache) ⭐ 829 📅 2024-03-12 - An in-memory cache with item expiration and generics.
- [ttlcache](https://github.com/cheshir/ttlcache) ⭐ 9 📅 2022-10-02 - In-memory key value storage with TTL for each record.

### Databases Implemented in Go

- [badger](https://github.com/dgraph-io/badger) ⭐ 13,254 📅 2024-01-19 - Fast key-value store in Go.
- [bbolt](https://github.com/etcd-io/bbolt) ⭐ 7,501 📅 2024-03-13 - An embedded key/value database for Go.
- [Bitcask](https://git.mills.io/prologic/bitcask) - Bitcask is an embeddable, persistent and fast key-value (KV) database written in pure Go with predictable read/write performance, low latency and high throughput thanks to the bitcask on-disk layout (LSM+WAL).
- [buntdb](https://github.com/tidwall/buntdb) ⭐ 4,357 📅 2023-04-13 - Fast, embeddable, in-memory key/value database for Go with custom indexing and spatial support.
- [clover](https://github.com/ostafen/clover) ⭐ 571 📅 2024-01-31 - A lightweight document-oriented NoSQL database written in pure Golang.
- [cockroach](https://github.com/cockroachdb/cockroach) ⭐ 28,856 📅 2024-03-22 - Scalable, Geo-Replicated, Transactional Datastore.
- [Coffer](https://github.com/claygod/coffer) ⭐ 37 📅 2023-04-09 - Simple ACID key-value database that supports transactions.
- [column](https://github.com/kelindar/column) ⭐ 1,363 📅 2023-10-13 - High-performance, columnar, embeddable in-memory store with bitmap indexing and transactions.
- [CovenantSQL](https://github.com/CovenantSQL/CovenantSQL) ⭐ 1,472 📅 2021-08-23 - CovenantSQL is a SQL database on blockchain.
- [Databunker](https://github.com/paranoidguy/databunker) ⭐ 1,181 📅 2023-12-20 - Personally identifiable information (PII) storage service built to comply with GDPR and CCPA.
- [dgraph](https://github.com/dgraph-io/dgraph) ⭐ 19,986 📅 2024-03-19 - Scalable, Distributed, Low Latency, High Throughput Graph Database.
- [diskv](https://github.com/peterbourgon/diskv) ⭐ 1,338 📅 2021-11-10 - Home-grown disk-backed key-value store.
- [dolt](https://github.com/dolthub/dolt) ⭐ 16,652 📅 2024-03-21 - Dolt – It's Git for Data.
- [dtf](https://github.com/dtm-labs/dtf) ⭐ 214 📅 2022-03-29 - A distributed transaction manager. Support XA, TCC, SAGA, Reliable Messages.
- [eliasdb](https://github.com/krotik/eliasdb) ⭐ 988 📅 2022-08-14 - Dependency-free, transactional graph database with REST API, phrase search and SQL-like query language.
- [godis](https://github.com/hdt3213/godis) ⭐ 3,275 📅 2024-01-19 - A Golang implemented high-performance Redis server and cluster.
- [goleveldb](https://github.com/syndtr/goleveldb) ⭐ 5,987 📅 2022-07-21 - Implementation of the [LevelDB](https://github.com/google/leveldb) ⭐ 34,822 📅 2023-04-18 key/value database in Go.
- [hare](https://github.com/jameycribbs/hare) ⭐ 86 📅 2021-02-24 - A simple database management system that stores each table as a text file of line-delimited JSON.
- [immudb](https://github.com/codenotary/immudb) ⭐ 8,452 📅 2024-03-01 - immudb is a lightweight, high-speed immutable database for systems and applications written in Go.
- [influxdb](https://github.com/influxdb/influxdb) ⭐ 27,505 📅 2024-03-21 - Scalable datastore for metrics, events, and real-time analytics.
- [ledisdb](https://github.com/siddontang/ledisdb) ⭐ 4,056 📅 2020-05-10 - Ledisdb is a high performance NoSQL like Redis based on LevelDB.
- [levigo](https://github.com/jmhodges/levigo) ⭐ 416 📅 2019-12-14 - Levigo is a Go wrapper for LevelDB.
- [libradb](https://github.com/amit-davidson/LibraDB) ⭐ 143 📅 2022-10-06 - LibraDB is a simple database with less then 1000 lines of code for learning.
- [LinDB](https://github.com/lindb/lindb) ⭐ 2,809 📅 2024-02-26 - LinDB is a scalable, high performance, high availability distributed time series database.
- [lotusdb](https://github.com/flower-corp/lotusdb) ⭐ 1,935 📅 2024-01-04 - Fast k/v database compatible with lsm and b+tree.
- [Milvus](https://github.com/milvus-io/milvus) ⭐ 26,157 📅 2024-03-22 - Milvus is a vector database for embedding management, analytics and search.
- [moss](https://github.com/couchbase/moss) ⭐ 943 📅 2022-03-02 - Moss is a simple LSM key-value storage engine written in 100% Go.
- [nutsdb](https://github.com/xujiajun/nutsdb) ⭐ 3,271 📅 2024-02-25 - Nutsdb is a simple, fast, embeddable, persistent key/value store written in pure Go. It supports fully serializable transactions and many data structures such as list, set, sorted set.
- [objectbox-go](https://github.com/objectbox/objectbox-go) ⭐ 1,014 📅 2024-02-16 - High-performance embedded Object Database (NoSQL) with Go API.
- [piladb](https://github.com/fern4lvarez/piladb) ⭐ 202 📅 2018-03-29 - Lightweight RESTful database engine based on stack data structures.
- [pogreb](https://github.com/akrylysov/pogreb) ⭐ 1,214 📅 2024-01-01 - Embedded key-value store for read-heavy workloads.
- [prometheus](https://github.com/prometheus/prometheus) ⭐ 52,290 📅 2024-03-22 - Monitoring system and time series database.
- [pudge](https://github.com/recoilme/pudge) ⭐ 360 📅 2020-04-13 - Fast and simple key/value store written using Go's standard library.
- [regatta](https://github.com/jamf/regatta) ⭐ 60 📅 2024-03-01 - Fast, simple, geo-distributed KV store built for cloud native era.
- [rosedb](https://github.com/roseduan/rosedb) ⭐ 4,282 📅 2024-03-03 - An embedded k-v database based on LSM+WAL, supports string, list, hash, set, zset.
- [rqlite](https://github.com/rqlite/rqlite) ⭐ 14,741 📅 2024-03-19 - The lightweight, distributed, relational database built on SQLite.
- [tempdb](https://github.com/rafaeljesus/tempdb) ⭐ 18 📅 2018-02-14 - Key-value store for temporary items.
- [tidb](https://github.com/pingcap/tidb) ⭐ 35,933 📅 2024-03-22 - TiDB is a distributed SQL database. Inspired by the design of Google F1.
- [tiedot](https://github.com/HouzuoGuo/tiedot) ⭐ 2,719 📅 2021-09-05 - Your NoSQL database powered by Golang.
- [unitdb](https://github.com/unit-io/unitdb) ⭐ 116 📅 2021-10-28 - Fast timeseries database for IoT, realtime messaging applications. Access unitdb with pubsub over tcp or websocket using github.com/unit-io/unitd application.
- [Vasto](https://github.com/chrislusf/vasto) ⭐ 255 📅 2019-03-07 - A distributed high-performance key-value store. On Disk. Eventual consistent. HA. Able to grow or shrink without service interruption.
- [VictoriaMetrics](https://github.com/VictoriaMetrics/VictoriaMetrics) ⭐ 10,631 📅 2024-03-21 - fast, resource-effective and scalable open source time series database. May be used as long-term remote storage for Prometheus. Supports PromQL.

### Database Schema Migration

- [atlas](https://github.com/ariga/atlas) ⭐ 4,770 📅 2024-03-21 - A Database Toolkit. A CLI designed to help companies better work with their data.
- [avro](https://github.com/khezen/avro) ⭐ 45 📅 2022-01-11 - Discover SQL schemas and convert them to AVRO schemas. Query SQL records into AVRO bytes.
- [bytebase](https://github.com/bytebase/bytebase) ⭐ 9,770 📅 2024-03-22 - Safe database schema change and version control for DevOps teams.
- [darwin](https://github.com/GuiaBolso/darwin) ⭐ 141 📅 2019-12-18 - Database schema evolution library for Go.
- [dbmate](https://github.com/amacneil/dbmate) ⭐ 4,252 📅 2024-03-11 - A lightweight, framework-agnostic database migration tool.
- [go-fixtures](https://github.com/RichardKnop/go-fixtures) ⭐ 28 📅 2019-12-26 - Django style fixtures for Golang's excellent built-in database/sql library.
- [go-pg-migrate](https://github.com/lawzava/go-pg-migrate) ⭐ 10 📅 2023-10-09 - CLI-friendly package for go-pg migrations management.
- [go-pg-migrations](https://github.com/robinjoseph08/go-pg-migrations) ⭐ 84 📅 2020-10-27 - A Go package to help write migrations with go-pg/pg.
- [goavro](https://github.com/linkedin/goavro) ⭐ 946 📅 2022-10-19 - A Go package that encodes and decodes Avro data.
- [godfish](https://github.com/rafaelespinoza/godfish) ⭐ 7 📅 2024-01-17 - Database migration manager, works with native query language. Support for cassandra, mysql, postgres, sqlite3.
- [goose](https://github.com/pressly/goose) ⭐ 5,399 📅 2024-03-15 - Database migration tool. You can manage your database's evolution by creating incremental SQL or Go scripts.
- [gorm-seeder](https://github.com/Kachit/gorm-seeder) ⭐ 13 📅 2022-11-20 - Simple database seeder for Gorm ORM.
- [gormigrate](https://github.com/go-gormigrate/gormigrate) ⭐ 979 📅 2024-03-18 - Database schema migration helper for Gorm ORM.
- [libschema](https://github.com/muir/libschema) ⭐ 14 📅 2023-06-02 - Define your migrations separately in each library. Migrations for open source libraries. MySQL & PostgreSQL.
- [migrate](https://github.com/golang-migrate/migrate) ⭐ 13,696 📅 2024-01-11 - Database migrations. CLI and Golang library.
- [migrator](https://github.com/lopezator/migrator) ⭐ 163 📅 2023-10-30 - Dead simple Go database migration library.
- [migrator](https://github.com/larapulse/migrator) ⭐ 24 📅 2022-07-07 - MySQL database migrator designed to run migrations to your features and manage database schema update with intuitive go code.
- [schema](https://github.com/adlio/schema) ⭐ 30 📅 2023-09-18 - Library to embed schema migrations for database/sql-compatible databases inside your Go binaries.
- [skeema](https://github.com/skeema/skeema) ⭐ 1,220 📅 2024-03-15 - Pure-SQL schema management system for MySQL, with support for sharding and external online schema change tools.
- [soda](https://github.com/gobuffalo/pop/tree/master/soda) - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
- [sql-migrate](https://github.com/rubenv/sql-migrate) ⭐ 3,065 📅 2023-12-22 - Database migration tool. Allows embedding migrations into the application using go-bindata.
- [sqlize](https://github.com/sunary/sqlize) ⭐ 77 📅 2024-03-11 - Database migration generator. Allows generate sql migration from model and existing sql by differ them.

### Database Tools

- [chproxy](https://github.com/Vertamedia/chproxy) ⭐ 1,196 📅 2024-03-20 - HTTP proxy for ClickHouse database.
- [clickhouse-bulk](https://github.com/nikepan/clickhouse-bulk) ⭐ 459 📅 2023-11-17 - Collects small inserts and sends big requests to ClickHouse servers.
- [dbbench](https://github.com/sj14/dbbench) ⭐ 99 📅 2024-03-22 - Database benchmarking tool with support for several databases and scripts.
- [dg](https://github.com/codingconcepts/dg) ⭐ 22 📅 2024-02-06 - A fast data generator that produces CSV files from generated relational data.
- [dynago](https://github.com/twharmon/dynago) ⭐ 11 📅 2023-07-22 - Simplify working with AWS DynamoDB.
- [go-mysql](https://github.com/siddontang/go-mysql) ⭐ 4,379 📅 2024-03-14 - Go toolset to handle MySQL protocol and replication.
- [go-mysql-elasticsearch](https://github.com/siddontang/go-mysql-elasticsearch) ⭐ 4,065 📅 2020-08-22 - Sync your MySQL data into Elasticsearch automatically.
- [hasql](https://golang.yandex/hasql) - Library for accessing multi-host SQL database installations.
- [kingshard](https://github.com/flike/kingshard) ⭐ 6,323 📅 2024-02-23 - kingshard is a high performance proxy for MySQL powered by Golang.
- [octillery](https://github.com/knocknote/octillery) ⭐ 188 📅 2021-01-04 - Go package for sharding databases ( Supports every ORM or raw SQL ).
- [onedump](https://github.com/liweiyi88/onedump) ⭐ 49 📅 2024-02-05 - Database backup from different drivers to different destinations with one command and configuration.
- [orchestrator](https://github.com/github/orchestrator) ⭐ 5,448 📅 2023-02-28 - MySQL replication topology manager & visualizer.
- [pg_timetable](https://github.com/cybertec-postgresql/pg_timetable) ⭐ 1,006 📅 2024-03-05 - Advanced scheduling for PostgreSQL.
- [pgweb](https://github.com/sosedoff/pgweb) ⭐ 8,239 📅 2024-03-16 - Web-based PostgreSQL database browser.
- [prep](https://github.com/hexdigest/prep) ⭐ 32 📅 2017-12-19 - Use prepared SQL statements without changing your code.
- [pREST](https://github.com/prest/prest) ⭐ 4,060 📅 2024-03-11 - Simplify and accelerate development, ⚡ instant, realtime, high-performance on any Postgres application, existing or new.
- [rdb](https://github.com/HDT3213/rdb) ⭐ 336 📅 2024-02-29 - Redis RDB file parser for secondary development and memory analysis.
- [rwdb](https://github.com/andizzle/rwdb) ⭐ 18 📅 2017-11-08 - rwdb provides read replica capability for multiple database servers setup.
- [vitess](https://github.com/youtube/vitess) ⭐ 17,685 📅 2024-03-21 - vitess provides servers and tools which facilitate scaling of MySQL databases for large scale web services.

### SQL Query Builders

_Libraries for building and using SQL._

- [bqb](https://github.com/nullism/bqb) ⭐ 121 📅 2023-10-18 - Lightweight and easy to learn query builder.
- [buildsqlx](https://github.com/arthurkushman/buildsqlx) ⭐ 143 📅 2023-10-21 - Go database query builder library for PostgreSQL.
- [builq](https://github.com/cristalhq/builq) ⭐ 86 📅 2024-03-20 - Easily build SQL queries in Go.
- [dbq](https://github.com/rocketlaunchr/dbq) ⭐ 389 📅 2021-02-22 - Zero boilerplate database operations for Go.
- [Dotsql](https://github.com/gchaincl/dotsql) ⭐ 714 📅 2023-11-23 - Go library that helps you keep sql files in one place and use them with ease.
- [gendry](https://github.com/didi/gendry) ⭐ 1,573 📅 2023-09-26 - Non-invasive SQL builder and powerful data binder.
- [godbal](https://github.com/xujiajun/godbal) ⭐ 59 📅 2019-01-30 - Database Abstraction Layer (dbal) for go. Support SQL builder and get result easily.
- [goqu](https://github.com/doug-martin/goqu) ⭐ 2,209 📅 2023-12-14 - Idiomatic SQL builder and query library.
- [gosql](https://github.com/twharmon/gosql) ⭐ 30 📅 2022-04-12 - SQL Query builder with better null values support.
- [Hotcoal](https://github.com/motrboat/hotcoal) ⭐ 14 📅 2023-12-23 - Secure your handcrafted SQL against injection.
- [igor](https://github.com/galeone/igor) ⭐ 120 📅 2023-12-25 - Abstraction layer for PostgreSQL that supports advanced functionality and uses gorm-like syntax.
- [jet](https://github.com/go-jet/jet) ⭐ 1,950 📅 2024-02-27 - Framework for writing type-safe SQL queries in Go, with ability to easily convert database query result into desired arbitrary object structure.
- [ormlite](https://github.com/pupizoid/ormlite) ⭐ 13 📅 2023-01-30 - Lightweight package containing some ORM-like features and helpers for sqlite databases.
- [ozzo-dbx](https://github.com/go-ozzo/ozzo-dbx) ⭐ 620 📅 2020-09-25 - Powerful data retrieval methods as well as DB-agnostic query building capabilities.
- [qry](https://github.com/HnH/qry) ⭐ 35 📅 2024-02-20 - Tool that generates constants from files with raw SQL queries.
- [sg](https://github.com/go-the-way/sg) ⭐ 5 📅 2022-05-11 - A SQL Gen for generating standard SQLs(supports: CRUD) written in Go.
- [sq](https://github.com/bokwoon95/go-structured-query) ⭐ 195 📅 2023-01-15 - Type-safe SQL builder and struct mapper for Go.
- [sqlc](https://github.com/kyleconroy/sqlc) ⭐ 10,499 📅 2024-03-20 - Generate type-safe code from SQL.
- [sqlf](https://github.com/leporo/sqlf) ⭐ 139 📅 2023-04-13 - Fast SQL query builder.
- [sqlingo](https://github.com/lqs/sqlingo) ⭐ 364 📅 2024-03-20 - A lightweight DSL to build SQL in Go.
- [sqrl](https://github.com/elgris/sqrl) ⭐ 268 📅 2021-07-27 - SQL query builder, fork of Squirrel with improved performance.
- [Squalus](https://gitlab.com/qosenergy/squalus) - Thin layer over the Go SQL package that makes it easier to perform queries.
- [Squirrel](https://github.com/Masterminds/squirrel) ⭐ 6,449 📅 2024-02-27 - Go library that helps you build SQL queries.
- [xo](https://github.com/knq/xo) ⭐ 3,542 📅 2024-03-12 - Generate idiomatic Go code for databases based on existing schema definitions or custom queries supporting PostgreSQL, MySQL, SQLite, Oracle, and Microsoft SQL Server.

**[⬆ back to top](#contents)**

## Database Drivers

### Interfaces to Multiple Backends

- [cayley](https://github.com/google/cayley) ⭐ 14,743 📅 2023-07-26 - Graph database with support for multiple backends.
- [dsc](https://github.com/viant/dsc) ⭐ 30 📅 2024-03-17 - Datastore connectivity for SQL, NoSQL, structured files.
- [dynamo](https://github.com/fogfish/dynamo) ⭐ 16 📅 2024-02-19 - A simple key-value abstraction to store algebraic and linked-data data types at AWS storage services: AWS DynamoDB and AWS S3.
- [go-transaction-manager](https://github.com/avito-tech/go-transaction-manager) ⭐ 152 📅 2024-02-15 - Transaction manager with multiple adapters (sql, sqlx, gorm, mongo, ...) controls transaction boundaries.
- [gokv](https://github.com/philippgille/gokv) ⭐ 650 📅 2024-01-28 - Simple key-value store abstraction and implementations for Go (Redis, Consul, etcd, bbolt, BadgerDB, LevelDB, Memcached, DynamoDB, S3, PostgreSQL, MongoDB, CockroachDB and many more).

### Relational Database Drivers

- [avatica](https://github.com/apache/calcite-avatica-go) ⭐ 114 📅 2024-03-13 - Apache Avatica/Phoenix SQL driver for database/sql.
- [bgc](https://github.com/viant/bgc) ⭐ 21 📅 2024-03-17 - Datastore Connectivity for BigQuery for go.
- [firebirdsql](https://github.com/nakagami/firebirdsql) ⭐ 215 📅 2024-03-03 - Firebird RDBMS SQL driver for Go.
- [go-adodb](https://github.com/mattn/go-adodb) ⭐ 135 📅 2022-04-21 - Microsoft ActiveX Object DataBase driver for go that uses database/sql.
- [go-mssqldb](https://github.com/denisenkom/go-mssqldb) ⭐ 1,793 📅 2023-04-30 - Microsoft MSSQL driver for Go.
- [go-oci8](https://github.com/mattn/go-oci8) ⭐ 624 📅 2021-01-09 - Oracle driver for go that uses database/sql.
- [go-sql-driver/mysql](https://github.com/go-sql-driver/mysql) ⭐ 14,098 📅 2024-03-17 - MySQL driver for Go.
- [go-sqlite3](https://github.com/mattn/go-sqlite3) ⭐ 7,362 📅 2024-02-21 - SQLite3 driver for go that uses database/sql.
- [godror](https://github.com/godror/godror) ⭐ 496 📅 2024-03-14 - Oracle driver for Go, using the ODPI-C driver.
- [gofreetds](https://github.com/minus5/gofreetds) ⭐ 110 📅 2020-08-26 - Microsoft MSSQL driver. Go wrapper over [FreeTDS](https://www.freetds.org).
- [KSQL](https://github.com/VinGarcia/ksql) ⭐ 273 📅 2024-01-22 - A Simple and Powerful Golang SQL Library
- [pgx](https://github.com/jackc/pgx) ⭐ 9,232 📅 2024-03-18 ⭐ 9,232 📅 2024-03-18 - PostgreSQL driver supporting features beyond those exposed by database/sql.
- [pig](https://github.com/alexeyco/pig) ⭐ 16 📅 2021-04-18 - Simple [pgx](https://github.com/jackc/pgx) ⭐ 9,232 📅 2024-03-18 ⭐ 9,232 📅 2024-03-18 wrapper to execute and [scan](https://github.com/georgysavva/scany) ⭐ 1,154 📅 2024-03-17 query results easily.
- [pq](https://github.com/lib/pq) ⭐ 8,670 📅 2023-07-07 - Pure Go Postgres driver for database/sql.
- [Sqinn-Go](https://github.com/cvilsmeier/sqinn-go) ⭐ 395 📅 2024-01-06 - SQLite with pure Go.
- [sqlhooks](https://github.com/qustavo/sqlhooks) ⭐ 631 📅 2022-04-01 - Attach hooks to any database/sql driver.
- [surrealdb.go](https://github.com/surrealdb/surrealdb.go) - SurrealDB Driver for Go.
- [ydb-go-sdk](https://github.com/ydb-platform/ydb-go-sdk) ⭐ 123 📅 2024-03-19 - native and database/sql driver YDB (Yandex Database)

### NoSQL Database Drivers

- [aerospike-client-go](https://github.com/aerospike/aerospike-client-go) ⭐ 420 📅 2024-01-25 - Aerospike client in Go language.
- [arangolite](https://github.com/solher/arangolite) ⭐ 73 📅 2021-03-10 - Lightweight golang driver for ArangoDB.
- [asc](https://github.com/viant/asc) ⭐ 9 📅 2019-04-20 - Datastore Connectivity for Aerospike for go.
- [forestdb](https://github.com/couchbase/goforestdb) ⭐ 36 📅 2016-12-15 - Go bindings for ForestDB.
- [go-couchbase](https://github.com/couchbase/go-couchbase) ⭐ 321 📅 2022-02-09 - Couchbase client in Go.
- [go-pilosa](https://github.com/pilosa/go-pilosa) ⭐ 58 📅 2022-09-27 - Go client library for Pilosa.
- [go-rejson](https://github.com/nitishm/go-rejson) ⭐ 337 📅 2023-03-31 - Golang client for redislabs' ReJSON module using Redigo golang client. Store and manipulate structs as JSON objects in redis with ease.
- [gocb](https://github.com/couchbase/gocb) ⭐ 356 📅 2024-03-20 - Official Couchbase Go SDK.
- [gocosmos](https://github.com/btnguyen2k/gocosmos) ⭐ 21 📅 2024-02-25 - REST client and standard `database/sql` driver for Azure Cosmos DB.
- [gocql](https://gocql.github.io) - Go language driver for Apache Cassandra.
- [godis](https://github.com/piaohao/godis) ⭐ 110 📅 2020-05-12 - redis client implement by golang, inspired by jedis.
- [godscache](https://github.com/defcronyke/godscache) ⭐ 11 📅 2019-02-08 - A wrapper for the Google Cloud Platform Go Datastore package that adds caching using memcached.
- [gomemcache](https://github.com/bradfitz/gomemcache/) ⭐ 1,684 📅 2023-09-05 - memcache client library for the Go programming language.
- [gomemcached](https://github.com/aliexpressru/gomemcached) ⭐ 16 📅 2024-02-19 - A binary Memcached client for Go with support for sharding using consistent hashing, along with SASL.
- [gorethink](https://github.com/dancannon/gorethink) ⭐ 1,646 📅 2022-06-02 - Go language driver for RethinkDB.
- [goriak](https://github.com/zegl/goriak) ⭐ 30 📅 2018-12-27 - Go language driver for Riak KV.
- [Kivik](https://github.com/go-kivik/kivik) ⭐ 296 📅 2024-03-18 - Kivik provides a common Go and GopherJS client library for CouchDB, PouchDB, and similar databases.
- [mgm](https://github.com/kamva/mgm) ⭐ 716 📅 2023-09-12 - MongoDB model-based ODM for Go (based on official MongoDB driver).
- [mgo](https://github.com/globalsign/mgo) ⭐ 1,962 📅 2018-10-15 - (unmaintained) MongoDB driver for the Go language that implements a rich and well tested selection of features under a very simple API following standard Go idioms.
- [mongo-go-driver](https://github.com/mongodb/mongo-go-driver) ⭐ 7,882 📅 2024-03-14 - Official MongoDB driver for the Go language.
- [neo4j](https://github.com/cihangir/neo4j) ⭐ 27 📅 2015-04-02 - Neo4j Rest API Bindings for Golang.
- [Neo4j-GO](https://github.com/davemeehan/Neo4j-GO) ⭐ 77 📅 2018-06-20 - Neo4j REST Client in golang.
- [neoism](https://github.com/jmcvetta/neoism) ⭐ 389 📅 2020-02-16 - Neo4j client for Golang.
- [qmgo](https://github.com/qiniu/qmgo) ⭐ 1,257 📅 2023-07-05 - The MongoDB driver for Go. It‘s based on official MongoDB driver but easier to use like Mgo.
- [redeo](https://github.com/bsm/redeo) ⭐ 432 📅 2023-01-20 - Redis-protocol compatible TCP servers/services.
- [redigo](https://github.com/gomodule/redigo) ⭐ 9,686 📅 2024-02-25 - Redigo is a Go client for the Redis database.
- [redis](https://github.com/redis/go-redis) ⭐ 19,093 📅 2024-03-21 - Redis client for Golang.
- [rueidis](http://github.com/rueian/rueidis) ⭐ 2,151 📅 2024-03-19 - Fast Redis RESP3 client with auto pipelining and server-assisted client side caching.
- [xredis](https://github.com/shomali11/xredis) ⭐ 19 📅 2019-06-08 - Typesafe, customizable, clean & easy to use Redis client.

### Search and Analytic Databases

- [clickhouse-go](https://github.com/ClickHouse/clickhouse-go/) ⭐ 2,711 📅 2024-03-19 - ClickHouse SQL client for Go with a `database/sql` compatibility.
- [elastic](https://github.com/olivere/elastic) ⭐ 7,296 📅 2022-03-23 - Elasticsearch client for Go.
- [elasticsql](https://github.com/cch123/elasticsql) ⭐ 1,137 📅 2023-08-06 - Convert sql to elasticsearch dsl in Go.
- [elastigo](https://github.com/mattbaird/elastigo) ⭐ 947 📅 2017-01-23 - Elasticsearch client library.
- [go-elasticsearch](https://github.com/elastic/go-elasticsearch) ⭐ 5,418 📅 2024-03-14 - Official Elasticsearch client for Go.
- [goes](https://github.com/OwnLocal/goes) ⭐ 30 📅 2017-03-02 - Library to interact with Elasticsearch.
- [skizze](https://github.com/seiflotfy/skizze) ⭐ 88 📅 2016-05-03 - probabilistic data-structures service and storage.

**[⬆ back to top](#contents)**

## Date and Time

_Libraries for working with dates and times._

- [approx](https://github.com/goschtalt/approx) ⭐ 7 📅 2024-03-21 - A Duration extension supporting parsing/printing durations in days, weeks and years.
- [carbon](https://github.com/golang-module/carbon) ⭐ 4,454 📅 2024-03-10 - A simple, semantic and developer-friendly golang package for datetime.
- [carbon](https://github.com/uniplaces/carbon) ⭐ 770 📅 2024-01-17 - Simple Time extension with a lot of util methods, ported from PHP Carbon library.
- [cronrange](https://github.com/1set/cronrange) ⭐ 18 📅 2022-02-03 - Parses Cron-style time range expressions, checks if the given time is within any ranges.
- [date](https://github.com/rickb777/date) ⭐ 124 📅 2024-02-17 - Augments Time for working with dates, date ranges, time spans, periods, and time-of-day.
- [dateparse](https://github.com/araddon/dateparse) ⭐ 1,978 📅 2021-04-29 - Parse date's without knowing format in advance.
- [durafmt](https://github.com/hako/durafmt) ⭐ 486 📅 2021-06-08 - Time duration formatting library for Go.
- [feiertage](https://github.com/wlbr/feiertage) ⭐ 45 📅 2021-08-16 - Set of functions to calculate public holidays in Germany, incl. specialization on the states of Germany (Bundesländer). Things like Easter, Pentecost, Thanksgiving...
- [go-anytime](https://github.com/ijt/go-anytime) ⭐ 14 📅 2023-01-17 - Parse dates/times like "next dec 22nd at 3pm" and ranges like "from today until next thursday" without knowing the format in advance.
- [go-datebin](https://github.com/deatil/go-datebin) ⭐ 4 📅 2024-03-09 - A simple datetime parse pkg.
- [go-persian-calendar](https://github.com/yaa110/go-persian-calendar) ⭐ 190 📅 2023-07-12 - The implementation of the Persian (Solar Hijri) Calendar in Go (golang).
- [go-str2duration](https://github.com/xhit/go-str2duration) ⭐ 89 📅 2023-10-14 - Convert string to duration. Support time.Duration returned string and more.
- [go-sunrise](https://github.com/nathan-osman/go-sunrise) ⭐ 82 📅 2022-08-28 - Calculate the sunrise and sunset times for a given location.
- [go-week](https://github.com/stoewer/go-week) ⭐ 9 📅 2021-11-15 - An efficient package to work with ISO8601 week dates.
- [gostradamus](https://github.com/bykof/gostradamus) ⭐ 196 📅 2023-12-24 - A Go package for working with dates.
- [iso8601](https://github.com/relvacode/iso8601) ⭐ 136 📅 2024-01-27 - Efficiently parse ISO8601 date-times without regex.
- [kair](https://github.com/GuilhermeCaruso/kair) ⭐ 25 📅 2020-06-18 - Date and Time - Golang Formatting Library.
- [now](https://github.com/jinzhu/now) ⭐ 4,347 📅 2022-03-17 - Now is a time toolkit for golang.
- [NullTime](https://github.com/kirillDanshin/nulltime) ⭐ 14 📅 2017-03-22 - Nullable `time.Time`.
- [strftime](https://github.com/awoodbeck/strftime) ⭐ 12 📅 2018-02-21 - C99-compatible strftime formatter.
- [timespan](https://github.com/SaidinWoT/timespan) ⭐ 84 📅 2016-04-03 - For interacting with intervals of time, defined as a start time and a duration.
- [timeutil](https://github.com/leekchan/timeutil) ⭐ 193 📅 2015-08-02 - Useful extensions (Timedelta, Strftime, ...) to the golang's time package.
- [tuesday](https://github.com/osteele/tuesday) ⭐ 12 📅 2021-06-19 - Ruby-compatible Strftime function.

**[⬆ back to top](#contents)**

## Distributed Systems

_Packages that help with building Distributed Systems._

- [arpc](https://github.com/lesismal/arpc) ⭐ 872 📅 2024-03-14 - More effective network communication, support two-way-calling, notify, broadcast.
- [bedrock](https://github.com/z5labs/bedrock) ⭐ 3 📅 2024-03-22 - Provides a minimal, modular and composable foundation for quickly developing services and more use case specific frameworks in Go.
- [celeriac](https://github.com/svcavallar/celeriac.v1) - Library for adding support for interacting and monitoring Celery workers, tasks and events in Go.
- [consistent](https://github.com/buraksezer/consistent) ⭐ 654 📅 2022-12-07 - Consistent hashing with bounded loads.
- [consistenthash](https://github.com/mbrostami/consistenthash) ⭐ 25 📅 2024-03-19 - Consistent hashing with configurable replicas.
- [dht](https://github.com/anacrolix/dht) ⭐ 296 📅 2024-02-23 - BitTorrent Kademlia DHT implementation.
- [digota](https://github.com/digota/digota) ⭐ 499 📅 2018-10-14 - grpc ecommerce microservice.
- [dot](https://github.com/dotchain/dot/) ⭐ 84 📅 2019-09-30 - distributed sync using operational transformation/OT.
- [doublejump](https://github.com/edwingeng/doublejump) ⭐ 98 📅 2022-10-19 - A revamped Google's jump consistent hash.
- [dragonboat](https://github.com/lni/dragonboat) ⭐ 4,911 📅 2023-12-22 - A feature complete and high performance multi-group Raft library in Go.
- [Dragonfly](https://github.com/dragonflyoss/Dragonfly2) ⭐ 1,917 📅 2024-03-22 - Provide efficient, stable and secure file distribution and image acceleration based on p2p technology to be the best practice and standard solution in cloud native architectures.
- [drmaa](https://github.com/dgruber/drmaa) ⭐ 48 📅 2022-03-07 - Job submission library for cluster schedulers based on the DRMAA standard.
- [dynamolock](https://cirello.io/dynamolock) - DynamoDB-backed distributed locking implementation.
- [dynatomic](https://github.com/tylfin/dynatomic) ⭐ 16 📅 2020-11-03 - A library for using DynamoDB as an atomic counter.
- [emitter-io](https://github.com/emitter-io/emitter) ⭐ 3,728 📅 2024-02-02 - High performance, distributed, secure and low latency publish-subscribe platform built with MQTT, Websockets and love.
- [failured](https://github.com/andy2046/failured) ⭐ 11 📅 2021-08-01 - adaptive accrual failure detector for distributed systems.
- [flowgraph](https://github.com/vectaport/flowgraph) ⭐ 55 📅 2021-04-24 - flow-based programming package.
- [gleam](https://github.com/chrislusf/gleam) ⭐ 3,332 📅 2024-03-16 - Fast and scalable distributed map/reduce system written in pure Go and Luajit, combining Go's high concurrency with Luajit's high performance, runs standalone or distributed.
- [glow](https://github.com/chrislusf/glow) ⭐ 3,180 📅 2018-11-02 - Easy-to-Use scalable distributed big data processing, Map-Reduce, DAG execution, all in pure Go.
- [gmsec](https://github.com/gmsec/micro) ⭐ 24 📅 2024-01-26 - A Go distributed systems development framework.
- [go-doudou](https://github.com/unionj-cloud/go-doudou) ⭐ 1,324 📅 2024-02-07 - A gossip protocol and OpenAPI 3.0 spec based decentralized microservice framework. Built-in go-doudou cli focusing on low-code and rapid dev can power up your productivity.
- [go-health](https://github.com/InVisionApp/go-health) ⭐ 734 📅 2023-07-24 - Library for enabling asynchronous dependency health checks in your service.
- [go-jump](https://github.com/dgryski/go-jump) ⭐ 377 📅 2021-10-18 - Port of Google's "Jump" Consistent Hash function.
- [go-kit](https://github.com/go-kit/kit) ⭐ 26,025 📅 2024-03-13 - Microservice toolkit with support for service discovery, load balancing, pluggable transports, request tracking, etc.
- [go-micro](https://github.com/micro/go-micro) ⭐ 21,292 📅 2024-02-15 - A distributed systems development framework.
- [go-mysql-lock](https://github.com/sanketplus/go-mysql-lock) ⭐ 58 📅 2023-05-25 - MySQL based distributed lock.
- [go-pdu](https://github.com/pdupub/go-pdu) ⭐ 46 📅 2023-08-08 - A decentralized identity-based social network.
- [go-sundheit](https://github.com/AppsFlyer/go-sundheit) ⭐ 521 📅 2023-12-06 - A library built to provide support for defining async service health checks for golang services.
- [go-zero](https://github.com/tal-tech/go-zero) ⭐ 27,323 📅 2024-03-20 - A web and rpc framework. It's born to ensure the stability of the busy sites with resilient design. Builtin goctl greatly improves the development productivity.
- [gorpc](https://github.com/valyala/gorpc) ⭐ 686 📅 2016-05-19 - Simple, fast and scalable RPC library for high load.
- [grpc-go](https://github.com/grpc/grpc-go) ⭐ 19,682 📅 2024-03-22 - The Go language implementation of gRPC. HTTP/2 based RPC.
- [hprose](https://github.com/hprose/hprose-golang) ⭐ 1,253 📅 2024-02-18 - Very newbility RPC Library, support 25+ languages now.
- [jsonrpc](https://github.com/osamingo/jsonrpc) ⭐ 185 📅 2023-05-01 - The jsonrpc package helps implement of JSON-RPC 2.0.
- [jsonrpc](https://github.com/ybbus/jsonrpc) ⭐ 306 📅 2024-01-31 - JSON-RPC 2.0 HTTP client implementation.
- [Kitex](https://github.com/cloudwego/kitex) ⭐ 6,585 📅 2024-03-22 - A high-performance and strong-extensibility Golang RPC framework that helps developers build microservices. If the performance and extensibility are the main concerns when you develop microservices, Kitex can be a good choice.
- [Kratos](https://github.com/go-kratos/kratos) ⭐ 22,253 📅 2024-03-20 - A modular-designed and easy-to-use microservices framework in Go.
- [liftbridge](https://github.com/liftbridge-io/liftbridge) ⭐ 2,530 📅 2024-02-21 - Lightweight, fault-tolerant message streams for NATS.
- [lura](https://github.com/luraproject/lura) ⭐ 6,019 📅 2024-03-12 - Ultra performant API Gateway framework with middlewares.
- [micro](https://github.com/micro/micro) ⭐ 11,982 📅 2023-07-28 - A distributed systems runtime for the cloud and beyond.
- [NATS](https://github.com/nats-io/gnatsd) ⭐ 14,556 📅 2024-03-21 - Lightweight, high performance messaging system for microservices, IoT, and cloud native systems.
- [outboxer](https://github.com/italolelis/outboxer) ⭐ 151 📅 2023-11-06 - Outboxer is a go library that implements the outbox pattern.
- [pglock](https://cirello.io/pglock) - PostgreSQL-backed distributed locking implementation.
- [pjrpc](https://gitlab.com/pjrpc/pjrpc) - Golang JSON-RPC Server-Client with Protobuf spec.
- [raft](https://github.com/hashicorp/raft) ⭐ 7,775 📅 2024-01-09 - Golang implementation of the Raft consensus protocol, by HashiCorp.
- [raft](https://github.com/etcd-io/raft) ⭐ 489 📅 2024-03-21 - Go implementation of the Raft consensus protocol, by CoreOS.
- [rain](https://github.com/cenkalti/rain) ⭐ 922 📅 2024-01-25 - BitTorrent client and library.
- [redis-lock](https://github.com/bsm/redislock) ⭐ 1,288 📅 2024-03-21 - Simplified distributed locking implementation using Redis.
- [resgate](https://resgate.io/) - Realtime API Gateway for building REST, real time, and RPC APIs, where all clients are synchronized seamlessly.
- [ringpop-go](https://github.com/uber/ringpop-go) ⭐ 813 📅 2022-07-22 - Scalable, fault-tolerant application-layer sharding for Go applications.
- [rpcx](https://github.com/smallnest/rpcx) ⭐ 7,915 📅 2024-03-13 - Distributed pluggable RPC service framework like alibaba Dubbo.
- [Semaphore](https://github.com/jexia/semaphore) ⭐ 91 📅 2021-06-04 - A straightforward (micro) service orchestrator.
- [sleuth](https://github.com/ursiform/sleuth) ⭐ 371 📅 2023-07-09 - Library for master-less p2p auto-discovery and RPC between HTTP services (using [ZeroMQ](https://github.com/zeromq/libzmq) ⭐ 9,185 📅 2024-03-20).
- [sponge](https://github.com/zhufuyi/sponge) ⭐ 774 📅 2024-03-14 - A distributed development framework that integrates automatic code generation, gin and grpc frameworks, base development frameworks.
- [Tarmac](https://github.com/tarmac-project/tarmac) ⭐ 306 📅 2024-02-10 - Framework for writing functions, microservices, or monoliths with WebAssembly
- [Temporal](https://github.com/temporalio/sdk-go) ⭐ 436 📅 2024-03-18 - Durable execution system for making code fault-tolerant and simple.
- [torrent](https://github.com/anacrolix/torrent) ⭐ 5,226 📅 2024-03-22 - BitTorrent client package.
- [trpc-go](https://github.com/trpc-group/trpc-go) ⭐ 637 📅 2024-01-30 - The Go language implementation of tRPC, which is a pluggable, high-performance RPC framework.

**[⬆ back to top](#contents)**

## Dynamic DNS

_Tools for updating dynamic DNS records._

- [DDNS](https://github.com/skibish/ddns) ⭐ 241 📅 2023-10-28 - Personal DDNS client with Digital Ocean Networking DNS as backend.
- [dyndns](https://gitlab.com/alcastle/dyndns) - Background Go process to regularly and automatically check your IP Address and make updates to (one or many) Dynamic DNS records for Google domains whenever your address changes.
- [GoDNS](https://github.com/timothyye/godns) ⭐ 1,420 📅 2024-03-14 - A dynamic DNS client tool, supports DNSPod & HE.net, written in Go.

**[⬆ back to top](#contents)**

## Email

_Libraries and tools that implement email creation and sending._

- [chasquid](https://blitiri.com.ar/p/chasquid) - SMTP server written in Go.
- [douceur](https://github.com/aymerick/douceur) ⭐ 239 📅 2018-03-22 - CSS inliner for your HTML emails.
- [email](https://github.com/jordan-wright/email) ⭐ 2,546 📅 2021-01-09 - A robust and flexible email library for Go.
- [email-verifier](https://github.com/AfterShip/email-verifier) ⭐ 1,044 📅 2024-01-12 - A Go library for email verification without sending any emails.
- [go-dkim](https://github.com/toorop/go-dkim) ⭐ 95 📅 2024-01-03 - DKIM library, to sign & verify email.
- [go-email-normalizer](https://github.com/dimuska139/go-email-normalizer) ⭐ 60 📅 2024-01-08 - Golang library for providing a canonical representation of email address.
- [go-email-validator](https://github.com/go-email-validator/go-email-validator) ⭐ 52 📅 2023-04-09 - Modular email validator for syntax, disposable, smtp, etc... checking.
- [go-imap](https://github.com/emersion/go-imap) ⭐ 1,960 📅 2024-03-19 - IMAP library for clients and servers.
- [go-mail](https://github.com/wneessen/go-mail) ⭐ 428 📅 2024-02-27 - A simple Go library for sending mails in Go.
- [go-message](https://github.com/emersion/go-message) ⭐ 350 📅 2024-03-06 - Streaming library for the Internet Message Format and mail messages.
- [go-premailer](https://github.com/vanng822/go-premailer) ⭐ 129 📅 2023-04-20 - Inline styling for HTML mail in Go.
- [go-simple-mail](https://github.com/xhit/go-simple-mail) ⭐ 585 📅 2024-03-12 - Very simple package to send emails with SMTP Keep Alive and two timeouts: Connect and Send.
- [Hectane](https://github.com/hectane/hectane) ⭐ 219 📅 2019-08-22 - Lightweight SMTP client providing an HTTP API.
- [hermes](https://github.com/matcornic/hermes) ⭐ 2,752 📅 2020-01-29 - Golang package that generates clean, responsive HTML e-mails.
- [Maddy](https://github.com/foxcpp/maddy) ⭐ 4,608 📅 2024-02-14 - All-in-one (SMTP, IMAP, DKIM, DMARC, MTA-STS, DANE) email server
- [mailchain](https://github.com/mailchain/mailchain) ⭐ 142 📅 2022-04-01 - Send encrypted emails to blockchain addresses written in Go.
- [mailgun-go](https://github.com/mailgun/mailgun-go) ⭐ 676 📅 2024-01-24 - Go library for sending mail with the Mailgun API.
- [MailHog](https://github.com/mailhog/MailHog) ⭐ 13,195 📅 2022-08-02 - Email and SMTP testing with web and API interface.
- [Mailpit](https://github.com/axllent/mailpit) ⭐ 4,300 📅 2024-03-17 - Email and SMTP testing tool for developers.
- [mailx](https://github.com/valord577/mailx) ⭐ 11 📅 2024-03-06 - Mailx is a library that makes it easier to send email via SMTP. It is an enhancement of the golang standard library `net/smtp`.
- [SendGrid](https://github.com/sendgrid/sendgrid-go) ⭐ 948 📅 2023-12-01 - SendGrid's Go library for sending email.
- [smtp](https://github.com/mailhog/smtp) ⭐ 74 📅 2016-11-19 - SMTP server protocol state machine.
- [smtpmock](https://github.com/mocktools/go-smtp-mock) ⭐ 110 📅 2024-03-03 - Lightweight configurable multithreaded fake SMTP server. Mimic any SMTP behaviour for your test environment.
- [truemail-go](https://github.com/truemail-rb/truemail-go) ⭐ 78 📅 2024-01-24 - Configurable Golang email validator/verifier. Verify email via Regex, DNS, SMTP and even more.

**[⬆ back to top](#contents)**

## Embeddable Scripting Languages

_Embedding other languages inside your go code._

- [anko](https://github.com/mattn/anko) ⭐ 1,425 📅 2023-12-12 - Scriptable interpreter written in Go.
- [binder](https://github.com/alexeyco/binder) ⭐ 69 📅 2018-07-29 - Go to Lua binding library, based on [gopher-lua](https://github.com/yuin/gopher-lua) ⭐ 5,941 📅 2023-12-12 ⭐ 5,941 📅 2023-12-12.
- [cel-go](https://github.com/google/cel-go) ⭐ 2,009 📅 2024-03-21 - Fast, portable, non-Turing complete expression evaluation with gradual typing.
- [ecal](https://github.com/krotik/ecal) ⭐ 38 📅 2021-05-23 - A simple embeddable scripting language which supports concurrent event processing.
- [expr](https://github.com/antonmedv/expr) ⭐ 5,436 📅 2024-03-20 - Expression evaluation engine for Go: fast, non-Turing complete, dynamic typing, static typing.
- [gentee](https://github.com/gentee/gentee) ⭐ 125 📅 2023-02-19 - Embeddable scripting programming language.
- [gisp](https://github.com/jcla1/gisp) ⭐ 510 📅 2014-06-29 - Simple LISP in Go.
- [go-duktape](https://github.com/olebedev/go-duktape) ⭐ 781 📅 2021-03-26 - Duktape JavaScript engine bindings for Go.
- [go-lua](https://github.com/Shopify/go-lua) ⭐ 2,893 📅 2024-03-12 - Port of the Lua 5.2 VM to pure Go.
- [go-php](https://github.com/deuill/go-php) ⭐ 922 📅 2018-10-01 - PHP bindings for Go.
- [go-python](https://github.com/sbinet/go-python) ⭐ 1,519 📅 2023-07-24 - naive go bindings to the CPython C-API.
- [goja](https://github.com/dop251/goja) ⭐ 4,813 📅 2024-02-20 - ECMAScript 5.1(+) implementation in Go.
- [golua](https://github.com/aarzilli/golua) ⭐ 634 📅 2021-05-07 - Go bindings for Lua C API.
- [gopher-lua](https://github.com/yuin/gopher-lua) ⭐ 5,941 📅 2023-12-12 ⭐ 5,941 📅 2023-12-12 - Lua 5.1 VM and compiler written in Go.
- [gval](https://github.com/PaesslerAG/gval) ⭐ 693 📅 2023-03-03 - A highly customizable expression language written in Go.
- [metacall](https://github.com/metacall/core) ⭐ 1,479 📅 2024-03-06 - Cross-platform Polyglot Runtime which supports NodeJS, JavaScript, TypeScript, Python, Ruby, C#, WebAssembly, Java, Cobol and more.
- [ngaro](https://github.com/db47h/ngaro) ⭐ 26 📅 2018-06-03 - Embeddable Ngaro VM implementation enabling scripting in Retro.
- [prolog](https://github.com/ichiban/prolog) ⭐ 526 📅 2024-02-18 - Embeddable Prolog.
- [purl](https://github.com/ian-kent/purl) ⭐ 40 📅 2014-12-07 - Perl 5.18.2 embedded in Go.
- [starlark-go](https://github.com/google/starlark-go) ⭐ 2,184 📅 2024-03-14 - Go implementation of Starlark: Python-like language with deterministic evaluation and hermetic execution.
- [tengo](https://github.com/d5/tengo) ⭐ 3,417 📅 2024-02-25 - Bytecode compiled script language for Go.

**[⬆ back to top](#contents)**

## Error Handling

_Libraries for handling errors._

- [emperror](https://github.com/emperror/emperror) ⭐ 327 📅 2020-10-04 - Error handling tools and best practices for Go libraries and applications.
- [eris](https://github.com/rotisserie/eris) ⭐ 1,410 📅 2023-02-13 - A better way to handle, trace, and log errors in Go. Compatible with the standard error library and github.com/pkg/errors.
- [errlog](https://github.com/snwfdhmp/errlog) ⭐ 456 📅 2023-06-27 - Hackable package that determines responsible source code for an error (and some other fast-debugging features). Pluggable to any logger in-place.
- [errors](https://github.com/emperror/errors) ⭐ 191 📅 2022-05-27 - Drop-in replacement for the standard library errors package and github.com/pkg/errors. Provides various error handling primitives.
- [errors](https://github.com/neuronlabs/errors) ⭐ 6 📅 2019-08-01 - Simple golang error handling with classification primitives.
- [errors](https://github.com/PumpkinSeed/errors) ⭐ 7 📅 2020-01-09 - The most simple error wrapper with awesome performance and minimal memory overhead.
- [errors](https://gitlab.com/tozd/go/errors) - Providing errors with a stack trace and optional structured details. Compatible with github.com/pkg/errors API but does not use it internally.
- [errors](https://github.com/bnkamalesh/errors) ⭐ 61 📅 2023-05-31 - Drop-in replacement for builtin Go errors. This is a minimal error handling package with custom error types, user friendly messages, Unwrap & Is. With very easy to use and straightforward helper functions.
- [errors](https://github.com/cockroachdb/errors) ⭐ 1,944 📅 2023-08-31 - Go error library with error portability over the network.
- [errorx](https://github.com/joomcode/errorx) ⭐ 1,070 📅 2023-07-04 - A feature rich error package with stack traces, composition of errors and more.
- [exception](https://github.com/rbrahul/exception) ⭐ 27 📅 2022-11-21 - A simple utility package for exception handling with try-catch in Golang.
- [Falcon](https://github.com/SonicRoshan/falcon) ⭐ 10 📅 2019-09-20 - A Simple Yet Highly Powerful Package For Error Handling.
- [Fault](https://github.com/Southclaws/fault) ⭐ 149 📅 2023-10-24 - An ergonomic mechanism for wrapping errors in order to facilitate structured metadata and context for error values.
- [go-multierror](https://github.com/hashicorp/go-multierror) ⭐ 2,162 📅 2024-01-23 - Go (golang) package for representing a list of errors as a single error.
- [oops](https://github.com/samber/oops) ⭐ 162 📅 2024-03-13 - Error handling with context, stack trace and source fragments.
- [tracerr](https://github.com/ztrue/tracerr) ⭐ 898 📅 2023-05-21 - Golang errors with stack trace and source fragments.

**[⬆ back to top](#contents)**

## File Handling

_Libraries for handling files and file systems._

- [afero](https://github.com/spf13/afero) ⭐ 5,637 📅 2023-11-28 - FileSystem Abstraction System for Go.
- [afs](https://github.com/viant/afs) ⭐ 285 📅 2024-03-16 - Abstract File Storage (mem, scp, zip, tar, cloud: s3, gs) for Go.
- [baraka](https://github.com/xis/baraka) ⭐ 54 📅 2022-09-30 - A library to process http file uploads easily.
- [bigfile](https://github.com/bigfile/bigfile) ⭐ 247 📅 2019-09-30 - A file transfer system, support to manage files with http api, rpc call and ftp client.
- [checksum](https://github.com/codingsince1985/checksum) ⭐ 97 📅 2023-02-16 - Compute message digest, like MD5, SHA256, SHA1, CRC or BLAKE2s, for large files.
- [copy](https://github.com/otiai10/copy) ⭐ 663 📅 2024-03-06 - Copy directory recursively.
- [flop](https://github.com/homedepot/flop) ⭐ 34 📅 2021-12-07 - File operations library which aims to mirror feature parity with [GNU cp](https://www.gnu.org/software/coreutils/manual/html_node/cp-invocation.html).
- [gdu](https://github.com/dundee/gdu) ⭐ 3,173 📅 2024-03-04 - Disk usage analyzer with console interface.
- [go-csv-tag](https://github.com/artonge/go-csv-tag) ⭐ 112 📅 2024-01-19 - Load csv file using tag.
- [go-decent-copy](https://github.com/hugocarreira/go-decent-copy) ⭐ 21 📅 2020-01-03 - Copy files for humans.
- [go-exiftool](https://github.com/barasher/go-exiftool) ⭐ 220 📅 2023-06-07 - Go bindings for ExifTool, the well-known library used to extract as much metadata as possible (EXIF, IPTC, ...) from files (pictures, PDF, office, ...).
- [go-gtfs](https://github.com/artonge/go-gtfs) ⭐ 38 📅 2023-08-16 - Load gtfs files in go.
- [gofs](https://github.com/no-src/gofs) ⭐ 402 📅 2024-03-14 - A cross-platform real-time file synchronization tool out of the box.
- [gut/yos](https://github.com/1set/gut) ⭐ 28 📅 2020-11-17 - Simple and reliable package for file operations like copy/move/diff/list on files, directories and symbolic links.
- [higgs](https://github.com/dastoori/higgs) ⭐ 19 📅 2022-01-29 - A tiny cross-platform Go library to hide/unhide files and directories.
- [iso9660](https://github.com/kdomanski/iso9660) ⭐ 251 📅 2023-12-21 - A package for reading and creating ISO9660 disk images
- [notify](https://github.com/rjeczalik/notify) ⭐ 875 📅 2023-02-21 - File system event notification library with simple API, similar to os/signal.
- [opc](https://github.com/qmuntal/opc) ⭐ 75 📅 2023-12-01 - Load Open Packaging Conventions (OPC) files for Go.
- [parquet](https://github.com/parsyl/parquet) ⭐ 92 📅 2023-07-20 - Read and write [parquet](https://parquet.apache.org) files.
- [pathtype](https://github.com/jonchun/pathtype) ⭐ 13 📅 2021-08-12 - Treat paths as their own type instead of using strings.
- [pdfcpu](https://github.com/pdfcpu/pdfcpu) ⭐ 6,065 📅 2024-03-22 - PDF processor.
- [skywalker](https://github.com/dixonwille/skywalker) ⭐ 96 📅 2021-08-31 - Package to allow one to concurrently go through a filesystem with ease.
- [stl](https://gitlab.com/russoj88/stl) - Modules to read and write STL (stereolithography) files. Concurrent algorithm for reading.
- [todotxt](https://github.com/1set/todotxt) ⭐ 20 📅 2022-10-09 - Go library for Gina Trapani's [_todo.txt_](http://todotxt.org/) files, supports parsing and manipulating of task lists in the [_todo.txt_ format](https://github.com/todotxt/todo.txt).
- [vfs](https://github.com/C2FO/vfs) ⭐ 273 📅 2024-03-09 - A pluggable, extensible, and opinionated set of filesystem functionality for Go across a number of filesystem types such as os, S3, and GCS.

**[⬆ back to top](#contents)**

## Financial

_Packages for accounting and finance._

- [accounting](https://github.com/leekchan/accounting) ⭐ 857 📅 2022-01-06 - money and currency formatting for golang.
- [ach](https://github.com/moov-io/ach) ⭐ 426 📅 2024-03-21 - A reader, writer, and validator for Automated Clearing House (ACH) files.
- [bbgo](https://github.com/c9s/bbgo) ⭐ 1,089 📅 2024-03-22 - A crypto trading bot framework written in Go. Including common crypto exchange API, standard indicators, back-testing and many built-in strategies.
- [currency](https://github.com/bojanz/currency) ⭐ 489 📅 2023-11-19 - Handles currency amounts, provides currency information and formatting.
- [currency](https://github.com/bnkamalesh/currency) ⭐ 59 📅 2021-11-13 - High performant & accurate currency computation package.
- [decimal](https://github.com/shopspring/decimal) ⭐ 5,814 📅 2024-02-19 - Arbitrary-precision fixed-point decimal numbers.
- [decimal](https://github.com/govalues/decimal) ⭐ 24 📅 2024-03-04 - Immutable decimal numbers with panic-free arithmetic.
- [fpdecimal](https://github.com/nikolaydubina/fpdecimal) ⭐ 28 📅 2024-03-21 - Fast and precise serialization and arithmetic for small fixed-point decimals
- [fpmoney](https://github.com/nikolaydubina/fpmoney) ⭐ 24 📅 2024-03-21 - Fast and simple ISO4217 fixed-point decimal money.
- [go-finance](https://github.com/alpeb/go-finance) ⭐ 164 📅 2021-12-02 - Library of financial functions for time value of money (annuities), cash flow, interest rate conversions, bonds and depreciation calculations.
- [go-finance](https://github.com/pieterclaerhout/go-finance) ⭐ 25 📅 2024-03-04 - Module to fetch exchange rates, check VAT numbers via VIES and check IBAN bank account numbers.
- [go-finnhub](https://github.com/m1/go-finnhub) ⭐ 85 📅 2020-02-01 - Client for stock market, forex and crypto data from finnhub.io. Access real-time financial market data from 60+ stock exchanges, 10 forex brokers, and 15+ crypto exchanges.
- [go-money](https://github.com/rhymond/go-money) ⭐ 1,475 📅 2023-11-14 - Implementation of Fowler's Money pattern.
- [go-nowpayments](https://github.com/matm/go-nowpayments) ⭐ 2 📅 2023-01-24 - Library for the crypto NOWPayments API.
- [money](https://github.com/govalues/money) ⭐ 13 📅 2023-12-18 - Immutable monetary amounts and exchange rates with panic-free arithmetic.
- [ofxgo](https://github.com/aclindsa/ofxgo) ⭐ 129 📅 2023-03-15 - Query OFX servers and/or parse the responses (with example command-line client).
- [orderbook](https://github.com/i25959341/orderbook) ⭐ 393 📅 2023-07-04 - Matching Engine for Limit Order Book in Golang.
- [payme](https://github.com/jovandeginste/payme) ⭐ 81 📅 2024-03-02 - QR code generator (ASCII & PNG) for SEPA payments.
- [sleet](https://github.com/BoltApp/sleet) ⭐ 135 📅 2024-02-29 - One unified interface for multiple Payment Service Providers (PsP) to process online payment.
- [swift](https://code.pfad.fr/swift/) - Offline validity check of IBAN (International Bank Account Number) and retrieval of BIC (for some countries).
- [techan](https://github.com/sdcoffey/techan) ⭐ 785 📅 2021-11-17 - Technical analysis library with advanced market analysis and trading strategies.
- [ticker](https://github.com/achannarasappa/ticker) ⭐ 4,799 📅 2024-01-25 - Terminal stock watcher and stock position tracker.
- [transaction](https://github.com/claygod/transaction) ⭐ 127 📅 2024-02-03 - Embedded transactional database of accounts, running in multithreaded mode.
- [vat](https://github.com/dannyvankooten/vat) ⭐ 110 📅 2023-11-07 - VAT number validation & EU VAT rates.

**[⬆ back to top](#contents)**

## Forms

_Libraries for working with forms._

- [bind](https://github.com/robfig/bind) ⭐ 30 📅 2014-08-16 - Bind form data to any Go values.
- [binding](https://github.com/mholt/binding) ⭐ 795 📅 2017-09-17 - Binds form and JSON data from net/http Request to struct.
- [checker](https://github.com/cinar/checker) ⭐ 6 📅 2023-06-25 - Checker helps validating user input through rules defined in struct tags or directly through functions.
- [conform](https://github.com/leebenson/conform) ⭐ 316 📅 2023-12-23 - Keeps user input in check. Trims, sanitizes & scrubs data based on struct tags.
- [form](https://github.com/go-playground/form) ⭐ 686 📅 2023-07-13 - Decodes url.Values into Go value(s) and Encodes Go value(s) into url.Values. Dual Array and Full map support.
- [formam](https://github.com/monoculum/formam) ⭐ 183 📅 2022-11-06 - decode form's values into a struct.
- [forms](https://github.com/albrow/forms) ⭐ 137 📅 2022-12-16 - Framework-agnostic library for parsing and validating form/JSON data which supports multipart forms and files.
- [gbind](https://github.com/bdjimmy/gbind) ⭐ 8 📅 2022-06-14 - Bind data to any Go value. Can use built-in and custom expression binding capabilities; supports data validation
- [gorilla/csrf](https://github.com/gorilla/csrf) ⭐ 984 📅 2023-11-05 - CSRF protection for Go web applications & services.
- [httpin](https://github.com/ggicci/httpin) ⭐ 252 📅 2024-03-15 - Decode an HTTP request into a custom struct, including querystring, forms, HTTP headers, etc.
- [nosurf](https://github.com/justinas/nosurf) ⭐ 1,490 📅 2020-08-30 - CSRF protection middleware for Go.
- [qs](https://github.com/sonh/qs) ⭐ 71 📅 2024-03-05 - Go module for encoding structs into URL query parameters.
- [queryparam](https://github.com/tomwright/queryparam) ⭐ 19 📅 2020-09-23 - Decode `url.Values` into usable struct values of standard or custom types.

**[⬆ back to top](#contents)**

## Functional

_Packages to support functional programming in Go._

- [fp-go](https://github.com/repeale/fp-go) ⭐ 284 📅 2022-12-01 - Collection of Functional Programming helpers powered by Golang 1.18+ generics.
- [fpGo](https://github.com/TeaEntityLab/fpGo) ⭐ 337 📅 2023-11-10 - Monad, Functional Programming features for Golang.
- [fuego](https://github.com/seborama/fuego) ⭐ 142 📅 2023-03-16 - Functional Experiment in Go.
- [go-functional](https://github.com/BooleanCat/go-functional) ⭐ 280 📅 2024-02-12 - Functional programming in Go using generics
- [go-underscore](https://github.com/tobyhede/go-underscore) ⭐ 1,293 📅 2023-02-28 - Useful collection of helpfully functional Go collection utilities.
- [gofp](https://github.com/rbrahul/gofp) ⭐ 144 📅 2021-02-23 - A lodash like powerful utility library for Golang.
- [mo](https://github.com/samber/mo) ⭐ 2,191 📅 2023-10-15 - Monads and popular FP abstractions, based on Go 1.18+ Generics (Option, Result, Either...).
- [underscore](https://github.com/rjNemo/underscore) ⭐ 106 📅 2023-06-13 - Functional programming helpers for Go 1.18 and beyond.
- [valor](https://github.com/phelmkamp/valor) ⭐ 16 📅 2022-10-19 - Generic option and result types that optionally contain a value.

**[⬆ back to top](#contents)**

## Game Development

_Awesome game development libraries._

- [Azul3D](https://github.com/azul3d/engine) ⭐ 598 📅 2021-10-24 - 3D game engine written in Go.
- [Ebitengine](https://github.com/hajimehoshi/ebiten) ⭐ 9,655 📅 2024-03-22 - dead simple 2D game engine in Go.
- [engo](https://github.com/EngoEngine/engo) ⭐ 1,705 📅 2023-09-01 - Engo is an open-source 2D game engine written in Go. It follows the Entity-Component-System paradigm.
- [fantasyname](https://github.com/s0rg/fantasyname) ⭐ 31 📅 2023-11-21 - Fantasy names generator.
- [g3n](https://github.com/g3n/engine) ⭐ 2,613 📅 2023-12-22 - Go 3D Game Engine.
- [go-astar](https://github.com/beefsack/go-astar) ⭐ 580 📅 2020-08-27 - Go implementation of the A\* path finding algorithm.
- [go-sdl2](https://github.com/veandco/go-sdl2) ⭐ 2,117 📅 2024-02-29 - Go bindings for the [Simple DirectMedia Layer](https://www.libsdl.org/).
- [go3d](https://github.com/ungerik/go3d) ⭐ 287 📅 2022-03-09 - Performance oriented 2D/3D math package for Go.
- [gonet](https://github.com/xtaci/gonet) ⭐ 1,244 📅 2017-05-12 - Game server skeleton implemented with golang.
- [goworld](https://github.com/xiaonanln/goworld) ⭐ 2,488 📅 2022-08-13 - Scalable game server engine, featuring space-entity framework and hot-swapping.
- [Harfang3D](https://github.com/harfang3d/harfang3d) ⭐ 450 📅 2023-08-16 - 3D engine for the Go language, works on Windows and Linux ([Harfang on Go.dev](https://github.com/harfang3d/harfang-go) ⭐ 37 📅 2022-12-13).
- [Leaf](https://github.com/name5566/leaf) ⭐ 5,120 📅 2022-10-21 - Lightweight game server framework.
- [nano](https://github.com/lonng/nano) ⭐ 2,650 📅 2023-11-16 - Lightweight, facility, high performance golang based game server framework.
- [Oak](https://github.com/oakmound/oak) ⭐ 1,498 📅 2024-01-14 - Pure Go game engine.
- [Pitaya](https://github.com/topfreegames/pitaya) ⭐ 2,129 📅 2024-02-22 - Scalable game server framework with clustering support and client libraries for iOS, Android, Unity and others through the C SDK.
- [Pixel](https://github.com/faiface/pixel) ⭐ 4,384 📅 2023-10-09 - Hand-crafted 2D game library in Go.
- [prototype](https://github.com/gonutz/prototype) ⭐ 87 📅 2024-03-03 - Cross-platform (Windows/Linux/Mac) library for creating desktop games using a minimal API.
- [raylib-go](https://github.com/gen2brain/raylib-go) ⭐ 1,252 📅 2024-02-27 - Go bindings for [raylib](https://www.raylib.com/), a simple and easy-to-use library to learn videogames programming.
- [termloop](https://github.com/JoelOtter/termloop) ⭐ 1,393 📅 2021-08-06 - Terminal-based game engine for Go, built on top of Termbox.
- [tile](https://github.com/kelindar/tile) ⭐ 134 📅 2023-12-10 - Data-oriented and cache-friendly 2D Grid library (TileMap), includes pathfinding, observers and import/export.

**[⬆ back to top](#contents)**

## Generators

_Tools that generate Go code._

- [convergen](https://github.com/reedom/convergen) ⭐ 26 📅 2024-03-11 - Feature rich type-to-type copy code generator.
- [copygen](https://github.com/switchupcb/copygen) ⭐ 326 📅 2023-03-24 - Generate type-to-type and type-based code without reflection.
- [generis](https://github.com/senselogic/GENERIS) ⭐ 43 📅 2022-02-22 - Code generation tool providing generics, free-form macros, conditional compilation and HTML templating.
- [go-enum](https://github.com/abice/go-enum) ⭐ 637 📅 2023-12-23 - Code generation for enums from code comments.
- [go-linq](https://github.com/ahmetalpbalkan/go-linq) ⭐ 3,420 📅 2020-12-29 - .NET LINQ-like query methods for Go.
- [goderive](https://github.com/awalterschulze/goderive) ⭐ 1,161 📅 2024-03-09 - Derives functions from input types.
- [gotype](https://github.com/wzshiming/gotype) ⭐ 58 📅 2022-06-21 - Golang source code parsing, usage like reflect package.
- [goverter](https://github.com/jmattheis/goverter) ⭐ 425 📅 2024-02-23 - Generate converters by defining an interface.
- [GoWrap](https://github.com/hexdigest/gowrap) ⭐ 877 📅 2023-12-08 - Generate decorators for Go interfaces using simple templates.
- [interfaces](https://github.com/rjeczalik/interfaces) ⭐ 416 📅 2022-08-07 - Command line tool for generating interface definitions.
- [jennifer](https://github.com/dave/jennifer) ⭐ 3,153 📅 2023-08-21 - Generate arbitrary Go code without templates.
- [oapi-codegen](https://github.com/deepmap/oapi-codegen) ⭐ 5,054 📅 2024-02-25 - This package contains a set of utilities for generating Go boilerplate code for services based on OpenAPI 3.0 API definitions.
- [typeregistry](https://github.com/xiaoxin01/typeregistry) ⭐ 23 📅 2020-02-20 - A library to create type dynamically.

**[⬆ back to top](#contents)**

## Geographic

_Geographic tools and servers_

- [geoserver](https://github.com/hishamkaram/geoserver) ⭐ 85 📅 2023-02-28 - geoserver Is a Go Package For Manipulating a GeoServer Instance via the GeoServer REST API.
- [gismanager](https://github.com/hishamkaram/gismanager) ⭐ 51 📅 2018-10-30 - Publish Your GIS Data(Vector Data) to PostGIS and Geoserver.
- [godal](https://github.com/airbusgeo/godal) ⭐ 117 📅 2023-12-20 - Go wrapper for GDAL.
- [H3](https://github.com/uber/h3-go) ⭐ 273 📅 2023-03-23 - Go bindings for H3, a hierarchical hexagonal geospatial indexing system.
- [H3 GeoJSON](https://github.com/mmadfox/go-geojson2h3) ⭐ 3 📅 2022-05-11 - Conversion utilities between H3 indexes and GeoJSON.
- [H3GeoDist](https://github.com/mmadfox/go-h3geo-dist) ⭐ 2 📅 2022-05-11 - Distribution of Uber H3geo cells by virtual nodes.
- [mbtileserver](https://github.com/consbio/mbtileserver) ⭐ 588 📅 2024-01-17 - A simple Go-based server for map tiles stored in mbtiles format.
- [osm](https://github.com/paulmach/osm) ⭐ 334 📅 2024-01-10 - Library for reading, writing and working with OpenStreetMap data and APIs.
- [pbf](https://github.com/maguro/pbf) ⭐ 48 📅 2022-06-04 - OpenStreetMap PBF golang encoder/decoder.
- [S2 geojson](https://github.com/pantrif/s2-geojson) ⭐ 27 📅 2020-04-05 - Convert geojson to s2 cells & demonstrating some S2 geometry features on map.
- [S2 geometry](https://github.com/golang/geo) ⭐ 1,625 📅 2023-04-21 - S2 geometry library in Go.
- [simplefeatures](https://github.com/peterstace/simplefeatures) ⭐ 116 📅 2024-03-21 - simplesfeatures is a 2D geometry library that provides Go types that model geometries, as well as algorithms that operate on them.
- [Tile38](https://github.com/tidwall/tile38) ⭐ 8,866 📅 2024-02-15 - Geolocation DB with spatial index and realtime geofencing.
- [Web-Mercator-Projection](https://github.com/jorelosorio/web-mercator-projection) ⭐ 5 📅 2022-03-24 A project to easily use and convert LonLat, Point and Tile to display info, markers, etc, in a map using the Web Mercator Projection.
- [WGS84](https://github.com/wroge/wgs84) ⭐ 112 📅 2024-01-17 - Library for Coordinate Conversion and Transformation (ETRS89, OSGB36, NAD83, RGF93, Web Mercator, UTM).

**[⬆ back to top](#contents)**

## Go Compilers

_Tools for compiling Go to other languages._

- [c2go](https://github.com/goplus/c2go) ⭐ 303 📅 2024-03-08 - Convert C code to Go code.
- [c4go](https://github.com/Konstantin8105/c4go) ⭐ 352 📅 2023-08-16 - Transpile C code to Go code.
- [esp32](https://github.com/andygeiss/esp32-transpiler) ⭐ 81 📅 2023-04-24 - Transpile Go into Arduino code.
- [f4go](https://github.com/Konstantin8105/f4go) ⭐ 42 📅 2023-08-17 - Transpile FORTRAN 77 code to Go code.
- [gopherjs](https://github.com/gopherjs/gopherjs) ⭐ 12,345 📅 2024-03-14 - Compiler from Go to JavaScript.
- [tardisgo](https://github.com/tardisgo/tardisgo) ⭐ 429 📅 2016-11-19 - Golang to Haxe to CPP/CSharp/Java/JavaScript transpiler.

**[⬆ back to top](#contents)**

## Goroutines

_Tools for managing and working with Goroutines._

- [ants](https://github.com/panjf2000/ants) ⭐ 11,890 📅 2024-03-17 - A high-performance and low-cost goroutine pool in Go.
- [artifex](https://github.com/borderstech/artifex) ⭐ 184 📅 2020-08-17 - Simple in-memory job queue for Golang using worker-based dispatching.
- [async](https://github.com/reugn/async) ⭐ 174 📅 2024-03-16 - An alternative sync library for Go (Future, Promise, Locks).
- [async](https://github.com/studiosol/async) ⭐ 132 📅 2020-11-19 - A safe way to execute functions asynchronously, recovering them in case of panic.
- [async-job](https://github.com/lab210-dev/async-job) ⭐ 8 📅 2022-05-30 - AsyncJob is an asynchronous queue job manager with light code, clear and speed.
- [breaker](https://github.com/kamilsk/breaker) ⭐ 16 📅 2021-05-11 - Flexible mechanism to make execution flow interruptible.
- [channelify](https://github.com/ddelizia/channelify) ⭐ 29 📅 2020-10-06 - Transform your function to return channels for easy and powerful parallel processing.
- [conc](https://github.com/sourcegraph/conc) ⭐ 8,269 📅 2024-01-21 - `conc` is your toolbelt for structured concurrency in go, making common tasks easier and safer.
- [concurrency-limiter](https://github.com/vivek-ng/concurrency-limiter) ⭐ 17 📅 2022-12-29 - Concurrency limiter with support for timeouts , dynamic priority and context cancellation of goroutines.
- [conexec](https://github.com/ITcathyh/conexec) ⭐ 14 📅 2020-06-28 - A concurrent toolkit to help execute funcs concurrently in an efficient and safe way. It supports specifying the overall timeout to avoid blocking and uses goroutine pool to improve efficiency.
- [cyclicbarrier](https://github.com/marusama/cyclicbarrier) ⭐ 137 📅 2020-06-30 - CyclicBarrier for golang.
- [execpool](https://github.com/hexdigest/execpool) ⭐ 19 📅 2021-07-06 - A pool built around exec.Cmd that spins up a given number of processes in advance and attaches stdin and stdout to them when needed. Very similar to FastCGI or Apache Prefork MPM but works for any command.
- [flowmatic](https://github.com/carlmjohnson/flowmatic) ⭐ 235 📅 2023-11-07 - Structured concurrency made easy.
- [go-accumulator](https://github.com/nar10z/go-accumulator) ⭐ 6 📅 2024-01-22 - Solution for accumulation of events and their subsequent processing.
- [go-actor](https://github.com/vladopajic/go-actor) ⭐ 108 📅 2024-03-19 - A tiny library for writing concurrent programs using actor model.
- [go-floc](https://github.com/workanator/go-floc) ⭐ 265 📅 2021-08-10 - Orchestrate goroutines with ease.
- [go-flow](https://github.com/kamildrazkiewicz/go-flow) ⭐ 217 📅 2017-09-19 - Control goroutines execution order.
- [go-tools/multithreading](https://github.com/nikhilsaraf/go-tools) ⭐ 14 📅 2019-03-27 - Manage a pool of goroutines using this lightweight library with a simple API.
- [go-trylock](https://github.com/subchen/go-trylock) ⭐ 34 📅 2021-05-07 - TryLock support on read-write lock for Golang.
- [go-waitgroup](https://github.com/pieterclaerhout/go-waitgroup) ⭐ 44 📅 2024-03-05 - Like `sync.WaitGroup` with error handling and concurrency control.
- [go-workerpool](https://github.com/zenthangplus/go-workerpool) ⭐ 10 📅 2022-08-20 - Inspired from Java Thread Pool, Go WorkerPool aims to control heavy Go Routines.
- [go-workers](https://github.com/catmullet/go-workers) ⭐ 163 📅 2021-06-22 - Easily and safely run workers for large data processing pipelines.
- [goccm](https://github.com/zenthangplus/goccm) ⭐ 69 📅 2023-01-18 - Go Concurrency Manager package limits the number of goroutines that allowed to run concurrently.
- [gohive](https://github.com/loveleshsharma/gohive) ⭐ 51 📅 2023-11-19 - A highly performant and easy to use Goroutine pool for Go.
- [gollback](https://github.com/vardius/gollback) ⭐ 117 📅 2023-02-16 - asynchronous simple function utilities, for managing execution of closures and callbacks.
- [gowl](https://github.com/hamed-yousefi/gowl) ⭐ 65 📅 2023-10-19 - Gowl is a process management and process monitoring tool at once. An infinite worker pool gives you the ability to control the pool and processes and monitor their status.
- [goworker](https://github.com/benmanns/goworker) ⭐ 2,774 📅 2020-08-28 - goworker is a Go-based background worker.
- [gowp](https://github.com/xxjwxc/gowp) ⭐ 488 📅 2023-06-12 - gowp is concurrency limiting goroutine pool.
- [gpool](https://github.com/Sherifabdlnaby/gpool) ⭐ 88 📅 2019-12-16 - manages a resizeable pool of context-aware goroutines to bound concurrency.
- [grpool](https://github.com/ivpusic/grpool) ⭐ 740 📅 2017-08-04 - Lightweight Goroutine pool.
- [hands](https://github.com/duanckham/hands) ⭐ 10 📅 2022-04-05 - A process controller used to control the execution and return strategies of multiple goroutines.
- [Hunch](https://github.com/AaronJan/Hunch) ⭐ 97 📅 2022-05-24 - Hunch provides functions like: `All`, `First`, `Retry`, `Waterfall` etc., that makes asynchronous flow control more intuitive.
- [kyoo](https://github.com/dirkaholic/kyoo) ⭐ 47 📅 2023-02-21 - Provides an unlimited job queue and concurrent worker pools.
- [neilotoole/errgroup](https://github.com/neilotoole/errgroup) ⭐ 158 📅 2023-01-10 - Drop-in alternative to `sync/errgroup`, limited to a pool of N worker goroutines.
- [nursery](https://github.com/arunsworld/nursery) ⭐ 62 📅 2021-07-08 - Structured concurrency in Go.
- [oversight](https://pkg.go.dev/cirello.io/oversight) - Oversight is a complete implementation of the Erlang supervision trees.
- [parallel-fn](https://github.com/rafaeljesus/parallel-fn) ⭐ 36 📅 2018-01-01 - Run functions in parallel.
- [pond](https://github.com/alitto/pond) ⭐ 1,168 📅 2024-03-14 - Minimalistic and High-performance goroutine worker pool written in Go.
- [pool](https://github.com/go-playground/pool) ⭐ 723 📅 2016-08-23 - Limited consumer goroutine or unlimited goroutine pool for easier goroutine handling and cancellation.
- [queue](https://github.com/AnikHasibul/queue) ⭐ 15 📅 2019-05-18 - Gives you a `sync.WaitGroup` like queue group accessibility. Helps you to throttle and limit goroutines, wait for the end of the all goroutines and much more.
- [routine](https://github.com/timandy/routine) ⭐ 181 📅 2024-02-20 - `routine` is a `ThreadLocal` for go library. It encapsulates and provides some easy-to-use, non-competitive, high-performance `goroutine` context access interfaces, which can help you access coroutine context information more gracefully.
- [routine](https://github.com/x-mod/routine) ⭐ 60 📅 2024-01-11 - go routine control with context, support: Main, Go, Pool and some useful Executors.
- [semaphore](https://github.com/kamilsk/semaphore) ⭐ 96 📅 2020-04-16 - Semaphore pattern implementation with timeout of lock/unlock operations based on channel and context.
- [semaphore](https://github.com/marusama/semaphore) ⭐ 166 📅 2021-03-28 - Fast resizable semaphore implementation based on CAS (faster than channel-based semaphore implementations).
- [stl](https://github.com/ssgreg/stl) ⭐ 29 📅 2019-10-01 - Software transactional locks based on Software Transactional Memory (STM) concurrency control mechanism.
- [threadpool](https://github.com/shettyh/threadpool) ⭐ 96 📅 2020-03-23 - Golang threadpool implementation.
- [tunny](https://github.com/Jeffail/tunny) ⭐ 3,778 📅 2021-07-12 - Goroutine pool for golang.
- [worker-pool](https://github.com/vardius/worker-pool) ⭐ 90 📅 2021-01-17 - goworker is a Go simple async worker pool.
- [workerpool](https://github.com/gammazero/workerpool) ⭐ 1,237 📅 2022-08-12 - Goroutine pool that limits the concurrency of task execution, not the number of tasks queued.

**[⬆ back to top](#contents)**

## GUI

_Libraries for building GUI Applications._

_Toolkits_

- [app](https://github.com/murlokswarm/app) ⭐ 7,640 📅 2023-08-16 - Package to create apps with GO, HTML and CSS. Supports: MacOS, Windows in progress.
- [energy](https://github.com/energye/energy) ⭐ 250 📅 2024-03-18 - Cross-platform based on LCL(Native System UI Control Library) and CEF(Chromium Embedded Framework) (Windows/ macOS / Linux)
- [fyne](https://github.com/fyne-io/fyne) ⭐ 22,934 📅 2024-02-13 - Cross platform native GUIs designed for Go based on Material Design. Supports: Linux, macOS, Windows, BSD, iOS and Android.
- [gio](https://gioui.org) - Gio is a library for writing cross-platform immediate mode GUI-s in Go. Gio supports all the major platforms: Linux, macOS, Windows, Android, iOS, FreeBSD, OpenBSD and WebAssembly.
- [go-gtk](https://mattn.github.io/go-gtk/) - Go bindings for GTK.
- [go-sciter](https://github.com/sciter-sdk/go-sciter) ⭐ 2,563 📅 2022-04-03 - Go bindings for Sciter: the Embeddable HTML/CSS/script engine for modern desktop UI development. Cross platform.
- [Goey](https://bitbucket.org/rj/goey/src/master/) - Cross platform UI toolkit aggregator for Windows / Linux / Mac. GTK, Cocoa, Windows API
- [goradd/html5tag](https://github.com/goradd/html5tag) ⭐ 8 📅 2023-12-10 - Library for outputting HTML5 tags.
- [gotk3](https://github.com/gotk3/gotk3) ⭐ 2,010 📅 2024-03-06 - Go bindings for GTK3.
- [gowd](https://github.com/dtylman/gowd) ⭐ 416 📅 2022-08-07 - Rapid and simple desktop UI development with GO, HTML, CSS and NW.js. Cross platform.
- [qt](https://github.com/therecipe/qt) ⭐ 10,191 📅 2020-09-04 - Qt binding for Go (support for Windows / macOS / Linux / Android / iOS / Sailfish OS / Raspberry Pi).
- [ui](https://github.com/andlabs/ui) ⭐ 8,327 📅 2020-06-10 - Platform-native GUI library for Go. Cross platform.
- [unison](https://github.com/richardwilkes/unison) ⭐ 134 📅 2024-03-19 - A unified graphical user experience toolkit for Go desktop applications. macOS, Windows, and Linux are supported.
- [Wails](https://wails.io) - Mac, Windows, Linux desktop apps with HTML UI using built-in OS HTML renderer.
- [walk](https://github.com/lxn/walk) ⭐ 6,685 📅 2021-01-12 - Windows application library kit for Go.
- [webview](https://github.com/zserge/webview) ⭐ 11,941 📅 2024-02-27 - Cross-platform webview window with simple two-way JavaScript bindings (Windows / macOS / Linux).

_Interaction_

- [AppIndicator Go](https://github.com/gopherlibs/appindicator) ⭐ 4 📅 2022-07-24 - Go bindings for libappindicator3 C library.
- [gosx-notifier](https://github.com/deckarep/gosx-notifier) ⭐ 585 📅 2018-02-01 - OSX Desktop Notifications library for Go.
- [mac-activity-tracker](https://github.com/prashantgupta24/activity-tracker) ⭐ 27 📅 2023-10-13 - OSX library to notify about any (pluggable) activity on your machine.
- [mac-sleep-notifier](https://github.com/prashantgupta24/mac-sleep-notifier) ⭐ 30 📅 2019-06-17 - OSX Sleep/Wake notifications in golang.
- [robotgo](https://github.com/go-vgo/robotgo) ⭐ 9,166 📅 2024-02-23 - Go Native cross-platform GUI system automation. Control the mouse, keyboard and other.
- [systray](https://github.com/getlantern/systray) ⭐ 3,084 📅 2023-11-10 - Cross platform Go library to place an icon and menu in the notification area.
- [trayhost](https://github.com/shurcooL/trayhost) ⭐ 249 📅 2022-07-11 - Cross-platform Go library to place an icon in the host operating system's taskbar.
- [zenity](https://github.com/ncruces/zenity) ⭐ 613 📅 2024-03-04 - Cross-platform Go library and CLI to create simple dialogs that interact graphically with the user.

**[⬆ back to top](#contents)**

## Hardware

_Libraries, tools, and tutorials for interacting with hardware._

- [arduino-cli](https://github.com/arduino/arduino-cli) ⭐ 4,142 📅 2024-03-20 - Official Arduino CLI and library. Can run standalone, or be incorporated into larger Go projects.
- [emgo](https://github.com/ziutek/emgo) ⭐ 1,051 📅 2021-12-05 - Go-like language for programming embedded systems (e.g. STM32 MCU).
- [ghw](https://github.com/jaypipes/ghw) ⭐ 1,567 📅 2024-03-13 - Golang hardware discovery/inspection library.
- [go-osc](https://github.com/hypebeast/go-osc) ⭐ 187 📅 2022-03-08 - Open Sound Control (OSC) bindings for Go.
- [go-rpio](https://github.com/stianeikeland/go-rpio) ⭐ 2,120 📅 2021-12-02 - GPIO for Go, doesn't require cgo.
- [goroslib](https://github.com/aler9/goroslib) ⭐ 296 📅 2024-03-19 - Robot Operating System (ROS) library for Go.
- [joystick](https://github.com/0xcafed00d/joystick) ⭐ 54 📅 2022-09-11 - a polled API to read the state of an attached joystick.
- [sysinfo](https://github.com/zcalusic/sysinfo) ⭐ 490 📅 2023-10-20 - A pure Go library providing Linux OS / kernel / hardware system information.

**[⬆ back to top](#contents)**

## Images

_Libraries for manipulating images._

- [bild](https://github.com/anthonynsimon/bild) ⭐ 3,899 📅 2022-06-14 - Collection of image processing algorithms in pure Go.
- [bimg](https://github.com/h2non/bimg) ⭐ 2,512 📅 2024-03-08 - Small package for fast and efficient image processing using libvips.
- [cameron](https://github.com/aofei/cameron) ⭐ 112 📅 2022-08-04 - An avatar generator for Go.
- [canvas](https://github.com/tdewolff/canvas) ⭐ 1,408 📅 2024-03-13 - Vector graphics to PDF, SVG or rasterized image.
- [color-extractor](https://github.com/marekm4/color-extractor) ⭐ 78 📅 2023-07-19 - Dominant color extractor with no external dependencies.
- [darkroom](https://github.com/gojek/darkroom) ⭐ 224 📅 2023-10-02 - An image proxy with changeable storage backends and image processing engines with focus on speed and resiliency.
- [draft](https://github.com/lucasepe/draft) ⭐ 576 📅 2021-09-08 - Generate High Level Microservice Architecture diagrams for GraphViz using simple YAML syntax.
- [geopattern](https://github.com/pravj/geopattern) ⭐ 1,260 📅 2017-05-09 - Create beautiful generative image patterns from a string.
- [gg](https://github.com/fogleman/gg) ⭐ 4,247 📅 2021-09-28 - 2D rendering in pure Go.
- [gift](https://github.com/disintegration/gift) ⭐ 1,714 📅 2020-11-21 - Package of image processing filters.
- [gltf](https://github.com/qmuntal/gltf) ⭐ 230 📅 2024-01-16 - Efficient and robust glTF 2.0 reader, writer and validator.
- [go-cairo](https://github.com/ungerik/go-cairo) ⭐ 139 📅 2024-03-04 - Go binding for the cairo graphics library.
- [go-gd](https://github.com/bolknote/go-gd) ⭐ 59 📅 2018-05-07 - Go binding for GD library.
- [go-nude](https://github.com/koyachi/go-nude) ⭐ 397 📅 2015-04-10 - Nudity detection with Go.
- [go-webcolors](https://github.com/jyotiska/go-webcolors) ⭐ 27 📅 2015-08-21 - Port of webcolors library from Python to Go.
- [go-webp](https://github.com/kolesa-team/go-webp) ⭐ 193 📅 2023-03-02 - Library for encode and decode webp pictures, using libwebp.
- [gocv](https://github.com/hybridgroup/gocv) ⭐ 6,190 📅 2023-10-12 - Go package for computer vision using OpenCV 3.3+.
- [goimagehash](https://github.com/corona10/goimagehash) ⭐ 687 📅 2024-01-21 - Go Perceptual image hashing package.
- [goimghdr](https://github.com/corona10/goimghdr) ⭐ 40 📅 2019-06-14 - The imghdr module determines the type of image contained in a file for Go.
- [govatar](https://github.com/o1egl/govatar) ⭐ 578 📅 2022-07-29 - Library and CMD tool for generating funny avatars.
- [govips](https://github.com/davidbyttow/govips) ⭐ 1,107 📅 2024-03-18 - A lightning fast image processing and resizing library for Go.
- [gowitness](https://github.com/sensepost/gowitness) ⭐ 2,639 📅 2024-03-19 - Screenshoting webpages using go and headless chrome on command line.
- [gridder](https://github.com/shomali11/gridder) ⭐ 73 📅 2021-09-30 - A Grid based 2D Graphics library.
- [image2ascii](https://github.com/qeesung/image2ascii) ⭐ 823 📅 2022-07-14 - Convert image to ASCII.
- [imagick](https://github.com/gographics/imagick) ⭐ 1,680 📅 2024-02-29 - Go binding to ImageMagick's MagickWand C API.
- [imaginary](https://github.com/h2non/imaginary) ⭐ 5,289 📅 2023-11-28 - Fast and simple HTTP microservice for image resizing.
- [imaging](https://github.com/disintegration/imaging) ⭐ 5,032 📅 2020-12-18 - Simple Go image processing package.
- [img](https://github.com/hawx/img) ⭐ 151 📅 2015-05-01 - Selection of image manipulation tools.
- [ln](https://github.com/fogleman/ln) ⭐ 3,228 📅 2017-02-23 - 3D line art rendering in Go.
- [mergi](https://github.com/noelyahan/mergi) ⭐ 222 📅 2019-05-14 - Tool & Go library for image manipulation (Merge, Crop, Resize, Watermark, Animate).
- [mort](https://github.com/aldor007/mort) ⭐ 499 📅 2023-05-22 - Storage and image processing server written in Go.
- [mpo](https://github.com/donatj/mpo) ⭐ 14 📅 2023-04-13 - Decoder and conversion tool for MPO 3D Photos.
- [picfit](https://github.com/thoas/picfit) ⭐ 1,990 📅 2024-03-21 - An image resizing server written in Go.
- [pt](https://github.com/fogleman/pt) ⭐ 2,065 📅 2017-06-19 - Path tracing engine written in Go.
- [rez](https://github.com/bamiaux/rez) ⭐ 210 📅 2017-07-31 - Image resizing in pure Go and SIMD.
- [scout](https://github.com/jonoton/scout) ⭐ 13 📅 2023-01-07 - Scout is a standalone open source software solution for DIY video security.
- [smartcrop](https://github.com/muesli/smartcrop) ⭐ 1,786 📅 2023-03-16 - Finds good crops for arbitrary images and crop sizes.
- [steganography](https://github.com/auyer/steganography) ⭐ 290 📅 2023-04-19 - Pure Go Library for LSB steganography.
- [stegify](https://github.com/DimitarPetrov/stegify) ⭐ 1,161 📅 2023-04-11 - Go tool for LSB steganography, capable of hiding any file within an image.
- [svgo](https://github.com/ajstarks/svgo) ⭐ 2,097 📅 2021-10-24 - Go Language Library for SVG generation.
- [tga](https://github.com/ftrvxmtrx/tga) ⭐ 34 📅 2015-05-24 - Package tga is a TARGA image format decoder/encoder.
- [transformimgs](https://github.com/Pixboost/transformimgs) ⭐ 179 📅 2024-03-18 - Transformimgs resizes and optimises images for Web using next-generation formats.
- [webp-server](https://github.com/mehdipourfar/webp-server) ⭐ 72 📅 2021-01-14 - Simple and minimal image server capable of storing, resizing, converting and caching images.

**[⬆ back to top](#contents)**

## IoT (Internet of Things)

_Libraries for programming devices of the IoT._

- [connectordb](https://github.com/connectordb/connectordb) ⭐ 393 📅 2022-06-27 - Open-Source Platform for Quantified Self & IoT.
- [devices](https://github.com/goiot/devices) ⭐ 264 📅 2016-07-08 - Suite of libraries for IoT devices, experimental for x/exp/io.
- [ekuiper](https://github.com/lf-edge/ekuiper) ⭐ 1,329 📅 2024-03-22 - Lightweight data stream processing engine for IoT edge.
- [eywa](https://github.com/xcodersun/eywa) ⭐ 61 📅 2017-04-12 - Project Eywa is essentially a connection manager that keeps track of connected devices.
- [flogo](https://github.com/tibcosoftware/flogo) ⭐ 2,365 📅 2022-08-09 - Project Flogo is an Open Source Framework for IoT Edge Apps & Integration.
- [gatt](https://github.com/paypal/gatt) ⭐ 1,104 📅 2015-10-11 - Gatt is a Go package for building Bluetooth Low Energy peripherals.
- [gobot](https://github.com/hybridgroup/gobot/) ⭐ 8,690 📅 2024-01-07 - Gobot is a framework for robotics, physical computing, and the Internet of Things.
- [huego](https://github.com/amimof/huego) ⭐ 246 📅 2023-06-30 - An extensive Philips Hue client library for Go.
- [iot](https://github.com/vaelen/iot/) ⭐ 65 📅 2019-11-08 - IoT is a simple framework for implementing a Google IoT Core device.
- [mainflux](https://github.com/Mainflux/mainflux) ⭐ 21 📅 2023-12-14 - Industrial IoT Messaging and Device Management Server.
- [periph](https://periph.io/) - Peripherals I/O to interface with low-level board facilities.
- [sensorbee](https://github.com/sensorbee/sensorbee) ⭐ 228 📅 2019-11-04 - Lightweight stream processing engine for IoT.

**[⬆ back to top](#contents)**

## Job Scheduler

_Libraries for scheduling jobs._

- [cdule](https://github.com/deepaksinghvi/cdule) ⭐ 45 📅 2022-11-27 - Job scheduler library with database support
- [cheek](https://github.com/datarootsio/cheek) ⭐ 117 📅 2024-02-01 - A simple crontab like scheduler that aims to offer a KISS approach to job scheduling.
- [clockwerk](https://github.com/onatm/clockwerk) ⭐ 141 📅 2019-09-10 - Go package to schedule periodic jobs using a simple, fluent syntax.
- [cronticker](https://github.com/krayzpipes/cronticker) ⭐ 12 📅 2021-01-02 - A ticker implementation to support cron schedules.
- [Dagu](https://github.com/dagu-go/dagu) ⭐ 1,114 📅 2024-03-19 - No-code workflow executor. it executes DAGs defined in a simple YAML format.
- [go-cron](https://github.com/rk/go-cron) ⭐ 224 📅 2020-02-10 - Simple Cron library for go that can execute closures or functions at varying intervals, from once a second to once a year on a specific date and time. Primarily for web applications and long running daemons.
- [go-dag](https://github.com/rhosocial/go-dag) ⭐ 3 📅 2024-02-19 - A framework developed in Go that manages the execution of workflows described by directed acyclic graphs.
- [go-quartz](https://github.com/reugn/go-quartz) ⭐ 1,630 📅 2024-03-18 - Simple, zero-dependency scheduling library for Go.
- [gocron](https://github.com/go-co-op/gocron) ⭐ 4,786 📅 2024-03-12 - Easy and fluent Go job scheduling. This is an actively maintained fork of [jasonlvhit/gocron](https://github.com/jasonlvhit/gocron) ⭐ 3,358 📅 2021-08-23.
- [goflow](https://github.com/fieldryand/goflow) ⭐ 256 📅 2024-03-14 - A simple but powerful DAG scheduler and dashboard.
- [gron](https://github.com/roylee0704/gron) ⭐ 1,009 📅 2016-06-21 - Define time-based tasks using a simple Go API and Gron’s scheduler will run them accordingly.
- [gronx](https://github.com/adhocore/gronx) ⭐ 360 📅 2024-03-22 - Cron expression parser, task runner and daemon consuming crontab like task list.
- [JobRunner](https://github.com/bamzi/jobrunner) ⭐ 1,009 📅 2019-10-10 - Smart and featureful cron job scheduler with job queuing and live monitoring built in.
- [jobs](https://github.com/albrow/jobs) ⭐ 494 📅 2017-12-14 - Persistent and flexible background jobs library.
- [leprechaun](https://github.com/kilgaloon/leprechaun) ⭐ 101 📅 2022-07-12 - Job scheduler that supports webhooks, crons and classic scheduling.
- [sched](https://github.com/romshark/sched) ⭐ 28 📅 2021-07-09 - A job scheduler with the ability to fast-forward time.
- [scheduler](https://github.com/carlescere/scheduler) ⭐ 440 📅 2017-01-09 - Cronjobs scheduling made easy.
- [tasks](https://github.com/madflojo/tasks) ⭐ 240 📅 2024-03-16 - An easy to use in-process scheduler for recurring tasks in Go.

**[⬆ back to top](#contents)**

## JSON

_Libraries for working with JSON._

- [ajson](https://github.com/spyzhov/ajson) ⭐ 209 📅 2024-03-14 - Abstract JSON for golang with JSONPath support.
- [ask](https://github.com/simonnilsson/ask) ⭐ 36 📅 2023-08-28 - Easy access to nested values in maps and slices. Works in combination with encoding/json and other packages that "Unmarshal" arbitrary data into Go data-types.
- [dynjson](https://github.com/cocoonspace/dynjson) ⭐ 16 📅 2021-10-11 - Client-customizable JSON formats for dynamic APIs.
- [ej](https://github.com/lucassscaravelli/ej) ⭐ 10 📅 2020-04-07 - Write and read JSON from different sources succinctly.
- [epoch](https://github.com/vtopc/epoch) ⭐ 14 📅 2024-02-25 - Contains primitives for marshaling/unmarshalling Unix timestamp/epoch to/from build-in time.Time type in JSON.
- [fastjson](https://github.com/valyala/fastjson) ⭐ 2,137 📅 2022-12-29 - Fast JSON parser and validator for Go. No custom structs, no code generation, no reflection.
- [gabs](https://github.com/Jeffail/gabs) ⭐ 3,344 📅 2023-02-14 - For parsing, creating and editing unknown or dynamic JSON in Go.
- [gjo](https://github.com/skanehira/gjo) ⭐ 123 📅 2020-04-23 - Small utility to create JSON objects.
- [GJSON](https://github.com/tidwall/gjson) ⭐ 13,484 📅 2024-02-15 - Get a JSON value with one line of code.
- [go-jsonerror](https://github.com/ddymko/go-jsonerror) ⭐ 15 📅 2019-10-03 - Go-JsonError is meant to allow us to easily create json response errors that follow the JsonApi spec.
- [go-respond](https://github.com/nicklaw5/go-respond) ⭐ 53 📅 2021-09-24 - Go package for handling common HTTP JSON responses.
- [gojmapr](https://github.com/limiu82214/gojmapr) ⭐ 22 📅 2023-06-21 - Get simple struct from complex json by json path.
- [gojq](https://github.com/elgs/gojq) ⭐ 192 📅 2023-06-28 - JSON query in Golang.
- [gojson](https://github.com/ChimeraCoder/gojson) ⭐ 2,637 📅 2018-08-18 - Automatically generate Go (golang) struct definitions from example JSON.
- [htmljson](https://github.com/nikolaydubina/htmljson) ⭐ 7 📅 2024-03-21 - Rich rendering of JSON as HTML in Go.
- [JayDiff](https://github.com/yazgazan/jaydiff) ⭐ 105 📅 2024-03-05 - JSON diff utility written in Go.
- [jettison](https://github.com/wI2L/jettison) ⭐ 168 📅 2023-01-06 - Fast and flexible JSON encoder for Go.
- [jscan](https://github.com/romshark/jscan) ⭐ 84 📅 2024-01-18 - High performance zero-allocation JSON iterator.
- [JSON-to-Go](https://mholt.github.io/json-to-go/) - Convert JSON to Go struct.
- [JSON-to-Proto](https://json-to-proto.github.io/) - Convert JSON to Protobuf online.
- [json2go](https://github.com/m-zajac/json2go) ⭐ 127 📅 2021-05-03 - Advanced JSON to Go struct conversion. Provides package that can parse multiple JSON documents and create struct to fit them all.
- [jsonapi-errors](https://github.com/AmuzaTkts/jsonapi-errors) ⭐ 14 📅 2016-11-17 - Go bindings based on the JSON API errors reference.
- [jsoncolor](https://github.com/neilotoole/jsoncolor) ⭐ 43 📅 2023-11-15 - Drop-in replacement for `encoding/json` that outputs colorized JSON.
- [jsondiff](https://github.com/wI2L/jsondiff) ⭐ 381 📅 2024-03-06 - JSON diff library for Go based on RFC6902 (JSON Patch).
- [jsonf](https://github.com/miolini/jsonf) ⭐ 65 📅 2020-12-13 - Console tool for highlighted formatting and struct query fetching JSON.
- [jsongo](https://github.com/ricardolonga/jsongo) ⭐ 109 📅 2016-12-15 - Fluent API to make it easier to create Json objects.
- [jsonhal](https://github.com/RichardKnop/jsonhal) ⭐ 14 📅 2018-11-01 - Simple Go package to make custom structs marshal into HAL compatible JSON responses.
- [jsonhandlers](https://github.com/abusomani/jsonhandlers) ⭐ 2 📅 2023-03-09 - JSON library to expose simple handlers that lets you easily read and write json from various sources.
- [jsonic](https://github.com/sinhashubham95/jsonic) ⭐ 11 📅 2021-01-15 - Utilities to handle and query JSON without defining structs in a type safe manner.
- [jsonvalue](https://github.com/Andrew-M-C/go.jsonvalue) - A fast and convenient library for unstructured JSON data, replacing `encoding/json`.
- [jzon](https://github.com/zerosnake0/jzon) ⭐ 12 📅 2022-08-02 - JSON library with standard compatible API/behavior.
- [kazaam](https://github.com/Qntfy/kazaam) ⭐ 274 📅 2021-07-05 - API for arbitrary transformation of JSON documents.
- [mapslice-json](https://github.com/mickep76/mapslice-json) ⭐ 17 📅 2021-07-20 - Go MapSlice for ordered marshal/ unmarshal of maps in JSON.
- [marshmallow](https://github.com/PerimeterX/marshmallow) ⭐ 347 📅 2023-07-03 - Performant JSON unmarshalling for flexible use cases.
- [mp](https://github.com/sanbornm/mp) ⭐ 47 📅 2016-05-11 - Simple cli email parser. It currently takes stdin and outputs JSON.
- [OjG](https://github.com/ohler55/ojg) ⭐ 775 📅 2024-02-29 - Optimized JSON for Go is a high performance parser with a variety of additional JSON tools including JSONPath.
- [omg.jsonparser](https://github.com/dedalqq/omg.jsonparser) - Simple JSON parser with validation by condition via golang struct fields tags.
- [ujson](https://github.com/olvrng/ujson) ⭐ 75 📅 2024-02-16 - Fast and minimal JSON parser and transformer that works on unstructured JSON.
- [vjson](https://github.com/miladibra10/vjson) ⭐ 39 📅 2022-10-18 - Go package for validating JSON objects with declaring a JSON schema with fluent API.

**[⬆ back to top](#contents)**

## Logging

_Libraries for generating and working with log files._

- [distillog](https://github.com/amoghe/distillog) ⭐ 32 📅 2018-07-26 - distilled levelled logging (think of it as stdlib + log levels).
- [glg](https://github.com/kpango/glg) ⭐ 189 📅 2023-09-27 - glg is simple and fast leveled logging library for Go.
- [glo](https://github.com/lajosbencz/glo) ⭐ 15 📅 2019-01-23 - PHP Monolog inspired logging facility with identical severity levels.
- [glog](https://github.com/golang/glog) ⭐ 3,507 📅 2023-11-22 - Leveled execution logs for Go.
- [go-cronowriter](https://github.com/utahta/go-cronowriter) ⭐ 56 📅 2020-11-25 - Simple writer that rotate log files automatically based on current date and time, like cronolog.
- [go-log](https://github.com/pieterclaerhout/go-log) ⭐ 10 📅 2024-03-04 - A logging library with stack traces, object dumping and optional timestamps.
- [go-log](https://github.com/subchen/go-log) ⭐ 14 📅 2018-05-19 - Simple and configurable Logging in Go, with level, formatters and writers.
- [go-log](https://github.com/siddontang/go-log) ⭐ 33 📅 2019-02-21 - Log lib supports level and multi handlers.
- [go-log](https://github.com/ian-kent/go-log) ⭐ 42 📅 2016-01-13 - Log4j implementation in Go.
- [go-logger](https://github.com/apsdehal/go-logger) ⭐ 286 📅 2019-05-15 - Simple logger of Go Programs, with level handlers.
- [gologger](https://github.com/sadlil/gologger) ⭐ 42 📅 2018-01-31 - Simple easy to use log lib for go, logs in Colored Console, Simple Console, File or Elasticsearch.
- [gomol](https://github.com/aphistic/gomol) ⭐ 19 📅 2019-03-14 - Multiple-output, structured logging for Go with extensible logging outputs.
- [gone/log](https://github.com/One-com/gone/tree/master/log) - Fast, extendable, full-featured, std-lib source compatible log library.
- [httpretty](https://github.com/henvic/httpretty) ⭐ 385 📅 2023-11-14 - Pretty-prints your regular HTTP requests on your terminal for debugging (similar to http.DumpRequest).
- [journald](https://github.com/ssgreg/journald) ⭐ 38 📅 2021-03-05 - Go implementation of systemd Journal's native API for logging.
- [kemba](https://github.com/clok/kemba) ⭐ 11 📅 2024-01-11 - A tiny debug logging tool inspired by [debug](https://github.com/visionmedia/debug) ⭐ 10,962 📅 2023-06-04, great for CLI tools and applications.
- [log](https://github.com/aerogo/log) ⭐ 10 📅 2019-10-26 - An O(1) logging system that allows you to connect one log to multiple writers (e.g. stdout, a file and a TCP connection).
- [log](https://github.com/apex/log) ⭐ 1,345 📅 2020-08-18 - Structured logging package for Go.
- [log](https://github.com/go-playground/log) ⭐ 290 📅 2023-08-17 - Simple, configurable and scalable Structured Logging for Go.
- [log](https://github.com/teris-io/log) ⭐ 26 📅 2017-12-04 - Structured log interface for Go cleanly separates logging facade from its implementation.
- [log](https://github.com/heartwilltell/log) ⭐ 15 📅 2022-12-06 - Simple leveled logging wrapper around standard log package.
- [log](https://github.com/no-src/log) ⭐ 3 📅 2024-03-12 - A simple logging framework out of the box.
- [log-voyage](https://github.com/firstrow/logvoyage) ⭐ 94 📅 2017-05-24 - Full-featured logging saas written in golang.
- [log15](https://github.com/inconshreveable/log15) ⭐ 1,100 📅 2022-11-22 - Simple, powerful logging for Go.
- [logdump](https://github.com/ewwwwwqm/logdump) ⭐ 11 📅 2018-04-02 - Package for multi-level logging.
- [logex](https://github.com/chzyer/logex) ⭐ 43 📅 2022-04-24 - Golang log lib, supports tracking and level, wrap by standard log lib.
- [logger](https://github.com/azer/logger) ⭐ 158 📅 2021-11-22 - Minimalistic logging library for Go.
- [logmatic](https://github.com/borderstech/logmatic) ⭐ 16 📅 2020-08-18 - Colorized logger for Golang with dynamic log level configuration.
- [logo](https://github.com/mbndr/logo) ⭐ 11 📅 2020-12-27 - Golang logger to different configurable writers.
- [logrus](https://github.com/Sirupsen/logrus) ⭐ 23,918 📅 2023-06-06 - Structured logger for Go.
- [logrusiowriter](https://github.com/cabify/logrusiowriter) ⭐ 16 📅 2020-07-15 - `io.Writer` implementation using [logrus](https://github.com/sirupsen/logrus) ⭐ 23,918 📅 2023-06-06 ⭐ 23,918 📅 2023-06-06 ⭐ 23,918 📅 2023-06-06 logger.
- [logrusly](https://github.com/sebest/logrusly) ⭐ 28 📅 2018-03-15 - [logrus](https://github.com/sirupsen/logrus) ⭐ 23,918 📅 2023-06-06 ⭐ 23,918 📅 2023-06-06 ⭐ 23,918 📅 2023-06-06 plug-in to send errors to a [Loggly](https://www.loggly.com/).
- [logur](https://github.com/logur/logur) ⭐ 196 📅 2020-10-04 - An opinionated logger interface and collection of logging best practices with adapters and integrations for well-known libraries ([logrus](https://github.com/sirupsen/logrus) ⭐ 23,918 📅 2023-06-06 ⭐ 23,918 📅 2023-06-06 ⭐ 23,918 📅 2023-06-06, [go-kit log](https://github.com/go-kit/kit/tree/master/log), [zap](https://github.com/uber-go/zap) ⭐ 20,717 📅 2024-03-07 ⭐ 20,717 📅 2024-03-07, [zerolog](https://github.com/rs/zerolog) ⭐ 9,634 📅 2024-03-06 ⭐ 9,634 📅 2024-03-06, etc).
- [logutils](https://github.com/hashicorp/logutils) ⭐ 364 📅 2023-01-25 - Utilities for slightly better logging in Go (Golang) extending the standard logger.
- [logxi](https://github.com/mgutz/logxi) ⭐ 352 📅 2016-10-27 - 12-factor app logger that is fast and makes you happy.
- [lumberjack](https://github.com/natefinch/lumberjack) ⭐ 4,564 📅 2023-02-06 - Simple rolling logger, implements io.WriteCloser.
- [mlog](https://github.com/jbrodriguez/mlog) ⭐ 33 📅 2018-08-05 - Simple logging module for go, with 5 levels, an optional rotating logfile feature and stdout/stderr output.
- [noodlog](https://github.com/gyozatech/noodlog) ⭐ 44 📅 2023-04-19 - Parametrized JSON logging library which lets you obfuscate sensitive data and marshal any kind of content. No more printed pointers instead of values, nor escape chars for the JSON strings.
- [onelog](https://github.com/francoispqt/onelog) ⭐ 415 📅 2019-03-06 - Onelog is a dead simple but very efficient JSON logger. It is the fastest JSON logger out there in all scenarios. Also, it is one of the logger with the lowest allocation.
- [ozzo-log](https://github.com/go-ozzo/ozzo-log) ⭐ 122 📅 2016-07-03 - High performance logging supporting log severity, categorization, and filtering. Can send filtered log messages to various targets (e.g. console, network, mail).
- [phuslu/log](https://github.com/phuslu/log) ⭐ 549 📅 2024-03-10 - High performance structured logging.
- [pp](https://github.com/k0kubun/pp) ⭐ 1,775 📅 2023-03-02 - Colored pretty printer for Go language.
- [rollingwriter](https://github.com/arthurkiller/rollingWriter) ⭐ 292 📅 2023-10-16 - RollingWriter is an auto-rotate `io.Writer` implementation with multi policies to provide log file rotation.
- [seelog](https://github.com/cihub/seelog) ⭐ 1,639 📅 2017-01-30 - Logging functionality with flexible dispatching, filtering, and formatting.
- [slf4g](https://github.com/echocat/slf4g) ⭐ 3 📅 2024-03-05 - Simple Logging Facade for Golang: Simple structured logging; but powerful, extendable and customizable, with huge amount of learnings from decades of past logging frameworks.
- [slog](https://github.com/gookit/slog) ⭐ 346 📅 2024-03-12 - Lightweight, configurable, extensible logger for Go.
- [slog-formatter](https://github.com/samber/slog-formatter) ⭐ 79 📅 2024-01-21 - Common formatters for slog and helpers to build your own.
- [slog-multi](https://github.com/samber/slog-multi) ⭐ 233 📅 2024-01-21 - Chain of slog.Handler (pipeline, fanout...).
- [spew](https://github.com/davecgh/go-spew) ⭐ 5,884 📅 2018-08-30 - Implements a deep pretty printer for Go data structures to aid in debugging.
- [sqldb-logger](https://github.com/simukti/sqldb-logger) ⭐ 334 📅 2023-01-08 - A logger for Go SQL database driver without modify existing \*sql.DB stdlib usage.
- [stdlog](https://github.com/alexcesaro/log) ⭐ 47 📅 2015-09-15 - Stdlog is an object-oriented library providing leveled logging. It is very useful for cron jobs.
- [structy/log](https://github.com/structy/log) ⭐ 5 📅 2022-01-26 - A simple to use log system, minimalist but with features for debugging and differentiation of messages.
- [tail](https://github.com/hpcloud/tail) ⭐ 2,665 📅 2018-05-14 - Go package striving to emulate the features of the BSD tail program.
- [tint](https://github.com/lmittmann/tint) ⭐ 568 📅 2024-01-18 - A slog.Handler that writes tinted logs.
- [xlog](https://github.com/xfxdev/xlog) ⭐ 8 📅 2019-01-15 - Plugin architecture and flexible log system for Go, with level ctrl, multiple log target and custom log format.
- [xlog](https://github.com/rs/xlog) ⭐ 138 📅 2017-12-27 - Structured logger for `net/context` aware HTTP handlers with flexible dispatching.
- [xylog](https://github.com/xybor-x/xylog) ⭐ 15 📅 2023-01-13 - Leveled and structured logging, dynamic fields, high performance, zone management, simple configuration, and readable syntax.
- [yell](https://github.com/jfcg/yell) ⭐ 1 📅 2022-02-24 - Yet another minimalistic logging library.
- [zap](https://github.com/uber-go/zap) ⭐ 20,717 📅 2024-03-07 ⭐ 20,717 📅 2024-03-07 - Fast, structured, leveled logging in Go.
- [zax](https://github.com/yuseferi/zax) ⭐ 17 📅 2024-02-26 - Integrate Context with Zap logger, which leads to more flexibility in Go logging.
- [zerolog](https://github.com/rs/zerolog) ⭐ 9,634 📅 2024-03-06 ⭐ 9,634 📅 2024-03-06 - Zero-allocation JSON logger.
- [zkits-logger](https://github.com/edoger/zkits-logger) ⭐ 25 📅 2023-05-19 - A powerful zero-dependency JSON logger.
- [zl](https://github.com/nkmr-jp/zl) ⭐ 5 📅 2024-02-24 - High Developer Experience, zap based logger. It offers rich functionality but is easy to configure.

**[⬆ back to top](#contents)**

## Machine Learning

_Libraries for Machine Learning._

- [bayesian](https://github.com/jbrukh/bayesian) ⭐ 784 📅 2023-11-17 - Naive Bayesian Classification for Golang.
- [CloudForest](https://github.com/ryanbressler/CloudForest) ⭐ 735 📅 2022-02-05 - Fast, flexible, multi-threaded ensembles of decision trees for machine learning in pure Go.
- [ddt](https://github.com/sgrodriguez/ddt) ⭐ 34 📅 2021-01-25 - Dynamic decision tree, create trees defining customizable rules.
- [eaopt](https://github.com/MaxHalford/eaopt) ⭐ 872 📅 2024-03-07 - An evolutionary optimization library.
- [evoli](https://github.com/khezen/evoli) ⭐ 29 📅 2021-10-27 - Genetic Algorithm and Particle Swarm Optimization library.
- [fonet](https://github.com/Fontinalis/fonet) ⭐ 80 📅 2021-06-01 - A Deep Neural Network library written in Go.
- [go-cluster](https://github.com/e-XpertSolutions/go-cluster) ⭐ 39 📅 2022-11-29 - Go implementation of the k-modes and k-prototypes clustering algorithms.
- [go-deep](https://github.com/patrikeh/go-deep) ⭐ 502 📅 2023-04-27 - A feature-rich neural network library in Go.
- [go-fann](https://github.com/white-pony/go-fann) ⭐ 115 📅 2015-02-03 - Go bindings for Fast Artificial Neural Networks(FANN) library.
- [go-featureprocessing](https://github.com/nikolaydubina/go-featureprocessing) ⭐ 109 📅 2024-03-21 - Fast and convenient feature processing for low latency machine learning in Go.
- [go-galib](https://github.com/thoj/go-galib) ⭐ 198 📅 2015-12-28 - Genetic Algorithms library written in Go / golang.
- [go-pr](https://github.com/daviddengcn/go-pr) ⭐ 62 📅 2013-06-08 - Pattern recognition package in Go lang.
- [gobrain](https://github.com/goml/gobrain) ⭐ 550 📅 2020-12-12 - Neural Networks written in go.
- [godist](https://github.com/e-dard/godist) ⭐ 36 📅 2015-05-11 - Various probability distributions, and associated methods.
- [goga](https://github.com/tomcraven/goga) ⭐ 209 📅 2022-04-13 - Genetic algorithm library for Go.
- [GoLearn](https://github.com/sjwhitworth/golearn) ⭐ 9,127 📅 2022-12-28 - General Machine Learning library for Go.
- [golinear](https://github.com/danieldk/golinear) ⭐ 44 📅 2017-04-18 - liblinear bindings for Go.
- [GoMind](https://github.com/surenderthakran/gomind) ⭐ 75 📅 2018-07-31 - A simplistic Neural Network Library in Go.
- [goml](https://github.com/cdipaolo/goml) ⭐ 1,533 📅 2022-07-15 - On-line Machine Learning in Go.
- [gonet](https://github.com/dathoangnd/gonet) ⭐ 79 📅 2020-04-05 - Neural Network for Go.
- [Goptuna](https://github.com/c-bata/goptuna) ⭐ 249 📅 2023-09-09 - Bayesian optimization framework for black-box functions written in Go. Everything will be optimized.
- [goRecommend](https://github.com/timkaye11/goRecommend) ⭐ 203 📅 2014-07-29 - Recommendation Algorithms library written in Go.
- [gorgonia](https://github.com/gorgonia/gorgonia) ⭐ 5,296 📅 2023-10-13 - graph-based computational library like Theano for Go that provides primitives for building various machine learning and neural network algorithms.
- [gorse](https://github.com/zhenghaoz/gorse) ⭐ 7,970 📅 2024-03-16 - An offline recommender system backend based on collaborative filtering written in Go.
- [goscore](https://github.com/asafschers/goscore) ⭐ 93 📅 2019-08-23 - Go Scoring API for PMML.
- [gosseract](https://github.com/otiai10/gosseract) ⭐ 2,446 📅 2024-03-12 - Go package for OCR (Optical Character Recognition), by using Tesseract C++ library.
- [libsvm](https://github.com/datastream/libsvm) ⭐ 72 📅 2016-05-09 - libsvm golang version derived work based on LIBSVM 3.14.
- [m2cgen](https://github.com/BayesWitnesses/m2cgen) ⭐ 2,698 📅 2022-10-05 - A CLI tool to transpile trained classic ML models into a native Go code with zero dependencies, written in Python with Go language support.
- [neat](https://github.com/jinyeom/neat) ⭐ 69 📅 2018-05-18 - Plug-and-play, parallel Go framework for NeuroEvolution of Augmenting Topologies (NEAT).
- [neural-go](https://github.com/schuyler/neural-go) ⭐ 67 📅 2013-10-18 - Multilayer perceptron network implemented in Go, with training via backpropagation.
- [ocrserver](https://github.com/otiai10/ocrserver) ⭐ 644 📅 2021-05-29 - A simple OCR API server, seriously easy to be deployed by Docker and Heroku.
- [onnx-go](https://github.com/owulveryck/onnx-go) ⭐ 622 📅 2023-10-16 - Go Interface to Open Neural Network Exchange (ONNX).
- [probab](https://github.com/ThePaw/probab) ⭐ 19 📅 2013-08-02 - Probability distribution functions. Bayesian inference. Written in pure Go.
- [randomforest](https://github.com/malaschitz/randomForest) ⭐ 39 📅 2024-02-28 - Easy to use Random Forest library for Go.
- [regommend](https://github.com/muesli/regommend) ⭐ 309 📅 2019-08-07 - Recommendation & collaborative filtering engine.
- [shield](https://github.com/eaigner/shield) ⭐ 156 📅 2013-04-15 - Bayesian text classifier with flexible tokenizers and storage backends for Go.
- [tfgo](https://github.com/galeone/tfgo) ⭐ 2,364 📅 2023-07-15 - Easy to use Tensorflow bindings: simplifies the usage of the official Tensorflow Go bindings. Define computational graphs in Go, load and execute models trained in Python.
- [Varis](https://github.com/Xamber/Varis) ⭐ 54 📅 2018-08-02 - Golang Neural Network.

**[⬆ back to top](#contents)**

## Messaging

_Libraries that implement messaging systems._

- [ami](https://github.com/kak-tus/ami) ⭐ 28 📅 2020-04-02 - Go client to reliable queues based on Redis Cluster Streams.
- [amqp](https://github.com/rabbitmq/amqp091-go) ⭐ 1,267 📅 2024-02-29 - Go RabbitMQ Client Library.
- [APNs2](https://github.com/sideshow/apns2) ⭐ 2,918 📅 2022-04-18 ⭐ 2,918 📅 2022-04-18 - HTTP/2 Apple Push Notification provider for Go — Send push notifications to iOS, tvOS, Safari and OSX apps.
- [Asynq](https://github.com/hibiken/asynq) ⭐ 8,414 📅 2024-03-15 - A simple, reliable, and efficient distributed task queue for Go built on top of Redis.
- [Beaver](https://github.com/Clivern/Beaver) ⭐ 1,503 📅 2023-12-28 - A real time messaging server to build a scalable in-app notifications, multiplayer games, chat apps in web and mobile apps.
- [Benthos](https://github.com/Jeffail/benthos) ⭐ 7,334 📅 2024-03-18 - A message streaming bridge between a range of protocols.
- [Bus](https://github.com/mustafaturan/bus) ⭐ 327 📅 2023-05-14 - Minimalist message bus implementation for internal communication.
- [Centrifugo](https://github.com/centrifugal/centrifugo) ⭐ 7,790 📅 2024-03-14 - Real-time messaging (Websockets or SockJS) server in Go.
- [Chanify](https://github.com/chanify/chanify) ⭐ 1,205 📅 2023-02-25 - A push notification server send message to your iOS devices.
- [Commander](https://github.com/jeroenrinzema/commander) ⭐ 65 📅 2021-04-28 - A high-level event driven consumer/producer supporting various "dialects" such as Apache Kafka.
- [Confluent Kafka Golang Client](https://github.com/confluentinc/confluent-kafka-go) ⭐ 4,375 📅 2024-03-18 - confluent-kafka-go is Confluent's Golang client for Apache Kafka and the Confluent Platform.
- [dbus](https://github.com/godbus/dbus) ⭐ 936 📅 2023-05-22 - Native Go bindings for D-Bus.
- [drone-line](https://github.com/appleboy/drone-line) ⭐ 79 📅 2021-06-18 - Sending [Line](https://at.line.me/en) notifications using a binary, docker or Drone CI.
- [emitter](https://github.com/olebedev/emitter) ⭐ 492 📅 2023-04-11 - Emits events using Go way, with wildcard, predicates, cancellation possibilities and many other good wins.
- [event](https://github.com/agoalofalife/event) ⭐ 55 📅 2018-02-19 - Implementation of the pattern observer.
- [EventBus](https://github.com/asaskevich/EventBus) ⭐ 1,615 📅 2020-09-07 - The lightweight event bus with async compatibility.
- [gaurun-client](https://github.com/osamingo/gaurun-client) ⭐ 11 📅 2018-07-23 - Gaurun Client written in Go.
- [Glue](https://github.com/desertbit/glue) ⭐ 410 📅 2019-06-19 - Robust Go and Javascript Socket Library (Alternative to Socket.io).
- [go-eventbus](https://github.com/stanipetrosyan/go-eventbus) ⭐ 1 📅 2024-03-18 - Simple Event Bus package for Go.
- [go-mq](https://github.com/cheshir/go-mq) ⭐ 89 📅 2023-05-17 - RabbitMQ client with declarative configuration.
- [go-notify](https://github.com/TheCreeper/go-notify) ⭐ 67 📅 2020-12-11 - Native implementation of the freedesktop notification spec.
- [go-nsq](https://github.com/nsqio/go-nsq) ⭐ 2,520 📅 2023-09-18 - the official Go package for NSQ.
- [go-res](https://github.com/jirenius/go-res) ⭐ 62 📅 2023-09-01 - Package for building REST/real-time services where clients are synchronized seamlessly, using NATS and Resgate.
- [go-socket.io](https://github.com/googollee/go-socket.io) - socket.io library for golang, a realtime application framework.
- [go-vitotrol](https://github.com/maxatome/go-vitotrol) ⭐ 23 📅 2022-05-26 - Client library to Viessmann Vitotrol web service.
- [Gollum](https://github.com/trivago/gollum) ⭐ 935 📅 2021-07-01 - A n:m multiplexer that gathers messages from different sources and broadcasts them to a set of destinations.
- [golongpoll](https://github.com/jcuga/golongpoll) ⭐ 648 📅 2023-08-20 - HTTP longpoll server library that makes web pub-sub simple.
- [gopush-cluster](https://github.com/Terry-Mao/gopush-cluster) ⭐ 2,077 📅 2017-05-25 - gopush-cluster is a go push server cluster.
- [gorush](https://github.com/appleboy/gorush) ⭐ 7,551 📅 2024-03-14 - Push notification server using [APNs2](https://github.com/sideshow/apns2) ⭐ 2,918 📅 2022-04-18 ⭐ 2,918 📅 2022-04-18 and google [GCM](https://github.com/google/go-gcm) ⭐ 103 📅 2017-02-14.
- [gosd](https://github.com/alexsniffin/gosd) ⭐ 24 📅 2022-08-17 - A library for scheduling when to dispatch a message to a channel.
- [guble](https://github.com/smancke/guble) ⭐ 156 📅 2017-10-31 - Messaging server using push notifications (Google Firebase Cloud Messaging, Apple Push Notification services, SMS) as well as websockets, a REST API, featuring distributed operation and message-persistence.
- [hare](https://github.com/leozz37/hare) ⭐ 51 📅 2022-08-07 - A user friendly library for sending messages and listening to TCP sockets.
- [hub](https://github.com/leandro-lugaresi/hub) ⭐ 140 📅 2020-10-26 - A Message/Event Hub for Go applications, using publish/subscribe pattern with support for alias like rabbitMQ exchanges.
- [jazz](https://github.com/socifi/jazz) ⭐ 18 📅 2019-03-20 - A simple RabbitMQ abstraction layer for queue administration and publishing and consuming of messages.
- [machinery](https://github.com/RichardKnop/machinery) ⭐ 7,254 📅 2024-03-19 - Asynchronous task queue/job queue based on distributed message passing.
- [mangos](https://github.com/nanomsg/mangos) ⭐ 639 📅 2024-03-17 - Pure go implementation of the Nanomsg ("Scalability Protocols") with transport interoperability.
- [melody](https://github.com/olahol/melody) ⭐ 3,481 📅 2024-03-06 - Minimalist framework for dealing with websocket sessions, includes broadcasting and automatic ping/pong handling.
- [Mercure](https://github.com/dunglas/mercure) ⭐ 3,708 📅 2024-03-19 - Server and library to dispatch server-sent updates using the Mercure protocol (built on top of Server-Sent Events).
- [messagebus](https://github.com/vardius/message-bus) ⭐ 263 📅 2021-01-14 - messagebus is a Go simple async message bus, perfect for using as event bus when doing event sourcing, CQRS, DDD.
- [NATS Go Client](https://github.com/nats-io/nats) ⭐ 5,076 📅 2024-03-20 - Lightweight and high performance publish-subscribe and distributed queueing messaging system - this is the Go library.
- [nsq-event-bus](https://github.com/rafaeljesus/nsq-event-bus) ⭐ 77 📅 2018-02-15 - A tiny wrapper around NSQ topic and channel.
- [oplog](https://github.com/dailymotion/oplog) ⭐ 112 📅 2015-11-07 - Generic oplog/replication system for REST APIs.
- [pubsub](https://github.com/tuxychandru/pubsub) ⭐ 411 📅 2024-02-11 - Simple pubsub package for go.
- [Quamina](https://github.com/timbray/quamina) ⭐ 356 📅 2024-03-20 - Fast pattern-matching for filtering messages and events.
- [rabbus](https://github.com/rafaeljesus/rabbus) ⭐ 97 📅 2019-07-23 - A tiny wrapper over amqp exchanges and queues.
- [rabtap](https://github.com/jandelgado/rabtap) ⭐ 252 📅 2023-10-29 - RabbitMQ swiss army knife cli app.
- [RapidMQ](https://github.com/sybrexsys/RapidMQ) ⭐ 67 📅 2017-12-07 - RapidMQ is a lightweight and reliable library for managing of the local messages queue.
- [Ratus](https://github.com/hyperonym/ratus) ⭐ 97 📅 2024-03-12 - Ratus is a RESTful asynchronous task queue server.
- [redisqueue](https://github.com/robinjoseph08/redisqueue) ⭐ 120 📅 2020-10-15 - redisqueue provides a producer and consumer of a queue that uses Redis streams.
- [rmqconn](https://github.com/sbabiv/rmqconn) ⭐ 22 📅 2020-01-27 - RabbitMQ Reconnection. Wrapper over amqp.Connection and amqp.Dial. Allowing to do a reconnection when the connection is broken before forcing the call to the Close () method to be closed.
- [sarama](https://github.com/Shopify/sarama) ⭐ 10,883 📅 2024-03-08 - Go library for Apache Kafka.
- [Uniqush-Push](https://github.com/uniqush/uniqush-push) ⭐ 1,523 📅 2020-04-09 - Redis backed unified push service for server-side notifications to mobile devices.
- [Watermill](https://github.com/ThreeDotsLabs/watermill) ⭐ 6,648 📅 2024-03-05 - Working efficiently with message streams. Building event driven applications, enabling event sourcing, RPC over messages, sagas. Can use conventional pub/sub implementations like Kafka or RabbitMQ, but also HTTP or MySQL binlog.
- [zmq4](https://github.com/pebbe/zmq4) ⭐ 1,126 📅 2023-10-31 - Go interface to ZeroMQ version 4. Also available for [version 3](https://github.com/pebbe/zmq3) ⭐ 133 📅 2021-03-25 and [version 2](https://github.com/pebbe/zmq2) ⭐ 19 📅 2021-03-25.

**[⬆ back to top](#contents)**

## Microsoft Office

- [unioffice](https://github.com/unidoc/unioffice) ⭐ 4,137 📅 2024-02-17 - Pure go library for creating and processing Office Word (.docx), Excel (.xlsx) and Powerpoint (.pptx) documents.

### Microsoft Excel

_Libraries for working with Microsoft Excel._

- [excelize](https://github.com/xuri/excelize) ⭐ 17,069 📅 2024-03-22 - Golang library for reading and writing Microsoft Excel&trade; (XLSX) files.
- [exl](https://github.com/go-the-way/exl) ⭐ 26 📅 2023-11-23 - Excel binding to struct written in Go.(Only supports Go1.18+)
- [go-excel](https://github.com/szyhf/go-excel) ⭐ 183 📅 2023-09-16 - A simple and light reader to read a relate-db-like excel as a table.
- [goxlsxwriter](https://github.com/fterrag/goxlsxwriter) ⭐ 21 📅 2018-04-20 - Golang bindings for libxlsxwriter for writing XLSX (Microsoft Excel) files.
- [xlsx](https://github.com/tealeg/xlsx) ⭐ 5,727 📅 2024-02-19 - Library to simplify reading the XML format used by recent version of Microsoft Excel in Go programs.
- [xlsx](https://github.com/plandem/xlsx) ⭐ 172 📅 2019-11-02 - Fast and safe way to read/update your existing Microsoft Excel files in Go programs.

**[⬆ back to top](#contents)**

## Miscellaneous

### Dependency Injection

_Libraries for working with dependency injection._

- [alice](https://github.com/magic003/alice) ⭐ 51 📅 2017-04-26 - Additive dependency injection container for Golang.
- [boot-go](http://github.com/boot-go/boot) ⭐ 30 📅 2024-01-29 - Component-based development with dependency injection using reflections for Go developers.
- [cosban/di](https://gitlab.com/cosban/di) - A code generation based dependency injection wiring tool.
- [di](https://github.com/goava/di) ⭐ 221 📅 2023-12-12 - A dependency injection container for go programming language.
- [dig](https://github.com/uber-go/dig) ⭐ 3,646 📅 2024-02-26 - A reflection based dependency injection toolkit for Go.
- [dingo](https://github.com/i-love-flamingo/dingo) ⭐ 173 📅 2023-06-01 - A dependency injection toolkit for Go, based on Guice.
- [do](https://github.com/samber/do) ⭐ 1,542 📅 2024-01-18 - A dependency injection framework based on Generics.
- [fx](https://github.com/uber-go/fx) ⭐ 5,086 📅 2024-03-13 - A dependency injection based application framework for Go (built on top of dig).
- [gocontainer](https://github.com/vardius/gocontainer) ⭐ 19 📅 2020-03-23 - Simple Dependency Injection Container.
- [goioc/di](https://github.com/goioc/di) ⭐ 328 📅 2024-03-04 - Spring-inspired Dependency Injection Container.
- [GoLobby/Container](https://github.com/golobby/container) ⭐ 524 📅 2023-08-30 - GoLobby Container is a lightweight yet powerful IoC dependency injection container for the Go programming language.
- [gontainer](https://github.com/NVIDIA/gontainer) ⭐ 22 📅 2024-01-12 - A dependency injection service container for Go projects.
- [gontainer/gontainer](https://github.com/gontainer/gontainer) ⭐ 15 📅 2024-03-21 - A YAML-based Dependency Injection container for GO. It supports dependencies' scopes, and auto-detection of circular dependencies. Gontainer is concurrent-safe.
- [google/wire](https://github.com/google/wire) ⭐ 12,139 📅 2024-02-07 - Automated Initialization in Go.
- [HnH/di](https://github.com/HnH/di) ⭐ 7 📅 2022-06-29 - DI container library that is focused on clean API and flexibility.
- [kinit](https://github.com/go-kata/kinit) ⭐ 10 📅 2021-06-12 - Customizable dependency injection container with the global mode, cascade initialization and panic-safe finalization.
- [kod](https://github.com/go-kod/kod) ⭐ 58 📅 2024-03-22 - A generics based dependency injection framework for Go.
- [linker](https://github.com/logrange/linker) ⭐ 35 📅 2024-02-21 - A reflection based dependency injection and inversion of control library with components lifecycle support.
- [nject](https://github.com/muir/nject) ⭐ 28 📅 2023-04-18 - A type safe, reflective framework for libraries, tests, http endpoints, and service startup.
- [ore](https://github.com/firasdarwish/ore) ⭐ 3 📅 2024-02-28 - Lightweight, generic & simple dependency injection (DI) container.
- [wire](https://github.com/Fs02/wire) ⭐ 38 📅 2021-08-22 - Strict Runtime Dependency Injection for Golang.

**[⬆ back to top](#contents)**

### Project Layout

_**Unofficial** set of patterns for structuring projects._

- [ardanlabs/service](https://github.com/ardanlabs/service) ⭐ 3,338 📅 2024-03-21 - A [starter kit](https://github.com/ardanlabs/service/wiki) for building production grade scalable web service applications.
- [cookiecutter-golang](https://github.com/lacion/cookiecutter-golang) ⭐ 665 📅 2023-10-07 - A Go application boilerplate template for quick starting projects following production best practices.
- [go-module](https://github.com/octomation/go-module) ⭐ 27 📅 2023-12-28 - Template for a typical module written on Go.
- [go-sample](https://github.com/zitryss/go-sample) ⭐ 126 📅 2019-01-24 - A sample layout for Go application projects with the real code.
- [go-starter](https://github.com/allaboutapps/go-starter) ⭐ 424 📅 2024-02-01 - An opinionated production-ready RESTful JSON backend template, highly integrated with VSCode DevContainers.
- [go-todo-backend](https://github.com/Fs02/go-todo-backend) ⭐ 296 📅 2023-05-19 - Go Todo Backend example using modular project layout for product microservice.
- [gobase](https://github.com/wajox/gobase) ⭐ 54 📅 2023-06-21 - A simple skeleton for golang application with basic setup for real golang application.
- [golang-standards/project-layout](https://github.com/golang-standards/project-layout) ⭐ 45,270 📅 2024-01-25 - Set of common historical and emerging project layout patterns in the Go ecosystem. Note: despite the org-name they do not represent official golang standards, see [this issue](https://github.com/golang-standards/project-layout/issues/117) for more information. Nonetheless, some may find the layout useful.
- [golang-templates/seed](https://github.com/golang-templates/seed) ⭐ 433 📅 2024-02-19 - Go application GitHub repository template.
- [insidieux/inizio](https://github.com/insidieux/inizio) ⭐ 18 📅 2022-06-20 - Golang project layout generator with plugins.
- [modern-go-application](https://github.com/sagikazarmark/modern-go-application) ⭐ 1,763 📅 2023-04-06 - Go application boilerplate and example applying modern practices.
- [nunu](https://github.com/go-nunu/nunu) ⭐ 1,047 📅 2024-03-14 - Nunu is a scaffolding tool for building Go applications. 
- [pagoda](https://github.com/mikestefanello/pagoda) ⭐ 1,253 📅 2024-03-21 - Rapid, easy full-stack web development starter kit built in Go.
- [scaffold](https://github.com/catchplay/scaffold) ⭐ 147 📅 2019-01-10 - Scaffold generates a starter Go project layout. Lets you focus on business logic implemented.
- [wangyoucao577/go-project-layout](https://github.com/wangyoucao577/go-project-layout) ⭐ 24 📅 2021-05-16 - Set of practices and discussions on how to structure Go project layout.

**[⬆ back to top](#contents)**

### Strings

_Libraries for working with strings._

- [bexp](https://github.com/happy-sdk/happy/tree/main/pkg/strings/bexp) - Go implementation of Brace Expansion mechanism to generate arbitrary strings.
- [caps](https://github.com/chanced/caps) ⭐ 52 📅 2023-12-30 - A case conversion library.
- [go-formatter](https://gitlab.com/tymonx/go-formatter) - Implements **replacement fields** surrounded by curly braces `{}` format strings.
- [gobeam/Stringy](https://github.com/gobeam/Stringy) ⭐ 199 📅 2024-03-17 - String manipulation library to convert string to camel case, snake case, kebab case / slugify etc.
- [strutil](https://github.com/ozgio/strutil) ⭐ 200 📅 2021-10-26 - String utilities.
- [sttr](https://github.com/abhimanyu003/sttr) ⭐ 797 📅 2024-02-11 - cross-platform, cli app to perform various operations on string.
- [xstrings](https://github.com/huandu/xstrings) ⭐ 1,272 📅 2022-12-01 - Collection of useful string functions ported from other languages.

**[⬆ back to top](#contents)**

### Uncategorized

_These libraries were placed here because none of the other categories seemed to fit._

- [anagent](https://github.com/mudler/anagent) ⭐ 15 📅 2018-08-10 - Minimalistic, pluggable Golang evloop/timer handler with dependency-injection.
- [antch](https://github.com/antchfx/antch) ⭐ 255 📅 2020-05-31 - A fast, powerful and extensible web crawling & scraping framework.
- [archiver](https://github.com/mholt/archiver) ⭐ 4,208 📅 2024-02-13 - Library and command for making and extracting .zip and .tar.gz archives.
- [autoflags](https://github.com/artyom/autoflags) ⭐ 39 📅 2022-06-11 - Go package to automatically define command line flags from struct fields.
- [avgRating](https://github.com/kirillDanshin/avgRating) ⭐ 16 📅 2017-08-05 - Calculate average score and rating based on Wilson Score Equation.
- [banner](https://github.com/dimiro1/banner) ⭐ 443 📅 2020-12-22 - Add beautiful banners into your Go applications.
- [base64Captcha](https://github.com/mojocn/base64Captcha) ⭐ 1,972 📅 2023-12-08 - Base64captch supports digit, number, alphabet, arithmetic, audio and digit-alphabet captcha.
- [basexx](https://github.com/bobg/basexx) ⭐ 5 📅 2023-07-09 - Convert to, from, and between digit strings in various number bases.
- [battery](https://github.com/distatus/battery) ⭐ 238 📅 2023-06-23 - Cross-platform, normalized battery information library.
- [bitio](https://github.com/icza/bitio) ⭐ 230 📅 2023-03-30 - Highly optimized bit-level Reader and Writer for Go.
- [browscap_go](https://github.com/digitalcrab/browscap_go) ⭐ 47 📅 2022-06-13 - GoLang Library for [Browser Capabilities Project](https://browscap.org/).
- [captcha](https://github.com/steambap/captcha) ⭐ 142 📅 2024-01-13 - Package captcha provides an easy to use, unopinionated API for captcha generation.
- [common](https://github.com/kubeservice-stack/common) ⭐ 4 📅 2023-12-07 - A library for server framework.
- [conv](https://github.com/cstockton/go-conv) ⭐ 387 📅 2021-08-23 - Package conv provides fast and intuitive conversions across Go types.
- [datacounter](https://github.com/miolini/datacounter) ⭐ 47 📅 2023-04-13 - Go counters for readers/writer/http.ResponseWriter.
- [faker](https://github.com/neotoolkit/faker) ⭐ 10 📅 2022-07-21 - Fake data generator.
- [faker](https://github.com/pioz/faker) ⭐ 89 📅 2023-10-06 - Random fake data and struct generator for Go.
- [ffmt](https://github.com/go-ffmt/ffmt) ⭐ 302 📅 2021-11-19 - Beautify data display for Humans.
- [gatus](https://github.com/TwinProduction/gatus) ⭐ 5,181 📅 2024-03-10 - Automated service health dashboard.
- [go-commandbus](https://github.com/lana/go-commandbus) ⭐ 11 📅 2020-04-20 - A slight and pluggable command-bus for Go.
- [go-commons-pool](https://github.com/jolestar/go-commons-pool) ⭐ 1,200 📅 2023-02-27 - Generic object pool for Golang.
- [go-openapi](https://github.com/go-openapi) - Collection of packages to parse and utilize open-api schemas.
- [go-resiliency](https://github.com/eapache/go-resiliency) ⭐ 2,041 📅 2024-02-21 - Resiliency patterns for golang.
- [go-unarr](https://github.com/gen2brain/go-unarr) ⭐ 267 📅 2023-11-30 - Decompression library for RAR, TAR, ZIP and 7z archives.
- [gofakeit](https://github.com/brianvoe/gofakeit) ⭐ 4,147 📅 2024-02-27 - Random data generator written in go.
- [gommit](https://github.com/antham/gommit) ⭐ 110 📅 2024-03-04 - Analyze git commit messages to ensure they follow defined patterns.
- [gopsutil](https://github.com/shirou/gopsutil) ⭐ 9,953 📅 2024-03-20 - Cross-platform library for retrieving process and system utilization(CPU, Memory, Disks, etc).
- [gosh](https://github.com/osamingo/gosh) ⭐ 35 📅 2023-05-01 - Provide Go Statistics Handler, Struct, Measure Method.
- [gosms](https://github.com/haxpax/gosms) ⭐ 1,446 📅 2020-07-07 - Your own local SMS gateway in Go that can be used to send SMS.
- [gotoprom](https://github.com/cabify/gotoprom) ⭐ 109 📅 2020-01-29 - Type-safe metrics builder wrapper library for the official Prometheus client.
- [gountries](https://github.com/pariz/gountries) ⭐ 402 📅 2022-08-12 - Package that exposes country and subdivision data.
- [gtree](https://github.com/ddddddO/gtree) ⭐ 187 📅 2024-03-02 - Provide CLI, Package and Web for tree output and directories creation from Markdown or programmatically.
- [health](https://github.com/alexliesenfeld/health) ⭐ 742 📅 2023-10-17 - A simple and flexible health check library for Go.
- [health](https://github.com/dimiro1/health) ⭐ 448 📅 2023-11-18 - Easy to use, extensible health check library.
- [healthcheck](https://github.com/etherlabsio/healthcheck) ⭐ 260 📅 2023-12-13 - An opinionated and concurrent health-check HTTP handler for RESTful services.
- [hostutils](https://github.com/Wing924/hostutils) ⭐ 12 📅 2023-04-18 - A golang library for packing and unpacking FQDNs list.
- [indigo](https://github.com/osamingo/indigo) ⭐ 107 📅 2023-05-01 - Distributed unique ID generator of using Sonyflake and encoded by Base58.
- [lk](https://github.com/hyperboloide/lk) ⭐ 342 📅 2023-03-25 - A simple licensing library for golang.
- [llvm](https://github.com/llir/llvm) ⭐ 1,143 📅 2023-08-25 - Library for interacting with LLVM IR in pure Go.
- [metrics](https://github.com/pascaldekloe/metrics) ⭐ 27 📅 2023-03-22 - Library for metrics instrumentation and Prometheus exposition.
- [morse](https://github.com/alwindoss/morse) ⭐ 80 📅 2022-08-30 - Library to convert to and from morse code.
- [numa](https://github.com/lrita/numa) ⭐ 21 📅 2023-03-22 - NUMA is a utility library, which is written in go. It help us to write some NUMA-AWARED code.
- [openapi](https://github.com/neotoolkit/openapi) ⭐ 10 📅 2022-06-26 - OpenAPI 3.x parser.
- [pdfgen](https://github.com/hyperboloide/pdfgen) ⭐ 70 📅 2018-02-19 - HTTP service to generate PDF from Json requests.
- [persian](https://github.com/mavihq/persian) ⭐ 80 📅 2023-10-20 - Some utilities for Persian language in go.
- [sandid](https://github.com/aofei/sandid) ⭐ 44 📅 2022-08-04 - Every grain of sand on earth has its own ID.
- [shellwords](https://github.com/Wing924/shellwords) ⭐ 22 📅 2023-04-20 - A Golang library to manipulate strings according to the word parsing rules of the UNIX Bourne shell.
- [shortid](https://github.com/teris-io/shortid) ⭐ 917 📅 2022-06-17 - Distributed generation of super short, unique, non-sequential, URL friendly IDs.
- [shoutrrr](https://github.com/containrrr/shoutrrr) ⭐ 833 📅 2024-01-03 - Notification library providing easy access to various messaging services like slack, mattermost, gotify and smtp among others.
- [sitemap-format](https://github.com/mingard/sitemap-format) ⭐ 4 📅 2022-11-16 - A simple sitemap generator, with a little syntactic sugar.
- [stateless](https://github.com/qmuntal/stateless) ⭐ 764 📅 2024-02-25 - A fluent library for creating state machines.
- [stats](https://github.com/go-playground/stats) ⭐ 170 📅 2016-09-07 - Monitors Go MemStats + System stats such as Memory, Swap and CPU and sends via UDP anywhere you want for logging etc...
- [turtle](https://github.com/hackebrot/turtle) ⭐ 156 📅 2021-10-04 - Emojis for Go.
- [url-shortener](https://github.com/pantrif/url-shortener) ⭐ 47 📅 2023-02-06 - A modern, powerful, and robust URL shortener microservice with mysql support.
- [VarHandler](https://github.com/azr/generators/tree/master/varhandler) - Generate boilerplate http input and output handling.
- [varint](https://github.com/chmike/varint) ⭐ 11 📅 2023-10-07 - A faster varying length integer encoder/decoder than the one provided in the standard library.
- [xdg](https://github.com/rkoesters/xdg) ⭐ 37 📅 2024-01-17 - FreeDesktop.org (xdg) Specs implemented in Go.
- [xkg](https://github.com/go-xkg/xkg) ⭐ 56 📅 2015-01-08 - X Keyboard Grabber.
- [xz](https://github.com/ulikunitz/xz) ⭐ 443 📅 2022-12-13 - Pure golang package for reading and writing xz-compressed files.

**[⬆ back to top](#contents)**

## Natural Language Processing

_Libraries for working with human languages._

See also [Text Processing](#text-processing) and [Text Analysis](#text-analysis).

### Language Detection

- [detectlanguage](https://github.com/detectlanguage/detectlanguage-go) ⭐ 24 📅 2022-04-30 - Language Detection API Go Client. Supports batch requests, short phrase or single word language detection.
- [getlang](https://github.com/rylans/getlang) ⭐ 165 📅 2020-12-27 - Fast natural language detection package.
- [guesslanguage](https://github.com/endeveit/guesslanguage) ⭐ 58 📅 2014-12-16 - Functions to determine the natural language of a unicode text.
- [whatlanggo](https://github.com/abadojack/whatlanggo) ⭐ 624 📅 2019-03-06 - Natural language detection package for Go. Supports 84 languages and 24 scripts (writing systems e.g. Latin, Cyrillic, etc).

### Morphological Analyzers

- [go-stem](https://github.com/agonopol/go-stem) ⭐ 77 📅 2015-06-30 - Implementation of the porter stemming algorithm.
- [go2vec](https://github.com/danieldk/go2vec) ⭐ 50 📅 2017-05-17 - Reader and utility functions for word2vec embeddings.
- [golibstemmer](https://github.com/rjohnsondev/golibstemmer) ⭐ 20 📅 2014-06-17 - Go bindings for the snowball libstemmer library including porter 2.
- [gosentiwordnet](https://github.com/dinopuguh/gosentiwordnet) ⭐ 10 📅 2021-03-11 - Sentiment analyzer using sentiwordnet lexicon in Go.
- [govader](https://github.com/jonreiter/govader) ⭐ 38 📅 2023-01-29 ⭐ 38 📅 2023-01-29 - Go implementation of [VADER Sentiment Analysis](https://github.com/cjhutto/vaderSentiment) ⭐ 4,206 📅 2022-04-01.
- [govader-backend](https://github.com/PIMPfiction/govader_backend) ⭐ 6 📅 2024-02-25 - Microservice implementation of [GoVader](https://github.com/jonreiter/govader) ⭐ 38 📅 2023-01-29 ⭐ 38 📅 2023-01-29.
- [kagome](https://github.com/ikawaha/kagome) ⭐ 788 📅 2024-02-21 - JP morphological analyzer written in pure Go.
- [libtextcat](https://github.com/goodsign/libtextcat) ⭐ 13 📅 2012-12-27 - Cgo binding for libtextcat C library. Guaranteed compatibility with version 2.2.
- [nlp](https://github.com/Shixzie/nlp) ⭐ 385 📅 2017-09-18 - Extract values from strings and fill your structs with nlp.
- [nlp](https://github.com/james-bowman/nlp) ⭐ 430 📅 2021-05-11 - Go Natural Language Processing library supporting LSA (Latent Semantic Analysis).
- [paicehusk](https://github.com/rookii/paicehusk) ⭐ 29 📅 2013-06-19 - Golang implementation of the Paice/Husk Stemming Algorithm.
- [porter](https://github.com/a2800276/porter) ⭐ 12 📅 2013-10-03 - This is a fairly straightforward port of Martin Porter's C implementation of the Porter stemming algorithm.
- [porter2](https://github.com/zhenjl/porter2) ⭐ 46 📅 2015-08-29 - Really fast Porter 2 stemmer.
- [RAKE.go](https://github.com/afjoseph/RAKE.Go) - Go port of the Rapid Automatic Keyword Extraction Algorithm (RAKE).
- [snowball](https://github.com/goodsign/snowball) ⭐ 36 📅 2012-12-11 - Snowball stemmer port (cgo wrapper) for Go. Provides word stem extraction functionality [Snowball native](http://snowball.tartarus.org/).
- [spaGO](https://github.com/nlpodyssey/spago) ⭐ 1,699 📅 2024-01-15 - Self-contained Machine Learning and Natural Language Processing library in Go.
- [spelling-corrector](https://github.com/jorelosorio/spellingcorrector) ⭐ 2 📅 2022-03-23 - A spelling corrector for the Spanish language or create your own.

### Slugifiers

- [go-slugify](https://github.com/mozillazg/go-slugify) ⭐ 89 📅 2016-08-13 - Make pretty slug with multiple languages support.
- [slug](https://github.com/gosimple/slug) ⭐ 1,073 📅 2024-02-24 - URL-friendly slugify with multiple languages support.
- [Slugify](https://github.com/avelino/slugify) ⭐ 32 📅 2018-05-01 - Go slugify application that handles string.

### Tokenizers

- [gojieba](https://github.com/yanyiwu/gojieba) ⭐ 2,311 📅 2023-04-28 - This is a Go implementation of [jieba](https://github.com/fxsjy/jieba) ⭐ 32,192 📅 2020-02-15 which a Chinese word splitting algorithm.
- [gotokenizer](https://github.com/xujiajun/gotokenizer) ⭐ 18 📅 2019-04-10 - A tokenizer based on the dictionary and Bigram language models for Golang. (Now only support chinese segmentation)
- [gse](https://github.com/go-ego/gse) ⭐ 2,452 📅 2024-02-23 - Go efficient text segmentation; support english, chinese, japanese and other.
- [MMSEGO](https://github.com/awsong/MMSEGO) ⭐ 62 📅 2012-04-18 - This is a GO implementation of [MMSEG](http://technology.chtsai.org/mmseg/) which a Chinese word splitting algorithm.
- [prose](https://github.com/jdkato/prose) ⭐ 3,031 📅 2021-09-21 - Library for text processing that supports tokenization, part-of-speech tagging, named-entity extraction, and more. English only.
- [segment](https://github.com/blevesearch/segment) ⭐ 85 📅 2022-12-19 - Go library for performing Unicode Text Segmentation as described in [Unicode Standard Annex #29](https://www.unicode.org/reports/tr29/)
- [sentences](https://github.com/neurosnap/sentences) ⭐ 413 📅 2024-02-28 - Sentence tokenizer: converts text into a list of sentences.
- [shamoji](https://github.com/osamingo/shamoji) ⭐ 13 📅 2022-12-01 - The shamoji is word filtering package written in Go.
- [stemmer](https://github.com/dchest/stemmer) ⭐ 51 📅 2016-12-07 - Stemmer packages for Go programming language. Includes English and German stemmers.
- [textcat](https://github.com/pebbe/textcat) ⭐ 71 📅 2021-02-20 - Go package for n-gram based text categorization, with support for utf-8 and raw text.

### Translation

- [go-i18n](https://github.com/nicksnyder/go-i18n/) ⭐ 2,726 📅 2024-03-16 - Package and an accompanying tool to work with localized text.
- [go-localize](https://github.com/m1/go-localize) ⭐ 57 📅 2021-10-29 - Simple and easy to use i18n (Internationalization and localization) engine - used for translating locale strings.
- [go-mystem](https://github.com/dveselov/mystem) ⭐ 32 📅 2016-10-05 - CGo bindings to Yandex.Mystem - russian morphology analyzer.
- [go-pinyin](https://github.com/mozillazg/go-pinyin) ⭐ 1,546 📅 2023-05-14 - CN Hanzi to Hanyu Pinyin converter.
- [go-words](https://github.com/saleh-rahimzadeh/go-words) ⭐ 6 📅 2024-02-26 - A words table and text resource library for Golang projects.
- [gotext](https://github.com/leonelquinteros/gotext) ⭐ 416 📅 2023-10-03 - GNU gettext utilities for Go.
- [icu](https://github.com/goodsign/icu) ⭐ 21 📅 2012-12-27 - Cgo binding for icu4c C library detection and conversion functions. Guaranteed compatibility with version 50.1.
- [iuliia-go](https://github.com/mehanizm/iuliia-go) ⭐ 46 📅 2021-06-15 - Transliterate Cyrillic → Latin in every possible way.
- [spreak](https://github.com/vorlif/spreak) ⭐ 37 📅 2023-12-09 - Flexible translation and humanization library for Go, based on the concepts behind gettext.
- [t](https://github.com/youthlin/t) ⭐ 18 📅 2024-01-05 - Another i18n pkg for golang, which follows GNU gettext style and supports .po/.mo files: `t.T (gettext)`, `t.N (ngettext)`, etc. And it contains a cmd tool [xtemplate](https://github.com/youthlin/t/blob/main/cmd/xtemplate), which can extract messages as a pot file from text/html template.

### Transliteration

- [enca](https://github.com/endeveit/enca) ⭐ 16 📅 2016-03-15 - Minimal cgo bindings for [libenca](https://cihar.com/software/enca/), which detects character encodings.
- [go-unidecode](https://github.com/mozillazg/go-unidecode) ⭐ 121 📅 2023-05-14 - ASCII transliterations of Unicode text.
- [gounidecode](https://github.com/fiam/gounidecode) ⭐ 79 📅 2015-06-29 - Unicode transliterator (also known as unidecode) for Go.
- [transliterator](https://github.com/alexsergivan/transliterator) ⭐ 39 📅 2022-09-14 - Provides one-way string transliteration with supporting of language-specific transliteration rules.

**[⬆ back to top](#contents)**

## Networking

_Libraries for working with various layers of the network._

- [arp](https://github.com/mdlayher/arp) ⭐ 350 📅 2022-05-12 - Package arp implements the ARP protocol, as described in RFC 826.
- [buffstreams](https://github.com/stabbycutyou/buffstreams) ⭐ 253 📅 2016-04-16 - Streaming protocolbuffer data over TCP made easy.
- [canopus](https://github.com/zubairhamed/canopus) ⭐ 153 📅 2018-02-07 - CoAP Client/Server implementation (RFC 7252).
- [cidranger](https://github.com/yl2chen/cidranger) ⭐ 877 📅 2021-09-28 - Fast IP to CIDR lookup for Go.
- [dhcp6](https://github.com/mdlayher/dhcp6) ⭐ 77 📅 2019-03-11 - Package dhcp6 implements a DHCPv6 server, as described in RFC 3315.
- [dns](https://github.com/miekg/dns) ⭐ 7,704 📅 2024-02-15 - Go library for working with DNS.
- [dnsmonster](https://github.com/mosajjal/dnsmonster) ⭐ 293 📅 2024-03-18 - Passive DNS Capture/Monitoring Framework.
- [easytcp](https://github.com/DarthPestilane/easytcp) ⭐ 787 📅 2024-03-19 - A light-weight TCP framework written in Go (Golang), built with message router. EasyTCP helps you build a TCP server easily fast and less painful.
- [ether](https://github.com/songgao/ether) ⭐ 80 📅 2016-04-05 - Cross-platform Go package for sending and receiving ethernet frames.
- [ethernet](https://github.com/mdlayher/ethernet) ⭐ 270 📅 2022-02-21 - Package ethernet implements marshaling and unmarshalling of IEEE 802.3 Ethernet II frames and IEEE 802.1Q VLAN tags.
- [event](https://github.com/cheng-zhongliang/event) ⭐ 153 📅 2023-12-28 - Simple I/O event notification library written in Golang.
- [fasthttp](https://github.com/valyala/fasthttp) ⭐ 20,880 📅 2024-03-06 - Package fasthttp is a fast HTTP implementation for Go, up to 10 times faster than net/http.
- [fortio](https://github.com/fortio/fortio) ⭐ 3,147 📅 2024-03-11 - Load testing library and command line tool, advanced echo server and web UI. Allows to specify a set query-per-second load and record latency histograms and other useful stats and graph them. Tcp, Http, gRPC.
- [ftp](https://github.com/jlaffaye/ftp) ⭐ 1,218 📅 2024-02-14 - Package ftp implements a FTP client as described in [RFC 959](https://tools.ietf.org/html/rfc959).
- [ftpserverlib](https://github.com/fclairamb/ftpserverlib) ⭐ 390 📅 2024-03-10 - Fully featured FTP server library.
- [fullproxy](https://github.com/shoriwe/fullproxy) ⭐ 68 📅 2023-06-12 - A fully featured scriptable and daemon configurable proxy and pivoting toolkit with SOCKS5, HTTP, raw ports and reverse proxy protocols.
- [gaio](https://github.com/xtaci/gaio) ⭐ 556 📅 2024-01-27 - High performance async-io networking for Golang in proactor mode.
- [gev](https://github.com/Allenxuxu/gev) ⭐ 1,699 📅 2022-12-03 - gev is a lightweight, fast non-blocking TCP network library based on Reactor mode.
- [gldap](https://github.com/jimlambrt/gldap) ⭐ 105 📅 2024-03-06 - gldap provides an ldap server implementation and you provide handlers for its ldap operations.
- [gmqtt](https://github.com/DrmagicE/gmqtt) ⭐ 946 📅 2023-09-15 - Gmqtt is a flexible, high-performance MQTT broker library that fully implements the MQTT protocol V3.1.1.
- [gnet](https://github.com/panjf2000/gnet) ⭐ 8,679 📅 2024-03-19 - `gnet` is a high-performance, lightweight, non-blocking, event-driven networking framework written in pure Go.
- [gnet](https://github.com/fish-tennis/gnet) ⭐ 12 📅 2024-03-15 - `gnet` is a high-performance networking framework,especially for game servers.
- [gNxI](https://github.com/google/gnxi) ⭐ 248 📅 2023-10-31 - A collection of tools for Network Management that use the gNMI and gNOI protocols.
- [go-getter](https://github.com/hashicorp/go-getter) ⭐ 1,570 📅 2023-12-04 - Go library for downloading files or directories from various sources using a URL.
- [go-powerdns](https://github.com/joeig/go-powerdns) ⭐ 79 📅 2024-02-12 - PowerDNS API bindings for Golang.
- [go-sse](https://github.com/lampctl/go-sse) ⭐ 6 📅 2023-05-21 - Go client and server implementation of HTML server-sent events.
- [go-stun](https://github.com/ccding/go-stun) ⭐ 630 📅 2024-01-16 - Go implementation of the STUN client (RFC 3489 and RFC 5389).
- [gobgp](https://github.com/osrg/gobgp) ⭐ 3,440 📅 2023-06-05 - BGP implemented in the Go Programming Language.
- [golibwireshark](https://github.com/sunwxg/golibwireshark) ⭐ 29 📅 2017-10-24 - Package golibwireshark use libwireshark library to decode pcap file and analyse dissection data.
- [gopacket](https://github.com/google/gopacket) ⭐ 6,068 📅 2022-08-06 - Go library for packet processing with libpcap bindings.
- [gopcap](https://github.com/akrennmair/gopcap) ⭐ 484 📅 2015-07-28 - Go wrapper for libpcap.
- [goshark](https://github.com/sunwxg/goshark) ⭐ 18 📅 2017-10-24 - Package goshark use tshark to decode IP packet and create data struct to analyse packet.
- [gosnmp](https://github.com/soniah/gosnmp) ⭐ 1,063 📅 2024-03-02 - Native Go library for performing SNMP actions.
- [gotcp](https://github.com/gansidui/gotcp) ⭐ 510 📅 2017-04-18 - Go package for quickly writing tcp applications.
- [grab](https://github.com/cavaliercoder/grab) ⭐ 1,357 📅 2022-01-08 - Go package for managing file downloads.
- [graval](https://github.com/koofr/graval) ⭐ 28 📅 2020-10-02 - Experimental FTP server framework.
- [gws](https://github.com/lxzan/gws) ⭐ 942 📅 2024-02-19 - High-Performance WebSocket Server & Client With AsyncIO Supporting .
- [HTTPLab](https://github.com/gchaincl/httplab) ⭐ 3,978 📅 2024-02-05 - HTTPLabs let you inspect HTTP requests and forge responses.
- [httpproxy](https://github.com/wzshiming/httpproxy) ⭐ 22 📅 2023-11-01 - HTTP proxy handler and dialer.
- [iplib](https://github.com/c-robinson/iplib) ⭐ 131 📅 2024-01-27 - Library for working with IP addresses (net.IP, net.IPNet), inspired by python [ipaddress](https://docs.python.org/3/library/ipaddress.html) and ruby [ipaddr](https://ruby-doc.org/stdlib-2.5.1/libdoc/ipaddr/rdoc/IPAddr.html)
- [jazigo](https://github.com/udhos/jazigo) ⭐ 206 📅 2023-11-02 - Jazigo is a tool written in Go for retrieving configuration for multiple network devices.
- [kcp-go](https://github.com/xtaci/kcp-go) ⭐ 3,903 📅 2024-03-11 - KCP - Fast and Reliable ARQ Protocol.
- [kcptun](https://github.com/xtaci/kcptun) ⭐ 13,642 📅 2024-03-12 - Extremely simple & fast udp tunnel based on KCP protocol.
- [lhttp](https://github.com/fanux/lhttp) ⭐ 690 📅 2018-04-08 - Powerful websocket framework, build your IM server more easily.
- [linkio](https://github.com/ian-kent/linkio) ⭐ 53 📅 2017-08-07 - Network link speed simulation for Reader/Writer interfaces.
- [llb](https://github.com/kirillDanshin/llb) ⭐ 14 📅 2016-04-04 - It's a very simple but quick backend for proxy servers. Can be useful for fast redirection to predefined domain with zero memory allocation and fast response.
- [mdns](https://github.com/hashicorp/mdns) ⭐ 1,113 📅 2024-03-21 - Simple mDNS (Multicast DNS) client/server library in Golang.
- [mqttPaho](https://eclipse.org/paho/clients/golang/) - The Paho Go Client provides an MQTT client library for connection to MQTT brokers via TCP, TLS or WebSockets.
- [nbio](https://github.com/lesismal/nbio) ⭐ 1,957 📅 2024-03-16 - Pure Go 1000k+ connections solution, support tls/http1.x/websocket and basically compatible with net/http, with high-performance and low memory cost, non-blocking, event-driven, easy-to-use.
- [netpoll](https://github.com/cloudwego/netpoll) ⭐ 3,839 📅 2024-03-11 - A high-performance non-blocking I/O networking framework, which focused on RPC scenarios, developed by ByteDance.
- [NFF-Go](https://github.com/intel-go/nff-go) ⭐ 1,350 📅 2022-11-22 - Framework for rapid development of performant network functions for cloud and bare-metal (former YANFF).
- [packet](https://github.com/aerogo/packet) ⭐ 78 📅 2019-10-26 - Send packets over TCP and UDP. It can buffer messages and hot-swap connections if needed.
- [peerdiscovery](https://github.com/schollz/peerdiscovery) ⭐ 621 📅 2023-11-09 - Pure Go library for cross-platform local peer discovery using UDP multicast.
- [portproxy](https://github.com/aybabtme/portproxy) ⭐ 53 📅 2014-12-13 - Simple TCP proxy which adds CORS support to API's which don't support it.
- [publicip](https://github.com/polera/publicip) ⭐ 27 📅 2016-12-29 - Package publicip returns your public facing IPv4 address (internet egress).
- [quic-go](https://github.com/lucas-clemente/quic-go) ⭐ 9,334 📅 2024-03-22 - An implementation of the QUIC protocol in pure Go.
- [raw](https://github.com/mdlayher/raw) ⭐ 422 📅 2022-02-21 - Package raw enables reading and writing data at the device driver level for a network interface.
- [sftp](https://github.com/pkg/sftp) ⭐ 1,450 📅 2024-03-20 - Package sftp implements the SSH File Transfer Protocol as described in <https://filezilla-project.org/specs/draft-ietf-secsh-filexfer-02.txt>.
- [ssh](https://github.com/gliderlabs/ssh) ⭐ 3,356 📅 2024-03-18 - Higher-level API for building SSH servers (wraps crypto/ssh).
- [sslb](https://github.com/eduardonunesp/sslb) ⭐ 148 📅 2024-02-18 - It's a Super Simples Load Balancer, just a little project to achieve some kind of performance.
- [stun](https://github.com/go-rtc/stun) ⭐ 490 📅 2020-11-23 - Go implementation of RFC 5389 STUN protocol.
- [tcp_server](https://github.com/firstrow/tcp_server) ⭐ 424 📅 2021-03-16 - Go library for building tcp servers faster.
- [tcpack](https://github.com/lim-yoona/tcpack) ⭐ 175 📅 2023-10-16 - tcpack is an application protocol based on TCP to Pack and Unpack bytes stream in go program.
- [tspool](https://github.com/two/tspool) ⭐ 14 📅 2018-10-29 - A TCP Library use worker pool to improve performance and protect your server.
- [utp](https://github.com/anacrolix/utp) ⭐ 172 📅 2023-05-19 - Go uTP micro transport protocol implementation.
- [vssh](https://github.com/yahoo/vssh) ⭐ 935 📅 2020-11-22 - Go library for building network and server automation over SSH protocol.
- [water](https://github.com/songgao/water) ⭐ 1,838 📅 2020-03-17 - Simple TUN/TAP library.
- [webrtc](https://github.com/pions/webrtc) ⭐ 12,535 📅 2024-03-18 - A pure Go implementation of the WebRTC API.
- [winrm](https://github.com/masterzen/winrm) ⭐ 413 📅 2023-12-27 - Go WinRM client to remotely execute commands on Windows machines.
- [xtcp](https://github.com/xfxdev/xtcp) ⭐ 148 📅 2020-02-29 - TCP Server Framework with simultaneous full duplex communication, graceful shutdown, and custom protocol.

**[⬆ back to top](#contents)**

### HTTP Clients

_Libraries for making HTTP requests._

- [fast-shot](https://github.com/opus-domini/fast-shot) ⭐ 30 📅 2024-03-10 - Hit your API targets with rapid-fire precision using Go's fastest and simple HTTP Client.
- [gentleman](https://github.com/h2non/gentleman) ⭐ 1,060 📅 2023-12-17 - Full-featured plugin-driven HTTP client library.
- [go-cleanhttp](https://github.com/hashicorp/go-cleanhttp) ⭐ 359 📅 2023-02-01 - Get easily stdlib HTTP client, which does not share any state with other clients.
- [go-http-client](https://github.com/bozd4g/go-http-client) ⭐ 70 📅 2024-01-28 - Make http calls simply and easily.
- [go-otelroundtripper](https://github.com/NdoleStudio/go-otelroundtripper) ⭐ 75 📅 2024-02-12 - Go http.RoundTripper that emits open telemetry metrics for HTTP requests.
- [go-req](https://github.com/wenerme/go-req) ⭐ 22 📅 2022-07-06 - Declarative golang HTTP client.
- [go-retryablehttp](https://github.com/hashicorp/go-retryablehttp) ⭐ 1,811 📅 2023-11-08 - Retryable HTTP client in Go.
- [go-zoox/fetch](https://github.com/go-zoox/fetch) ⭐ 65 📅 2023-12-17 - A Powerful, Lightweight, Easy Http Client, inspired by Web Fetch API.
- [grequests](https://github.com/levigross/grequests) ⭐ 2,027 📅 2023-12-03 - A Go "clone" of the great and famous Requests library.
- [heimdall](https://github.com/gojektech/heimdall) ⭐ 2,547 📅 2021-05-21 - An enhanced http client with retry and hystrix capabilities.
- [httpretry](https://github.com/ybbus/httpretry) ⭐ 41 📅 2023-02-22 - Enriches the default go HTTP client with retry functionality.
- [pester](https://github.com/sethgrid/pester) ⭐ 634 📅 2022-02-09 - Go HTTP client calls with retries, backoff, and concurrency.
- [req](https://github.com/imroc/req) ⭐ 3,954 📅 2024-03-12 - Simple Go HTTP client with Black Magic (Less code and More efficiency).
- [request](https://github.com/monaco-io/request) ⭐ 280 📅 2024-01-08 - HTTP client for golang. If you have experience about axios or requests, you will love it. No 3rd dependency.
- [requests](https://github.com/carlmjohnson/requests) ⭐ 1,367 📅 2024-02-24 - HTTP requests for Gophers. Uses context.Context and doesn't hide the underlying net/http.Client, making it compatible with standard Go APIs. Also includes testing tools.
- [resty](https://github.com/go-resty/resty) ⭐ 9,178 📅 2024-03-17 - Simple HTTP and REST client for Go inspired by Ruby rest-client.
- [rq](https://github.com/ddo/rq) ⭐ 51 📅 2019-08-28 - A nicer interface for golang stdlib HTTP client.
- [sling](https://github.com/dghubble/sling) ⭐ 1,637 📅 2024-03-05 - Sling is a Go HTTP client library for creating and sending API requests.

**[⬆ back to top](#contents)**

## OpenGL

_Libraries for using OpenGL in Go._

- [gl](https://github.com/go-gl/gl) ⭐ 1,027 📅 2023-10-21 - Go bindings for OpenGL (generated via glow).
- [glfw](https://github.com/go-gl/glfw) ⭐ 1,495 📅 2024-03-07 - Go bindings for GLFW 3.
- [go-glmatrix](https://github.com/technohippy/go-glmatrix) ⭐ 8 📅 2021-02-05 - Go port of [glMatrix](https://glmatrix.net/) library.
- [goxjs/gl](https://github.com/goxjs/gl) ⭐ 170 📅 2022-07-11 - Go cross-platform OpenGL bindings (OS X, Linux, Windows, browsers, iOS, Android).
- [goxjs/glfw](https://github.com/goxjs/glfw) ⭐ 80 📅 2018-04-16 - Go cross-platform glfw library for creating an OpenGL context and receiving events.
- [mathgl](https://github.com/go-gl/mathgl) ⭐ 527 📅 2024-01-26 - Pure Go math package specialized for 3D math, with inspiration from GLM.

**[⬆ back to top](#contents)**

## ORM

_Libraries that implement Object-Relational Mapping or datamapping techniques._

- [bun](https://github.com/uptrace/bun) ⭐ 2,885 📅 2024-03-22 - SQL-first Golang ORM. Successor of go-pg.
- [cacheme](https://github.com/Yiling-J/cacheme-go) ⭐ 24 📅 2021-12-18 - Schema based, typed Redis caching/memoize framework for Go.
- [CQL](https://github.com/FrancoLiberali/cql) ⭐ 14 📅 2024-01-15 - Built on top of GORM, adds compile-time verified queries based on auto-generated code.
- [ent](https://github.com/facebook/ent) ⭐ 14,761 📅 2024-03-18 - An entity framework for Go. Simple, yet powerful ORM for modeling and querying data.
- [go-dbw](https://github.com/hashicorp/go-dbw) ⭐ 12 📅 2024-03-12 - A simple package that encapsulates database operations.
- [go-firestorm](https://github.com/jschoedt/go-firestorm) ⭐ 48 📅 2021-12-13 - A simple ORM for Google/Firebase Cloud Firestore.
- [go-sql](https://github.com/rushteam/gosql) ⭐ 176 📅 2021-06-21 - A easy ORM for mysql.
- [go-sqlbuilder](https://github.com/huandu/go-sqlbuilder) ⭐ 1,180 📅 2023-11-30 - A flexible and powerful SQL string builder library plus a zero-config ORM.
- [go-store](https://github.com/gosuri/go-store) ⭐ 112 📅 2017-02-23 - Simple and fast Redis backed key-value store library for Go.
- [golobby/orm](https://github.com/golobby/orm) ⭐ 153 📅 2023-08-30 - Simple, fast, type-safe, generic orm for developer happiness.
- [GORM](https://github.com/go-gorm/gorm) ⭐ 35,121 📅 2024-03-21 - The fantastic ORM library for Golang, aims to be developer friendly.
- [gormt](https://github.com/xxjwxc/gormt) ⭐ 2,308 📅 2023-05-24 - Mysql database to golang gorm struct.
- [gorp](https://github.com/go-gorp/gorp) ⭐ 3,706 📅 2022-10-18 - Go Relational Persistence, ORM-ish library for Go.
- [grimoire](https://github.com/Fs02/grimoire) ⭐ 161 📅 2021-10-25 - Grimoire is a database access layer and validation for golang. (Support: MySQL, PostgreSQL and SQLite3).
- [lore](https://github.com/abrahambotros/lore) ⭐ 14 📅 2017-10-21 - Simple and lightweight pseudo-ORM/pseudo-struct-mapping environment for Go.
- [marlow](https://github.com/marlow/marlow) ⭐ 14 📅 2020-08-18 - Generated ORM from project structs for compile time safety assurances.
- [pop/soda](https://github.com/gobuffalo/pop) ⭐ 1,402 📅 2023-04-26 - Database migration, creation, ORM, etc... for MySQL, PostgreSQL, and SQLite.
- [Prisma](https://github.com/prisma/prisma-client-go) ⭐ 1,902 📅 2024-03-21 - Prisma Client Go, Typesafe database access for Go.
- [reform](https://github.com/go-reform/reform) ⭐ 1,436 📅 2022-01-24 - Better ORM for Go, based on non-empty interfaces and code generation.
- [rel](https://github.com/go-rel/rel) ⭐ 726 📅 2024-03-04 - Modern Database Access Layer for Golang - Testable, Extendable and Crafted Into a Clean and Elegant API.
- [SQLBoiler](https://github.com/volatiletech/sqlboiler) ⭐ 6,363 📅 2024-03-19 - ORM generator. Generate a featureful and blazing-fast ORM tailored to your database schema.
- [upper.io/db](https://github.com/upper/db) ⭐ 3,469 📅 2023-11-05 - Single interface for interacting with different data sources through the use of adapters that wrap mature database drivers.
- [XORM](https://gitea.com/xorm/xorm) - Simple and powerful ORM for Go. (Support: MySQL, MyMysql, PostgreSQL, Tidb, SQLite3, MsSql and Oracle).
- [Zoom](https://github.com/albrow/zoom) ⭐ 305 📅 2023-02-02 - Blazing-fast datastore and querying engine built on Redis.

**[⬆ back to top](#contents)**

## Package Management

_Official tooling for dependency and package management_

- [go modules](https://golang.org/cmd/go/#hdr-Modules__module_versions__and_more) - Modules are the unit of source code interchange and versioning. The go command has direct support for working with modules, including recording and resolving dependencies on other modules.

_Official experimental tooling for package management_

- [dep](https://github.com/golang/dep) ⭐ 12,893 📅 2020-09-04 - Go dependency tool.
- [vgo](https://go.googlesource.com/vgo/) - Versioned Go.

_Unofficial libraries for package and dependency management._

- [glide](https://github.com/Masterminds/glide) ⭐ 8,165 📅 2019-07-10 - Manage your golang vendor and vendored packages with ease. Inspired by tools like Maven, Bundler, and Pip.
- [godep](https://github.com/tools/godep) ⭐ 5,556 📅 2018-01-26 - dependency tool for go, godep helps build packages reproducibly by fixing their dependencies.
- [gom](https://github.com/mattn/gom) ⭐ 1,386 📅 2019-07-26 - Go Manager - bundle for go.
- [goop](https://github.com/nitrous-io/goop) ⭐ 780 📅 2014-10-02 - Simple dependency manager for Go (golang), inspired by Bundler.
- [gop](https://github.com/lunny/gop) ⭐ 49 📅 2019-03-22 - Build and manage your Go applications out of GOPATH.
- [gopm](https://github.com/gpmgo/gopm) ⭐ 2,470 📅 2019-07-29 - Go Package Manager.
- [govendor](https://github.com/kardianos/govendor) ⭐ 4,945 📅 2020-03-02 - Go Package Manager. Go vendor tool that works with the standard vendor file.
- [gpm](https://github.com/pote/gpm) ⭐ 1,191 📅 2017-09-07 - Barebones dependency manager for Go.
- [gup](https://github.com/nao1215/gup) ⭐ 263 📅 2024-01-28 - Update binaries installed by "go install".
- [johnny-deps](https://github.com/VividCortex/johnny-deps) ⭐ 214 📅 2020-12-15 - Minimal dependency version using Git.
- [modgv](https://github.com/lucasepe/modgv) ⭐ 480 📅 2023-02-23 - Converts 'go mod graph' output into Graphviz's DOT language.
- [mvn-golang](https://github.com/raydac/mvn-golang) ⭐ 162 📅 2024-02-18 - plugin that provides way for auto-loading of Golang SDK, dependency management and start build environment in Maven project infrastructure.
- [nut](https://github.com/jingweno/nut) ⭐ 234 📅 2015-06-25 - Vendor Go dependencies.
- [VenGO](https://github.com/DamnWidget/VenGO) ⭐ 125 📅 2016-04-26 - create and manage exportable isolated go virtual environments.

**[⬆ back to top](#contents)**

## Performance

- [go-instrument](https://github.com/nikolaydubina/go-instrument) ⭐ 129 📅 2024-03-21 - Automatically add spans to all methods and functions.
- [jaeger](https://github.com/jaegertracing/jaeger) ⭐ 19,245 📅 2024-03-21 - A distributed tracing system.
- [pixie](https://github.com/pixie-labs/pixie) ⭐ 5,220 📅 2024-03-15 - No instrumentation tracing for Golang applications via eBPF.
- [profile](https://github.com/pkg/profile) ⭐ 1,952 📅 2022-10-20 - Simple profiling support package for Go.
- [statsviz](https://github.com/arl/statsviz) ⭐ 3,097 📅 2024-02-18 - Live visualization of your Go application runtime statistics.
- [tracer](https://github.com/kamilsk/tracer) ⭐ 84 📅 2020-06-05 - Simple, lightweight tracing.

**[⬆ back to top](#contents)**

## Query Language

- [api-fu](https://github.com/ccbrown/api-fu) ⭐ 54 📅 2024-03-19 - Comprehensive GraphQL implementation.
- [dasel](https://github.com/tomwright/dasel) ⭐ 4,827 📅 2024-03-18 - Query and update data structures using selectors from the command line. Comparable to jq/yq but supports JSON, YAML, TOML and XML with zero runtime dependencies.
- [gojsonq](https://github.com/thedevsaddam/gojsonq) ⭐ 2,140 📅 2021-03-22 - A simple Go package to Query over JSON Data.
- [goven](https://github.com/SeldonIO/goven) ⭐ 56 📅 2022-04-14 - A drop-in query language for any database schema.
- [gqlgen](https://github.com/99designs/gqlgen) ⭐ 9,545 📅 2024-03-18 - go generate based graphql server library.
- [grapher](https://github.com/reaganiwadha/grapher) ⭐ 3 📅 2023-07-21 - A GraphQL field builder utilizing Go generics with extra utilities and features.
- [graphql](https://github.com/tmc/graphql) ⭐ 57 📅 2017-06-02 - graphql parser + utilities.
- [graphql](https://github.com/neelance/graphql-go) ⭐ 4,586 📅 2024-02-21 - GraphQL server with a focus on ease of use.
- [graphql-go](https://github.com/graphql-go/graphql) ⭐ 9,672 📅 2023-07-22 - Implementation of GraphQL for Go.
- [gws](https://github.com/Zaba505/gws) ⭐ 7 📅 2020-09-04 - Apollos' "GraphQL over Websocket" client and server implementation.
- [jsonpath](https://github.com/AsaiYusuke/jsonpath) ⭐ 21 📅 2023-10-28 - A query library for retrieving part of JSON based on JSONPath syntax.
- [jsonql](https://github.com/elgs/jsonql) ⭐ 273 📅 2020-03-29 - JSON query expression library in Golang.
- [jsonslice](https://github.com/bhmj/jsonslice) ⭐ 81 📅 2022-01-02 - Jsonpath queries with advanced filters.
- [mql](https://github.com/hashicorp/mql) ⭐ 31 📅 2023-12-19 - Model Query Language (mql) is a query language for your database models.
- [rql](https://github.com/a8m/rql) ⭐ 326 📅 2022-05-06 - Resource Query Language for REST API.
- [rqp](https://github.com/timsolov/rest-query-parser) ⭐ 67 📅 2023-04-28 - Query Parser for REST API. Filtering, validations, both `AND`, `OR` operations are supported directly in the query.
- [straf](https://github.com/SonicRoshan/straf) ⭐ 36 📅 2020-05-16 - Easily Convert Golang structs to GraphQL objects.

**[⬆ back to top](#contents)**

## Resource Embedding

- [debme](https://github.com/leaanthony/debme) ⭐ 29 📅 2021-06-06 - Create an `embed.FS` from an existing `embed.FS` subdirectory.
- [esc](https://github.com/mjibson/esc) ⭐ 640 📅 2023-10-19 - Embeds files into Go programs and provides http.FileSystem interfaces to them.
- [fileb0x](https://github.com/UnnoTed/fileb0x) ⭐ 633 📅 2021-02-14 - Simple tool to embed files in go with focus on "customization" and ease to use.
- [go-resources](https://github.com/omeid/go-resources) ⭐ 176 📅 2022-10-19 - Unfancy resources embedding with Go.
- [go.rice](https://github.com/GeertJohan/go.rice) - go.rice is a Go package that makes working with resources such as HTML, JS, CSS, images, and templates very easy.
- [mule](https://github.com/wlbr/mule) ⭐ 14 📅 2021-08-16 - Embed external resources like images, movies ... into Go source code to create single file binaries using `go generate`. Focused on simplicity.
- [packr](https://github.com/gobuffalo/packr) ⭐ 3,412 📅 2021-11-23 - The simple and easy way to embed static files into Go binaries.
- [rebed](https://github.com/soypat/rebed) ⭐ 29 📅 2022-02-18 - Recreate folder structures and files from Go 1.16's `embed.FS` type
- [statics](https://github.com/go-playground/statics) ⭐ 67 📅 2016-10-05 - Embeds static resources into go files for single binary compilation + works with http.FileSystem + symlinks.
- [statik](https://github.com/rakyll/statik) ⭐ 3,707 📅 2020-04-06 - Embeds static files into a Go executable.
- [templify](https://github.com/wlbr/templify) ⭐ 30 📅 2021-08-16 - Embed external template files into Go code to create single file binaries.
- [vfsgen](https://github.com/shurcooL/vfsgen) ⭐ 980 📅 2023-04-30 - Generates a vfsdata.go file that statically implements the given virtual filesystem.

**[⬆ back to top](#contents)**

## Science and Data Analysis

_Libraries for scientific computing and data analyzing._

- [assocentity](https://github.com/ndabAP/assocentity) ⭐ 14 📅 2023-05-27 - Package assocentity returns the average distance from words to a given entity.
- [bradleyterry](https://github.com/seanhagen/bradleyterry) ⭐ 9 📅 2019-05-02 - Provides a Bradley-Terry Model for pairwise comparisons.
- [calendarheatmap](https://github.com/nikolaydubina/calendarheatmap) ⭐ 385 📅 2024-03-21 - Calendar heatmap in plain Go inspired by Github contribution activity.
- [chart](https://github.com/vdobler/chart) ⭐ 766 📅 2021-06-03 - Simple Chart Plotting library for Go. Supports many graphs types.
- [dataframe-go](https://github.com/rocketlaunchr/dataframe-go) ⭐ 1,110 📅 2021-10-25 - Dataframes for machine-learning and statistics (similar to pandas).
- [decimal](https://github.com/db47h/decimal) ⭐ 39 📅 2022-07-17 - Package decimal implements arbitrary-precision decimal floating-point arithmetic.
- [evaler](https://github.com/soniah/evaler) ⭐ 52 📅 2018-07-27 - Simple floating point arithmetic expression evaluator.
- [ewma](https://github.com/VividCortex/ewma) ⭐ 427 📅 2021-04-26 - Exponentially-weighted moving averages.
- [geom](https://github.com/skelterjohn/geom) ⭐ 55 📅 2018-01-03 - 2D geometry for golang.
- [go-dsp](https://github.com/mjibson/go-dsp) ⭐ 841 📅 2018-05-08 - Digital Signal Processing for Go.
- [go-estimate](https://github.com/milosgajdos/go-estimate) ⭐ 107 📅 2023-11-02 - State estimation and filtering algorithms in Go.
- [go-gt](https://github.com/ThePaw/go-gt) ⭐ 10 📅 2013-04-03 - Graph theory algorithms written in "Go" language.
- [godesim](https://github.com/soypat/godesim) ⭐ 23 📅 2022-06-04 - Extended/multivariable ODE solver framework for event-based simulations with simple API.
- [goent](https://github.com/kzahedi/goent) ⭐ 34 📅 2019-04-03 - GO Implementation of Entropy Measures.
- [gograph](https://github.com/hmdsefi/gograph) ⭐ 43 📅 2024-02-17 - A golang generic graph library that provides mathematical graph-theory and algorithms.
- [gohistogram](https://github.com/VividCortex/gohistogram) ⭐ 173 📅 2020-12-15 - Approximate histograms for data streams.
- [gonum](https://github.com/gonum/gonum) ⭐ 7,204 📅 2024-03-15 - Gonum is a set of numeric libraries for the Go programming language. It contains libraries for matrices, statistics, optimization, and more.
- [gonum/plot](https://github.com/gonum/plot) ⭐ 2,612 📅 2023-09-02 - gonum/plot provides an API for building and drawing plots in Go.
- [goraph](https://github.com/gyuho/goraph) ⭐ 732 📅 2022-04-10 - Pure Go graph theory library(data structure, algorithm visualization).
- [gosl](https://github.com/cpmech/gosl) ⭐ 1,799 📅 2024-03-16 - Go scientific library for linear algebra, FFT, geometry, NURBS, numerical methods, probabilities, optimisation, differential equations, and more.
- [GoStats](https://github.com/OGFris/GoStats) ⭐ 20 📅 2019-01-14 - GoStats is an Open Source GoLang library for math statistics mostly used in Machine Learning domains, it covers most of the Statistical measures functions.
- [graph](https://github.com/yourbasic/graph) ⭐ 676 📅 2021-06-06 - Library of basic graph algorithms.
- [jsonl-graph](https://github.com/nikolaydubina/jsonl-graph) ⭐ 70 📅 2024-03-21 - Tool to manipulate JSONL graphs with graphviz support.
- [ode](https://github.com/ChristopherRabotin/ode) ⭐ 22 📅 2017-01-18 - Ordinary differential equation (ODE) solver which supports extended states and channel-based iteration stop conditions.
- [orb](https://github.com/paulmach/orb) ⭐ 816 📅 2024-01-29 - 2D geometry types with clipping, GeoJSON and Mapbox Vector Tile support.
- [pagerank](https://github.com/alixaxel/pagerank) ⭐ 80 📅 2020-01-05 - Weighted PageRank algorithm implemented in Go.
- [piecewiselinear](https://github.com/sgreben/piecewiselinear) ⭐ 26 📅 2023-12-10 - Tiny linear interpolation library.
- [PiHex](https://github.com/claygod/PiHex) ⭐ 20 📅 2022-11-20 - Implementation of the "Bailey-Borwein-Plouffe" algorithm for the hexadecimal number Pi.
- [rootfinding](https://github.com/khezen/rootfinding) ⭐ 11 📅 2020-03-22 - root-finding algorithms library for finding roots of quadratic functions.
- [sparse](https://github.com/james-bowman/sparse) ⭐ 150 📅 2021-07-29 - Go Sparse matrix formats for linear algebra supporting scientific and machine learning applications, compatible with gonum matrix libraries.
- [stats](https://github.com/montanaflynn/stats) ⭐ 2,870 📅 2023-05-11 - Statistics package with common functions missing from the Golang standard library.
- [streamtools](https://github.com/nytlabs/streamtools) ⭐ 1,313 📅 2015-04-02 - general purpose, graphical tool for dealing with streams of data.
- [TextRank](https://github.com/DavidBelicza/TextRank) ⭐ 193 📅 2021-07-08 - TextRank implementation in Golang with extendable features (summarization, weighting, phrase extraction) and multithreading (goroutine) support.
- [triangolatte](https://github.com/tchayen/triangolatte) ⭐ 36 📅 2021-08-04 - 2D triangulation library. Allows translating lines and polygons (both based on points) to the language of GPUs.

**[⬆ back to top](#contents)**

## Security

_Libraries that are used to help make your application more secure._

- [acmetool](https://github.com/hlandau/acme) ⭐ 2,019 📅 2023-01-08 - ACME (Let's Encrypt) client tool with automatic renewal.
- [acra](https://github.com/cossacklabs/acra) ⭐ 1,284 📅 2023-12-19 - Network encryption proxy to protect database-based applications from data leaks: strong selective encryption, SQL injections prevention, intrusion detection system.
- [age](https://github.com/FiloSottile/age) ⭐ 15,096 📅 2024-01-10 - A simple, modern and secure encryption tool (and Go library) with small explicit keys, no config options, and UNIX-style composability.
- [argon2-hashing](https://github.com/andskur/argon2-hashing) ⭐ 20 📅 2024-01-23 - light wrapper around Go's argon2 package that closely mirrors with Go's standard library Bcrypt and simple-scrypt package.
- [argon2pw](https://github.com/raja/argon2pw) ⭐ 90 📅 2021-09-10 - Argon2 password hash generation with constant-time password comparison.
- [autocert](https://pkg.go.dev/golang.org/x/crypto/acme/autocert) - Auto provision Let's Encrypt certificates and start a TLS server.
- [BadActor](https://github.com/jaredfolkins/badactor) ⭐ 319 📅 2020-05-28 - In-memory, application-driven jailer built in the spirit of fail2ban.
- [beelzebub](https://github.com/mariocandela/beelzebub) ⭐ 523 📅 2024-03-19 - A secure low code honeypot framework, leveraging AI for System Virtualization.
- [booster](https://github.com/anatol/booster) ⭐ 440 📅 2024-02-02 - Fast initramfs generator with full-disk encryption support.
- [Cameradar](https://github.com/Ullaakut/cameradar) ⭐ 3,843 📅 2023-10-17 - Tool and library to remotely hack RTSP streams from surveillance cameras.
- [certificates](https://github.com/mvmaasakkers/certificates) ⭐ 37 📅 2022-12-27 - An opinionated tool for generating tls certificates.
- [CertMagic](https://github.com/caddyserver/certmagic) ⭐ 4,772 📅 2024-03-21 - Mature, robust, and powerful ACME client integration for fully-managed TLS certificate issuance and renewal.
- [Coraza](https://github.com/corazawaf/coraza) ⭐ 1,747 📅 2024-03-15 - Enterprise-ready, modsecurity and OWASP CRS compatible WAF library.
- [dongle](https://github.com/golang-module/dongle) ⭐ 833 📅 2024-01-30 - A simple, semantic and developer-friendly golang package for encoding&decoding and encryption&decryption.
- [encid](https://github.com/bobg/encid) ⭐ 1 📅 2024-02-20 - Encode and decode encrypted integer IDs.
- [firewalld-rest](https://github.com/prashantgupta24/firewalld-rest) ⭐ 336 📅 2020-09-03 - A rest application to dynamically update firewalld rules on a linux server.
- [go-generate-password](https://github.com/m1/go-generate-password) ⭐ 52 📅 2022-04-17 - Password generator that can be used on the cli or as a library.
- [go-htpasswd](https://github.com/tg123/go-htpasswd) ⭐ 34 📅 2023-12-19 - Apache htpasswd Parser for Go.
- [go-password-validator](https://github.com/lane-c-wagner/go-password-validator) ⭐ 470 📅 2022-08-31 - Password validator based on raw cryptographic entropy values.
- [go-peer](https://github.com/number571/go-peer) ⭐ 180 📅 2024-03-21 - A software library for creating secure and anonymous decentralized systems.
- [go-yara](https://github.com/hillu/go-yara) ⭐ 339 📅 2024-01-22 - Go Bindings for [YARA](https://github.com/plusvic/yara) ⭐ 136 📅 2020-03-13, the "pattern matching swiss knife for malware researchers (and everyone else)".
- [goArgonPass](https://github.com/dwin/goArgonPass) ⭐ 16 📅 2020-12-11 - Argon2 password hash and verification designed to be compatible with existing Python and PHP implementations.
- [goSecretBoxPassword](https://github.com/dwin/goSecretBoxPassword) ⭐ 58 📅 2022-08-31 - A probably paranoid package for securely hashing and encrypting passwords.
- [Interpol](https://github.com/avahidi/interpol) ⭐ 2 📅 2022-05-29 - Rule-based data generator for fuzzing and penetration testing.
- [lego](https://github.com/go-acme/lego) ⭐ 7,171 📅 2024-03-20 - Pure Go ACME client library and CLI tool (for use with Let's Encrypt).
- [memguard](https://github.com/awnumar/memguard) ⭐ 2,470 📅 2023-12-04 - A pure Go library for handling sensitive values in memory.
- [nacl](https://github.com/kevinburke/nacl) ⭐ 542 📅 2021-04-05 - Go implementation of the NaCL set of API's.
- [optimus-go](https://github.com/pjebs/optimus-go) ⭐ 357 📅 2020-05-04 - ID hashing and Obfuscation using Knuth's Algorithm.
- [passlib](https://github.com/hlandau/passlib) ⭐ 288 📅 2021-03-23 - Futureproof password hashing library.
- [passwap](https://github.com/zitadel/passwap) ⭐ 34 📅 2024-03-05 - Provides a unified implementation between different password hashing algorithms
- [secret](https://github.com/rsjethani/secret) ⭐ 25 📅 2023-04-27 - Prevent your secrets from leaking into logs, std\* etc.
- [secure](https://github.com/unrolled/secure) ⭐ 2,198 📅 2023-12-27 - HTTP middleware for Go that facilitates some quick security wins.
- [secureio](https://github.com/xaionaro-go/secureio) ⭐ 32 📅 2020-06-28 - An keyexchanging+authenticating+encrypting wrapper and multiplexer for `io.ReadWriteCloser` based on XChaCha20-poly1305, ECDH and ED25519.
- [simple-scrypt](https://github.com/elithrar/simple-scrypt) ⭐ 192 📅 2018-06-06 - Scrypt package with a simple, obvious API and automatic cost calibration built-in.
- [ssh-vault](https://github.com/ssh-vault/ssh-vault) ⭐ 425 📅 2024-03-07 - encrypt/decrypt using ssh keys.
- [sslmgr](https://github.com/adrianosela/sslmgr) ⭐ 25 📅 2022-10-12 - SSL certificates made easy with a high level wrapper around acme/autocert.
- [teler-waf](https://github.com/kitabisa/teler-waf) ⭐ 268 📅 2024-03-22 - teler-waf is a Go HTTP middleware that provide teler IDS functionality to protect against web-based attacks and improve the security of Go-based web applications. It is highly configurable and easy to integrate into existing Go applications.
- [themis](https://github.com/cossacklabs/themis) ⭐ 1,795 📅 2023-12-12 - high-level cryptographic library for solving typical data security tasks (secure data storage, secure messaging, zero-knowledge proof authentication), available for 14 languages, best fit for multi-platform apps.

**[⬆ back to top](#contents)**

## Serialization

_Libraries and tools for binary serialization._

- [asn1](https://github.com/PromonLogicalis/asn1) ⭐ 53 📅 2019-03-12 - Asn.1 BER and DER encoding library for golang.
- [bambam](https://github.com/glycerine/bambam) ⭐ 65 📅 2016-10-07 - generator for Cap'n Proto schemas from go.
- [bel](https://github.com/32leaves/bel) ⭐ 36 📅 2019-04-18 - Generate TypeScript interfaces from Go structs/interfaces. Useful for JSON RPC.
- [binstruct](https://github.com/ghostiam/binstruct) ⭐ 86 📅 2022-04-24 - Golang binary decoder for mapping data into the structure.
- [cbor](https://github.com/fxamacker/cbor) ⭐ 651 📅 2024-03-20 - Small, safe, and easy CBOR encoding and decoding library.
- [colfer](https://github.com/pascaldekloe/colfer) ⭐ 729 📅 2023-10-30 - Code generation for the Colfer binary format.
- [csvutil](https://github.com/jszwec/csvutil) ⭐ 873 📅 2024-02-03 - High Performance, idiomatic CSV record encoding and decoding to native Go structures.
- [elastic](https://github.com/epiclabs-io/elastic) ⭐ 24 📅 2020-02-26 - Convert slices, maps or any other unknown value across different types at run-time, no matter what.
- [fixedwidth](https://github.com/huydang284/fixedwidth) ⭐ 9 📅 2019-12-12 - Fixed-width text formatting (UTF-8 supported).
- [fwencoder](https://github.com/o1egl/fwencoder) ⭐ 26 📅 2022-08-08 - Fixed width file parser (encoding and decoding library) for Go.
- [go-capnproto](https://github.com/glycerine/go-capnproto) ⭐ 288 📅 2019-01-18 - Cap'n Proto library and parser for go.
- [go-codec](https://github.com/ugorji/go) ⭐ 1,809 📅 2024-03-07 - High Performance, feature-Rich, idiomatic encode, decode and rpc library for msgpack, cbor and json, with runtime-based OR code-generation support.
- [go-lctree](https://github.com/sbourlon/go-lctree) ⭐ 4 📅 2020-06-03 - Provides a CLI and primitives to serialize and deserialize [LeetCode binary trees](https://support.leetcode.com/hc/en-us/articles/360011883654-What-does-1-null-2-3-mean-in-binary-tree-representation).
- [gogoprotobuf](https://github.com/gogo/protobuf) ⭐ 5,625 📅 2022-10-24 - Protocol Buffers for Go with Gadgets.
- [goprotobuf](https://github.com/golang/protobuf) ⭐ 9,498 📅 2024-03-06 - Go support, in the form of a library and protocol compiler plugin, for Google's protocol buffers.
- [gotiny](https://github.com/raszia/gotiny) ⭐ 16 📅 2024-01-16 - Efficient Go serialization library, gotiny is almost as fast as serialization libraries that generate code.
- [jsoniter](https://github.com/json-iterator/go) ⭐ 12,997 📅 2022-09-15 - High-performance 100% compatible drop-in replacement of "encoding/json".
- [mapstructure](https://github.com/mitchellh/mapstructure) ⭐ 7,591 📅 2023-12-16 - Go library for decoding generic map values into native Go structures.
- [php_session_decoder](https://github.com/yvasiyarov/php_session_decoder) ⭐ 160 📅 2018-08-03 - GoLang library for working with PHP session format and PHP Serialize/Unserialize functions.
- [pletter](https://github.com/vimeda/pletter) ⭐ 19 📅 2023-03-27 - A standard way to wrap a proto message for message brokers.
- [structomap](https://github.com/tuvistavie/structomap) ⭐ 144 📅 2019-05-16 - Library to easily and dynamically generate maps from static structures.
- [unitpacking](https://github.com/recolude/unitpacking) ⭐ 6 📅 2021-04-17 - Library to pack unit vectors into as fewest bytes as possible.

**[⬆ back to top](#contents)**

## Server Applications

- [algernon](https://github.com/xyproto/algernon) ⭐ 2,601 📅 2024-03-10 - HTTP/2 web server with built-in support for Lua, Markdown, GCSS and Amber.
- [Caddy](https://github.com/caddyserver/caddy) ⭐ 53,037 📅 2024-03-22 - Caddy is an alternative, HTTP/2 web server that's easy to configure and use.
- [consul](https://www.consul.io/) - Consul is a tool for service discovery, monitoring and configuration.
- [cortex-tenant](https://github.com/blind-oracle/cortex-tenant) ⭐ 94 📅 2024-03-08 - Prometheus remote write proxy that adds add Cortex tenant ID header based on metric labels.
- [devd](https://github.com/cortesi/devd) ⭐ 3,391 📅 2020-04-27 - Local webserver for developers.
- [discovery](https://github.com/Bilibili/discovery) ⭐ 1,764 📅 2020-12-04 - A registry for resilient mid-tier load balancing and failover.
- [dudeldu](https://github.com/krotik/dudeldu) ⭐ 144 📅 2019-09-22 - A simple SHOUTcast server.
- [dummy](https://github.com/neotoolkit/dummy) ⭐ 178 📅 2022-07-25 - Run mock server based off an API contract with one command.
- [Easegress](https://github.com/megaease/easegress) ⭐ 5,679 📅 2024-03-11 - A cloud native high availability/performance traffic orchestration system with observability and extensibility.
- [etcd](https://github.com/etcd-io/etcd) ⭐ 46,004 📅 2024-03-21 - Highly-available key value store for shared configuration and service discovery.
- [Euterpe](https://github.com/ironsmile/euterpe) ⭐ 514 📅 2023-04-02 - Self-hosted music streaming server with built-in web UI and REST API.
- [Fider](https://github.com/getfider/fider) ⭐ 2,585 📅 2023-07-16 - Fider is an open platform to collect and organize customer feedback.
- [Flagr](https://github.com/checkr/flagr) ⭐ 2,345 📅 2024-03-15 - Flagr is an open-source feature flagging and A/B testing service.
- [flipt](https://github.com/markphelps/flipt) ⭐ 3,245 📅 2024-03-21 - A self contained feature flag solution written in Go and Vue.js
- [go-feature-flag](https://github.com/thomaspoignant/go-feature-flag) ⭐ 1,039 📅 2024-03-21 - A simple, complete and lightweight self-hosted feature flag solution 100% Open Source.
- [go-proxy-cache](https://github.com/fabiocicerchia/go-proxy-cache) ⭐ 116 📅 2023-12-08 - Simple Reverse Proxy with Caching, written in Go, using Redis.
- [jackal](https://github.com/ortuman/jackal) ⭐ 1,442 📅 2023-03-01 - An XMPP server written in Go.
- [lets-proxy2](https://github.com/rekby/lets-proxy2) ⭐ 91 📅 2024-03-07 - Reverse proxy for handle https with issue certificates in fly from lets-encrypt.
- [minio](https://github.com/minio/minio) ⭐ 43,646 📅 2024-03-21 - Minio is a distributed object storage server.
- [Moxy](https://github.com/sinhashubham95/moxy) ⭐ 12 📅 2022-05-17 - Moxy is a simple mocker and proxy application server, you can create mock endpoints as well as proxy requests in case no mock exists for the endpoint.
- [nginx-prometheus](https://github.com/blind-oracle/nginx-prometheus) ⭐ 40 📅 2020-09-16 - Nginx log parser and exporter to Prometheus.
- [nsq](https://nsq.io/) - A realtime distributed messaging platform.
- [protoxy](https://github.com/camgraff/protoxy) ⭐ 34 📅 2020-11-08 - A proxy server that converts JSON request bodies to Protocol Buffers.
- [psql-streamer](https://github.com/blind-oracle/psql-streamer) ⭐ 57 📅 2020-03-10 - Stream database events from PostgreSQL to Kafka.
- [riemann-relay](https://github.com/blind-oracle/riemann-relay) ⭐ 2 📅 2019-10-29 - Relay to load-balance Riemann events and/or convert them to Carbon.
- [RoadRunner](https://github.com/spiral/roadrunner) ⭐ 7,644 📅 2024-03-18 - High-performance PHP application server, load-balancer and process manager.
- [SFTPGo](https://github.com/drakkan/sftpgo) ⭐ 7,904 📅 2024-03-18 - Fully featured and highly configurable SFTP server with optional FTP/S and WebDAV support. It can serve local filesystem and Cloud Storage backends such as S3 and Google Cloud Storage.
- [simple-jwt-provider](https://github.com/leberKleber/simple-jwt-provider) ⭐ 39 📅 2021-10-06 - Simple and lightweight provider which exhibits JWTs, supports login, password-reset (via mail) and user management.
- [Trickster](https://github.com/tricksterproxy/trickster) ⭐ 1,944 📅 2024-02-18 - HTTP reverse proxy cache and time series accelerator.
- [Wish](https://github.com/charmbracelet/wish) ⭐ 2,826 📅 2024-03-08 - Make SSH apps, just like that!

**[⬆ back to top](#contents)**

## Stream Processing

_Libraries and tools for stream processing and reactive programming._

- [go-streams](https://github.com/reugn/go-streams) ⭐ 1,716 📅 2024-03-09 - Go stream processing library.
- [goio](https://github.com/primetalk/goio) ⭐ 77 📅 2023-06-29 - An implementation of IO, Stream, Fiber for Golang, inspired by awesome Scala libraries cats and fs2.
- [machine](https://github.com/whitaker-io/machine) ⭐ 142 📅 2024-03-06 - Go library for writing and generating stream workers with built in metrics and traceability.
- [stream](https://github.com/youthlin/stream) ⭐ 85 📅 2024-02-08 - Go Stream, like Java 8 Stream: Filter/Map/FlatMap/Peek/Sorted/ForEach/Reduce...

**[⬆ back to top](#contents)**

## Template Engines

_Libraries and tools for templating and lexing._

- [ego](https://github.com/benbjohnson/ego) ⭐ 577 📅 2021-07-14 - Lightweight templating language that lets you write templates in Go. Templates are translated into Go and compiled.
- [extemplate](https://github.com/dannyvankooten/extemplate) ⭐ 56 📅 2022-12-06 - Tiny wrapper around html/template to allow for easy file-based template inheritance.
- [fasttemplate](https://github.com/valyala/fasttemplate) ⭐ 799 📅 2022-10-18 - Simple and fast template engine. Substitutes template placeholders up to 10x faster than [text/template](https://golang.org/pkg/text/template/).
- [gomponents](https://www.gomponents.com) - HTML 5 components in pure Go, that look something like this: `func(name string) g.Node { return Div(Class("headline"), g.Textf("Hi %v!", name)) }`.
- [gospin](https://github.com/m1/gospin) ⭐ 54 📅 2020-05-06 - Article spinning and spintax/spinning syntax engine, useful for A/B, testing pieces of text/articles and creating more natural conversations.
- [got](https://github.com/goradd/got) ⭐ 26 📅 2023-11-12 - A Go code generator inspired by Hero and Fasttemplate. Has include files, custom tag definitions, injected Go code, language translation, and more.
- [goview](https://github.com/foolin/goview) ⭐ 396 📅 2023-03-13 - Goview is a lightweight, minimalist and idiomatic template library based on golang html/template for building Go web application.
- [jet](https://github.com/CloudyKit/jet) ⭐ 1,164 📅 2024-03-06 - Jet template engine.
- [liquid](https://github.com/osteele/liquid) ⭐ 260 📅 2023-09-24 - Go implementation of Shopify Liquid templates.
- [maroto](https://github.com/johnfercher/maroto) ⭐ 1,414 📅 2024-03-20 - A maroto way to create PDFs. Maroto is inspired in Bootstrap and uses gofpdf. Fast and simple.
- [pongo2](https://github.com/flosch/pongo2) ⭐ 2,761 📅 2023-04-11 - Django-like template-engine for Go.
- [quicktemplate](https://github.com/valyala/quicktemplate) ⭐ 2,986 📅 2021-09-15 - Fast, powerful, yet easy to use template engine. Converts templates into Go code and then compiles it.
- [raymond](https://github.com/aymerick/raymond) ⭐ 580 📅 2018-03-22 - Complete handlebars implementation in Go.
- [Razor](https://github.com/sipin/gorazor) ⭐ 838 📅 2023-09-14 - Razor view engine for Golang.
- [Soy](https://github.com/robfig/soy) ⭐ 172 📅 2024-03-18 - Closure templates (aka Soy templates) for Go, following the [official spec](https://developers.google.com/closure/templates/).
- [sprig](https://github.com/Masterminds/sprig) ⭐ 3,951 📅 2022-11-29 - Useful template functions for Go templates.
- [tbd](https://github.com/lucasepe/tbd) ⭐ 25 📅 2021-08-29 - A really simple way to create text templates with placeholders - exposes extra builtin Git repo metadata.
- [templ](https://github.com/a-h/templ) ⭐ 6,078 📅 2024-03-21 - A HTML templating language that has great developer tooling.

**[⬆ back to top](#contents)**

## Testing

_Libraries for testing codebases and generating test data._

- Testing Frameworks

  - [apitest](https://apitest.dev) - Simple and extensible behavioural testing library for REST based services or HTTP handlers that supports mocking external http calls and rendering of sequence diagrams.
  - [assert](https://github.com/go-playground/assert) ⭐ 62 📅 2022-09-06 - Basic Assertion Library used along side native go testing, with building blocks for custom assertions.
  - [badio](https://github.com/cavaliercoder/badio) ⭐ 12 📅 2016-02-13 - Extensions to Go's `testing/iotest` package.
  - [baloo](https://github.com/h2non/baloo) ⭐ 771 📅 2022-08-09 - Expressive and versatile end-to-end HTTP API testing made easy.
  - [be](https://github.com/carlmjohnson/be) ⭐ 89 📅 2023-10-18 - The minimalist generic test assertion library.
  - [biff](https://github.com/fulldump/biff) ⭐ 14 📅 2023-01-11 - Bifurcation testing framework, BDD compatible.
  - [charlatan](https://github.com/percolate/charlatan) ⭐ 200 📅 2023-03-16 - Tool to generate fake interface implementations for tests.
  - [commander](https://github.com/SimonBaeumer/commander) ⭐ 222 📅 2023-11-05 - Tool for testing cli applications on windows, linux and osx.
  - [covergates](https://github.com/covergates/covergates) ⭐ 61 📅 2020-10-09 - Self-hosted code coverage report review and management service.
  - [cupaloy](https://github.com/bradleyjkemp/cupaloy) ⭐ 282 📅 2022-09-14 - Simple snapshot testing addon for your test framework.
  - [dbcleaner](https://github.com/khaiql/dbcleaner) ⭐ 157 📅 2021-11-10 - Clean database for testing purpose, inspired by `database_cleaner` in Ruby.
  - [dsunit](https://github.com/viant/dsunit) ⭐ 43 📅 2024-03-15 - Datastore testing for SQL, NoSQL, structured files.
  - [embedded-postgres](https://github.com/fergusstrange/embedded-postgres) ⭐ 722 📅 2024-02-28 - Run a real Postgres database locally on Linux, OSX or Windows as part of another Go application or test.
  - [endly](https://github.com/viant/endly) ⭐ 252 📅 2024-03-11 - Declarative end to end functional testing.
  - [fixenv](https://github.com/rekby/fixenv) ⭐ 27 📅 2023-11-26 - Fixture manage engine, inspired by pytest fixtures.
  - [fluentassert](https://github.com/fluentassert/verify) ⭐ 39 📅 2024-03-14 - Extensible, type-safe, fluent assertion Go library.
  - [flute](https://github.com/suzuki-shunsuke/flute) ⭐ 18 📅 2022-01-07 - HTTP client testing framework.
  - [frisby](https://github.com/verdverm/frisby) ⭐ 277 📅 2017-06-04 - REST API testing framework.
  - [gherkingen](https://github.com/hedhyw/gherkingen) ⭐ 67 📅 2024-02-01 - BDD boilerplate generator and framework.
  - [ginkgo](https://onsi.github.io/ginkgo/) - BDD Testing Framework for Go.
  - [gnomock](https://github.com/orlangure/gnomock) ⭐ 1,295 📅 2023-08-26 - integration testing with real dependencies (database, cache, even Kubernetes or AWS) running in Docker, without mocks.
  - [go-carpet](https://github.com/msoap/go-carpet) ⭐ 242 📅 2024-03-16 - Tool for viewing test coverage in terminal.
  - [go-cmp](https://github.com/google/go-cmp) ⭐ 3,930 📅 2023-08-31 - Package for comparing Go values in tests.
  - [go-hit](https://github.com/Eun/go-hit) ⭐ 246 📅 2024-02-13 - Hit is an http integration test framework written in golang.
  - [go-mutesting](https://github.com/zimmski/go-mutesting) ⭐ 616 📅 2021-06-10 - Mutation testing for Go source code.
  - [go-mysql-test-container](https://github.com/arikama/go-mysql-test-container) ⭐ 2 📅 2022-06-08 - Golang MySQL testcontainer to help with MySQL integration testing.
  - [go-snaps](http://github.com/gkampitakis/go-snaps) ⭐ 123 📅 2024-02-04 - Jest-like snapshot testing in Golang.
  - [go-testdeep](https://github.com/maxatome/go-testdeep) ⭐ 417 📅 2024-03-18 - Extremely flexible golang deep comparison, extends the go testing package.
  - [go-testpredicate](https://github.com/maargenton/go-testpredicate) ⭐ 5 📅 2021-11-20 - Test predicate style assertions library with extensive diagnostics output.
  - [go-vcr](https://github.com/dnaeon/go-vcr) ⭐ 1,085 📅 2024-03-13 - Record and replay your HTTP interactions for fast, deterministic and accurate tests.
  - [goblin](https://github.com/franela/goblin) ⭐ 885 📅 2021-10-03 - Mocha like testing framework of Go.
  - [goc](https://github.com/qiniu/goc) ⭐ 761 📅 2024-01-11 - Goc is a comprehensive coverage testing system for The Go Programming Language.
  - [gocheck](https://labix.org/gocheck) - More advanced testing framework alternative to gotest.
  - [GoConvey](https://github.com/smartystreets/goconvey/) ⭐ 8,068 📅 2024-03-06 - BDD-style framework with web UI and live reload.
  - [gocrest](https://github.com/corbym/gocrest) ⭐ 99 📅 2023-04-11 - Composable hamcrest-like matchers for Go assertions.
  - [godog](https://github.com/cucumber/godog) ⭐ 2,163 📅 2024-02-06 - Cucumber BDD framework for Go.
  - [gofight](https://github.com/appleboy/gofight) ⭐ 438 📅 2021-06-27 - API Handler Testing for Golang Router framework.
  - [gogiven](https://github.com/corbym/gogiven) ⭐ 14 📅 2023-04-03 - YATSPEC-like BDD testing framework for Go.
  - [gomatch](https://github.com/jfilipczyk/gomatch) ⭐ 46 📅 2021-01-15 - library created for testing JSON against patterns.
  - [gomega](https://onsi.github.io/gomega/) - Rspec like matcher/assertion library.
  - [Gont](https://github.com/stv0g/gont) ⭐ 70 📅 2024-03-18 - Go network testing toolkit for testing building complex network topologies using Linux namespaces.
  - [gospecify](https://github.com/stesla/gospecify) ⭐ 53 📅 2011-06-18 - This provides a BDD syntax for testing your Go code. It should be familiar to anybody who has used libraries such as rspec.
  - [gosuite](https://github.com/pavlo/gosuite) ⭐ 12 📅 2016-10-18 - Brings lightweight test suites with setup/teardown facilities to `testing` by leveraging Go1.7's Subtests.
  - [got](https://github.com/ysmood/got) ⭐ 263 📅 2024-01-08 - An enjoyable golang test framework.
  - [gotest.tools](https://github.com/gotestyourself/gotest.tools) - A collection of packages to augment the go testing package and support common patterns.
  - [Hamcrest](https://github.com/rdrdr/hamcrest) ⭐ 29 📅 2021-01-07 - fluent framework for declarative Matcher objects that, when applied to input values, produce self-describing results.
  - [httpexpect](https://github.com/gavv/httpexpect) ⭐ 2,438 📅 2023-12-18 - Concise, declarative, and easy to use end-to-end HTTP and REST API testing.
  - [is](https://github.com/matryer/is) ⭐ 1,705 📅 2023-05-03 - Professional lightweight testing mini-framework for Go.
  - [jsonassert](https://github.com/kinbiko/jsonassert) ⭐ 117 📅 2023-06-24 - Package for verifying that your JSON payloads are serialized correctly.
  - [omg.testingtools](https://github.com/dedalqq/omg.testingtools) - The simple library for change a values of private fields for testing.
  - [restit](https://github.com/yookoala/restit) ⭐ 55 📅 2023-11-15 - Go micro framework to help writing RESTful API integration test.
  - [schema](https://github.com/jgroeneveld/schema) ⭐ 21 📅 2019-10-13 - Quick and easy expression matching for JSON schemas used in requests and responses.
  - [stop-and-go](https://github.com/elgohr/stop-and-go) ⭐ 10 📅 2024-03-01 - Testing helper for concurrency.
  - [testcase](https://github.com/adamluzsi/testcase) ⭐ 114 📅 2024-03-06 - Idiomatic testing framework for Behavior Driven Development.
  - [testcontainers-go](https://github.com/testcontainers/testcontainers-go) ⭐ 2,949 📅 2024-03-21 - A Go package that makes it simple to create and clean up container-based dependencies for automated integration/smoke tests. The clean, easy-to-use API enables developers to programmatically define containers that should be run as part of a test and clean up those resources when the test is done.
  - [testfixtures](https://github.com/go-testfixtures/testfixtures) ⭐ 1,033 📅 2024-02-18 - A helper for Rails' like test fixtures to test database applications.
  - [Testify](https://github.com/stretchr/testify) ⭐ 21,788 📅 2024-03-19 - Sacred extension to the standard go testing package.
  - [testsql](https://github.com/zhulongcheng/testsql) ⭐ 17 📅 2019-09-26 - Generate test data from SQL files before testing and clear it after finished.
  - [testza](https://github.com/MarvinJWendt/testza) ⭐ 415 📅 2023-02-03 - Full-featured test framework with nice colorized output.
  - [trial](https://github.com/jgroeneveld/trial) ⭐ 6 📅 2022-10-05 - Quick and easy extendable assertions without introducing much boilerplate.
  - [Tt](https://github.com/vcaesar/tt) ⭐ 7 📅 2023-08-23 - Simple and colorful test tools.
  - [wstest](https://github.com/posener/wstest) ⭐ 102 📅 2020-12-30 - Websocket client for unit-testing a websocket http.Handler.

- Mock

  - [counterfeiter](https://github.com/maxbrunsfeld/counterfeiter) ⭐ 913 📅 2024-03-19 - Tool for generating self-contained mock objects.
  - [genmock](https://gitlab.com/so_literate/genmock) - Go mocking system with code generator for building calls of the interface methods.
  - [go-localstack](https://github.com/elgohr/go-localstack) ⭐ 74 📅 2024-03-20 - Tool for using localstack in AWS testing.
  - [go-sqlmock](https://github.com/DATA-DOG/go-sqlmock) ⭐ 5,775 📅 2024-01-15 - Mock SQL driver for testing database interactions.
  - [go-txdb](https://github.com/DATA-DOG/go-txdb) ⭐ 610 📅 2024-03-13 - Single transaction based database driver mainly for testing purposes.
  - [gock](https://github.com/h2non/gock) ⭐ 2,004 📅 2023-12-28 - Versatile HTTP mocking made easy.
  - [gomock](https://github.com/golang/mock) ⭐ 9,211 📅 2023-06-27 - Mocking framework for the Go programming language.
  - [govcr](https://github.com/seborama/govcr) ⭐ 161 📅 2023-07-29 - HTTP mock for Golang: record and replay HTTP interactions for offline testing.
  - [hoverfly](https://github.com/SpectoLabs/hoverfly) ⭐ 2,302 📅 2024-03-20 - HTTP(S) proxy for recording and simulating REST/SOAP APIs with extensible middleware and easy-to-use CLI.
  - [httpmock](https://github.com/jarcoal/httpmock) ⭐ 1,856 📅 2024-02-07 - Easy mocking of HTTP responses from external resources.
  - [minimock](https://github.com/gojuno/minimock) ⭐ 548 📅 2024-02-01 - Mock generator for Go interfaces.
  - [mockery](https://github.com/vektra/mockery) ⭐ 5,531 📅 2024-03-13 - Tool to generate Go interfaces.
  - [mockhttp](https://github.com/tv42/mockhttp) ⭐ 23 📅 2014-10-29 - Mock object for Go http.ResponseWriter.
  - [mockit](https://github.com/pasdam/mockit) ⭐ 16 📅 2023-04-05 - Allows functions and method easy mocking, without defining new types; it's similar to Mockito for Java.
  - [monkey](https://github.com/awterman/monkey) ⭐ 2 📅 2023-11-13 - One line to mock functions/methods/variables in place without dependency injection or code generation.
  - [mooncake](https://github.com/GuilhermeCaruso/mooncake) ⭐ 18 📅 2022-09-18 - A simple way to generate mocks for multiple purposes
  - [timex](https://github.com/cabify/timex) ⭐ 70 📅 2020-08-03 - A test-friendly replacement for the native `time` package.

- Fuzzing and delta-debugging/reducing/shrinking.

  - [go-fuzz](https://github.com/dvyukov/go-fuzz) ⭐ 4,700 📅 2024-02-02 - Randomized testing system.
  - [gofuzz](https://github.com/google/gofuzz) ⭐ 1,480 📅 2022-10-18 - Library for populating go objects with random values.
  - [Tavor](https://github.com/zimmski/tavor) ⭐ 243 📅 2018-10-31 - Generic fuzzing and delta-debugging framework.

- Selenium and browser control tools.

  - [cdp](https://github.com/mafredri/cdp) ⭐ 714 📅 2023-04-04 - Type-safe bindings for the Chrome Debugging Protocol that can be used with browsers or other debug targets that implement it.
  - [chromedp](https://github.com/knq/chromedp) ⭐ 10,231 📅 2024-02-04 - a way to drive/test Chrome, Safari, Edge, Android Webviews, and other browsers supporting the Chrome Debugging Protocol.
  - [ggr](https://github.com/aerokube/ggr) ⭐ 310 📅 2024-01-09 - a lightweight server that routes and proxies Selenium WebDriver requests to multiple Selenium hubs.
  - [playwright-go](https://github.com/mxschmitt/playwright-go) ⭐ 1,719 📅 2024-03-21 - browser automation library to control Chromium, Firefox and WebKit with a single API.
  - [rod](https://github.com/go-rod/rod) ⭐ 4,651 📅 2024-02-18 - A Devtools driver to make web automation and scraping easy.
  - [selenoid](https://github.com/aerokube/selenoid) ⭐ 2,477 📅 2024-03-22 - alternative Selenium hub server that launches browsers within containers.

- Fail injection
  - [failpoint](https://github.com/pingcap/failpoint) ⭐ 799 📅 2022-08-01 - An implementation of [failpoints](https://www.freebsd.org/cgi/man.cgi?query=fail) for Golang.

**[⬆ back to top](#contents)**

## Text Processing

_Libraries for parsing and manipulating texts._

See also [Natural Language Processing](#natural-language-processing) and [Text Analysis](#text-analysis).

### Formatters

- [address](https://github.com/bojanz/address) ⭐ 69 📅 2024-02-25 - Handles address representation, validation and formatting.
- [align](https://github.com/Guitarbum722/align) ⭐ 83 📅 2021-09-12 - A general purpose application that aligns text.
- [bytes](https://github.com/labstack/gommon/tree/master/bytes) - Formats and parses numeric byte values (10K, 2M, 3G, etc.).
- [go-fixedwidth](https://github.com/ianlopshire/go-fixedwidth) ⭐ 80 📅 2024-02-08 - Fixed-width text formatting (encoder/decoder with reflection).
- [go-humanize](https://github.com/dustin/go-humanize) ⭐ 3,975 📅 2023-10-09 - Formatters for time, numbers, and memory size to human readable format.
- [gotabulate](https://github.com/bndr/gotabulate) ⭐ 309 📅 2021-02-09 - Easily pretty-print your tabular data with Go.
- [textwrap](https://github.com/isbm/textwrap) ⭐ 5 📅 2019-07-29 - Wraps text at end of lines. Implementation of `textwrap` module from Python.

### Markup Languages

- [bafi](https://github.com/mmalcek/bafi) ⭐ 92 📅 2024-03-07 - Universal JSON, BSON, YAML, XML translator to ANY format using templates.
- [bbConvert](https://github.com/CalebQ42/bbConvert) ⭐ 8 📅 2024-01-01 - Converts bbCode to HTML that allows you to add support for custom bbCode tags.
- [blackfriday](https://github.com/russross/blackfriday) ⭐ 5,342 📅 2020-10-27 - Markdown processor in Go.
- [go-output-format](https://github.com/drewstinnett/go-output-format) ⭐ 14 📅 2024-02-24 - Output go structures into multiple formats (YAML/JSON/etc) in your command line app.
- [go-toml](https://github.com/pelletier/go-toml) ⭐ 1,592 📅 2024-03-19 - Go library for the TOML format with query support and handy cli tools.
- [goldmark](https://github.com/yuin/goldmark) ⭐ 3,249 📅 2024-02-29 - A Markdown parser written in Go. Easy to extend, standard (CommonMark) compliant, well structured.
- [goq](https://github.com/andrewstuart/goq) ⭐ 251 📅 2021-09-02 - Declarative unmarshalling of HTML using struct tags with jQuery syntax (uses GoQuery).
- [html-to-markdown](https://github.com/JohannesKaufmann/html-to-markdown) ⭐ 692 📅 2023-12-27 - Convert HTML to Markdown. Even works with entire websites and can be extended through rules.
- [htmlquery](https://github.com/antchfx/htmlquery) ⭐ 687 📅 2024-03-20 - An XPath query package for HTML, lets you extract data or evaluate from HTML documents by an XPath expression.
- [htmlyaml](https://github.com/nikolaydubina/htmlyaml) ⭐ 4 📅 2024-03-21 -  Rich rendering of YAML as HTML in Go
- [htree](https://github.com/bobg/htree) ⭐ 4 📅 2024-01-27 - Traverse, navigate, filter, and otherwise process trees of [html.Node](https://pkg.go.dev/golang.org/x/net/html#Node) objects.
- [mxj](https://github.com/clbanning/mxj) ⭐ 603 📅 2023-10-11 - Encode / decode XML as JSON or map[string]interface{}; extract values with dot-notation paths and wildcards. Replaces x2j and j2x packages.
- [toml](https://github.com/BurntSushi/toml) ⭐ 4,415 📅 2024-01-03 - TOML configuration format (encoder/decoder with reflection).

### Parsers/Encoders/Decoders

- [allot](https://github.com/sbstjn/allot) ⭐ 58 📅 2016-10-24 - Placeholder and wildcard text parsing for CLI tools and bots.
- [codetree](https://github.com/aerogo/codetree) ⭐ 23 📅 2019-10-26 - Parses indented code (python, pixy, scarlet, etc.) and returns a tree structure.
- [commonregex](https://github.com/mingrammer/commonregex) ⭐ 881 📅 2019-11-12 - A collection of common regular expressions for Go.
- [did](https://github.com/ockam-network/did) ⭐ 83 📅 2021-01-03 - DID (Decentralized Identifiers) Parser and Stringer in Go.
- [doi](https://github.com/hscells/doi) ⭐ 8 📅 2017-08-21 - Document object identifier (doi) parser in Go.
- [editorconfig-core-go](https://github.com/editorconfig/editorconfig-core-go) ⭐ 128 📅 2024-03-11 - Editorconfig file parser and manipulator for Go.
- [encdec](https://github.com/mickep76/encdec) ⭐ 9 📅 2019-11-12 - Package provides a generic interface to encoders and decoders.
- [go-fasttld](https://github.com/elliotwutingfeng/go-fasttld) ⭐ 29 📅 2024-03-04 - High performance effective top level domains (eTLD) extraction module.
- [go-nmea](https://github.com/adrianmo/go-nmea) ⭐ 205 📅 2023-07-02 - NMEA parser library for the Go language.
- [go-vcard](https://github.com/emersion/go-vcard) ⭐ 97 📅 2023-08-15 - Parse and format vCard.
- [gofeed](https://github.com/mmcdole/gofeed) ⭐ 2,419 📅 2024-03-01 - Parse RSS and Atom feeds in Go.
- [gographviz](https://github.com/awalterschulze/gographviz) ⭐ 541 📅 2023-02-28 - Parses the Graphviz DOT language.
- [gonameparts](https://github.com/polera/gonameparts) ⭐ 40 📅 2017-05-26 - Parses human names into individual name parts.
- [ltsv](https://github.com/Wing924/ltsv) ⭐ 8 📅 2019-06-23 - High performance [LTSV (Labeled Tab Separated Value)](http://ltsv.org/) reader for Go.
- [normalize](https://github.com/avito-tech/normalize) ⭐ 42 📅 2021-03-23 - Sanitize, normalize and compare fuzzy text.
- [omniparser](https://github.com/jf-tech/omniparser) ⭐ 618 📅 2023-10-09 - A versatile ETL library that parses text input (CSV/txt/JSON/XML/EDI/X12/EDIFACT/etc) in streaming fashion and transforms data into JSON output using data-driven schema.
- [parseargs-go](https://github.com/nproc/parseargs-go) ⭐ 10 📅 2017-01-24 - string argument parser that understands quotes and backslashes.
- [parth](https://github.com/codemodus/parth) ⭐ 46 📅 2019-02-01 - URL path segmentation parsing.
- [sdp](https://github.com/gortc/sdp) ⭐ 113 📅 2020-05-01 - SDP: Session Description Protocol [[RFC 4566](https://tools.ietf.org/html/rfc4566)].
- [sh](https://github.com/mvdan/sh) ⭐ 6,688 📅 2024-02-25 - Shell parser and formatter.
- [tokenizer](https://github.com/bzick/tokenizer) ⭐ 79 📅 2023-10-23 - Parse any string, slice or infinite buffer to any tokens.
- [when](https://github.com/olebedev/when) ⭐ 1,311 📅 2023-12-02 - Natural EN and RU language date/time parser with pluggable rules.
- [xj2go](https://github.com/stackerzzq/xj2go) ⭐ 34 📅 2021-10-12 - Convert xml or json to go struct.

### Regular Expressions

- [genex](https://github.com/alixaxel/genex) ⭐ 76 📅 2020-01-05 - Count and expand Regular Expressions into all matching Strings.
- [go-wildcard](https://github.com/IGLOU-EU/go-wildcard) ⭐ 68 📅 2023-08-16 - Simple and lightweight wildcard pattern matching.
- [goregen](https://github.com/zach-klippenstein/goregen) ⭐ 89 📅 2016-03-03 - Library for generating random strings from regular expressions.
- [regroup](https://github.com/oriser/regroup) ⭐ 141 📅 2023-05-27 - Match regex expression named groups into go struct using struct tags and automatic parsing.
- [rex](https://github.com/hedhyw/rex) ⭐ 179 📅 2024-02-01 - Regular expressions builder.

### Sanitation

- [bluemonday](https://github.com/microcosm-cc/bluemonday) ⭐ 2,942 📅 2023-12-11 - HTML Sanitizer.
- [gofuckyourself](https://github.com/JoshuaDoes/gofuckyourself) ⭐ 61 📅 2023-04-16 - A sanitization-based swear filter for Go.

### Scrapers

- [colly](https://github.com/asciimoo/colly) ⭐ 21,904 📅 2023-10-20 - Fast and Elegant Scraping Framework for Gophers.
- [dataflowkit](https://github.com/slotix/dataflowkit) ⭐ 638 📅 2020-06-12 - Web scraping Framework to turn websites into structured data.
- [go-recipe](https://github.com/kkyr/go-recipe) ⭐ 26 📅 2023-03-16 - A package for scraping recipes from websites.
- [GoQuery](https://github.com/PuerkitoBio/goquery) ⭐ 13,463 📅 2024-02-29 - GoQuery brings a syntax and a set of features similar to jQuery to the Go language.
- [gospider](https://github.com/zhshch2002/gospider) ⭐ 204 📅 2021-03-16 - A simple golang spider/scraping framework,build a spider in 3 lines. migrated from [goribot](https://github.com/zhshch2002/goribot) ⭐ 210 📅 2020-07-04
- [pagser](https://github.com/foolin/pagser) ⭐ 97 📅 2023-10-15 - Pagser is a simple, extensible, configurable parse and deserialize html page to struct based on goquery and struct tags for golang crawler.
- [Tagify](https://github.com/zoomio/tagify) ⭐ 36 📅 2023-10-07 - Produces a set of tags from given source.
- [walker](https://github.com/cyucelen/walker) ⭐ 7 📅 2023-02-17 - Seamlessly fetch paginated data from any source. Simple and high performance API scraping included.
- [xurls](https://github.com/mvdan/xurls) ⭐ 1,144 📅 2024-01-01 - Extract urls from text.

### RSS

- [podcast](https://github.com/eduncan911/podcast) ⭐ 127 📅 2020-11-02 - iTunes Compliant and RSS 2.0 Podcast Generator in Golang

### Utility/Miscellaneous

- [go-runewidth](https://github.com/mattn/go-runewidth) ⭐ 578 📅 2023-07-23 - Functions to get fixed width of the character or string.
- [go-zero-width](https://github.com/trubitsyn/go-zero-width) ⭐ 111 📅 2020-08-06 - Zero-width character detection and removal for Go.
- [kace](https://github.com/codemodus/kace) ⭐ 20 📅 2018-08-26 - Common case conversions covering common initialisms.
- [petrovich](https://github.com/striker2000/petrovich) ⭐ 45 📅 2023-11-29 - Petrovich is the library which inflects Russian names to given grammatical case.
- [radix](https://github.com/yourbasic/radix) ⭐ 189 📅 2018-03-08 - Fast string sorting algorithm.
- [TySug](https://github.com/Dynom/TySug) ⭐ 17 📅 2023-02-23 - Alternative suggestions with respect to keyboard layouts.

**[⬆ back to top](#contents)**

## Third-party APIs

_Libraries for accessing third party APIs._

- [airtable](https://github.com/mehanizm/airtable) ⭐ 70 📅 2023-07-09 - Go client library for the [Airtable API](https://airtable.com/api).
- [amazon-product-advertising-api](https://github.com/ngs/go-amazon-product-advertising-api) ⭐ 57 📅 2016-12-03 - Go Client Library for [Amazon Product Advertising API](https://affiliate-program.amazon.com/gp/advertising/api/detail/main.html).
- [anaconda](https://github.com/ChimeraCoder/anaconda) ⭐ 1,141 📅 2018-10-14 - Go client library for the Twitter 1.1 API.
- [appstore-sdk-go](https://github.com/Kachit/appstore-sdk-go) ⭐ 5 📅 2024-01-26 - Unofficial Golang SDK for AppStore Connect API.
- [aws-sdk-go](https://github.com/aws/aws-sdk-go-v2) ⭐ 2,348 📅 2024-03-21 - The official AWS SDK for the Go programming language.
- [bqwriter](https://github.com/OTA-Insight/bqwriter) ⭐ 15 📅 2023-09-11 - High Level Go Library to write data into [Google BigQuery](https://cloud.google.com/bigquery) at a high throughout.
- [brewerydb](https://github.com/naegelejd/brewerydb) ⭐ 19 📅 2015-06-18 - Go library for accessing the BreweryDB API.
- [cachet](https://github.com/andygrunwald/cachet) ⭐ 91 📅 2021-06-22 - Go client library for [Cachet (open source status page system)](https://cachethq.io/).
- [circleci](https://github.com/jszwedko/go-circleci) ⭐ 66 📅 2024-01-27 - Go client library for interacting with CircleCI's API.
- [clarifai](https://github.com/samuelcouch/clarifai) ⭐ 55 📅 2017-08-28 - Go client library for interfacing with the Clarifai API.
- [codeship-go](https://github.com/codeship/codeship-go) ⭐ 18 📅 2020-11-03 - Go client library for interacting with Codeship's API v2.
- [coinpaprika-go](https://github.com/coinpaprika/coinpaprika-api-go-client) ⭐ 23 📅 2022-12-08 - Go client library for interacting with Coinpaprika's API.
- [device-check-go](https://github.com/rinchsan/device-check-go) ⭐ 25 📅 2023-09-24 - Go client library for interacting with [iOS DeviceCheck API](https://developer.apple.com/documentation/devicecheck) v1.
- [discordgo](https://github.com/bwmarrin/discordgo) ⭐ 4,657 📅 2024-03-15 - Go bindings for the Discord Chat API.
- [dusupay-sdk-go](https://github.com/Kachit/dusupay-sdk-go) ⭐ 3 📅 2022-12-06 - Unofficial Dusupay payment gateway API Client for Go
- [ethrpc](https://github.com/onrik/ethrpc) ⭐ 262 📅 2023-06-27 - Go bindings for Ethereum JSON RPC API.
- [facebook](https://github.com/huandu/facebook) ⭐ 1,259 📅 2024-01-16 - Go Library that supports the Facebook Graph API.
- [fasapay-sdk-go](https://github.com/Kachit/fasapay-sdk-go) ⭐ 2 📅 2022-06-16 - Unofficial Fasapay payment gateway XML API Client for Golang.
- [fcm](https://github.com/maddevsio/fcm) ⭐ 51 📅 2020-03-06 - Go library for Firebase Cloud Messaging.
- [gads](https://github.com/emiddleton/gads) ⭐ 50 📅 2015-09-08 - Google Adwords Unofficial API.
- [gami](https://github.com/bit4bit/gami) ⭐ 33 📅 2017-06-10 - Go library for Asterisk Manager Interface.
- [gcm](https://github.com/Aorioli/gcm) ⭐ 31 📅 2015-12-04 - Go library for Google Cloud Messaging.
- [geo-golang](https://github.com/codingsince1985/geo-golang) ⭐ 495 📅 2022-12-17 - Go Library to access [Google Maps](https://developers.google.com/maps/documentation/geocoding/intro), [MapQuest](https://developer.mapquest.com/documentation/geocoding-api/), [Nominatim](https://developer.mapquest.com/documentation/open/nominatim-search), [OpenCage](https://opencagedata.com/api), [Bing](https://msdn.microsoft.com/en-us/library/ff701715.aspx), [Mapbox](https://www.mapbox.com/developers/api/geocoding/), and [OpenStreetMap](https://wiki.openstreetmap.org/wiki/Nominatim) geocoding / reverse geocoding APIs.
- [github](https://github.com/google/go-github) ⭐ 10,020 📅 2024-03-20 - Go library for accessing the GitHub REST API v3.
- [githubql](https://github.com/shurcooL/githubql) ⭐ 1,078 📅 2024-01-20 - Go library for accessing the GitHub GraphQL API v4.
- [go-atlassian](https://github.com/ctreminiom/go-atlassian) ⭐ 105 📅 2024-03-08 - Go library for accessing the [Atlassian Cloud](https://www.atlassian.com/enterprise/cloud) services (Jira, Jira Service Management, Jira Agile, Confluence, Admin Cloud)
- [go-aws-news](https://github.com/circa10a/go-aws-news) ⭐ 18 📅 2023-02-28 - Go application and library to fetch what's new from AWS.
- [go-chronos](https://github.com/axelspringer/go-chronos) ⭐ 8 📅 2018-01-23 - Go library for interacting with the [Chronos](https://mesos.github.io/chronos/) Job Scheduler
- [go-hacknews](https://github.com/PaulRosset/go-hacknews) ⭐ 17 📅 2017-08-15 - Tiny Go client for HackerNews API.
- [go-here](https://github.com/abdullahselek/go-here) ⭐ 13 📅 2020-05-23 - Go client library around the HERE location based APIs.
- [go-hibp](https://github.com/wneessen/go-hibp) ⭐ 8 📅 2024-03-14 - Simple Go binding to the "Have I Been Pwned" APIs.
- [go-imgur](https://github.com/koffeinsource/go-imgur) ⭐ 25 📅 2023-02-27 - Go client library for [imgur](https://imgur.com)
- [go-jira](https://github.com/andygrunwald/go-jira) ⭐ 1,412 📅 2024-01-16 - Go client library for [Atlassian JIRA](https://www.atlassian.com/software/jira)
- [go-lark](https://github.com/go-lark/lark) ⭐ 179 📅 2024-01-10 - An easy-to-use unofficial SDK for [Feishu](https://open.feishu.cn/) and [Lark](https://open.larksuite.com/) Open Platform.
- [go-marathon](https://github.com/gambol99/go-marathon) ⭐ 199 📅 2020-01-16 - Go library for interacting with Mesosphere's Marathon PAAS.
- [go-myanimelist](https://github.com/nstratos/go-myanimelist) ⭐ 38 📅 2023-03-29 - Go client library for accessing the [MyAnimeList API](https://myanimelist.net/apiconfig/references/api/v2).
- [go-openai](https://github.com/sashabaranov/go-openai) ⭐ 7,958 📅 2024-03-15 - OpenAI ChatGPT, DALL·E, Whisper API library for Go.
- [go-openproject](https://github.com/manuelbcd/go-openproject) ⭐ 15 📅 2022-11-22 - Go client library for interacting with [OpenProject](https://docs.openproject.org/api/) API.
- [go-postman-collection](https://github.com/rbretecher/go-postman-collection) ⭐ 72 📅 2022-09-20 - Go module to work with [Postman Collections](https://learning.getpostman.com/docs/postman/collections/creating-collections/) (compatible with Insomnia).
- [go-redoc](https://github.com/mvrilo/go-redoc) ⭐ 60 📅 2024-01-20 - Embedded OpenAPI/Swagger documentation ui for Go using [ReDoc](https://redocly.com/).
- [go-restcountries](https://github.com/chriscross0/go-restcountries) ⭐ 4 📅 2021-10-27 - Go library for the [REST Countries API](https://countrylayer.com/).
- [go-sophos](https://github.com/esurdam/go-sophos) ⭐ 12 📅 2022-05-06 - Go client library for the [Sophos UTM REST API](https://www.sophos.com/en-us/medialibrary/PDFs/documentation/UTMonAWS/Sophos-UTM-RESTful-API.pdf?la=en) with zero dependencies.
- [go-sptrans](https://github.com/sergioaugrod/go-sptrans) ⭐ 9 📅 2020-09-16 - Go client library for the SPTrans Olho Vivo API.
- [go-swagger-ui](https://github.com/esurdam/go-swagger-ui) ⭐ 10 📅 2022-10-23 - Go library containing precompiled [Swagger UI](https://swagger.io/tools/swagger-ui/) for serving swagger json.
- [go-telegraph](https://gitlab.com/toby3d/telegraph) - Telegraph publishing platform API client.
- [go-trending](https://github.com/andygrunwald/go-trending) ⭐ 139 📅 2024-03-01 - Go library for accessing [trending repositories](https://github.com/trending) and [developers](https://github.com/trending/developers) ❌ at Github.
- [go-twitter](https://github.com/dghubble/go-twitter) ⭐ 1,586 📅 2022-11-04 - Go client library for the Twitter v1.1 APIs.
- [go-unsplash](https://github.com/hbagdi/go-unsplash) ⭐ 73 📅 2023-04-14 - Go client library for the [Unsplash.com](https://unsplash.com) API.
- [go-xkcd](https://github.com/nishanths/go-xkcd) ⭐ 52 📅 2022-10-23 - Go client for the xkcd API.
- [go-yapla](https://git.iglou.eu/Production/go-yapla) - Go client library for the Yapla v2.0 API.
- [goagi](https://github.com/staskobzar/goagi) ⭐ 9 📅 2022-11-08 - Go library to build Asterisk PBX agi/fastagi applications.
- [goami2](https://github.com/staskobzar/goami2) ⭐ 14 📅 2024-02-01 - AMI v2 library for Asterisk PBX.
- [GoFreeDB](https://github.com/FreeLeh/GoFreeDB) ⭐ 32 📅 2022-10-01 - Golang library providing common and simple database abstractions on top of Google Sheets.
- [gogtrends](https://github.com/groovili/gogtrends) ⭐ 78 📅 2022-06-14 - Google Trends Unofficial API.
- [golang-tmdb](https://github.com/cyruzin/golang-tmdb) ⭐ 96 📅 2024-03-22 - Golang wrapper for The Movie Database API v3.
- [golyrics](https://github.com/mamal72/golyrics) ⭐ 41 📅 2018-06-30 - Golyrics is a Go library to fetch music lyrics data from the Wikia website.
- [gomalshare](https://github.com/MonaxGT/gomalshare) ⭐ 13 📅 2019-04-29 - Go library MalShare API [malshare.com](https://www.malshare.com/)
- [GoMusicBrainz](https://github.com/michiwend/gomusicbrainz) ⭐ 54 📅 2018-10-08 - Go MusicBrainz WS2 client library.
- [google](https://github.com/google/google-api-go-client) ⭐ 3,747 📅 2024-03-22 - Auto-generated Google APIs for Go.
- [google-analytics](https://github.com/chonthu/go-google-analytics) ⭐ 15 📅 2015-05-30 - Simple wrapper for easy google analytics reporting.
- [google-cloud](https://github.com/GoogleCloudPlatform/gcloud-golang) ⭐ 3,574 📅 2024-03-21 - Google Cloud APIs Go Client Library.
- [google-email-audit-api](https://github.com/ngs/go-google-email-audit-api) ⭐ 8 📅 2016-10-26 - Go client library for [Google G Suite Email Audit API](https://developers.google.com/admin-sdk/email-audit/).
- [google-play-scraper](https://github.com/n0madic/google-play-scraper) ⭐ 80 📅 2023-10-14 - Get data from Google Play Store.
- [gopaapi5](https://github.com/utekaravinash/gopaapi5) ⭐ 15 📅 2020-04-03 - Go Client Library for [Amazon Product Advertising API 5.0](https://webservices.amazon.com/paapi5/documentation/).
- [gopensky](https://github.com/navidys/gopensky) ⭐ 2 📅 2024-03-20 - Go client implementation for [OpenSKY Network](https://opensky-network.org/) live's API (airspace ADS-B and Mode S data).
- [gosip](https://github.com/koltyakov/gosip) ⭐ 131 📅 2024-02-27 - Client library for SharePoint.
- [gostorm](https://github.com/jsgilmore/gostorm) ⭐ 129 📅 2017-10-09 - GoStorm is a Go library that implements the communications protocol required to write Storm spouts and Bolts in Go that communicate with the Storm shells.
- [hipchat](https://github.com/andybons/hipchat) ⭐ 104 📅 2016-03-24 - This project implements a golang client library for the Hipchat API.
- [hipchat (xmpp)](https://github.com/daneharrigan/hipchat) ⭐ 111 📅 2017-05-12 - A golang package to communicate with HipChat over XMPP.
- [igdb](https://github.com/Henry-Sarabia/igdb) ⭐ 79 📅 2020-12-15 - Go client for the [Internet Game Database API](https://api.igdb.com/).
- [ip2location-io-go](https://github.com/ip2location/ip2location-io-go) ⭐ 10 📅 2024-03-12 - Go wrapper for the IP2Location.io API [IP2Location.io](https://www.ip2location.io/).
- [jokeapi-go](https://github.com/icelain/jokeapi) ⭐ 22 📅 2023-12-30 - Go client for [JokeAPI](https://sv443.net/jokeapi/v2/).
- [lark](https://github.com/chyroc/lark) ⭐ 376 📅 2024-03-22 - [Feishu](https://open.feishu.cn/)/[Lark](https://open.larksuite.com/) Open API Go SDK, Support ALL Open API and Event Callback.
- [lastpass-go](https://github.com/ansd/lastpass-go) ⭐ 33 📅 2022-09-10 - Go client library for the [LastPass](https://www.lastpass.com/) API.
- [libgoffi](https://github.com/clevabit/libgoffi) ⭐ 9 📅 2020-08-23 - Library adapter toolbox for native [libffi](https://sourceware.org/libffi/) integration
- [Medium](https://github.com/Medium/medium-sdk-go) ⭐ 139 📅 2017-12-30 - Golang SDK for Medium's OAuth2 API.
- [megos](https://github.com/andygrunwald/megos) ⭐ 54 📅 2021-06-22 - Client library for accessing an [Apache Mesos](https://mesos.apache.org/) cluster.
- [minio-go](https://github.com/minio/minio-go) ⭐ 2,231 📅 2024-03-11 - Minio Go Library for Amazon S3 compatible cloud storage.
- [mixpanel](https://github.com/dukex/mixpanel) ⭐ 60 📅 2022-08-24 - Mixpanel is a library for tracking events and sending Mixpanel profile updates to Mixpanel from your go applications.
- [newsapi-go](https://github.com/jellydator/newsapi-go) ⭐ 6 📅 2024-03-01 - Go client for [NewsAPI](https://newsapi.org/).
- [openaigo](https://github.com/otiai10/openaigo) ⭐ 282 📅 2023-09-12 - OpenAI GPT3/GPT3.5 ChatGPT API client library for Go.
- [patreon-go](https://github.com/mxpv/patreon-go) ⭐ 38 📅 2019-09-17 - Go library for Patreon API.
- [paypal](https://github.com/logpacker/PayPal-Go-SDK) ⭐ 634 📅 2024-02-01 - Wrapper for PayPal payment API.
- [playlyfe](https://github.com/playlyfe/playlyfe-go-sdk) ⭐ 2 📅 2016-03-06 - The Playlyfe Rest API Go SDK.
- [pushover](https://github.com/gregdel/pushover) ⭐ 138 📅 2023-08-30 - Go wrapper for the Pushover API.
- [rawg-sdk-go](https://github.com/dimuska139/rawg-sdk-go) ⭐ 9 📅 2022-05-28 - Go library for the [RAWG Video Games Database](https://rawg.io/) API
- [rrdaclient](https://github.com/Omie/rrdaclient) ⭐ 10 📅 2014-09-19 - Go Library to access statdns.com API, which is in turn RRDA API. DNS Queries over HTTP.
- [shopify](https://github.com/rapito/go-shopify) ⭐ 25 📅 2020-12-03 - Go Library to make CRUD request to the Shopify API.
- [simples3](https://github.com/rhnvrm/simples3) ⭐ 131 📅 2022-07-11 - Simple no frills AWS S3 Library using REST with V4 Signing written in Go.
- [slack](https://github.com/slack-go/slack) ⭐ 4,528 📅 2024-03-20 - Slack API in Go.
- [smite](https://github.com/sergiotapia/smitego) ⭐ 11 📅 2014-07-18 - Go package to wraps access to the Smite game API.
- [spotify](https://github.com/rapito/go-spotify) ⭐ 48 📅 2020-12-03 - Go Library to access Spotify WEB API.
- [steam](https://github.com/sostronk/go-steam) ⭐ 32 📅 2018-03-13 - Go Library to interact with Steam game servers.
- [stripe](https://github.com/stripe/stripe-go) ⭐ 1,976 📅 2024-03-21 - Go client for the Stripe API.
- [swag](https://github.com/zc2638/swag) ⭐ 44 📅 2024-03-14 - No comments, simple go wrapper to create swagger 2.0 compatible APIs. Support most routing frameworks, such as built-in, gin, chi, mux, echo, httprouter, fasthttp and more.
- [textbelt](https://github.com/dietsche/textbelt) ⭐ 19 📅 2015-09-04 - Go client for the textbelt.com txt messaging API.
- [translate](https://github.com/poorny/translate) ⭐ 33 📅 2016-02-28 - Go online translation package.
- [Trello](https://github.com/adlio/trello) ⭐ 215 📅 2024-03-17 - Go wrapper for the Trello API.
- [TripAdvisor](https://github.com/mrbenosborne/tripadvisor-golang) ⭐ 2 📅 2019-08-12 - Go wrapper for the TripAdvisor API.
- [tumblr](https://github.com/mattcunningham/gumblr) ⭐ 9 📅 2016-10-30 - Go wrapper for the Tumblr v2 API.
- [twitter-scraper](https://github.com/n0madic/twitter-scraper) ⭐ 843 📅 2023-11-04 - Scrape the Twitter Frontend API without authentication and limits.
- [uptimerobot](https://github.com/bitfield/uptimerobot) ⭐ 57 📅 2023-04-22 - Go wrapper and command-line client for the Uptime Robot v2 API.
- [vl-go](https://github.com/verifid/vl-go) ⭐ 2 📅 2021-05-26 - Go client library around the VerifID identity verification layer API.
- [webhooks](https://github.com/go-playground/webhooks) ⭐ 917 📅 2023-11-29 - Webhook receiver for GitHub and Bitbucket.
- [wit-go](https://github.com/wit-ai/wit-go) ⭐ 150 📅 2022-10-10 - Go client for wit.ai HTTP API.
- [ynab](https://github.com/brunomvsouza/ynab.go) - Go wrapper for the YNAB API.
- [zooz](https://github.com/gojuno/go-zooz) ⭐ 7 📅 2018-06-05 - Go client for the Zooz API.

**[⬆ back to top](#contents)**

## Utilities

_General utilities and tools to make your life easier._

- [air](https://github.com/cosmtrek/air) ⭐ 14,770 📅 2024-02-25 - Air - Live reload for Go apps.
- [apm](https://github.com/topfreegames/apm) ⭐ 166 📅 2016-11-24 - Process manager for Golang applications with an HTTP API.
- [backscanner](https://github.com/icza/backscanner) ⭐ 58 📅 2024-02-21 - A scanner similar to bufio.Scanner, but it reads and returns lines in reverse order, starting at a given position and going backward.
- [beyond](https://github.com/wesovilabs/beyond) ⭐ 56 📅 2019-12-04 - The Go tool that will drive you to the AOP world!
- [blank](https://github.com/Henry-Sarabia/blank) ⭐ 12 📅 2019-07-31 - Verify or remove blanks and whitespace from strings.
- [bleep](https://github.com/sinhashubham95/bleep) ⭐ 11 📅 2021-01-06 - Perform any number of actions on any set of OS signals in Go.
- [boilr](https://github.com/tmrts/boilr) ⭐ 1,686 📅 2017-07-19 - Blazingly fast CLI tool for creating projects from boilerplate templates.
- [changie](https://github.com/miniscruff/changie) ⭐ 574 📅 2024-03-18 - Automated changelog tool for preparing releases with lots of customization options.
- [chyle](https://github.com/antham/chyle) ⭐ 154 📅 2024-03-04 - Changelog generator using a git repository with multiple configuration possibilities.
- [circuit](https://github.com/cep21/circuit) ⭐ 732 📅 2024-01-26 - An efficient and feature complete Hystrix like Go implementation of the circuit breaker pattern.
- [circuitbreaker](https://github.com/rubyist/circuitbreaker) ⭐ 1,108 📅 2019-10-21 - Circuit Breakers in Go.
- [clipboard](https://github.com/golang-design/clipboard) ⭐ 511 📅 2023-04-16 - 📋 cross-platform clipboard package in Go.
- [clockwork](https://github.com/jonboulle/clockwork) ⭐ 592 📅 2023-12-13 - A simple fake clock for golang.
- [cmd](https://github.com/SimonBaeumer/cmd) ⭐ 146 📅 2024-01-31 - Library for executing shell commands on osx, windows and linux.
- [command](https://github.com/txgruppi/command) ⭐ 14 📅 2016-04-20 - Command pattern for Go with thread safe serial and parallel dispatcher.
- [config-file-validator](https://github.com/Boeing/config-file-validator) ⭐ 229 📅 2024-03-20 - Cross Platform tool to validate configuration files.
- [contextplus](https://github.com/contextplus/contextplus) ⭐ 17 📅 2022-09-26 - Package contextplus provide more easy to use functions for contexts.
- [copy](https://github.com/gotidy/copy) ⭐ 39 📅 2020-12-28 - Package for fast copying structs of different types.
- [copy-pasta](https://github.com/jutkko/copy-pasta) ⭐ 50 📅 2020-06-20 - Universal multi-workstation clipboard that uses S3 like backend for the storage.
- [countries](https://github.com/biter777/countries) ⭐ 347 📅 2024-02-29 - Full implementation of ISO-3166-1, ISO-4217, ITU-T E.164, Unicode CLDR and IANA ccTLD standards.
- [countries](https://github.com/pioz/countries) ⭐ 85 📅 2023-10-06 - All you need when you are working with countries in Go.
- [create-go-app](https://github.com/create-go-app/cli) ⭐ 2,308 📅 2024-01-08 - A powerful CLI for create a new production-ready project with backend (Golang), frontend (JavaScript, TypeScript) & deploy automation (Ansible, Docker) by running one command.
- [cryptgo](https://github.com/Gituser143/cryptgo) ⭐ 144 📅 2021-10-17 - Crytpgo is a TUI based application written purely in Go to monitor and observe cryptocurrency prices in real time!
- [ctop](https://github.com/bcicen/ctop) ⭐ 15,086 📅 2022-08-01 - [Top-like](https://ctop.sh) interface (e.g. htop) for container metrics.
- [ctxutil](https://github.com/posener/ctxutil) ⭐ 25 📅 2019-08-02 - A collection of utility functions for contexts.
- [cvt](https://github.com/shockerli/cvt) ⭐ 46 📅 2023-12-20 - Easy and safe convert any value to another type.
- [dbt](https://github.com/nikogura/dbt) ⭐ 58 📅 2023-03-13 - A framework for running self-updating signed binaries from a central, trusted repository.
- [Death](https://github.com/vrecan/death) ⭐ 192 📅 2022-05-28 - Managing go application shutdown with signals.
- [Deepcopier](https://github.com/ulule/deepcopier) ⭐ 437 📅 2020-04-30 - Simple struct copying for Go.
- [delve](https://github.com/derekparker/delve) ⭐ 619 📅 2020-05-18 - Go debugger.
- [dive](https://github.com/wagoodman/dive) ⭐ 43,083 📅 2024-02-02 - A tool for exploring each layer in a Docker image.
- [dlog](https://github.com/kirillDanshin/dlog) ⭐ 17 📅 2017-07-28 - Compile-time controlled logger to make your release smaller without removing debug calls.
- [EaseProbe](https://github.com/megaease/easeprobe) ⭐ 2,000 📅 2024-03-04 - A simple, standalone, and lightWeight tool that can do health/status checking daemon, support HTTP/TCP/SSH/Shell/Client/... probes, and Slack/Discord/Telegram/SMS... notification.
- [equalizer](https://github.com/reugn/equalizer) ⭐ 74 📅 2024-03-14 - Quota manager and rate limiter collection for Go.
- [ergo](https://github.com/cristianoliveira/ergo) ⭐ 604 📅 2023-09-29 - The management of multiple local services running over different ports made easy.
- [evaluator](https://github.com/nullne/evaluator) ⭐ 38 📅 2021-07-25 - Evaluate an expression dynamically based on s-expression. It's simple and easy to extend.
- [filetype](https://github.com/h2non/filetype) ⭐ 1,986 📅 2023-12-28 - Small package to infer the file type checking the magic numbers signature.
- [filler](https://github.com/yaronsumel/filler) ⭐ 17 📅 2017-04-10 - small utility to fill structs using "fill" tag.
- [filter](https://github.com/gookit/filter) ⭐ 147 📅 2024-03-11 - provide filtering, sanitizing, and conversion of Go data.
- [fzf](https://github.com/junegunn/fzf) ⭐ 58,748 📅 2024-03-21 - Command-line fuzzy finder written in Go.
- [generate](https://github.com/go-playground/generate) ⭐ 30 📅 2017-01-10 - runs go generate recursively on a specified path or environment variable and can filter by regex.
- [ghokin](https://github.com/antham/ghokin) ⭐ 42 📅 2024-03-05 - Parallelized formatter with no external dependencies for gherkin (cucumber, behat...).
- [git-time-metric](https://github.com/git-time-metric/gtm) ⭐ 961 📅 2019-08-02 - Simple, seamless, lightweight time tracking for Git.
- [gitbatch](https://github.com/isacikgoz/gitbatch) ⭐ 1,523 📅 2023-01-17 - manage your git repositories in one place.
- [go-actuator](https://github.com/sinhashubham95/go-actuator) ⭐ 15 📅 2021-08-26 - Production ready features for Go based web frameworks.
- [go-astitodo](https://github.com/asticode/go-astitodo) ⭐ 61 📅 2023-07-26 - Parse TODOs in your GO code.
- [go-bind-plugin](https://github.com/wendigo/go-bind-plugin) ⭐ 184 📅 2019-08-29 - go:generate tool for wrapping symbols exported by golang plugins (1.8 only).
- [go-bsdiff](https://github.com/gabstv/go-bsdiff) ⭐ 155 📅 2019-03-21 - Pure Go bsdiff and bspatch libraries and CLI tools.
- [go-clip](https://github.com/prashantgupta24/go-clip) ⭐ 12 📅 2021-02-05 - A minimalistic clipboard manager for Mac.
- [go-convert](https://github.com/Eun/go-convert) ⭐ 22 📅 2024-02-13 - Package go-convert enables you to convert a value into another type.
- [go-countries](https://github.com/mikekonan/go-countries) ⭐ 13 📅 2020-12-17 - Lightweight lookup over ISO-3166 codes.
- [go-dry](https://github.com/ungerik/go-dry) ⭐ 490 📅 2023-10-11 - DRY (don't repeat yourself) package for Go.
- [go-funk](https://github.com/thoas/go-funk) ⭐ 4,583 📅 2023-06-20 - Modern Go utility library which provides helpers (map, find, contains, filter, chunk, reverse, ...).
- [go-health](https://github.com/Talento90/go-health) ⭐ 94 📅 2022-01-19 - Health package simplifies the way you add health check to your services.
- [go-httpheader](https://github.com/mozillazg/go-httpheader) ⭐ 46 📅 2023-06-29 - Go library for encoding structs into Header fields.
- [go-lambda-cleanup](https://github.com/karl-cardenas-coding/go-lambda-cleanup) ⭐ 87 📅 2024-03-03 - A CLI for removing unused or previous versions of AWS Lambdas. 
- [go-lock](https://github.com/viney-shih/go-lock) ⭐ 107 📅 2022-06-18 - go-lock is a lock library implementing read-write mutex and read-write trylock without starvation.
- [go-pattern-match](https://github.com/PhakornKiong/go-pattern-match) ⭐ 86 📅 2023-08-26 - A Pattern matching library inspired by ts-pattern.
- [go-pkg](https://github.com/chenquan/go-pkg) ⭐ 6 📅 2022-06-29 - A go toolkit.
- [go-problemdetails](https://github.com/mvmaasakkers/go-problemdetails) ⭐ 17 📅 2020-02-17 - Go package for working with Problem Details.
- [go-qr](https://github.com/piglig/go-qr) ⭐ 14 📅 2024-01-09 - A native, high-quality and minimalistic QR code generator.
- [go-rate](https://github.com/beefsack/go-rate) ⭐ 394 📅 2022-02-14 - Timed rate limiter for Go.
- [go-sitemap-generator](https://github.com/ikeikeikeike/go-sitemap-generator) ⭐ 214 📅 2019-03-26 - XML Sitemap generator written in Go.
- [go-trigger](https://github.com/sadlil/go-trigger) ⭐ 242 📅 2017-03-28 - Go-lang global event triggerer, Register Events with an id and trigger the event from anywhere from your project.
- [go-type](https://github.com/mikekonan/go-types) ⭐ 18 📅 2024-03-07 - Library providing Go types for store/validation and transfer of ISO-4217, ISO-3166, and other types.
- [goback](https://github.com/carlescere/goback) ⭐ 49 📅 2015-03-14 - Go simple exponential backoff package.
- [goctx](https://github.com/zerosnake0/goctx) ⭐ 7 📅 2020-11-24 - Get your context value with high performance.
- [godaemon](https://github.com/VividCortex/godaemon) ⭐ 494 📅 2021-04-27 - Utility to write daemons.
- [godropbox](https://github.com/dropbox/godropbox) ⭐ 4,170 📅 2023-06-23 - Common libraries for writing Go services/applications from Dropbox.
- [gofn](https://github.com/tiendc/gofn) ⭐ 29 📅 2023-11-25 - High performance utility functions written using Generics for Go 1.18+.
- [gohper](https://github.com/cosiner/gohper) ⭐ 256 📅 2017-08-12 - Various tools/modules help for development.
- [golarm](https://github.com/msempere/golarm) ⭐ 53 📅 2015-08-24 - Fire alarms with system events.
- [golog](https://github.com/mlimaloureiro/golog) ⭐ 60 📅 2016-07-03 - Easy and lightweight CLI tool to time track your tasks.
- [gopencils](https://github.com/bndr/gopencils) ⭐ 451 📅 2016-11-13 - Small and simple package to easily consume REST APIs.
- [goplaceholder](https://github.com/michiwend/goplaceholder) ⭐ 28 📅 2016-01-17 - a small golang lib to generate placeholder images.
- [goreadability](https://github.com/philipjkim/goreadability) ⭐ 69 📅 2019-04-22 - Webpage summary extractor using Facebook Open Graph and arc90's readability.
- [goreleaser](https://github.com/goreleaser/goreleaser) ⭐ 12,817 📅 2024-03-20 - Deliver Go binaries as fast and easily as possible.
- [goreporter](https://github.com/wgliang/goreporter) ⭐ 3,105 📅 2018-09-02 - Golang tool that does static analysis, unit testing, code review and generate code quality report.
- [goseaweedfs](https://github.com/linxGnu/goseaweedfs) ⭐ 113 📅 2022-11-11 - SeaweedFS client library with almost full features.
- [gostrutils](https://github.com/ik5/gostrutils) ⭐ 44 📅 2023-03-25 - Collections of string manipulation and conversion functions.
- [gotenv](https://github.com/subosito/gotenv) ⭐ 283 📅 2023-08-15 - Load environment variables from `.env` or any `io.Reader` in Go.
- [goval](https://github.com/maja42/goval) ⭐ 142 📅 2022-11-02 - Evaluate arbitrary expressions in Go.
- [gpath](https://github.com/tenntenn/gpath) ⭐ 40 📅 2017-06-04 - Library to simplify access struct fields with Go's expression in reflection.
- [graterm](https://github.com/skovtunenko/graterm) ⭐ 27 📅 2022-11-05 - Provides primitives to perform ordered (sequential/concurrent) GRAceful TERMination (aka shutdown) in Go application.
- [grofer](https://github.com/pesos/grofer) ⭐ 328 📅 2022-01-11 - A system and resource monitoring tool written in Golang!
- [gubrak](https://github.com/novalagung/gubrak) ⭐ 474 📅 2023-03-08 - Golang utility library with syntactic sugar. It's like lodash, but for golang.
- [handy](https://github.com/miguelpragier/handy) ⭐ 77 📅 2020-09-30 - Many utilities and helpers like string handlers/formatters and validators.
- [hostctl](https://github.com/guumaster/hostctl) ⭐ 994 📅 2023-08-20 - A CLI tool to manage /etc/hosts with easy commands.
- [htcat](https://github.com/htcat/htcat) ⭐ 553 📅 2015-06-08 - Parallel and Pipelined HTTP GET Utility.
- [hub](https://github.com/github/hub) ⭐ 22,667 📅 2023-10-04 - wrap git commands with additional functionality to interact with github from the terminal.
- [hystrix-go](https://github.com/afex/hystrix-go) ⭐ 4,133 📅 2018-05-02 - Implements Hystrix patterns of programmer-defined fallbacks aka circuit breaker.
- [immortal](https://github.com/immortal/immortal) ⭐ 789 📅 2024-02-01 - \*nix cross-platform (OS agnostic) supervisor.
- [intrinsic](https://github.com/mengzhuo/intrinsic) ⭐ 46 📅 2017-06-22 - Use x86 SIMD without writing any assembly code.
- [jsend](https://github.com/clevergo/jsend) ⭐ 21 📅 2021-06-28 - JSend's implementation written in Go.
- [jump](https://github.com/gsamokovarov/jump) ⭐ 1,725 📅 2023-08-16 - Jump helps you navigate faster by learning your habits.
- [just](https://github.com/kazhuravlev/just) ⭐ 18 📅 2024-03-11 - Just a collection of useful functions for working with generic data structures.
- [koazee](https://github.com/wesovilabs/koazee) ⭐ 520 📅 2019-11-04 - Library inspired in Lazy evaluation and functional programming that takes the hassle out of working with arrays.
- [lancet](https://github.com/duke-git/lancet) ⭐ 3,617 📅 2024-03-06 - A comprehensive, efficient, and reusable util function library of go.
- [lets-go](https://github.com/aplescia-chwy/lets-go) ⭐ 6 📅 2021-04-24 - Go module that provides common utilities for Cloud Native REST API development. Also contains AWS Specific utilities.
- [limiters](https://github.com/mennanov/limiters) ⭐ 314 📅 2024-03-19 - Rate limiters for distributed applications in Golang with configurable back-ends and distributed locks.
- [lo](https://github.com/samber/lo) ⭐ 15,024 📅 2023-12-19 - A Lodash like Go library based on Go 1.18+ Generics (map, filter, contains, find...)
- [loncha](https://github.com/kazu/loncha) ⭐ 7 📅 2022-07-03 - A high-performance slice Utilities.
- [lrserver](https://github.com/jaschaephraim/lrserver) ⭐ 124 📅 2024-03-06 - LiveReload server for Go.
- [mani](https://github.com/alajmo/mani) ⭐ 417 📅 2023-11-02 - CLI tool to help you manage multiple repositories.
- [mc](https://github.com/minio/mc) ⭐ 2,673 📅 2024-03-20 - Minio Client provides minimal tools to work with Amazon S3 compatible cloud storage and filesystems.
- [mergo](https://github.com/imdario/mergo) ⭐ 2,681 📅 2023-09-11 - Helper to merge structs and maps in Golang. Useful for configuration default values, avoiding messy if-statements.
- [mimemagic](https://github.com/zRedShift/mimemagic) ⭐ 97 📅 2023-02-27 - Pure Go ultra performant MIME sniffing library/utility.
- [mimesniffer](https://github.com/aofei/mimesniffer) ⭐ 32 📅 2022-08-04 - A MIME type sniffer for Go.
- [mimetype](https://github.com/gabriel-vasile/mimetype) ⭐ 1,374 📅 2024-02-26 - Package for MIME type detection based on magic numbers.
- [minify](https://github.com/tdewolff/minify) ⭐ 3,559 📅 2024-03-14 - Fast minifiers for HTML, CSS, JS, XML, JSON and SVG file formats.
- [minquery](https://github.com/icza/minquery) ⭐ 62 📅 2023-03-31 - MongoDB / mgo.v2 query that supports efficient pagination (cursors to continue listing documents where we left off).
- [moldova](https://github.com/StabbyCutyou/moldova) ⭐ 168 📅 2017-09-04 - Utility for generating random data based on an input template.
- [mole](https://github.com/davrodpin/mole) ⭐ 1,680 📅 2021-10-06 - cli app to easily create ssh tunnels.
- [mongo-go-pagination](https://github.com/gobeam/mongo-go-pagination) ⭐ 128 📅 2022-08-09 - Mongodb Pagination for official mongodb/mongo-go-driver package which supports both normal queries and Aggregation pipelines.
- [mssqlx](https://github.com/linxGnu/mssqlx) ⭐ 102 📅 2024-03-12 - Database client library, proxy for any master slave, master master structures. Lightweight and auto balancing in mind.
- [multitick](https://github.com/VividCortex/multitick) ⭐ 70 📅 2021-04-26 - Multiplexor for aligned tickers.
- [myhttp](https://github.com/inancgumus/myhttp) ⭐ 34 📅 2018-05-06 - Simple API to make HTTP GET requests with timeout support.
- [netbug](https://github.com/e-dard/netbug) ⭐ 73 📅 2015-10-29 - Easy remote profiling of your services.
- [nfdump](https://github.com/chrispassas/nfdump) ⭐ 8 📅 2023-01-26 - Read nfdump netflow files.
- [nostromo](https://github.com/pokanop/nostromo) ⭐ 140 📅 2023-02-25 - CLI for building powerful aliases.
- [objwalker](https://github.com/rekby/objwalker) ⭐ 2 📅 2022-03-04 - Walk by go objects with reflection.
- [okrun](https://github.com/xta/okrun) ⭐ 16 📅 2014-10-06 - go run error steamroller.
- [olaf](https://github.com/btnguyen2k/olaf) ⭐ 6 📅 2019-04-10 - Twitter Snowflake implemented in Go.
- [onecache](https://github.com/adelowo/onecache) ⭐ 134 📅 2020-05-25 - Caching library with support for multiple backend stores (Redis, Memcached, filesystem etc).
- [panicparse](https://github.com/maruel/panicparse) ⭐ 3,479 📅 2023-10-05 - Groups similar goroutines and colorizes stack dump.
- [pattern-match](https://github.com/alexpantyukhin/go-pattern-match) ⭐ 236 📅 2023-03-01 - Pattern matching library.
- [peco](https://github.com/peco/peco) ⭐ 7,551 📅 2023-09-16 - Simplistic interactive filtering tool.
- [pgo](https://github.com/arthurkushman/pgo) ⭐ 85 📅 2023-05-04 - Convenient functions for PHP community.
- [pm](https://github.com/VividCortex/pm) ⭐ 81 📅 2020-12-15 - Process (i.e. goroutine) manager with an HTTP API.
- [pointer](https://github.com/xorcare/pointer) ⭐ 41 📅 2023-07-10 - Package pointer contains helper routines for simplifying the creation of optional fields of basic type.
- [ptr](https://github.com/gotidy/ptr) ⭐ 23 📅 2021-12-18 - Package that provide functions for simplified creation of pointers from constants of basic types.
- [rclient](https://github.com/zpatrick/rclient) ⭐ 35 📅 2019-11-28 - Readable, flexible, simple-to-use client for REST APIs.
- [reflectutils](https://github.com/muir/reflectutils) ⭐ 7 📅 2024-03-14 - Helpers for working with reflection: struct tag parsing; recursive walking; fill value from string.
- [remote-touchpad](https://github.com/Unrud/remote-touchpad) ⭐ 473 📅 2024-02-06 - Control mouse and keyboard from a smartphone.
- [repeat](https://github.com/ssgreg/repeat) ⭐ 84 📅 2020-02-13 - Go implementation of different backoff strategies useful for retrying operations and heartbeating.
- [request](https://github.com/mozillazg/request) ⭐ 426 📅 2017-10-23 - Go HTTP Requests for Humans™.
- [rerun](https://github.com/ivpusic/rerun) ⭐ 166 📅 2017-03-31 - Recompiling and rerunning go apps when source changes.
- [rest-go](https://github.com/edermanoel94/rest-go) ⭐ 16 📅 2020-03-09 - A package that provide many helpful methods for working with rest api.
- [retry](https://github.com/kamilsk/retry) ⭐ 335 📅 2021-02-23 - The most advanced functional mechanism to perform actions repetitively until successful.
- [retry](https://github.com/percolate/retry) ⭐ 10 📅 2023-03-16 - A simple but highly configurable retry package for Go.
- [retry](https://github.com/thedevsaddam/retry) ⭐ 65 📅 2020-03-24 - Simple and easy retry mechanism package for Go.
- [retry](https://github.com/shafreeck/retry) ⭐ 12 📅 2020-02-11 - A pretty simple library to ensure your work to be done.
- [retry-go](https://github.com/avast/retry-go) ⭐ 2,175 📅 2023-11-14 - Simple library for retry mechanism.
- [retry-go](https://github.com/rafaeljesus/retry-go) ⭐ 47 📅 2017-12-14 - Retrying made simple and easy for golang.
- [robustly](https://github.com/VividCortex/robustly) ⭐ 157 📅 2021-04-26 - Runs functions resiliently, catching and restarting panics.
- [rospo](https://github.com/ferama/rospo) ⭐ 265 📅 2024-03-21 - Simple and reliable ssh tunnels with embedded ssh server in Golang.
- [scan](https://github.com/blockloop/scan) ⭐ 505 📅 2023-11-06 - Scan golang `sql.Rows` directly to structs, slices, or primitive types.
- [scan](https://github.com/wroge/scan) ⭐ 60 📅 2024-03-08 - Scan sql rows into any type powered by generics.
- [scany](https://github.com/georgysavva/scany) ⭐ 1,154 📅 2024-03-17 - Library for scanning data from a database into Go structs and more.
- [serve](https://github.com/syntaqx/serve) ⭐ 322 📅 2024-03-04 - A static http server anywhere you need.
- [set](https://github.com/nofeaturesonlybugs/set) ⭐ 46 📅 2022-06-12 - Performant and flexible struct mapping and loose type conversion.
- [shutdown](https://github.com/ztrue/shutdown) ⭐ 57 📅 2022-01-15 - App shutdown hooks for `os.Signal` handling.
- [silk](https://github.com/chrispassas/silk) ⭐ 13 📅 2022-03-09 - Read silk netflow files.
- [slice](https://github.com/psampaz/slice) ⭐ 51 📅 2020-04-09 - Type-safe functions for common Go slice operations.
- [sliceconv](https://github.com/Henry-Sarabia/sliceconv) ⭐ 8 📅 2020-02-03 - Slice conversion between primitive types.
- [slicer](https://github.com/leaanthony/slicer) ⭐ 46 📅 2021-08-08 - Makes working with slices easier.
- [sorty](https://github.com/jfcg/sorty) ⭐ 128 📅 2023-02-09 - Fast Concurrent / Parallel Sorting.
- [sqlx](https://github.com/jmoiron/sqlx) ⭐ 15,219 📅 2022-04-16 - provides a set of extensions on top of the excellent built-in database/sql package.
- [sshman](https://github.com/shoobyban/sshman) ⭐ 44 📅 2022-11-03 - SSH Manager for authorized_keys files on multiple remote servers.
- [statiks](https://github.com/janiltonmaciel/statiks) ⭐ 10 📅 2020-10-06 - Fast, zero-configuration, static HTTP filer server.
- [Storm](https://github.com/asdine/storm) ⭐ 2,030 📅 2020-09-09 - Simple and powerful toolkit for BoltDB.
- [structs](https://github.com/PumpkinSeed/structs) ⭐ 24 📅 2017-10-23 - Implement simple functions to manipulate structs.
- [throttle](https://github.com/yudppp/throttle) ⭐ 35 📅 2021-08-24 - Throttle is an object that will perform exactly one action per duration.
- [tik](https://github.com/andy2046/tik) ⭐ 5 📅 2020-10-17 - Simple and easy timing wheel package for Go.
- [tome](https://github.com/cyruzin/tome) ⭐ 35 📅 2022-04-20 - Tome was designed to paginate simple RESTful APIs.
- [toolbox](https://github.com/viant/toolbox) ⭐ 196 📅 2024-03-17 - Slice, map, multimap, struct, function, data conversion utilities. Service router, macro evaluator, tokenizer.
- [ugo](https://github.com/alxrm/ugo) ⭐ 27 📅 2016-06-30 - ugo is slice toolbox with concise syntax for Go.
- [UNIS](https://github.com/esemplastic/unis) ⭐ 70 📅 2017-05-09 - Common Architecture™ for String Utilities in Go.
- [upterm](https://github.com/owenthereal/upterm) ⭐ 751 📅 2024-03-17 - A tool for developers to share terminal/tmux sessions securely over the web. It’s perfect for remote pair programming, accessing computers behind NATs/firewalls, remote debugging, and more.
- [usql](https://github.com/knq/usql) ⭐ 8,534 📅 2024-03-12 - usql is a universal command-line interface for SQL databases.
- [util](https://github.com/shomali11/util) ⭐ 285 📅 2022-07-17 - Collection of useful utility functions. (strings, concurrency, manipulations, ...).
- [watchhttp](https://github.com/nikolaydubina/watchhttp) ⭐ 29 📅 2024-03-21 - Run command periodically and expose latest STDOUT or its rich delta as HTTP endpoint.
- [wifiqr](https://github.com/reugn/wifiqr) ⭐ 249 📅 2023-04-12 - Wi-Fi QR Code Generator.
- [wuzz](https://github.com/asciimoo/wuzz) ⭐ 10,460 📅 2021-01-22 - Interactive cli tool for HTTP inspection.
- [xferspdy](https://github.com/monmohan/xferspdy) ⭐ 100 📅 2020-12-03 - Xferspdy provides binary diff and patch library in golang.
- [yogo](https://github.com/antham/yogo) ⭐ 37 📅 2024-03-05 - Check yopmail mails from command line.

**[⬆ back to top](#contents)**

## UUID

_Libraries for working with UUIDs._

- [goid](https://github.com/jakehl/goid) ⭐ 40 📅 2019-02-18 - Generate and Parse RFC4122 compliant V4 UUIDs.
- [gouid](https://github.com/twharmon/gouid) ⭐ 22 📅 2024-01-11 - Generate cryptographically secure random string IDs with just one allocation.
- [nanoid](https://github.com/aidarkhanov/nanoid) ⭐ 60 📅 2021-09-15 - A tiny and efficient Go unique string ID generator.
- [sno](https://github.com/muyo/sno) ⭐ 89 📅 2021-11-12 - Compact, sortable and fast unique IDs with embedded metadata.
- [ulid](https://github.com/oklog/ulid) ⭐ 4,052 📅 2024-03-02 - Go implementation of ULID (Universally Unique Lexicographically Sortable Identifier).
- [uniq](https://gitlab.com/skilstak/code/go/uniq) - No hassle safe, fast unique identifiers with commands.
- [uuid](https://github.com/agext/uuid) ⭐ 18 📅 2020-03-12 - Generate, encode, and decode UUIDs v1 with fast or cryptographic-quality random node identifier.
- [uuid](https://github.com/gofrs/uuid) ⭐ 1,490 📅 2023-09-19 - Implementation of Universally Unique Identifier (UUID). Supports both creation and parsing of UUIDs. Actively maintained fork of satori uuid.
- [uuid](https://github.com/google/uuid) ⭐ 4,956 📅 2024-02-22 - Go package for UUIDs based on RFC 4122 and DCE 1.1: Authentication and Security Services.
- [wuid](https://github.com/edwingeng/wuid) ⭐ 514 📅 2024-01-26 - An extremely fast globally unique number generator.
- [xid](https://github.com/rs/xid) ⭐ 3,698 📅 2023-08-09 - Xid is a globally unique id generator library, ready to be safely used directly in your server code.

**[⬆ back to top](#contents)**

## Validation

_Libraries for validation._

- [checkdigit](https://github.com/osamingo/checkdigit) ⭐ 110 📅 2023-05-01 - Provide check digit algorithms (Luhn, Verhoeff, Damm) and calculators (ISBN, EAN, JAN, UPC, etc.).
- [gody](https://github.com/guiferpa/gody) ⭐ 66 📅 2021-02-02 - :balloon: A lightweight struct validator for Go.
- [govalid](https://github.com/twharmon/govalid) ⭐ 37 📅 2021-10-14 - Fast, tag-based validation for structs.
- [govalidator](https://github.com/asaskevich/govalidator) ⭐ 5,922 📅 2023-03-01 - Validators and sanitizers for strings, numerics, slices and structs.
- [govalidator](https://github.com/thedevsaddam/govalidator) ⭐ 1,273 📅 2020-04-12 - Validate Golang request data with simple rules. Highly inspired by Laravel's request validation.
- [jio](https://github.com/faceair/jio) ⭐ 99 📅 2020-05-08 - jio is a json schema validator similar to [joi](https://github.com/hapijs/joi) ⭐ 20,550 📅 2024-02-21.
- [ozzo-validation](https://github.com/go-ozzo/ozzo-validation) ⭐ 3,527 📅 2020-10-29 - Supports validation of various data types (structs, strings, maps, slices, etc.) with configurable and extensible validation rules specified in usual code constructs instead of struct tags.
- [validate](https://github.com/gookit/validate) ⭐ 1,000 📅 2024-03-12 - Go package for data validation and filtering. support validate Map, Struct, Request(Form, JSON, url.Values, Uploaded Files) data and more features.
- [validate](https://github.com/gobuffalo/validate) ⭐ 95 📅 2022-09-26 - This package provides a framework for writing validations for Go applications.
- [validator](https://github.com/go-playground/validator) ⭐ 15,330 📅 2024-03-02 - Go Struct and Field validation, including Cross Field, Cross Struct, Map, Slice and Array diving.
- [Validator](https://github.com/go-the-way/validator) ⭐ 7 📅 2022-05-11 - A lightweight model validator written in Go.Contains VFs:Min, Max, MinLength, MaxLength, Length, Enum, Regex.
- [valix](https://github.com/marrow16/valix) ⭐ 24 📅 2023-11-10 Go package for validating requests

**[⬆ back to top](#contents)**

## Version Control

_Libraries for version control._

- [cli](https://gitlab.com/gitlab-org/cli) - An open-source GitLab command line tool bringing GitLab's cool features to your command line.
- [froggit-go](https://github.com/jfrog/froggit-go) ⭐ 42 📅 2024-01-02 - Froggit-Go is a Go library, allowing to perform actions on VCS providers.
- [gh](https://github.com/rjeczalik/gh) ⭐ 82 📅 2017-07-25 - Scriptable server and net/http middleware for GitHub Webhooks.
- [git2go](https://github.com/libgit2/git2go) ⭐ 1,900 📅 2022-10-05 - Go bindings for libgit2.
- [githooks](https://github.com/gabyx/githooks) ⭐ 91 📅 2024-03-21 - Per-repo and shared Git hooks with version control and auto update.
- [go-git](https://github.com/go-git/go-git) ⭐ 5,415 📅 2024-03-19 - highly extensible Git implementation in pure Go.
- [go-vcs](https://github.com/sourcegraph/go-vcs) ⭐ 77 📅 2023-07-17 - manipulate and inspect VCS repositories in Go.
- [hercules](https://github.com/src-d/hercules) ⭐ 1,990 📅 2022-11-29 - gaining advanced insights from Git repository history.
- [hgo](https://github.com/beyang/hgo) ⭐ 17 📅 2015-08-25 - Hgo is a collection of Go packages providing read-access to local Mercurial repositories.

**[⬆ back to top](#contents)**

## Video

_Libraries for manipulating video._

- [gmf](https://github.com/3d0c/gmf) ⭐ 871 📅 2022-09-06 - Go bindings for FFmpeg av\* libraries.
- [go-astisub](https://github.com/asticode/go-astisub) ⭐ 545 📅 2024-03-22 - Manipulate subtitles in GO (.srt, .stl, .ttml, .webvtt, .ssa/.ass, teletext, .smi, etc.).
- [go-astits](https://github.com/asticode/go-astits) ⭐ 520 📅 2023-08-08 - Parse and demux MPEG Transport Streams (.ts) natively in GO.
- [go-m3u8](https://github.com/etherlabsio/go-m3u8) ⭐ 26 📅 2022-09-20 - Parser and generator library for Apple m3u8 playlists. Actively maintained version of quangngotan95/go-m3u8 with improvements and latest HLS playlist parsing compatibility.
- [go-mpd](https://github.com/unki2aut/go-mpd) ⭐ 23 📅 2023-11-11 - Parser and generator library for MPEG-DASH manifest files.
- [goav](https://github.com/giorgisio/goav) ⭐ 2,061 📅 2022-05-19 - Comprehensive Go bindings for FFmpeg.
- [gortsplib](https://github.com/aler9/gortsplib) ⭐ 583 📅 2024-03-19 - Pure Go RTSP server and client library.
- [gst](https://github.com/ziutek/gst) ⭐ 168 📅 2021-01-07 - Go bindings for GStreamer.
- [libgosubs](https://github.com/wargarblgarbl/libgosubs) ⭐ 24 📅 2018-12-04 - Subtitle format support for go. Supports .srt, .ttml, and .ass.
- [libvlc-go](https://github.com/adrg/libvlc-go) ⭐ 402 📅 2023-03-22 - Go bindings for libvlc 2.X/3.X/4.X (used by the VLC media player).
- [m3u8](https://github.com/grafov/m3u8) ⭐ 1,142 📅 2023-11-09 - Parser and generator library of M3U8 playlists for Apple HLS.
- [v4l](https://github.com/korandiz/v4l) ⭐ 77 📅 2021-12-29 - Video capture library for Linux, written in Go.

**[⬆ back to top](#contents)**

## Web Frameworks

_Full stack web frameworks._

- [aah](https://aahframework.org) - Scalable, performant, rapid development Web framework for Go.
- [Aero](https://github.com/aerogo/aero) ⭐ 563 📅 2024-02-21 - High-performance web framework for Go, reaches top scores in Lighthouse.
- [Air](https://github.com/aofei/air) ⭐ 436 📅 2021-04-18 - An ideally refined web framework for Go.
- [anoweb](https://github.com/go-the-way/anoweb) ⭐ 5 📅 2022-06-21 - The lightweight and powerful web framework using the new way for Go.Another go the way.
- [appy](https://github.com/appist/appy) ⭐ 131 📅 2021-07-02 - An opinionated productive web framework that helps scaling business easier.
- [Atreugo](https://github.com/savsgio/atreugo) ⭐ 1,180 📅 2024-03-04 - High performance and extensible micro web framework with zero memory allocations in hot paths.
- [Banjo](https://github.com/nsheremet/banjo) ⭐ 22 📅 2018-01-31 - Very simple and fast web framework for Go.
- [Beego](https://github.com/beego/beego) ⭐ 30,751 📅 2024-03-12 - beego is an open-source, high-performance web framework for the Go programming language.
- [Buffalo](https://gobuffalo.io) - Bringing the productivity of Rails to Go!
- [Confetti Framework](https://confetti-framework.github.io/docs/) - Confetti is a Go web application framework with an expressive, elegant syntax. Confetti combines the elegance of Laravel and the simplicity of Go.
- [Don](https://github.com/abemedia/go-don) ⭐ 40 📅 2024-03-18 - A highly performant and simple to use API framework.
- [Echo](https://github.com/labstack/echo) ⭐ 28,234 📅 2024-03-21 - High performance, minimalist Go web framework.
- [Fiber](https://github.com/gofiber/fiber) ⭐ 30,927 📅 2024-03-19 - An Express.js inspired web framework build on Fasthttp.
- [Fireball](https://github.com/zpatrick/fireball) ⭐ 59 📅 2018-10-03 - More "natural" feeling web framework.
- [Flamingo](https://github.com/i-love-flamingo/flamingo) ⭐ 424 📅 2024-03-14 - Framework for pluggable web projects. Including a concept for modules and offering features for DI, Configareas, i18n, template engines, graphql, observability, security, events, routing & reverse routing etc.
- [Flamingo Commerce](https://github.com/i-love-flamingo/flamingo-commerce) ⭐ 475 📅 2024-03-21 - Providing e-commerce features using clean architecture like DDD and ports and adapters, that you can use to build flexible e-commerce applications.
- [Gearbox](https://github.com/abahmed/gearbox) ⭐ 739 📅 2022-09-21 - A web framework written in Go with a focus on high performance and memory optimization.
- [Gin](https://github.com/gin-gonic/gin) ⭐ 74,870 📅 2024-03-22 - Gin is a web framework written in Go! It features a martini-like API with much better performance, up to 40 times faster. If you need performance and good productivity.
- [Ginrpc](https://github.com/xxjwxc/ginrpc) ⭐ 287 📅 2023-03-10 - Gin parameter automatic binding tool,gin rpc tools.
- [Gizmo](https://github.com/NYTimes/gizmo) ⭐ 3,751 📅 2021-04-30 - Microservice toolkit used by the New York Times.
- [go-json-rest](https://github.com/ant0ine/go-json-rest) ⭐ 3,510 📅 2017-09-13 - Quick and easy way to setup a RESTful JSON API.
- [go-rest](https://github.com/ungerik/go-rest) ⭐ 128 📅 2017-01-20 - Small and evil REST framework for Go.
- [Goa](https://github.com/goadesign/goa) ⭐ 5,437 📅 2024-03-18 - Goa provides a holistic approach for developing remote APIs and microservices in Go.
- [goa](https://github.com/goa-go/goa) ⭐ 49 📅 2019-12-04 - goa is just like koajs for golang, it is a flexible, light, high-performance and extensible web framework based on middleware.
- [GoFr](https://github.com/gofr-dev/gofr) ⭐ 718 📅 2024-03-19 - Gofr is an opinionated microservice development framework.
- [GoFrame](https://github.com/gogf/gf) ⭐ 10,710 📅 2024-03-21 - GoFrame is a modular, powerful, high-performance and enterprise-class application development framework of Golang.
- [golamb](https://github.com/twharmon/golamb) ⭐ 7 📅 2022-08-24 - Golamb makes it easier to write API endpoints for use with AWS Lambda and API Gateway.
- [Golax](https://github.com/fulldump/golax) ⭐ 75 📅 2023-01-11 - A non Sinatra fast HTTP framework with support for Google custom methods, deep interceptors, recursion and more.
- [Golf](https://github.com/dinever/golf) ⭐ 271 📅 2017-02-24 - Golf is a fast, simple and lightweight micro-web framework for Go. It comes with powerful features and has no dependencies other than the Go Standard Library.
- [Gondola](https://github.com/rainycape/gondola) ⭐ 312 📅 2017-02-20 - The web framework for writing faster sites, faster.
- [gongular](https://github.com/mustafaakin/gongular) ⭐ 503 📅 2020-07-05 - Fast Go web framework with input mapping/validation and (DI) Dependency Injection.
- [GoTuna](https://github.com/gotuna/gotuna) ⭐ 47 📅 2023-08-31 - Minimalistic web framework for Go with mux router, middlewares, sessions, templates, embedded views and static files.
- [goweb](https://github.com/twharmon/goweb) ⭐ 36 📅 2022-08-30 - Web framework with routing, websockets, logging, middleware, static file server (optional gzip), and automatic TLS.
- [Goyave](https://github.com/go-goyave/goyave) ⭐ 1,411 📅 2023-06-09 - Feature-complete REST API framework aimed at clean code and fast development, with powerful built-in functionalities.
- [Hertz](https://github.com/cloudwego/hertz) ⭐ 4,607 📅 2024-03-10 - A high-performance and strong-extensibility Go HTTP framework that helps developers build microservices.
- [hiboot](https://github.com/hidevopsio/hiboot) ⭐ 182 📅 2024-02-23 - hiboot is a high performance web application framework with auto configuration and dependency injection support.
- [Huma](https://github.com/danielgtaylor/huma/) ⭐ 1,034 📅 2024-03-22 - Framework for modern REST/GraphQL APIs with built-in OpenAPI 3, generated documentation, and a CLI.
- [Lit](https://github.com/jvcoutinho/lit) ⭐ 24 📅 2024-02-27 - Highly performant declarative web framework for Golang, aiming for simplicity and quality of life.
- [Macaron](https://github.com/go-macaron/macaron) ⭐ 3,469 📅 2024-03-11 - Macaron is a high productive and modular design web framework in Go.
- [mango](https://github.com/paulbellamy/mango) ⭐ 373 📅 2017-10-17 - Mango is a modular web-application framework for Go, inspired by Rack, and PEP333.
- [Microservice](https://github.com/claygod/microservice) ⭐ 115 📅 2022-12-31 - The framework for the creation of microservices, written in Golang.
- [neo](https://github.com/ivpusic/neo) ⭐ 419 📅 2017-08-14 - Neo is minimal and fast Go Web Framework with extremely simple API.
- [patron](https://github.com/beatlabs/patron) ⭐ 124 📅 2024-03-17 - Patron is a microservice framework following best cloud practices with a focus on productivity.
- [Pnutmux](https://gitlab.com/fruitygo/pnutmux) - Pnutmux is a powerful Go web framework that uses regex for matching and handling HTTP requests. It offers features such as CORS handling, structured logging, URL parameters extraction, middlewares, and concurrency limiting.
- [Pulse](https://github.com/gopulse/pulse) ⭐ 37 📅 2023-04-26 - Pulse is an HTTP web framework written in Go (Golang)
- [Resoursea](https://github.com/resoursea/api) ⭐ 34 📅 2015-02-01 - REST framework for quickly writing resource based services.
- [REST Layer](https://github.com/rs/rest-layer) ⭐ 1,245 📅 2021-09-30 - Framework to build REST/GraphQL API on top of databases with mostly configuration over code.
- [Revel](https://github.com/revel/revel) ⭐ 13,065 📅 2022-04-12 - High-productivity web framework for the Go language.
- [rex](https://github.com/goanywhere/rex) ⭐ 33 📅 2017-12-22 - Rex is a library for modular development built upon gorilla/mux, fully compatible with `net/http`.
- [rk-boot](https://github.com/rookie-ninja/rk-boot) ⭐ 488 📅 2023-11-30 - A bootstrapper library for building enterprise go microservice with Gin and gRPC quickly and easily.
- [rux](https://github.com/gookit/rux) ⭐ 97 📅 2024-03-11 - Simple and fast web framework for build golang HTTP applications.
- [tango](https://github.com/lunny/tango) ⭐ 832 📅 2019-05-17 - Micro & pluggable web framework for Go.
- [tigertonic](https://github.com/rcrowley/go-tigertonic) ⭐ 996 📅 2017-04-20 - Go framework for building JSON web services inspired by Dropwizard.
- [uAdmin](https://github.com/uadmin/uadmin) ⭐ 322 📅 2023-10-30 - Fully featured web framework for Golang, inspired by Django.
- [utron](https://github.com/gernest/utron) ⭐ 2,217 📅 2018-10-28 - Lightweight MVC framework for Go(Golang).
- [vox](https://github.com/aisk/vox) ⭐ 84 📅 2022-12-09 - A golang web framework for humans, inspired by Koa heavily.
- [WebGo](https://github.com/bnkamalesh/webgo) ⭐ 294 📅 2023-03-08 - A micro-framework to build web apps; with handler chaining, middleware and context injection. With standard library compliant HTTP handlers(i.e. http.HandlerFunc).
- [YARF](https://github.com/yarf-framework/yarf) ⭐ 67 📅 2019-03-07 - Fast micro-framework designed to build REST APIs and web services in a fast and simple way.
- [Yokai](https://github.com/ankorstore/yokai) ⭐ 129 📅 2024-03-22 - Simple, modular, and observable Go framework for backend applications.

**[⬆ back to top](#contents)**

### Middlewares

#### Actual middlewares

- [client-timing](https://github.com/posener/client-timing) ⭐ 24 📅 2018-02-26 - An HTTP client for Server-Timing header.
- [CORS](https://github.com/rs/cors) ⭐ 2,514 📅 2024-02-28 - Easily add CORS capabilities to your API.
- [echo-middleware](https://github.com/faabiosr/echo-middleware) ⭐ 14 📅 2023-10-18 - Middleware for Echo framework with logging and metrics.
- [formjson](https://github.com/rs/formjson) ⭐ 38 📅 2015-12-17 - Transparently handle JSON input as a standard form POST.
- [go-fault](https://github.com/github/go-fault) ⭐ 502 📅 2024-03-10 - Fault injection middleware for Go.
- [go-server-timing](https://github.com/mitchellh/go-server-timing) ⭐ 860 📅 2020-11-08 - Add/parse Server-Timing header.
- [Limiter](https://github.com/ulule/limiter) ⭐ 1,926 📅 2023-06-13 - Dead simple rate limit middleware for Go.
- [ln-paywall](https://github.com/philippgille/ln-paywall) ⭐ 138 📅 2018-10-07 - Go middleware for monetizing APIs on a per-request basis with the Lightning Network (Bitcoin).
- [mid](https://github.com/bobg/mid) ⭐ 7 📅 2022-06-28 - Miscellaneous HTTP middleware features: idiomatic error return from handlers; receive/respond with JSON data; request tracing; and more.
- [rk-gin](https://github.com/rookie-ninja/rk-gin) ⭐ 43 📅 2023-10-31 - Middleware for Gin framework with logging, metrics, auth, tracing etc.
- [rk-grpc](https://github.com/rookie-ninja/rk-grpc) ⭐ 70 📅 2023-10-31 - Middleware for gRPC with logging, metrics, auth, tracing etc.
- [Tollbooth](https://github.com/didip/tollbooth) ⭐ 2,572 📅 2022-11-30 - Rate limit HTTP request handler.
- [XFF](https://github.com/sebest/xff) ⭐ 98 📅 2021-01-06 - Handle `X-Forwarded-For` header and friends.

#### Libraries for creating HTTP middlewares

- [alice](https://github.com/justinas/alice) ⭐ 2,949 📅 2021-11-04 - Painless middleware chaining for Go.
- [catena](https://github.com/codemodus/catena) ⭐ 9 📅 2018-08-25 - http.Handler wrapper catenation (same API as "chain").
- [chain](https://github.com/codemodus/chain) ⭐ 63 📅 2018-08-25 - Handler wrapper chaining with scoped data (net/context-based "middleware").
- [gores](https://github.com/alioygur/gores) ⭐ 102 📅 2021-01-01 - Go package that handles HTML, JSON, XML and etc. responses. Useful for RESTful APIs.
- [interpose](https://github.com/carbocation/interpose) ⭐ 293 📅 2016-12-06 - Minimalist net/http middleware for golang.
- [mediary](https://github.com/HereMobilityDevelopers/mediary) ⭐ 89 📅 2020-06-24 - add interceptors to `http.Client` to allow dumping/shaping/tracing/... of requests/responses.
- [muxchain](https://github.com/stephens2424/muxchain) ⭐ 208 📅 2019-02-21 - Lightweight middleware for net/http.
- [negroni](https://github.com/urfave/negroni) ⭐ 7,409 📅 2024-02-18 - Idiomatic HTTP middleware for Golang.
- [render](https://github.com/unrolled/render) ⭐ 1,893 📅 2023-10-17 - Go package for easily rendering JSON, XML, and HTML template responses.
- [renderer](https://github.com/thedevsaddam/renderer) ⭐ 261 📅 2018-12-19 - Simple, lightweight and faster response (JSON, JSONP, XML, YAML, HTML, File) rendering package for Go.
- [rye](https://github.com/InVisionApp/rye) ⭐ 102 📅 2023-05-12 - Tiny Go middleware library (with canned Middlewares) that supports JWT, CORS, Statsd, and Go 1.7 context.
- [stats](https://github.com/thoas/stats) ⭐ 594 📅 2019-04-07 - Go middleware that stores various information about your web application.

**[⬆ back to top](#contents)**

### Routers

- [alien](https://github.com/gernest/alien) ⭐ 129 📅 2022-11-13 - Lightweight and fast http router from outer space.
- [bellt](https://github.com/GuilhermeCaruso/bellt) ⭐ 54 📅 2022-07-18 - A simple Go HTTP router.
- [Bone](https://github.com/go-zoo/bone) ⭐ 1,295 📅 2019-04-16 - Lightning Fast HTTP Multiplexer.
- [Bxog](https://github.com/claygod/Bxog) ⭐ 103 📅 2022-09-07 - Simple and fast HTTP router for Go. It works with routes of varying difficulty, length and nesting. And he knows how to create a URL from the received parameters.
- [chi](https://github.com/go-chi/chi) ⭐ 16,841 📅 2024-02-17 - Small, fast and expressive HTTP router built on net/context.
- [fasthttprouter](https://github.com/buaazp/fasthttprouter) ⭐ 875 📅 2019-01-09 - High performance router forked from `httprouter`. The first router fit for `fasthttp`.
- [FastRouter](https://github.com/razonyang/fastrouter) ⭐ 23 📅 2017-11-02 - a fast, flexible HTTP router written in Go.
- [goblin](https://github.com/bmf-san/goblin) ⭐ 73 📅 2023-10-01 - A golang http router based on trie tree.
- [gocraft/web](https://github.com/gocraft/web) ⭐ 1,507 📅 2019-02-07 - Mux and middleware package in Go.
- [Goji](https://github.com/goji/goji) ⭐ 954 📅 2019-01-26 - Goji is a minimalistic and flexible HTTP request multiplexer with support for `net/context`.
- [GoLobby/Router](https://github.com/golobby/router) ⭐ 22 📅 2022-03-30 - GoLobby Router is a lightweight yet powerful HTTP router for the Go programming language.
- [goroute](https://github.com/goroute/route) ⭐ 9 📅 2019-12-23 - Simple yet powerful HTTP request multiplexer.
- [GoRouter](https://github.com/vardius/gorouter) ⭐ 151 📅 2024-01-01 - GoRouter is a Server/API micro framework, HTTP request router, multiplexer, mux that provides request router with middleware supporting `net/context`.
- [gowww/router](https://github.com/gowww/router) ⭐ 188 📅 2023-09-11 - Lightning fast HTTP router fully compatible with the net/http.Handler interface.
- [httprouter](https://github.com/julienschmidt/httprouter) ⭐ 16,205 📅 2024-01-30 - High performance router. Use this and the standard http handlers to form a very high performance web framework.
- [httptreemux](https://github.com/dimfeld/httptreemux) ⭐ 615 📅 2023-02-01 - High-speed, flexible tree-based HTTP router for Go. Inspiration from httprouter.
- [lars](https://github.com/go-playground/lars) ⭐ 389 📅 2017-10-31 - Is a lightweight, fast and extensible zero allocation HTTP router for Go used to create customizable frameworks.
- [mux](https://github.com/gorilla/mux) ⭐ 20,036 📅 2023-12-21 - Powerful URL router and dispatcher for golang.
- [nchi](https://github.com/muir/nchi) ⭐ 13 📅 2023-07-08 - chi-like router built on httprouter with dependency injection based middleware wrappers
- [ngamux](https://github.com/ngamux/ngamux) ⭐ 63 📅 2023-03-27 - Simple HTTP router for Go.
- [ozzo-routing](https://github.com/go-ozzo/ozzo-routing) ⭐ 450 📅 2021-09-04 - An extremely fast Go (golang) HTTP router that supports regular expression route matching. Comes with full support for building RESTful APIs.
- [pure](https://github.com/go-playground/pure) ⭐ 148 📅 2023-07-13 - Is a lightweight HTTP router that sticks to the std "net/http" implementation.
- [Siesta](https://github.com/VividCortex/siesta) ⭐ 350 📅 2021-04-26 - Composable framework to write middleware and handlers.
- [vestigo](https://github.com/husobee/vestigo) ⭐ 267 📅 2020-10-08 - Performant, stand-alone, HTTP compliant URL Router for go web applications.
- [violetear](https://github.com/nbari/violetear) ⭐ 107 📅 2022-09-27 - Go HTTP router.
- [xmux](https://github.com/rs/xmux) ⭐ 98 📅 2017-06-09 - High performance muxer based on `httprouter` with `net/context` support.
- [xujiajun/gorouter](https://github.com/xujiajun/gorouter) ⭐ 532 📅 2019-09-27 - A simple and fast HTTP router for Go.

**[⬆ back to top](#contents)**

## WebAssembly

- [dom](https://github.com/dennwc/dom) ⭐ 482 📅 2019-05-27 - DOM library.
- [go-canvas](https://github.com/markfarnan/go-canvas) ⭐ 226 📅 2020-07-22 - Library to use HTML5 Canvas, with all drawing within go code.
- [tinygo](https://github.com/tinygo-org/tinygo) ⭐ 14,315 📅 2024-03-10 - Go compiler for small places. Microcontrollers, WebAssembly, and command-line tools. Based on LLVM.
- [vert](https://github.com/norunners/vert) ⭐ 96 📅 2022-10-23 - Interop between Go and JS values.
- [wasmbrowsertest](https://github.com/agnivade/wasmbrowsertest) ⭐ 173 📅 2023-08-27 - Run Go WASM tests in your browser.
- [webapi](https://github.com/gowebapi/webapi) ⭐ 160 📅 2022-12-21 - Bindings for DOM and HTML generated from WebIDL.

**[⬆ back to top](#contents)**

## Windows

- [d3d9](https://github.com/gonutz/d3d9) ⭐ 156 📅 2023-04-20 - Go bindings for Direct3D9.
- [go-ole](https://github.com/go-ole/go-ole) ⭐ 1,085 📅 2023-10-30 - Win32 OLE implementation for golang.
- [gosddl](https://github.com/MonaxGT/gosddl) ⭐ 11 📅 2019-04-30 - Converter from SDDL-string to user-friendly JSON. SDDL consist of four part: Owner, Primary Group, DACL, SACL.

**[⬆ back to top](#contents)**

## XML

_Libraries and tools for manipulating XML._

- [XML-Comp](https://github.com/xml-comp/xml-comp) ⭐ 21 📅 2018-07-19 - Simple command line XML comparer that generates diffs of folders, files and tags.
- [xml2map](https://github.com/sbabiv/xml2map) ⭐ 62 📅 2021-12-07 - XML to MAP converter written Golang.
- [xmlwriter](https://github.com/shabbyrobe/xmlwriter) ⭐ 26 📅 2023-05-25 - Procedural XML generation API based on libxml2's xmlwriter module.
- [xpath](https://github.com/antchfx/xpath) ⭐ 645 📅 2024-03-20 - XPath package for Go.
- [xquery](https://github.com/antchfx/xquery) ⭐ 158 📅 2018-05-15 - XQuery lets you extract data from HTML/XML documents using XPath expression.
- [zek](https://github.com/miku/zek) ⭐ 724 📅 2024-02-19 - Generate a Go struct from XML.

## Zero Trust

_Libraries and tools to implement Zero Trust architectures._

- [Cosign](https://github.com/sigstore/cosign) ⭐ 3,985 📅 2024-03-21 - Container Signing, Verification and Storage in an OCI registry.
- [in-toto](https://github.com/in-toto/in-toto-golang) ⭐ 114 📅 2024-03-17 - Go implementation of the in-toto (provides a framework to protect the integrity of the software supply chain) python reference implementation.
- [Spiffe-Vault](https://github.com/philips-labs/spiffe-vault) ⭐ 75 📅 2024-03-13 - Utilizes Spiffe JWT authentication with Hashicorp Vault for secretless authentication.
- [Spire](https://github.com/spiffe/spire) ⭐ 1,653 📅 2024-03-21 - SPIRE (the SPIFFE Runtime Environment) is a toolchain of APIs for establishing trust between software systems across a wide variety of hosting platforms.

## Code Analysis

_Source code analysis tools, also known as Static Application Security Testing (SAST) Tools._

- [apicompat](https://github.com/bradleyfalzon/apicompat) ⭐ 177 📅 2017-02-05 - Checks recent changes to a Go project for backwards incompatible changes.
- [asty](https://github.com/asty-org/asty) ⭐ 71 📅 2023-05-22 - Converts golang AST to JSON and JSON to AST.
- [blanket](https://gitlab.com/verygoodsoftwarenotvirus/blanket) - blanket is a tool that helps you catch functions which don't have direct unit tests in your Go packages.
- [ChainJacking](https://github.com/Checkmarx/chainjacking) ⭐ 54 📅 2022-05-29 - Find which of your Go lang direct GitHub dependencies is susceptible to ChainJacking attack.
- [Chronos](https://github.com/amit-davidson/Chronos) ⭐ 418 📅 2022-04-22 - Detects race conditions statically
- [dupl](https://github.com/mibk/dupl) ⭐ 327 📅 2020-12-17 - Tool for code clone detection.
- [errcheck](https://github.com/kisielk/errcheck) ⭐ 2,258 📅 2024-02-08 - Errcheck is a program for checking for unchecked errors in Go programs.
- [gcvis](https://github.com/davecheney/gcvis) ⭐ 1,093 📅 2019-03-13 - Visualise Go program GC trace data in real time.
- [go-checkstyle](https://github.com/qiniu/checkstyle) ⭐ 129 📅 2018-11-22 - checkstyle is a style check tool like java checkstyle. This tool inspired by java checkstyle, golint. The style referred to some points in Go Code Review Comments.
- [go-cleanarch](https://github.com/roblaszczak/go-cleanarch) ⭐ 815 📅 2021-11-08 - go-cleanarch was created to validate Clean Architecture rules, like a The Dependency Rule and interaction between packages in your Go projects.
- [go-critic](https://github.com/go-critic/go-critic) ⭐ 1,753 📅 2024-03-10 - source code linter that brings checks that are currently not implemented in other linters.
- [go-mod-outdated](https://github.com/psampaz/go-mod-outdated) ⭐ 647 📅 2023-02-19 - An easy way to find outdated dependencies of your Go projects.
- [go-outdated](https://github.com/firstrow/go-outdated) ⭐ 44 📅 2019-01-15 - Console application that displays outdated packages.
- [goast-viewer](https://github.com/yuroyoro/goast-viewer) ⭐ 747 📅 2019-05-31 - Web based Golang AST visualizer.
- [goimports](https://pkg.go.dev/golang.org/x/tools/cmd/goimports) - Tool to fix (add, remove) your Go imports automatically.
- [golang-ifood-sdk](https://github.com/arxdsilva/golang-ifood-sdk) ⭐ 11 📅 2022-04-05 - iFood API SDK.
- [golangci-lint](https://github.com/golangci/golangci-lint) ⭐ 14,267 📅 2024-03-21 – A fast Go linters runner. It runs linters in parallel, uses caching, supports `yaml` config, has integrations with all major IDE and has dozens of linters included.
- [golines](https://github.com/segmentio/golines) ⭐ 803 📅 2024-01-22 - Formatter that automatically shortens long lines in Go code.
- [GoPlantUML](https://github.com/jfeliu007/goplantuml) ⭐ 1,654 📅 2024-02-22 - Library and CLI that generates text plantump class diagram containing information about structures and interfaces with the relationship among them.
- [goreturns](https://sourcegraph.com/github.com/sqs/goreturns) - Adds zero-value return statements to match the func return types.
- [gostatus](https://github.com/shurcooL/gostatus) ⭐ 242 📅 2021-01-17 - Command line tool, shows the status of repositories that contain Go packages.
- [lint](https://github.com/surullabs/lint) ⭐ 66 📅 2017-10-03 - Run linters as part of go test.
- [php-parser](https://github.com/z7zmey/php-parser) ⭐ 935 📅 2021-02-13 - A Parser for PHP written in Go.
- [revive](https://github.com/mgechev/revive) ⭐ 4,567 📅 2024-03-05 – ~6x faster, stricter, configurable, extensible, and beautiful drop-in replacement for `golint`.
- [staticcheck](https://github.com/dominikh/go-tools/tree/master/cmd/staticcheck) - staticcheck is `go vet` on steroids, applying a ton of static analysis checks you might be used to from tools like ReSharper for C#.
- [testifylint](https://github.com/Antonboom/testifylint) ⭐ 60 📅 2024-03-03 – A linter that checks usage of [github.com/stretchr/testify](https://github.com/stretchr/testify) ⭐ 21,788 📅 2024-03-19.
- [tickgit](https://github.com/augmentable-dev/tickgit) ⭐ 318 📅 2020-06-21 - CLI and go package for surfacing code comment TODOs (in any language) and applying a `git blame`to identify the author.
- [todocheck](https://github.com/preslavmihaylov/todocheck) ⭐ 411 📅 2023-10-14 - Static code analyser which links TODO comments in code with issues in your issue tracker.
- [unconvert](https://github.com/mdempsky/unconvert) ⭐ 375 📅 2023-09-07 - Remove unnecessary type conversions from Go source.
- [usestdlibvars](https://github.com/sashamelentyev/usestdlibvars) ⭐ 42 📅 2024-02-12 - A linter that detect the possibility to use variables/constants from the Go standard library.
- [vacuum](https://github.com/daveshanley/vacuum) ⭐ 390 📅 2024-03-14 - An ultra-super-fast, lightweight OpenAPI linter and quality checking tool.
- [validate](https://github.com/mccoyst/validate) ⭐ 61 📅 2023-08-18 - Automatically validates struct fields with tags.

**[⬆ back to top](#contents)**

## Editor Plugins

_Plugin for text editors and IDEs._

- [coc-go language server extension for Vim/Neovim](https://github.com/josa42/coc-go) ⭐ 563 📅 2023-12-19 - This plugin adds [gopls](https://github.com/golang/tools/blob/master/gopls/README.md) features to Vim/Neovim.
- [Go Doc](https://github.com/msyrus/vscode-go-doc) ⭐ 8 📅 2024-02-08 - A Visual Studio Code extension for showing definition in output and generating go doc.
- [Go plugin for JetBrains IDEs](https://plugins.jetbrains.com/plugin/9568-go) - Go plugin for JetBrains IDEs.
- [go-language-server](https://github.com/theia-ide/go-language-server) ⭐ 32 📅 2019-03-15 - A wrapper to turn the VSCode go extension into a language server supporting the language-server-protocol.
- [go-mode](https://github.com/dominikh/go-mode.el) - Go mode for GNU/Emacs.
- [go-plus](https://github.com/joefitzgerald/go-plus) ⭐ 1,513 📅 2019-05-26 - Go (Golang) Package For Atom That Adds Autocomplete, Formatting, Syntax Checking, Linting and Vetting.
- [gocode](https://github.com/nsf/gocode) ⭐ 5,007 📅 2023-03-22 - Autocompletion daemon for the Go programming language.
- [goimports-reviser](https://github.com/incu6us/goimports-reviser) ⭐ 525 📅 2024-01-24 - Formatting tool for imports.
- [goprofiling](https://marketplace.visualstudio.com/items?itemName=MaxMedia.go-prof) - This extension adds benchmark profiling support for the Go language to VS Code.
- [GoSublime](https://github.com/DisposaBoy/GoSublime) ⭐ 3,416 📅 2020-06-14 - Golang plugin collection for the text editor SublimeText 3 providing code completion and other IDE-like features.
- [gounit-vim](https://github.com/hexdigest/gounit-vim) ⭐ 23 📅 2018-10-29 - Vim plugin for generating Go tests based on the function's or method's signature.
- [theia-go-extension](https://github.com/theia-ide/theia-go-extension) ⭐ 15 📅 2019-03-13 - Go language support for the Theia IDE.
- [vim-compiler-go](https://github.com/rjohnsondev/vim-compiler-go) ⭐ 87 📅 2016-06-28 - Vim plugin to highlight syntax errors on save.
- [vim-go](https://github.com/fatih/vim-go) ⭐ 15,810 📅 2024-03-18 - Go development plugin for Vim.
- [vscode-go](https://github.com/golang/vscode-go) ⭐ 3,700 📅 2024-03-14 - Extension for Visual Studio Code (VS Code) which provides support for the Go language.
- [Watch](https://github.com/eaburns/Watch) ⭐ 202 📅 2023-03-18 - Runs a command in an acme win on file changes.

**[⬆ back to top](#contents)**

## Go Generate Tools

- [envdoc](https://github.com/g4s8/envdoc) ⭐ 31 📅 2024-03-12 -  generate documentation for environment variables from Go source files.
- [generic](https://github.com/usk81/generic) ⭐ 48 📅 2020-08-22 - flexible data type for Go.
- [genny](https://github.com/cheekybits/genny) ⭐ 1,692 📅 2020-07-09 - Elegant generics for Go.
- [gocontracts](https://github.com/Parquery/gocontracts) ⭐ 104 📅 2019-01-26 - brings design-by-contract to Go by synchronizing the code with the documentation.
- [godal](https://github.com/mafulong/godal) ⭐ 18 📅 2021-10-23 - Generate orm models corresponding to golang by specifying sql ddl file, which can be used by gorm.
- [gonerics](https://github.com/bouk/gonerics) ⭐ 114 📅 2014-09-29 - Idiomatic Generics in Go.
- [gotests](https://github.com/cweill/gotests) ⭐ 4,824 📅 2021-05-23 - Generate Go tests from your source code.
- [gounit](https://github.com/hexdigest/gounit) ⭐ 76 📅 2018-08-17 - Generate Go tests using your own templates.
- [hasgo](https://github.com/DylanMeeus/hasgo) ⭐ 133 📅 2021-02-22 - Generate Haskell inspired functions for your slices.
- [options-gen](https://github.com/kazhuravlev/options-gen) ⭐ 53 📅 2024-01-25 - Functional options described by Dave Cheney's post "Functional options for friendly APIs".
- [re2dfa](https://gitlab.com/opennota/re2dfa) - Transform regular expressions into finite state machines and output Go source code.
- [sqlgen](https://github.com/anqiansong/sqlgen) ⭐ 75 📅 2023-02-14 - Generate gorm, xorm, sqlx, bun, sql code from SQL file or DSN.
- [TOML-to-Go](https://xuri.me/toml-to-go) - Translates TOML into a Go type in the browser instantly.
- [xgen](https://github.com/xuri/xgen) ⭐ 289 📅 2023-07-02 - XSD (XML Schema Definition) parser and Go/C/Java/Rust/TypeScript code generator.

**[⬆ back to top](#contents)**

## Go Tools

- [colorgo](https://github.com/songgao/colorgo) ⭐ 113 📅 2016-10-28 - Wrapper around `go` command for colorized `go build` output.
- [decouple](https://github.com/bobg/decouple) ⭐ 18 📅 2024-02-19 - Find “overspecified” function parameters that could be generalized with interface types.
- [depth](https://github.com/KyleBanks/depth) ⭐ 874 📅 2021-12-10 - Visualize dependency trees of any package by analyzing imports.
- [docs](https://github.com/go-oas/docs) ⭐ 34 📅 2023-03-15 - Automatically generate RESTful API documentation for GO projects - aligned with Open API Specification standard.
- [go-callvis](https://github.com/TrueFurby/go-callvis) ⭐ 5,683 📅 2023-05-08 - Visualize call graph of your Go program using dot format.
- [go-james](https://github.com/pieterclaerhout/go-james) ⭐ 63 📅 2023-05-08 - Go project skeleton creator, builds and tests your projects without the manual setup.
- [go-pkg-complete](https://github.com/skelterjohn/go-pkg-complete) ⭐ 43 📅 2017-11-17 - Bash completion for go and wgo.
- [go-swagger](https://github.com/go-swagger/go-swagger) ⭐ 9,220 📅 2024-03-19 - Swagger 2.0 implementation for go. Swagger is a simple yet powerful representation of your RESTful API.
- [godbg](https://github.com/tylerwince/godbg) ⭐ 199 📅 2019-04-20 - Implementation of Rusts `dbg!` macro for quick and easy debugging during development.
- [gomodrun](https://github.com/dustinblackman/gomodrun/) ⭐ 31 📅 2024-02-07 - Go tool that executes and caches binaries included in go.mod files.
- [gotemplate.io](https://gotemplate.io/) - Online tool to preview `text/template` templates live.
- [gotestdox](https://github.com/bitfield/gotestdox) ⭐ 82 📅 2024-02-08 - Show Go test results as readable sentences.
- [gothanks](https://github.com/psampaz/gothanks) ⭐ 122 📅 2023-02-18 - GoThanks automatically stars your go.mod github dependencies, sending this way some love to their maintainers.
- [igo](https://github.com/rocketlaunchr/igo) ⭐ 65 📅 2020-04-06 - An igo to go transpiler (new language features for Go language!)
- [modver](https://github.com/bobg/modver) ⭐ 16 📅 2024-02-18 - Compare two versions of a Go module to check the version-number change required (major, minor, or patchlevel), according to [semver](https://semver.org/) rules.
- [OctoLinker](https://github.com/OctoLinker/browser-extension) ⭐ 5,233 📅 2023-07-03 - Navigate through go files efficiently with the OctoLinker browser extension for GitHub.
- [richgo](https://github.com/kyoh86/richgo) ⭐ 827 📅 2023-07-09 - Enrich `go test` outputs with text decorations.
- [roumon](https://github.com/becheran/roumon) ⭐ 166 📅 2024-01-04 - Monitor current state of all active goroutines via a command line interface.
- [rts](https://github.com/galeone/rts) ⭐ 248 📅 2022-10-29 - RTS: response to struct. Generates Go structs from server responses.
- [textra](https://github.com/ravsii/textra) ⭐ 4 📅 2023-04-30 - Extract Go struct field names, types and tags for filtering and exporting.
- [typex](https://github.com/dtgorski/typex) ⭐ 195 📅 2023-09-15 - Examine Go types and their transitive dependencies, alternatively export results as TypeScript value objects (or types) declaration.

**[⬆ back to top](#contents)**

## Software Packages

_Software written in Go._

**[⬆ back to top](#contents)**

### DevOps Tools

- [abbreviate](https://github.com/dnnrly/abbreviate) ⭐ 212 📅 2023-10-03 - abbreviate is a tool turning long strings in to shorter ones with configurable separators, for example to embed branch names in to deployment stack IDs.
- [aptly](https://github.com/smira/aptly) ⭐ 11 📅 2019-07-03 - aptly is a Debian repository management tool.
- [aurora](https://github.com/xuri/aurora) ⭐ 591 📅 2021-08-19 - Cross-platform web-based Beanstalkd queue server console.
- [awsenv](https://github.com/soniah/awsenv) ⭐ 34 📅 2018-07-17 - Small binary that loads Amazon (AWS) environment variables for a profile.
- [Balerter](https://github.com/balerter/balerter) ⭐ 296 📅 2022-08-15 - A self-hosted script-based alerting manager.
- [Blast](https://github.com/dave/blast) ⭐ 216 📅 2018-03-01 - A simple tool for API load testing and batch jobs.
- [bombardier](https://github.com/codesenberg/bombardier) ⭐ 5,199 📅 2023-12-09 - Fast cross-platform HTTP benchmarking tool.
- [bosun](https://github.com/bosun-monitor/bosun) ⭐ 3,365 📅 2021-05-13 - Time Series Alerting Framework.
- [cassowary](https://github.com/rogerwelin/cassowary) ⭐ 716 📅 2023-04-26 - Modern cross-platform HTTP load-testing tool written in Go.
- [Ddosify](https://github.com/ddosify/ddosify) ⭐ 8,153 📅 2024-03-18 - High-performance load testing tool, written in Golang.
- [decompose](https://github.com/s0rg/decompose) ⭐ 71 📅 2024-03-19 - tool to generate and process Docker containers connections graphs.
- [DepCharge](https://github.com/centerorbit/depcharge) ⭐ 23 📅 2021-12-23 - Helps orchestrating the execution of commands across the many dependencies in larger projects.
- [Docker](https://www.docker.com/) - Open platform for distributed applications for developers and sysadmins.
- [docker-go-mingw](https://github.com/x1unix/docker-go-mingw) ⭐ 41 📅 2023-03-24 - Docker image for building Go binaries for Windows with MinGW toolchain.
- [Dockerfile-Generator](https://github.com/ozankasikci/dockerfile-generator) ⭐ 163 📅 2022-05-23 - A go library and an executable that produces valid Dockerfiles using various input channels.
- [dogo](https://github.com/liudng/dogo) ⭐ 259 📅 2016-11-02 - Monitoring changes in the source file and automatically compile and run (restart).
- [drone-jenkins](https://github.com/appleboy/drone-jenkins) ⭐ 38 📅 2020-09-26 - Trigger downstream Jenkins jobs using a binary, docker or Drone CI.
- [drone-scp](https://github.com/appleboy/drone-scp) ⭐ 134 📅 2024-01-11 - Copy files and artifacts via SSH using a binary, docker or Drone CI.
- [Dropship](https://github.com/chrismckenzie/dropship) ⭐ 64 📅 2018-07-25 - Tool for deploying code via cdn.
- [easyssh-proxy](https://github.com/appleboy/easyssh-proxy) ⭐ 304 📅 2024-03-19 - Golang package for easy remote execution through SSH and SCP downloading via `ProxyCommand`.
- [fac](https://github.com/mkchoi212/fac) ⭐ 1,827 📅 2023-12-29 - Command-line user interface to fix git merge conflicts.
- [Flannel](https://github.com/flannel-io/flannel) ⭐ 8,459 📅 2024-03-21 - Flannel is a network fabric for containers, designed for Kubernetes.
- [Fleet device management](https://github.com/fleetdm/fleet) ⭐ 2,019 📅 2024-03-21 - Lightweight, programmable telemetry for servers and workstations.
- [gaia](https://github.com/gaia-pipeline/gaia) ⭐ 5,151 📅 2022-03-16 - Build powerful pipelines in any programming language.
- [ghorg](https://github.com/gabrie30/ghorg) ⭐ 1,438 📅 2024-03-14 - Quickly clone an entire org/users repositories into one directory - Supports GitHub, GitLab, Gitea, and Bitbucket.
- [Gitea](https://github.com/go-gitea/gitea) ⭐ 41,329 📅 2024-03-22 - Fork of Gogs, entirely community driven.
- [gitea-github-migrator](https://git.jonasfranz.software/JonasFranzDEV/gitea-github-migrator) - Migrate all your GitHub repositories, issues, milestones and labels to your Gitea instance.
- [go-furnace](https://github.com/go-furnace/go-furnace) ⭐ 97 📅 2019-09-19 - Hosting solution written in Go. Deploy your Application with ease on AWS, GCP or DigitalOcean.
- [go-rocket-update](https://github.com/mouuff/go-rocket-update) ⭐ 92 📅 2024-03-09 - A simple way to make self updating Go applications - Supports Github and Gitlab.
- [go-selfupdate](https://github.com/sanbornm/go-selfupdate) ⭐ 1,397 📅 2023-07-14 - Enable your Go applications to self update.
- [gobrew](https://github.com/cryptojuice/gobrew) ⭐ 194 📅 2020-05-21 - gobrew lets you easily switch between multiple versions of go.
- [gobrew](https://github.com/kevincobain2000/gobrew) ⭐ 336 📅 2024-03-14 - Go version manager. Super simple tool to install and manage Go versions. Install go without root. Gobrew doesn't require shell rehash.
- [godbg](https://github.com/sirnewton01/godbg) ⭐ 227 📅 2018-07-09 - Web-based gdb front-end application.
- [Gogs](https://gogs.io/) - A Self Hosted Git Service in the Go Programming Language.
- [gonative](https://github.com/inconshreveable/gonative) ⭐ 338 📅 2016-07-21 - Tool which creates a build of Go that can cross compile to all platforms while still using the Cgo-enabled versions of the stdlib packages.
- [govvv](https://github.com/ahmetalpbalkan/govvv) ⭐ 536 📅 2023-03-24 - “go build” wrapper to easily add version information into Go binaries.
- [gox](https://github.com/mitchellh/gox) ⭐ 4,590 📅 2022-07-01 - Dead simple, no frills Go cross compile tool.
- [goxc](https://github.com/laher/goxc) ⭐ 1,682 📅 2018-03-02 - build tool for Go, with a focus on cross-compiling and packaging.
- [grapes](https://github.com/yaronsumel/grapes) ⭐ 167 📅 2023-03-13 - Lightweight tool designed to distribute commands over ssh with ease.
- [GVM](https://github.com/moovweb/gvm) ⭐ 9,462 📅 2023-08-14 - GVM provides an interface to manage Go versions.
- [Hey](https://github.com/rakyll/hey) ⭐ 17,091 📅 2021-03-23 - Hey is a tiny program that sends some load to a web application.
- [httpref](https://github.com/dnnrly/httpref) ⭐ 35 📅 2023-06-26 - httpref is a handy CLI reference for HTTP methods, status codes, headers, and TCP and UDP ports.
- [jcli](https://github.com/jenkins-zh/jenkins-cli) ⭐ 374 📅 2023-02-26 - Jenkins CLI allows you manage your Jenkins as an easy way.
- [k3d](https://github.com/k3d-io/k3d) ⭐ 5,023 📅 2024-02-15 - Little helper to run CNCF's k3s in Docker.
- [k3s](https://github.com/k3s-io/k3s) ⭐ 26,143 📅 2024-03-17 - Lightweight Kubernetes.
- [k6](https://github.com/grafana/k6) ⭐ 23,068 📅 2024-03-21 - A modern load testing tool, using Go and JavaScript.
- [kala](https://github.com/ajvb/kala) ⭐ 2,080 📅 2023-02-21 - Simplistic, modern, and performant job scheduler.
- [kcli](https://github.com/cswank/kcli) ⭐ 208 📅 2020-01-04 - Command line tool for inspecting kafka topics/partitions/messages.
- [kind](https://github.com/kubernetes-sigs/kind) ⭐ 12,639 📅 2024-03-18 - Kubernetes IN Docker - local clusters for testing Kubernetes.
- [ko](https://github.com/google/ko) ⭐ 7,127 📅 2023-04-27 - Command line tool for building and deploying Go applications on Kubernetes
- [kool](https://github.com/kool-dev/kool) ⭐ 661 📅 2024-02-29 - Command line tool for managing Docker environments as an easy way.
- [kubernetes](https://github.com/kubernetes/kubernetes) ⭐ 105,959 📅 2024-03-21 - Container Cluster Manager from Google.
- [kubeshark](https://github.com/kubeshark/kubeshark) ⭐ 10,429 📅 2024-03-19 - API traffic analyzer for Kubernetes, inspired by Wireshark, purposely built for Kubernetes.
- [KubeVela](https://github.com/kubevela/kubevela) ⭐ 5,978 📅 2024-03-15 - Cloud native application delivery.
- [kubevpn](https://github.com/kubenetworks/kubevpn) ⭐ 343 📅 2024-03-08 - VPN tools to connect kubernetes cluster network and proxy workloads inbound traffic to local PC with service mesh.
- [kwatch](https://github.com/abahmed/kwatch) ⭐ 914 📅 2024-03-18 - Monitor & detect crashes in your Kubernetes(K8s) cluster instantly.
- [lstags](https://github.com/ivanilves/lstags) ⭐ 319 📅 2023-03-24 - Tool and API to sync Docker images across different registries.
- [lwc](https://github.com/timdp/lwc) ⭐ 32 📅 2022-07-26 - A live-updating version of the UNIX wc command.
- [manssh](https://github.com/xwjdsh/manssh) ⭐ 292 📅 2022-02-11 - manssh is a command line tool for managing your ssh alias config easily.
- [Mantil](https://github.com/mantil-io/mantil) ⭐ 108 📅 2022-11-07 - Go specific framework for building serverless applications on AWS that enables you to focus on pure Go code while Mantil takes care of the infrastructure.
- [minikube](https://github.com/kubernetes/minikube) ⭐ 28,204 📅 2024-03-21 - Run Kubernetes locally.
- [Moby](https://github.com/moby/moby) ⭐ 67,550 📅 2024-03-22 - Collaborative project for the container ecosystem to assemble container-based systems.
- [Mora](https://github.com/emicklei/mora) ⭐ 314 📅 2022-11-01 - REST server for accessing MongoDB documents and meta data.
- [ostent](https://github.com/ostrost/ostent) ⭐ 178 📅 2022-12-12 - collects and displays system metrics and optionally relays to Graphite and/or InfluxDB.
- [Packer](https://github.com/mitchellh/packer) ⭐ 14,843 📅 2024-03-21 - Packer is a tool for creating identical machine images for multiple platforms from a single source configuration.
- [Pewpew](https://github.com/bengadbois/pewpew) ⭐ 403 📅 2022-05-18 - Flexible HTTP command line stress tester.
- [PipeCD](https://github.com/pipe-cd/pipecd) ⭐ 939 📅 2024-03-20 - A GitOps-style continuous delivery platform that provides consistent deployment and operations experience for any applications.
- [Pomerium](https://github.com/pomerium/pomerium) ⭐ 3,807 📅 2024-03-22 - Pomerium is an identity-aware access proxy.
- [Rodent](https://github.com/alouche/rodent) ⭐ 33 📅 2017-04-22 - Rodent helps you manage Go versions, projects and track dependencies.
- [s3-proxy](https://github.com/oxyno-zeta/s3-proxy) ⭐ 259 📅 2024-03-20 - S3 Proxy with GET, PUT and DELETE methods and authentication (OpenID Connect and Basic Auth).
- [s3gof3r](https://github.com/rlmcpherson/s3gof3r) ⭐ 1,142 📅 2017-02-10 - Small utility/library optimized for high speed transfer of large objects into and out of Amazon S3.
- [s5cmd](https://github.com/peak/s5cmd) ⭐ 2,281 📅 2023-10-12 - Blazing fast S3 and local filesystem execution tool.
- [Scaleway-cli](https://github.com/scaleway/scaleway-cli) ⭐ 864 📅 2024-03-20 - Manage BareMetal Servers from Command Line (as easily as with Docker).
- [script](https://github.com/bitfield/script) ⭐ 4,905 📅 2024-02-08 - Making it easy to write shell-like scripts in Go for DevOps and system administration tasks.
- [sg](https://github.com/ChristopherRabotin/sg) ⭐ 8 📅 2016-10-28 - Benchmarks a set of HTTP endpoints (like ab), with possibility to use the response code and data between each call for specific server stress based on its previous response.
- [skm](https://github.com/TimothyYe/skm) ⭐ 927 📅 2023-05-12 - SKM is a simple and powerful SSH Keys Manager, it helps you to manage your multiple SSH keys easily!
- [StatusOK](https://github.com/sanathp/statusok) ⭐ 1,605 📅 2020-02-01 - Monitor your Website and REST APIs.Get Notified through Slack, E-mail when your server is down or response time is more than expected.
- [tau](https://github.com/taubyte/tau) ⭐ 142 📅 2024-03-08 - Easily build Cloud Computing Platforms with features like Serverless WebAssembly Functions, Frontend Hosting, CI/CD, Object Storage, K/V Database, and Pub-Sub Messaging.
- [terraform-provider-openapi](https://github.com/dikhan/terraform-provider-openapi) ⭐ 270 📅 2022-10-17 - Terraform provider plugin that dynamically configures itself at runtime based on an OpenAPI document (formerly known as swagger file) containing the definitions of the APIs exposed.
- [tf-profile](https://github.com/datarootsio/tf-profile) ⭐ 142 📅 2024-02-07 - Profiler for Terraform runs. Generate global stats, resource-level stats or visualizations.
- [traefik](https://github.com/containous/traefik) ⭐ 47,317 📅 2024-02-27 - Reverse proxy and load balancer with support for multiple backends.
- [trubka](https://github.com/xitonix/trubka) ⭐ 331 📅 2020-12-09 - A CLI tool to manage and troubleshoot Apache Kafka clusters with the ability of generically publishing/consuming protocol buffer and plain text events to/from Kafka.
- [uTask](https://github.com/ovh/utask) ⭐ 1,079 📅 2024-02-26 - Automation engine that models and executes business processes declared in yaml.
- [Vegeta](https://github.com/tsenart/vegeta) ⭐ 22,605 📅 2023-10-17 - HTTP load testing tool and library. It's over 9000!
- [wait-for](https://github.com/dnnrly/wait-for) ⭐ 18 📅 2023-02-02 - Wait for something to happen (from the command line) before continuing. Easy orchestration of Docker services and other things.
- [webhook](https://github.com/adnanh/webhook) ⭐ 9,744 📅 2024-02-20 - Tool which allows user to create HTTP endpoints (hooks) that execute commands on the server.
- [Wide](https://wide.b3log.org/login) - Web-based IDE for Teams using Golang.
- [winrm-cli](https://github.com/masterzen/winrm-cli) ⭐ 162 📅 2020-05-15 - Cli tool to remotely execute commands on Windows machines.

**[⬆ back to top](#contents)**

### Other Software

- [Better Go Playground](https://goplay.tools) - Go playground with syntax highlight, code completion and other features.
- [blocky](https://github.com/0xERR0R/blocky) ⭐ 3,490 📅 2024-01-27 - Fast and lightweight DNS proxy as ad-blocker for local network with many features.
- [borg](https://github.com/crufter/borg) ⭐ 1,602 📅 2018-02-07 - Terminal based search engine for bash snippets.
- [boxed](https://github.com/tejo/boxed) ⭐ 80 📅 2018-08-09 - Dropbox based blog engine.
- [Cherry](https://github.com/rafael-santiago/cherry) ⭐ 299 📅 2016-12-14 - Tiny webchat server in Go.
- [Circuit](https://github.com/gocircuit/circuit) ⭐ 1,973 📅 2016-11-21 - Circuit is a programmable platform-as-a-service (PaaS) and/or Infrastructure-as-a-Service (IaaS), for management, discovery, synchronization and orchestration of services and hosts comprising cloud applications.
- [Comcast](https://github.com/tylertreat/Comcast) ⭐ 10,201 📅 2022-04-22 - Simulate bad network connections.
- [confd](https://github.com/kelseyhightower/confd) ⭐ 8,256 📅 2023-12-09 - Manage local application configuration files using templates and data from etcd or consul.
- [crawley](https://github.com/s0rg/crawley) ⭐ 218 📅 2024-03-08 - Web scraper/crawler for cli.
- [croc](https://github.com/schollz/croc) ⭐ 26,098 📅 2024-03-11 - Easily and securely send files or folders from one computer to another.
- [Documize](https://github.com/documize/community) ⭐ 2,049 📅 2024-02-19 - Modern wiki software that integrates data from SaaS tools.
- [dp](https://github.com/scryinfo/dp) ⭐ 82 📅 2021-06-22 - Through SDK for data exchange with blockchain, developers can get easy access to DAPP development.
- [drive](https://github.com/odeke-em/drive) ⭐ 6,620 📅 2021-02-08 - Google Drive client for the commandline.
- [Duplicacy](https://github.com/gilbertchen/duplicacy) ⭐ 4,971 📅 2024-01-16 - A cross-platform network and cloud backup tool based on the idea of lock-free deduplication.
- [fjira](https://github.com/mk-5/fjira) ⭐ 82 📅 2024-02-12 - A fuzzy-search based terminal UI application for Attlasian Jira
- [Gebug](https://github.com/moshebe/gebug) ⭐ 630 📅 2024-01-27 - A tool that makes debugging of Dockerized Go applications super easy by enabling Debugger and Hot-Reload features, seamlessly.
- [gfile](https://github.com/Antonito/gfile) ⭐ 725 📅 2019-04-13 - Securely transfer files between two computers, without any third party, over WebRTC.
- [Go Package Store](https://github.com/shurcooL/Go-Package-Store) ⭐ 898 📅 2021-03-13 - App that displays updates for the Go packages in your GOPATH.
- [go-peerflix](https://github.com/Sioro-Neoku/go-peerflix) ⭐ 466 📅 2019-12-04 - Video streaming torrent client.
- [goblin](https://goblin.reaper.im) - Golang binaries in a curl, built by goblins.
- [GoBoy](https://github.com/Humpheh/goboy) ⭐ 2,573 📅 2020-08-09 - Nintendo Game Boy Color emulator written in Go.
- [gocc](https://github.com/goccmack/gocc) ⭐ 592 📅 2023-02-28 - Gocc is a compiler kit for Go written in Go.
- [GoDocTooltip](https://github.com/diankong/GoDocTooltip) ⭐ 13 📅 2022-12-03 - Chrome extension for Go Doc sites, which shows function description as tooltip at function list.
- [Gokapi](https://github.com/Forceu/gokapi) ⭐ 934 📅 2024-02-28 - Lightweight server to share files, which expire after a set amount of downloads or days. Similar to Firefox Send, but without public upload.
- [GoLand](https://jetbrains.com/go) - Full featured cross-platform Go IDE.
- [GoNB](https://github.com/janpfeifer/gonb) ⭐ 396 📅 2024-02-18 - Interactive Go programming with Jupyter Notebooks (also works in VSCode, Binder and Google's Colab).
- [Gor](https://github.com/buger/gor) ⭐ 18,218 📅 2024-03-20 - Http traffic replication tool, for replaying traffic from production to stage/dev environments in real-time.
- [Guora](https://github.com/meloalright/guora) ⭐ 662 📅 2023-01-31 - A self-hosted Quora like web application written in Go.
- [hoofli](https://github.com/dnnrly/hoofli) ⭐ 8 📅 2022-10-23 - Generate PlantUML diagrams from Chrome or Firefox network inspections.
- [hotswap](https://github.com/edwingeng/hotswap) ⭐ 290 📅 2024-02-25 - A complete solution to reload your go code without restarting your server, interrupting or blocking any ongoing procedure.
- [hugo](https://gohugo.io/) - Fast and Modern Static Website Engine.
- [ide](https://github.com/thestrukture/ide) ⭐ 356 📅 2022-11-24 - Browser accessible IDE. Designed for Go with Go.
- [ipe](https://github.com/dimiro1/ipe) ⭐ 367 📅 2018-12-19 - Open source Pusher server implementation compatible with Pusher client libraries written in GO.
- [joincap](https://github.com/assafmo/joincap) ⭐ 202 📅 2020-04-19 - Command-line utility for merging multiple pcap files together.
- [Juju](https://jujucharms.com/) - Cloud-agnostic service deployment and orchestration - supports EC2, Azure, Openstack, MAAS and more.
- [Leaps](https://github.com/jeffail/leaps) ⭐ 745 📅 2021-02-22 - Pair programming service using Operational Transforms.
- [lgo](https://github.com/yunabe/lgo) ⭐ 2,351 📅 2019-07-09 - Interactive Go programming with Jupyter. It supports code completion, code inspection and 100% Go compatibility.
- [limetext](https://limetext.github.io) - Lime Text is a powerful and elegant text editor primarily developed in Go that aims to be a Free and open-source software successor to Sublime Text.
- [LiteIDE](https://github.com/visualfc/liteide) ⭐ 7,437 📅 2024-01-15 - LiteIDE is a simple, open source, cross-platform Go IDE.
- [mockingjay](https://github.com/quii/mockingjay-server) ⭐ 549 📅 2021-01-15 - Fake HTTP servers and consumer driven contracts from one configuration file. You can also make the server randomly misbehave to help do more realistic performance tests.
- [myLG](https://github.com/mehrdadrad/mylg) ⭐ 2,683 📅 2020-02-26 - Command Line Network Diagnostic tool written in Go.
- [naclpipe](https://github.com/unix4fun/naclpipe) ⭐ 24 📅 2018-11-18 - Simple NaCL EC25519 based crypto pipe tool written in Go.
- [Neo-cowsay](https://github.com/Code-Hex/Neo-cowsay) ⭐ 286 📅 2023-08-17 - 🐮 cowsay is reborn. for a New Era.
- [nes](https://github.com/fogleman/nes) ⭐ 5,354 📅 2023-09-07 - Nintendo Entertainment System (NES) emulator written in Go.
- [Orbit](https://github.com/gulien/orbit) ⭐ 179 📅 2021-01-18 - A simple tool for running commands and generating files from templates.
- [peg](https://github.com/pointlander/peg) ⭐ 961 📅 2024-03-06 - Peg, Parsing Expression Grammar, is an implementation of a Packrat parser generator.
- [Plik](https://github.com/root-gg/plik) ⭐ 1,369 📅 2024-02-28 - Plik is a temporary file upload system (Wetransfer like) in Go.
- [portal](https://github.com/SpatiumPortae/portal) ⭐ 1,105 📅 2024-03-16 - Portal is a quick and easy command-line file transfer utility from any computer to another.
- [protoncheck](https://github.com/servusdei2018/protoncheck) ⭐ 5 📅 2022-02-13 - ProtonMail module for waybar/polybar/yabar/i3blocks.
- [restic](https://github.com/restic/restic) ⭐ 23,340 📅 2024-03-17 - De-duplicating backup program.
- [sake](https://github.com/alajmo/sake) ⭐ 636 📅 2023-09-25 - sake is a command runner for local and remote hosts.
- [scc](https://github.com/boyter/scc) ⭐ 5,809 📅 2024-03-22 - Sloc Cloc and Code, a very fast accurate code counter with complexity calculations and COCOMO estimates.
- [Seaweed File System](https://github.com/chrislusf/seaweedfs) ⭐ 20,785 📅 2024-03-22 - Fast, Simple and Scalable Distributed File System with O(1) disk seek.
- [shell2http](https://github.com/msoap/shell2http) ⭐ 1,255 📅 2024-03-16 - Executing shell commands via http server (for prototyping or remote control).
- [Snitch](https://github.com/lucasgomide/snitch) ⭐ 17 📅 2018-07-23 - Simple way to notify your team and many tools when someone has deployed any application via Tsuru.
- [Stack Up](https://github.com/pressly/sup) ⭐ 2,459 📅 2022-01-21 - Stack Up, a super simple deployment tool - just Unix - think of it like 'make' for a network of servers.
- [stew](https://github.com/marwanhawari/stew) ⭐ 127 📅 2024-01-22 - An independent package manager for compiled binaries.
- [syncthing](https://syncthing.net/) - Open, decentralized file synchronization tool and protocol.
- [tcpdog](https://github.com/mehrdadrad/tcpdog) ⭐ 248 📅 2021-07-21 - eBPF based TCP observability.
- [tcpprobe](https://github.com/mehrdadrad/tcpprobe) ⭐ 350 📅 2021-02-21 - TCP tool for network performance and path monitoring, including socket statistics.
- [term-quiz](https://github.com/crazcalm/term-quiz) ⭐ 26 📅 2018-10-24 - Quizzes for your terminal.
- [toxiproxy](https://github.com/shopify/toxiproxy) ⭐ 10,216 📅 2024-03-12 - Proxy to simulate network and system conditions for automated tests.
- [tsuru](https://tsuru.io/) - Extensible and open source Platform as a Service software.
- [vaku](https://github.com/lingrino/vaku) ⭐ 152 📅 2024-03-20 - CLI & API for folder-based functions in Vault like copy, move, and search.
- [vFlow](https://github.com/VerizonDigital/vflow) ⭐ 1,055 📅 2024-03-06 - High-performance, scalable and reliable IPFIX, sFlow and Netflow collector.
- [Wave Terminal](https://waveterm.dev) - Wave is an open-source, AI-native terminal built for seamless developer workflows with inline rendering, a modern UI, and persistent sessions.
- [wellington](https://github.com/wellington/wellington) ⭐ 304 📅 2020-09-08 - Sass project management tool, extends the language with sprite functions (like Compass).
- [woke](https://github.com/get-woke/woke) ⭐ 420 📅 2022-08-14 - Detect non-inclusive language in your source code.
- [yai](https://github.com/ekkinox/yai) ⭐ 521 📅 2023-12-14 - AI powered terminal assistant.
- [zs](https://git.mills.io/prologic/zs) - an extremely minimal static site generator.

**[⬆ back to top](#contents)**

# Resources

_Where to discover new Go libraries._

**[⬆ back to top](#contents)**

## Benchmarks

- [autobench](https://github.com/davecheney/autobench) ⭐ 99 📅 2014-06-19 - Framework to compare the performance between different Go versions.
- [go-benchmark-app](https://github.com/mrLSD/go-benchmark-app) ⭐ 27 📅 2017-03-17 - Powerful HTTP-benchmark tool mixed with Аb, Wrk, Siege tools. Gathering statistics and various parameters for benchmarks and comparison results.
- [go-benchmarks](https://github.com/tylertreat/go-benchmarks) ⭐ 146 📅 2016-02-25 - Few miscellaneous Go microbenchmarks. Compare some language features to alternative approaches.
- [go-http-routing-benchmark](https://github.com/julienschmidt/go-http-routing-benchmark) ⭐ 1,636 📅 2020-07-26 - Go HTTP request router benchmark and comparison.
- [go-json-benchmark](https://github.com/zerosnake0/go-json-benchmark) ⭐ 9 📅 2020-10-08 - Go JSON benchmark.
- [go-ml-benchmarks](https://github.com/nikolaydubina/go-ml-benchmarks) ⭐ 30 📅 2022-10-20 - benchmarks for machine learning inference in Go.
- [go-web-framework-benchmark](https://github.com/smallnest/go-web-framework-benchmark) ⭐ 1,992 📅 2024-01-30 - Go web framework benchmark.
- [go_serialization_benchmarks](https://github.com/alecthomas/go_serialization_benchmarks) ⭐ 1,518 📅 2024-01-14 - Benchmarks of Go serialization methods.
- [gocostmodel](https://github.com/PuerkitoBio/gocostmodel) ⭐ 61 📅 2021-05-19 - Benchmarks of common basic operations for the Go language.
- [golang-sql-benchmark](https://github.com/tyler-smith/golang-sql-benchmark) ⭐ 65 📅 2015-03-13 - Collection of benchmarks for popular Go database/SQL utilities.
- [gospeed](https://github.com/feyeleanor/GoSpeed) ⭐ 117 📅 2022-06-13 - Go micro-benchmarks for calculating the speed of language constructs.
- [kvbench](https://github.com/jimrobinson/kvbench) ⭐ 26 📅 2019-09-28 - Key/Value database benchmark.
- [skynet](https://github.com/atemerev/skynet) ⭐ 1,035 📅 2023-11-10 - Skynet 1M threads microbenchmark.
- [speedtest-resize](https://github.com/fawick/speedtest-resize) ⭐ 237 📅 2020-10-28 - Compare various Image resize algorithms for the Go language.

**[⬆ back to top](#contents)**

## Conferences

- [GoCon](https://gocon.connpass.com/) - Tokyo, Japan.
- [GoDays](https://www.godays.io/) - Berlin, Germany.
- [GoLab](https://golab.io/) - Florence, Italy.
- [GopherChina](https://gopherchina.org) - Shanghai, China.
- [GopherCon](https://www.gophercon.com/) - Denver, USA.
- [GopherCon Australia](https://gophercon.com.au/) - Sydney, Australia.
- [GopherCon Brazil](https://gopherconbr.org) - Florianópolis, Brazil.
- [GopherCon Europe](https://gophercon.eu/) - Berlin, Germany.
- [GopherCon India](https://gopherconindia.org/) - Pune, India.
- [GopherCon Israel](https://www.gophercon.org.il/) - Tel Aviv, Israel.
- [GopherCon Russia](https://www.gophercon-russia.ru) - Moscow, Russia.
- [GopherCon Singapore](https://gophercon.sg) - Mapletree Business City, Singapore.
- [GopherCon UK](https://www.gophercon.co.uk/) - London, UK.
- [GopherCon Vietnam](https://gophercon.vn/) - Ho Chi Minh City, Vietnam.
- [GoWest Conference](https://www.gowestconf.com/) - Lehi, USA.

**[⬆ back to top](#contents)**

## E-Books

### E-books for purchase

- [100 Go Mistakes: How to Avoid Them](https://www.manning.com/books/100-go-mistakes-how-to-avoid-them)
- [Black Hat Go](https://nostarch.com/blackhatgo) - Go programming for hackers and pentesters.
- [Build an Orchestrator in Go](https://www.manning.com/books/build-an-orchestrator-in-go)
- [Continuous Delivery in Go](https://www.manning.com/books/continuous-delivery-in-go) - This practical guide to continuous delivery shows you how to rapidly establish an automated pipeline that will improve your testing, code quality, and final product.
- [Creative DIY Microcontroller Project With TinyGo and WebAssembly](https://www.packtpub.com/product/creative-diy-microcontroller-projects-with-tinygo-and-webassembly/9781800560208) - An introduction into the TinyGo compiler with projects involving Arduino and WebAssembly.
- [Effective Go: Elegant, efficient, and testable code](https://www.manning.com/books/effective-go) - Unlock Go’s unique perspective on program design, and start writing simple, maintainable, and testable Go code.
- [For the Love of Go](https://bitfieldconsulting.com/books/love) - An introductory book for Go beginners.
- [Go in Practice, Second Edition](https://www.manning.com/books/go-in-practice-second-edition)  - Your practical guide on the ins-and-outs of Go development, covering the standard library and the most important tools from Go’s powerful ecosystem.
- [Know Go: Generics](https://bitfieldconsulting.com/books/generics) - A guide to understanding and using generics in Go.
- [Lets-Go](https://lets-go.alexedwards.net) - A step-by-step guide to creating fast, secure and maintanable web applications with Go.
- [Lets-Go-Further](https://lets-go-further.alexedwards.net) - Advanced patterns for building APIs and web applications in Go.
- [The Power of Go: Tests](https://bitfieldconsulting.com/books/tests) - A guide to testing in Go.
- [The Power of Go: Tools](https://bitfieldconsulting.com/books/tools) - A guide to writing command-line tools in Go.
- [Writing A Compiler In Go](https://compilerbook.com)
- [Writing An Interpreter In Go](https://interpreterbook.com) - Book that introduces dozens of techniques for writing idiomatic, expressive, and efficient Go code that avoids common pitfalls.

### Free e-books

- [A Go Developer's Notebook](https://leanpub.com/GoNotebook/read)
- [An Introduction to Programming in Go](http://www.golang-book.com/)
- [Build Web Application with Golang](https://astaxie.gitbooks.io/build-web-application-with-golang/content/en/)
- [Building Web Apps With Go](https://codegangsta.gitbooks.io/building-web-apps-with-go/content/)
- [Go 101](https://go101.org) - A book focusing on Go syntax/semantics and all kinds of details.
- [Go AST Book (Chinese)](https://github.com/chai2010/go-ast-book) ⭐ 5,238 📅 2023-07-21 - A book focusing on Go `go/*` packages.
- [Go Faster](https://leanpub.com/gofaster) - This book seeks to shorten your learning curve and help you become a proficient Go programmer, faster.
- [Go Succinctly](https://github.com/thedevsir/gosuccinctly) ⭐ 22 📅 2018-10-03 - in Persian.
- [Go with the domain](https://threedots.tech/go-with-the-domain/) - A book showing how to apply DDD, Clean Architecture, and CQRS by practical refactoring.
- [GoBooks](https://github.com/dariubs/GoBooks) ⭐ 15,807 📅 2024-03-02 - A curated list of Go books.
- [How To Code in Go eBook](https://www.digitalocean.com/community/books/how-to-code-in-go-ebook) - A 600 page introduction to Go aimed at first time developers.
- [Learning Go](https://www.miek.nl/downloads/Go/Learning-Go-latest.pdf)
- [Network Programming With Go](https://jan.newmarch.name/golang/)
- [Practical Go Lessons](https://www.practical-go-lessons.com/)
- [Spaceship Go A Journey to the Standard Library](https://blasrodri.github.io/spaceship-go-gh-pages/)
- [The Go Programming Language](https://www.gopl.io/)
- [The Golang Standard Library by Example (Chinese)](https://github.com/polaris1119/The-Golang-Standard-Library-by-Example) ⭐ 9,420 📅 2022-03-06
- [Web Application with Go the Anti-Textbook](https://github.com/thewhitetulip/web-dev-golang-anti-textbook/) ⭐ 3,157 📅 2021-10-19

**[⬆ back to top](#contents)**

## Gophers

- [Free Gophers Pack](https://github.com/MariaLetta/free-gophers-pack) ⭐ 3,284 📅 2022-11-27 - Gopher graphics pack by Maria Letta with illustrations and emotional characters in vector and raster.
- [Go-gopher-Vector](https://github.com/keygx/Go-gopher-Vector) ⭐ 67 📅 2018-03-04 - Go gopher Vector Data [.ai, .svg].
- [gopher-logos](https://github.com/GolangUA/gopher-logos) ⭐ 120 📅 2018-06-26 - adorable gopher logos.
- [gopher-stickers](https://github.com/tenntenn/gopher-stickers) ⭐ 579 📅 2016-08-23
- [gophericons](https://github.com/shalakhin/gophericons) ⭐ 610 📅 2018-03-23
- [gopherize.me](https://github.com/matryer/gopherize.me) - Gopherize yourself.
- [gophers](https://github.com/ashleymcnamara/gophers) ⭐ 2,895 📅 2019-04-12 - Gopher artworks by Ashley McNamara.
- [gophers](https://github.com/egonelbre/gophers) ⭐ 3,339 📅 2022-07-06 - Free gophers.
- [gophers](https://github.com/rogeralsing/gophers) ⭐ 58 📅 2020-08-06 - random gopher graphics.
- [gophers](https://github.com/sillecelik/go-gopher) ⭐ 137 📅 2022-11-30 - Gopher amigurumi toy pattern.
- [gophers](https://github.com/scraly/gophers) ⭐ 30 📅 2023-08-17 - Gophers by Aurélie Vache.

**[⬆ back to top](#contents)**

## Meetups

- [Basel Go Meetup](https://www.meetup.com/Basel-Go-Meetup/)
- [Belfast Gophers](https://www.meetup.com/Belfast-Gophers/)
- [Belgrade Golang Meetup](https://www.meetup.com/golang-serbia/)
- [Berlin Golang](https://www.meetup.com/golang-users-berlin/)
- [Brisbane Gophers](https://www.meetup.com/Brisbane-Golang-Meetup/)
- [Bärner Go Meetup - Berne, Switzerland](https://www.meetup.com/berner-go-meetup/)
- [Canberra Gophers](https://www.meetup.com/Canberra-Gophers/)
- [Go Language NYC](https://www.meetup.com/golanguagenewyork/)
- [Go London User Group](https://www.meetup.com/Go-London-User-Group/)
- [Go Remote Meetup](https://www.meetup.com/Go-Remote-Meetup/)
- [Go Toronto](https://www.meetup.com/go-toronto/)
- [Go User Group Atlanta](https://www.meetup.com/Go-Users-Group-Atlanta/)
- [GoBandung](https://www.meetup.com/GoBandung/)
- [GoBridge, San Francisco, CA](https://www.meetup.com/gobridge/)
- [GoCracow - Krakow, Poland](https://www.meetup.com/GoCracow/)
- [GoJakarta](https://www.meetup.com/GoJakarta/)
- [Golang Amsterdam](https://www.meetup.com/golang-amsterdam/)
- [Golang Argentina](https://www.meetup.com/Golang-Argentina/)
- [Golang Athens](https://www.meetup.com/Athens-Gophers/)
- [Golang Baltimore, MD](https://www.meetup.com/BaltimoreGolang/)
- [Golang Bangalore](https://www.meetup.com/Golang-Bangalore/)
- [Golang Belo Horizonte - Brazil](https://www.meetup.com/go-belo-horizonte/)
- [Golang Boston](https://www.meetup.com/bostongo/)
- [Golang Bulgaria](https://www.meetup.com/Golang-Bulgaria/)
- [Golang Cardiff, UK](https://www.meetup.com/Cardiff-Go-Meetup/)
- [Golang Copenhagen](https://www.meetup.com/Go-Cph/)
- [Golang Curitiba - Brazil](https://www.meetup.com/GolangCWB/)
- [Golang DC, Arlington, VA](https://www.meetup.com/Golang-DC/)
- [Golang Dorset, UK](https://www.meetup.com/golang-dorset/)
- [Golang Estonia](https://www.meetup.com/Golang-Estonia/)
- [Golang Gurgaon, India](https://www.meetup.com/Gurgaon-Go-Meetup/)
- [Golang Hamburg - Germany](https://www.meetup.com/Go-User-Group-Hamburg/)
- [Golang Israel](https://www.meetup.com/Go-Israel/)
- [Golang Kathmandu](https://www.meetup.com/Golang-Kathmandu/)
- [Golang Korea](https://www.meetup.com/GDG-Golang-Korea/)
- [Golang Lima - Peru](https://www.meetup.com/Golang-Peru/)
- [Golang Lyon](https://www.meetup.com/Golang-Lyon/)
- [Golang Marseille](https://www.meetup.com/fr-FR/Golang-Marseille/)
- [Golang Melbourne](https://www.meetup.com/golang-mel/)
- [Golang North East](https://www.meetup.com/en-AU/Golang-North-East/)
- [Golang Paris](https://www.meetup.com/Golang-Paris/)
- [Golang Poland](https://www.meetup.com/Golang-Poland/)
- [Golang Pune](https://www.meetup.com/Golang-Pune/)
- [Golang Rotterdam](https://www.meetup.com/golang-rotterdam/)
- [Golang Singapore](https://www.meetup.com/golangsg/)
- [Golang Stockholm](https://www.meetup.com/Go-Stockholm/)
- [Golang Sydney, AU](https://www.meetup.com/golang-syd/)
- [Golang São Paulo - Brazil](https://www.meetup.com/golangbr/)
- [Golang Taipei](https://www.meetup.com/golang-taipei-meetup/)
- [Golang Thessaloniki](https://www.meetup.com/thessaloniki-golang-meetup/)
- [Golang Turkey](https://kommunity.com/goturkiye)
- [Golang Vancouver, BC](https://www.meetup.com/golangvan/)
- [Golang Vienna, Austria](https://www.meetup.com/viennago/)
- [Golang Москва](https://www.meetup.com/Golang-Moscow/)
- [GoSF - San Francisco, CA](https://www.meetup.com/golangsf)
- [Istanbul Golang](https://www.meetup.com/Istanbul-Golang/)
- [Seattle Go Programmers](https://www.meetup.com/golang/)
- [Ukrainian Golang User Groups](https://www.meetup.com/uagolang/)
- [Utah Go User Group](https://www.meetup.com/utahgophers/)
- [Women Who Go - San Francisco, CA](https://www.meetup.com/Women-Who-Go/)
- [Zürich Gophers - Zurich, Switzerland](https://www.meetup.com/zurich-gophers/)

_Add the group of your city/country here (send **PR**)_

**[⬆ back to top](#contents)**

## Style Guides

- [bahlo/go-styleguide](https://github.com/bahlo/go-styleguide) ⭐ 1,468 📅 2022-12-27
- [CockroachDB](https://github.com/cockroachdb/cockroach/blob/master/docs/style.md)
- [GitLab](https://docs.gitlab.com/ee/development/go_guide/)
- [Google](https://google.github.io/styleguide/go/)
- [Hyperledger](https://github.com/hyperledger/fabric/blob/release-1.4/docs/source/style-guides/go-style.rst)
- [Magnetico](https://github.com/boramalper/magnetico/wiki/magnetico-Design-Specification)
- [Sourcegraph](https://docs.sourcegraph.com/dev/background-information/languages/go)
- [Thanos](https://thanos.io/tip/contributing/coding-style-guide.md/)
- [Trybe](https://github.com/betrybe/playbook-go/blob/main/README_EN.md)
- [Uber](https://github.com/uber-go/guide/blob/master/style.md)

**[⬆ back to top](#contents)**

## Social Media

### Twitter

- [@GoDiscussions](https://twitter.com/GoDiscussions)
- [@golang](https://twitter.com/golang)
- [@golang_news](https://twitter.com/golang_news)
- [@golangch](https://twitter.com/golangch)
- [@golangflow](https://twitter.com/golangflow)
- [@golangweekly](https://twitter.com/golangweekly)

**[⬆ back to top](#contents)**

### Reddit

- [r/golang](https://www.reddit.com/r/golang/)

**[⬆ back to top](#contents)**

## Websites

- [Awesome Go @LibHunt](https://go.libhunt.com) - Your go-to Go Toolbox.
- [Awesome Golang Workshops](https://github.com/amit-davidson/awesome-golang-workshops) ⭐ 495 📅 2021-07-07 - A curated list of awesome golang workshops.
- [Awesome Remote Job](https://github.com/lukasz-madon/awesome-remote-job) ⭐ 27,862 📅 2024-03-14 - Curated list of awesome remote jobs. A lot of them are looking for Go hackers.
- [awesome-awesomeness](https://github.com/bayandin/awesome-awesomeness) ⭐ 31,146 📅 2022-03-24 - List of other amazingly awesome lists.
- [awesome-go-extra](https://github.com/xwjdsh/awesome-go-extra) ⭐ 22 📅 2022-08-25 - Parse awesome-go README file and generate a new README file with repo info.
- [Code with Mukesh](https://codewithmukesh.com/blog/category/golang) - Software Engineer and Blogs @ codewithmukesh.com.
- [Coding Mystery](https://codingmystery.com) - Solve exciting escape-room-inspired programming challenges using Go.
- [CodinGame](https://www.codingame.com/) - Learn Go by solving interactive tasks using small games as practical examples.
- [Explore Go Libraries & Projects](https://kandi.openweaver.com/explore/go) - Discover & find a curated list of popular & new Go libraries, top authors, trending project kits, discussions, tutorials & learning resources on kandi.
- [Go Blog](https://blog.golang.org) - The official Go blog.
- [Go Code Club](https://www.youtube.com/watch?v=nvoIPQYdx9g&list=PLEcwzBXTPUE_YQR7R0BRtHBYJ0LN3Y0i3) - A group of Gophers read and discuss a different Go project every week.
- [Go Community on Hashnode](https://hashnode.com/n/go) - Community of Gophers on Hashnode.
- [Go Forum](https://forum.golangbridge.org) - Forum to discuss Go.
- [Go Projects](https://github.com/golang/go/wiki/Projects) - List of projects on the Go community wiki.
- [Go Proverbs](https://go-proverbs.github.io/) - Go Proverbs by Rob Pike.
- [Go Report Card](https://goreportcard.com) - A report card for your Go package.
- [go.dev](https://go.dev/) - A hub for Go developers.
- [gocryforhelp](https://github.com/ninedraft/gocryforhelp) ⭐ 41 📅 2017-09-23 - Collection of Go projects that needs help. Good place to start your open-source way in Go.
- [Golang Developer Jobs](https://golangjob.xyz) - Developer Jobs exclusively for Golang related Roles.
- [Golang Flow](https://golangflow.io) - Post Updates, News, Packages and more.
- [Golang News](https://golangnews.com) - Links and news about Go programming.
- [Golang Resources](https://golangresources.com) - A curation of the best articles, exercises, talks and videos to learn Go.
- [Golang Weekly](https://discu.eu/weekly/golang/) - Each monday projects, tutorials and articles about Go.
- [golang-graphics](https://github.com/mholt/golang-graphics) ⭐ 139 📅 2015-08-24 - Collection of Go images, graphics, and art.
- [golang-nuts](https://groups.google.com/forum/#!forum/golang-nuts) - Go mailing list.
- [Google Plus Community](https://plus.google.com/communities/114112804251407510571) - The Google+ community for #golang enthusiasts.
- [Gopher Community Chat](https://invite.slack.golangbridge.org) - Join Our New Slack Community For Gophers ([Understand how it came](https://blog.gopheracademy.com/gophers-slack-community/)).
- [Gophercises](https://gophercises.com/) - Free coding exercises for budding gophers.
- [json2go](https://m-zajac.github.io/json2go) - Advanced JSON to Go struct conversion - online tool.
- [justforfunc](https://www.youtube.com/c/justforfunc) - Youtube channel dedicated to Go programming language tips and tricks, hosted by Francesc Campoy [@francesc](https://twitter.com/francesc).
- [Learn Go Programming](https://blog.learngoprogramming.com) - Learn Go concepts with illustrations.
- [Made with Golang](https://madewithgolang.com/?ref=awesome-go)
- [pkg.go.dev](https://pkg.go.dev/) - Documentation for open source Go packages.
- [r/Golang](https://www.reddit.com/r/golang) - News about Go.
- [studygolang](https://studygolang.com) - The community of studygolang in China.
- [Trending Go repositories on GitHub today](https://github.com/trending?l=go) - Good place to find new Go libraries.
- [TutorialEdge - Golang](https://tutorialedge.net/course/golang/)

**[⬆ back to top](#contents)**

### Tutorials

- [50 Shades of Go](https://devs.cloudimmunity.com/gotchas-and-common-mistakes-in-go-golang/) - Traps, Gotchas, and Common Mistakes for New Golang Devs.
- [A Comprehensive Guide to Structured Logging in Go](https://betterstack.com/community/guides/logging/logging-in-go/) - Delve deep into the world of structured logging in Go with a specific focus on recently accepted slog proposal which aims to bring high performance structured logging with levels to the standard library.
- [A Guide to Golang E-Commerce](https://snipcart.com/blog/golang-ecommerce-ponzu-cms-demo?utm_term=golang-ecommerce-ponzu-cms-demo) - Building a Golang site for e-commerce (demo included).
- [A Tour of Go](https://tour.golang.org/) - Interactive tour of Go.
- [Build a Database in 1000 lines of code]( https://link.medium.com/O9YQlx89Htb) - Build a NoSQL Database From Zero in 1000 Lines of Code.
- [Build web application with Golang](https://github.com/astaxie/build-web-application-with-golang) ⭐ 42,790 📅 2022-09-10 - Golang ebook intro how to build a web app with golang.
- [Building and Testing a REST API in Go with Gorilla Mux and PostgreSQL](https://semaphoreci.com/community/tutorials/building-and-testing-a-rest-api-in-go-with-gorilla-mux-and-postgresql) - We’ll write an API with the help of the powerful Gorilla Mux.
- [Building Go Web Applications and Microservices Using Gin](https://semaphoreci.com/community/tutorials/building-go-web-applications-and-microservices-using-gin) - Get familiar with Gin and find out how it can help you reduce boilerplate code and build a request handling pipeline.
- [Caching Slow Database Queries](https://medium.com/@rocketlaunchr.cloud/caching-slow-database-queries-1085d308a0c9) - How to cache slow database queries.
- [Canceling MySQL](https://medium.com/@rocketlaunchr.cloud/canceling-mysql-in-go-827ed8f83b30) - How to cancel MySQL queries.
- [CodeCrafters Golang Track](https://app.codecrafters.io/tracks/go) - Achieve mastery in advanced Go by building your own Redis, Docker, Git, and SQLite. Featuring goroutines, systems programming, file I/O, and more.
- [Debugged.it Go patterns](https://github.com/haveyoudebuggedit/go-patterns) ⭐ 10 📅 2021-06-25 - Advanced Go patterns with ready-to-run examples.
- [Design Patterns in Go](https://github.com/shubhamzanwar/design-patterns) ⭐ 109 📅 2023-01-03 - Collection of programming design patterns implemented in Go.
- [Ethereum Development with Go](https://github.com/miguelmota/ethereum-development-with-go-book) ⭐ 1,679 📅 2022-11-19 - A little e-book on Ethereum Development with Go.
- [Games With Go](https://www.youtube.com/watch?v=9D4yH7e_ea8&list=PLDZujg-VgQlZUy1iCqBbe5faZLMkA3g2x) - A video series teaching programming and game development.
- [Go By Example](https://gobyexample.com/) - Hands-on introduction to Go using annotated example programs.
- [Go Cheat Sheet](https://github.com/a8m/go-lang-cheat-sheet) ⭐ 8,074 📅 2022-08-27 - Go's reference card.
- [Go database/sql tutorial](http://go-database-sql.org/) - Introduction to database/sql.
- [Go in 7 days](https://github.com/harrytran103/7_days_of_go) ⭐ 135 📅 2020-08-29 - Learn everything about Go in 7 days (from a Nodejs developer).
- [Go Language Tutorial](https://www.javatpoint.com/go-tutorial) - Learn Go language Tutorial.
- [Go Tutorial](https://www.tutorialspoint.com/go/index.htm) - Learn Go programming.
- [Go WebAssembly Tutorial - Building a Simple Calculator](https://tutorialedge.net/golang/go-webassembly-tutorial/)
- [go-clean-template](https://github.com/evrone/go-clean-template) ⭐ 5,864 📅 2023-02-08 - Clean Architecture template for Golang services.
- [go-patterns](https://github.com/tmrts/go-patterns) ⭐ 23,788 📅 2017-07-19 - Curated list of Go design patterns, recipes and idioms.
- [goapp](https://github.com/bnkamalesh/goapp) ⭐ 759 📅 2023-02-05 - An opinionated guideline to structure & develop a Go web application/service.
- [Golang for Node.js Developers](https://github.com/miguelmota/golang-for-nodejs-developers) ⭐ 4,485 📅 2022-11-19 - Examples of Golang compared to Node.js for learning.
- [Golang Tutorial Guide](https://www.freecodecamp.org/news/golang-tutorial-list-free-courses-learn-go-programming-language/) - A List of Free Courses to Learn the Go Programming Language.
- [Golangbot](https://golangbot.com/learn-golang-series/) - Tutorials to get started with programming in Go.
- [GopherCoding](https://gophercoding.com/) - Collection of code snippets and tutorials to help tackle every day issues.
- [GopherSnippets](https://gophersnippets.com/) - Code snippets with tests and testable examples for the Go programming language.
- [Gosamples](https://gosamples.dev/) - Collection of code snippets that let you solve everyday code problems.
- [Hackr.io](https://hackr.io/tutorials/learn-golang) - Learn Go from the best online golang tutorials submitted & voted by the golang programming community.
- [Hex Monscape](https://github.com/Haraj-backend/hex-monscape) ⭐ 49 📅 2023-07-26 - Getting started guidelines in writing maintainable code using Hexagonal Architecture.
- [How to Benchmark: dbq vs sqlx vs GORM](https://medium.com/@rocketlaunchr.cloud/how-to-benchmark-dbq-vs-sqlx-vs-gorm-e814caacecb5) - Learn how to benchmark in Go. As a case-study, we will benchmark dbq, sqlx and GORM.
- [How To Deploy a Go Web Application with Docker](https://semaphoreci.com/community/tutorials/how-to-deploy-a-go-web-application-with-docker) - Learn how to use Docker for Go development and how to build production Docker images.
- [How to Use Godog for Behavior-driven Development in Go](https://semaphoreci.com/community/tutorials/how-to-use-godog-for-behavior-driven-development-in-go) - Get started with Godog — a Behavior-driven development framework for building and testing Go applications.
- [Learn Go with 1000+ Exercises](https://github.com/inancgumus/learngo) ⭐ 18,257 📅 2024-02-18 - Learn Go with thousands of examples, exercises, and quizzes.
- [Learn Go with TDD](https://github.com/quii/learn-go-with-tests) ⭐ 21,066 📅 2024-03-20 - Learn Go with test-driven development.
- [Learning Go by examples](https://dev.to/aurelievache/learning-go-by-examples-introduction-448n) - Series of articles in order to learn Golang language by concrete applications as example.
- [Microservices with Go](https://www.youtube.com/playlist?list=PLmD8u-IFdreyh6EUfevBcbiuCKzFk0EW_) - Dive deep into building microservices using Go, including gRPC.
- [package main](https://www.youtube.com/packagemain) - YouTube channel about Programming in Go.
- [Programming with Google Go](https://www.coursera.org/specializations/google-golang) - Coursera Specialization to learn about Go from scratch.
- [Saving a Third of Our Memory by Re-ordering Go Struct Fields](https://qvault.io/golang/struct-field-ordering-memory/) - How inefficient field ordering in Go structs.
- [Scaling Go Applications](https://betterstack.com/community/guides/scaling-go/) - Everything about building, deploying and scaling Go applications in production.
- [The world’s easiest introduction to WebAssembly with Golang](https://medium.com/@martinolsansky/webassembly-with-golang-is-fun-b243c0e34f02)
- [Understanding Go in a visual way](https://dev.to/aurelievache/series/26234) - Learn Go visually
- [W3basic Go Tutorials](https://www.w3basic.com/golang/) - W3Basic provides an in-depth tutorial and well-organized content to learn Golang programming.
- [Working with Go](https://github.com/mkaz/working-with-go) ⭐ 1,156 📅 2020-02-03 - Intro to go for experienced programmers.
- [Your basic Go](https://yourbasic.org/golang) - Huge collection of tutorials and how to's.

**[⬆ back to top](#contents)**

### Guided Learning

- [The Go Developer Roadmap](https://roadmap.sh/golang) - A visual roadmap that new Go developers can follow through to help them learn Go.
- [The Go Learning Path](https://tutorialedge.net/paths/golang/) - A guided learning path containing a mix of free and premium resources.

**[⬆ back to top](#contents)**
