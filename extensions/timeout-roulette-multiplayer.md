---
title: Timeout roulette with multiplayer (by TheShiningOne)
description: Timeout roulette with singlepayer, multiplayer and duel games.
published: true
date: 2022-09-21T12:56:08.636Z
tags:
editor: markdown
dateCreated: 2022-09-21T11:27:27.379Z
---

# Tutorial
<div class=“iframe-container”><iframe src="https://www.youtube.com/embed/SP0VkEmmbpQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; fullscreen" allow fullscreen style="border: none; max-width: 100%; width: 100%; aspect-ratio: 16/9;"></iframe></div>

# Import code
```
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
```


# Installation
In Streamer.bot select `Import` from the top left.
Copy the `Import Code` and paste it into the `Import String`.

After importing code you will need to enable commands, because for security reasons they are disable by default when imported. Reset command should be set to mods only, it resets the game in case it got stuck somehow.

Then you need to set the paths to audio files with gun sounds inside `roulette_Engine` action. All text and timeouts are also configurable.

References required.
```
mscorlib.dll
System.dll
System.Runtime.dll
```
# Configuration
Inside `roulette_Engine` action you can find manu class attributes which can be changed to you liking, for example sounds, timeouts and printed text.

Inside `Reset` method you can set how many players can play by changing `NumberOfChambers` and `MaxNumberOfPlayers`.

# Example Usage
To start the game viewer just need to type !roulette in the chat and he will be prompted with the instructions.

Multiplayer versions got two mods: normal and knockout, where game ends when someone "eats the bullet".

Game supports Twitch and YouTube chats. In case of multistreaming both chat can play in one game, but mind the delay between chats.

> Right now YouTube doesn't have command or API to timeout users, so you will have to do it manually via chat window.
{.is-warning}

# Contributors

 - [<i class="mdi mdi-twitch"></i> ShiningOne](https://www.twitch.tv/shiningone)
 {.contributors}