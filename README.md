<p align="center">
  <img src="https://static.wikia.nocookie.net/logopedia/images/4/4e/Family_Guy_Online_%28Peter%29.png" />
</p>

**Family Guy Online Reaired** is a community-driven project with two primary goals: to create a comprehensive archive of all available assets, information, and data from the defunct Family Guy Online MMO, and to reverse-engineer and revive the game itself. Inspired by successful revival efforts for games like **Toontown Rewritten**, **FusionFall Retro/OpenFusion**, and **Pirates of the Caribbean Online (TLOPO)**, this project aims to bring Quahog back to life.

# What Was Family Guy Online?

Family Guy Online (commonly abbreviated as FGO) was a free-to-play, browser-based 3D massively multiplayer online role-playing game (MMORPG) based on the hit animated television series Family Guy. It was developed by Roadhouse Interactive in partnership with 20th Century Fox.

The game was announced at San Diego Comic-Con in July 2011 and entered open beta on April 17, 2012. It was built using the Unity game engine and ran within a user's web browser via the Unity Web Player plugin.

# Gameplay

In _Family Guy Online_, players didn't play as the Griffin family themselves, but rather as custom-made residents of Quahog who used the Griffins as class templates. The class system was themed around the show's characters:

- **Stewie** as a ranged DPS
- **Chris** as a melee DPS
- **Peter** as a tank
- **Lois** as a healer
- **Brian** as an all-rounder. He was presented as a locked, upcoming fifth class and was eventually unlockable through a requirement to log in for six consecutive days or behind a one-time payment of $19.99. 

Players explored a fully 3D Quahog, visiting iconic locations such as the Griffin house, Spooner Street, and The Drunken Clam. Characters from the show served as quest givers, with voice acting from the actual cast. Quests ranged from chasing the Greased-Up Deaf Guy to rescuing a midget from a well and even fighting Peter over the "Surfin' Bird" record.

The game featured:

- Turn-based combat with an active time element
- A customizable "Materia" system for abilities
- Mini-games and social activities
- "Quick Pops": interactive non-sequitur gags that popped up when clicking on objects
- A free-to-play model supported by microtransactions for cosmetic items

# Why Did It Shut Down?

Family Guy Online was shut down on January 18, 2013, while still in beta, less than nine months after its open beta launch. 20th Century Fox did not publicly disclose the official reason, but lack of profitability is widely believed to have been the primary factor.

However, the most infamous reason comes from an unofficial report cited by multiple outlets: the average player spent less than 3 minutes playing before quitting.

Roadhouse Interactive president James Hursthouse later explained the struggles behind the game's demise:

"We learned that players did not take to the early version of Family Guy Online. They did not understand the basic MMO concepts of quests and magic and many called the game extremely quote unquote 'for nerds'. They did like the non sequitur cutscenes of the game because it reminded them of the show".

He went on to describe how the team tried to dumb down the mechanics so even children could understand, but players still couldn't grasp the rock-paper-scissors battle system. Some players even asked whether Lois would become nude after making a sex joke and spent their time trying to attack NPCs.

Hursthouse revealed that:

- 90% of conversations between players were just Family Guy quotes
- 70% of players could not progress past level 2
- Peak simultaneous players: 200
- 60% of the jokes were re-used from the show
- The game's audience simply wasn't the MMO crowd

However, the game has since remained a cult classic and a remnant of early 2010's browser games powered by Unity Web Player. Occasional dumps have appeared at random points within the last decade offering thousands of model and texture assets, but have ubiquitously lacked any .dll and .unity3d file necessary to piece the game together in any playable capacity. This absense subsequently brought attention to Family Guy Online from lost media spaces, unsuccessfully searching for said files. There has also been an attempt or two from different sides of the internet, each trying to attempt at a revival of the game itself but ultimately failing.

# What We're Doing

Much like the **Fusionfall Retro** project and every version of it since, we are both actively searching for all Family Guy Online assets that can be found as well as simultaneously reverse-engineering the game from the ground up using what's currently available. The goal is to preserve and recreate the game as faithfully as possible, targeting the August–November 2012 timeframe for which we have the most asset data.

However, this is a from-scratch revival effort. There is no working server or client yet. We are starting with the assets and building everything else.

The original game relied on:

- A web browser with NPAPI plugin support (deprecated in modern browsers)
- The Unity Web Player NPAPI plugin
- A .unity3d bundle containing game code and resources
- A login server and a shard (gameplay) server communicating over TCP
- Our approach is inspired by OpenFusion's solution: we plan to use an older version of Electron (a specialized web browser) to load the game via the file:// protocol, bypassing the need for a web server. The client would fetch assets from a standard web server and connect to a reverse-engineered login and shard server.

