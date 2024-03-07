# Awesome Packdev [![Awesome](https://awesome.re/badge-flat.svg)](https://github.com/sindresorhus/awesome/) <img src="https://splashes.modernmodpacks.site/?splashes=Awesome!,Not finished!,Randomly generated!,Made in markdown!,Icon-ful!,Version-indifferent!,Helping packdevs since 2023!,Credit the creators!,Completely free!,Alphabetically sorted!,CC0!,§fDark mode!,Not affiliated with Notch!,Beans funny!Self-promotion!§cSus§epiciously good!,Unnecessary!,Has §1c§2o§3l§4o§5r§6s§e!,Made by Modern Modpacks!,Useless features!,:heh:,Hello world!,More mods for the mod god!,Award-winning!,Good (sometimes)!,0 flux rifts!,Requires no APIs!,Woo\, MPD!,Designed by a committee!,Looks good!,Silent!,Smash that star button!,Contributions welcome!&size=300" align="right">

A curated list of mods, apps, and resources simplifying the lives of Minecraft modpack developers.

## Contents

- [Icon Legend](#icon-legend)
  - [Versions](#versions)
  - [Modloaders](#modloaders)
  - [Misc](#misc)
- [Mods](#mods)
  - [Documentation](#documentation)
  - [Resource Loading](#resource-loading)
  - [Gameplay/Balancing](#gameplaybalancing)
  - [Scripting](#scripting)
  - [Utility](#utility)
- [Apps](#apps)
  - [Assetmaking](#assetmaking)
    - [Music](#music)
    - [Textures/Models](#texturesmodels)
  - [Coding](#coding)
  - [CLI](#cli-foss)
    - [Packaging](#packaging)
  - [Discord Bots](#discord-bots-foss)
  - [Productivity](#productivity)
- [Resources](#resources)
  - [Discord Servers](#discord-servers)
  - [Websites](#websites)
    - [Fun](#fun)
- [Contributing](#contributing)
- [License](#license)

## Icon Legend

### Versions

* [![1.7](icons/versions/7.png)](## "Supports 1.7") [![1.7+](icons/versions/plus/7.png)](## "Supports 1.7 and up") [![no1.7](icons/versions/no/7.png)](## "Doesn't support 1.7") [![no1.7+](icons/versions/plus/no/7.png)](## "Doesn't support 1.7 and up") - Supports/doesn't support 1.7 (and up).
* [![1.12](icons/versions/12.png)](## "Supports 1.12") [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up") [![no1.12](icons/versions/no/12.png)](## "Doesn't support 1.12") [![no1.12+](icons/versions/plus/no/12.png)](## "Doesn't support 1.12 and up") - Supports/doesn't support 1.12 (and up).
* [![1.16](icons/versions/16.png)](## "Supports 1.16") [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up") [![no1.16](icons/versions/no/16.png)](## "Doesn't support 1.16") [![no1.16+](icons/versions/plus/no/16.png)](## "Doesn't support 1.16 and up") - Supports/doesn't support 1.16 (and up).
* [![1.18](icons/versions/18.png)](## "Supports 1.18") [![1.18+](icons/versions/plus/18.png)](## "Supports 1.18 and up") [![no1.18](icons/versions/no/18.png)](## "Doesn't support 1.18") [![no1.18+](icons/versions/plus/no/18.png)](## "Doesn't support 1.18 and up") - Supports/doesn't support 1.18 (and up).
* [![1.19](icons/versions/19.png)](## "Supports 1.19") [![1.19+](icons/versions/plus/19.png)](## "Supports 1.19 and up") [![no1.19](icons/versions/no/19.png)](## "Doesn't support 1.19") [![no1.19+](icons/versions/plus/no/19.png)](## "Doesn't support 1.19 and up") - Supports/doesn't support 1.19 (and up).
* [![1.20](icons/versions/20.png)](## "Supports 1.20") [![1.20+](icons/versions/plus/20.png)](## "Supports 1.20 and up") [![no1.20](icons/versions/no/20.png)](## "Doesn't support 1.20") [![no1.20+](icons/versions/plus/no/20.png)](## "Doesn't support 1.20 and up") - Supports/doesn't support 1.20 (and up).

### Modloaders

* [![forge](icons/modloaders/forge.png)](## "Forge exclusive") - Forge/NeoForge-exclusive mod.
* [![fabric](icons/modloaders/fabric.png)](## "Fabric exclusive") - Fabric/Quilt-exclusive mod.

### Misc

* [![paid](icons/misc/paid.png)](## "Paid") - Paid software.
* [![freeware](icons/misc/freeware.png)](## "Conditionally free") - Conditionally free software.
* [![foss](icons/misc/foss.png)](## "Free and open-source") - Free and open-source software.
* [![unmaintained](icons/misc/unmaintained.png)](## "Unmaintained/abandoned") - Unmaintained/abandoned project.
* [![borked](icons/misc/borked.png)](## "Borked") - Borked project.
* [![experimental](icons/misc/experimental.png)](## "Experimental") - Experimental project.
* [![fork](icons/misc/fork.png)](## "Forked") - Forked project.

## Mods

### Documentation

- [Better Questing](https://curseforge.com/minecraft/mc-mods/better-questing/) - Questing mod only accessible for older versions with vanilla-esque customizable design. [![1.7](icons/versions/7.png)](## "Supports 1.7") [![1.12](icons/versions/12.png)](## "Supports 1.12")
- [Better Questing Unofficial](https://curseforge.com/minecraft/mc-mods/better-questing-unofficial/) - Fork of the Better Questing mod, adding more features such as the view mode. [![1.12](icons/versions/12.png)](## "Supports 1.12") [![fork](icons/misc/fork.png)](## "Forked")
- [FTB Quests](https://curseforge.com/minecraft/mc-mods/ftb-quests-forge/) - Questing mod with modern customizable design maintained by the FTB team, mostly popular among modern-version modpack developers. [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up")
- [Hardcore Questing Mode](https://curseforge.com/minecraft/mc-mods/hardcore-questing-mode/) - Questing mod with more experimental features, the main gimmick of which is a custom hardcore-esque mode that can be manipulated with in various ways using the questbook reward system. [![1.7+](icons/versions/plus/7.png)](## "Supports 1.7 and up")
- [Patchouli](https://curseforge.com/minecraft/mc-mods/patchouli/) - Simple data-driven library mod for adding in-game documentation books. [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up")
- [Quest Additions](https://curseforge.com/minecraft/mc-mods/quests-additions/) - Unofficial addon for FTB Quests, adding various extra features like repeatable rewards and new tasks. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up")

### Resource Loading

- [Load My Resources](https://curseforge.com/minecraft/mc-mods/load-my-resources-forge/) - Resourcepack loader, maintained by the creator of Fancy Menu, Keksuccino. [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up") [![forge](icons/modloaders/forge.png)](## "Forge exclusive")
- [Open Loader](https://curseforge.com/minecraft/mc-mods/open-loader/) - Resource-loading tool, allowing modpack developers to add instance-wide datapacks and resourcepacks. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up")
- [Paxi](https://curseforge.com/minecraft/mc-mods/paxi/) - Global resource/data pack loader, developed by YUNGNICKYOUNG. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up")
- [Resource Loder](https://curseforge.com/minecraft/mc-mods/resource-loader/) - Resource-loading tool specialized for older versions of the game using older-versioned resourcepacks. [![1.7](icons/versions/7.png)](## "Supports 1.7") [![1.12](icons/versions/12.png)](## "Supports 1.12")

### Gameplay/Balancing

- [Starter Structure](https://www.curseforge.com/minecraft/mc-mods/starter-structure/) - Allows packdevs to add structures to be generated at spawn on new world creation. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up")
- [Undurability](https://www.curseforge.com/minecraft/mc-mods/undurability/) - Makes all item unbreakable by default. [![1.18+](icons/versions/plus/18.png)](## "Supports 1.18 and up")
- [Void Island Control](https://curseforge.com/minecraft/mc-mods/void-island-control/) - World generation customizer, adding a configurable skyblock-esque void world type. [![1.12](icons/versions/12.png)](## "Supports 1.12")

### Scripting

- [CraftTweaker](https://curseforge.com/minecraft/mc-mods/crafttweaker/) - In-game feature tweaker allowing developers to change certain mechanics using a custom language called ZenScript. [![1.7+](icons/versions/plus/7.png)](## "Supports 1.7 and up")
- [Custom Machinery](https://curseforge.com/minecraft/mc-mods/custom-machinery/) - Data-driven utility for adding custom machines with heavy integration with both CraftTweaker and KubeJS. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up") [![no1.20](icons/versions/no/20.png)](## "Doesn't support 1.20")
- [Game Stages](https://curseforge.com/minecraft/mc-mods/game-stages/) - Library, allowing packdevs using mods like CraftTweaker or GroovyScript to add certain "game stages" to players based on their level of progression, that then could be used to alter custom mechanics. [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up")
- [GroovyScript](https://curseforge.com/minecraft/mc-mods/groovyscript/) - Sandboxed Apache Groovy in-game interpreter that includes interfaces for tempering with the game. [![1.12](icons/versions/12.png)](## "Supports 1.12")
- [KubeJS](https://curseforge.com/minecraft/mc-mods/kubejs/) - JavaScript script loader allowing for interactions with the game mainly through the event system. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up")
- [Packmode](https://curseforge.com/minecraft/mc-mods/packmode/) - Library that adds a "pack mode" system which can be used to alter custom mechanics based on the mode the player selected. [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up")
- [ProbeJS](https://curseforge.com/minecraft/mc-mods/probejs/) - Addon to KubeJS, adding support for VSCode intellisense. [![1.18+](icons/versions/plus/18.png)](## "Supports 1.18 and up")
- [ProbeJS Legacy](https://www.curseforge.com/minecraft/mc-mods/probejs-legacy/) - Experimental port of ProbeJS for 1.16.5. [![1.16](icons/versions/16.png)](## "Supports 1.16") [![forge](icons/modloaders/forge.png)](## "Forge exclusive") [![experimental](icons/misc/experimental.png)](## "Experimental") [![fork](icons/misc/fork.png)](## "Forked") 

### Utility

- [AtlasViewer](https://www.curseforge.com/minecraft/mc-mods/atlasviewer/) - Atlas explorer that allows you to view and inspect atlases and the textures comprising them through and in-game menu. [![1.18+](icons/versions/plus/18.png)](## "Supports 1.18 and up") 
- [Celestial](https://www.curseforge.com/minecraft/mc-mods/celestial/) - Allows packdevs to customize per-dimension skyboxes through a simple JSON config system. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up") [![no1.20](icons/versions/no/20.png)](## "Doesn't support 1.20")
- [In Control!](https://www.curseforge.com/minecraft/mc-mods/in-control/) - Mob spawn editor, configurable through JSON files. [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up") [![forge](icons/modloaders/forge.png)](## "Forge exclusive")
- [Lockdown](https://curseforge.com/minecraft/mc-mods/lockdown/) - Tool that allows you to package maps with your modpack as world as world presets. [![1.7+](icons/versions/plus/7.png)](## "Supports 1.7 and up") [![no1.20](icons/versions/no/20.png)](## "Doesn't support 1.20") [![forge](icons/modloaders/forge.png)](## "Forge exclusive")
- [Modern Custom Discs](https://curseforge.com/minecraft/mc-mods/modern-custom-discs/) - Packdev tool that allows you to add customizable music discs with .ogg files. [![1.16](icons/versions/16.png)](## "Supports 1.16") [![forge](icons/modloaders/forge.png)](## "Forge exclusive")
- [Oh The Trees You'll Grow](https://curseforge.com/minecraft/mc-mods/oh-the-trees-youll-grow/) - Library that allows packdevs to add custom trees with Minecraft's .nbt structure files. [![1.20](icons/versions/20.png)](## "Supports 1.20")
- [Pefect Spawn](https://curseforge.com/minecraft/mc-mods/perfect-spawn/) - Utility, allowing packdevs to modify the spawn position of the player with a higher degree of control. [![1.7](icons/versions/7.png)](## "Supports 1.7") [![1.12](icons/versions/12.png)](## "Supports 1.12")
- [Resource Reloader](https://curseforge.com/minecraft/mc-mods/resource-reloader/) - Utility, adding a set of commands to reload only specific types of resources (instead of reloading all of them with F3+T), speeding up the process. [![1.12](icons/versions/12.png)](## "Supports 1.12")
- [TellMe](https://curseforge.com/minecraft/mc-mods/tellme/) - Asset information dumper/lister, accessible using in-game commands. [![1.7+](icons/versions/plus/7.png)](## "Supports 1.7 and up")
- [Totally Harmonious Item Stages](https://curseforge.com/minecraft/mc-mods/totally-harmonious-item-stages/) - Gamestage-based utility mod for item gating. [![1.16+](icons/versions/plus/16.png)](## "Supports 1.16 and up") [![forge](icons/modloaders/forge.png)](## "Forge exclusive")

## Apps

### Assetmaking

#### Music

- [FL Studio](https://www.image-line.com/) - Paid tool professional tool for making digital music. [![freeware](icons/misc/freeware.png)](## "Conditionally free")
- [LMMS](https://lmms.io/) - Free and open-source multimedia studio prefect for beginners as well as advanced users. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [Tenacity](https://github.com/jd/tenacity/) - Open-source fork of Audacity, the software used for editing audio at a lower level. [![foss](icons/misc/foss.png)](## "Free and open-source") [![fork](icons/misc/fork.png)](## "Forked")

#### Textures/Models

- [Aseprite](https://www.aseprite.org/) - Source-available (previously open-source) tool for creating textures using pixelart. [![paid](icons/misc/paid.png)](## "Paid")
- [Blockbench](https://www.blockbench.net/) - Specialized tool for editing Minecraft's various model formats. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [LibreSprite](https://libresprite.github.io/) - Free and open-source maintainted fork of Aseprite, based on its last available version under a free license. [![foss](icons/misc/foss.png)](## "Free and open-source") [![fork](icons/misc/fork.png)](## "Forked")
- [LibreSprite Dotto](https://libresprite.github.io/Dotto/) - Version of LibreSprite available directly inside a web browser. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [Minecraft Title Generator](https://youtu.be/iGaufrACVj4/) - Blockbench plugin that adds a simple way to generate logos in the Minecraft style.

### Coding

- [VSCode](https://code.visualstudio.com/) - General Integrated Development Environment perfect for working with Java and scripting languages in the same app. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [VSCodium](https://vscodium.com/) - Distribution of VSCode, providing compiled binaries of it licensed under an open-source license. [![foss](icons/misc/foss.png)](## "Free and open-source") [![fork](icons/misc/fork.png)](## "Forked")

### CLI [![foss](icons/misc/foss.png)](## "Free and open-source")

- [CarbonJS](https://github.com/malezjaa/carbonjs/) - Advanced package manager for KubeJS scripts implementing version control, written in Rust. [![unmaintained](icons/misc/unmaintained.png)](https://github.com/malezjaa/carbonjs/blob/main/README.md "Unmaintained/abandoned (click for info)") [![borked](icons/misc/borked.png)](## "Borked")
- [KJSPKG](https://github.com/Modern-Modpacks/kjspkg/) - Simple lightweight-ish crossplatform package manager for KubeJS scripts written in Python 3. [![1.12+](icons/versions/plus/12.png)](## "Supports 1.12 and up")

#### Packaging

- [AlmostPacked](https://github.com/AlmostReliable/almostpacked/) - Automated git hook developed by the Almost Reliable team allowing for distribution of modpacks.
- [InstanceSync](https://github.com/Vazkii/InstanceSync/) - Git hook allowing for distribution of modpacks using version control. [![unmaintained](icons/misc/unmaintained.png)](## "Unmaintained/abandoned")
- [Packwiz](https://packwiz.infra.link/) - Automation utility for distributing modpacks across the CurseForge and Modrinth ecosystems, written in Go.
- [Pax](https://github.com/froehlichA/pax/) - Automation utility for distributing modpacks across the CurseForge ecosystem, focused on collaboration and written in Nim.

### Discord Bots [![foss](icons/misc/foss.png)](## "Free and open-source")

- [Linkie](https://linkie.shedaniel.dev/) - Bot providing various useful utilities for mod and modpack developers, the main one being the ability to see information about various mappings.

### Productivity

- [Draw.io](https://draw.io/) - Tool for creating diagrams that also allows for real-time collaboration, very useful for visualizing code. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [Figma](https://figma.com/) - Web tool that allows you to edit design files and FigJam boards which are perfect for brainstorming. [![freeware](icons/misc/freeware.png)](## "Conditionally free")
- [Notion](https://www.notion.so/) - Closed-source cooperative/individual online text document editor using a custom format with extensive markup features. [![freeware](icons/misc/freeware.png)](## "Conditionally free")
- [Obsidian](https://obsidian.md/) - Open-source individual local document editor using the Markdown format for text files and including various visualization features. [![freeware](icons/misc/freeware.png)](## "Conditionally free")
- [Trello](https://trello.com/) - Cloud organization-focused app including various productivity tools, mainly a cooperative ToDo board. [![freeware](icons/misc/freeware.png)](## "Conditionally free")

## Resources

### Discord Servers

- [Almost Reliable](https://discord.com/invite/ThFnwZCyYY/) - Community owned by the Almost Reliable team, offering support for their mods.
- [BlameJared](https://discord.blamejared.com/) - Developer-owned community for CraftTweaker, offering support for modpack developers who use it.
- [FTB](https://go.ftb.team/discord/) - Server owned by the FTB team, providing support for modpacks using their mods and more.
- [Kekscord](https://discord.gg/rhayah27GC/) - Server created by Keksuccino, the developer of FancyMenu, Drippy Loading Screen, and Load My Resources, offering support for both of these mods and more.
- [Latvian.dev](https://discord.gg/lat/) - Server created by the developers of KubeJS, the members of which frequently provide help for other people using it and JavaScript in general.
- [Minecraft Pack Development (MPD)](https://discord.gg/R4tBduGsne/) - General community of modpack developers, sharing their works and help to others.
- [Modded Minecraft](https://discord.gg/moddedmc/) - General community for all things modded Minecraft.
- [Modded Minecraft Reviews](https://discord.gg/vGphAv7TZA/) - Developer-owned server for the Modded Minecraft Reviews project.
- [Modern Modpacks](https://discord.modernmodpacks.site/) - Developer-owned server for the Modern Modpacks organization, also offering help for other 1.16 project maintainers.
- [Packwiz](https://discord.gg/Csh8zbbhCt/) - Official support server for packwiz.
- [Shedaniel's Development](https://discord.gg/Vs9AVkxjYY/) - Server owned by shedaniel, the creator of Roughly Enough Items and other mods, providing support for them.
- [The 1.12 Modding Coalition](https://discord.gg/2JZ8KePDKd/) - Community offering help for all 1.12 mod and modpack creators alike.

### Websites

- [CFLookup](https://cflookup.com/) - Webpage allowing you to look up deleted mods in the CurseForge ecosystem by typing in their IDs. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [CurseRinth](https://curserinth.kuylar.dev/) - Frontend for the CurseRinth api, a CurseForge api mirror that's fully compatable with Modrinth's api. [![foss](icons/misc/foss.png)](## "Free and open-source") [![unmaintained](icons/misc/unmaintained.png)](## "Unmaintained/abandoned") [![borked](icons/misc/borked.png)](## "Borked")
- [CurseRinth (Tizu Fork)](https://curserinth-tizu.vercel.app/) - Forked version of CurseRinth, maintained by tizu69. [![foss](icons/misc/foss.png)](## "Free and open-source") [![fork](icons/misc/fork.png)](## "Forked")
- [KJSPKG Lookup](https://kjspkglookup.modernmodpacks.site/) - Simple registry/search website for all package on KJSPKG. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [Linkie](https://linkie.shedaniel.dev/) - WebUI-version of the Linkie discord bot. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [Modded Minecraft Reviews](https://mmcreviews.com/) - Community-maintained hub offering reviews for submitted mods and modpacks, includes the ability for maintainers of projects to respond to the reviews.
- [Modpack Index](https://www.modpackindex.com/) - Reimplementation of CurseForge's modpack list/search UI with more filters and other various features. [![foss](icons/misc/foss.png)](## "Free and open-source") [![unmaintained](icons/misc/unmaintained.png)](## "Unmaintained/abandoned") 
- [Opticraft](https://red-studio-ragnarok.github.io/Opticraft/) - List of various 1.12.2 optimization mods including the descriptions of what they do.
- [Unused Textures](https://github.com/malcolmriley/unused-textures/) - Large repository of freely-licensed Minecraft-styled textures. [![foss](icons/misc/foss.png)](## "Free and open-source")
- [Useful Mods](https://github.com/TheUsefulLists/UsefulMods/) - General list of mods for different versions that improve the performance of the game and fix various bugs.

#### Fun

- [ThisRecipeDoesNotExist](https://thisrecipedoesnotexist.modernmodpacks.site/) - Random recipe generator, can serve as a inspiration for your actual custom recipes. [![foss](icons/misc/foss.png)](## "Free and open-source")

---

[**Go Back Up**](#contents)

## Contributing

If you wish to add something to the list, please first read the [contribution guidelines](CONTRIBUTING.md).

## License

[![CC0](https://upload.wikimedia.org/wikipedia/commons/thumb/4/43/CC_Zero_badge.svg/88px-CC_Zero_badge.svg.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This repository is licensed under CC0, and thus freely available for redistribution and modification without any conditions.

---

**THIS PROJECT IS NOT ENDORSED BY THE MAINTAINERS OF [THE ORIGINAL AWESOME LIST]((https://github.com/sindresorhus/awesome/)), NOR WILL IT EVER BE SUBMITTED TO THE LIST BECAUSE [THEIR REQUIRED GUIDELINES](https://github.com/sindresorhus/awesome/blob/main/pull_request_template.md/) ARE NOT BEING FULLY ENFORCED HERE. ~~well, as with most projects in that list :trollface:~~**
