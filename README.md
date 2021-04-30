# At the distance

Notes on distance information sharing.

I would like to share some experiences on how to share information using some Audio and Video shareing channels and tools.

The main concern was to use open source tools as well as open protocols.

This should be considered a never ending mission that might get improved over time but will never be finished.

## The Software

My favourite [meet.jit.si](https://meet.jit.si/) no install opensource.
Hosted or [self hosted](https://github.com/jitsi/docker-jitsi-meet).

For (not-only-)video editing:

* https://www.blender.org/ - 3D modeler and beyond (it can edit video footage)
* http://cinelerra.org/ - The open source video editing

The live and recorded video awesome piece of software:

* https://obsproject.com - the original (Win, Lin, Mac)
* https://streamlabs.com - made to be easier
* https://www.twitch.tv/broadcast/studio - Twitch tailored version
* https://www.vmix.com/ - the commercial brother made to be more robust with many plugins

Not to forget the audio:

* https://pocketstreamer.app/ - do you have your icecast server

## The Hardware

When you plan to share some content please do your homework and learn from those Youtubers, Twitchers and other streaming animals. These people are damn good and they have things to share.

* [Alpha Gaming](https://www.youtube.com/channel/UCATWC1JSlhzmYeDbjnS8WwA)
* to add...

Thing that I have learned was that the content matter. When you present something that is interesting and the material quality is great then you get more engagement. On the other hand sharing those boring blinking squares on small screen which many teachers do is... well at least boring...

What to consider:

* The __content__: slides/handouts, videos of experiments, shared board drawing
* The __audio__: if you do broadcast live you must sound good (echo is bad! barking dog can be fun just once)
* The __video__: actualy might not be that important if you do not have a content to show, consider using some pre-recorded content rather then talking head

## The Pipe

There is always two content production approaches:

* __live broadcasting__ - heavily depends on your masterhood, technology can help but you have to be an actor/actress to convey message properly
* __recording__ - this gives you the chance to edit out mistakes, and tune the result to perfection

When you start you should consider the later, recording. I was always admiring those BBC documentaries. BTW do you know [Bang goes the theory](https://www.bbc.co.uk/programmes/b00lwxj1) series, [Sir David Attenborough](https://www.bbc.co.uk/iplayer/group/p03szck8), [Royal Institution Christmas Lectures](https://www.bbc.co.uk/programmes/b00pmbqq). Or [Matt Parker](http://standupmaths.com/) the math showman.


## The Protocols

If we consider the A/V transport there exist whole pile of protocols to be used. Each hanving their own legacy and also ease of use.

* [SRT - UDT](https://www.haivision.com/blog/broadcast-video/created-srt-difference-srt-udt/) (UDP) based for harsh transport environment
* [RTMP](https://en.wikipedia.org/wiki/Real-Time_Messaging_Protocol) - TCP based, used by StreamLabs, Twitch, YouTube
* [RTP](https://en.wikipedia.org/wiki/Real-time_Transport_Protocol) - UDP based but used mostly by WebRTC, (but also [WebTTY](https://github.com/maxmcd/webtty))
* NDI - NewTek and BlackMagic, 125 Mpbs down to 5 Mbpx with HX (H.264) and HX2 (H.264, HEVC=H.265)
* MPEG - the EBU and broadcasters are used to this
	* MPEG-DASH
	* MPEG-TS
* [Adaptive bitrate streaming](https://en.wikipedia.org/wiki/Adaptive_bitrate_streaming) 
	* HLS
	* MS Smoothstreaming
	* MPEG-Dash
	* m3u8

Nginx with [RTMP module](https://docs.peer5.com/guides/setting-up-hls-live-streaming-server-using-nginx/).

iOS:

* [Larix Broadcaster](https://apps.apple.com/us/app/larix-broadcaster/id1042474385)
* [Broadcast Me](https://apps.apple.com/us/app/broadcast-me/id491982406)
* [Wowza GoCoder](https://apps.apple.com/us/app/wowza-gocoder/id640338185)

Android:

* [Larix Broadcaster](https://play.google.com/store/apps/details?id=com.wmspanel.larix_broadcaster)

[Many droid cams](https://play.google.com/store/search?q=droidcam&c=apps)

Or just use the built in application for shooting videos and then just transfer files by some mean:

* [Syncthing](https://play.google.com/store/apps/details?id=com.nutomic.syncthingandroid)
* [Nextcloud](https://play.google.com/store/apps/details?id=com.nextcloud.client)
* [Astro file manager](https://play.google.com/store/apps/details?id=com.metago.astro)

Other media:

* [VS Live Share](https://visualstudio.microsoft.com/cs/services/live-share/)
* [Google Docs](https://docs.google.com/)
* [EtherPad](https://etherpad.org/)
* [MSRP](https://en.wikipedia.org/wiki/Message_Session_Relay_Protocol) - over RTP/UDP
* [STUN](https://cs.wikipedia.org/wiki/STUN) - the relay

[SylkServer](https://sylkserver.com/)

