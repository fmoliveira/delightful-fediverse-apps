:heavy_check_mark: == **added to live website**

:tada: == **projects that have successfully federated with this protocol**

:black_nib: == newly added to this page (added, not altered. Only @lostinlight to remove please)

*Note*: Tools with open protocol issue (not yet implemented), not fully open sourced code, no documentation at all, or alpha state with development inactive for several months, not added for now.

## List of projects that have an ActivityPub implementation or are committed to one

*Note*: This list began in issue https://gitlab.com/fediverse/fediverse.gitlab.io/issues/8. Most of these projects include both a back-end and a web client, but this list can also include projects that are only a back-end. Projects that are only a web app, for use with an existing back-end, will go on the [client watchlist ](https://gitlab.com/fediverse/fediverse.gitlab.io/wikis/watchlist-for-client-apps).

#### Social networks, Microblog Apps

* :heavy_check_mark: [Aardwolf](https://github.com/Aardwolf-Social/aardwolf) - aims to create a FB-a-like in Rust. Still in alpha, Web demo promised soon.

* :tada: :heavy_check_mark: [Friendica](https://friendi.ca/) - [AP support was rolled out in the 2019.01 release](https://friendi.ca/2019/01/21/friendica-2019-01-released/).

* :tada: :heavy_check_mark: [GangGo](https://git.feneas.org/ganggo/federation/issues/17)  - Seems to have settled on using [Go-Fed for AP federation](https://git.feneas.org/ganggo/activity).

* :heavy_check_mark: [GNU social](https://git.gnu.io/gnu/gnu-social/issues/256) - AP support was done as a Summer of Code project, but not yet merged into mainline.

* [Kitsune](https://github.com/valerauko/kitsune) - in alpha

* :tada: [Kroeg](https://puckipedia.com/kroeg) - [current source repo](https://git.puckipedia.com/kroeg) seems active - [older GH repo](https://github.com/jfmcbrayer/Kroeg) with no activity for 2 years). 

* :tada: :heavy_check_mark: [Mastodon](https://joinmastodon.org)

* :tada: :heavy_check_mark: [microblog.pub](https://github.com/tsileo/microblog.pub) - single-user microblog server, "Getting closer to a stable release, it should be the "last" migration". Like Pubgate, uses [little-boxes AP library](https://github.com/tsileo/little-boxes)

* :heavy_check_mark: [microstatus](https://github.com/Arkanosis/microstatus) - Lightweight Mastodon- and GNU Social-compatible ActivityPub and OStatus server implementation, "still under active design and not yet ready for mainstream usage".

* :tada: :heavy_check_mark: [Misskey](https://joinmisskey.github.io/) - Japanese Ap server

* :tada: :heavy_check_mark: [Pleroma](https://pleroma.social/)

* [pump.io](https://github.com/pump-io/pump.io/issues/1241)

* :heavy_check_mark: [Rustodon](https://github.com/rustodon/rustodon)

* :heavy_check_mark: [SocialHome](https://git.feneas.org/socialhome/socialhome/issues/522) - currently working on adding AP support to their [Python federation library](https://git.feneas.org/jaywink/federation/issues/7)

* :heavy_check_mark: [Kibou](https://git.cybre.club/kibouproject/kibou) - highly customizable multi-protocol social networking server

#### Blog and Publishing Apps

* :heavy_check_mark: [Dokie.li](https://dokie.li)

* :heavy_check_mark: [FediBlog](https://framagit.org/DavidLibeau/FediBlog) - fully customisable blog engine

* :heavy_check_mark: [Huzbilla](https://project.hubzilla.org/) - federated CMS with a range of groupware tools available as plug-ins. Support AP with the [pubcrawl plug-in](https://framagit.org/hubzilla/addons/tree/master/pubcrawl).

* [Known](https://github.com/idno/Known/issues/1701)

* :black_nib: :tada: [Minds](https://gitlab.com/minds/engine/issues/183) - a centralized attempt at a FB replacement, incorporating short or long form posts, and live chat, as well as an internal token system (a bit like Reddit gold?). Have rolled out [AP support for following newsfeeds](https://gitlab.com/minds/engine/merge_requests/28).

* [picopub](https://github.com/transitracer/picopub) - created by the developer of Fontina as a "tiny, Mastodon-compatible blog"

* :heavy_check_mark: [Plume](https://github.com/Plume-org/Plume)

* :heavy_check_mark: [Read.as](https://github.com/writeas/Read.as) - a reading app 

* :heavy_check_mark: [WordPress](https://gitlab.com/fediverse/fediverse.gitlab.io/wikis/Wordpress-integration-with-Fediverse) - an [AP plug-in](https://wordpress.org/plugins/activitypub/) by @pfefferle@mastodon.social, that allows users on AP apps to follow WP blogs, was recently updated. See also [Pterotype](https://getpterotype.com/), which @pfefferle says is currently more feature complete. WordPress is now [listed as a project on the-federation.info](https://the-federation.info/wordpress).

* :heavy_check_mark: [Write Freely](https://writefreely.org)

* :black_nib: [NoteIn](https://github.com/notein/NoteIn) - alpha stage

#### Link-sharing Apps

* [Anancus](https://gitlab.com/tuxether/anancus)

* :heavy_check_mark: [Prismo](https://gitlab.com/mbajur/prismo)

* :heavy_check_mark: [Lemmy](https://github.com/dessalines/lemmy)

#### Media-hosting Apps

* :heavy_check_mark: [Anfora](https://github.com/anforaProject/anfora) (formerly Zinat) - image sharing

* :heavy_check_mark: [FunkWhale](https://medium.com/we-distribute/funkwhale-an-open-source-grooveshark-alternative-begins-activitypub-implementation-cbc10a412b20) - music streaming

* :black_nib: [Marmota](https://gitlab.com/Nefix/marmota/issues?label_name=ActivityPub) - service like Spotify or any music streaming service, initial commit; 

* [PeerPx](https://github.com/peerpx) - social network for photographers ("alternative to 500px / Flickr")

* :heavy_check_mark: [PeerTube](http://joinpeertube.org/) - video-hosting site using WebTorrent

* :heavy_check_mark: [PixelFed](https://pixelfed.org/) - image sharing

* [snap.as](https://github.com/snapas) - photo sharing

* :heavy_check_mark: [reel2bits](https://github.com/rhaamo/reel2bits) - Soundcloud-like
 
#### Events and Meetups

* [Calendar-social](https://gitea.polonkai.eu/gergely/calendar-social/issues/122) - definitely planning to [implement AP](https://gitea.polonkai.eu/gergely).

* [GetTogether](https://github.com/GetTogetherComm/GetTogether/issues/60)

* :heavy_check_mark: [Mobilizon](https://framagit.org/framasoft/mobilizon/issues/9) - aims to be more than a Meetup clone

Friendica (see above) has an events engine but there are conflicting reports about whether or not federation of events over AP is working yet. [NextCloud federated events](https://github.com/nextcloud/calendar/pull/878) are in the work but this may or may not be AP-compatible.

#### Files, Contacts, and Calendar Syncing Apps

* :heavy_check_mark: [NextCloud-Social](https://github.com/nextcloud/social)

* [MoodleNet](https://gitlab.com/moodlenet) - a [social client for Moodle](https://moodle.com/moodlenet) LMS (Learning Management System) aimed at helping teachers collaboratively collate and curate sets of OER (Open Educational Resources).

#### Developer Tools

* :heavy_check_mark: [ActivityPub PHP](https://github.com/pterotype-project/activitypub-php) - library

* :heavy_check_mark: [BridgyFed](https://github.com/snarfed/bridgy-fed/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+activitypub)

* :heavy_check_mark: [CommonsPub](https://gitlab.com/OpenCoop/CommonsPub) - a fork of Pleroma intended to provide a UX that supports economic transactions and coordination

* :heavy_check_mark: [Distbin](http://distbin.com/about)  

* :heavy_check_mark: [Express ActivityPub](https://github.com/dariusk/express-activitypub) - reference implementation using Express.js 

* :black_nib: [FedEvent](https://github.com/shiburizu/fedevent) - a prototype for federating event information

* :heavy_check_mark: [ForgeFed](https://github.com/forgefed/forgefed/) (formerly GitPub) - a set of extensions to AP for federation between code forges (Git hosting sites like GitLab, Gogs, Gitea etc)

* :heavy_check_mark: [go-fed](https://github.com/go-fed/activity) - AP libraries written in Go

* [Indienet](https://source.ind.ie/indienet) - [homepage](https://indienet.info/) - projects goals seem similar to the federated homepages of the IndieWeb, but federated using AP.

* :heavy_check_mark: [LitePub](https://litepub.social/litepub/) - a set of extensions to AP, being developed by devs from Pleroma and Mastodon

* :heavy_check_mark: [Nautilus](https://github.com/aaronpk/Nautilus) - a tool to allow self-hosted blog sites to have their posts followed and commented on via AP

* :heavy_check_mark: [p3k](https://indieweb.org/p3k) - a set of tools indie.web sites can use to support AP [servers](https://the-federation.info/p3k)

* [Places.pub](https://github.com/w3c/activitypub/issues/282) - AP implementation testing tool?

* :heavy_check_mark: [pubgate](https://github.com/autogestion/pubgate) - "Asyncronous Lightweight ActivityPub API ... Based on little-boxes. Implements both the client-to-server API and the federated server-to-server API. Compatible with Mastodon, Pleroma and microblog.pub"

* [Pubstrate](https://gitlab.com/dustyweb/pubstrate) - experimental AP implementation written in GNU Guile (no docs?)

* :black_nib: [RSS-to-ActivityPub Converter](https://github.com/dariusk/rss-to-activitypub) - what is says on the tin ;)

* [Spritely](https://gitlab.com/spritely/) - a new federated media-streaming server in Ratchet, planned by Chris Webber of MediaGoblin fame

* [tags.pub](https://github.com/w3c/activitypub/issues/281) - AP implementation testing tool?

#### Relays [reference](https://github.com/distributopia/fediverse-relays)

* :heavy_check_mark: [Pub relay](https://source.joinmastodon.org/mastodon/pub-relay)

* :heavy_check_mark: [Activity relay](https://git.pleroma.social/pleroma/relay)

* :heavy_check_mark: [Seattle relay](https://gitlab.com/jankysolutions/social.seattle.wa.us/relay)

#### It's Dead, Jim

Projects that are officially abandoned by the maintainers or with no signs of life on their code repo or any other official channels for more than a year. Listed on this watchlist just in case anyone doesn't realize they're dead, and thinks we just didn't know about them. Also in case a project is orphaned, then reactivated by a new developer.

* [Acorde](https://github.com/polymerwitch/Acorde) - federated social music platform. Almost a year has passed since the initial commit.

* [CloutStream](https://web.archive.org/web/20180808152307/http://cloutstream.com/) - proposed as a federated replacement for LinkedIn. Original Mastodon.social account appears to have been removed ([copy on Pinafore]( https://pinafore.social/accounts/25168)), all the links projects tools appear to be down. 

* [Fontina](https://github.com/beta-phenylethylamine/fontina) - proposed as a photo-sharing social media network. GH repo has gone read-only, and now says "dead project".

* [MediaGoblin](https://issues.mediagoblin.org/ticket/5503) - streaming of any and all media files. Currently in "[unofficial retirement](https://news.ycombinator.com/item?id=19779594)".

* [Numa](https://github.com/numaverse/numaverse-gateway/issues/3) - built on Ethereum blockchain but intended to federate with AP. No commits since April 2018. No reply on issue about AP compatibility testing from May 8. Homepage now a spam site.

* [Osada](https://framagit.org/zot/osada) - Osada was a full featured social network application running under the ActivityPub protocol. It also communicated with and inter-operated with servers on the Zot6 network. Abandoned by the developers in March 2019.

* [Pylodon](https://github.com/rowanlupton/pylodon) - Flask-based (Python) ActivityPub server , [source code also on GitLab](https://gitlab.com/rowanlupton/pylodon), no updates on either repo for about a year, nor on their Smilodon client app.

* [Quit.im](https://quit.im) - this was a photo-sharing web client for a GNU social server, rather than a completely separate app. It would become an AP implementation when the AP plug-in for GS is done, but it's been obsoleted by the release of PixelFed.

* :heavy_check_mark: [Smilodon](https://gitlab.com/tuxcrafting/smilodon) - abandoned by developer "I'm now [working on Sminos](https://gitlab.com/tuxcrafting/sminos/issues/1) and so this will probably be 100% abandoned. There's not much to salvage, its code is cancer."

## Sources

Aside from project homepages and issue trackers, and comments made on the fediverse, the [SocialWG has a list](https://www.w3.org/wiki/Socialwg/ActivityPub_network) of projects they hoped would implement ActivityPub and links to Issues where it's discussed. Also, there is an [implementation report on ActivityPub.rocks](https://activitypub.rocks/implementation-report/). @Mayel from Social.coop created a [web spreadsheet of AP apps](https://ethercalc.org/fediverse-stacks) and their characteristics. More projects using AP are [profiled on We Distribute](http://wedistribute.org/) by Sean Tilley. The [ActivityPub tag on GH](https://github.com/topics/activitypub) is also a way to discover projects experimenting with AP.