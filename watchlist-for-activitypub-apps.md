&#10004; == **added to live website**

[Tools with open protocol issue (not yet implemented), not fully open sourced code, no documentation at all, or alpha state with development inactive for several months - not added for now]

### List of projects that may be implementing ActivityPub, which began in issue https://gitlab.com/fediverse/fediverse.gitlab.io/issues/8

The [SocialWG has a list](https://www.w3.org/wiki/Socialwg/ActivityPub_network) of projects they hope will implement ActivityPub and links to Issues where it&#39;s discussed. Also, there is an [implementation report on ActivityPub.rocks](https://activitypub.rocks/implementation-report/). @Mayel from Social.coop is maintaining a [web spreadsheet of AP apps](https://ethercalc.org/fediverse-stacks) and their characteristics. More projects using AP are [profiled on We Distribute](https://medium.com/we-distribute) by Sean Tilley. From these and other sources (see links), it looks like all these apps are either considering, working on, or already rolling out AP support:

*Note*: most of these projects include both a back-end and a web client, but this list also includes projects that are only a back-end. Projects that are only a web app, for use with an existing back-end, will go on the client list [here](https://gitlab.com/fediverse/fediverse.gitlab.io/wikis/watchlist-for-client-apps).

#### Social network, Microblog Apps

* &#10004; [Aardwolf](https://github.com/Aardwolf-Social/aardwolf)

* &#10004; [Friendica](https://friendi.ca/) - [AP support still in beta](https://friendi.ca/2018/11/18/activitypub-support-in-friendica/), due to be included in the December release of stable.

* &#10004; [GNU social](https://gnu.io/social)

* [Kitsune](https://github.com/valerauko/kitsune) - microblogging

* &#10004; [Kroeg](https://git.puckipedia.com/kroeg)

* &#10004; [Mastodon](https://joinmastodon.org/)

* &#10004; [microblog.pub](https://github.com/tsileo/microblog.pub) - single-user microblog server

* [microstatus](https://github.com/Arkanosis/microstatus) - Lightweight Mastodon- and GNU Social-compatible ActivityPub and OStatus server implementation

* &#10004; [Misskey](https://joinmisskey.github.io/)

* &#10004; [Osada](https://macgirvin.com/wiki/mike/Osada/Home) - an AP server that can also act as a bridge for smoother inter-operation between AP networks and Zot networks (Hubzilla)

* &#10004; [Pleroma](https://pleroma.social/)

* [pump.io](https://github.com/pump-io/pump.io/issues/1241)

* [Pylodon](https://github.com/rowanlupton/pylodon) - Flask-based (Python) ActivityPub server ([Smilodon client](https://github.com/rowanlupton/smilodon), [article](https://blog.rowan.website/2017/12/23/pylodon))

* &#10004; [Rustodon](https://github.com/rustodon/rustodon)

#### Blog and Publishing Apps

* &#10004; [Dokie.li](https://dokie.li)

* &#10004; [FediBlog](https://framagit.org/DavidLibeau/FediBlog) - fully customisable blog engine

* [Ghost](https://forum.ghost.org/t/federate-over-activitypub/1989/15)

* &#10004; [Huzbilla](https://project.hubzilla.org/) - federated CMS with a range of groupware tools available as plug-ins

* [Known](https://github.com/idno/Known/issues/1701)

* &#10004; [Plume](https://github.com/Plume-org/Plume)

* &#10004; [Read.as](https://github.com/writeas/Read.as) - a reading app 

* [WordPress](https://gitlab.com/fediverse/fediverse.gitlab.io/wikis/Wordpress-integration-with-Fediverse) - an [AP plug-in](https://wordpress.org/plugins/activitypub/) by @pfefferle@mastodon.social, that allows users on AP apps to follow WP blogs, was recently updated. See also [Pterotype](https://getpterotype.com/), which @pfefferle says is currently more feature complete. WordPress is now [listed as a project on the-federation.info](https://the-federation.info/wordpress).

* &#10004; [Write Freely](https://writefreely.org)

#### Link-sharing Apps

* [Anancus](https://gitlab.com/tuxether/anancus)

* &#10004; [Prismo](https://gitlab.com/mbajur/prismo)

#### Media-hosting Apps

* [Acorde](https://github.com/polymerwitch/Acorde) - federated social music platform (initial commit)

* &#10004; [Anfora](https://github.com/anforaProject/anfora) (formerly Zinat) - image sharing

* &#10004; [FunkWhale](https://medium.com/we-distribute/funkwhale-an-open-source-grooveshark-alternative-begins-activitypub-implementation-cbc10a412b20) - music streaming

* [MediaGoblin](https://issues.mediagoblin.org/ticket/5503) - streaming of any and all media files

* [PeerPx](https://github.com/peerpx) - social network for photographers ("alternative to 500px / Flickr")

* &#10004; [PeerTube](http://joinpeertube.org/) - video-hosting site using WebTorrent

* [PixelFed](https://pixelfed.org/) - image sharing

* [Quit.im](https://quit.im) - this is a photo-sharing web client for a GNU social server, rather than a completely separate app, so it will become an AP implementation when the AP plug-in for GS is done.

* [snap.as](https://github.com/snapas) - photo sharing

* &#10004; [reel2bits](https://github.com/rhaamo/reel2bits) - Soundcloud-like
 
#### Events and Meetups

* [Calendar-social](https://gitea.polonkai.eu/gergely/calendar-social/issues/122) - no specific mention of ActivityPub on the repo but rumour on the fediverse is that it will be an AP app. I will post a question on their issue tracker.

* [GetTogether](https://github.com/GetTogetherComm/GetTogether/issues/60)

* [Mobilizon](https://framagit.org/framasoft/mobilizon) - aims to be more than a Meetup clone

#### Files, Contacts, and Calendar Syncing Apps

* &#10004; [NextCloud](https://help.nextcloud.com/t/activitypub-the-new-standard-for-decentralized-networks/26381) - seem to be only using AP for internal federation?

* &#10004; [ownCloud](https://github.com/owncloud/activity/issues/494) - seem to be only using AP for internal federation?

#### Developer Tools

* &#10004; [ActivityPub PHP](https://github.com/pterotype-project/activitypub-php) - library

* &#10004; [BridgyFed](https://github.com/snarfed/bridgy-fed/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+activitypub)

* &#10004; [CommonsPub](https://gitlab.com/OpenCoop/CommonsPub) - a fork of Pleroma intended to provide a UX that supports economic transactions and coordination

* [Distbin](http://distbin.com/about) - not FOSS

* [Express ActivityPub](https://github.com/dariusk/express-activitypub) - reference implementation using Express.js 

* &#10004; [ForgeFed](https://github.com/forgefed/forgefed/) (formerly GitPub) - a set of extensions to AP for federation between code forges (Git hosting sites like GitLab, Gogs, Gitea etc)

* &#10004; [go-fed](https://github.com/go-fed/activity) - AP libraries written in Go

* [GitLab](https://gitlab.com/gitlab-org/gitlab-ce/issues/4013) (see also: https://gitlab.com/gitlab-org/gitlab-ce/issues/30991)

* &#10004; [Nautilus](https://github.com/aaronpk/Nautilus)

* [p3k](https://indieweb.org/p3k) - a set of tools indie.web sites can use to support AP [servers](https://the-federation.info/p3k)

* [Places.pub](https://github.com/w3c/activitypub/issues/282) - AP implementation testing tool?

* [Pubstrate](https://gitlab.com/dustyweb/pubstrate) - experimental AP implementation written in GNU Guile (no docs?)

* [tags.pub](https://github.com/w3c/activitypub/issues/281) - AP implementation testing tool?

#### Proposed Projects

A place to list rumoured projects for further research, and vapourware, projects that have been planned but no usable code has been written yet.

* [Communecter](https://github.com/pixelhumain/communecter) - already supports ActivityStreams, plans to implement the rest of AP soon (is it alive?)

* [Indienet](https://source.ind.ie/indienet) - [homepage](https://indienet.info/) - projects goals seem similar to the federated homepages of the IndieWeb, but federated using AP.

* [Spritely](https://gitlab.com/spritely/spritely) - a new federated media-streaming server in Ratchet, planned by Chris Webber of MediaGoblin fame

#### Dead Projects

Listed on this watchlist just in case anyone doesn't realize they're dead, and thinks we just didn't know about them. Also in case a project is orphaned, then reactivated by a new developer.

* [CloutStream](https://web.archive.org/web/20180808152307/http://cloutstream.com/) - proposed as a federated replacement for LinkedIn. Original Mastodon.social account appears to have been removed ([copy on Pinafore]( https://pinafore.social/accounts/25168)), all the links projects tools appear to be down. 

* [Fontina](https://github.com/beta-phenylethylamine/fontina) - proposed as a photo-sharing social media network. GH repo has gone read-only, and now says "dead project".

* [Numa](https://github.com/numaverse/numaverse-gateway/issues/3) - built on Ethereum blockchain but intends to federate with AP. No commits since April 2018. No reply on issue about AP compatibility testing from May 8.