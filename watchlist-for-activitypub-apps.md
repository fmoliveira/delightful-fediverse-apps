&#10004; == **added to live website**

🎉 == **projects that have successfully federated with this protocol**

:black_nib: == newly added to this page (added, not altered. Only @lostinlight to remove please)

*Note*: Tools with open protocol issue (not yet implemented), not fully open sourced code, no documentation at all, or alpha state with development inactive for several months, not added for now.

## List of projects have an ActivityPub implementation or are committed to one

*Note*: This list began in issue https://gitlab.com/fediverse/fediverse.gitlab.io/issues/8. Most of these projects include both a back-end and a web client, but this list can also include projects that are only a back-end. Projects that are only a web app, for use with an existing back-end, will go on the [client watchlist ](https://gitlab.com/fediverse/fediverse.gitlab.io/wikis/watchlist-for-client-apps).

#### Social networks, Microblog Apps

* &#10004; [Aardwolf](https://github.com/Aardwolf-Social/aardwolf)

* &#10004; [Friendica](https://friendi.ca/) - [AP support still in beta](https://friendi.ca/2018/11/18/activitypub-support-in-friendica/), due to be included in the December release of stable.

* &#10004;[GangGo](https://git.feneas.org/ganggo/federation/issues/17)  - have a basic implementation of AP done. Considering adopting Go-Fed in its place.

* &#10004; [GNU social](https://gnu.io/social)

