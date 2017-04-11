# LARS - A Linux (lv2) rythm section machine

 + ... for stand alone with in/out management and as a lv2 plugin
 + ... to make Linux pro audio even more sexy than it already is :-)

[!] This document is a work in progress, so please do not feel offended or badly affected by wrongly shaped paragraphs, missing facts or anything weird for you to read until it is finished. I decided to make the progress on this document public to the Open Source community to contribute to it for a faster and more open minded finished result.

Were do I come from for this?
-----------------------------

All has started with a planned and written 5 pages letter to the developers of Hydrogen, a very potential and long time existing drum machine software for Linux. I have - as always - many respect for the hard work which goes into Open Source projects to make software available for professionals working on Linux like this. And I can't say it often enough how often this movement gets misunderstood and the developers and contributors treated badly IMHO. I don't want to go too deep into what community driven open source projects is about and how it works and how to contribute to them. I only want to make clear how much repect I have for this projects and how much I was already involved in such attempts and how hard it is for me to find the right way to go for this issue.

Here is a short excerpt out of an IRC chat were the idea was born to start this document:
```
14:26 < diqidoq> I wrote a 4 pages long letter addressed to the developer team of Hydrogen with many details and explanations about several aspects regarding the future of Hydrogen and my motivation to write this up, only to come to the final conlusion now, that this letter only shows off that it would maybe even be better to start a project like Hydrogen from scratch :-/ ... I think I won't send it *facepalm*
14:26 < typonese> diqidoq: sometimes that's the best way to come to a conclusion :)
14:27 < diqidoq> typonese: I know
14:27 < diqidoq> typonese: I have many of those unsent letters :-$
14:27 < diqidoq> :)
14:27 < typonese> diqidoq: same :D
14:27 < snadge> diqidoq, hydrogen is a drum sequencer right? what is it in particular that you like about it?
14:33 < diqidoq> snadge: its potential to be a fast intuitive rythm programming machine "right on the _qualified_ finger tips". Something I have talked about a lot on conferences over the years. the potential is there and only viewable for those how are really deep into rythm programming and its nature (also old school). I am not talking about "boom clap boom clap". And I have tested a lot on many OS for many projects. 
14:33 < diqidoq> Even for well known US feature film score titles.

14:40 < diqidoq> snadge: its more than that, especially often "how" ... and where, in which layer and how easy to access etc. very much about intuitive interaction, etc. so its not jsut about available things on the table
14:41 < diqidoq> snadge: thats (w)hy I sad its only viewable for those who have ;-)
14:43 < diqidoq> In many genres the drum sequence and its micro complexity is a very important center of the whole impression regarding this peace of music
14:44 < speak> diqidoq: As someone who's made a ton of dnb and jungle, very trye :P
14:46 < las> diqidoq: i actually want to see this implemented in ardour as an LV2 or similar plugin
14:46 < las> diqidoq: probably needs some extensions to get really tight plugin GUI integration
14:58 < diqidoq> las: I can not more agree. Thats exactly one important part of the letter. nowadays sth like this should have 2 available modes: stand alone and as a plugin. Look at Fxpansion's Guru or follow up Geist(1,2) which I have used for a film score title for the film Equalizer (Denzel Washington)
15:02 < diqidoq> The whole Hydrogen eco-system lacks of many things to achieve such an approach as you can see on Composite. You can't achieve this in OSS world with 2 people as a closed cycle. Thats part of the problem: resources, community building, founding, flexible modern GUI, modern communication ways for developers to interact, website ;-), and many more. It all sticks together. You maybe can write a 5 pages letter 
15:02 < diqidoq> alone about the website of Hydrogen. :-P
15:04 < diqidoq> but well, its not ok this way in a chat without the guys here (another point I made: where are they? IRC) ... I should think about sending it to mauser.
15:04 < speak> diqidoq: Yeah I think you should send it
15:04 < diqidoq> snadge: a lot.
15:07 < las> diqidoq: you can run any LV2 plugin as a standalone already
15:07 < las> diqidoq: there are several ways to do this
15:11 < diqidoq> speak: las: but first let me start a road map independend from Hydrogen. This shapes better "what to achieve" compared to "what is there" and this maybe makes more clear if Hydrogen is really the right starting point, before stiring up a hornest nest.
15:11 < diqidoq> las: yeah, thats why many things would maybe start from scratch or would make Hydrogen as is obsolete (lv2)
15:11 < typonese> diqidoq: excellent point
15:12 < shamus397> diqidoq: looking forward to the roadmap :-)
15:13 < las> diqidoq: the big question for me is how well or if it integrates with an Ableton-Live-like pattern/clip model
15:14 < diqidoq> las: for me too :)
15:15 < las> diqidoq: i don't think many people use Live to sequence individual drum hits using their clip launcher
15:15 < las> diqidoq: you would build up 1-8 bar phrases as clips, and then use the clip launcher to sequence them
15:34 < diqidoq> well, let me shape it the other way around: there is a niche of people who has never been 99% satisfied with any of the new age drum or rythm section developing philosophy on computer based software yet. I can tell you that for granted. Painting events in a completely other corner of the UI than where you switch samples, layers, attacks, releases, sustains, curves, micro timing, midi setting changes, 
15:34 < diqidoq> swing modes, etc. becomes a pain in the speed and work flow of a rythm professional. And these are the guys who need a voice here. Listening to them would inspire many others because it is a very underrated topic. Because of the misunderstanding what it is. Or maybe better sayed: what it can be. Rythm section programming is far beyond what many think of when they put their basedrum and snare layers and 
15:34 < diqidoq> hihats in a midi region, go back to their bank to change some properties and mix them finally (to say it simple). Programming should be one way of many. A rythm guru is fast, and he needs something fast on his finger tips. If there would be a proper software, I would be able to play drums (even on a midi drumstation), record them, split them on keys, mix them with samples, which can be easely exchanged on 
15:34 < diqidoq> the fly while the loop still runs from my library. I can switch many important settings with key commands and near by near interface spots. A rythm expert feels the "breath" of his section before it is finished and he needs to write it down fast. Like an author and his dictaphone. Hydrogen was close to some parts of FxPansions Geist, but only on some points. As often, its all about priorities. Which 
15:34 < diqidoq> functionality has prio and comes first for such an approach. Thats what makes the difference between many computer audio instruments.
15:45 < diqidoq> additionally there are many other aspects to consider, proprietary file format replacement like rex2 and others, and some common ways need to stay implemented to gain a big enough audience too. Well, I think its too mcuh for here, my road map is better than to fill the chat here ;-)
´´´

Were are we now?
----------------

 + There are some examples of "close to what it can be" in the 

well, let me shape it the other way around: there is a niche of people who has never been 99% satisfied with any of the new age drum or rythm section developing philosophy on computer based software yet. I can tell you that for granted. Painting events in a completely other corner of the UI than where you switch samples, layers, attacks, releases, sustains, curves, micro timing, midi setting changes, swing modes, etc. becomes a pain in the speed and work flow of a rythm professional. And these are the guys who need a voice here. Listening to them would inspire many others because it is a very underrated topic. Because of the misunderstanding what it is. Or maybe better sayed: what it can be. Rythm section programming is far beyond what many think of when they put their basedrum and snare layers and hihats in a midi region, go back to their bank to change some properties and mix them finally (to say it simple). Programming should be one way of many. A rythm guru is fast, and he needs something fast on his finger tips. If there would be a proper software, I would be able to play drums (even on a midi drumstation), record them, split them on keys, mix them with samples, which can be easely exchanged on the fly while the loop still runs from my library. I can switch many important settings with key commands and near by near interface spots. A rythm expert feels the "breath" of his section before it is finished and he needs to write it down fast. Like an author and his dictaphone. Hydrogen was close to some parts of FxPansions Geist, but only on some points. As often, its all about priorities. Which functionality has prio and comes first for such an approach. Thats what makes the difference between many computer audio instruments.

Additionally there are many other aspects to consider, proprietary file format replacement like rex2 and others, and some common ways need to stay implemented to gain a big enough audience too. Well, I think its too much for here, my road map is better than to fill the chat here ;-)
