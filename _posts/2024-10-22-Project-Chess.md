---
title: "PROJECT: Chess"
date: 2024-10-22 12:00:00 +0000
categories: [blog, project]
tags: [chess, java]
description: A chess engine and application
---

# Chess
[Github](https://github.com/Ademfcan/chess)\
Over the last couple of months I have been working on a rather interesting project. Building a chess engine and surrounding application from scratch. Today I would like to showcase the project, highlight some features, and share some struggles I have faced along the way

> Please note this project is very much still in progress, and lots of things (especially ui) need some work to be "production ready"
{: .prompt-info}

## Overview
The central component of this project is the **chess engine**. Esssentially it takes in a given chess position, and "tries" different moves to see what the best move is. Connecting this, the application side manages a chessboard and allows the user to interact with the chess engine, and play games against it. Of course this is a gross oversimplification, as you can do much more than just play an engine. 

The first part of this blog will go over general features and capabilites, with the later parts diving into the specifics. 

## Features
Using this chess engine/application, you can:
- Play games at various difficulties against either the custom chess engine, or [stockfish](https://stockfishchess.org/)
- Play a diverse campaign against various chess personalities, starting easy and finishing at master level
- Play 1v1 matches against another player locally
- Play ranked online matches against others with different time modes
- Simulate and watch games where **any** of the computer options can play against each other, with time constraints.
- Play puzzles to improve your decision making skills
- Load games through pgn
- Take any game and analyze it, with recommended moves and evaluation of the moves you played
- Save your progress with an account




## Gallery

#### Home Screen
![Home Screen](/assets/img/Project-Chess/homemenu.png)

#### Local 1v1 Game
![Local 1v1 Game](/assets/img/Project-Chess/local1v1.png)

#### Campaign Menu Screen
![Campaign Menu](/assets/img/Project-Chess/campaignmenu.png)

#### Campaign Game
![Campaign Game](/assets/img/Project-Chess/insidecampaign.png)

#### Move Evaluation
![Move Evaluation](/assets/img/Project-Chess/moveevaluation.png)

#### Move Suggestion
![Move Suggestion](/assets/img/Project-Chess/movesuggestions.png)

#### Online Game
![Online Game](/assets/img/Project-Chess/onlinegame.png)

#### Load Pgn
![Load Pgn](/assets/img/Project-Chess/pgnloadingmenu.png)

#### An easy puzzle
![Easy Puzzle](/assets/img/Project-Chess/easypuzzle.png)

#### A hard puzzle
![Hard Puzzle](/assets/img/Project-Chess/hardpuzzle.png)

#### Video of my computer beating stockfish
{% include embed/youtube.html id='NlpMeYA5lgU' %}