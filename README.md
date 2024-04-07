[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Joshua Martin
### Student number: 47708336

This document discusses and reflects on the design of your platformer level for the Level Design assessment. It should be 1500 words. Make sure you delete this and all other instructional text throughout the document before checking your word count prior to submission. Hint: You can check word count by copying this text into a Word or Google doc.

Your document must include images. To insert an image into your documentation, place it in the "DocImages" folder in this repo, then place the below text where you want the image to appear:

```
![Place any alt text here](DocImages/<IMAGE NAME AND FILE EXTENSION>)
```

Example:

![This is the alt text for an image!](DocImages/exampleimage.png)

## 1. Player Experience (~700 words)
Outline and justify how your level design facilitates the core player experience goals outlined in the assignment spec. Each section should be supported by specific examples and screenshots of your game encounters that highlight design choices made to facilitate that particular experience.

### 1.1. Discovery
What does the player learn? How does your encounter and broader level design facilitate learning in a way that follows good design practice?

Initially when the player starts the game, they appear in a room with only a few things to interact with. 

![leveldesign_0](DocImages/leveldesign_0.PNG)

Upon further inspection around the room, the player learns that platforms can be jumped through both upwards and downwards, spikes hurt when they touch them, and switches activate when you walk over them causing the door in front of it to open, incentivising that the other doors can also be opened if a switch is found. The rock walls are uninteractable until the player discovers what to do with them later in the level. Only a few mechanics are initially introduced in order to not overwhelm the player. 

Going through the opened door begins the first section of the level, and the player is introduced to two new objects: the pressure plate and the pushable box. The player learns that when they step on the pressure plate, the door opens, and when they step off it, the door closes, not leaving the player any time to run through. They also learn that the box can be pushed in either direction. With gentle nudging through how the room is designed by how the box can only be pushed left to cause any drastic changes, the player with their problem solving skills can figure out to push the box onto the pressure plate to keep the door open, the player learning one of the main mechanics of how to complete the level: pushing a box on to a pressure plate.

![leveldesign_1](DocImages/leveldesign_1.PNG)

In the next room, the player learns they need to use the same mechanic, box on pressure plate, but is further introduced to a few more mechanics such as acid and how to avoid hazards with increasing simple and nuanced control. As shown above, mechanics are discovered by the player naturally, using purely the design of the level and the player's own problem solving skills, and gradually, so as to not overwhelm the player with information.

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

The intensity curve to visualise is a zig-zag moving diagonally upwards. The level is designed so that inbetween the moments of increasing tension are moments of relief. In between in each section, the player gains access to infirmaries located in the starting area.

![leveldesign_2](DocImages/leveldesign_2.PNG)

![leveldesign_3](DocImages/leveldesign_3.PNG)

Each infirmary holds 3 hearts each and acts as a way to recover after or during the first and second section. 

Not only between the sections but also within them are moments of relief, except section 3. During section 1 and 2, there are moments where players have to keep moving as well as moments where players can just stop and think about what they will do. For example, during section 2, the player will have to jump up a series of platforms while being attacked by a combination of spitters and chompers, but afterwards can rest at the next checkpoint.

![leveldesign_4](DocImages/leveldesign_4.PNG)

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

This level engages with the physical, intellectual, and perceptive skills of the player regularly. For example in section 2, there is a part where the player will encounter a lake they have to cross. They have to look around for a solution, finding a box to push into the lake (perceptive), solve how to use the solution, pushing it into the lake (intellectual), then act upon it, jumping onto the box to cross the lake (physical).

![leveldesign_5](DocImages/leveldesign_5.PNG)

The level keeps the player in the flow channel by having the sections ascend in difficulty, the first section having problem solving, the seconnd section having harder problem solving, and the final section having problem solving in timed conditions. The sections also have clear objectives and immediate rewards when completing them besides the keys. For example, after completing the first section and returning to the starting area, the player will see that they now have access to the section 1 infirmary and the section 2 area as well as making progress to unlocking the bottom entrance, having one of the doors opened.

![leveldesign_6](DocImages/leveldesign_6.PNG)

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

From the beginning of the level, the player is free to explore the starting area. After investigating it, the player will realise there are 5 entrances and only one they can open.

![leveldesign_7](DocImages/leveldesign_7.PNG)

The player is invited to explore regularly throughout the level in order for them to figure out how to get to the sections goal. For example, when the player reaches the first section and unlock the ability to break the rock walls, in the vicinity is 2 rock walls on the players screen. The player then is incentivised to break those walls to explore more of the level in order to reach the encounters goal. Alternatively if the player has thoroughly explored the starting area, they can recall more rock walls to be broken at that location, thus is given the liberty to go back and break those first. 

![leveldesign_8](DocImages/leveldesign_8.PNG)

In important areas, the yellow brick tile is commonly used and is a pattern throughout the level, highlighting the main starting area incentivising the player to keep coming back to it, and highlighting the infirmaries and keys inviting the player to figure out how to get inside given its emphasized nature.

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1. Acid

### 2.2. Checkpoints

### 2.3. Chompers

### 2.4. Health Pickups

### 2.5. Keys

### 2.6. Moving Platforms

### 2.7. Passthrough Platforms

### 2.8. Spikes

### 2.9. Spitters

### 2.10. Weapon Pickup (Gun)

### 2.11. Weapon Pickup (Staff)

## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram
![molecule_diagram](DocImages/molecule_diagram.PNG)

### 3.2. Level Map – Section 1
![key](DocImages/section_key.PNG)
![section_1](DocImages/section_1.PNG)

### 3.3.	Level Map – Section 2
![key](DocImages/section_key.PNG)
![section_2](DocImages/section_2.PNG)

### 3.4.	Level Map – Section 3
![key](DocImages/section_key.PNG)
![section_3](DocImages/section_3.PNG)

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: ChatGPT
**Nature of Use** Finding relevant design theory.

**Evidence Attached?** Screenshot of ChatGPT conversation included in the folder "GenAI" in this repo.

**Additional Notes:** I used ChatGPT to try and find some more relevant design theory that I could apply to my game. After googling them, however, I found most of them were inaccurate, and some didn't exist. One theory mentioned, however, was useful, and I've incorporated it into my work.

### Tool Used: Example
**Nature of Use** Example Text

**Evidence Attached?** Example Text

**Additional Notes:** Example Text


