# Serious Game Design Document Outline

A game design document is the blueprint from which a game is to be built. As such, every single detail necessary to build the game should be addressed. The larger the team and the longer the design and development cycle, the more critical is the need. For your purpose, the intent is to capture as much as possible of your design. I want you to think big…bigger than what you are able to develop. I also want you to be clear about what the software delivers and what the design entails. Use this document to define the ultimate game, but be clear about what you have delivered.

This document also includes elements that are normally considered part of a software design document but are included to give a more complete picture of the game.

You do not need to include all topics and you do not need to use the numbered outline structure for your document, but as a team you should review all items to be sure that you have considered all of these elements and why they are or are not relevant to your game. It should also be easy for me to identify the topic that you are covering.

---

## Title Page (page and all elements are required)

### Game Name
The Fireball Game

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
The whole game is meant to be a simple fighting game with only 2 moves, (apart from movement) similar to what divekick, and footsies attempts to recreate. But instead of teaching footsies, it will teach the fireball game. 

### Purpose of the Game
The entire point of this game is to be a solid introduction to the more interesting mechanics of fighting games, that can only be built by intuition. Things like advantage vs disadvantage states, frame data, blocking vs parrying, etc. 

### Justification for the Use
Is there research that shows that this is apt to be successful? Are there other games or applications that take a similar approach? If this is an experiment to see if it will work, why does the researcher believe that it might?

### Target Audience
There's a significant difference in a game teaching biology to a kindergartener or to a college student.

### Genre(s)

---

## Gameplay


### Objectives
The whole objective is to win 3 rounds against your opponent, to win the match. In order to win a round, you must lower your opponnets healthbar to zero, in order to do that, you must hit them with fireballs. 

### Game Progression and Play Flow
The characters will start at mid screen, in neutral, then they will attempt to throw fireballs, parry, or jump in order to damage and trick the opponent. 


### Mission, Challenge or Puzzle Structure

---

## Mechanics (Key Section)


### Rules
It will be best of 3 matches, with the players starting at middle screen. 

### Model of the Game Universe
2D, single platform arena, with walls on either side of the arena to prevent the players from going to far. 

### Physics
Simple Street fighter 6 type physics, where the jumps are weightu floaty, and the movement on the ground is tight. The fireballs will just move striaght with no physics applied. 

### Economy
The only economy is the health, the one and only resoruce in the game. Players will attempt to keep their health, and drain the opponents. 

### Character Actions

#### Character Movement
The players will move with WASD, and Q for parry, and E for fireball for player 1  (Left Player). and PL";" "'" keys for movement, o for fireball, and [ for parry for player 2 (Right Player) 


#### Combat
Combat can ONLY be done through fireball, or reflecting a fireball with the parry. 


### Game Options
Potential character select screen. Could also allow for the "standard" game settings, like volume, screen resolution, quality ETC. 


---

## Story and Narrative
If you have a puzzle game, there is probably no backstory or story. As soon as you add an avatar of any sort, you have a story. It may be as simple as who the character is.

### Backstory
If there is no plot or narrative in the story but you need to understand the background, that is a backstory. The backstory can also be setting the stage for the story that is going to unfold.

### Plot Elements
There are multiple patterns of a plot: the 3-act play, the hero's journey, episodic, … Use one of the models to describe the story of the game.

### Game Story Progression
Explain how the progression of the plot is exposed to the player. Remember that there are different approaches to the narrative: how it is exposed, who is telling it, and the sequence that things happen. If you are using cut scenes to progress the story, describe the cut scenes in detail.

---

## Game World
The gameworld will be 

---

## Characters and Opponents

### Player Avatar
Each player will have their own character with a distinct visual look. 

### Character List
List Of Characters: 
TO DO


---

## Levels


### Level Maps
The levels will be purely visual for now, just having different backgrounds and msuic. 

### Training Level
there will be a tutorial on which buttons mean what, and taking the player through a parry and fireball trainign session. 



---

## User Interface

### Visual System
The visual hud will contain 3 major things, the top of the screen will be dominated by the healthbars, that drain inwards, with a timer in the center, counting down from 99. Then on each players side, they can have a super gague. T

### Control System
How does the game player control the game? What are the specific commands?

### Audio, Music, and Sound Effects

### Game Art
The intended style is incredibly simple, maybe having pixel like graphics, to allow it to get created easily. and to evoke simplicity from the player. 

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

- Where is it deployed?
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
