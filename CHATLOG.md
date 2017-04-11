--- Log opened Tue Apr 11 00:00:50 2017
00:20 < digidog> las: I saw you mentioning Composite today from the logs. Maybe this is an interesting info for you? -> I had to request the removal of Composite from the Debian repos (sadly I had to because it was never ready for any use) and Gabriel has replied to it. https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=859808#69 ... I think Composite is dead. I am very sorry for all the effort until that.
00:20 < LAbot`> Title: #859808 - composite: Composite not ready for being qualified package of Debian yet. - Debian Bug report logs (at bugs.debian.org)
00:21 < las> digidog: that's a shame
00:21  * las -> mattress
00:25 < digidog> las: yeah it is :/ ... have a good night.
00:38 < snadge> what did composite do better than drmr?
00:42 < snadge> i gave up on trying to master drskit 
...
00:46 < petererer> hmm, drmr, forgot about that. even has my name in the commits :p
00:50 < snadge> Maybe we should have a drskit challenge ;)
00:51 < snadge> make a drum track that sounds good using it.. hehe.. no rules
...
14:26 < diqidoq> las: I wrote a 4 pages long letter addressed to the developer team of Hydrogen with many details and explanations about several aspects regarding the future of Hydrogen and my motivation to write this up, only to come to the final conlusion now, that this letter only shows off that it would maybe even be better to start a project like Hydrogen from scratch :-/ ... I think I won't send it *facepalm*
14:26 < typonese> diqidoq: sometimes that's the best way to come to a conclusion :)
14:27 < diqidoq> typonese: I know
14:27 < typonese> :D
14:27 < diqidoq> typonese: I have many of those unsend letters :-$
14:27 < diqidoq> :)
14:27 < typonese> diqidoq: same :D
14:27 < typonese> so many in the drafts box :D
14:27 < snadge> diqidoq, hydrogen is a drum sequencer right? what is it in particular that you like about it?
14:33 < diqidoq> snadge: its potential to be a fast intuitive rythm programming machine "right on the _qualified_ finger tips". Something I have talked about a lot on conferences over the years. the potential is there and only viewable for those how are really deep into rythm programming and its nature (also old school). I am not talking about "boom clap boom clap". And I have tested a lot on many OS for many projects. 
14:33 < diqidoq> Even for well known US feature film score titles.
...
14:34 < snadge> whats your opinion of something like the roland tr-8, or the boutique tr-09?
14:35 < snadge> i have a couple of classic drum sequencers.. like the tr-808 and tr-909.. but they're absolute garbage ;)
...
14:39 < snadge> im familiar with tr drum sequencers, and their hardware interfaces, and just your regular pianoroll type midi software.. most of them have a drum map mode
...
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
14:58 < diqidoq> las: I can not more agree. Thats exactly one important part of the letter. nowadays sth like this should have 2 available modes: stand alone and as a plugin. Look at Fxpansion's Guru or follow up Geist(1,2) which I have used for a film score title for the film Equalizer (Denzel Washington)
15:02 < diqidoq> The whole Hydrogen eco-system lacks of many things to achieve such an approach as you can see on Composite. You can't achieve this in OSS world with 2 people as a closed cycle. Thats part of the problem: resources, community building, founding, flexible modern GUI, modern communication ways for developers to interact, website ;-), and many more. It all sticks together. You maybe can write a 5 pages letter 
15:02 < diqidoq> alone about the website of Hydrogen. :-P
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
15:34 < diqidoq> well, let me shape it the other way around: there is a niche of people who has never been 99% satisfied with any of the new age drum or rythm section developing philosophy on computer based software yet. I can tell you that for granted. Painting events in a completely other corner of the UI than where you switch samples, layers, attacks, releases, sustains, curves, micro timing, midi setting changes, 
15:34 < diqidoq> swing modes, etc. becomes a pain in the speed and work flow of a rythm professional. And these are the guys who need a voice here. Listening to them would inspire many others because it is a very underrated topic. Because of the misunderstanding what it is. Or maybe better sayed: what it can be. Rythm section programming is far beyond what many think of when they put their basedrum and snare layers and 
15:34 < diqidoq> hihats in a midi region, go back to their bank to change some properties and mix them finally (to say it simple). Programming should be one way of many. A rythm guru is fast, and he needs something fast on his finger tips. If there would be a proper software, I would be able to play drums (even on a midi drumstation), record them, split them on keys, mix them with samples, which can be easely exchanged on 
15:34 < diqidoq> the fly while the loop still runs from my library. I can switch many important settings with key commands and near by near interface spots. A rythm expert feels the "breath" of his section before it is finished and he needs to write it down fast. Like an author and his dictaphone. Hydrogen was close to some parts of FxPansions Geist, but only on some points. As often, its all about priorities. Which 
15:34 < diqidoq> functionality has prio and comes first for such an approach. Thats what makes the difference between many computer audio instruments.
15:35 < typonese> this conversation would be great to publish
15:45 < diqidoq> additionally there are many other aspects to consider, proprietary file format replacement like rex2 and others, and some common ways need to stay implemented to gain a big enough audience too. Well, I think its too mcuh for here, my road map is better than to fill the chat here ;-)
15:51 < shamus397> sounds to me like h2 is about 50-60% there according to your spec :-)
16:30 < diqidoq> ok. lets do it via a repo, I think, its the best and fastest way to start off. i'll let you know. need some minutes to set it up. there we all can give our 2 cents to it and shape it later.
16:35 < shamus397> cool
16:43 < typonese> wow
16:47 < speak> diqidoq: Have you ever tried a sampler called SliceX (a demo ships with FL Studio) ? I think there are a multitude of things that could be learnt from it
16:49 < diqidoq> speak: yes I did. There is so many to say here from my side to get you on the same marker in the map. e.g. forgot to mention that I have really tested ALL available software on any OS to be able to really compare them.
16:49 < speak> Alright
16:50 < speak> I can offer expertise regarding drum programming with SliceX, if needed. I'm thoroughly familiar with it
16:50 < diqidoq> speak: if you know SliceX a bit, feel free to add some points of it you like
16:50 < diqidoq> speak: hah:)
16:50 < diqidoq> speak: thats what i wanted to ask you :)
16:51 < diqidoq> I humbled over slicex from the idea to implement recycle like functionality into plugins like Guru but smaller in footprint and shorter in setup ways.
16:52 < speak> Yeah, gives us the url when you've got the repo set :) I could make bullet points of remarkable features and workflows that I've learnt with SliceX, if that's of any help
16:52 < diqidoq> speak: it is!
16:52 < speak> Great :)
...
