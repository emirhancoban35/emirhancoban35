# Hey, I'm Emirhan 👋

### Game Developer · Playable Ads · Mobile Prototyping

I've been building games and software since my teenage years and working professionally in the game industry since 2022.

Most of my work revolves around **Unity, mobile games, playable ads, gameplay systems and rapid prototyping**.

Over the years I've worked across production mobile games, publishing-driven prototypes, internal Unity tools, independent projects and playable-ad production.

I especially enjoy building systems that are lightweight, reusable and easy to iterate on — whether that's a playable-ad framework, a gameplay prototype or a larger game architecture.

This profile is a mix of my newer production-focused work and older projects that I've intentionally kept close to their original implementations.

---

# 🚀 Featured Work

## 🧱 Color Block Playable Framework

A reusable playable-ad framework inspired by **Color Block Jam**, built with **Unity + Luna / Playworks**.

I didn't want it to be just another one-off playable, so I built the project around reusable gameplay, visual and ad-flow configurations.

Different grid layouts, block shapes, movement restrictions, exits, themes and creative flows can be prepared through editor tooling without rewriting the core gameplay logic for every variant.

### Highlights

- Configurable grid layouts and board shapes
- Multiple block shapes and movement restrictions
- Multiple exit directions and conditions
- Configurable visual themes and palettes
- Custom Unity editor workflow
- Prepared geometry and shared meshes
- Preallocated visual effects
- Centralized runtime updates
- Grid-based gameplay without physics simulation
- Responsive playable-ad UI and safe-area handling

The current **80-block stress-test** setup runs at around:

**16 draw calls · ~2 ms frame time in Playworks · ~671 KB ironSource build report**

