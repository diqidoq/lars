# Excerpts of a chat history log from the #ardour IRC channel on 11.04.2017

You maybe can read and follow this document better in the [raw view here](https://raw.githubusercontent.com/diqidoq/lars/master/CHATLOG.md).

<pre>
 + --- Log opened Tue Apr 11 00:00:50 2017
 + 00:20 < digidog> las: I saw you mentioning Composite today from the logs. Maybe this is an interesting info for you? -> I had to request the removal of Composite from the Debian repos (sadly I had to because it was never ready for any use) and Gabriel has replied to it. https://bugs.debian.org/cgi-bin/bugreport.cgi?bug=859808#69 ... I think Composite is dead. I am very sorry for all the effort until that. Title: #859808 - composite: Composite not ready for being qualified package of Debian yet. - Debian Bug report logs (at bugs.debian.org)
 + 00:21 < las> digidog: that's a shame
 + 00:25 < digidog> las: yeah it is :/
 + 00:38 < snadge> what did composite do better than drmr?
 + 00:42 < snadge> i gave up on trying to master drskit 
 + ...
 + 00:46 < petererer> hmm, drmr, forgot about that. even has my name in the commits :p
 + 00:50 < snadge> Maybe we should have a drskit challenge ;)
 + 00:51 < snadge> make a drum track that sounds good using it.. hehe.. no rules
 + ...
 + 14:26 < diqidoq> las: I wrote a 4 pages long letter addressed to the developer team of Hydrogen with many details and explanations about several aspects regarding the future of Hydrogen and my motivation to write this up, only to come to the final conlusion now, that this letter only shows off that it would maybe even be better to start a project like Hydrogen from scratch :-/ ... I think I won't send it *facepalm*
 + 14:26 < typonese> diqidoq: sometimes that's the best way to come to a conclusion :)
 + 14:27 < diqidoq> typonese: I know
 + 14:27 < typonese> :D
 + 14:27 < diqidoq> typonese: I have many of those unsend letters :-$
 + 14:27 < diqidoq> :)
 + 14:27 < typonese> diqidoq: same :D
 + 14:27 < typonese> so many in the drafts box :D
 + 14:27 < snadge> diqidoq, hydrogen is a drum sequencer right? what is it in particular that you like about it?
 + 14:33 < diqidoq> snadge: its potential to be a fast intuitive rythm programming machine "right on the _qualified_ finger tips". Something I have talked about a lot on conferences over the years. the potential is there and only viewable for those how are really deep into rythm programming and its nature (also old school). I am not talking about "boom clap boom clap". And I have tested a lot on many OS for many projects. 
 + 14:33 < diqidoq> Even for well known US feature film score titles.
 + ...
 + 14:34 < snadge> whats your opinion of something like the roland tr-8, or the boutique tr-09?
 + 14:35 < snadge> i have a couple of classic drum sequencers.. like the tr-808 and tr-909.. but they're absolute garbage ;)
 + ...
 + 14:39 < snadge> im familiar with tr drum sequencers, and their hardware interfaces, and just your regular pianoroll type midi software.. most of them have a drum map mode
 + ...
 + 14:40 < diqidoq> snadge: its more than that, especially often "how" ... and where, in which layer and how easy to access etc. very much about intuitive interaction, etc. so its not jsut about available things on the table
 + 14:41 < snadge> hydrogen didn't really jump out at me as anything special.. since i don't have any particular fetish for drum pattern sequencing ;)
 + 14:41 < diqidoq> snadge: thats hy I sad its only viewable for those who have ;-)
 + 14:41 < diqidoq> snadge: thats (w)hy I sad its only viewable for those who have ;-)
 + 14:41 < snadge> if your goal is to smash out drum tracks all day.. then yeah, i can think of much more efficient ways to do it than either a hardware pattern sequencer, or a midi notation editor sure
 + 14:43 < diqidoq> In many genres the drum sequence and its micro complexity is a very important center of the whole impression regarding this peace of music
 + 14:43 < snadge> i spent 2 days programing pen pineapple apple pen into a tr-808
 + 14:43 < diqidoq> lol
 + 14:43 < snadge> only to realise at the end of it.. the guy didn't actually use a real tr-808.. he couldn't have
 + 14:44 < speak> diqidoq: As someone who's made a ton of dnb and jungle, very trye :P
 + 14:44 < speak> also true
 + 14:44 < snadge> as i used up every available pattern bank to sequence the track.. it has a bar with 6 beats, and a section of the song uses triplets on the hi-hats.. but 4/4 for everything else
 + 14:44 < speak> Not sure how good Hydrogen would be for that though
 + 14:45 < speak> I haven't given it a go due to the lack of a plugin I can just use straight in Ardour
 + 14:46 < las> diqidoq: i actually want to see this implemented in ardour as an LV2 or similar plugin
 + 14:46 < las> diqidoq: probably needs some extensions to get really tight plugin GUI integration
 + 14:50 < snadge> i still haven't finished my remix of pen pineapple apple pen.. its 90% done.. and i lost inspiration trying to find the last two instruments
 + 14:58 < diqidoq> las: I can not more agree. Thats exactly one important part of the letter. nowadays sth like this should have 2 available modes: stand alone and as a plugin. Look at Fxpansion's Guru or follow up Geist(1,2) which I have used for a film score title for the film Equalizer (Denzel Washington)
 + 15:02 < diqidoq> The whole Hydrogen eco-system lacks of many things to achieve such an approach as you can see on Composite. You can't achieve this in OSS world with 2 people as a closed cycle. Thats part of the problem: resources, community building, founding, flexible modern GUI, modern communication ways for developers to interact, website ;-), and many more. It all sticks together. You maybe can write a 5 pages letter 
 + 15:02 < diqidoq> alone about the website of Hydrogen. :-P
 + 15:04 < snadge> what happened to composite, how much work would need to be done to get it up to scratch?
 + 15:04 < diqidoq> but well, its not ok this way in a chat without the guys here (another point I made: where are they? IRC) ... I should think about sending it to mauser.
 + 15:04 < speak> diqidoq: Yeah I think you should send it
 + 15:04 < diqidoq> snadge: a lot.
 + 15:07 < las> diqidoq: you can run any LV2 plugin as a standalone already
 + 15:07 < las> diqidoq: there are several ways to do this
 + 15:11 < diqidoq> speak: las: but first let me start a road map independend from Hydrogen. This shapes better "what to achieve" compared to "what is there" and this maybe makes more clear if Hydrogen is really the right starting point, before stiring up a hornest nest.
 + 15:11 < diqidoq> las: yeah, thats why many things would maybe start from scratch or would make Hydrogen as is obsolete (lv2)
 + 15:11 < typonese> diqidoq: excellent point
 + 15:12 < shamus397> diqidoq: looking forward to the roadmap :-)
 + 15:13 < speak> Honestly the only reason I was looking at Hydrogen was to use it as a sampler, since sequencing imo is fine done in your DAW of choice
 + 15:13 < speak> I never got the sequencer within a sequencer thing
 + 15:13 < las> diqidoq: the big question for me is how well or if it integrates with an Ableton-Live-like pattern/clip model
 + 15:14 < diqidoq> las: for me too :)
 + 15:15 < las> diqidoq: i don't think many people use Live to sequence individual drum hits using their clip launcher
 + 15:15 < las> diqidoq: you would build up 1-8 bar phrases as clips, and then use the clip launcher to sequence them
 + 15:19 < snadge> i really like the amplesound guitar/bass plugins
 + 15:34 < diqidoq> well, let me shape it the other way around: there is a niche of people who has never been 99% satisfied with any of the new age drum or rythm section developing philosophy on computer based software yet. I can tell you that for granted. Painting events in a completely other corner of the UI than where you switch samples, layers, attacks, releases, sustains, curves, micro timing, midi setting changes, 
 + 15:34 < diqidoq> swing modes, etc. becomes a pain in the speed and work flow of a rythm professional. And these are the guys who need a voice here. Listening to them would inspire many others because it is a very underrated topic. Because of the misunderstanding what it is. Or maybe better sayed: what it can be. Rythm section programming is far beyond what many think of when they put their basedrum and snare layers and 
 + 15:34 < diqidoq> hihats in a midi region, go back to their bank to change some properties and mix them finally (to say it simple). Programming should be one way of many. A rythm guru is fast, and he needs something fast on his finger tips. If there would be a proper software, I would be able to play drums (even on a midi drumstation), record them, split them on keys, mix them with samples, which can be easely exchanged on 
 + 15:34 < diqidoq> the fly while the loop still runs from my library. I can switch many important settings with key commands and near by near interface spots. A rythm expert feels the "breath" of his section before it is finished and he needs to write it down fast. Like an author and his dictaphone. Hydrogen was close to some parts of FxPansions Geist, but only on some points. As often, its all about priorities. Which 
 + 15:34 < diqidoq> functionality has prio and comes first for such an approach. Thats what makes the difference between many computer audio instruments.
 + 15:35 < typonese> this conversation would be great to publish
 + 15:45 < diqidoq> additionally there are many other aspects to consider, proprietary file format replacement like rex2 and others, and some common ways need to stay implemented to gain a big enough audience too. Well, I think its too mcuh for here, my road map is better than to fill the chat here ;-)
 + 15:51 < shamus397> sounds to me like h2 is about 50-60% there according to your spec :-)
 + 16:30 < diqidoq> ok. lets do it via a repo, I think, its the best and fastest way to start off. i'll let you know. need some minutes to set it up. there we all can give our 2 cents to it and shape it later.
 + 16:35 < shamus397> cool
 + 16:43 < typonese> wow
 + 16:47 < speak> diqidoq: Have you ever tried a sampler called SliceX (a demo ships with FL Studio) ? I think there are a multitude of things that could be learnt from it
 + 16:49 < diqidoq> speak: yes I did. There is so many to say here from my side to get you on the same marker in the map. e.g. forgot to mention that I have really tested ALL available software on any OS to be able to really compare them.
 + 16:49 < speak> Alright
 + 16:50 < speak> I can offer expertise regarding drum programming with SliceX, if needed. I'm thoroughly familiar with it
 + 16:50 < diqidoq> speak: if you know SliceX a bit, feel free to add some points of it you like
 + 16:50 < diqidoq> speak: hah:)
 + 16:50 < diqidoq> speak: thats what i wanted to ask you :)
 + 16:51 < diqidoq> I humbled over slicex from the idea to implement recycle like functionality into plugins like Guru but smaller in footprint and shorter in setup ways.
 + 16:52 < speak> Yeah, gives us the url when you've got the repo set :) I could make bullet points of remarkable features and workflows that I've learnt with SliceX, if that's of any help
 + 16:52 < diqidoq> speak: it is!
 + 16:52 < speak> Great :)
 + ...
 --- Log opened Wed Apr 12 00:00:36 2017
