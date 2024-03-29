> From a long way of testing and writing bug reports, filing issues, up to writing long letters to project maintainers, which have been never send because of doubts of mine if this is the right starting point, I came to the conclusion to start this road map like a questionaire for an *idea* ... It's just a twinkle in an eye ... and by chance it became a thing ... and answers to the name: ...

# LARS (Linux advanced rhythm section *machine*)

 + a flexible sample triggering (step sequencer including?) Linux audio instrument to manage/support complex drumbeat sound and rhythm section programming.
 + its not about real live drum simulation, its about innovative drumbeat and rhythm section conducting. 
 + as a *stand alone* machine with in/out management.
 + as a lv2 plugin.
 + to make Linux pro audio even more sexy than it already is :-)
 + to integrate perfect with awesome projects like my favourite Ardour and JACK or Mixbus, but also with Qtractor, LMMS and others.
 + to really show off and support the advantages from Linux OS modular audio concepts and work flows over other OS.
 + to fulfil a dream of mine: to finally fill the gap of real intuitive and useful rhythm section programming for the pros on their __qualified__ fingertips.
 
## Feature road map

>  Basically it's all about drumbeat and rhythm programming improvement. It doesn't matter on which projects: on existing ones or on newly to initiate ones ... please join with [your 2 cents](https://github.com/diqidoq/lars/issues/1).

 + a simple, flat and intuitive UI with pro user requirements:
   + neat and clean with only a few logical and useful flat color highlights.
   + no fancy, no pictures of instruments or virtual mixer toys and such kindergarden.
   + flexible, configurable and stretchable flat design.
   + option to choose between stack and float window mode and flexible boxes.
   + real smart key commands (multi tap, combinations, mappable).
   + simple zoom in/out on sample shapes, envelopes, midi sequences.
 + embrace as much hardware controller as possible, use standards, enhance them, thighten them.
 + no useless tools and toys which only limit your possible expressions.
 + real managable and groupable and smart sound layers for dynamic triggering and sample sound mix creation.
 + envelopes (attack,release,sustain,relative to filters) and smart envelope grouping logic (also for whole layers, groups, flow and punch grouping/design).
 + _if we agree on an included_ midi step sequencer, let it please be smart and intuitive:
   + accurate and precise timing like a clockwork.
   + horizontal and vertical timeline views (classic midi drum, event list, and tracker view)
   + smart and editable multi key commands.
   + straight-to-the-goal way of event management. no fuzz, simple click>add, doubleclick>remove, etc.
   + intuitive and fast trigger setups.
   + drum and rhythm centric functionality and standards (notes, events, look, feel, handling)
   + take a deeper look at [Hydrogen](http://hydrogen-music.org)s pattern designer, [seg24](http://www.filter24.org/seq24/seq24.large.png), Guru and its precessor [FxPansion Geist](https://www.youtube.com/watch?v=uENbCYlEkR0).
   + rhythm step pattern templates (only for musician centric accents and swing types, no kiddy library fuzz)
   + group and layer based swing faders.
   + fast prebuild prenote/upbeat/kickoff and syncope adding options (key commands, presets)
   + multiple sync/latch options
   + advanced micro timing functionality (also group, pattern and layer based)
   + and many more
 + synth (humble) and noise (pink,white) addition feature for breath and rhythm instrument design.
 + many import/export features into every possible format.
   + embracing standarts.
   + drag and drop of samples and midi regions/patterns into DAW.
   + easy rendering of sf and other file formats for resuse.
 + loop slice and chop support incl. triggering slices of loops on certain keys.
 + typical *tricks* at hand for rhythm section pros (more here to come after shaping the papers).
 + fast and intuitive sample management:
   + easy replacement of samples on the fly (key command combi on selected event with up/down while loop plays)
   + option to keep replace settings with samples or keep them for next sample
   + dim and raise switch to review very loud or very soft samples in context
   + simple copy paste samples and/or its settings from here to there
 + distraction free editing
   + values by mouse wheel, touch slide, gestures, keys, automation by painting, moving, start/end point setting
   + priority mode for key commands if LARS is in background
   + no detours for common tasks
   + easy value readablilty
   + tips & links management to a centralized community online manual
 + simple backup button to get folder with a bunch of usefile common files (midi, samples, patterns, setup, sf, rendered wav)
 + a.s.o ... (list not complete)
 
 ![example-snapshot-of-geist](https://www.fxpansion.com/site/assets/files/11949/geist2_browser-pattern-1.png)
 ![step sequencer example with individual samples per event](https://a.fsdn.com/con/app/proj/cythar-sequenzer/screenshots/drumset_cythar_sequenzer.png/1)
 ![minimal-step-sequencer-example--seq24](http://www.filter24.org/seq24/seq24.large.png)
 ![tremor-own-rare-step-sequencing-sound-shaping-concept](https://macprovid.vo.llnwd.net/o43/hub/media/1093/7163/tremor_2.png)
 ![motu-bpm](http://www.delamar.de/wp-content/uploads/2010/08/MOTU-BPM-1.5.jpeg)
 ![akai-renaissance](http://kb.inmusicbrands.com/media/images/akai/akai_mpc_renaissance_bpm_2.png)
 ![landing-large](http://sugar-bytes.de/images/Egoist/landinglarge.jpg)
 ![good-knobs](https://static.kvraudio.com/i/b/izotope-ozone-7-standard-standalone-dynamics.jpg)

This document is a work in progress, a crib, a very early and first note. So please do not feel offended or badly affected by wrongly shaped paragraphs, typo, missing facts, missing options not mentioned or already around in other projects which are filling some of the points here, or anything weird for you to read until it is finished. A strong and self-aware feature comparision-list is planned and one of the main reasons for that paper. Also read the [CHATLOG.md](CHATLOG.md). I decided to make the progress on this document public to the Open Source community to contribute to it for a faster and more open minded finished result.

It all happend by accident, when I was investigating for drum pattern exchange, practical minimalism on old school step sequencers and drum sample design over the last days under Linux with some discouraging results. And it wasn't planned. My experience from many pro audio software over 20 years on almost any OS lead me to the impression that non of the existing fills the gap for real pros really. Some come close, but they fail on some important parts. Many concentrate on fancy selling polish but lack some innovative work flow enhancements. Some have awesome UI but a few features. Others have interesting starting points but it never felt like finished. I think this paper makes sense because discussing all that on all discussion places of all possible exisitng projects would be a killer. Here we can have a growing overview and I invite any project to whom it may concern to shameless steel any idea, which has been shaped here. 

> It's not about business or medding and pomposity here. It's all about improvement for the rhythm nerds. 

### Another important point to make ...
 
And! ... **It's not about forking and splitting the hell out of a community.** I am an advocate for building, grouping and motivating communities and to **bundle forces**, not too loose them. So if anything of this white paper here can go into something else or can be re-merged into another existing project, I am absolutely fine with that. It's all about improvement. But until then I try to prevent to stir up a hornets' nest by trying to discuss this dream inside of existing projects yet, since there are too many aspects which can get in the way of the road maps of other projects.

## Where do I want to go with this?

All has started with a planned and written pages long [letter to the developers of Hydrogen](LETTER_TO_HYDROGEN.md), a very potential and long time existing drum machine software for Linux. I have - as always - many respect for the hard work which goes into Open Source projects to make software available for professionals working on Linux like this. And I can't say it often enough how often this movement gets misunderstood and the developers and contributors treated badly IMHO. I don't want to go too deep into what community driven open source projects is about and how it works and how to contribute to them. I only want to make clear how much repect I have for this projects and how much I was already involved in such attempts and how hard it is for me to find the right way to go for this issue.

## What is the motivation ?

Well, let me shape it the other way around: there is a *niche* of people who has never been 99% satisfied with any of the new age drum or __rhythm section developing philosophy on computer based software__ yet. I can tell you that for granted. Painting events in a grid which is neither fish, nor flesh, nor good red herring in a completely other corner of the UI than where you switch samples, layers, attacks, releases, sustains, curves, micro timing, midi setting changes, swing modes, etc. becomes a pain in the speed and work flow of a rhythm professional, who btw. is hart to convince to do this task on a computer. And these are the guys who need a voice here. Listening to them would inspire many others because it is a very underrated topic. Because of the misunderstanding what it is: drum programming. Or maybe better sayed: what it can be.

*And please, stop mentioning EZ Drummer, Addictive Drums or BFD. This is like mentioning computer games when I ask for real flight training. It's not about multi layer sample players only here. It is more complex.*

Rhythm section programming is far beyond what many think of when they put their basedrum and snare layers and hihats in a midi region, go back to their bank to change some properties and mix them finally (to say it simple). Or the boring cut and paste of drum loop parts or pattern templates. Real drum programming is a professional niche where I would see not many fitting in. And programming them should be only one way of many.

A rhythm guru is fast, and he needs something fast on his finger tips. If there would be a proper software, I would be able to play drums (even on a midi drumstation), record them, split them on keys, mix them with samples, which can be easely exchanged on the fly while the loop still runs from my library. I can switch many important settings with key commands and near by near interface spots. A rhythm expert feels the "breath" of his section before it is finished and he needs to write it down fast. Like an author and his dictaphone. Hydrogen was close to some parts of FxPansions Geist, but only on some points. As often, its all about priorities. Which functionality has prio and comes first for such an approach. Thats what makes the difference between many computer audio instruments.

[Here](CHATLOG.md) is a short excerpt out of an IRC chat were the idea was born to start this document.

## Were are we now?

There are some examples of "close to what it can be" in the wild.

### Examples of existing projects (needs clearance about the concept we are after, step sequencer yes no?)

| Name              | Active | Features  | License | Slice | Pattern | Link       | User experience |
|-------------------|--------|-----------|---------|-------|---------|------------|-----------------|
| Hydrogen          | ✔      | pls fill  |         | -     | ✔       | Link       | report link     |
| Slicex            | ✔      | pls fill  |         | ✔     | ?       | Link       | report link     |
| Guru              | -      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| Geist             | ✔      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| LiveSlice         | ?      | pls fill  |         | ✔     | ?       | Link       | report link     |
| NI Battery        | ?      | pls fill  |         | ✔     | -       | Link       | report link     |
| iDrum             | ?      | pls fill  |         | -     | ✔       | Link       | report link     |
| DrumStar          | ?      | pls fill  |         | ?     | ?       | Link       | report link     |
| ADM               | ?      | pls fill  |         | ?     | ?       | Link       | report link     |
| RMV               | ?      | pls fill  |         | -     | -       | Link       | report link     |
| BreakTweaker      | ✔      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| NI Maschine       | ✔      | pls fill  |         | ?     | ✔       | Link       | report link     |
| orDrumBox         | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| Phatmatik         | -      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| Xfer Nerve        | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| ~Ez Drummer~      | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| ~Addictive Drums~ | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| ~BFD~             | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| Motu BPM          | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| StiX by Xils      | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |

> We maybe should mention other Linux drum plugins but before that we must clear up if we split the list in drum sample players/creators apart from pattern and step sequencing supporting machines or not. For me Geist and Hydrogen is closest to what I am after with this paper.

## There are many additional aspects to consider:

 + Is this idea lost in translation because it tries to cover existing features with additions which are impossible to achieve?
 + Are there replacements for proprietary and much outdated file formats like rex2 required for the audio slicing chopping part? And how would that coexist and be interchangable (maybe a wav>marker kind of thing? E.g.: How does PhatMatik solved this license issue with rex files?)
 + What midi/audio/library file formats should be supported in general. What licenses do they use? Are they open?
 + Upsidedown view: What did others do right (*"Do not reinvent the wheel!"*)
 + Some maybe not too useful but sadly common concepts of beat programming may need to stay implemented to gain a big enough audience to build a community around a new idea.
 
 > 15:21 < speak> But yeah sounds like diqidoq doesn't have any unrealistic expectations, which really is key here!

 > 15:35 < diqidoq> speak: indeed, because "if" ..., then ..., it wouldn't be my first dev project initiation ;-) ... but as the draft/paper states clearly already on many places: it's not about reinventing the wheel nor about a new instrument road map at first place. it's a brain pool for improvement. Where this gonna happen depends on where is the best starting point for it. And something important I already have stated here and on many other places again and again: Any attempt is only worth a word if it is made for lasting long. A problem I have stated so many times regarding OSS projects, that I even get fluff on the mouth by thinking about it. This is maybe one of the most underrated aspects of such projects because it is one of the hardest goals to achieve. Nobody can really feel that who wasn't in that situation himself for a long enough time. Sustaining a big project like Ardour for example... Keeping it up all the time. And this is why I have so much respect for project leads like Paul and others. Because I know what it means to keep a stiff upper lip.

 > 15:46 < typonese> amen :)

 > 15:49 < speak> diqidoq: Well said!
 
