# 👩🏻‍💻🧑🏼‍💻👩🏽‍💻👨🏾‍💻 Collaborative Coding Practices

A repository with suggestions, repertoire, tools and exercises for collaborating coders that use live coding to make music. Part of the *Collaborative Coding Music in Flok* workshop by Lina Bautista and Timo Hoogland, first presented at [/* VIU */ Festival 2024](https://toplap.cat/posts/viu-2024/).

# 📖 Table of Content

- [Setup](#-setup)
- [Exercises](#-exercises)
- [Collaborative Editors](#-collaborative-editors)
- [Repertoire](#-repertoire)
- [Further Reading](#-further-reading)
- [Inspiration](#-inspiration-from-other-performances)
- [Useful Tools](#-other-useful-tools)

# 📟 Setup

First we setup the collaborative coding environment. For this workshop we use [**Flok**](#flok). Flok allows for using the languages Foxdot, Mercury, Sardine, Strudel, SuperCollider and Tidal. In the future you can choose a different editor depending on personal preferences and the language you like to code with. For a list of other collaborative editors see [Collaborative Editors](#-collaborative-editors).

1. Go to [https://flok.cc](https://flok.cc)
2. Choose a username
3. Share the url with your collaborator
4. In the top-left menu choose the language you want to use
5. If you choose `Mercury-web` or `Strudel` you are ready to go!
5. If you use a language that is not browser based (eg. Tidal, SC, Foxdot) you have to setup the `REPL` via the terminal to connect your editors' output with your interpreter and sound engine.
	- Click `REPLs` in the top-right corner. 
	- Copy the command and paste/run it in the terminal (you need to have `npm`/`npx` installed from [NodeJS](https://nodejs.org/en))
	- Start your environment and check if the code is coming in through the OSC port.
	- [More info on using the REPL's](https://github.com/munshkr/flok?tab=readme-ov-file#supported-repl-targets)

# 🕹 Exercises

**One rule: No pasting code!**

## Exercise 0

*Start from scratch*

Listen to a short 3-minute solo-jam from eachother. While one is typing the others are just listening to what this person is making. This will help you to get to know eachothers styles and strengths.

## Exercise 1

*Start from scratch*

Code only one instruments/sound per person and only work on your individual sound (in parallel). Carefully listen & read what the others are doing and adapt your code based on that. Divide the arrangement of the music in a way that makes sense for you all. For example one person can work on a rhythmic/percussive sound, while the other makes a bass or melodic instrument. Think in terms of complementary sounds. You can divide an arrangement in many ways, percussive-tonal, dense-sparse, staccato-legato, high-low, and much more.

## Exercise 2

*Continue with the code you wrote above*

Create a new instrument/sound from scratch and work on that code together, slowly changing the instrument to both your tastes. Only, don't remove each others ideas but build upon them. Accept decisions from the other, also if you don't immediately like them.

## Exercise 3

*Start from scratch or continue with the code above*

In this exercise one of you will be the *"initiator"* of a new instrument/sound, while the other will be the *"adjuster"*. The *initiator* will code new ideas and execute them. After evaluating and listening to the result, the *adjuster* will start to delete and change the values or functions of the thing that was just coded, introducing variations on the original idea. Don't feel bad about deleting each others work, allow ["code to die"](https://www.pastagang.cc/blog/let-code-die/).

## Exercise 4

*For this exercise you continue with the instruments from above.*

It is quite common in live coding performances to evaluate the code after every little change, so you can hear the results directly. However, for this exercise one of you will only be allowed to evaluate small changes in the instrument. At the same time the other has to make a lot of changes to another instrument, but wait till the best moment to evaluate introducing some radical changes in the composition. It could help to code things as a comment to avoid things being evaluated before they are ready to go.

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

## Nudel

- site: https://nudel.cc/
- github: https://github.com/pastagang/nudel
- docs: https://github.com/pastagang/nudel?tab=readme-ov-file#nudel

Nudel was born out of curiosity, to see if Flok.cc could be treated as a protocol, where different web clients access the same session.

Languages (in browser): `Hydra` `Strudel` `KabelSalat` `Shader` `JS`

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

- [**Damage Such** - Live at /* VUI */ Festival in Sala Vol ](https://youtu.be/7KH7fn4k8kE?si=fnD3A5u_uZOMrl9R&t=1501)
	- Using: Flok, Mercury

- [**RGGTRN**](https://rggtrn.github.io/)
	- Using: Supercollider 

- [Enter your suggestion here](https://github.com/tmhglnd/collaborative-coding-practices/issues)

# 📚 Further Reading

Below is a list of reading material that touches on the subject of collaborative coding and remote performances.

- [**Remote Sets** - Blogpost on TOPLAP.org by GEIKHA 芸下☭](https://blog.toplap.org/2024/05/27/remote-sets-livecoding-in-its-purest-form/)

- [**How To: Live Coding Jams** - Blogpost by TH4](https://th4music.net/how-to-live-coding-jams.html)

- [**Bad Code Only** - Pastagang Blogpost](https://www.pastagang.cc/blog/bad-code-only/)

- [**Let Code Die** - Pastagang Blogpost](https://www.pastagang.cc/blog/let-code-die/)

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