[View Repository →](https://github.com/emirhancoban35/color-block-playable-ad)

---

## 🌀 Color Coil

A mobile puzzle game I designed and developed during my collaboration with **Voodoo's publishing ecosystem**.

Color Coil was much more than a programming project for me. I worked across the complete prototype lifecycle — from the initial game idea and core mechanic to level design, onboarding, progression, creative production and publishing iteration.

The project included puzzle mechanics, progression systems, tutorials, power-ups, special gameplay elements, mobile UI and CPI-oriented creatives.

It eventually went through Voodoo's testing and evaluation process, giving me hands-on experience with the full:

**Idea → Prototype → Polish → Creative Production → Market Test → Publishing Feedback**

workflow.

The source repository is private, but Color Coil remains one of the projects that shaped how I approach mobile game development and product iteration.

---

## 🀄 Okey Rummy

A modular Unity project supporting both **Classic Okey and 101 Okey** on top of the same reusable tile-game architecture.

The project originally started as **101 Okey Lite**, an older hand-written Unity project I built while getting deeper into OOP, modular systems and responsibility separation. I later returned to the original foundation and expanded it into a much broader Okey / Rummy framework.

Today, the project includes a complete local table experience with **one human player and three AI opponents**, configurable game rules, local rooms, partnership play, scoring, turn timers and separate Classic Okey / 101 Okey gameplay policies.

### Some of the systems include

- Classic Okey and 101 Okey sharing the same table, rack and input infrastructure
- Runs, sets, pairs, real jokers and physical fake jokers
- Configurable opening thresholds, penalties and rising openings
- Public meld boards and tile layoffs
- Joker reclaim rules
- Individual and opposite-seat partnership modes
- Local room creation, browsing, passwords and configurable match lengths
- Multiple AI behaviors with replaceable decision policies
- Match history and separate scoring implementations for each game mode
- Drag-and-drop rack organization and group movement
- Turn timers with automatic legal timeout actions

The architecture is split into separate assemblies:

**Okey.Core** contains the Unity-independent game state, rules, scoring, AI and room logic.  
**Okey.Configuration** adapts ScriptableObjects into runtime configuration.  
**Okey.Presentation** contains passive views and input handling.  
**Okey.Composition** connects the application through Zenject and coordinates gameplay.

The core gameplay doesn't branch on game-name enums. Different game modes provide their own rules, opening policies, scoring and bot behavior through replaceable boundaries.

The project also contains **EditMode and PlayMode test suites** covering game rules, deck generation, AI decisions, scoring, room flow, pointer interactions, scene bindings and real gameplay flows.

A large part of the original foundation comes from my earlier hand-written Unity work, while the current version expands that architecture into a reusable and configurable system for Okey-style games.

[View Repository →](https://github.com/emirhancoban35/okey-rummy)

---

## 🌐 State.io Playable Ad

One of my earlier playable-ad projects, inspired by **State.io**.

I built this project before I started working with Luna / Playworks, so it uses a more direct **WebGL + MRAID** advertising workflow.

It focuses on lightweight gameplay logic, mobile-ad constraints, interaction tracking, store redirects and keeping the runtime small enough for playable-ad environments.

Compared with my newer playable work, the implementation is deliberately simpler, but it represents an important earlier stage of my playable-ad development.

[View Repository →](https://github.com/emirhancoban35/state-io-playablead)

---

## 🚗 Car Simulator

A more traditional Unity gameplay project focused on vehicle systems, driving and gameplay interactions.

I keep this project in my portfolio because it represents a different side of my Unity work outside playable ads and short-form mobile prototypes.

The project was structured around reusable gameplay responsibilities rather than treating everything as a single quick prototype.

[View Repository →](https://github.com/emirhancoban35/car-sim)

---

## 🕴️ MrPresident

An unfinished but relatively large experimental Unity project from an earlier period of my development journey.

I intentionally keep this repository close to its original implementation.

It represents how I approached larger Unity architectures before modern code-generation workflows became part of everyday development.

The project contains modular gameplay systems, reusable services, responsibility separation and dependency management with **Zenject**.

The game itself was never completed, but the architecture is the main reason I still keep the project public.

[View Repository →](https://github.com/emirhancoban35/mrpresident)

---

## 🧩 Place Blocks

An older mobile puzzle prototype from my early game-development years.

It was built with a much more experimental workflow than my current projects, but I keep it public because it shows an earlier stage of how I approached puzzle mechanics, gameplay logic and Unity project structure.

[View Repository →](https://github.com/emirhancoban35/place-blocks)

---

# 🧪 Independent Game Development

Alongside my professional work, I've been developing independent Unity projects since **2022**.

This has been one of the main ways I've experimented with mechanics and learned how to take ideas beyond isolated programming tasks.

My independent work has covered mobile puzzle games, hyper-casual and hybrid-casual concepts, playable ads, gameplay systems, level design, mobile UI, editor tools, optimization and publishing preparation.

Some of the public repositories on this profile started during this period and were later expanded or rebuilt as more reusable systems.

I still use independent projects to explore new gameplay ideas, production workflows and technical approaches outside of my day-to-day work.

---

# 💼 Industry Experience

## 🎮 UDO Games
### Game Developer
`Jul 2026 - Present`

Currently working on a production mobile basketball game.

My responsibilities span **core gameplay, UI, rapid prototyping and internal development tooling**.

During my time on the project I've worked through major gameplay iterations and product pivots, taking responsibility for systems well beyond UI-focused implementation.

My work has included core gameplay systems, input and interaction flows, score and reward systems, onboarding, feature prototyping, UI integration, internal Unity tooling, production debugging and polish.

The project has also given me hands-on experience working inside an established mobile-game architecture under short production and iteration cycles.

---

## ⚽ Blay Games
### Game Developer Intern
`Jul 2025 - Aug 2025`

Worked on **GOKA Street**, an online mobile football game.

I contributed both to gameplay-related systems and internal production tooling.

My work included systems and tools around Training Mode, spawn protection, gameplay feedback, Normcore synchronization, gyro simulation, editor tooling, matchmaking / reward workflows and production utilities.

I also built Unity tools, camera rigs and animation-testing utilities used to make creative and marketing production faster.

Technologies included **Unity, Normcore, UI Toolkit, Addressables, DOTween and Odin Inspector**.

---

## 🧩 Voodoo
### Game Developer — Publishing Collaboration
`Apr 2025 - Sep 2025`

Designed and developed mobile puzzle prototypes in collaboration with **Voodoo's publishing ecosystem**, while taking part in the **Voodoo Academy** program.

My main project during this period was **Color Coil**.

I worked across game ideation, gameplay design, Unity development, level design, onboarding, progression, CPI creatives and iteration based on publishing feedback.

This experience gave me direct exposure to the mobile publishing workflow and changed the way I think about games — not only as technical products, but as experiences that need to be tested, measured and iterated on.

---

## 🟡 Ruby Games — a Rovio Studio
### Long-Term Software Developer Intern
`Jun 2022 - Sep 2023`

My first long-term professional experience in the game industry.

I worked across both internal software development and game-related projects.

On the software side, I developed internal automation tools, Slack-based workflows, database-backed systems and web utilities using technologies including **.NET Core, SQL, JavaScript, HTML, CSS and Node.js**.

I also supported mobile game prototype development and collaborated with product, level design, marketing and creative teams.

This was one of my first opportunities to see how engineering, product development and creative production come together inside a game studio.

---

# 🛠 Technologies

**Game Development**  
Unity · C# · ScriptableObjects · Zenject · DOTween · UI Toolkit · uGUI

**Playable Ads**  
Luna / Playworks · WebGL · MRAID · JavaScript · HTML5

**Production & Tooling**  
Git · Odin Inspector · Addressables · Firebase · Custom Unity Editor Tools

---

# 🔬 Current Interests

Right now I'm especially interested in:

- Playable-ad production and creative iteration
- Reusable gameplay frameworks
- Mobile puzzle mechanics
- Lightweight runtime systems
- Rapid gameplay prototyping
- Unity editor tooling
- Mobile-game architecture
- Turning reusable systems into faster production workflows

I generally prefer building systems that can be extended and iterated on instead of solving the same problem from scratch every time.

---

# 🔗 More About Me

For my full professional background and career timeline:

[LinkedIn →](https://www.linkedin.com/in/emirhancoban)
