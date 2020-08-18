## Contents

- [Developer tools](#developer-tools)
  - [Libraries](#libraries)
  - [Plugins](#plugins)
  - [Bridges](#bridges)
  - [Utilities](#utilities)
  - [Testing](#testing)
- [Reference material](#reference-material)
  - [Protocol specifications](#protocol-specifications)
  - [API documentation](#api-documentation)
- [Tutorials](#tutorials)
  - [Getting started](#getting-started)
  - [ActivityPub server-to-server (S2S)](#activitypub-server-to-server-s2s)
  - [ActivityPub client-to-server (C2S)](#activitypub-server-to-server-s2s)
  - [WebFinger](#webfinger)
  - [Security](#security)
- [Research & Development](#research-development)
  - [Datashards](#datashards)
  - [Object capabilities](#object-capabilities)
  - [Federated authentication](#federated-authentication)
  - [Content addressing](#content-addressing)
  - [Peer-to-peer networking](peer-to-peer-networking)

## Developer tools

#### Libraries

* :heavy_check_mark: [**ActivityPhp**](https://github.com/landrok/activitypub) ([site](https://landrok.github.io/activitypub), [Fedi account](https://cybre.space/@landrok)): A PHP implementation of ActivityPub protocol based upon the ActivityStreams 2.0 data format. `MIT, PHP`

* :heavy_check_mark: [**ActivityPub-PHP**](https://github.com/pterotype-project/activitypub-php) ([Fedi account](https://mastodon.technology/@jdormit)): A PHP implementation of the ActivityPub protocol (used in Pterotype plugin).  `MIT, PHP`

* :black_nib: [**activityPub4j**](https://github.com/msummers/activityPub4j): W3C ActivityPub and ActivityStreams implementation in Java using Spring Boot. `?, Java` (no license, see: [issue](https://github.com/msummers/activityPub4j/issues/1))

* :black_nib: [ActivityStreams](https://github.com/OpenSocial/activitystreams): Full ActivityStreams 1.0 and 2.0 reference implementation in Java. `Apache-2.0, Java`

* :heavy_check_mark: [**CommonsPub**](https://gitlab.com/CommonsPub) ([site](http://commonspub.org)): Building blocks for creating multifunctional federated networks with ActivityPub. `AGPL-3.0, Elixir`

* :heavy_check_mark: [**Express ActivityPub**](https://github.com/dariusk/express-activitypub): A very simple reference implementation of an ActivityPub server using Express.js. `MIT, Javascript`

* :heavy_check_mark: [**astreams**](https://github.com/MatejLach/astreams) ([Fedi account](https://social.matej-lach.me/@MatejLach)): A hand-crafted implementation of the Activity Streams 2.0 specification in Go, especially suitable for projects implementing ActivityPub. `AGPL-3.0, Go`

* :black_nib: [**Golang ActivityPub**](https://github.com/go-ap) ([Fedi account](https://metalhead.club/@mariusor)): Libraries for using ActivityPub in the Go language. `MIT, Go`

* :heavy_check_mark: [**go-fed activity**](https://github.com/go-fed/activity) ([site](https://go-fed.org), [Fedi account](https://mastodon.technology/@cj)): Full ActivityStreams & ActivityPub implementation in Golang. Extensions can be easily added by design-time code generation from JSON-LD schema's (also supports [ForgeFed](https://forgefed.peers.community) this way, by default). `BSD-3-clause, Go`

* :black_nib: [**go-fed apcore**](https://github.com/go-fed/apcore)** ([site](https://go-fed.org), [Fedi account](https://mastodon.technology/@cj)): A powerful single server ActivityPub framework for performant Fediverse applications. `AGPL-3.0, Go`

* :heavy_check_mark: [**pubgate**](https://github.com/autogestion/pubgate):  Asyncronous lightweight ActivityPub API / CMS that implements both client-to-server and server-to-server APIs. Compatible with Mastodon, Pixelfed, Pleroma and microblog.pub `BSD-3-clause, Python`

* [**Pubstrate](https://gitlab.com/dustyweb/pubstrate): ActivityStreams and ActivityPub library implementation for GNU Guile. Includes a full ActivityStreams library and most of an ActivityPub implementation. `GPL-3.0, Guile`

* [**Spritely**](https://gitlab.com/spritely) ([Fedi account](https://octodon.social/@cwebber)): Research space for a next-gen distributed social network written in Racket and consisting of multiple projects. Research conducted by AP specification writer Christopher Lemmer Webber. `Apache-2.0, Racket` 

#### Plugins

* :black_nib: [**Drupal integration**](https://github.com/swentel/activitypub) ([Lead dev](https://github.com/swentel)): ActivityPub integration for Drupal 8 `?, PHP` (no license, see: [issue](https://github.com/swentel/activitypub/issues/26))

* :black_nib: [**XWiki Extension for ActivityPub**](https://github.com/xwiki-contrib/application-activitypub) ([site](https://extensions.xwiki.org/xwiki/bin/view/Extension/ActivityPub%20Application/), [Fedi account](https://social.weho.st/@XWiki)): An implementation of the ActivityPub protocol for XWiki (see [forum discussion](https://forum.xwiki.org/t/new-application-activitypub/6186)). `LGPL-2.1, Java`

#### Bridges

* :heavy_check_mark: [**BridgyFed**](https://github.com/snarfed/bridgy-fed) ([site](https://fed.brid.gy)): Bridges the IndieWeb to federated social networks: ActivityPub, OStatus, etc. `?, Python` (no license, see: [issue](https://github.com/snarfed/bridgy-fed/issues/67))

* :heavy_check_mark: [**feed2toot**](https://gitlab.com/chaica/feed2toot): Parses RSS feeds, identifies new posts and posts them on the Mastodon social network ([using the Mastodon API]((https://gitlab.com/chaica/feed2toot/issues/35#note_289027030))). `MIT, Python`

* :heavy_check_mark: [**RSS-to-ActivityPub Converter**](https://github.com/dariusk/rss-to-activitypub): Convert any RSS feed to an ActivityPub actor that can be followed by users on ActivityPub-compliant social networks like Mastodon. `MIT, Javascript`

#### Utilities

* [**tags-pub**](https://gitlab.com/evanp/tags-pub): Provides hashtag objects on the ActivityPub network. `Apache-2.0, Javascript`

#### Testing

* :heavy_check_mark: [**activitypub-mock**](https://gitlab.com/evanp/activitypub-mock): A mock ActivityPub server to use in testing code `Apache-2.0, Javascript`

## Reference material

#### Protocol specifications

* [**ForgeFed**](https://notabug.org/peers/forgefed), formerly GitPub ([site](https://forgefed.peers.community), [Fedi account](https://floss.social/@forgefed)): A set of extensions to ActivityPub for federation between code forges (i.e. git hosting sites like GitLab, Gogs, Gitea, etc. Reference implementation is [Vervis](https://dev.angeley.es/s/fr33domlover/p/vervis)). `CC0-1.0`

* [**LitePub**](https://github.com/litepub/litepub) ([site](https://litepub.social/litepub), [Fedi account](https://pleroma.site/users/kaniini)): A set of extensions to AP, being developed by devs from Pleroma and Mastodon (status: for the most part litepub group folded back into SocialCG, see: [issue](https://github.com/litepub/litepub/issues/6))

#### API documentation

## Tutorials

#### Getting started

#### ActivityPub server-to-server (S2S)

#### ActivityPub client-to-server (C2S)

#### WebFinger

#### Security

#### NodeInfo

## Research & Development

#### Datashards

#### Object capabilities

#### Federated authentication

#### Content addressing

#### Peer-to-peer networking