00:04 < rgareus> digidog: the linux audio session handler
00:04 < rgareus> hasn't that been dead since 10 years?
00:05 < digidog> rgareus: has it ? ... o.@
00:05 < rgareus> pretty much since NSM
00:07 < digidog> rgareus: sometimes it is hart to tell apart if somethings has a break, sleeps, or is dead in the Linux universe ... xD
00:07 < rgareus> I recall adding support for it to xjadeo in 2006/8 and removing it in 2014
00:08 < rgareus> because it didn't compile anymore 
00:08 < digidog> rgareus: ok
00:08 < rgareus> maybe +/- 1 year. I don't remember
00:09 < rgareus> digidog: it's one of those  "nice idea, but too geeky for any real-world-use" things :(
00:11 < digidog> rgareus: sounds like approaching to me :p
...
00:33 < rgareus> snadge: the DG devs sometimes hang out here on #ardour
00:34 < snadge> i dont think it was drskit though
00:34 < rgareus> chaot4  is online actually
00:37 < snadge> maybe they can do a new kit with way less bleed and reverb ;)
00:38 < snadge> you can always add reverb.. but you cant easily take it out
00:39 < snadge> ill have to keep looking.. but i literally dont know what to do with 13 channels of drums with each drum in every mic
00:40 < snadge> i guess you adjust balance, eq and compress like any other mix
00:41 < snadge> i had a really bad time with it though :P 
...
00:52 < snadge> drskit is newer and a lot of effort was put into it... but...
00:54 < snadge> i was trying to get a jazz sound out if it like the description insisted was possible ;)
00:55 < snadge> I tried to remove that from the equation by recording just a kick drum track
00:56 < snadge> and flattening it to a single mono audio region
00:57 < snadge> but i couldn't get that to sound good either
00:58 < snadge> It needs compression.. a snare has a massive attack.. which dwarfs the detail in the tail
00:59 < snadge> which i guess is partly why you mic the top and bottom of a snare
01:00 < digidog> snadge: your guess is right
01:02 < digidog> snadge: but also because of the different proliferation of different frequence dominatings away from the hit
01:03 < snadge> Yeah i guess the snare is unique in the sense that youre interested in the detail in the decay because of the springs
01:04 < snadge> whereas a kick or tom has a less interesting decay
01:22 < digidog> snadge: have you fetched the last comment here of the road map about drumbeat programming experience improvement? The first really early draft/questionaire is there.
01:25 < snadge> no?
01:28 < digidog> snadge: https://diqidoq.github.io/lars
...
14:03 < digidog> speak: you yesterday sad at 16:50 "I can offer expertise regarding drum programming with SliceX, if needed. I'm thoroughly familiar with it". Would you mind to post an issue on the road map repo I started yesterday? We need such reports from many of such instruments to clarify if we are on the right tracks or rather off the track..
14:08 < digidog> speak: the link to the web view of this paper is here (still in progress) https://diqidoq.github.io/lars -  Path to the issues is here: https://github.com/diqidoq/lars/issues
14:10 < digidog> It took me half the day of yesterday to do this paper thing *facepalm* while I actually have really spare time atm. Not even sure yet if this will be any helpful soon. But it is very important that anybody who would like to comment on this reads the whole paper first. Many complains are already addressed there.
14:12 < digidog> I would love to see a strong coupling to Ardour and to be clear (its not about sth like EZ Drummer or time and loop matching of audio). Its about drumbeat and rhythmsection design in a seperated enviroment because of its own special needs.
14:12 < typonese> digidog: heads up
14:12 < typonese> 11:45 < ahellquist> rgareus, (and digidoq but he is offline) I live in the same city as Toontrack EZdrummer HQ and have been close to write them a letter to bump them into porting their stuff to linux. maybe we could do something clever if we have people volunteering to help porting ... ?
14:12 < typonese> 11:46 < ahellquist> rgareus, I might even know someone working there. at least i know people playing instruments for them like a drummer that contributed to the sample library
14:14 < speak> Heya digidog ! Thank you I did check that page out but you had left at that point
14:15 < digidog> typonese: porting EZ Drummer would be great! Thanks for chiming in. But it is just another issue actually, if it is ok for you ;-) because what I am after is sth more programming engineering like and free of any UI and drag and drop patterns, etc. It wasn't accidently, that I came from Hydrogen letter to this paper ;-)
14:15 < speak> digidog: I will also say: I think the paper needs pretty heavy editing to really make the point clear and solid
14:15 < typonese> digidog: actually that was all from ahellquist. you'll want to check in with him i just wanted to make sure you got the messages :)
14:15 < digidog> speak: hey !
14:16 < digidog> speak: great I am fine with any suggestions. Please put them here if it is ok for you: https://github.com/diqidoq/lars/issues/1
14:16 < typonese> yeah i was thinking i'd like to do a bit of proof reading for the paper. typos and grammar and whatnot
14:16 < speak> Grand, thanks digidog!
14:16 < digidog> speak: Which version do you read? I did a lot of more over the night later ...
14:17 < typonese> oh yeah that's right you added nice screenshot as well
14:17 < speak> digidog: Ooh I'm not sure, might've been an earlier draft. I can check it out again :)
14:18 < digidog> typonese: yeah :-/ my typo is horrable atm, I know. Its a very floppy laptop keyboard, not my native tongue, and I am very tired atm after many weeks 2-3 hours sleep per day.
14:18 < typonese> digidog: hey no problem that's what volunteers are for :)
14:18 < digidog> typonese: I just wanted to make a start, because I knew, if I don't do it now, I will never do it.
14:18 < typonese> i've been a bit of a mess myself after a lot of work, no sleep, and then the lorry attack on friday in stockholm
14:19 < speak> digidog: Yeah that is absolutely smart
14:19 < typonese> digidog: yep i understand :)
14:19 < typonese> no complaints from me :D
14:19 < speak> digidog: I might query about some of the parts, so that we can have more immediate dialogue about it
14:19 < speak> *query you
14:21 < speak> Also a question that I don't know the answer for: Is the current state of drum machine / samplers on linux a lack of ideas, or a lack of coders with motivation & time?
14:23 < typonese> i forgot there's a video link that las and rgareus suggested to watch. need to check that out as well
14:23 < digidog> speak: thanks for chiming in! to your Q: a mix of both. but please form such questions over there in the issue queue. it would live things up
14:24 < speak> Cool digidog, I'll leave rest of the suggestions in the issue queue
14:24 < digidog> we can discuss the close coupling (if useful) to Ardour here.
14:25 < digidog> speak: awesome! thank you very much
14:25 < digidog> typonese: omg! what a lorry attack? o.O didn't know ...
14:26 < ahellquist> https://www.youtube.com/watch?v=usD7mWWWmoE
14:26 < digidog> ahellquist: yeah, I know about that. its awesome. I wanted to show the link yesterday when snadge was after the parts a snare is made of.
14:26 < ahellquist> digidog, ok, sorry
...
14:27 < digidog> ahellquist: no need to sorry. its an awesome attempt I wish them they will grow with it. A drum synth with complex synthesis is very interesting and very inspiring. also for other instruments.
14:28 < ahellquist> digidog, agreed
14:28 < typonese> ahellquist: hey that might be it yes thank you
14:28 < ahellquist> typonese, np
14:28 < snadge> yeah that is pretty awesome
14:29 < typonese> digidog: yeah it happened last friday close to where i live so meh
14:29 < snadge> do they sell a vst of this kit yet? lol
14:29 < speak> typonese: wow that's fough
14:29 < speak> er
14:29 < speak> *rough
14:29 < digidog> typonese: oh ... -.- I see ... are your relatives and friends ok?
14:29 < typonese> rgareus: lovely. my dark humour approves 
14:30 < typonese> digidog: thank you yes :)
14:30 < snadge> ahh okay its not finished yet.. still, dat snare
14:30 < typonese> speak: yeah pretty insane stuff eh?
14:32 < rgareus> digidog: joyful as I am, today I'm tempted to say: Now you only need a team of programmers, a small resaerch team, some drummers to create a pattern library, and 5-10 years full time.
14:33 < digidog> rgareus: thats what I thought yesterday :) ... but some parts are already there ;-)
...
14:40 < digidog> rgareus: but as I sad in the papers: Here we can have a growing overview and I invite any project to whom it may concern to shameless steel any idea, which has been shaped here. It’s not about business or medding and pomposity here. It’s all about improvement for the rhythm nerds.
14:40 < digidog> SO I will put in all what we have here, no matter if it goes into a fictive LARS project or somewhere else existing.
14:40 < rgareus> digidog: fair enough. and you have to start somewhere.
14:42 < snadge> it seems like the effort might be justified.. just looking at whats available, people seem to be using step sequencers and standard notation... asides from hydrogen, what is there other than standard notation type sequencers/daws
14:42 < digidog> snadge: would you mind to put this question into here? : https://github.com/diqidoq/lars/issues/1
14:43 < digidog> snadge: copy paste is enough. we need all thoughts collected there. thats the reason for that repo actually ;-9
14:44 < rgareus> seq24 is pretty cool
14:44 < snadge> i've only heard that its cool.. i should probably fire it up one of these days.. because editing looping patterns, is cool
14:45 < snadge> its a workflow that i've always wanted to explore further.. but im taking a detour with DAWs instead.. gotta learn to mix :/
14:47 < snadge> i was dead set keen on analog mixing and avoiding daws entirely.. using outboard effects and hardware sequencers etc.. its actually kinda fun, i recommend it
14:47 < digidog> rgareus: I still laugh about rythm / rhythm ... it was almost everywhere *facepalm* ... thanks for your fast note on this.
14:47 < digidog> snadge: we do a lot of it here ;)
...
14:49 < digidog> rgareus: seq24 ... yes it is. It lacks some important parts to be ready but the way and concept it is, also in its minimalizn kind of feel, this is absolutely favouritable and distraction free. Thats why I recommend to look on it in the papers.
...
14:50 < digidog> rgareus: its maybe because I know what it can make with you to work this way (from the good old days) :-)
14:51 < snadge> digidog, what are your thoughts on hardware pattern based sequencers?
14:51 < snadge> like the tr-8
14:52 < snadge> i've never really gotten into it much.. but im sure you can cut and paste individual drum parts etc.. and i kinda get how fiddly and annoying it can be with anything more complicated than dance 4/4 type arrangements
14:54 < digidog> snadge: it would break the mold here to get into this topic. There are some real attracting points to make on them, but it should be put in context to the flaws, but I can't do it now.
14:56 < snadge> yeah .. im just looking at it from the other way.. i dont think a lot of music producers really give a lot of thought to exactly how their beat is constructed.. i mean.. a drum track is a sequence of patterns.. thats it.. you copy paste them, click them in, tap them in, record it via a midi drum kit.. there's a heap of existing ways to do it
...
15:02 < diqidoq> No matter what I set up on Irrsi, it always logs me back in with digidog, not with with diqidoq, damn it.
...
15:21 < speak> rgareus: Yes hah that was the question I had in mind (re: having a bunch of programmers etc)
15:21 < speak> But yeah sounds like diqidoq doesn't have any unrealistic expectations, which really is key here!
15:35 < diqidoq> speak: indeed, because "if" ..., then ..., it wouldn't be my first dev project initiation ;-) ... but as the draft/paper states clearly already on many places: it's not about reinventing the wheel nor about a new instrument road map at first place. it's a brain pool for improvement. Where this gonna happen depends on where is the best starting point for it. And something important I already have stated 
15:35 < diqidoq> here and on many other places again and again: Any attempt is only worth a word if it is made for lasting long. A problem I have stated so many times regarding OSS projects, that I even get fluff on the mouth by thinking about it. 
15:40 < snadge> thanks for flying with united ;0
15:45 < diqidoq> speak: this is maybe one of the most underrated aspects of such projects because it is one of the hardest goals to achieve. Nobody can really feel that who wasn't in that situation himself for a long enough time. Sustaining a big project like Ardour for example... Keeping it up all the time. And this is why I have so much respect for project leads like Paul and others. Because I know what it means to keep a stiff upper lip.
15:46 < typonese> amen :)
15:49 < speak> diqidoq: Well said!
15:49 < speak> Yeah I'll add to an issue as soon as I have bit of time
15:50 < diqidoq> speak: thx!
...
16:35 < diqidoq> speak: typonese: do not bother too much about how you layout your comments on LARS over there. I don't want you to leave too much time on it. Only try to be not offending to anybody. Drop in some ideas like in the chat here. Sadly I can't always copy paste the chat parts here all the time, so it would be great if you just log in on Github and put it right under the topic of the first issue started if this is the fastest way.
16:41 < diqidoq> speak: typonese: oops that can possibly become a misunderstanding! sorry!! :/ these are too different contexts actually! nobody WAS already offending. I just meant: feel free to layout your thoughts fast like in the chat here...
16:42 < typonese> diqidoq: hey thanks for that :) yeah i'll make sure to post questions or what have you on the git :D
16:43 < diqidoq> typonese: sorry and thanks! :)
16:46 < typonese> diqidoq: hey no problem, nobody got hurt :D thanks for clearing up :)
16:46 < petererer> seq64? Nintendo 64 stuff?
16:48 < diqidoq> petererer: there are many forks of seq24 around like seq64, seq42, etc.
16:49 < petererer> yeah but seq64 is specifically... https://github.com/sauraen/seq64
16:49 < petererer> sequencer64 makes more sense ofc :)
16:49 < diqidoq> petererer: but I am pretty sure you were able to run seq24 on a nintendo box ... xD
16:55 < petererer> so which is best? ;p
16:59 < diqidoq> :)
...
 </pre>
