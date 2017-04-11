--- Log opened Tue Apr 11 00:00:50 2017
00:05 -!- dbolton [~Thunderbi@50-83-92-171.client.mchsi.com] has joined #ardour
00:14 < tom-> MaurizioB: it has a script now :)
00:16 < MaurizioB> tom-: good :)
00:19 < tom-> MaurizioB: please let me know when - you get at it - if there were any issues or things you'd like to do
00:20 -!- dbolton [~Thunderbi@50-83-92-171.client.mchsi.com] has quit [Ping timeout: 245 seconds]
00:20 < digidog> las: I saw you mentioning Composite today from the logs. Maybe this is an interesting info for you? -> I had to request the removal of Composite from the Debian repos (sadly I had to because it was never ready for any use) and Gabriel has replied to it. https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=859808#69 ... I think Composite is dead. I am very sorry for all the effort until that.
00:20 < LAbot`> Title: #859808 - composite: Composite not ready for being qualified package of Debian yet. - Debian Bug report logs (at bugs.debian.org)
00:20 < MaurizioB> tom-: I'm a little busy these days. but I'll check it out as soon as possible
00:21 < tom-> MaurizioB: yep good luck
00:21 < las> digidog: that's a shame
00:21  * las -> mattress
00:22 < MaurizioB> tom-: thanks :)
00:25 < digidog> las: yeah it is :/ ... have a good night.
00:26 -!- takuan [~takuan@178-116-220-20.access.telenet.be] has quit [Remote host closed the connection]
00:36 -!- NickSB [~nicksb@cpc13-harb9-2-0-cust41.19-1.cable.virginm.net] has quit [Remote host closed the connection]
00:38 < snadge> what did composite do better than drmr?
00:40 -!- kyan [~kyan@cpe-24-198-97-231.maine.res.rr.com] has joined #ardour
00:42 < snadge> i gave up on trying to master drskit 
00:43 -!- ressected [~DR@c-68-80-98-220.hsd1.de.comcast.net] has joined #ardour
00:43 < snadge> i mean, you can whack a tissue box in a bathroom and turn that into a kick drum, by use of magic / witchcraft
00:45 < snadge> i failed to get a result in about 15 minutes of trying 
00:46 < petererer> hmm, drmr, forgot about that. even has my name in the commits :p
00:48 -!- henkz [~henke@h-180-60.a193.priv.bahnhof.se] has quit [Quit: Leaving]
00:48 < snadge> the_CLA was going to try installing drskit
00:50 < snadge> Maybe we should have a drskit challenge ;)
00:51 < snadge> make a drum track that sounds good using it.. hehe.. no rules
00:51 < the_CLA> It isn't that bad - just not my personal taste...
00:53 < snadge> i wanted to try and get a clean jazz sound out of it
00:53 < snadge> the description indicated that it should be possible ;)
00:54 < snadge> that woukd make an excellent youtube video if someone could 
00:55 < the_CLA> Playing drums myself is more fun than editing MIDI, though. ;)
00:56 < snadge> i literally cant.. two reasons.. no kit, and the more fundamental problem, no coordination or talent.. hell, i dont even have much experience composing / sequencing
00:58 < snadge> heaven forbid if i ever become any good i'd love to work with session musicians.. but until then, i have to work with midi, sequencers, and the best sounding instruments / vsts that i can
01:00 -!- barjac [~quassel@host86-184-238-121.range86-184.btcentralplus.com] has joined #ardour
01:03 -!- barjac_ [~quassel@host86-191-77-171.range86-191.btcentralplus.com] has quit [Ping timeout: 240 seconds]
01:04 < snadge> does anyone here have or know of a youtube channel predominantly about mixing / mastering? :P
01:07 < shamus397> since you asked: https://www.youtube.com/channel/UC-pxLUJ9wLliHhDdsx6JHKQ
01:09 -!- c3r1c3-Win [~c3r1c3-Wi@ip72-211-87-79.no.no.cox.net] has joined #ardour
01:09 -!- aisyk [~aisyk@2a02-8429-8179-d500-7d11-1d03-cf73-c1c8.rev.sfr.net] has quit [Remote host closed the connection]
01:13 -!- c3r1c3-Win [~c3r1c3-Wi@ip72-211-87-79.no.no.cox.net] has quit [Ping timeout: 240 seconds]
01:14 -!- c3r1c3-Win [~c3r1c3-Wi@ip72-211-87-79.no.no.cox.net] has joined #ardour
01:19 -!- ressected [~DR@c-68-80-98-220.hsd1.de.comcast.net] has quit [Remote host closed the connection]
01:20 -!- ressected [~DR@c-68-80-98-220.hsd1.de.comcast.net] has joined #ardour
01:22 -!- Alby_Fox [~cccookied@2600:8803:a80f:f400:fe31:d8c5:25ae:620b] has quit [Quit: Leaving]
01:23 -!- Alby_Fox [~cccookied@2600:8803:a80f:f400:fe31:d8c5:25ae:620b] has joined #ardour
01:26 < snadge> subbed :p
01:29 -!- dbolton [~Thunderbi@50-83-92-171.client.mchsi.com] has joined #ardour
01:31 -!- Stuzz [~Stuzz@124-170-165-19.dyn.iinet.net.au] has joined #ardour
01:33 -!- dbolton [~Thunderbi@50-83-92-171.client.mchsi.com] has quit [Ping timeout: 255 seconds]
01:35 -!- CrustY_ [~crusty@93.85.48.160] has quit [Quit: Konversation terminated!]
01:37 -!- drobilla` [~user@2a02:8109:a5bf:fa18:2bca:f443:db5d:f8e8] has joined #ardour
01:38 -!- drobilla [~user@2a02:8109:a5bf:fa18:2bca:f443:db5d:f8e8] has quit [Ping timeout: 240 seconds]
01:44 -!- Yruama_Lairba [~UTILISATE@mut38-h04-89-80-39-202.dsl.sta.abo.bbox.fr] has quit [Read error: Connection reset by peer]
01:46 < the_CLA> rgareus: BTW did you see http://paste.debian.net/hidden/859b9667/
01:46 < the_CLA> ...when trying to connect to already running jack.
01:50 -!- remixvinil [~remix@95.46.18.239] has quit [Ping timeout: 255 seconds]
01:58 < rgareus> the_CLA: yeah, I've seen it before, left it to las to fix
01:58 < the_CLA> Ah, ok.
01:59 < rgareus> IIRC it's a bug in jack, but we probably need to work-around this in ardour
01:59 < rgareus> port=0x0
01:59 < rgareus> should be a NO-OP
02:01 < rgareus> hmm ardour 5.8.272 ?!  I thought that since 5.8-262-g7dde6c3b8  fill_midi_port_info() is no longer called
02:01 < rgareus> las: ^^
02:12 < the_CLA> Anyway... I'm off to bed now. Good night. :)
02:13 < rgareus> 'night
02:22 -!- avlinux [~tester@xplr-104-249-226-222.xplornet.com] has joined #ardour
02:24 < tom-> rgareus: did you try cso?
02:26 -!- NickSB [~nicksb@cpc13-harb9-2-0-cust41.19-1.cable.virginm.net] has joined #ardour
02:29 -!- naturally [~naturally@unaffiliated/naturally] has joined #ardour
02:43 < snadge> man.. some of these studio tips are a bit basic..
02:43 < snadge> use 24bit.. make sure your signal doesn't clip.. cut out noise
02:44 < snadge> needs to get to the bit where you make something that sounds ordinary.. sound awesome ;)
02:47 < snadge> lol.. apparently when stereo first came out.. the beatles had tracks with hard panning.. drums on the left, vocals on the right etc
02:47 < snadge> noobs :P
02:49 -!- gbs [~gbs@unaffiliated/gbs] has joined #ardour
02:49 < rgareus> snadge: except they didn't. that was added for the US edition only
02:50 < snadge> if that was deliberate.. doesn't that fact just make it worse? :p
02:51 < rgareus> also some songs lost the groove because of that.
02:52 < rgareus> it went as far as the Beatles deliberatly destroying some of the master-tapes to make those US stereo versions impossible.
02:53 < snadge> okay wow, that adds a different dimension to that story
02:53 < snadge> so they were opposed to it?
02:54 -!- avlinux [~tester@xplr-104-249-226-222.xplornet.com] has quit [Quit: Leaving]
02:55 < rgareus> remember that in the early 60s you basically had a switch  left, right ,both.
02:55 < rgareus> not a panner
02:55 < snadge> the potentiometer wasn't invented until the 70s? ;)
02:56 < rgareus> lol
02:58 < rgareus> multi-tracks were at the same time. and I guess it took a year or 4 for someone to put it together
02:58 < rgareus> older stereo was just A-B or X-Y mic'ing, no use for a panner
03:00 < snadge> that makes sense yeah.. so to take mono tracks and try to convert those songs into stereo.. is kind of stupid
03:00 < snadge> so i can understand why they were annoyed about it
03:00 < snadge> without a panner that is
03:01 < snadge> they needed to re-record the tracks as stereo and remix them for that to be appropriate.. im presuming that was the source of their annoyance
03:01 < rgareus> it's one of those "obvious in hindsight" things
03:01 < snadge> and headphones wern't as popular as well
03:02 < rgareus> avlinux just left.. but he went back to the root lately: triosonic
03:02 < rgareus> http://bandshed.net/images/logos/TSLogoMMWSIPlainWhite-DS.png  guitar hard right, bass hard left, drums in the center. 
03:03 < rgareus> the rated-blue album of his
03:03 < snadge> the commodore amiga also did this ;)
03:03 < snadge> quadrophonic.. L R R L
03:03 < snadge> hehe
03:04 < rgareus> it's a bit like live from the stage (with speakers -- not headphones)
03:04 < rgareus> bass amp on one side, guitar amp on the other.  drums in the center
03:05 < rgareus> that's strictly speaking also hard-panned
03:06 < rgareus> anyway, bedtime
03:06 < rgareus> TTYL
03:14 < snadge> i wish it was bed time.. im at work.. and seem to be developing some kind of respiratory illness
03:19 -!- nstewart [~nps@cpe-2606-A000-1120-140-9836-315C-7D96-5FBF.dyn6.twc.com] has joined #ardour
03:21 < nstewart> can we have multiple control surfaces? I'm working on a mapping for my Alesis QX25, but it doesn't seem to work. My Zoom R24 works (Mackie) but the Alesis is generic MIDI. Ardour shows the messages in the MIDI tracer
03:22 < nstewart> actually if you go to Preferences->Control Surfaces, click on Generic MIDI, then hit "Show Protocol Settings" it won't come up even if it's checked - unless you uncheck the checkbox, and recheck it
03:28 < OvenWerks> nstewart: you should be able to have more than one control surface under certain conditions
03:29 < OvenWerks> nstewart: one MCP and one generic midi for example.
03:30 < OvenWerks> nstewart: two (or more) MCP where one is master and the others are extenders (making one big surface)
03:31 < OvenWerks> nstewart: as many OSC controllers as you want...
03:32 < OvenWerks> nstewart: of course they do have to be on different midi ports.
03:32 < nstewart> I have one MCP and one Generic MIDI. But generic doesn't work by itself either.  But If I do de/reenable Generic MIDI, then hit protocol, I can set MIDI input to Alesis QX25, show MIDI Control In in the MIDI viewer, and |> shows channel 1, note 73. which is bound to Transport-roll, but it's not working. 
03:33 < nstewart>   <Binding msg="bf 73 7f"         function="transport-roll"/>
03:34 < OvenWerks> "bf 73 7f" is channel 16
03:34 < OvenWerks> "bo would be channel 1
03:35 < nstewart> ah - wrong channel then. 
03:36 < OvenWerks> Ya and I should have had s/bo/b0/
03:38 < nstewart> weird - I changed it to msg="1 73 7f" and set MIDI in and out both to the QX25 - hitting play causes "PLY" to show up in the keyboard's LED window, but doesn't move the transport.
03:38 < OvenWerks>  msg="1 73 7f" is wrong
03:38 < OvenWerks> un less that is b1
03:39 < OvenWerks> b1 would be midi channel 2
03:40 < nstewart> 0 based. only been doing this stuff 30 years now...
03:41 < OvenWerks> <Binding channel="1" note="73" might be easier to use
03:42 < OvenWerks> (channels are 1 based)
03:42 < OvenWerks> But ya, in hex they are zero based
03:44 -!- timbyr [~timbyr@opt-123-254-32-140.client.pikara.ne.jp] has joined #ardour
03:54 < nstewart> where does the map get copied to? It' seems Ardour is using a stale copy. I don't see a copy in ~/.config/ardour5
04:01 -!- chaot4 [~irssi@mailrelay.hostingcloud24.de] has quit [Read error: Connection reset by peer]
04:02 -!- chaot4 [~irssi@mailrelay.hostingcloud24.de] has joined #ardour
04:05 < OvenWerks>  try ~/.config/ardour5/midi_maps
04:05 < OvenWerks>  try ~/.config/ardour5/midi_maps/
04:09 < nstewart>  grep -rIn Alesis ~/.config/ardour5/ shows nothing, must be in session
04:10 < nstewart> and I have no midi_maps dir in ~/.config/ardour5 at all
04:11 -!- c3r1c3-Win [~c3r1c3-Wi@ip72-211-87-79.no.no.cox.net] has quit [Read error: Connection reset by peer]
04:17 -!- Stuzz [~Stuzz@124-170-165-19.dyn.iinet.net.au] has quit [Ping timeout: 252 seconds]
04:18 -!- Stuzz [~Stuzz@203-206-254-62.dyn.iinet.net.au] has joined #ardour
04:25 -!- NoCode [~NoCode@unaffiliated/nocode] has quit [Ping timeout: 260 seconds]
04:35 -!- dsp_ [~dsp@212-183-50-150.adsl.highway.telekom.at] has quit [Ping timeout: 240 seconds]
04:38 -!- nstewart [~nps@cpe-2606-A000-1120-140-9836-315C-7D96-5FBF.dyn6.twc.com] has left #ardour []
04:49 -!- tom- [~srv@84-74-158-93.dclient.hispeed.ch] has quit [Quit: leaving]
04:50 -!- Stuzz [~Stuzz@203-206-254-62.dyn.iinet.net.au] has quit [Ping timeout: 255 seconds]
04:52 -!- Stuzz [~Stuzz@124-150-91-84.dyn.iinet.net.au] has joined #ardour
05:04 -!- naught101 [~naught101@14-202-176-150.static.tpgi.com.au] has joined #ardour
05:18 -!- naturally [~naturally@unaffiliated/naturally] has quit [Ping timeout: 245 seconds]
05:28 -!- DarkAceZ [~DarkAceZ@unaffiliated/darkacez] has quit [Ping timeout: 252 seconds]
05:32 -!- naught101 [~naught101@14-202-176-150.static.tpgi.com.au] has quit [Quit: Konversation terminated!]
05:32 -!- naught101 [~naught101@14-202-176-150.static.tpgi.com.au] has joined #ardour
05:37 -!- joephelius [~joe@gateway/vpn/privateinternetaccess/joephelius] has quit [Ping timeout: 240 seconds]
05:37 -!- naught101 [~naught101@14-202-176-150.static.tpgi.com.au] has quit [Ping timeout: 245 seconds]
05:37 -!- joephelius [~joe@55d474b6.access.ecotel.net] has joined #ardour
--- Log closed Tue Apr 11 05:52:22 2017
--- Log opened Tue Apr 11 05:52:34 2017
05:52 -!- digidog_ [~digidog@x4db3f5a5.dyn.telefonica.de] has joined #ardour
05:52 -!- Irssi: #ardour: Total of 137 nicks [1 ops, 0 halfops, 0 voices, 136 normal]
05:54 -!- Irssi: Join to #ardour was synced in 106 secs
05:55 -!- digidog [~digidog@x4db47b8f.dyn.telefonica.de] has quit [Ping timeout: 245 seconds]
06:11 -!- NoCode [~NoCode@unaffiliated/nocode] has joined #ardour
06:11 -!- GrusGrus [~Thunderbi@yor3.gofore.com] has joined #ardour
06:17 -!- Freejack [~Freejack@unaffiliated/freejack] has quit [Ping timeout: 245 seconds]
06:19 -!- dsr1204__ [~dsr1204__@c-73-72-102-18.hsd1.il.comcast.net] has joined #ardour
06:22 -!- Freejack [~Freejack@unaffiliated/freejack] has joined #ardour
06:25 -!- dsr1204__ [~dsr1204__@c-73-72-102-18.hsd1.il.comcast.net] has quit [Quit: dsr1204__]
06:26 -!- dsr1204__ [~dsr1204__@c-73-72-102-18.hsd1.il.comcast.net] has joined #ardour
07:03 -!- clark|w [~clark_wil@173-25-249-144.client.mchsi.com] has quit [Quit: Leaving]
07:09 -!- olinuxx [~capturixe@unaffiliated/olinuxx] has quit [Remote host closed the connection]
07:25 -!- TheSpy0 [~TheSpy0@108-64-74-45.lightspeed.sntcca.sbcglobal.net] has quit [Quit: No Ping reply in 180 seconds.]
07:26 -!- TheSpy0 [~TheSpy0@108-64-74-45.lightspeed.sntcca.sbcglobal.net] has joined #ardour
07:39 -!- dsr1204__ [~dsr1204__@c-73-72-102-18.hsd1.il.comcast.net] has quit [Ping timeout: 240 seconds]
07:58 -!- remixvinil [~remix@176.60.213.3] has joined #ardour
08:02 -!- jpbouza__ [~Juan@191.85.174.74] has quit [Quit: Leaving]
08:03 -!- takuan [~takuan@178-116-220-20.access.telenet.be] has joined #ardour
08:13 -!- oofus_lt [~quassel@5.148.32.98] has joined #ardour
08:34 -!- Headwar [~edouard@2a01cb00054ce40014888f354b409774.ipv6.abo.wanadoo.fr] has joined #ardour
08:37 -!- ressected [~DR@c-68-80-98-220.hsd1.de.comcast.net] has quit [Quit: Leaving]
08:41 -!- Caterpillar [~caterpill@unaffiliated/caterpillar] has joined #ardour
08:46 -!- _FrnchFrgg_ [~Icedove@37.163.21.109] has joined #ardour
08:51 -!- kyan [~kyan@cpe-24-198-97-231.maine.res.rr.com] has quit [Quit: Leaving]
08:52 -!- Elysion [~Elysion@124-171-186-161.dyn.iinet.net.au] has joined #ardour
08:52 -!- _FrnchFrgg_ [~Icedove@37.163.21.109] has quit [Ping timeout: 255 seconds]
09:07 -!- edogawa [~Thunderbi@194-118-140-208.adsl.highway.telekom.at] has joined #ardour
09:14 -!- Stuzz [~Stuzz@124-150-91-84.dyn.iinet.net.au] has quit [Quit: Vote Ziltoid!]
09:27 -!- magloda [~aht@109-124-147-131.customer.t3.se] has joined #ardour
09:37 -!- aisyk [~aisyk@2a02-8429-8179-d500-849c-80d3-2522-8357.rev.sfr.net] has joined #ardour
09:57 -!- krabador [~krabador@unaffiliated/krabador] has joined #ardour
10:12 -!- tdankert [~tdankert@ip6-2001-638-504-20e0-ffff-0-1-296.Wired.Dyn.CIT-EC.NET] has joined #ardour
10:22 -!- ShalokShalom [~quassel@192-164-248-47.adsl.highway.telekom.at] has joined #ardour
10:30 -!- rgh [~rob@145.130.225.41] has joined #ardour
10:35 -!- melanie_1 [~melanie@d86-32-65-66.cust.tele2.at] has joined #ardour
10:35 -!- melanie__ [~melanie@d86-32-65-115.cust.tele2.at] has quit [Ping timeout: 241 seconds]
10:38 -!- remixvinil [~remix@176.60.213.3] has quit [Quit: Leaving.]
10:40 -!- remixvinil [~remix@176.60.213.3] has joined #ardour
10:40 -!- pecisk [~peteris@195.13.228.110] has joined #ardour
10:47 -!- Miblo_ [~matt@46.234.90.146.dyn.plus.net] has joined #ardour
10:50 -!- Miblo [~matt@58.245.159.143.dyn.plus.net] has quit [Ping timeout: 255 seconds]
10:50 -!- Miblo_ is now known as Miblo
10:54 -!- the_CLA_2 [~the_CLA@p57B98909.dip0.t-ipconnect.de] has joined #ardour
10:57 -!- the_CLA [~the_CLA@p57B98A9A.dip0.t-ipconnect.de] has quit [Ping timeout: 240 seconds]
11:04 -!- nils [nils@nat/redhat/x-dmmxyychtkywnymu] has joined #ardour
11:09 -!- Valvalion [~Valvalion@230.245-245-81.adsl-dyn.isp.belgacom.be] has joined #ardour
11:16 < Bollie> OvenWerks: Regarding the USB issues, we've discussed: I've discovered, that I had my Tascam hooked up to the same bus as my keyboard and mouse. That very bus being USB2 only. Because my mainboard seems to have 4 busses, I kept swapping plugs until I had the Tascam on its own bus und did a test run for several hours. No xruns anymore.
11:17 < Bollie> Don't ask me, why I hadn't found out earlier. *blushes*
11:19 -!- electro-flinch [~colinf@axicon.plus.com] has joined #ardour
11:21 -!- rgh [~rob@145.130.225.41] has quit [Ping timeout: 240 seconds]
11:26 < snadge> interesting
11:26 < snadge> i have to turn my cpu profile to performance to avoid xruns, at 2.7ms
11:30 < petererer> me too
11:30 < petererer> oh
11:30 < petererer> no, i'm at 5.8ms
11:30 -!- psosmol [b05662a8@gateway/web/freenode/ip.176.86.98.168] has joined #ardour
11:31 < petererer> old core2quad q6600 though, seems not as good at switching than newer cpus
11:33 -!- psosmol [b05662a8@gateway/web/freenode/ip.176.86.98.168] has quit [Client Quit]
11:35 -!- rgh [~rob@145.130.225.41] has joined #ardour
11:38 < the_CLA_2> petererer: Even with quite new CPUs you might need to use performance mode.
11:39 < snadge> im curious to see how amd ryzen goes with audio 
11:39 < snadge> most benchmarks seem focused on other aspects 
11:41 < petererer> lots of cores
11:48 < snadge> low latency needs good single core perf.. ardour and plugins compiled -march=native would probably be balls out
11:49 < snadge> id try it, but im kinda waiting for 16 core, and vega
11:49 < snadge> that seams more like a real upgrade from what i have
12:08 < las> snadge: low latency has almost nothing to do with CPU speed or compiler optimization
12:09 < las> snadge: or number of cores
12:10 -!- krabador [~krabador@unaffiliated/krabador] has quit [Remote host closed the connection]
12:12 < digidog_>  las++
12:16 < edogawa> switching the governor to performance makes the difference for me as well, using a slightly older asus motherboard i can go from 256 to 128 frames with jack
12:16 < edogawa> i wonder why when i read las' comment on that
12:17 < snadge> except the more a cpu can do per unit of time, the quicker it can get the same amount of work done
12:18 < snadge> hence its going to be lower latency, than if it was slower
12:18 < petererer> that's only if it's overloaded
12:19 < digidog_> petererer++
12:19 < digidog_> exactly
12:19 < snadge> the ability for a realtime process to interrupt the current task and how quickly it can switch between tasks is more relevant for lower latency sure
12:20 < snadge> but that is a constant, the performance of the cpu is the varying factor
12:21 < edogawa> maybe i confuse things, the other thing i found out that putting things on different usb ports increased stability and responsiveness a lot for my audio poc
12:21 < edogawa> pc
12:21 < snadge> i have an 8350 cpu currently, and im actually betting that usb is the limiting factor
12:21 -!- OvenWerks [~len@jenw.static.uniserve.ca] has quit [Ping timeout: 246 seconds]
12:21 < snadge> exactly 
12:21 -!- OvenWerks [~len@jenw.static.uniserve.ca] has joined #ardour
12:21 < petererer> edogawa, it is not the "performance" makes it run faster, and therefore better
12:22 < digidog_> short data transmittion time, response time, throughput, bandwidth, infearing devices like networking, many things count in. size or count of cpu is on the very end of it before that.
12:22 < digidog_> edogawa: your usb experience is best example of what las says
12:23 < petererer> edogawa, is it because when it is on "performance", there is no speed switching, which on some cpus (/maybe motherboards) can cause issues.
12:23 < edogawa> petererer: in ondemand it seemed to stick in 800 MHz always, even when compiling and eating up all the cpu cycles it didn't speed up instead the mouse lagged etc.
12:24 < edogawa> while it's a phenom 4 core 2,4GHz
12:25 < digidog_> we run very up-to-date 16-core pcs here for feature film editing and tested them regarding audio latency. they were even worse regarding udio latency than the "smaller" pcs here in the sound enginieering room because of other interfearing facts. plus: there are very extrem important differences between TYPES of cpu.
12:29  * digidog_ needs to reboot... this test machine here runs since 24 hours
--- Log closed Tue Apr 11 12:29:58 2017
--- Log opened Tue Apr 11 12:38:56 2017
12:38 -!- digidog [~digidog@x4db3f5a5.dyn.telefonica.de] has joined #ardour
12:38 -!- Irssi: #ardour: Total of 147 nicks [1 ops, 0 halfops, 0 voices, 146 normal]
12:39 -!- You're now known as diqidoq
12:40 -!- Irssi: Join to #ardour was synced in 103 secs
12:44 -!- NickSB2 [~NickSB2__@cpc13-harb9-2-0-cust41.19-1.cable.virginm.net] has joined #ardour
12:49 < diqidoq> ok, for whom it may concern: compiling hydrogen from source brings no improvement in comparision to the latest Debian package.
12:49 -!- edogawa [~Thunderbi@194-118-140-208.adsl.highway.telekom.at] has quit [Ping timeout: 255 seconds]
12:51 < snadge> multicore cpus can lack single thread performance which does make them crappier for low latency sure
12:56 < snadge> its a bit rich from me to be schooling las on the specifics of low latency audio.. its fair enough for him to assume that i didn't know that, from some of the other dumb things that i've said on here :P
13:03 -!- electro-flinch [~colinf@axicon.plus.com] has quit [Ping timeout: 255 seconds]
13:04 < las> snadge: you're mostly wrong about CPU speed
13:10 -!- electro-flinch [~colinf@axicon.plus.com] has joined #ardour
13:10 < snadge> im kind of confused by that.. because all things considered equal, except for the speed of the cpu.. then the quicker cpu will have lower latency
13:12 < las> snadge: nope
13:12 < las> snadge: the real costs of latency are related to context switching
13:13 < las> snadge: this is not typically limited by CPU speed but by (a) size of the register set (b) the working set size of both the switched-from and switched-to task (c) cache misses and their handling
13:13 < las> snadge: none of thse are related to CPU "speed"
13:14 < snadge> thats true.. so i guess my original musings were with regards to ryzen specifically
13:14 < snadge> so as you've pointed out.. that question is best answered by how quickly a context switch can occur in linux, using that cpu architecture
13:15 < snadge> and that would actually be an interesting thing to see in a chart, given a bunch of different cpu types and architectures etc
13:18 < las> snadge: such things have been measured, and i repeat: this is not related to the "CPU"
13:18 < las> snadge: it is overwhelmingly a function of the working set size
13:19 -!- Elysion [~Elysion@124-171-186-161.dyn.iinet.net.au] has quit [Ping timeout: 240 seconds]
13:19 < las> snadge: if you context switch between two tasks which touch almost no memory at all, the switch will be very fast no matter what. if you switch between two tasks which will both touch large amounts of memory as they run, the switch will (effectively) be slow and a function of the MMU
13:21 < snadge> right.. and i just kinda realise how dumb that is.. if my current pc fairly comfortably runs with a 128 byte buffer, i just checked, i cant actually make it any smaller than that anyway
13:22 < snadge> plus im using a usb 1.1 sound card
13:23 < snadge> its pretty hard to justify upgrading my cpu.. for latency reasons
13:23 -!- Yruama_Lairba [~UTILISATE@mut38-h04-89-80-39-202.dsl.sta.abo.bbox.fr] has joined #ardour
13:23 < snadge> plus.. check out this chart
13:23 < snadge> https://www.cpubenchmark.net/singleThread.html
13:24 < LAbot`> Title: PassMark CPU Benchmarks - Single Thread Performance (at www.cpubenchmark.net)
13:27 < snadge> thats supposed to make you feel good about buying a 7700k i guess ;)
13:36 < las> snadge: that chart is almost 100% irrelevant for audio unless you generally have DSP loads up above 60%
13:37 < snadge> is the 7700k the best value for using ardour and doing linux based audio stuff? or is something else better
13:37 < snadge> or like anything does it depend on what you're doing
13:40 < snadge> some people don't even need low latency i guess.. its just handy for previewing or doing software monitoring or live effects
13:43 < snadge> if you're going to be mixing/mastering.. the ability to route all your effects via busses, instead of being forced to flatten them because you're limited by DSP load
13:46 -!- dsp_ [~dsp@193-80-33-149.adsl.highway.telekom.at] has joined #ardour
13:47 -!- sdoherty [sdoherty@nat/redhat/x-krbpmiytbjawnktq] has joined #ardour
13:48 < las> snadge: the motherboard is probably more important than the cpu
13:51 < snadge> memory and storage speed? the motherboard chipset?
13:57 -!- DarkAceZ [~DarkAceZ@unaffiliated/darkacez] has joined #ardour
14:02 -!- NickSB2 [~NickSB2__@cpc13-harb9-2-0-cust41.19-1.cable.virginm.net] has quit [Ping timeout: 252 seconds]
14:04 -!- NickSB2 [~NickSB2__@cpc13-harb9-2-0-cust41.19-1.cable.virginm.net] has joined #ardour
14:06 -!- jaZz_KCS [~64H@ip4d173b94.dynamic.kabel-deutschland.de] has joined #ardour
14:07 < las> snadge: mobo chipset
14:07 < las> snadge: and wiring
14:10 -!- remixvinil [~remix@176.60.213.3] has quit [Remote host closed the connection]
14:11 < snadge> enthusiast chipsets are better?
14:15 < las> snadge: there are no rules
14:15 < las> snadge: everything is trial and error
14:15  * typonese adds mysterious interstitial music 
14:15 -!- remixvinil [~remix@176.60.213.3] has joined #ardour
14:18 < snadge> remember i was complaining about how drumgizmo sounds
14:19 < snadge> https://www.youtube.com/watch?v=8U_nmfdOIVU
14:19 < snadge> Recorded and mixed in Harrison Mixbus 3.2
14:19 < snadge> Drum software: Drumgizmo
14:19 < snadge> im gonna chuck that guy a like
14:21 < snadge> im guessing that is the MuldjordKit, it doesn't say
14:23 -!- audiophilo [~audiophil@94-36-176-69.adsl-ull.clienti.tiscali.it] has joined #ardour
14:24 -!- NickSB2 [~NickSB2__@cpc13-harb9-2-0-cust41.19-1.cable.virginm.net] has quit [Ping timeout: 240 seconds]
14:26 < diqidoq> las: I wrote a 4 pages long letter addressed to the developer team of Hydrogen with many details and explanations about several aspects regarding the future of Hydrogen and my motivation to write this up, only to come to the final conlusion now, that this letter only shows off that it would maybe even be better to start a project like Hydrogen from scratch :-/ ... I think I won't send it *facepalm*
14:26 < typonese> diqidoq: sometimes that's the best way to come to a conclusion :)
14:27 < diqidoq> typonese: I know
14:27 < typonese> :D
14:27 < diqidoq> typonese: I have mayn of those unsend letters :-$
14:27 < diqidoq> :)
14:27 < typonese> diqidoq: same :D
14:27 < typonese> so many in the draughts box :D
14:27 < typonese> er drafts 
14:27 < snadge> diqidoq, hydrogen is a drum sequencer right? what is it in particular that you like about it?
14:28 -!- NickSB2 [~NickSB2__@cpc13-harb9-2-0-cust41.19-1.cable.virginm.net] has joined #ardour
14:29 < las> diqidoq: s/q/g/ ?
14:30 < speak> s/q/g/g   < bettar!
14:31 < typonese> heh
14:33 < diqidoq> snadge: its potential to be a fast intuitive rythm programming machine "right on the _qualified_ finger tips". Something I have talked about a lot on conferences over the years. the potential is there and only viewable for those how are really deep into rythm programming and its nature (also old school). I am not talking about "boom clap boom clap". And I have tested a lot on many OS for many projects. 
14:33 < diqidoq> Even for well known US feature film score titles.
14:33 < diqidoq> las: ?
14:34 < las> diqidoq: generally, i've seen your nick as "digidog" now its "diqidoq"
14:34 < las> maybe more clear: DIGIDOG vs. DIQIDOQ
14:34 < snadge> whats your opinion of something like the roland tr-8, or the boutique tr-09?
14:34 < diqidoq> las: hah, ok ... sorry
14:35 < snadge> i have a couple of classic drum sequencers.. like the tr-808 and tr-909.. but they're absolute garbage ;)
14:36 < diqidoq> las: its because I have started with digidog back in the days and had trouble with registering for github and others while I was already established under Digidog e.g. as a contributor to the Drupal project. So I choose another nick looking almost similar. digidog is actually only in the irssi login config still up, so I need to fix that soon :)
14:37 -!- remixvinil [~remix@176.60.213.3] has quit [Remote host closed the connection]
14:37 < diqidoq> actually its diqidoq (nowadays)
14:37 -!- ShalokShalom [~quassel@192-164-248-47.adsl.highway.telekom.at] has quit [Quit: No Ping reply in 180 seconds.]
14:37 < diqidoq> this is how you find me also on google, github etc
14:38 -!- naturally [~naturally@unaffiliated/naturally] has joined #ardour
14:38 -!- jaZz_KCS [~64H@ip4d173b94.dynamic.kabel-deutschland.de] has quit [Remote host closed the connection]
14:38 -!- AlexRussia [~Alex@unaffiliated/alexrussia] has quit [Ping timeout: 240 seconds]
14:39 < snadge> im familiar with tr drum sequencers, and their hardware interfaces, and just your regular pianoroll type midi software.. most of them have a drum map mode
14:39 < diqidoq> las: I was realising the replace sequence s///g at first place but then somehow I thought you are referring to sth else *facepalm* sometimes I am not very familiar with some chat abbr. and such thats why I wasnt sure
14:40 -!- ShalokShalom [~quassel@192-164-248-47.adsl.highway.telekom.at] has joined #ardour
14:40 -!- GrusGrus [~Thunderbi@yor3.gofore.com] has quit [Ping timeout: 255 seconds]
14:40 < diqidoq> snadge: its more than that, especially often "how" ... and where, in which layer and how easy to access etc. very much about intuitive interaction, etc. so its not jsut about available things on the table
14:41 < snadge> hydrogen didn't really jump out at me as anything special.. since i don't have any particular fetish for drum pattern sequencing ;)
14:41 < diqidoq> snadge: thats hy I sad its only viewable for those who have ;-)
14:41 < diqidoq> snadge: thats (w)hy I sad its only viewable for those who have ;-)
14:41 < snadge> if your goal is to smash out drum tracks all day.. then yeah, i can think of much more efficient ways to do it than either a hardware pattern sequencer, or a midi notation editor sure
14:43 < diqidoq> In many genres the drum sequence and its micro complexity is a very important center of the whole impression regarding this peace of music
14:43 < snadge> i spent 2 days programing pen pineapple apple pen into a tr-808
14:43 < diqidoq> lol
14:43 < snadge> only to realise at the end of it.. the guy didn't actually use a real tr-808.. he couldn't have
14:44 < speak> diqidoq: As someone who's made a ton of dnb and jungle, very trye :P
14:44 < speak> also *true
14:44 < snadge> as i used up every available pattern bank to sequence the track.. it has a bar with 6 beats, and a section of the song uses triplets on the hi-hats.. but 4/4 for everything else
14:44 < speak> Not sure how good Hydrogen would be for that though
14:45 < speak> I haven't given it a go due to the lack of a plugin I can just use straight in Ardour
14:46 < las> diqidoq: i actually want to see this implemented in ardour as an LV2 or similar plugin
14:46 < las> diqidoq: probably needs some extensions to get really tight plugin GUI integration
14:50 < snadge> i still haven't finished my remix of pen pineapple apple pen.. its 90% done.. and i lost inspiration trying to find the last two instruments
14:54 -!- Ricardus [~rich@2604:6000:ab42:1f00:3cc2:e73a:6e8:a56e] has quit [Ping timeout: 246 seconds]
14:57 -!- Ricardus [~rich@2604:6000:ab42:1f00:80bc:7464:5ace:ba18] has joined #ardour
14:58 -!- dsr1204__ [~dsr1204__@c-73-72-102-18.hsd1.il.comcast.net] has joined #ardour
14:58 < diqidoq> las: I can not more agree. Thats exactly one important part of the letter. nowadays sth like this should have 2 available modes: stand alone and as a plugin. Look at Fxpansion's Guru or follow up Geist(1,2) which I have used for a film score title for the film Equalizer (Denzel Washington)
15:02 < diqidoq> The whole Hydrogen eco-system lacks of many things to achieve such an approach as you can see on Composite. You can't achieve this in OSS world with 2 people as a closed cycle. Thats part of the problem: resources, community building, founding, flexible modern GUI, modern communication ways for developers to interact, website ;-), and many more. It all sticks together. You maybe can write a 5 pages letter 
15:02 < diqidoq> alone about the website of Hydrogen. :-P
15:03 -!- _FrnchFrgg_ [~Icedove@2a01:e35:2e92:63f0:fa16:54ff:fef7:e1a8] has joined #ardour
15:03 -!- henkz [~henke@h-180-60.a193.priv.bahnhof.se] has joined #ardour
15:04 < snadge> what happened to composite, how much work would need to be done to get it up to scratch?
15:04 < diqidoq> but well, its not ok this way in a chat without the guys here (another point I made: where are they? IRC) ... I should think about sending it to mauser.
15:04 < speak> diqidoq: Yeah I think you should send it
15:04 < diqidoq> snadge: a lot.
15:07 < las> diqidoq: you can run any LV2 plugin as a standalone already
15:07 < las> diqidoq: there are several ways to do this
15:11 < diqidoq> speak: las: but first let me start a road map independend from Hydrogen. This shapes better "what to achieve" compared to "what is there" and this maybe makes more clear if Hydrogen is really the right starting point, before stiring up a hornest nest.
15:11 < diqidoq> las: yeah, thats why many things would maybe start from scratch or would make Hydrogen as is obsolete (lv2)
15:11 < typonese> diqidoq: excellent point
15:12 < shamus397> diqidoq: looking forward to the roadmap :-)
15:13 < speak> Honestly the only reason I was looking at Hydrogen was to use it as a sampler, since sequencing imo is fine done in your DAW of choice
15:13 < speak> I never got the sequencer within a sequencer thing
15:13 < las> diqidoq: the big question for me is how well or if it integrates with an Ableton-Live-like pattern/clip model
15:14 < diqidoq> las: for me too :)
15:15 < las> diqidoq: i don't think many people use Live to sequence individual drum hits using their clip launcher
15:15 < las> diqidoq: you would build up 1-8 bar phrases as clips, and then use the clip launcher to sequence them
15:19 < snadge> i really like the amplesound guitar/bass plugins
15:20 -!- dsr1204__ [~dsr1204__@c-73-72-102-18.hsd1.il.comcast.net] has quit [Quit: dsr1204__]
15:23 -!- electro-flinch [~colinf@axicon.plus.com] has quit [Ping timeout: 260 seconds]
15:34 < diqidoq> well, let me shape it the other way around: there is a niche of people who has never been 99% satisfied with any of the new age drum or rythm section developing philosophy on computer based software yet. I can tell you that for granted. Painting events in a completely other corner of the UI than where you switch samples, layers, attacks, releases, sustains, curves, micro timing, midi setting changes, 
15:34 < diqidoq> swing modes, etc. becomes a pain in the speed and work flow of a rythm professional. And these are the guys who need a voice here. Listening to them would inspire many others because it is a very underrated topic. Because of the misunderstanding what it is. Or maybe better sayed: what it can be. Rythm section programming is far beyond what many think of when they put their basedrum and snare layers and 
15:34 < diqidoq> hihats in a midi region, go back to their bank to change some properties and mix them finally (to say it simple). Programming should be one way of many. A rythm guru is fast, and he needs something fast on his finger tips. If there would be a proper software, I would be able to play drums (even on a midi drumstation), record them, split them on keys, mix them with samples, which can be easely exchanged on 
15:34 < diqidoq> the fly while the loop still runs from my library. I can switch many important settings with key commands and near by near interface spots. A rythm expert feels the "breath" of his section before it is finished and he needs to write it down fast. Like an author and his dictaphone. Hydrogen was close to some parts of FxPansions Geist, but only on some points. As often, its all about priorities. Which 
15:34 < diqidoq> functionality has prio and comes first for such an approach. Thats what makes the difference between many computer audio instruments.
15:35 < typonese> this conversation would be great to publish
15:38 -!- _FrnchFrgg_ [~Icedove@2a01:e35:2e92:63f0:fa16:54ff:fef7:e1a8] has quit [Ping timeout: 252 seconds]
15:40 -!- electro-flinch [~colinf@82-132-230-4.dab.02.net] has joined #ardour
15:40 -!- dbolton [~Thunderbi@c-69-245-174-35.hsd1.il.comcast.net] has joined #ardour
15:41 -!- sirriffsalothp [~sirriffsa@212.112.40.45] has joined #ardour
15:45 < diqidoq> additionally there are many other aspects to consider, proprietary file format replacement like rex2 and others, and some common ways need to stay implemented to gain a big enough audience too. Well, I think its too mcuh for here, my road map is better than to fill the chat here ;-)
15:45 -!- electro-flinch [~colinf@82-132-230-4.dab.02.net] has quit [Ping timeout: 240 seconds]
15:46 -!- jpbouza [~Juan@191.85.174.74] has joined #ardour
15:46 -!- dbolton [~Thunderbi@c-69-245-174-35.hsd1.il.comcast.net] has quit [Ping timeout: 240 seconds]
15:46 -!- electro-flinch [~colinf@axicon.plus.com] has joined #ardour
15:49 -!- sirriffsalothp [~sirriffsa@212.112.40.45] has quit [Ping timeout: 240 seconds]
15:51 < shamus397> sounds to me like h2 is about 50-60% there according to your spec :-)
15:53 -!- clark|w [~clark_wil@12.22.75.10] has joined #ardour
15:54 -!- deva [~deva@aasimon.org] has joined #ardour
16:17 -!- magloda [~aht@109-124-147-131.customer.t3.se] has quit [Ping timeout: 240 seconds]
16:21 -!- ShalokShalom [~quassel@192-164-248-47.adsl.highway.telekom.at] has quit [Read error: Connection timed out]
16:23 -!- ShalokShalom [~quassel@192-164-248-47.adsl.highway.telekom.at] has joined #ardour
16:25 -!- pecisk [~peteris@195.13.228.110] has quit [Quit: pecisk]
16:28 -!- gbs [~gbs@unaffiliated/gbs] has quit [Ping timeout: 240 seconds]
16:30 < diqidoq> ok. lets do it via a repo, I think, its the best and fastest way to start off. i'll let you know. need some minutes to set it up. there we all can give our 2 cents to it and shape it later.
16:35 < shamus397> cool
16:37 -!- AlexRussia [~Alex@unaffiliated/alexrussia] has joined #ardour
16:43 < typonese> wow
