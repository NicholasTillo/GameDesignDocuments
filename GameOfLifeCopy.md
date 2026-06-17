# Serious Game Design Document Outline

A game design document is the blueprint from which a game is to be built. As such, every single detail necessary to build the game should be addressed. The larger the team and the longer the design and development cycle, the more critical is the need. For your purpose, the intent is to capture as much as possible of your design. I want you to think big…bigger than what you are able to develop. I also want you to be clear about what the software delivers and what the design entails. Use this document to define the ultimate game, but be clear about what you have delivered.

This document also includes elements that are normally considered part of a software design document but are included to give a more complete picture of the game.

You do not need to include all topics and you do not need to use the numbered outline structure for your document, but as a team you should review all items to be sure that you have considered all of these elements and why they are or are not relevant to your game. It should also be easy for me to identify the topic that you are covering.

---

## Title Page (page and all elements are required)

### Game Name
The Game Of The Meaning Of Life
### Tag Line
A tag line is a statement or phrase that brands your game. Famous tag lines are "Just do it!", "Got milk?", "The King of Beers". Or from the video game world: Dark Souls: "Prepare to Die", Dead Space: "Only the Dead Survive", Deus Ex: "Trust no one. Question Everything", Pokémon: "Gotta catch em all!"

### Team
Nicholas Tillo

### Date of Last Update

---

## Revision History
Only needed if you are working on multiple versions of the document or making major changes to the game. Probably not needed for most games in this class. However if I review a version that then significantly changes, include the history.

---

## Game Overview (required of all games)
This is intended as a cohesive paragraph or two that lets someone understand what you are working on. It must include:

### Purpose of the Game
The message of the game is to help explore the meaning of life and I mean help cope with some meaning coming after death. The captian will be the main character that explores this, he will die in one of the early cutscenes but his legacy will live on. . 


### Target Audience
Its me, I love this game, there is no other reason for me to make it other than I love it and its helping me cope with Roma's death. 

### Genre(s)

- Puzzle, Story, Sci-Fi 
---

## Gameplay
The gameplay loop will start the player in the space ship, in which they are presented with a random grid of the game of life, representing the space ship's population. They can then take actions to change the game state, buying upgrades, changing the grid by changing specific cells, or eventually contunie by going to the next iteration. 

### Objectives
The goal is to make it to the "end" of the story. with the 5 cutscenes, in order to see what the meaning of life truely is. There can also be a survival mode with the goal of getting as far as possible. 

### Mission, Challenge or Puzzle Structure

---

## Mechanics (Key Section)
These are topics that should be covered if relevant. All games are different and not everything applies. Consider this a checklist to help you capture all that is important. It should be complete enough that someone could build a clone of your game based on this detail.


### Model of the Game Universe
Think of it as a simulation of a world — how do all the pieces interact? If it is a puzzle game, there may be no universe to discuss, but there is the layout and the structure of the puzzle. Included in the universe are:


### Economy
2 Resoures the player will use, money, and resource 1. Money will be used to affect the state of the game within the gameplay loop. the resource 1 will be used to affect the initial starting point of the game, and carries throughout the gameplay loop iterations. 
- The idea of morale is interesting, it fits with the theme of the population surviving, but it might be for later. 

### Character Actions


#### Objects
##### Classes: 

Alive: As In Conways Game Of Life Each alive cell that stays alive generates 1 money. 
Dead: As in Conways Game Of Life
Zombie: If > 3 alive neighbours, or < 1 neighbour, turns dead, else stays a zombie and turns the rest of the surrounding alives into zombies. 
Mechanic: required >1 surrouinding alive cell, produces 1 addtiional 10 money per round. 
Chef: makes the surrounding alive not starve to death from overpopulation or underpopulation. But costs 25 gold per round to employ.

Only gotten through the pet store event. 
Sandshark - IMPLEMENT
Plorbian - IMPLEMENT
Dog - IMPLEMENT

Springtrap: If an alive cell is around it, it will kill it, turning it into a corpse. 
Life: Turns all surrounding cells into life, only occurs at the very end of the game. 
Wall: Lierally just seperates rooms. 
Zealot: I forgot what this one does. 

TO Implement: 
- Bartender, 
- Some machinery, maybe a generator of some sort, maybe a fabricator that creates things. 
- Radar scanner. 

#### Random Events: 

Zombie Invation - Spawns like 5 zombies randomly. 
Springtrap Appears - Spawns a springtrap randomly 
Pet Shop - Be able to pay for the 3 exotic pet options. 

Finding Life - win the game. 

To Implement: 
- Something about a warp gate. 
- Astroid Belt, random people dying. 
- Ecological Dead Zone, (turn off shader in the back, and reduce the amount of people alive.)
- Religious Reform
- Spaceship Upgrade Bay. 
- Spaceship Attack from outside sources. 
    - Create a little mini game that you defend it, if you get hit, it will kill a bunch of random alive cells. 

#### Actions

