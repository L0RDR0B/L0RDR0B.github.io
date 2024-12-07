---
layout: post
title:  "iGGi Game Development 1: Versus Tower Defence"
date:   2022-11-18 12:00:00 +0000
categories: coursework
permalink: "/:categories/iggi-tower-defence"
---

![Menu](../img/Tower_Defence_1.png "The main menu of Versus Tower Defence.")

[The full project can be found on the GitHub Repository][tower-defence].

Versus Tower Defence is a two-player versus game created as part of the Game Development 1 training module during the first year of my PhD research at the EPSRC CDT for Intelligent Games & Game Intelligence (iGGi).

The game takes the simple concept of the Tower Defence genre, with a twist - now, rather than the player fighting against a horde of enemy waves, they are fighting against another player, and control both the towers and the enemies! The objective is to destroy the opponent's base before they can do the same to you.

![Level1](../img/Tower_Defence_2.png "An overview of the game's layout on the first level.")

There are six tower types to choose from: Basic Level 1, 2 and 3 (increasing in strength and cost), Sniper (slow, long ranged), Rapid-Fire (fast, short-ranged) and Area-of-Effect (damages multiple nearby enemies). Players can only place towers on their colour-coded half of the map.

Likewise, there are six unit types to recruit: Weak, Basic and Strong (increased health and cost but decreased speed), Swarm (numerous, weak but fast), Bomber (destroys nearby enemy towers upon death) and Boss (very high health, strongest but slowest).

Both towers and units cost Money to deploy. Money is earned steadily over time, as well as whenever you defeat an enemy unit or when your unit successfully damages the enemy base. Each base produces a Weak unit periodically to ensure both sides have a constant flow of units.

![Level2](../img/Tower_Defence_3.png "An overview of the game's layout on the second level.")

Two different map layouts were implemented. The first, a very basic layout, and the second, where the units cross back and forth into each others' territories as they progress.

A video demonstration of the game in action is shown below:

<iframe width="560" height="315" src="https://www.youtube.com/embed/kKFXZtiydtI?si=41kYaJgvaFLgtVPa" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

[tower-defence]: https://github.com/Toby-Best/TowerDefenceIGGI/tree/final