---
title: Games
---

This page collects games built with the Flow Graph!

Feel free to add information on project. Every game entry should provide these few elements, so this list wouldn't look boring.
* Title and short description of the game.
* At least a single embedded image, or a link to the game video.
* (Optional) Short info on how Flow Graph helped you with the development of this game.

Only games publicly available in game stores should be added here.
<br/><br/>

## The Thaumaturge
The Thaumaturge is an RPG set in the tumultuous times of 20th-century Warsaw, developed by Fool's Theory and published by 11 bit studios. Esoteric creatures known as salutors roam the streets. You play as Wiktor, a talented thaumaturge, who captures and commands those spirits.

* We switched our quest system from blueprint-based solution in mid-production, and we were very happy with the decision. We managed to automatically convert most of quest graphs.
* We built cinematic dialogue system on top of Flow Graph. It gave us easy-to-use graph for creating non-linear dialogues. Having a single Flow Node for dialogue section allowed us to greatly simplify code responsible for generating Level Sequence from raw data of dialogue lines (text and parameters filled by written, narrative designers and cinematic artitsts).

<a href="https://www.youtube.com/watch?v=ZUxJxPIR3Kk"><img src="https://img.youtube.com/vi/ZUxJxPIR3Kk/mqdefault.jpg" alt="The Thaumaturge | Example of non-linear cinematic dialogue"></a>

## The Legend of Khimorii
The Legend of Khiimori is a system-driven game where you explore the untamed land of 13th century Mongolia as a brave courier rider. You breed and train horses with specialized abilities to explore every aspect of this diverse and fascinating landscape.

* Initially we worked with an in-house system migrated from previous projects, though the flow plugin was considered already then. Late in pre-production we rolled a big refactor to swap in Flow as core for scripting the quest flow - replacing the stricter, tree-based way of the old system.
* Our quests are all root flow instances. We had parametrization/procedural quests from the old system and later integrated those with data pins, though there's consideration to fully lean on data pins in the future. Our quests also have a feature named traits, which are optional, shareable behaviors/data providers that designers can add to quests and based on which parts of e.g. UI can be switched on or off.

<a href="https://www.youtube.com/watch?v=ZUxJxPIR3Kk"><img src="https://img.youtube.com/vi/ZUxJxPIR3Kk/mqdefault.jpg" alt="The Thaumaturge | Example of non-linear cinematic dialogue"></a>