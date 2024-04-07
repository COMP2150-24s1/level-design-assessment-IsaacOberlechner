[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/YyUO0xtt)
# COMP2150  - Level Design Document
### Name: Isaac Oberlechner
### Student number: 46615962

## 1. Player Experience (~700 words)


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


### 2.1.  Spikes and Chompers

![This is the alt text for an image!](DocImages/Storyboard%20-%20Spikes%20and%20Chompers.png)

This encounter scaffolds learning to core uses of jumping and movement - to traverse the level and to evade enemies. By placing this encounter first they are defenceless and must learn how to take damage, avoid damage, and how traversal is required to progress the level. 

### 2.2. Passthrough Platforms and Weapon Pickup (Staff)

![This is the alt text for an image!](DocImages/Storyboard%20-%20Staff%20and%20Chomper.png)

The second encounter offers players a new traversal method (e.g. passing between platforms) and the ability to defend themselves at close range - both of which are required skills later in the level.  Once the staff is acquired, the player learns two key functionalities of it - to break environmental obstacles (i.e. break the wall) and defend themselves (i.e. kill Chomper). 

### 2.3. Checkpoints and Health Pickups

![This is the alt text for an image!](DocImages/Storyboard%20-%20Checkpoint%20and%20Health.png)

As the player has already had some light experience in combat, they are introduced to ways they can strengthen their likelihood of survival. Checkpoints offer a way to save their progress and prevent repeating previous encounters while health pickups strengthen their chances of progressing through upcoming encounters. 

### 2.4. Weapon Pickup (Gun)

![This is the alt text for an image!](DocImages/Storyboard%20-%20Gun.png)

Now familiar with the movement and the staff, the player must now use the staff to access their next essential tool. By utilizing a previously learned skill (i.e. breaking environmental obstacles with the staff) the player is rewarded with the gun, motivating them to progress forward to find its function. 

### 2.5. Acid, Moving Platforms, and Spitters

![This is the alt text for an image!](DocImages/Storyboard%20-%20Acid,%20Platform,%20Spitter.png)

The player must learn how to utilize the gun and execute an intermediate level of movement and jumping. The player learns the gun activates switches (i.e. for the moving platform) and defends them long-range (e.g. shooting the Spitter). Moreover, contact with the acid pit immediately kills the player, placing them back at the last checkpoint. Thus, the player must utilise coordinated jumping and moving to jump onto the moving platform and successfully progress.

### 2.6. Keys

The player has learned all the core mechanics and now has access to the first key. The key is situated at the end to reward the player for learning the basic mechanics and to scaffold the understanding that collecting a key signals the end of the level. The player can now jump down to the level's starting point (i.e. the Portal) and progress with Sections Two and Three.  

![This is the alt text for an image!](DocImages/Storyboard%20-%20Keys.png)

## 3. Spatiotemporal Design
 
### 3.1. Molecule Diagram

![This is the alt text for an image!](DocImages/Molecule%20Diagram.png)

### 3.2. Level Maps - Key

Level Map Key: ![This is the alt text for an image!](DocImages/Level%20Map%20-%20Key.png)

### 3.2.1. Level Map - Section 1

![This is the alt text for an image!](DocImages/Level%20Map%20-%20Section%201.png)

### 3.2.2. Level Map – Section 2

![This is the alt text for an image!](DocImages/Level%20Map%20-%20Section%202.png)

### 3.2.3 Level Map – Section 3

![This is the alt text for an image!](DocImages/Level%20Map%20-%20Section%203.png)

## 4. Iterative Design (~400 words)

![This is the alt text for an image!](DocImages/Prototype%20-%20Section%201.png)
![This is the alt text for an image!](DocImages/Prototype%20-%20Staff,%20Chomper,%20and%20Checkpoint%20(Section%201).png)
![This is the alt text for an image!](DocImages/Prototype%20-%20Gun%20and%20Spitter.png)

Section One prototypes demonstrated that players may skip the Chomper in the original staff encounter. Playtesting confirmed this which meant players may not use the staff. As such, a breakable wall was added and the Chomper was moved to enhance the learning of the uses of the staff. Prototypes further showed that players may use the staff to kill the Spitter, instead of the gun. Playtesting confirmed this and showed that the Spitter was too challenging and frustrating to face. The Spitter was moved to the acid pit and players now had to use the gun to kill the Spitter and activate the platform, scaffolding its main uses. 

![This is the alt text for an image!](DocImages/Prototype%20-%20Section%202.png)
![This is the alt text for an image!](DocImages/Prototype%20-%20Trench.png)

Section Two prototypes demonstrated little challenge compared to Section One. Moreover, the original trench encounter appeared too close quarters for traversal. Playtesting in Unity confirmed the latter. As such, a Chomper was removed and more space was made making it a less overwhelming but still moderately challenging encounter. To enhance the challenge in the rest of the section, the original passthrough platform (leading to health) was removed and players now had to coordinate their jumps to reach the health. Players also tried to explore the top of the trench at times and as such an elevator and Spitter were added in this location to reward players for exploring here. 

![This is the alt text for an image!](DocImages/Prototype%20-%20Section%203.png)

Section Three prototypes revealed the section was too claustrophobic. Playtesting confirmed this as players would bounce off the roof into the acid. The second spitter was also difficult to hit and spikes made it difficult to traverse. As such, the space became wide, spikes were reduced and the second Chomper was moved to a spot that was easier to hit. Moreover, players now had access to a health pickup and a shortcut. After these iterations, Section Three became moderately challenging, rather than highly challenging. The addition of the health and shortcut encounter rebalanced the dramatic curve making the difficulty increase at a rate consistent with the rest of the level. 

Section Two contains few encounters that focus on challenging the player beyond the trench. Section Two could incorporate more encounters that challenge the player. Moreover, encounters could focus on staff and gun mechanics as these mechanics were mainly used for environmental purposes (e.g. activating switch, breaking walls) and had limited defensive use. Iterations focusing on these aspects could improve the variety of encounters throughout the level. 

## Generative AI Use Acknowledgement


### Tool Used: Grammarly

**Nature of Use** Grammar, spelling, and punctuation checking. 

**Evidence Attached?** Evidence of the use of Grammarly can be found under the folder "GenAI" in this repo. 

**Additional Notes:** Grammarly was used strictly as a tool in Pages to check grammar, spelling, and punctuation of written material in this design document. 