* [Kitsune](https://github.com/valerauko/kitsune) - microblogging

* [Kroeg](https://git.puckipedia.com/kroeg) - git repo errors out

* &#10004; [Mastodon](https://joinmastodon.org)

* &#10004; [microblog.pub](https://github.com/tsileo/microblog.pub) - single-user microblog server

* &#10004; [microstatus](https://github.com/Arkanosis/microstatus) - Lightweight Mastodon- and GNU Social-compatible ActivityPub and OStatus server implementation

* &#10004; [Misskey](https://joinmisskey.github.io/)

* &#10004; [Osada](https://macgirvin.com/wiki/mike/Osada/Home) - an AP server that can also act as a bridge for smoother inter-operation between AP networks and Zot networks (Hubzilla)

* &#10004; [Pleroma](https://pleroma.social/)

* [pump.io](https://github.com/pump-io/pump.io/issues/1241)

* [Pylodon](https://github.com/rowanlupton/pylodon) - Flask-based (Python) ActivityPub server , [article](https://blog.rowan.website/2017/12/23/pylodon))

* &#10004; [Rustodon](https://github.com/rustodon/rustodon)

* &#10004; [SocialHome](https://git.feneas.org/socialhome/socialhome/issues/522) - currently working on adding AP support to their [Python federation library](https://git.feneas.org/jaywink/federation/issues/7)

* &#10004; [Kibou](https://git.cybre.club/kibouproject/kibou) - highly customizable multi-protocol social networking server

* &#10004; [Smilodon](https://gitlab.com/tuxcrafting/smilodon)

#### Blog and Publishing Apps

* &#10004; [Dokie.li](https://dokie.li)

* &#10004; [FediBlog](https://framagit.org/DavidLibeau/FediBlog) - fully customisable blog engine

* &#10004; [Huzbilla](https://project.hubzilla.org/) - federated CMS with a range of groupware tools available as plug-ins. Support AP with the [pubcrawl plug-in](https://framagit.org/hubzilla/addons/tree/master/pubcrawl).

* [Known](https://github.com/idno/Known/issues/1701)

* [picopub](https://github.com/transitracer/picopub) - created by the developer of Fontina as a "tiny, Mastodon-compatible blog"

* &#10004; [Plume](https://github.com/Plume-org/Plume)

* &#10004; [Read.as](https://github.com/writeas/Read.as) - a reading app 

* &#10004; [WordPress](https://gitlab.com/fediverse/fediverse.gitlab.io/wikis/Wordpress-integration-with-Fediverse) - an [AP plug-in](https://wordpress.org/plugins/activitypub/) by @pfefferle@mastodon.social, that allows users on AP apps to follow WP blogs, was recently updated. See also [Pterotype](https://getpterotype.com/), which @pfefferle says is currently more feature complete. WordPress is now [listed as a project on the-federation.info](https://the-federation.info/wordpress).

* &#10004; [Write Freely](https://writefreely.org)

* &#10002; [NoteIn](https://github.com/notein/NoteIn) - alpha stage

#### Link-sharing Apps

* [Anancus](https://gitlab.com/tuxether/anancus)

* &#10004; [Prismo](https://gitlab.com/mbajur/prismo)

* &#10004; [Lemmy](https://github.com/dessalines/lemmy)

#### Media-hosting Apps

* &#10004; [Anfora](https://github.com/anforaProject/anfora) (formerly Zinat) - image sharing

* &#10004; [FunkWhale](https://medium.com/we-distribute/funkwhale-an-open-source-grooveshark-alternative-begins-activitypub-implementation-cbc10a412b20) - music streaming

* [MediaGoblin](https://issues.mediagoblin.org/ticket/5503) - streaming of any and all media files

* [PeerPx](https://github.com/peerpx) - social network for photographers ("alternative to 500px / Flickr")

* &#10004; [PeerTube](http://joinpeertube.org/) - video-hosting site using WebTorrent

* &#10004; [PixelFed](https://pixelfed.org/) - image sharing

* [Quit.im](https://quit.im) - this is a photo-sharing web client for a GNU social server, rather than a completely separate app, so it will become an AP implementation when the AP plug-in for GS is done.

* [snap.as](https://github.com/snapas) - photo sharing

* &#10004; [reel2bits](https://github.com/rhaamo/reel2bits) - Soundcloud-like
 
#### Events and Meetups

* [Calendar-social](https://gitea.polonkai.eu/gergely/calendar-social/issues/122) - definitely planning to [implement AP](https://gitea.polonkai.eu/gergely).

* [Fedevent](https://github.com/shiburizu/fedevent) - a prototype for a "[front-end for a bot account on Mastodon to send out notifications](https://socialhub.network/t/federated-events/226/3)".

* [GetTogether](https://github.com/GetTogetherComm/GetTogether/issues/60)

* &#10004; [Mobilizon](https://framagit.org/framasoft/mobilizon/issues/9) - aims to be more than a Meetup clone

Friendica (see above) has an events engine but there are conflicting reports about whether or not federation of events over AP is working yet. [NextCloud federated events](https://github.com/nextcloud/calendar/pull/878) are in the work but this may or may not be AP-compatible.

#### Files, Contacts, and Calendar Syncing Apps

* &#10004; [NextCloud-Social](https://github.com/nextcloud/social)

* [MoodleNet](https://moodle.com/moodlenet) - a social client for the Moodle LMS (Learning Management System) aimed at helping teachers collaboratively collate and curate sets of OER (Open Educational Resources).

#### Developer Tools

* &#10004; [ActivityPub PHP](https://github.com/pterotype-project/activitypub-php) - library

* &#10004; [BridgyFed](https://github.com/snarfed/bridgy-fed/issues?utf8=%E2%9C%93&q=is%3Aissue+is%3Aopen+activitypub)

* &#10004; [CommonsPub](https://gitlab.com/OpenCoop/CommonsPub) - a fork of Pleroma intended to provide a UX that supports economic transactions and coordination

* &#10004; [Distbin](http://distbin.com/about)  

* &#10004; [Express ActivityPub](https://github.com/dariusk/express-activitypub) - reference implementation using Express.js 

* &#10002; [FedEvent](https://github.com/shiburizu/fedevent) - a prototype for federating event information

* &#10004; [ForgeFed](https://github.com/forgefed/forgefed/) (formerly GitPub) - a set of extensions to AP for federation between code forges (Git hosting sites like GitLab, Gogs, Gitea etc)

* &#10004; [go-fed](https://github.com/go-fed/activity) - AP libraries written in Go

* [GitLab](https://gitlab.com/gitlab-org/gitlab-ce/issues/4013) (see also: https://gitlab.com/gitlab-org/gitlab-ce/issues/30991 and https://gitlab.com/gitlab-org/gitlab-ce/issues/44486)

* &#10004; [LitePub](https://litepub.social/litepub/) - a set of extensions to AP, being developed by devs from Pleroma and Mastodon

* &#10004; [Nautilus](https://github.com/aaronpk/Nautilus) - a tool to allow self-hosted blog sites to have their posts followed and commented on via AP

* &#10004; [p3k](https://indieweb.org/p3k) - a set of tools indie.web sites can use to support AP [servers](https://the-federation.info/p3k)

* [Places.pub](https://github.com/w3c/activitypub/issues/282) - AP implementation testing tool?

* &#10004; [pubgate](https://github.com/autogestion/pubgate) - "Asyncronous Lightweight ActivityPub API ... Based on little-boxes. Implements both the client-to-server API and the federated server-to-server API. Compatible with Mastodon, Pleroma and microblog.pub"

* [Pubstrate](https://gitlab.com/dustyweb/pubstrate) - experimental AP implementation written in GNU Guile (no docs?)

* [tags.pub](https://github.com/w3c/activitypub/issues/281) - AP implementation testing tool?

#### Relays [reference](https://github.com/distributopia/fediverse-relays)

* &#10004; [Pub relay](https://source.joinmastodon.org/mastodon/pub-relay)

* &#10004; [Activity relay](https://git.pleroma.social/pleroma/relay)

* &#10004; [Seattle relay](https://gitlab.com/jankysolutions/social.seattle.wa.us/relay)

#### Proposed Projects and implementations in development

A place to list rumoured projects for further research, apps whose developers have expressed interest in implementing AP, and vapourware projects that have been planned but no usable code has been written yet. Once it's clear that the project really exists, is definitely working on implementing AP, and code is actually being committed, it can be moved to the appropriate category above.

* [Communecter](https://github.com/pixelhumain/) - already supports ActivityStreams, [plans to implement the rest of AP](https://www.loomio.org/d/Y8kHSzPE/activitypub-as-a-decentralized-oae-infrastructure-/3). Codebase is currently being [refactored into a set of smaller components](https://www.loomio.org/d/Y8kHSzPE/activitypub-as-a-decentralized-oae-infrastructure-/19).

* [Dreamwidth](https://github.com/dreamwidth/dw-free/issues/2337) - a blogging engine forked from LiveJournal.

* [Ghost](https://forum.ghost.org/t/federate-over-activitypub/1989/15)

* &#10002; [Human Connection](https://github.com/Human-Connection/Human-Connection/issues/114)

* [Indienet](https://source.ind.ie/indienet) - [homepage](https://indienet.info/) - projects goals seem similar to the federated homepages of the IndieWeb, but federated using AP.

* &#10002; [Marmota](https://gitlab.com/Nefix/marmota) - service like Spotify or any music streaming service, initial commit; 

* [Minds](https://gitlab.com/minds/engine/issues/183) - a centralized attempt at a FB replacement, incorporating short or long form posts, and live chat, as well as an internal token system (a bit like Reddit gold?)

* [Spritely](https://gitlab.com/spritely/) - a new federated media-streaming server in Ratchet, planned by Chris Webber of MediaGoblin fame

#### It's Dead, Jim

Listed on this watchlist just in case anyone doesn't realize they're dead, and thinks we just didn't know about them. Also in case a project is orphaned, then reactivated by a new developer.

* [Acorde](https://github.com/polymerwitch/Acorde) - federated social music platform. Almost a year has passed since the initial commit.

* &#10006; [CloutStream](https://web.archive.org/web/20180808152307/http://cloutstream.com/) - proposed as a federated replacement for LinkedIn. Original Mastodon.social account appears to have been removed ([copy on Pinafore]( https://pinafore.social/accounts/25168)), all the links projects tools appear to be down. 

* &#10006; [Fontina](https://github.com/beta-phenylethylamine/fontina) - proposed as a photo-sharing social media network. GH repo has gone read-only, and now says "dead project".

* &#10006; [Numa](https://github.com/numaverse/numaverse-gateway/issues/3) - built on Ethereum blockchain but intended to federate with AP. No commits since April 2018. No reply on issue about AP compatibility testing from May 8. Homepage now a spam site.

* &#10006; [Osada](https://framagit.org/zot/osada) - Osada was a full featured social network application running under the ActivityPub protocol. It also communicated with and inter-operated with servers on the Zot6 network. Abandoned by the developers in March 2019.

##Sources

Aside from project homepages and issue trackers, and comments made on the fediverse, the [SocialWG has a list](https://www.w3.org/wiki/Socialwg/ActivityPub_network) of projects they hoped would implement ActivityPub and links to Issues where it's discussed. Also, there is an [implementation report on ActivityPub.rocks](https://activitypub.rocks/implementation-report/). @Mayel from Social.coop created a [web spreadsheet of AP apps](https://ethercalc.org/fediverse-stacks) and their characteristics. More projects using AP are [profiled on We Distribute](http://wedistribute.org/) by Sean Tilley. 