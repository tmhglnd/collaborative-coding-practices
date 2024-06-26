# 👩🏻‍💻🧑🏼‍💻👩🏽‍💻👨🏾‍💻 Collaborative Coding Practices

A repository with suggestions, repertoire, tools and exercises for collaborating coders that use live coding to make music. Part of the *Collaborative Coding Music in Flok* workshop by Lina Bautista and Timo Hoogland first presented at [/* VIU */ Festival 2024](https://toplap.cat/posts/viu-2024/).

# 📖 Table of Content

- [Setup](#-setup)
- [Exercises](#-exercises)
- [Collaborative Editors](#-collaborative-editors)
- [Repertoire](#-repertoire)
- [Further Reading](#-further-reading)
- [Inspiration](#-inspiration-from-other-performances)
- [Useful Tools](#-other-useful-tools)

# 📟 Setup

First we setup the collaborative coding environment. The editor you choose in the future can depend on personal preference and the language you like to code with, but for this workshop we use [**Flok**](#flok). Flok allows for using Foxdot, Mercury, Sardine, Strudel, SuperCollider and Tidal.

1. Go to [https://flok.cc](https://flok.cc)
2. Choose a username
3. Share the url with your collaborator
4. In the top-left menu choose the language you want to use
5. If you choose `Mercury-web` or `Strudel` you are ready to go!
5. If you use a language that is not browser based (eg. Tidal, SC, Foxdot) you have to setup the `REPL` via the terminal to connect your editors output with your interpreter and sound engine.
	- Click `REPLs` in the top-right corner. 
	- Copy the command and paste/run it in the terminal (you need to have `npm`/`npx` installed from [NodeJS](https://nodejs.org/en))
	- Start your environment and check if the code is coming in through the OSC port.
	- [More info on using the REPL's](https://github.com/munshkr/flok?tab=readme-ov-file#supported-repl-targets)

# 🕹 Exercises

## Exercise 1

Code only 2 instruments/sounds and only work one instrument individually (so in parallel). Listen/read what the other is doing and adapt your code based on that. Divide the arrangement in a way that makes sense for both of you, for example one person can work on a rhythmic/percussive sound while the other makes a bass or melodic instrument.

## Exercise 2

In this exercise one of you two will be the *"initiator"* of a new instrument/sound, and the other will be the *"adjuster"*. The *initiator* will code new ideas and evaluate. After it is evaluated and you hear the result the *adjuster* will change the value or function of the thing that was just coded to something else, introducing some slight variation on the original idea.

## Exercise 3

Create a new instrument/sound from scratch and work on that code together, slowly changing the instrument to both your tastes. Don't remove each others ideas but build upon them. Accept decisions from the other even if you don't immediately like them.

## Exercise 4

Continue with the instruments from above. It is quite common in live coding to evaluate after every little change. For this exercise one of you will be allowed to evaluate small changes in the instrument, while at the same time the other is make a lot of changes to the other instrument but wait till the best moment to evaluate introducing some radical changes in the composition. It can help to code things as a comment to avoid things being evaluated before they are ready.

# 🛰 Collaborative Editors

## Flok

- site: https://flok.cc
- github: https://github.com/munshkr/flok
- docs: https://github.com/munshkr/flok?tab=readme-ov-file#usage

Flok is an online collaborative coding editor developed by Damián Silvani (a.k.a Munshkr). The editor allows you to join with multiple people by accessing the same URL. You can add various panels for different languages. Some run directly in the browser, others are send to the terminal via OSC.

Languages (in browser): `Hydra` `Strudel` `Mercury`

Languages (with repl): `Foxdot` `Mercury` `Sardine` `SClang` `TidalCycles`

## Estuary

- site: https://estuary.mcmaster.ca/
- github: https://github.com/dktr0/estuary

Estuary is a platform for collaboration and learning through live coding. It enables you to experiment with sound, music, and visuals in a web browser. Estuary brings together a curated collection of live coding languages in a single environment, without the requirement to install software (other than a web browser), and with support for networked ensembles (whether in the same room or distributed around the world). 

Languages (in browser): `MiniTidal` `Punctual` `Hydra` `CineCer0` `LocoMotion` `Seis8s` `TimeNot` `TransMit`

## Troop

- site: https://github.com/Qirky/Troop/releases
- github: https://github.com/Qirky/Troop
- docs: https://github.com/Qirky/Troop?tab=readme-ov-file#getting-started

Troop is a real-time collaborative tool that enables group live coding within the same document across multiple computers. Hypothetically Troop can talk to any interpreter that can take input as a string from the command line but it is already configured to work with live coding languages FoxDot, TidalCycles, and SuperCollider. It was developed by Ryan Kirkbride (a.k.a. Quirky).

Languages (locally): `Foxdot` `TidalCycles` `SuperCollider` `SonicPi`

## P5Live

- site: https://www.teddavis.org/p5live/
- github: https://github.com/ffd8/P5LIVE

P5Live is a collaborative live coding editor for P5.js (but also includes Hydra) developed by Ted Davis. Through the "cocoding" functionality you can edit code together.

Languages (in browser): `p5.js` `Hydra` `p5.sound`

# 👾 Repertoire

Below is a list of repertoire from people collaborating on live coding via these various tools. Suggestions are welcome!

- [**Sabrina Verhage & Flor de Fuego** - Live at Livecodera 8m](https://www.youtube.com/live/iY9Vc8LpMFQ?si=BWR1m3NZNcf9zkfs&t=3526)
	- Using: Flok, Mercury, Hydra

- [**Damage Such** - Live at Sala Taro](https://youtu.be/Ykhjx7ZkaEQ?si=UbrMjEvV58BQozb4&t=1336)
	- Using: Flok, Mercury, Animatron

- [**Benoît and the Mandelbrots** - Live at TEDx](https://youtu.be/Ix2b_qFYfAA?si=q128_ddemHYy7z9X&t=238)
	- Using: Supercollider

- [**Bad Circulation** - Live at Corridor of Light Algorave](https://youtu.be/AlhEc2N8VII?si=ysRyQamkiIIGlW3w&t=838)
	- Using: Troop, TidalCycles

- [**iTypeMusic** - Live Coding Techno Vibes](https://youtu.be/aB1mdxLCR7c?si=cA7Z5FSpl7LpuVHX&t=766)
	- Using: Flok, Mercury, Hydra

- [**CrashServer** - Live at TOPLAP 20](https://youtu.be/UZ4fAR3yk1c?si=KQpTz5V2DdJInxD-)
	- Using: Troop, Foxdot

- [**Epiploke** - Live at Solstice Stream 2023](https://youtu.be/fMd1CwLwMj4?si=bO77HpSdDP-9kSj8&t=257)
	- Using: Flok, Tidal

- [**Estuary WeekendJam** - Over more than 160 jamsessions in Estuary streamed weekly in Eulerroom](https://www.youtube.com/playlist?list=PLMBIpibV-wQLvP7jitjnV9E61DfV11235)
	- Using: Estuary, MiniTidal, Punctual

- [Enter your suggestion here](https://github.com/tmhglnd/collaborative-coding-practices/issues)

# 📚 Further Reading

Below is a list of reading material that touches on the subject of collaborative coding and remote performances.

- [**Remote Sets** - Blogpost on TOPLAP.org by GEIKHA 芸下☭](https://blog.toplap.org/2024/05/27/remote-sets-livecoding-in-its-purest-form/)

# ✨ Inspiration from other performances

- [**Overmono** - Live at Boilerroom](https://youtu.be/xgJBhezlMoE?si=3nSXC_0DBkCmd0mY&t=2053)

- [**Moderat** - Live at KEXP](https://youtu.be/HVkVq_qs7FM?si=6eQEzd4yqg6T3QwL&t=1036)

# 🛠 Other Useful Tools

## Brave Browser

- site: https://brave.com/download/
- github: https://github.com/brave/brave-browser
	
Many collaborative coding editors run in the browser. Brave is an open source browser running on chromium and is very suitable for all the platforms. It supports WebGL, WebAudio and WebMidi.

OS: `Mac` `Windows` `Linux`

## Sonobus

- site: https://sonobus.net/
- github: https://github.com/sonosaurus/sonobus
- docs: https://sonobus.net/sonobus_userguide.html

SonoBus is an easy to use application for streaming high-quality, low-latency peer-to-peer audio between devices over the internet or a local network. 

OS: `Mac` `Windows` `Linux` `iOS` `Android`

## OBS (Open Broadcast Software)

- site: https://obsproject.com/
- github: https://github.com/obsproject/obs-studio
- docs: https://obsproject.com/help

Free and open source software for video recording and live streaming. This platform allows you to livestream or record your screen or seperate Windows from applications. Very helpful if you like to record your works or want to go live on Youtube, Twitch, Facebook or wherever.

OS: `Mac` `Windows` `Linux`

## BlackHoleAudio

- site: https://existential.audio/blackhole/
- github: https://github.com/ExistentialAudio/BlackHole
- docs: https://github.com/ExistentialAudio/BlackHole/wiki

BlackHole is a modern MacOS virtual audio loopback driver that allows applications to pass audio to other applications with zero additional latency.

OS: `Mac`

## VB-Cables

- site: https://www.vb-audio.com/Cable/

VB-CABLE is a virtual audio device working as virtual audio cable. All audio coming in the CABLE input is simply forwarded to the CABLE output.

OS: `Windows`

## Spout

- site: https://spout.zeal.co/
- help: https://spout.discourse.group/

Spout leverages your graphics card enabling to you send realtime video between Windows applications with near-zero latency or overhead. It is provided free and open source thanks to support from its users.

OS: `Windows`

## SpoutToNDI

- site: https://leadedge.github.io/
- help: https://spout.discourse.group/

Spout to NDI is a set of programs that allow Spout senders and receivers to share video, not only with each other but also by way of a network using the Newtek NDI (“Network Device Interface”) protocol version 5.

OS: `Windows`

## NDISyphon

- site: https://docs.vidvox.net/freebies_ndi_syphon.html
- docs: https://docs.vidvox.net/freebies_ndi_syphon.html#using-ndisyphon

NDISyphon is a simple, free utility that makes it possible for any Syphon enabled software to efficiently send and receive video streams to and from other applications over a network using the NDI® protocol from Newtek.

OS: `Mac`

## NDITools

- site: https://ndi.video/tools/
- docs: https://ndi.video/resources/docs-guides/

Wide variety of software for NDI applications. The NDI Virtual Input is especially useful as virtual webcam device.

OS: `Mac` `Windows`

## Ableton Link

- site: https://www.ableton.com/en/link/products/

Link is a technology that keeps devices in time over a local network. Link is part of Ableton Live, and also comes as a built-in feature of other software and hardware for music making. View the site for all available platforms/apps.