But **none of this is available yet**. We are at the very beginning of this project.

# What We Have

We currently have cache dumps containing over 3,000 files, including 3D models, textures, UI elements, and other game assets. Although these are all incredibly useful and better than nothing, we cannot use these to recreate the game alone without any .dll or .unity3d files, as mentioned earlier.

Page assets are also avaliable from the Wayback Machine and archive.is to recreate the website itself.

A handful of emails sent to players at the time have also been archived.

We also have various gameplay videos, documentation, and reference materials to use as a guide for recreating things such as server mechanisms, which FusionFall Retro was forced to do during their initial revival project.

# What We Need

We are looking for **ANYONE** who can help. This is a massive undertaking, and we need people with a wide range of skills:

| Role      | Description |
| ------------- | ------------- |
| Asset Hunters  | Find more cache dumps, asset files, or any leftover data from the game. Every file helps.  |
| Reverse Engineers  | Analyze the Unity bundle structure, extract assets, and figure out how the game worked.  |
| Server Developers  | Write new server-side logic in preferably C# and/or C++. No server code is currently available; we are building it from the ground up.  |
| Client Developers  | Build a launcher and client that can load the game assets and connect to our custom server.  |
| Unity Developers  | Work with the Unity bundle, figure out how to load and modify it, and potentially rebuild parts of the client.  |
| 3D Modelers  | Create or restore 3D models for characters, environments, and props.  |
| 2D Artists  | Create or restore textures, UI elements, and 2D images used in both the game and website.  |
| UI/UX Designers  | Help design the launcher and any custom interfaces we need.  |
| Writers  | Document the game's quests, dialogue, and systems. Help write guides and lore documentation.  |
| Testers  | Once we have something playable, we'll need people to test and report bugs.  |
| Community Managers  | Help organize the project, manage Discord, and coordinate efforts.  |

Even if you don't have technical skills, you can help by spreading the word, digging for old files, or documenting what you remember about the game. **_Please note that these roles are NOT paid for, as this project is and will indefinitely remain non-for-profit._**

# How You Can Get Involved

## 1. Join the Community

The first step is to join our Discord server where all coordination and collaboration happens.

https://discord.gg/kYsvXpEm88

## 2. Dig for Assets

If you have or anyone you know has any old files, browser caches, or backups from 2012, please share them. Even small files can be valuable. A zip of all currently available raw cache dumps can be downloaded in the Releases section.

## 3. Start Reverse-Engineering

If you have experience with:

- Unity asset extraction
- Network protocol reverse-engineering
- Disassembling and debugging Unity Web Player games
- C#, C++, or general server development
...we need you. Join the Discord and let us know what you can work on.

## 4. Spread the Word

The more people who know about this project, the more likely we are to find someone with the skills we need. Share this README, post about it on forums, and tell your friends.

# Project Goals

1. Short-term: Build a community of contributors, collect more assets, and begin reverse-engineering the client and network protocol.
2. Medium-term: Develop a proof-of-concept server that can handle basic login and character creation, and a client that can load the game assets.
3. Long-term: Fully recreate Family Guy Online as it was in late 2012, with all quests, combat, social features, and content restored.

# Frequently Asked Questions
### Is there a playable version yet?

No. This project is in its early stages. We are building everything from scratch with all the assets that we currently have.

### Where did the avaiable files come from?

They were collected from previous players who had archived and shared their old browser caches. If you have more, please share them!

### What files are needed to help preserve or revive the game?

The most valuable files are original Unity game builds, Unity Web Player files (.unity3d), asset bundles, game DLLs such as Assembly-CSharp.dll, server code, database backups, API documentation, and website source files. These files **must** come from the original game; generic DLLs or .unity3d files found online are **not** useful, as they are unique to each game and contain game-specific code, assets, and data. Even partial backups, development builds, or archived project files may help preserve or reconstruct the game.

### When will the game be playable?

You tell us. It depends entirely on how many contributors we get and how quickly we can make progress.

### I'm not a developer. Can I still help?

Absolutely! We need asset hunters, writers, testers, community managers, and people to spread the word.

### Is this legal?

This is a fan-made revival effort no different than any made for Toontown, FusionFall, or Pirates of the Carribean Online, which all currently fall under a legal grey area. We are not affiliated with Disney, 20th Century Fox, Roadhouse Interactive, or any other rights holders. Family Guy and all related characters are trademarks of said rights holders. This project is solely for preservation and educational purposes only. Only assets that were publicly cached are being distributed and used for research purposes. We are not responsible for any repercussions that you may face when accessing the files provided by us or anywhere else.
