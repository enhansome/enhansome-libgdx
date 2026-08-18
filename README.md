[![Awesome libGDX Logo](logo.png "Awesome libGDX Logo")](https://libgdx.com/)

# Awesome libGDX with stars

> <a href="https://libgdx.com/"><img src="https://libgdx.com/assets/images/logo.png" alt="libGDX Logo" align="right" style="margin-right: 25px" height=40></a>
>
> [libGDX](https://libgdx.com/) is a relatively low level, free, open source cross platform game development framework written in Java.
>
> This list is a curated collection of awesome resources, tools, tutorials, and projects using the [libGDX](https://libgdx.com/) game framework to help developers make *awesome* games, conforming to the [Awesome Manifesto](https://github.com/sindresorhus/awesome/blob/master/awesome.md) ⭐ 497,344 | 🐛 102 | 📅 2026-08-18.
>
> Contributions *very welcome* but first see [Contributing](#contributing).

***

## Contents

* [Resources](#resources)
  * [Artificial Intelligence](#algorithms-and-ai)
  * [Controllers](#controllers)
  * [Editors](#editors)
  * [Entity Component System (ECS)](#entity-component-system-ecs)
  * [Physics](#physics)
  * [Services](#services)
  * [Setup and Deployment](#setup-and-deployment)
  * [User Interface](#user-interface)
  * [Visual Effects](#visual-effects)
  * [Audio](#audio)
  * [Others](#others)
* [Tutorials](#tutorials)
  * [Getting Started](#getting-started)
  * [Advanced](#advanced)
* [Assets](#assets)
* [Community](#community)
* [Other Lists](#other-lists)

***

## Resources

*Resources that can be used in libGDX code to boost the framework's capabilities.*

### Algorithms and AI

* [gdx-ai](https://github.com/libgdx/gdx-ai) ⭐ 1,301 | 🐛 33 | 🌐 Java | 📅 2024-10-01 - Artificial Intelligence framework featuring Steering Behaviors, Formation Motion, Pathfinding, Behavior Trees and Finite State Machines.
* [Simple Graphs](https://github.com/earlygrey/simple-graphs) ⭐ 52 | 🐛 1 | 🌐 Java | 📅 2023-01-10 - A java library for graph data structures and algorithms (including fast pathfinding).

### Controllers

* [sdl2gdx](https://github.com/electronstudio/sdl2gdx) ⭐ 88 | 🐛 12 | 🌐 Java | 📅 2024-10-01 - Powerful gamepad implementation using SDL. Supports hundreds of controllers under the same mapping, rumble, and hotplugging.
* [gdx-controllers](https://github.com/libgdx/gdx-controllers) ⭐ 86 | 🐛 7 | 🌐 Java | 📅 2025-06-08 - Adds support to gamepads and joysticks.
* [gdx-controllerutils](https://github.com/MrStahlfelge/gdx-controllerutils) ⭐ 63 | 🐛 2 | 🌐 Java | 📅 2023-11-19 - Adds Scene2D button input support, user configurable button mappings and hotplugging for LWJGL2.

### Editors

* [HyperLap2D](https://github.com/rednblackgames/HyperLap2D) ⭐ 439 | 🐛 11 | 🌐 Java | 📅 2026-08-18 - Visual editor for complex 2D worlds and scenes with a runtime for libGDX.
* [Mundus](https://github.com/JamesTKhan/Mundus) ⭐ 190 | 🐛 22 | 🌐 Java | 📅 2026-05-18 - World/level editor for 3D worlds with a runtime for libGDX.
* [Spine](http://esotericsoftware.com/) - Skeleton-based animation tool that focuses specifically on 2D animation for games.

### Entity Component System (ECS)

* [Ashley](https://github.com/libgdx/ashley) ⭐ 931 | 🐛 20 | 🌐 Java | 📅 2023-06-26 - A Java entity system inspired by Ash & Artemis.
* [Artemis-odb](https://github.com/junkdog/artemis-odb) ⭐ 832 | 🐛 41 | 🌐 Java | 📅 2023-04-14 - High performance java based Entity-Component-System framework.

### Physics

* [Box2D](https://libgdx.com/wiki/extensions/physics/box2d) - One of the most popular physics libraries for 2D games.
* [Bullet](https://libgdx.com/wiki/extensions/physics/bullet/bullet-physics) - 3D Collision Detection and Rigid Body Dynamics Library.
* [jbump](https://github.com/tommyettinger/jbump) ⭐ 36 | 🐛 0 | 🌐 Java | 📅 2021-02-16 - Easy to implement AABB collision detection useful for platformers and other simple 2D games.

### Services

* [steamworks4j](https://github.com/code-disaster/steamworks4j) ⭐ 549 | 🐛 33 | 🌐 Java | 📅 2026-05-06 - A thin wrapper which allows Java applications to access the Steamworks C++ API.
* [gdx-pay](https://github.com/libgdx/gdx-pay) ⭐ 242 | 🐛 9 | 🌐 Java | 📅 2026-06-16 - Provides a cross-platform API for InApp purchasing.
* [gdx-gamesvcs](https://github.com/MrStahlfelge/gdx-gamesvcs) ⭐ 116 | 🐛 7 | 🌐 Java | 📅 2025-03-11 - Easy integration of gameservices, such as Google Play Games, Apple Game Center, and more.
* [gdx-fireapp](https://github.com/mk-5/gdx-fireapp) ⭐ 67 | 🐛 12 | 🌐 Java | 📅 2024-04-15 - Cross-platform API for Firebase.
* [gdx-facebook](https://github.com/TomGrill/gdx-facebook) ⭐ 58 | 🐛 8 | 🌐 Java | 📅 2018-12-04 - Provides cross-platform support for Facebook Graph API.
* [gdx-firebase](https://github.com/TomGrill/gdx-firebase) ⭐ 37 | 🐛 1 | 🌐 Java | 📅 2019-04-24 - Cross-platform (only Desktop/Android) API for Firebase.
* [gdx-gameanalytics](https://github.com/MrStahlfelge/gdx-gameanalytics) ⭐ 30 | 🐛 0 | 🌐 Java | 📅 2021-02-06 - Game Analytics REST API client implementation for libGDX. Works on all backends.

### Setup and Deployment

* [Packr](https://github.com/libGDX/packr) ⭐ 2,621 | 🐛 31 | 🌐 C++ | 📅 2024-04-11 - Packages your JAR, assets and a JVM for distribution on Windows, Linux and macOS.
* [gdx-liftoff](https://github.com/tommyettinger/gdx-liftoff) ⭐ 678 | 🐛 22 | 🌐 Kotlin | 📅 2026-08-18 - A modern setup tool for libGDX that supports more backends and allows adding libraries with one click.
* [libgdx-library-template](https://github.com/tommyettinger/libgdx-library-template) ⭐ 14 | 🐛 0 | 📅 2026-02-02 - A skeleton project for making new libraries, since they need different config.

### User Interface

* [VisUI](https://github.com/kotcrab/vis-ui) ⭐ 772 | 🐛 27 | 🌐 Java | 📅 2026-06-02 - Allows to create nice looking UI in libGDX using scene2d.ui. Note this is not a UI editor.
* [gdx-skins](https://github.com/czyzby/gdx-skins) ⭐ 536 | 🐛 1 | 📅 2022-08-22 - Free Scene2D GUI skins.
* [Skin Composer](https://github.com/raeleus/skin-composer) ⭐ 477 | 🐛 18 | 🌐 Java | 📅 2024-05-20 - Create skins for libGDX scene2d.ui with a graphical interface.
* [TypingLabel](https://github.com/rafaskb/typing-label) ⭐ 161 | 🐛 3 | 🌐 Java | 📅 2024-05-30 - A libGDX Label that appears as if it was being typed in real time.
* [InGameConsole](https://github.com/StrongJoshua/libGDX-inGameConsole) ⭐ 135 | 🐛 8 | 🌐 Java | 📅 2021-09-17 - Allows a developer to add a console (similar to how it is featured in Source games) to their game.
* [TextraTypist](https://github.com/tommyettinger/textratypist) ⭐ 135 | 🐛 8 | 🌐 Java | 📅 2026-08-18 - Like TypingLabel (below), but also supports styles, emoji, multiple fonts, clickable links, etc.
* [PieMenu](https://github.com/payne911/PieMenu) ⭐ 88 | 🐛 1 | 🌐 Java | 📅 2022-12-01 - Radial menus for Scene2D that are highly flexible and easy to customize.
* [gdx-dialogs](https://github.com/TomGrill/gdx-dialogs) ⭐ 79 | 🐛 5 | 🌐 Java | 📅 2019-12-31 - Provides cross-platform support for native dialogs.
* [TenPatch](https://github.com/raeleus/TenPatch) ⭐ 49 | 🐛 1 | 🌐 Java | 📅 2022-03-30 - An alternative to libGDX's 9patch implementation that implements multiple stretch regions.
* [msdf-gdx](https://github.com/maltaisn/msdf-gdx) ⭐ 40 | 🐛 2 | 🌐 Kotlin | 📅 2023-12-21 - Provides lightweight utilities to draw high-quality MSDF (multi-channel signed distance field) text on libGDX.
* [Freetype](https://libgdx.com/wiki/extensions/gdx-freetype) - Generate BitmapFonts of your desired size on the fly from lightweight .ttf font files.
* [Ray3K Skins](https://ray3k.wordpress.com/artwork/) - Free Scene2D.UI skins with example code, custom drawables, and experimental features.

### Visual Effects

* [Box2DLights](https://github.com/libgdx/box2dlights) ⭐ 266 | 🐛 15 | 🌐 Java | 📅 2026-07-17 - 2D lighting framework that uses Box2D for raycasting and OpenGL ES 2.0 for rendering.
* [gdx-gltf](https://github.com/mgsx-dev/gdx-gltf) ⭐ 249 | 🐛 22 | 🌐 Java | 📅 2026-02-05 - GLTF 3D file format support (import/export), PBR shaders, and others advanced rendering.
* [gdx-vfx](https://github.com/crashinvaders/gdx-vfx) ⭐ 212 | 🐛 8 | 🌐 Java | 📅 2026-08-15 - Flexible post-processing shader visual effects based on libgdx-contribs-postprocessing.
* [Shape Drawer](https://github.com/earlygrey/shapedrawer) ⭐ 202 | 🐛 13 | 🌐 Java | 📅 2024-10-20 - A performant alternative to ShapeRenderer that avoids Batch flushing.
* [libgdx-screenmanager](https://github.com/crykn/libgdx-screenmanager) ⭐ 113 | 🐛 0 | 🌐 Java | 📅 2025-08-09 - A screen manager for libGDX supporting various transition effects
* [colorful-gdx](https://github.com/tommyettinger/colorful-gdx) ⭐ 91 | 🐛 0 | 🌐 Java | 📅 2026-04-29 - Expands how tinting can affect colors; also has many pre-written shaders.
* [Particle Park](https://github.com/raeleus/Particle-Park) ⭐ 77 | 🐛 1 | 🌐 Java | 📅 2022-02-01 - A showcase of downloadable particle effects with live previews.
* [gdx-graph](https://github.com/MarcinSc/gdx-graph) ⭐ 49 | 🐛 0 | 🌐 Java | 📅 2026-04-26 - Provides a GUI to design your rendering pipeline and shaders, and a library to easily incorporate them into your games.
* [HackLights](https://github.com/aliasifk/HackLights) ⭐ 27 | 🐛 0 | 🌐 Java | 📅 2022-08-31 - Lightweight framebuffer based lighting engine for libGDX.

### Audio

* [gdx-miniaudio](https://github.com/rednblackgames/gdx-miniaudio) ⭐ 77 | 🐛 3 | 🌐 C | 📅 2026-08-16 - Advanced Cross Platform Audio Engine for libGDX based on MiniAudio.
* [TuningFork](https://github.com/Hangman/TuningFork) ⭐ 39 | 🐛 1 | 🌐 Java | 📅 2026-07-09 - Advanced 3D audio features for libGDX desktop users.
* [gdx-pd](https://github.com/mgsx-dev/gdx-pd) ⭐ 27 | 🐛 8 | 🌐 Java | 📅 2020-05-28 - Pure Data extension for libGDX.
* [gdx-sfx](https://github.com/spookygames/gdx-sfx) ⭐ 23 | 🐛 0 | 🌐 Java | 📅 2025-01-25 - Some goodies for better sound effects in libGDX.

### Others

* [KTX](https://github.com/libktx/ktx) ⭐ 1,460 | 🐛 12 | 🌐 Kotlin | 📅 2025-06-28 - Kotlin extensions and utilities for libGDX.
* [Texture Packer GUI](https://github.com/crashinvaders/gdx-texture-packer-gui) ⭐ 705 | 🐛 18 | 🌐 Java | 📅 2024-08-09 - A simple way to pack and manage texture atlases for libGDX game framework.
* [libGDX Plugin](https://github.com/BlueBoxWare/LibGDXPlugin) ⭐ 159 | 🐛 2 | 🌐 Kotlin | 📅 2026-05-29 - A plugin for IntelliJ IDEA and Android Studio that adds a number of libGDX features and tools, such as color previews and additional inspections for common mistakes.
* [noise4j](https://github.com/czyzby/noise4j) ⚠️ Archived - Simple map generators based on various procedural content generation tutorials.
* [gdx-jnigen](https://github.com/libgdx/gdx-jnigen) ⭐ 88 | 🐛 12 | 🌐 Java | 📅 2026-08-18 - Small library that allows C/C++ code to be written inline with Java source code.
* [anim8-gdx](https://github.com/tommyettinger/anim8-gdx) ⭐ 54 | 🐛 1 | 🌐 Java | 📅 2026-05-30 - Allows saving (animated) GIFs and PNGs from sequences of Pixmaps, with configurable dithering if needed.
* [gdxGifRecorder](https://github.com/Anuken/GDXGifRecorder) ⭐ 38 | 🐛 1 | 🌐 Java | 📅 2019-11-20 - A utility class that records a GIF and saves it automatically.
* [gdx-dbgagent](https://github.com/PokeMMO/gdx-dbgagent) ⭐ 33 | 🐛 0 | 🌐 Java | 📅 2022-03-25 - Java Agent for debugging common issues, like objects not being disposed and constants such as Color.WHITE being modified.

## Tutorials

*Tutorials for newbies and seasoned developers alike.*

### Getting Started

* [Deploying with JPackage](https://github.com/raeleus/skin-composer/wiki/libGDX-and-JPackage) ⭐ 477 | 🐛 18 | 🌐 Java | 📅 2024-05-20 - A tutorial on deploying libGDX games with JPackage via Gradle commands.
* [Progress Bar Design](https://github.com/raeleus/skin-composer/wiki/The-Man-Who-Killed-Hitler-and-then-The-Progress-Bar) ⭐ 477 | 🐛 18 | 🌐 Java | 📅 2024-05-20 - Discusses the pros and cons of different progress bar design techniques with examples.
* [Scene2D.UI From the Ground Up](https://github.com/raeleus/skin-composer/wiki/From-the-Ground-Up:-Scene2D.UI-Tutorials) ⭐ 477 | 🐛 18 | 🌐 Java | 📅 2024-05-20 - Covers the basics of UI design in Scene2D, libGDX's premiere scene graph and layout toolkit.
* [Official libGDX Wiki](https://libgdx.com/wiki/) - Official libGDX wiki that contains a huge amount of information.
* [Tann's Hello libGDX](https://colourtann.github.io/HelloLibgdx/) - An excellent guide for beginners on how to create a game from scratch.
* [Development Tutorial Playlist by Phillip Mod Dev](https://www.youtube.com/playlist?list=PLLwCf-qdpyEnB_FO_1HkUFh7smwGNjAaC) - A series of videos going over the basics of libGDX.
* [Brandon Grasley's Space Shooter Game](https://www.youtube.com/playlist?list=PLfd-5Q3Fwq0WKrkEKw12nqpfER3MG5_Wi) - Video tutorial series on making a complete Android game from scratch.
* [Creating a Launcher](https://youtu.be/3l5F7f7vfTU) - Video tutorial on using libGDX to make a game launcher.
* [JSON in Game Dev](http://mana-break.blogspot.com/2014/06/power-of-json-in-game-development-items.html) - General tutorial on using JSON for storing data.
* [libGDX External Tutorials](https://libgdx.com/wiki/articles/external-tutorials) - Big list of official unofficial tutorials.

### Advanced

* [Code Hotswapping](https://youtu.be/zKfh6WuaikQ) - Video tutorial on enabling code hotswapping for libGDX projects to increase productivity.
* [Dynamic Textures with Pixmap](https://javadocmd.com/blog/libgdx-dynamic-textures-with-pixmap/) - Details how to create a mask using Pixmaps.
* [iOS Deployment Tutorial](https://link.medium.com/vgYo0mSi3W) - Deploying to iOS in 2019 using RoboVM.
* [Sub-pixel Perfect Smooth Scrolling](http://code-disaster.com/2016/02/subpixel-perfect-smooth-scrolling.html) - Pixel-perfect smooth scrolling.
* [Introduction to 3D Series](https://www.youtube.com/playlist?list=PLjUR2MkQ0cuHZ70Ps8F9WMyoyKHKAbYvQ) - A tutorial series on libGDX 3D using gdx-gltf.

### General Learning Material

* [Book of Shaders](https://github.com/patriciogonzalezvivo/thebookofshaders) ⭐ 6,980 | 🐛 68 | 🌐 GLSL | 📅 2026-02-28 - Step-by-step guide through the abstract and complex universe of Fragment Shaders. GLSL.
* [Game Programming Patterns](https://gameprogrammingpatterns.com/) - Architecture and design patterns for games.

## Assets

*Collection of free and high quality assets to get your game to the next level.*

* [Kenney Assets](https://kenney.nl/) - High quality assets for your game, from 2D and 3D art to sound effects.
* [OpenGameArt.org](https://opengameart.org/) - Repository offering a variety of open content assets.
* [Game-Icons.net](http://game-icons.net/) - Repository containing heaps of cool game related graphics.
* [Jsfxr](https://chr15m.itch.io/jsfxr) - Quickly create unique sound effects by pressing a few buttons, excellent for prototyping.
* [freesound.org](https://freesound.org/) - Huge collaborative database of audio snippets, samples, recordings, bleeps.

## Community

*Get in touch with other libGDX developers to collaborate and get help.*

* [Discord](https://discord.gg/4S8pQqc) - An active chat with various leaders from the community available every day. **Recommended**
* [Reddit](https://www.reddit.com/r/libgdx/) - Unofficial subreddit for libGDX. Not a lot of activity.

## Other Lists

*Other awesome lists that might be useful to libGDX developers.*

* [Java](https://github.com/akullpp/awesome-java) ⭐ 48,772 | 🐛 9 | 📅 2026-08-17 - A curated list of awesome Java frameworks, libraries and software.
* [Magic Tools](https://github.com/ellisonleao/magictools) ⭐ 17,145 | 🐛 12 | 🌐 Markdown | 📅 2026-08-17 - A list of Game Development resources to make magic happen.
* [Kotlin](https://github.com/KotlinBy/awesome-kotlin) ⭐ 11,373 | 🐛 55 | 🌐 Kotlin | 📅 2026-07-03 - A curated list of awesome Kotlin related stuff.
* [Game Networking](https://github.com/MFatihMAR/Awesome-Game-Networking) ⭐ 8,643 | 🐛 2 | 🌐 C | 📅 2026-07-29 - A Curated List of Game Network Programming Resources.
* [Awesome Gamedev](https://github.com/Calinou/awesome-gamedev) ⭐ 3,103 | 🐛 13 | 📅 2026-07-07 - A collection of free software and free culture resources for making amazing games.
* [Game Talks](https://github.com/hzoo/awesome-gametalks) ⭐ 1,179 | 🐛 6 | 📅 2024-05-09 - A curated list of gaming talks (development, design, etc).
* [Game Accessibility Guidelines](http://gameaccessibilityguidelines.com/) - A straightforward reference for inclusive game design, to ensure that games are just as fun for as wide a range of people as possible. **Recommended**

***

## Contributing

Contributions welcome! Read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-18._
