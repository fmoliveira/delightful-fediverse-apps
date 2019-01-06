This protocol summary was originally put together by Strypey on the [Ind.ie GitLab server](https://source.ind.ie/project/heartbeat-cocoa/issues/194#note_10161), and was first put up here in issue #11. 

Tent is dead ([last commit on Tent code was in 2016](https://github.com/tent)), and OStatus is in the process of being superseded by ActivityPub, probably by the end of 2018. Depending on what kind of interaction you want to federate, the actively used protocols are:


- social network (private, asynchronous messaging): Diaspora protocol (as used internally by Diaspora, and implemented for inter-operation with them by Friendica, and Hubzilla), Zot (used internally by Hubzilla), email protocols! ActivityPub can support private messages in theory, but so far Mastodon and Pleroma are the only AP-supporting apps that allow private "Direct Messages", and it's unclear if this is compatible with the AP spec.

- social media (public, asynchronous messaging): ActivityPub (used internally by Mastodon, Pleroma, and implemented for inter-operation by Hubzilla and Friendica, implementations underway for GNU Social, postActiv, and pump.io), Diaspora protocol, Zot, Micropub (micro.blog and IndieWeb sites).

- realtime chat (private): XMPP used mostly in desktop clients like Pidgin and Jitsi, but there are a few mobile clients (Conversations, Yaxim, Tigase, Xabber, Kontalk) and web clients (Let's Chat, Inverse/ Converse, Xabber), MUC (group chat room extension for XMPP)

- realtime chat (public): Matrix (Riot.im as used on Matrix.org and chat.disroot.org), IRC (as used on Freenode).

Some newer client devs are trying to make more Slack-a-like IRC clients, but I suspect Matrix might be better for this, as it handles server-to-server federation in a more standardized way. There are even people trying to build social network web clients on XMPP (Mov.im, Libervia). It's been suggested that this may create challenges, due to the fact XMPP was not designed to be web native, although the Matrix team have backed off from the claims on this they used to make in the [Matrix FAQ](https://matrix.org/docs/guides/faq.html#what-is-the-difference-between-matrix-and-xmpp%3F) (try using web.archive.org to compare this with what it said about XMPP a year ago).