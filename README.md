> From a long way of testing and writing bug reports, filing issues up to writing long letters to project maintainers, which have been never send because of doubts of mine if this is the right starting point, I came to the conclusion to start this roadmap for an *idea*.... It's just a twinkle in an eye ... and answers to the name: ...

# LARS (Linux audio rhythm section machine)

 + a flexible samples and step sequencer based groove machine to manage drum and rhythm section programming via triggered samples the right way, with features like:
   + managed layers for dynamic triggering and sample mix creations
   + envelopes and smart envelope grouping logic (flow and punch grouping/design)
   + smart and intuitive step sequencing (key commands, intuitive and fast trigger setups)
   + rhythm templates, group and layer based swing faders, sync options, micro timing faders, etc.
   + synth and noise addition feature for breath 
   + many import/export features into every possible format, embracing standarts
   + loop slice and chop support incl. triggering slices of loops on certain keys
   + typical *tricks* at hand for rhythm section pros (more here to come after shaping the papers)
 + as a *stand alone* machine with in/out management
 + as a lv2 plugin
 + to make Linux pro audio even more sexy than it already is :-)
 + to integrate perfect with awesome projects like my favourite Ardour and JACK or Mixbus, but also with Qtractor, LMMS and others
 + to really show off and support the advantages from Linux OS modular audio concepts and work flows over other OS
 + to fulfil a dream of mine: to finally fill the gap of real intuitive and useful rhythm section programming for the pros on their __qualified__ fingertips.

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

### Examples of existing projects

| Name            | Activity     | Features   | License | Slices  | Pattern | Link       | User experience report |
|-----------------|--------------|------------|---------|---------|---------|------------|------------------------|
| Hydrogen        | yes          | pls fill   |         | -       | x       | Link       | Internal doc link      |
| Slicex          | yes          | pls fill   |         | x       |         | Link       | Internal doc link      |
| Guru            | maintenaince | pls fill   |         | x       | x       | Link       | Internal doc link      |
| Geist           | yes (v2)     | pls fill   |         | x       | x       | Link       | Internal doc link      |
| LiveSlice       | yes          | pls fill   |         | x       |         | Link       | Internal doc link      |
| NI Battery      | some improv. | pls fill   |         | x       | --      | Link       | Internal doc link      |
| iDrum           | ?            | pls fill   |         | -       | x       | Link       | Internal doc link      |
| DrumStar        | ?            | pls fill   |         | ?       |         | Link       | Internal doc link      |
| ADM             | ?            | pls fill   |         | ?       |         | Link       | Internal doc link      |
| RMV             | ?            | pls fill   |         | ?       | --      | Link       | Internal doc link      |
| BreakTweaker    | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |
| NI Maschine     | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |
| orDrumBox       | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |
| Phatmatik       | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |
| Xfer Nerve      | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |
| Ez Drummer      | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |
| Addictive Drums | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |
| Xfer Nerve      | ?            | pls fill   |         | ?       | x       | Link       | Internal doc link      |

> We maybe should mention other Linux drum plugins but before that wemsut clear if we split the list in drum sample players/creators apart from pattern and step sequencing supporting machines or not.

## Additionally there are many other aspects to consider:

 + required replacements for proprietary and much outdated file formats like rex2 (maybe a wav>marker kind of thing?)
 + what file formats should be support in general (licenses?)
 + what did others right (do not reinvent the wheel)
 + some maybe not too useful but sadly common concepts need to stay implemented to gain a big enough audience to build a community.
