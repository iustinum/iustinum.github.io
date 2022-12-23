---
layout: page
title: build your own world
description: a game engine for generating 2D tile-based world
img: 
importance: 2
category: school
---

***design document and code cannot be publicly shared per course guideline, though they are available upon [request](mailto:jwu25@berkeley.edu).***

Build Your Own World (BYOW) is a game that randomly generates 2D tile-based worlds where players can navigate using the keyboard. Each world
consists of a series of pseudorandomly generated rooms connected by hallways. A player in the form of an avatar will spawn in a random room
at the beginning of an instance of the game, in which users will need to control to complete an objective. In our instance, a player wins if 
and only if they collect a all the coins from maze before a forest fire reaches the player.


### Notable Features ###

- Ability for the user to “replay” their most recent save, visually displaying all of the actions taken sequentially since the last time a new world was created. The replay would display up to the same final state as would occur if the user had loaded the most recent save.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/byow1.gif" title="byow_replay" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- Avatar customization

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/byow2.gif" title="byow_customization" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

- Avatar and background animations

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/byow4.gif" title="byow_animation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>


### Takeaways ###

Though less challenging then Gitlet in terms of complexity, byow teaches me to use Google and Stack Overflow when stuck
on specific features. For example, my project partner and I referenced dungeon generation algorithms from professional
game developers when we designed our random room generation functions. I also found myself more inclined to apply the data
structures taught in 61B into more applicable scenarios in this game.

