# Video Game AI
Video Game AI Research. Started 4/14/2023, Covering advanced AI states, using the unity game engine (Unity 2021.3.21f1 HDRP)

## Introduction

Video Game AI has always been a unique part of game development. At the time of writing, multiplayer games have taken the industry by storm, meaning AI isn't needed at all in some cases. However, singleplayer games play a massive role in the industry. During the course of this research project, i will be trying to find the most intelligent way possible to implement animal AI.

## Why?


I've been a gamer ever since around the age of 4, and throughout that time period i've played a lot of different games. Something that has fascinated me recently is the afterthought of animal AI, specifically in survival games. I'd like to point to some great games which suffer from this issue, one being the game *Rust*. Rust is a great multiplayer survival expeirence but i think it lacks a decent animal AI. In my opinion, animals shouldn't be viewed as just something in a game and considered a chore to hunt. Animals should scare you and instill some kind of fear into players. When was the last time you played a game where the idea of a animal attacking you generally feared you? Animals are almost always considered by gamers to be 'clunky' and generally not appealing. But in real life, animals are interesting, and fascinating to just watch. This is not the case in most survival video games. I'm not setting out to create a whole real life-like simulation of a forest ecosystem, i just want to create something that is fun to be in a world with. 

## How

This AI will be a advanced state machine that bases it's decisions on multiple factors. States won't change cause the animal feels like it's thristy. States will only change if it passes a *Think Function*. This *Think* function will contain tons of logic, trying to replicate how a animal in real life would make decisions. Any major occurence in the animals physical or mental state will call this *Think* function, like for example, being hungry, being thristy, and feeling threatened. But other occurences such as minor ones will need to happen either A. Overtime or B. Multiple times. 
