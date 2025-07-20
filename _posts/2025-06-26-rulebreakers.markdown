---
layout: post
title:  "7th International Summer School on Artificial Intelligence and Games Game Jam: Rulebreakers"
date:   2025-06-26 12:00:00 +0000
categories: gamejam
permalink: "/:categories/summer-school-2025-rulebreakers"
---

![Gameplay](../assets/img/Rulebreakers_1.png "Gameplay screenshot of Rulebreakers.")

[The full project can be found on the GitHub Repository][github].

Rulebreakers is a two-player versus game created as part of the 7th International Summer School on Artificial Intelligence and Games, hosted at the University of Malmö in Sweden, across the week of the 23rd to 27th June.

The game was conceptualised, prototyped, programmed and playtested within the last two days of the Summer School, which were dedicated for the Game Jam. Created in collaboration with Daniel Togelius, Muhammad Umair Nasir, Stefan Nordborg Eriksen and Weijie Huang, all fellow participants of the Summer School. This was programmed in Unity.

The game pits two players in a Connect 4-style grid, where they take turns to place a token on the grid. However, each turn, players may choose to 'break' the rules, submitting a new 'Joker Rule' if they so wished to a Large Language Model (LLM) that restricts what spaces can or cannot be played for the rest of the game. We used the model GROQ for rules generation.

![Rules](../assets/img/Rulebreakers_2.png "Gameplay screenshot of the possible Win and Lose Conditions.")

Players may choose from a list of pre-determined conditions for winning or losing, such as placing tokens in a 4-In-A-Row orientation or in a Tetris L-Block orientation, or allow the game to randomly choose a win and lose condition from its list.

Despite our best efforts, sadly we ran out of time to fully implement and debug the game prior to presentations. We accidentally managed to break the LLM connectivity in merging branches, and were unable to fix it in time. Instead, we resorted to using our paper prototype, and simply had the players agree upon the rules each turn and validate whether they were acceptable requests.

Regardless, this game was a lot of fun to implement, and it was great to meet so many different people at the Summer School and work together!

![Prototype](../assets/img/Rulebreakers_3.png "Photo of our paper prototype being demonstrated.")

[github]: https://github.com/GameAISchool2025members/RuleBreakers