While the player is in the gameplay loop. They are able to do the following: 
Change any cell to the classes the player has unlocked (Usually for a price), Purchase In round Upgrades. 

Upgrades: The possible list of upgrades that can be made by the player are: 
Increased Grid Size. 
Additional Ships



### Screen Flow
!! -- iNSERT DIAGRAM HERE--!! 
Start from main menu, then to main game, then to death screen, or main menu to upgrade menu, then back. 


### Game Options


### Replaying and Saving
The player is able to save and load from the save file, located in. This saves the current upgrades (non ingame upgrades), and the current resource amount C:\Users\##\AppData\Roaming\Godot\app_userdata\Game Of Life Rip Off

Each new upgrade MUST be added into the saving and loading functionality. Make sure the ID is unique, and the chosen upgrades dictionary has the correct keys. 


### Cheats and Easter Eggs
[ give 500 resource 
] give 500 money. 

---

## Story and Narrative
The overall story is about a planet exploding and therefore the surviving population is living on a spaceship. 

### Backstory
The backstory is the planet Earth, it used to have inhabitents who lived nicely on the planet, but they searched for soemthing greater. Learning about why they lived there, and how they managed to be born. 

### Plot Elements
The story is the people of this spaceship learning the meaning of life. They live and die with the hopes of finding the meaning of life, and eventually their ancestor do find it. 

### Game Story Progression
Each of the cutscenes are the way the plot develops. They need to survive more iterations than the previous runs in order to progress the story. Insentive to get higher and higher scores. The information is given by a omnipresent narrator. 

Cutscene 0: Show the people leaving for the first time, like them suiting up to take on outerspace in hopes of a secret mission. 

Cutscene 1: Maybe learn more about who managed the events of the trip. Show the captain of the ship at the construction site of the ship.

Cutscene 2: Learn about the early years of the ship. The captain growing old and dying, but still keeping a secret why he wanted to start this one. 

Cutscene 3: Show many many geneartions passing. 

Cutscene 4: Show the "outer wilds eye". The key to learning the meaning of life somewhere beyond the edge of the universe. and they are about to cross that edge. 

Cutscene 5: Learn the meaning of life, I want it to look like the beyond the quiet. Show what the meaning of life is. 


Explain how the progression of the plot is exposed to the player. Remember that there are different approaches to the narrative: how it is exposed, who is telling it, and the sequence that things happen. If you are using cut scenes to progress the story, describe the cut scenes in detail.

---

## Game World
Generally, the look of the game is a sci-fi world. There is interstellar travel, there are laser guns, regular sci-fi asestetic. Rimworld type setting. There are random events that make space more dangerous, but most of them are going to be silly. 
The player sees the universe only through the cutscenes, the ship and the random events that occur. Its a very "cartoony" sci-fi world. 

---

## Characters and Opponents


### Character List
Captain 1 
Captain Cup, - The one that goes into the edge of the universe
Captain ???? - The one that finds the meaning of the universe. 

---

## User Interface

### Visual System
- Main screen, 1/2 of the game is the cell sheet. The other 1/2 is the UI menu, 


### Control System
The entire game is played with the mouse, all through clickable buttons, and through menus to click. no typing required. 

### Audio, Music, and Sound Effects

### Game Art
The game will be intentionally simplistic, to emulate the enviroment in which the game of life was mostly used. In early computing. It will intentionally rely on the nostalgia of early 2000s computer graphics. Another art style like the dwarf fortress. 
Pixel art will be used in most places, I should use a consistent pixel resolution, currently everyhting is kinda all over the place. I want to refine this most of all. 

### Help System

### Settings
What can the user change?

---

## Content Additions
How can the administrator add new content to the game? The information on the Functional Specification and Software Design Document pages may be useful in thinking about this non-game part of the project.

---

## Feedback for the Player
How can the player tell if they are doing well? Are there mechanisms to tell them what they are doing wrong?

---

## Data Collection for the Administrator
What information is being collected for the administrator? How can they access it?

---

## Deployment
Describe everything that a person will need to run the game.

- Where is it deployed? - Desktop Windows application. 
- How can they recreate it?
- What information is needed to get it started? Do not, however, include any passwords in this document!
- What systems are required to run the game?
- If it is a game that runs on local devices, deployment includes how to rebuild it and where it needs to be stored for users to be able to download it.
- What configurations and settings are required to get the game working?

---

## Development
What does a developer need to know in order to continue development on the game? The information on the Software Design Document pages may be useful in thinking about what needs to be captured.

- What platform is it built on, including versions? Be sure to include all dependencies.
- Where are the source code and assets to be found? This should be in a publicly available repository.
- What are the key elements of the game? This will differ considerably based on the platform. Where can a developer find details on the game structure? The details need not be included in this document — a reference is fine. Wherever the documentation is, however, it needs to be sufficient for them to find their way around the code and to understand what the different elements are. Be especially careful to identify the key problems that you encountered and solved. These are likely to be subtle points that the next developers will encounter as well.
