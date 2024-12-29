# Introduction

Gilienor game is my collaboration of methods learnt within our first semester. This is a treasure hunting game which allows two players to traverse the world battling monsters, avoiding traps, finding treasure and ultimately defeating the boss in the dungeon at the end of the game. The players use familiar controls 'wasd' in order to travel across the game board with markers showing that something (or someone) may be in the path ready to attack. 

# Project Overview

## Inspiration
I decided for my game to give it a theme in which i was comfortable with and could add in my creative side. I took a lot of my inspiration from a popular mmorpg 'Runescape' in order to clearly set my goals of what i wanted the players to achieve. The town, enemies and the boss are taken as inspiration however the direction is randomly generated so that the user experiences different monsters and traps each time they play.

## Direction of the game
From the introduction, the player is given a brief overview of what is transpiring in the land. This is to give player purpose and direction so they understand what they need to achieve in order to beat the game. This is paired with warnings of the dangers and players will need to prepare themselves before setting off on their journey. I wanted to add in a shop to not only give the world life, but to also give players the option to take a break from the dangers outside of the town walls.

## player interaction
With this being a somewhat rpg game, i wanted the player to have full freedom of the items/spells that they can use in combat. I added in the shop mechanic so that the player can stock up on supplies to give them that edge. For example i added in a dodge ability that would lower the damage take from enemies, this is especially helpful if they come up against something with higher health/damage giving a level of difficulty to the game. As the players traverse the world, if they do come across an enemy that they cannot fight due to low health, they can avoid the encounter with the 'Run' option. This adds a level of safety and control to the player, however, this is not available for the boss.

## Movement and combat
During combat, the game goes into a turn based mode where the players and monsters will take turns to either attack or use an item/spell. For this prototype i have made it so the player always goes first just for ease with understanding how the program runs but also giving a chance to run from the encounter just in case. In the future, the turn timer would also be randomised to give the true feeling of an ambush.

# Challenges and Solutions

## Binary Search
With my binary search, i have had issues implamenting it into my game. I have tried various ways to incorporate it however I wasnt able to get it to find an outcome where the outcome is either a selection (Inventory) or map interaction. This was due to the format of the map grid itself and how all of the other entities react with it such as traps, monsters and locations. In this case i have reverted to a simplified randomiser for the map and list functions for the inventory.

## Timeframe
My lack of understanding for algorithms caused a very large setback in my project. A lot of my time has been spent in trial and error with not much of a breakthrough. I have therefore stuck with what i understand and attempted to make the game enjoyable whilst also demonstrating the skills i understand whilst also pushing myself.

## Simplicity
I wanted the game to be easy to pick up and understand so i kept the instructions on how to play in every instance whilst the game is running. This was due to an earlier itteration of the game, some of the controls seemed uncommon and may confuse the player (such as the (c)ast magic button). This was countered with the options printed as the game was played.

## Variety
For my encounters i wanted this to be the random side of my game to simulate wandering around a wilderness where ambushes were the big threat. For this i created my list of monsters that varied in difficulty based on their health and damage. This was easy enough to implament and really gave some depth to the encounters.

## 2 player
I wasnt entirely sure how to create a 2 player session. I had implamented multiple stages during the game where it would check if a second player was present, however, it wouldnt run properly and would further skip any interaction with the player. I think with time and understanding i would be able to implament it properly and maybe making the game technically simpler it would be easier to understand.

# Search Algorithms

## Content


# Pseudocode/flowchart

## Flowchart


## Pseudocode


# Test Evidence

## Movement

## Combat

## End Goal


# Conclusions

This project has been very difficult to grasp for me, however i feel the techniques that i have implamented have been executed well to give the experience intended. I am happy that the game can play from start to finish with minor errors, if any. However, i am still confused with algorithms and how to implement them in a project like this successfully. In the future i need to spend more time understanding binary search 