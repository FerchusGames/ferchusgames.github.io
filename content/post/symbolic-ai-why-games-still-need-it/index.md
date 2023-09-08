---
title: "Symbolic AI: Why Games Still Need It"
date: 2023-05-06T11:17:13-06:00
draft: false
tags: ["AI", "Symbolic", "Game", "Ferchus", "FerchusGames", "Amerike"]
---

## What is Symbolic AI?

Symbolic AI is a branch of artificial intelligence that uses a symbolic system to represent and manipulate knowledge. A symbolic system consists of two components: a set of knowledge, which can be words, numbers, sentences, pictures, or any other kind of information, and a reasoning algorithm to generate problem solutions or new knowledge.

Search and knowledge are intrinsically linked in AI. The more knowledge you have, the less searching you need to do for an answer you need. Conversely, the more search you can do, the less knowledge you need. This trade-off between knowledge and search is unavoidable in any AI system. Symbolic systems acknowledge this and give their algorithms a large amount of knowledge to process. They have been widely applicable to games, as they can model various aspects of game logic, such as blackboard architectures, pathfinding, decision trees, state machines, and more.

## The Rise of Deep Learning

In recent years, there was a tendency to assume that symbolic approaches were dead, and that deep learning was the future of AI. Deep learning is a form of statistical computing that uses neural networks to learn from data and perform tasks such as image recognition, natural language processing, and game playing. Deep learning is essentially a compute intensive search technique: it tries to find patterns in data by adjusting the weights of the network connections.

One of the most impressive examples of deep learning is AlphaGo Zero, a program that learned to play the game of Go from scratch, without any human guidance or prior knowledge. AlphaGo Zero had minimal knowledge of the rules of the game, but extraordinary amounts of processing time and resources: it played millions of games against itself to improve its skills.

## Simplicity Drives Control

However, this does not mean that symbolic AI is obsolete or irrelevant. In fact, for most game applications, symbolic AI is still preferable and superior to deep learning. For example, a character that needs to use a health pack when injured can be told that explicitly using a simple rule:

 ```
IF injured THEN use health pack
```

This rule requires no search at all: it directly tells the character what to do in a given situation. It is also easy to understand, modify, and debug by developers. On the other hand, if we wanted to use deep learning to achieve the same behavior, we would need to train a neural network with a lot of data and feedback, which would take a lot of time and resources. And even then, we would not have much control or insight into how the network makes its decisions.

## Symbolic AI Prevails

The only way any algorithm can outperform another is to consume more processing power or to be optimized toward a specific set of problems. However, games are usually designed to run on consumer hardware, which means that graphics and sound take up the majority of the processing power. For AI, this means that game developers have to be smart and efficient with their algorithms. In many cases, low computation / high knowledge approaches are often the clear winners.

This is not to say that statistical computing techniques are not useful for games. They can be very useful for specific problems that require complex pattern recognition or adaptation. However, for games they are often unnecessary: the same effect can often be achieved better, faster, and with more control using a simpler approach.

In conclusion, AI used in games is still largely based on symbolic technology. Symbolic AI offers many benefits for game development: it is expressive, efficient, transparent, and flexible. Symbolic AI is not dead: it is alive and kicking in games.

## References

Millington, I. (2019). AI for games (pp. 5–8). Crc Press, Taylor & Francis Group.