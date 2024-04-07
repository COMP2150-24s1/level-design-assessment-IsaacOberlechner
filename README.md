[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Isaac Oberlechner
### Student number: 46615962

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

This level facilitates discovery through the scaffolding of various mechanics. Discovery is delivered in Section One where the player learns the core mechanics via structured encounters. The first encounter in Section 1 pits the player against a spike and a Chomper with no weapons. This teaches the player that Chompers and spikes damage the player and movement and jumping must be utilised to avoid contact. 

![This is the alt text for an image!](DocImages/Discovery%20-%20Spikes%20and%20Chompers.png)

The following encounter provides players with the Staff - a tool to break through environmental obstacles (e.g. a breakable wall) and defend themselves against close-range threats. 

![This is the alt text for an image!](DocImages/Discovery%20-%20Passthrough%20Platforms,%20Staff,%20Checkpoint,%20Health.png)

Later encounters in this Section provide players with the Gun and pit them against acid, a Spitter, and a moving platform. The player learns to utilise the Gun as a long-range tool to activate switches (e.g. to move the platform) and defend themselves from a distance. Progression through Section 1 rewards the players with the first key, signified by UI feedback. This scaffolds an understanding of the level objective, that is, to collect three keys. 

![This is the alt text for an image!](DocImages/Discovery%20-%20Gun,%20Spitter,%20Acid,%20Moving%20Platofrm.png)

Progression through Section 1 rewards the players with the first key which in combination with the UI feedback scaffolds an understanding of the level objective - to collect keys and progress. 

![This is the alt text for an image!](DocImages/Drama%20-%20Key.png)

### 1.2. Drama
What is the intensity curve? How does your design facilitate increasing yet modulating intensity, with moments of tension and relief? 

The level has an intensity curve characterised by a steady flow of tense and relieving encounters. The encounters are facilitated mainly by rewards and penalties, with some moments of uncertainty.  

For example, Section Three presents the player with a drop they must go down to progress. 

![This is the alt text for an image!](DocImages/Drama%20-%20Hole.png)

The player has previously learned that drops can be rewarding (e.g. dropping to the portal after collecting the first Key) or dangerous (e.g. dropping into the trench with the Chomper). Tension arises due to uncertainty of whether the current drop will lead to reward or danger.  

![This is the alt text for an image!](DocImages/Drama%20-%20Key.png)
![This is the alt text for an image!](DocImages/Drama%20-%20trench.png)

Dropping down the hole reveals an acid pit and a Spitter the player must fight against or risk taking damage and losing progression, further facilitating tension. 

![This is the alt text for an image!](DocImages/Drama%20-%20Cavern.png)

Completing this encounter rewards the player with access to health and an alternative shortcut down to the cavern. These rewards offer the player relief by contributing to their progression - they are strengthened for later encounters with health and have access to a shortcut, situated at their previous checkpoint, that bypasses a portion of the cavern. 

![This is the alt text for an image!](DocImages/Drama%20-%20Rewards.png)
![This is the alt text for an image!](DocImages/Drama%20-%20Checkpoint.png)

### 1.3. Challenge
What are the main challenges? How have you designed and balanced these challenges to control the difficulty curve and keep the player in the flow channel?

The level consists of physical challenges that exercise core intrinsic skills. The difficulty curve represents incrementing difficulty from easy (Section One) to intermediate (Sections Two and Three). Section One sets the foundation with easy challenges engaging core skills. Sections Two and Three build upon the foundation through the addition of coordination. The difficulty is gradually implemented so the player can maintain flow by feeling challenged yet capable throughout the level. 

Section One engages the core skills of movement and jumping with horizontal traversal (e.g. jumping over spike and Chomper), vertical traversal (e.g. climbing the hill), and a combination of both (e.g. moving platform). Weapon skills are engaged through the light use of the staff and gun. 

![This is the alt text for an image!](DocImages/Discovery%20-%20Spikes%20and%20Chompers.png)
![This is the alt text for an image!](DocImages/Discovery%20-%20Passthrough%20Platforms,%20Staff,%20Checkpoint,%20Health.png)
![This is the alt text for an image!](DocImages/Challenge%20-%20Moving%20Platform.png)

Section Two builds upon the challenge by adding the element of coordination. For example, the player coordinates their jumping to reach a health pickup. The player also needs to coordinate shots to defeat Spitters.

![This is the alt text for an image!](DocImages/Challenge%20-%20Health.png) 
![This is the alt text for an image!](DocImages/Challenge%20-%20Spitters.png)

Section 3 increments the challenge by adding instant death via acid pits, requiring the player to execute a greater skill level to avoid losing progression. 

![This is the alt text for an image!](DocImages/Drama%20-%20Cavern.png)

### 1.4. Exploration
How does your level design facilitate autonomy and invite the player to explore? How do your aesthetic and layout choices create distinct and memorable spaces and/or places?

This level encourages exploration through the integration of non-linear paths. This grants players autonomy by allowing them to find the “correct” path by exploring the space or rewarding them with combat and heath. 

For example, the player starts the level at the portal and is aesthetically presented with an open space presenting three paths - left, right or down. The openness of the space invites the player to explore and consequently learn that they must first take the left path to progress the level. Though structurally linear, this encounter refrains from telling that player where to go explicitly. Instead, the open space provides a sense of autonomy via discovering the correct path through exploration.

![This is the alt text for an image!](DocImages/Exploration%20-%20Spawn.png)
![This is the alt text for an image!](DocImages/Exploration%20-%20Section%201.png)
![This is the alt text for an image!](DocImages/Exploration%20-%20Section%202.png)
![This is the alt text for an image!](DocImages/Exploration%20-%20Section%203.png)

In Section Three, the player can choose to explore the cavern further underground. Moving through this section rewards them with light combat and health. If the player descends, they must go right to attack a Chomper and collect health. This creates a distinct space in contrast to the path and layout of the rest of Section Three where the players progress the section by moving left.

![This is the alt text for an image!](DocImages/Exploration%20-%20Descent.png)
![This is the alt text for an image!](DocImages/Exploration%20-%20Going%20Left.png)

## 2. Core Gameplay (~400 words)
A section on Core Gameplay, where storyboards are used to outline how you introduce the player to each of the required gameplay elements in the first section of the game. Storyboards should follow the format provided in lectures.

Storyboards can be combined when multiple mechanics are introduced within a single encounter. Each section should include a sentence or two to briefly justify why you chose to introduce the mechanic/s to the player in that sequence.

You should restructure the headings below to match the order they appear in your level.

### 2.1.  Spikes and Chompers

![This is the alt text for an image!](DocImages/Storyboard%20-%20Spikes%20and%20Chompers.png)

### 2.2. Passthrough Platforms and Weapon Pickup (Staff)

### 2.3. Checkpoints and Health Pickups

### 2.4. Weapon Pickup (Gun)

### 2.5. Acid, Moving Platforms, and Spitters

### 2.6. Keys


## 3. Spatiotemporal Design
A section on Spatiotemporal Design, which includes your molecule diagram and annotated level maps (one for each main section of your level). These diagrams may be made digitally or by hand, but must not be created from screenshots of your game. The annotated level maps should show the structure you intend to build, included game elements, and the path the player is expected to take through the level. Examples of these diagrams are included in the level design lectures.

No additional words are necessary for this section (any words should only be within your images/diagrams).
 
### 3.1. Molecule Diagram

![This is the alt text for an image!](DocImages/Molecule%20Diagram.png)

### 3.2. Level Maps

Level Map Key: ![This is the alt text for an image!](DocImages/Level%20Map%20-%20Key.png)

### 3.2.1. Level Map - Section 1

![This is the alt text for an image!](DocImages/Level%20Map%20-%20Section%201.png)

### 3.2.2. Level Map – Section 2

![This is the alt text for an image!](DocImages/Level%20Map%20-%20Section%202.png)

### 3.2.3 Level Map – Section 3

![This is the alt text for an image!](DocImages/Level%20Map%20-%20Section%203.png)

## 4. Iterative Design (~400 words)
Reflect on how iterative design helped to improve your level. Additional prototypes and design artefacts should be included to demonstrate that you followed an iterative design process (e.g. pictures of paper prototypes, early grey-boxed maps, additional storyboards of later gameplay sequences, etc.). You can also use this section to justify design changes made in Unity after you drew your level design maps shown in section 3. 


![This is the alt text for an image!](DocImages/Prototype%20-%20Section%201.png)

You should conclude by highlighting a specific example of an encounter, or another aspect of your level design, that could be improved through further iterative design.

## Generative AI Use Acknowledgement

Use the below table to indicate any Generative AI or writing assistance tools used in creating your document. Please be honest and thorough in your reporting, as this will allow us to give you the marks you have earnt. Place any drafts or other evidence inside this repository. This form and related evidence do not count to your word count.
An example has been included. Please replace this with any actual tools, and add more as necessary.


### Tool Used: Grammarly
**Nature of Use** Grammar, spelling, and punctuation checking. 

**Evidence Attached?** Evidence of the use of Grammarly can be found under the folder "GenAI" in this repo. 

**Additional Notes:** Grammarly was used strictly as a tool in Pages to check grammar, spelling, and punctuation of written material in this design document. 


