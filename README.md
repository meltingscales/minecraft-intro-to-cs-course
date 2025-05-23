# Amethyst Algorithms: Minecraft Intro to CS Course

Note to myself: PAUSE this course and just make a mod called `AmethystShards`.
Henry: You need to really understand how to write mods. `04-13-2025 HP`

![Amethyst Algorithms](amethyst-algorithms.png)

my desire to teach and love of minecraft all rolled into one

in sha' Allah 2025 I get to teach at a university

## course links

TBD

## summary

This course is meant to get you up to speed with many different important computer science topics using the game Minecraft as a substrate.

You'll learn basic Java syntax, how to set up an editor, how to run Java code, and slowly get more advanced until you're creating new items, new mobs, new world-generation, and more advanced concepts like custom GUIs, abstraction, interfaces, profiling, runtime complexity, 3d model editing, and more!

## tools

- a computer with 8GB of RAM
- Java 21
- JetBrains IntelliJ IDEA
- TODO: Pixel art editor for Minecraft art?

## high level topics

### easy

- debugging
- ide setup
- basic syntax
- object oriented programming (and why it can be evil OR useful)

### medium

- data types
- interfaces
- abstraction
- texture mapping
- rendering
- custom GUI

### hard

- a* pathfinding
- profiling
- runtime complexity
- optimization
- 3d models

## ⭐ course overview

### project 1: coding basics

<!-- TODO: Steal from https://javabook.mccue.dev/classes/instances as it's very useful, and iterative -->
<!-- Thank you to Ethan McCue! -->

- 1.1: setup the IDE
- 1.2: basic syntax that is ONLY related to minecraft
- 1.3: basic commands, example: `player.sendMessage("Hello, Minecraft!");` or `world.setBlock(player.getPosition().up(), Blocks.DIAMOND_BLOCK);`
- 1.4: variables and datatypes, examples:
  - `String playerName = player.getName();`
  - `int playerX = player.getPosition().getX();`
  - `boolean isDay = world.isDaytime();`
- 1.5: order of evaluation

### project 2: talk about tooling

- why are we using IntelliJ IDEA?
- how do we debug?
- what is gradle?
- how do you run gradle targets? list targets? list dependencies?
- what even is a dependency?
- what is neoforged?
  - how to get help with neoforged?

### project 3: let's make our own tree!

- new wood block + texture
- new leaf block + texture
- how do we extend the OakTree class?

### project 4: let's make our own ore, AmethystOre, a crafting recipe, and an AmethystPickaxe pickaxe item

### project 5: aside: how can we learn more about making mods? (discord/StackOverflow/other OSS)

### project 9: sidetrack: How to run your own server

- docker
- VMs
- locally hosted
- port forwarding, what is it?
- how to test port forwarding: https://mcsrvstat.us/server/minecraft.henrypost.net
- how to set up your own domain
- alternative: use tailscale
- how to do backups: plugins? cron jobs?
- how to run a modpack server?

## inspiration/learning
- over 20,000 hours into this glorious game
- [Modding By Kaupenjoe: Minecraft Modding 1.20.X for Forge](https://www.udemy.com/course/minecraft-modding-120x-for-forge)
  - [course code](https://github.com/Kaupenjoe/Forge-Course-1.20.X)
- [Applied Energistics 2 mod, and studying its code to understand how to use NeoForged](https://github.com/AppliedEnergistics/Applied-Energistics-2)
- [Botania](https://github.com/VazkiiMods/Botania)
- [NeoForged Keymappings](https://docs.neoforged.net/docs/misc/keymappings/)
- [NeoForged Events](https://docs.neoforged.net/docs/concepts/events/#registering-an-event-handler)
- [hfbpOrbMod](https://github.com/meltingscales/hfbpOrbMod)
