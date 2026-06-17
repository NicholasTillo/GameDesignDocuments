# Serious Game Design Document Outline

A game design document is the blueprint from which a game is to be built. As such, every single detail necessary to build the game should be addressed. The larger the team and the longer the design and development cycle, the more critical is the need. For your purpose, the intent is to capture as much as possible of your design. I want you to think big…bigger than what you are able to develop. I also want you to be clear about what the software delivers and what the design entails. Use this document to define the ultimate game, but be clear about what you have delivered.

This document also includes elements that are normally considered part of a software design document but are included to give a more complete picture of the game.

You do not need to include all topics and you do not need to use the numbered outline structure for your document, but as a team you should review all items to be sure that you have considered all of these elements and why they are or are not relevant to your game. It should also be easy for me to identify the topic that you are covering.

---

## Title Page (page and all elements are required)

### Game Name
This is more important than you think even in a non-commercial environment. It sets the tone for the game's use and gives it an identity.

### Tag Line
A tag line is a statement or phrase that brands your game. Famous tag lines are "Just do it!", "Got milk?", "The King of Beers". Or from the video game world: Dark Souls: "Prepare to Die", Dead Space: "Only the Dead Survive", Deus Ex: "Trust no one. Question Everything", Pokémon: "Gotta catch em all!"

### Team
Names and roles. Remember that your client is part of the team.

### Date of Last Update

---

## Revision History
Only needed if you are working on multiple versions of the document or making major changes to the game. Probably not needed for most games in this class. However if I review a version that then significantly changes, include the history.

---

## Game Overview (required of all games)
This is intended as a cohesive paragraph or two that lets someone understand what you are working on. It must include:

### Purpose of the Game
The purpose of the game is to give the player a space to do something as they focus on a conversation. It is meant to be a visual, and a physical fidget toy. They are supposed to be able to launch and close this game quick, as they start a deep conversation, and then end said conversation. 


### Justification for the Use
Me, This is what I found myself, (and others, I saw it in instagram posts with >50 comments saying they do the same) jumping on chests in minecraft when the conversation got good. 



### Genre(s)

---

## Gameplay
The enitre point of this game is to give a space for players to parkour around, as they have conversations in discord. My favoutire times in minecraft are just talking about stupid stuff jumping around the base on chests. So that is the whole gameplay. Fun movement, aestetic area, and conversations. This is a single player game, the voice chat is all handled through discord and not inside the game itself. 



### Objectives
There are no objectives, at all. Its just to build a relaxing enviroment for you to mess around in. 


### Game Progression and Play Flow
The game flow will be the player will launch and immedietly be put into a randomly generated enviroment. From here they can affect it, to be how they want, with custom shaders and stuff. 

### Mission, Challenge or Puzzle Structure

---

## Mechanics (Key Section)
The player will be able to move between a building mode, and a movement mode,  

### Rules


### Physics
It is going to be simple minecraft-like physcis, where the blocks do not fall (unless otherwise specifed) the player will move as a earth-like movement with gravity, and inertia simulations. The one exception is sand, which falls when there is nothing under it, thats just a placeholder for now in case I want to add more falling blocks later. 


### Character Actions

#### Character Movement
This is going to be a main part of the game, the movement should be simple wasd, space to jump movement, it must be fluid and responsive, it must be satisfying to move. 


#### Objects
The player will have an inventory, however nothing is limited, so they are able to place as much of the blocks that they want down. 
The list of blocks will be: 
- Dirt 
- Stone Blocks
- Grass Blocks, 
- Wood Blocks. 
- Sand (this one falls when there is nothing under it)

#### Actions
The player will be able to place new blocks. And go into a "survival" mode where they dont place new blocks, but they just explore the enviroment that they created. 

### Game Options
Change and affect the enviroment by a full options menu that includes a large amount of features like, sky colour, biome, fog level and block configurations, like choosing the perlin noise area thats chosen. There will also be sliders for the different "vibes" of the world, so the player could turn up the "cozy" scale and we would swap a shader on the backend to match it. If they want, they can also choose from a selection of premade worlds, there will be 5 of them to pick from and swap between, being dungeon, clifftop, forest, cityscape, and crystal cave. 


### Replaying and Saving
Players can save their world to their disk, these worlds can then be relaunched to jump around again. The save will keep both the blocks they placed or broke, and the shaders and options they had on, so the world comes back exactly how they left it. 
### Cheats and Easter Eggs
Easter eggs will be added into some of the premade worlds, just for my personal enjoyment. 

---

## Story and Narrative
No real backstory or story at all, its just a block world to jump around in. Maybe make some easter eggs if possible. 



---

## Game World
The overall game world will be a "nostalgic" "soft" "dream like" "warm" "bright" "cozy", block based world. The player will make the game world to their desire, but it will always be those key words. The world is a finite bounded area, but it will be big enough that the player would never realisticially meet the end of it. 

---

## Characters and Opponents

### Player Avatar
Literally the most neutral character possible. to have the player be able to self insert, no matter what they look like. 

---

## User Interface

### Visual System
- When in building mode, they will have their inventory, it will be a hotbar, just like minecraft, unless there is a more efficient way to build. 
- When in parkour mode, there will be little to no hud, except for a single light source, probably a lantern, and a hand that they can see in front of them.

### Control System
WASD - Movement
Space - Jump. 
The movement will have a strafe system, like in the source engine, used in counterstrike and garry's mod. 

### Audio, Music, and Sound Effects
Music will be intentially cozy, with a single playlist of around 10 songs that will be shuffled through, playing randomly throughout the players experiance in the game. With periods of silence inbetween. 
There will be sound effects for landing, walking, and jumping off each block type, to increase immersion. 



### Game Art
See the game world for intended style 

### Help System


---

## Content Additions
How can the administrator add new content to the game? The information on the Functional Specification and Software Design Document pages may be useful in thinking about this non-game part of the project.


---

## Deployment
Describe everything that a person will need to run the game.

- Deployment will be decided after the game is developed, but for now we are just assuming a windows desktop build. 
- How can they recreate it?
- What information is needed to get it started? Do not, however, include any passwords in this document!
- What systems are required to run the game?
- If it is a game that runs on local devices, deployment includes how to rebuild it and where it needs to be stored for users to be able to download it.
- What configurations and settings are required to get the game working?

---

## Development
What does a developer need to know in order to continue development on the game? The information on the Software Design Document pages may be useful in thinking about what needs to be captured.

- This will be developed in Godot, 4.6 build. , specifically on the v4.6.stable.double.custom_build [89cea1439] build created by Zylann, found in this github repository. 
https://github.com/Zylann/godot_voxel
Refer to this github for all documentation and coding pracices. 


- All changes of the repository will be in my personal repository on NicholasTillo's github. 
- What are the key elements of the game? This will differ considerably based on the platform. Where can a developer find details on the game structure? The details need not be included in this document — a reference is fine. Wherever the documentation is, however, it needs to be sufficient for them to find their way around the code and to understand what the different elements are. Be especially careful to identify the key problems that you encountered and solved. These are likely to be subtle points that the next developers will encounter as well.
