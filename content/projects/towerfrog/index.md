---
title: "Towerfrog"
description: "An online and LAN basic recreation of the game Towerfall using an authoritative server and client-side prediction."
summary: "An online and LAN basic recreation of the game Towerfall using an authoritative server and client-side prediction."
date: 2024-06-13T12:00:00-06:00
showReadingTime: false
showWordCount: false
tags: ["Unity", "Multiplayer", "Game Programming"]
draft: false
---

{{< youtubeLite id="FGd5RAU7RZg" label="Towerfrog Gameplay">}}

##

<iframe frameborder="0" src="https://itch.io/embed/2796284?bg_color=191919&amp;fg_color=ffffff&amp;link_color=945bfa&amp;border_color=474747" width="552" height="167"><a href="https://ferchus.itch.io/towerfrog">Towerfrog by Ferchus</a></iframe>

Tower Frog is a multiplayer game where players engage in platform-based, player-vs-player combat. You must shoot and dodge enemy arrows in a 2D arena filled with teleportation portals, reminiscent of Pac-Man's action style. This project was developed for the networked video games class taught by Professor Edgar Moreno.

## Learning the Fundamentals

We began by learning the fundamentals of Fishnet Networking Evolved framework. This simplifies the network coding for games with its extensive documentation and built-in elements. In class, we first covered the basic concepts of the framework, including RPC (Remote Procedure Call) and how connections between multiple computers work. We learned about game synchronization, server-authoritative models, and client-server systems.

## Remote servers with PlayFlow 

We then moved on to the PlayFlow service, which offers cloud-based, authoritative servers and matchmaking systems. Initially, the game was meant to be a prototype copy of Don't Starve Together, but realizing its complexity, I switched to developing this game. The name Towerfrog is a parody of the original game's title, Towerfall. Many years ago, I had a lot of fun playing Towerfall with my sister locally, but the game lacked an online mode. This motivated me to create a version playable remotely on multiple computers using Fishnet.

## Development and Challenges

Once we understood the concepts, development began. I decided to use Fishnet's prediction model. Unlike the popular RPC method, the prediction model sends player inputs to the server, which then executes them, ensuring synchronization and reducing cheating possibilities. This model is more secure because the server handles all execution, and players only send inputs.

However, implementing this model was challenging due to limited documentation and its recent addition to Fishnet. Ensuring synchronization between clients and the server proved difficult. Fortunately, Professor Edgar Moreno provided significant support, especially in the final two months of the class.

## Final Implementation and Demo Day

In the end, the game worked, but playing through PlayFlow's cloud services resulted in some lag and synchronization bugs. I suspect this is due to the prediction model's demands, possibly overloading the server. For the school's demo day event, where we showcase the semester’s projects, I created a LAN version, which provided a smoother and more competitive experience using Fishnet Network Discovery for server advertisement and connections.

## Available on Itch.io

You can download the LAN version of the game from Itch.io. The cloud version used PlayFlow's premium matchmaking service, which I only paid for one month to present for the class. I hope you enjoy it and have fun playing Towerfrog!

<iframe frameborder="0" src="https://itch.io/embed/2796284?bg_color=191919&amp;fg_color=ffffff&amp;link_color=945bfa&amp;border_color=474747" width="552" height="167"><a href="https://ferchus.itch.io/towerfrog">Towerfrog by Ferchus</a></iframe>

## GitHub Repository

{{< github repo="FerchusGames/towerfall-unity-fishnet" >}} 