This protocol summary was originally put together by Strypey on the [Ind.ie GitLab server](https://source.ind.ie/project/heartbeat-cocoa/issues/194#note_10161), and was first put up here in issue #11. 

Tent is dead, and OStatus is in the process of being superseded by ActivityPub, probably by the end of 2018. Depending on what kind of interaction you want to federate, the actively used protocols are:


- social network (private, asynchronous messaging): Diaspora protocol (as used internally by Diaspora, and implemented for inter-operation with them by Friendica, and Hubzilla), Zot (used internally by Hubzilla), email protocols!

- social media (public, asynchronous messaging): ActivityPub (used internally by Mastodon, Pleroma, and implemented for inter-operation by Hubzilla, implementations underway for GNU Social, postActiv, Friendica, and pump.io), Diaspora protocol, Zot, and Micropub (micro.blog and IndieWeb sites)

- realtime chat (private): XMPP used mostly in desktop clients like Pidgin and Jitsi, but there are a few mobile clients (Conversations, Yaxim, Tigase, Xabber, Kontalk) and web clients (Let's Chat, Inverse/ Converse, Xabber), MUC (group chat room extension for XMPP)

- realtime chat (public): Matrix (Riot.im as used on Matrix.org and chat.disroot.org), IRC (as used on Freenode).

Some newer client devs are trying to make more Slack-a-like XMPP and IRC clients, but I suspect Matrix is better for this, and handles server-to-server federation in a more standardized way. There are even people trying to build social network web clients on XMPP (Mov.im, Libervia), but this requires a heavy stack, and challenges are created by the fact XMPP was not designed to be web native.