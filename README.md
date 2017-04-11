> From a long way of testing and writing bug reports, filing issues, up to writing long letters to project maintainers, which have been never send because of doubts of mine if this is the right starting point, I came to the conclusion to start this roadmap like a questionaire for an *idea* ... It's just a twinkle in an eye ... and by chance it became a thing ... and answers to the name: ...

# LARS (Linux audio rhythm section machine)

 + a flexible sample triggering (step sequencer including?) Linux audio instrument to manage/support complex drum sound and rhythm section programming
 + as a *stand alone* machine with in/out management.
 + as a lv2 plugin.
 + to make Linux pro audio even more sexy than it already is :-)
 + to integrate perfect with awesome projects like my favourite Ardour and JACK or Mixbus, but also with Qtractor, LMMS and others.
 + to really show off and support the advantages from Linux OS modular audio concepts and work flows over other OS.
 + to fulfil a dream of mine: to finally fill the gap of real intuitive and useful rhythm section programming for the pros on their __qualified__ fingertips.
 
## Feature roadmap

>  Basically it's all about drum and rhythm programming improvement. It doesn't matter on which projects: on existing ones or on newly to initiate ones ... please join with [your 2 cents](https://github.com/diqidoq/lars/issues/1).

 + a simple, flat and intuitive UI with pro user requirements:
   + neat and clean with only a few logical and useful flat color highlights.
   + no fancy, no pictures of instruments or virtual mixer toys and such kindergarden.
   + flexible, configurable and stretchable flat design.
   + real smart key commands (multi tap, combinations, mappable).
   + simple zoom in/out on sample shapes, envelopes, midi sequences.
 + no useless tools and toys which only limit your possible expressions.
 + real managable and groupable and smart sound layers for dynamic triggering and sample sound mix creation.
 + envelopes and smart envelope grouping logic (also for whole layers, groups, flow and punch grouping/design).
 + _if we agree on an included_ step sequencer, let it please be smart and intuitive:
   + smart and editable multi key commands.
   + straight-to-the-goal way of event management. no fuzz, simple click>add, doubleclick>remove, etc.
   + intuitive and fast trigger setups.
   + drum and rhythm centric functionality and standards (notes,events,look,feel,handling)
   + take a deeper look at Hydrogens pattern designer, seg24, Guru and Geist.
   + rhythm templates
   + group and layer based swing faders
   + sync options
   + micro timing faders
   + and many more
 + synth (humble) and noise (pink,white) addition feature for breath and rhythm instrument design.
 + many import/export features into every possible format.
   + embracing standarts.
   + drag and drop of samples and midi regions/patterns into DAW.
   + easy rendering of sf and other file formats for resuse.
 + loop slice and chop support incl. triggering slices of loops on certain keys.
 + typical *tricks* at hand for rhythm section pros (more here to come after shaping the papers).
 + easy replace of samples on the fly (key command combi on selected event with up/down while loop plays)
 + a.s.o ... (list not complete)

## For the complainers about this paper

This document is a work in progress, a crib, a very early and first note. So please do not feel offended or badly affected by wrongly shaped paragraphs, typo, missing facts, missing options not mentioned or already around in other projects which are filling some of the points here, or anything weird for you to read until it is finished. A strong and self-aware feature comparision-list is planned and one of the main reasons for that paper. Also read the [CHATLOG.md](CHATLOG.md). I decided to make the progress on this document public to the Open Source community to contribute to it for a faster and more open minded finished result.

It all happend by chance when I was investigating for drum pattern and step sequencer and drum sample machines over the last days under Linux and it wasn't planned. My experience from many pro audio software over 20 years on almost any OS lead me to the impression that non of the existing fills the gap really.

### An important point to make ...
 
**It's not about forking and splitting the hell out of a community.** I am an advocate for building, grouping and motivating communities and to **bundle forces**, not too loose them. So if anything of this white paper here can go into something else or can be remerged into another existing project, I am absolutely fine with that. It's all about improvement. But until then I try to prevent to stir up a hornets' nest by trying to discuss this dream inside of existing projects yet, since there are too many aspects which can get in the way of the roadmaps of other projects.

## Were do I come from ?

[Who is me?](AUTHOR.md) Where do I want to go with this? All has started with a planned and written pages long [letter to the developers of Hydrogen](LETTER_TO_HYDROGEN.md), a very potential and long time existing drum machine software for Linux. I have - as always - many respect for the hard work which goes into Open Source projects to make software available for professionals working on Linux like this. And I can't say it often enough how often this movement gets misunderstood and the developers and contributors treated badly IMHO. I don't want to go too deep into what community driven open source projects is about and how it works and how to contribute to them. I only want to make clear how much repect I have for this projects and how much I was already involved in such attempts and how hard it is for me to find the right way to go for this issue.

## What is the motivation ?

Well, let me shape it the other way around: there is a *niche* of people who has never been 99% satisfied with any of the new age drum or __rhythm section developing philosophy on computer based software__ yet. I can tell you that for granted. Painting events in a completely other corner of the UI than where you switch samples, layers, attacks, releases, sustains, curves, micro timing, midi setting changes, swing modes, etc. becomes a pain in the speed and work flow of a rhythm professional. And these are the guys who need a voice here. Listening to them would inspire many others because it is a very underrated topic. Because of the misunderstanding what it is. Or maybe better sayed: what it can be.

Rhythm section programming is far beyond what many think of when they put their basedrum and snare layers and hihats in a midi region, go back to their bank to change some properties and mix them finally (to say it simple). Or the boring cut and paste of drum loop parts or pattern templates. Real drum programming is a professional niche where I would see not many fitting in. And programming them should be only one way of many.

A rhythm guru is fast, and he needs something fast on his finger tips. If there would be a proper software, I would be able to play drums (even on a midi drumstation), record them, split them on keys, mix them with samples, which can be easely exchanged on the fly while the loop still runs from my library. I can switch many important settings with key commands and near by near interface spots. A rhythm expert feels the "breath" of his section before it is finished and he needs to write it down fast. Like an author and his dictaphone. Hydrogen was close to some parts of FxPansions Geist, but only on some points. As often, its all about priorities. Which functionality has prio and comes first for such an approach. Thats what makes the difference between many computer audio instruments.

[Here](CHATLOG.md) is a short excerpt out of an IRC chat were the idea was born to start this document.

## Were are we now?

There are some examples of "close to what it can be" in the wild.

### Examples of existing projects (needs clearance about the concept we are after, step sequencer yes no?)

| Name            | Active | Features  | License | Slice | Pattern | Link       | User experience |
|-----------------|--------|-----------|---------|-------|---------|------------|-----------------|
| Hydrogen        | ✔      | pls fill  |         | -     | ✔       | Link       | report link     |
| Slicex          | ✔      | pls fill  |         | ✔     | ?       | Link       | report link     |
| Guru            | -      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| Geist           | ✔      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| LiveSlice       | ?      | pls fill  |         | ✔     | ?       | Link       | report link     |
| NI Battery      | ?      | pls fill  |         | ✔     | -       | Link       | report link     |
| iDrum           | ?      | pls fill  |         | -     | ✔       | Link       | report link     |
| DrumStar        | ?      | pls fill  |         | ?     | ?       | Link       | report link     |
| ADM             | ?      | pls fill  |         | ?     | ?       | Link       | report link     |
| RMV             | ?      | pls fill  |         | -     | -       | Link       | report link     |
| BreakTweaker    | ✔      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| NI Maschine     | ✔      | pls fill  |         | ?     | ✔       | Link       | report link     |
| orDrumBox       | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| Phatmatik       | -      | pls fill  |         | ✔     | ✔       | Link       | report link     |
| Xfer Nerve      | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| Ez Drummer      | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| Addictive Drums | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |
| BFD             | ?      | pls fill  |         | ?     | ✔       | Link       | report link     |

> We maybe should mention other Linux drum plugins but before that we must clear up if we split the list in drum sample players/creators apart from pattern and step sequencing supporting machines or not. For me Geist and Hydrogen is closest to what I am after with this paper.

## There are many additional aspects to consider:

 + Is this idea lost in translation because it tries to cover existing features with additions which are impossible to achieve?
 + Are there replacements for proprietary and much outdated file formats like rex2 required for the audiop slice part and how would that be coexist and be interchangable (maybe a wav>marker kind of thing? How does PhatMatik solved this license issue?)
 + What midi/audio/library file formats should be supported in general (Licenses?)
 + What did others do right (*"Do not reinvent the wheel!"*)
 + Some maybe not too useful but sadly common concepts of beat programming may need to stay implemented to gain a big enough audience to build a community around a new idea.
