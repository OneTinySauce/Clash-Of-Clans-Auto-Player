# Design

**Group 10:** _Clash of Clans Auto Player_\
**Date:** March 24th, 2021\
**Group members:** Teng Ao, Miles Brown, Ran Li, Devin O'Neal, Ulugbgek Abdullayev, and Junjian Yin

## 1. Description

Clash of Clans Autoplayer will allow players to save time and minimize frustration. Our Autoplayer automates all of the boring parts of Clash of Clans so that you can free up your time to do other things. The system can train your troops, build/upgrade structures, collect your resources, and even take care of destroying rocks and trees for you. Clash of Clans Autoplayer saves you time and helps you enjoy playing the game even more.

The full system will have the ability to harvest resources, train troops, destroy rocks/trees and build buildings from a queue, all automatically and customizable in the settings for each action. A simple UI will run alongside the Clash of Clans emulator to allow the user to change these things while playing. For Clash of Clans players who don’t enjoy the repetitive gameplay loops, or want to succeed in the game, the Clash of Clans Autoplayer helps you get through all the boring repetitive gameplay and succeed in the game. Our product does not overwhelm your device with inappropriate ads and has a user friendly interface.

## 2. Architecture

![Our UML Package Diagram](https://github.com/OneTinySauce/Clash-Of-Clans-Auto-Player/blob/main/screenshots/Autoplayer%20Package%20Diagram.png?raw=true)

Above is the UML Package Diagram for our system, which I designed close to the examples given because I was not sure how to create a package diagram for our system. I believe to make a more accurate package diagram, we will need to split our system into classes with some restructuring.

## 3. Class Diagram

![Our Class Diagram](https://github.com/OneTinySauce/Clash-Of-Clans-Auto-Player/blob/main/D5%20Class%20Diagram.PNG)

## 4. Sequence Diagram

## 5. Design Patterns

Desing Pattern 1: (Structural) *Singleton* - method to add building to queues and to retrieve the queue

![](https://github.com/OneTinySauce/Clash-Of-Clans-Auto-Player/blob/main/buildingQueue.PNG)

Figure 5.1 - UML Diagram of the implementation of the Singleton patter in the BuildQueue class

## 6. Design Principles