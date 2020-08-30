:heavy_check_mark: == **added to live website at [fediverse.party](https://fediverse.party)**

:tada: == **projects that have successfully federated with this protocol**

:black_nib: == newly added to this page (added, not altered. Only @light to remove please)

*Note*: Tools with open protocol issue (not yet implemented), not fully open sourced code, no documentation at all, or alpha state with development inactive for several months, not added for now.

## List of projects that have an ActivityPub implementation or are committed to one

*Note*: Most of these projects include both a back-end and a web client, but this list can also include projects that are only a back-end. Projects that are only a web app, for use with an existing back-end, will go on the [client watchlist ](https://git.feneas.org/feneas/fediverse/wikis/watchlist-for-client-apps).

#### Contents

* [Social networks, Microblog Apps](#social-networks-microblog-apps)
* [Blog, Publishing, and Reading Apps](#blog-publishing-and-reading-apps)
* [Link-sharing, Forum, and Group Apps](#link-sharing-forum-and-group-apps)
* [Media-hosting Apps](#media-hosting-apps)
* [Events and Meetups](#events-and-meetups)
* [Files, Contacts, and Calendar Syncing Apps](#files-contacts-and-calendar-syncing-apps)
* [Open data](#open-data)
* [Developer Tools](#developer-tools)
* [Extentions](#extentions)
* [Relays reference](#relays-reference)
* [Not yet Categorized](#not-yet-categorized)
* [Is it Alive?](#is-it-alive)
* [It's Dead, Jim](#its-dead-jim)

#### Social networks, Microblog Apps

* :heavy_check_mark: **[Aardwolf](https://github.com/Aardwolf-Social/aardwolf)** ([site](https://aardwolf.social)): Facebook-like social network connecting communities across the web `AGPL-3.0, Rust`

* :heavy_check_mark: **[ActorsCafé](https://github.com/Xeltica/actorscafe)**: Microblogging server written in C# `AGPL-3.0, C#`

* :heavy_check_mark: **[Dolphin](https://github.com/syuilo/dolphin)**: Lightweight ActivityPub Server optimized for single-user. A fork and sister project of Misskey `AGPL-3.0, Javascript`

* :tada: :heavy_check_mark: **[Epicyon](https://code.freedombone.net/bashrc/epicyon)** ([site](https://epicyon.net)): ActivityPub server implementing S2S and C2S protocols, suitable for single board computers. Includes features such as moderation tools, post expiry, content warnings, and image descriptions `AGPL-3.0, Python`

* :heavy_check_mark: **[FlockingBird](https://git.webschuur.com/flockingbird)** ([site](https://flockingbird.social), [Fedi account](https://bitcoinhackers.org/@berkes/104601907980186487)): social network for professionals (WIP)

* :tada: :heavy_check_mark: **[Friendica](https://github.com/friendica/friendica)** ([site](https://friendi.ca)): Personal network that helps to keep in contact with friends. Interface and functionality include common features of a mainstream social network `AGPL-3.0, PHP`

* :heavy_check_mark: **[GNU social](https://notabug.org/diogo/gnu-social)** ([site](https://gnusocial.network)): Microblogging server with multiple plugins `AGPL-3.0, PHP`

* :tada: :heavy_check_mark: **[groundpolis](https://github.com/xeltica/groundpolis)**: A microblogging service forked from Misskey `AGPL-3.0, Typescript`

* :tada: :heavy_check_mark: **[Honk](https://humungus.tedunangst.com/r/honk)** ([Fedi account](https://honk.tedunangst.com/u/tedu)): ActivityPub server with minimal setup and support costs `ISC, Go`

* :heavy_check_mark: **[Kanzaki](https://github.com/KnzkDev/kanzaki)**: A Mastodon-compatible, ActivityPub-speaking server in OCaml `AGPL-3.0, OCaml`

* :heavy_check_mark: **[Kibou](https://git.cybre.club/kibouproject/kibou)**: Lightweight social networking server `AGPL-3.0, Rust`

* :tada: :heavy_check_mark: **[Kroeg](https://puckipedia.com/kroeg)** ([site](https://puckipedia.com/kroeg)): Generic ActivityPub server, with a focus on microblogging style activities `- , Rust` 

* :tada: :heavy_check_mark: **[Mastodon](https://github.com/tootsuite/mastodon)** ([site](https://joinmastodon.org)): Epic microblogging network with many features and multiple interface layouts to choose from `AGPL-3.0, Ruby`

* :tada: :heavy_check_mark: **[microblog.pub](https://github.com/tsileo/microblog.pub)** ([site](http://microblog.pub)): Self-hosted, single-user, ActivityPub powered microblog. Like Pubgate, uses [little-boxes AP library](https://github.com/tsileo/little-boxes) `AGPL-3.0, Python`

* :heavy_check_mark: **[microstatus](https://github.com/Arkanosis/microstatus)**: Lightweight Mastodon and GNU Social-compatible server implementation `ISC, Rust`

* :tada: :heavy_check_mark: **[Misskey](https://joinmisskey.github.io)** ([site](https://joinmisskey.github.io)): Sophisticated microblogging with personality. Provides many additional features like calendar, emoji reactions, polls, games, and many other widgets `AGPL-3.0, Javascript`

* :black_nib: :heavy_check_mark: [**Mistpark 2020**](https://codeberg.org/zot/misty/) aka 'misty' ([site](https://zotlabs.com/misty), [Fedi account](https://z.macgirvin.com/channel/mike)) - A webserver app that supports AP and Zot protocols, fork of Zap `CC0-like, PHP`

* :tada: :heavy_check_mark: **[Pleroma](https://git.pleroma.social/pleroma)** ([site](https://pleroma.social)): Microblogging platform `AGPL-3.0, Elixir`

* **[pump.io](https://github.com/pump-io/pump.io/issues/1241)**: still considers adding ActivityPub

* :heavy_check_mark: **[Rustodon](https://github.com/rustodon/rustodon)**: Mastodon-compatible server `AGPL-3.0, Rust`

* :black_nib: **[Scuttlebutt](https://github.com/DanielMowitz/ssb_ap_bridge)** - currently working on a bridge between SSB and AP networks

* :tada: :heavy_check_mark: **[Smithereen](https://github.com/grishka/Smithereen)**: VKontakte-like social network, with friends, walls, photo albums and groups `Unlicense, Java`

* :tada: :heavy_check_mark: **[SocialHome](https://git.feneas.org/socialhome/socialhome)** ([site](https://socialhome.network)): Personal webpage with social networking functionality `AGPL-3.0, Python`

* :tada: :heavy_check_mark: **[Tavern](https://gitlab.com/ngerakines/tavern/-/tree/release-amber-ale)** ([Fedi account](https://mastodon.social/@ngerakines)): A minimalistic Activity Pub server. Think Mastodon, but smaller and with fewer features `Go, MIT`

* :tada: :heavy_check_mark: **[Zap](https://codeberg.org/zot/zap)** ([site](https://zotlabs.com/zap/), [Fedi account](https://z.macgirvin.com/channel/mike)): A webserver app that supports AP and Zot protocols `CC0-like, PHP`

#### Blog, Publishing, and Reading Apps

* :black_nib: **[Diffu](https://mockup.diffu.social)**: an attempt at a federated Tumblr/ Medium, aimed at hosting long form articles that easily and neatly embed other kinds of content from any fediverse platform (microblog posts, PixelFed images, PeerTube videos etc). Proposed by a French company called Befox, who attempted to crowdfund development (inspired perhaps by the success or PeerTube and Mobilizon), but didn't hit their target.

* :heavy_check_mark: **[Distbin](https://github.com/gobengo/distbin)** ([site](https://distbin.com)): Post bin `Apache-2.0, Typescript`

* :heavy_check_mark: **[Dokie.li](https://github.com/linkeddata/dokieli)** ([site](https://dokie.li)): Article authoring and formating `Apache-2.0, Javascript`

* :heavy_check_mark: **[FediBlog](https://framagit.org/DavidLibeau/FediBlog)** ([site](https://fedi.blog)): Fully customisable blog engine `GPL-3.0, PHP`

* :heavy_check_mark: :tada: [Bookwyrm](https://github.com/mouse-reeve/bookwyrm) ([site](http://fedireads-test.glitch.me)): A federated alternative to Goodreads `CC0-1.0, Python`

* :heavy_check_mark: **[Readlebee](https://gitlab.com/Alamantus/Readlebee)** ( [Fedi account](https://floss.social/@Readlebee)): An attempt to create a viable Goodreads alternative, book reading progress, lists, reviews, comments `AGPL-3.0, Javascript`

* :heavy_check_mark: **[Hubzilla](https://framagit.org/hubzilla)** ([site](https://hubzilla.org)): CMS with a range of groupware tools available as plug-ins `MIT, PHP` 

* **[Known](https://github.com/idno/Known/issues/1701)**: Still considers adding AP support

* :heavy_check_mark: **[Little Library](https://github.com/Alamantus/little-library)**: A digital give-a-book, take-a-book library for ebooks. `AGPL-3.0, Javascript`

* :black_nib: **[NoteIn](https://github.com/notein/NoteIn)**: No commits since October 2018

* :black_nib: **[picopub](https://github.com/transitracer/picopub)**: Created by the developer of Fontina as a "tiny, Mastodon-compatible blog"; no commits since February 2019

* :tada: :heavy_check_mark: **[Plume](https://github.com/Plume-org/Plume)** ([site](https://joinplu.me)): Blogging application `AGPL-3.0, Rust`

* :heavy_check_mark: **[Read.as](https://github.com/writeas/Read.as)** ([site](https://read.as)): Reading app by the devs of WriteFreely `AGPL-3.0, Go`

* :heavy_check_mark: **[Redaktor](https://redaktor.me)**: AP-powered CMS

* :heavy_check_mark: **[WordPress](https://git.feneas.org/feneas/fediverse/-/wikis/Wordpress-integration-with-Fediverse)** - [listed as a project on the-federation.info](https://the-federation.info/wordpress). [AP plug-in](https://wordpress.org/plugins/activitypub) by @pfefferle@mastodon.social, that allows users on AP apps to follow WP blogs, and comment on them, from an AP app.

* :tada: :heavy_check_mark: **[Write Freely](https://github.com/writeas/writefreely)** ([site](https://writefreely.org)): Blog software `AGPL-3.0, Go`

#### Link-sharing, Forum, and Group Apps

* :black_nib: **[Discourse](https://socialhub.activitypub.rocks/t/about-discourse/102)** - Forum software, still considers adding AP support

* :black_nib: **[Flarum](https://github.com/squeevee/flarum-ext-feddle)**: Experimental plugin for [Flarum](https://flarum.org/) forum software by [@squeevee](https://yiff.life/@squeevee/102496777538790361)

* :black_nib: **[FediQuest](https://shapegoal.org/matejlach/fediQ-server)** ([site](https://shapegoal.org)): A federated alternative to traditionally centralized question & answer platforms, such as Quora/StackOverflow. `GPL-3.0, Go`

* :heavy_check_mark: **[Lemmy](https://github.com/dessalines/lemmy)**: Link aggregator, by [@LemmyDev](https://mastodon.social/@LemmyDev/102106696961226378) `AGPL-3.0, Rust`

* :black_nib: **[Lobste.rs](https://github.com/lobsters/lobsters/issues/499)**: Existing Reddit replacement adding AP support

* :heavy_check_mark: **[Littr.me](https://github.com/mariusor/littr.go)** ([Fedi account](https://metalhead.club/@mariusor)): Link aggregator inspired by Reddit `MIT, Go`

* :black_nib: **[lotide](https://git.sr.ht/~vpzom/lotide)**: A federated forum / link aggregator. `AGPL-3.0, Rust`

* :heavy_check_mark: **[MoonTree](https://github.com/Faleidel/moontreeproject)**: Link aggregator, a work in progress `MIT, Typescript`

* :black_nib: **[Pantheon](https://github.com/TGNThump/Pantheon)**: Platform for building communities, no commits since September 2019

* :heavy_check_mark: **[Smilodon](https://source.puri.sm/liberty/host/smilodon)**: the server by Purism used in LibreOne, not the abandoned Tuxcraft server or Pylodon client; a complementary fork of Mastodon, focusing on opt-in public spaces `AGPL-3.0, Ruby`

#### Media-hosting Apps

* :heavy_check_mark: **[Anfora](https://github.com/anforaProject/anfora)** ([site](https://anfora.app)): (formerly Zinat) Image sharing `AGPL-3.0, Python`

* :tada: :heavy_check_mark: **[FunkWhale](https://dev.funkwhale.audio/funkwhale/funkwhale)** ([site](https://funkwhale.audio)): Music streaming `AGPL-3.0, Python`

* :black_nib: **[Marmota](https://gitlab.com/Nefix/marmota/issues?label_name=ActivityPub)**: Streaming service like Spotify, no commits since March 2019; 

* **[PeerPx](https://github.com/peerpx)**: Social network for photographers (alternative to 500px / Flickr); no commits since October 2018

* :tada: :heavy_check_mark: **[PeerTube](https://github.com/Chocobozzz/PeerTube)** ([site](http://joinpeertube.org)): Video-hosting site using WebTorrent `AGPL-3.0, Typescript`

* :tada: :heavy_check_mark: **[PixelFed](https://github.com/dansup/pixelfed)** ([site](https://pixelfed.org)): Image sharing `AGPL-3.0, PHP`

* :heavy_check_mark: **[Pubcast](https://github.com/pubcast/pubcast)** ([site](https://pubcast.pub)): Podcasting platform `MPL-2.0, Go`

* **[snap.as](https://github.com/snapas)**: Photo sharing
 
#### Events and Meetups

* :tada: :heavy_check_mark: **[Gancio](https://framagit.org/les/gancio)** ([site](https://gancio.org)): Shared agenda for local communities; demo [site](https://demo.gancio.org) `AGPL-3.0, Javascript`

* :heavy_check_mark: **[Gath](https://github.com/lowercasename/gathio)**: Public events with no registration required, an instance connected with the friend.camp Mastodon instance is up at: http://events.friend.camp `GPL-3.0, Javascript`

* **[GetTogether](https://github.com/GetTogetherComm/GetTogether/issues/60)** - Still considering adding AP support

* :heavy_check_mark: **[Mobilizon](https://framagit.org/framasoft/mobilizon)** ([site](https://joinmobilizon.org/en), [Fedi account](https://framapiaf.org/@mobilizon)): Aims to be more than a Meetup clone `AGPL-3.0, Elixir`

Friendica (see above) has an [events engine that federates events over AP](https://socialhub.activitypub.rocks/t/activitypub-at-36c3-the-decentral-assembly-and-fediverse-party/402/5) and is looking to test interop with other AP events apps. [NextCloud federated events](https://github.com/nextcloud/calendar/pull/878) are in the works but this [may or may not be AP-compatible](https://github.com/nextcloud/server/issues/1440).

#### Files, Contacts, and Calendar Syncing Apps

* :tada: :heavy_check_mark: **[NextCloud-Social](https://github.com/nextcloud/social)** ([site](https://apps.nextcloud.com/apps/social)): Social networking app for NextCloud `AGPL-3.0, PHP`

* **[MoodleNet](https://gitlab.com/moodlenet)**: [Social client for Moodle](https://moodle.com/moodlenet) LMS (Learning Management System) aimed at helping teachers collaboratively collate and curate sets of OER (Open Educational Resources)

#### Open data

* :heavy_check_mark: **[OLKi](https://framagit.org/synalp/olki/olki/-/wikis/ActivityPub-dialect-documentation)** ([site](https://olki.loria.fr/platform), [Fedi account](https://mastodon.etalab.gouv.fr/@scifed)): A self-hosted linguistic corpora exchange platform that aims to be a simple gateway to the Fediverse for scientific interaction `AGPL-3.0, Python`

#### Developer Tools

* :heavy_check_mark: **[ActivityPubMock](https://gitlab.com/evanp/activitypub-mock)**: A mock ActivityPub server to use in testing code `Apache-2.0, Javascript`

* :heavy_check_mark: **[ActivityPHP](https://landrok.github.io/activitypub)** ([Fedi account](https://cybre.space/@landrok)): Library for AP in PHP `MIT, PHP`

* :heavy_check_mark: **[BridgyFed](https://github.com/snarfed/bridgy-fed)** ([site](https://fed.brid.gy)): Bridge to the IndieWeb `CC-0, Python`

* :heavy_check_mark: **[CommonsPub](https://gitlab.com/OpenCoop/CommonsPub)** ([site](http://commonspub.org)): A fork of Pleroma intended to provide a UX that supports economic transactions and coordination `AGPL-3.0, Elixir`

* :black_nib: **[Drupal plugin](https://github.com/swentel/activitypub)** by [@swentel](https://github.com/swentel)

* :heavy_check_mark: **[Express ActivityPub](https://github.com/dariusk/express-activitypub)**: Reference implementation using Express.js `MIT, Express` 

* :heavy_check_mark: **[feed2toot](https://gitlab.com/chaica/feed2toot)**: Feed to Mastodon, [using the Mastodon client<>server API, not AP](https://gitlab.com/chaica/feed2toot/issues/35#note_289027030) `MIT, Python`

* :heavy_check_mark: **[astreams](https://github.com/MatejLach/astreams)** ([Fedi account](https://social.matej-lach.me/@MatejLach)): "ActivityStreams 2.0 encoding/decoding for Go" for use with [fediQuest](https://shapegoal.org) `AGPL-3.0, Go`

* :heavy_check_mark: **[ForgeFed](https://notabug.org/peers/forgefed)** (formerly GitPub) ([site](https://forgefed.peers.community), [Fedi account](https://floss.social/@forgefed)): A set of extensions to AP for federation between code forges (Git hosting sites like GitLab, Gogs, Gitea etc) `CC-1.0`

* :black_nib: **[go-ap](https://github.com/go-ap)** ([Fedi account](https://metalhead.club/@mariusor)): Libraries for using ActivityPub in the Go language. `MIT, Go`

* :heavy_check_mark: **[go-fed](https://github.com/go-fed/activity)**: ActivityStreams & ActivityPub in golang `BSD-3-clause, Go`

* :heavy_check_mark: **[LitePub](https://github.com/litepub/litepub)** ([site](https://litepub.social/litepub)): A set of extensions to AP, being developed by devs from Pleroma and Mastodon

* :heavy_check_mark: **[p3k](https://indieweb.org/p3k)**: A set of tools indie.web sites can use to support AP [servers](https://the-federation.info/p3k) `MIT, PHP`

* :heavy_check_mark: **[ActivityPub-PHP](https://github.com/pterotype-project/activitypub-php)** ([Fedi account](https://mastodon.technology/@jdormit)): A PHP implementation of the ActivityPub protocol, used in Perotype plugin  `MIT, PHP`

* :heavy_check_mark: **[pubgate](https://github.com/autogestion/pubgate)**:  "Asyncronous Lightweight ActivityPub API based on little-boxes. Implements both the client-to-server API and the federated server-to-server API. Compatible with Mastodon, Pleroma and microblog.pub" `BSD-3-clause, Python`

* **[Pubstrate](https://gitlab.com/dustyweb/pubstrate)**: Experimental AP implementation written in GNU Guile, no commits since November 2017

* :heavy_check_mark: **[RSS-to-ActivityPub Converter](https://github.com/dariusk/rss-to-activitypub)**: RSS to AP converter `MIT, Javascript`

* :heavy_check_mark: [**Spritely**](https://gitlab.com/spritely) ([Fedi account](https://octodon.social/@cwebber)): Research space for a next-gen distributed social network written in Racket and consisting of multiple projects. Research conducted by AP specification writer Christopher Lemmer Webber. `Apache-2.0, Racket` 

* **[tags.pub](https://github.com/w3c/activitypub/issues/281)**: AP implementation testing tool?

* :black_nib: **[XWiki](https://github.com/xwiki)** ([site](https://www.xwiki.org), [Fedi account](https://social.weho.st/@XWiki)): A text-based collaboration platform. Stared to [implement](https://forum.xwiki.org/t/new-application-activitypub/6186) AP support. The XWiki team are the creators of [Cryptpad](cryptpad.fr)

#### Extentions

* :tada: :heavy_check_mark: **[Guppe](https://github.com/wmurphyrd/guppe)** ([site](https://gup.pe)): By [@datatitian](https://social.coop/@datatitian/102837577105371476), adds "groups" support as group-type actors `GPL-3.0, Javascript`

#### Relays [reference](https://github.com/distributopia/fediverse-relays)

* :heavy_check_mark: **[Activity relay](https://git.pleroma.social/pleroma/relay)** `AGPL-3.0, Python`

* :heavy_check_mark: **[Pub relay](https://source.joinmastodon.org/mastodon/pub-relay)** `AGPL-3.0, Crystal`

* :heavy_check_mark: **[Seattle relay](https://gitlab.com/jankysolutions/social.seattle.wa.us/relay)** `-, Python`

#### Not yet Categorized

* :black_nib: **[Agora](https://github.com/scenaristeur/agora)**: [Home page](https://scenaristeur.github.io/agora/), developed by [@spoggy@mstdn.fr](https://mstdn.fr/@spoggy) , '[license?, js/node lithtml/webcomponents](https://mstdn.fr/@spoggy/104043279616873128)'

* :heavy_check_mark: **[CPub](https://gitlab.com/openengiadina/cpub)**: a semantic web server, part of the [openEngiadina](https://openengiadina.net) project `AGPL-3.0, Elixir`

* :black_nib: **[Hash2Pub](https://socialhub.activitypub.rocks/t/about-hash2pub/543)**: A fully-decentralised relay for global hashtag federation. [White paper](https://git.orlives.de/schmittlauch/paper_hashtag_federation). No source code available yet.

* :black_nib: **[Kepi](https://gitlab.com/marnanel/chapeau) (formerly Chapeau?)**: "daemon in Django". `GPL-2.0, Python`

* :black_nib: **[Life-Server](https://github.com/interop-alliance/life-server)**: [Homepage](https://permanent.cloud/apps/life-server), "A decentralized personal data server inspired by MIT's Solid Project ... Since node-solid-server (NSS) is being deprecated in favor of inrupt/pod-server, this repo intends to be another compatible implementation", `MIT, Nodejs`

* :heavy_check_mark: **[PherePhone](https://github.com/writeas/pherephone)**: "A server that reblogs all the statuses of certain actors". `AGPL-3.0, Go` 

* :heavy_check_mark: **[SemApps](http://www.virtual-assembly.org/semapps-2/)** ([site](http://semapps.org/?PagePrincipale&lang=en)): Software toolkit for easy deployment and configuration of semantic information systems. `Apache-2.0, Javascript`

* :heavy_check_mark: **[SkoHub](https://github.com/hbz/skohub-pubsub)** ([site](https://skohub.io)): A novel approach for finding content on the web. SkoHub extends Knowledge Organization Systems (KOS) to create a publication / subscription infrastructure for Open Educational Resources. `Apache-2.0, Javscript`

* :black_nib: **[un chapeau](https://gitlab.com/marnanel/un_chapeau/-/issues/17)**: Server for the Mastodon protocol, implemented in Django. `AGPl-3.0, Python`

* :heavy_check_mark: **[RavenVale](https://git.lubar.me/lubar-local/ravenvale)**: federating GuildWars2 website `-, Go`

* **[Learn Awesome](https://github.com/learn-awesome/learn)**: Open-source equivalent review aggregation site. Think GoodReads, but generalized to all learning resources organized by topics, formats and difficulty `AGPL-3.0, Ruby`

* :black_nib: **[castling.club](https://github.com/stephank/castling.club)** ([site](https://castling.club/), [Fedi account](https://mastodon.social/@kosinus)): Challenge someone to a game of chess using toots. `MIT, Typescript`

#### Is it Alive?

Projects that seem dormant and may be dead, but may also be doing dev quietly in private, or have moved to a new code forge without leaving a forwarding address, etc. Any information that could help us clarify whether these projects are still alive would be much appreciated.

* **[Anancus](https://gitlab.com/tuxether/anancus)**: By [@tuxether](https://floss.social/@tuxether), Link aggregator, [discontinued](https://gitlab.com/tuxether/anancus/issues/2)?

* :heavy_check_mark: **[Prismo](https://gitlab.com/prismosuite/prismo)** ([Fedi account](https://mastodon.social/@prismo)): Link aggregator `AGPL-3.0, Ruby`

* :heavy_check_mark: **[reel2bits](https://github.com/rhaamo/reel2bits)** ([site](https://reel2bits.org)): Music and podcast hosting, `AGPL-3.0, Python`

#### It's Dead, Jim

Projects that are officially abandoned by the maintainers or with no signs of life on their code repo or any other official channels for more than a year. Listed on this watchlist just in case anyone doesn't realize they're dead, and thinks we just didn't know about them. Also in case a project is orphaned, then reactivated by a new developer.

* [Acorde](https://github.com/polymerwitch/Acorde) - federated social music platform. Almost a year has passed since the initial commit.

* [ActivityPub.jl](https://github.com/Matt5sean3/ActivityPub.jl) - AP support in the Julia language by [@Matt5sean3](https://rva.party/@Matt5sean3), no commits since August, 2018. Project is [missing, presumed dead](https://github.com/Matt5sean3/ActivityPub.jl/issues/1).

* [Calendar-social](https://gitea.polonkai.eu/gergely/calendar-social/) - was definitely planning to [implement AP](https://gitea.polonkai.eu/gergely/calendar-social/issues/122). Missing, [presumed discontinued](https://gitea.polonkai.eu/gergely/calendar-social/issues/123)

* [CloutStream](https://web.archive.org/web/20180808152307/http://cloutstream.com/) - proposed by [@mwpdx](https://mstdn.io/@mwpdx/100591379202470027) as a federated replacement for LinkedIn. Both @cloutstream and @mwpdx Mastodon.social accounts appears to have been removed from the server, all the project tools appear to be down, or removed from the host. 

* [FedEvent](https://github.com/shiburizu/fedevent): A prototype for federating event information

* [Fontina](https://github.com/beta-phenylethylamine/fontina) - proposed as a photo-sharing social media network. GH repo has gone read-only, and now says "dead project".

* [GangGo](https://git.feneas.org/ganggo/federation/issues/17)  - Seems to have settled on using [Go-Fed for AP federation](https://git.feneas.org/ganggo/activity). Developer has suspended development for the foreseeable future.

* [Indienet](https://source.ind.ie/indienet) - [homepage](https://web.archive.org/web/20190507034117/https://indienet.info/) - abandoned in favour of [Tincan development](https://small-tech.org/research-and-development/).

* **[Kitsune](https://github.com/valerauko/kitsune)**: early alpha; no commits since November 2018; homepage down

* [Numa](https://github.com/numaverse/numaverse-gateway/issues/3) - built on Ethereum blockchain but intended to federate with AP. No commits since April 2018. No reply on issue about AP compatibility testing from May 8. Homepage now a spam site.

* [Osada](https://framagit.org/zot/osada) - Osada was a full featured social network application running under the ActivityPub protocol. It also communicated with and inter-operated with servers on the Zot6 network. Abandoned by the developers in March 2019 (**Update**: Recent activity Aug 2020, moved to [Codeberg](https://codeberg.org/zot/osada)).

* [Places.pub](https://github.com/w3c/activitypub/issues/282): AP implementation testing tool?

* [Pylodon](https://github.com/rowanlupton/pylodon) - Flask-based (Python) ActivityPub server , [source code also on GitLab](https://gitlab.com/rowanlupton/pylodon), no updates on either repo for about a year, nor on their [Smilodon client app](https://github.com/rowanlupton/smilodon).

* [Quit.im](https://quit.im) - this was a photo-sharing web client for a GNU social server, rather than a completely separate app. It would become an AP implementation when the AP plug-in for GS is done, but it's been obsoleted by the release of PixelFed.

* [Smilodon](https://gitlab.com/tuxcrafting/smilodon) (server by Tuxcraft) - abandoned by developer "I'm now [working on Sminos](https://gitlab.com/tuxcrafting/sminos/issues/1) and so this will probably be 100% abandoned. There's not much to salvage, its code is cancer." Sminos appears to have never got beyond the initial commits.

## Sources

Aside from project homepages and issue trackers, and comments made on the fediverse, the [SocialWG has a list](https://www.w3.org/wiki/Socialwg/ActivityPub_network) of projects they hoped would implement ActivityPub and links to issues where it's discussed. Also, there is an [implementation report on ActivityPub.rocks](https://activitypub.rocks/implementation-report/). @Mayel from Social.coop created a [web spreadsheet of AP apps](https://ethercalc.org/fediverse-stacks) and their characteristics. More projects using AP are [profiled on We Distribute](http://wedistribute.org/) by Sean Tilley and his team. There are boards for discussing a range of [AP implementations on the SocialHub forum](https://socialhub.activitypub.rocks/c/software/14). [Alternative.to](https://alternativeto.net/list/5696/activitypub) has a list of AP servers and client apps. The [ActivityPub tag on GH](https://github.com/topics/activitypub) is also a way to discover projects experimenting with AP.