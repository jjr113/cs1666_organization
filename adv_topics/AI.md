# AI Advanced Topic Presentations

Before your presentation, use this file to get your talk outline approved. Be
sure to provide an estimated time to spend on teach topic (totalling 45 minutes)
and be sure not to repeat any topics covered in previous presentations.

## Presentation I

Vansh Desai 
Mary Grady
Jon Riklan

Outline


Summary from README: 

“Enemy AI will mainly focus on the implementation of the boss fight. Using utility AI, we will assign a point system that will calculate the systematically most efficient move that the enemy should make at any given instance when in combat with the player. Based on this point system, the enemy will decide its actions that will prove most dire for the player. This should make the boss fight extremely difficult for the player to beat without thinking like the enemy. In addition, we will track the player's combat decisions throughout the game. We can measure the average time the player takes between attacks, as well as its movement, to allow the enemy to know the most efficient time to attack and block the player. For smaller enemies, we will have a basic AI that follows the player around from point A to point B while making its basic default assigned attacks. Finally, the number of smaller enemies will be dependent on the number of active players. We will have N+1 smaller enemies in any given dungeon, where N is the number of active players. Four behaviors for boss include attack, block, avoid, and change target.”

Introduction: 

-	Intro to advanced topic (generalized to be specified later)
-	Explanation of final boss fight i.e. a short description of player vs enemy from the start of the game to the final boss fight
-	Basically and overview of what we are trying/will be accomplishing before we break it down into specifics 
-	Introduction to Utility AI : focus not so much on the use of AI (as in this is an upper level course so we don’t need to go into that much detail)  
-	Why is this AI useful for this situation 
-	Specifics relating to utility vs opposing ones 
-	Utility AI is a decision making system that allows the system to gather data on the current situation and allow the NPC to make a coordinated action in that exact moment 
-	The action with the highest score will win
-	Consideration: scores probability of something in this case players choice vs boss then decision 
-	Condition: allows a true of false 
-	Score mapping: job to map one or more scores into other single score 
-	How will utility AI work in this game? 
-	Mention specifics relating to player decisions and how this is the main deciding factor for the main boss 
-	Mention point system, go into depth later.


Sub-topic 1: Tracking player movement – point system (utility AI) (14 minutes)

-	In depth explanation of point system and how we are going to assign certain player movement to boss level integration of said movement. (i.e. how will these points dictate how the boss moves) 
-	How will points be assigned to players based on movement
-	How each movement is scored
-	How boss will use this score to know which movement is which and decipher how to counter it 
-	Movement capabilities of boss integrated into AI 



Sub-topic 2: Choices – point system (utility AI) (14 minutes)

-	In depth explanation of point system and how we are going to assign certain player decisions to boss level integration of said decisions.
-	How will points be assigned to specific actions 
-	Players have these possible actions: attack, dash
-	The point system needs to specify 1-10 point system
-	Which assignment goes to which task/ decision 
-	Movement, decision of player? 
-	Boss decision and movement 
-	However we are choosing to formulate or change these scores/points into actions for reasonable choice by the boss
-	Level of priority 
-	Point system is predetermined, but we calculate expected utility of an action and then compare it to our point system that we decided for actions
-	Changes during boss fight or no 
-	Difficulty modifier than can be applied depending on the level of enemy (i.e. small boss, medium boss, main boss)
-	This can be used to multiply by the utility that is calculated from our general scale


Sub-topic 3: Possible player actions vs possible boss actions (utility AI)  (14 minutes)

-	Boss is given the ability for four separate behaviors: attack, block, avoid, and change target.
-	How will the point system affect these choices?
-	As explained about the point system is designed to track the player’s decisions and movement and assigns a score to said player–these are specific to each player 
-	Based on calculated probabilities of possible responses to the players actions using the expected utility formula, in combination with the utility of different boss actions, the proper action will be taken at the time of player response
-	In terms of score – what will said score impose in terms of boss fight
-	If score is this do this etc….


Sub-topic 4: Smaller bosses (simplified AI) (14 minutes)

-	Intro to how the smaller enemies are worked into the game/ ie their role and why we used a basic AI for them vs the main boss 
-	Algorithm of tracking player position 
-	How it is implemented and possible collisions avoided 
-	How the smaller enemies play into the “block” and “avoid” points since smaller enemies only attack 


## Presentation II

- Topic 1 (XX minutes)
  - ...
- Topic 2 (XX minutes)
  - ...
- Topic 3 (XX minutes)
  - ...
...


## Presentation III

- Topic 1 (XX minutes)
  - ...
- Topic 2 (XX minutes)
  - ...
- Topic 3 (XX minutes)
  - ...
...
