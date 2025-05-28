# Forest Punk

Table of contents
#### 1. Game Concept
> ##### 1.2 Game-idea
> ##### 1.3 Genre
> ##### 1.4 Style & References
> ##### 1.5 Concept Art
#### 2. Project Management
> ##### 2.2 Monetization
> ##### 2.3 Scheduling
> ##### 2.4 Risks
#### 3. Game Script
> ##### 3.2 Story
> ##### 3.3 Characters
> ##### 3.4 Game World/Levels
> ##### 3.5 Collectables
#### 4. Gamedesign (Gameplay)
> ##### 4.2 Progression
> ##### 4.3 Core-loops
> ##### 4.4 Movement and Actions
> ##### 4.5 Game View
> ##### 4.6 Levels
> ##### 4.7 Collectable Items
#### 5. Visuality & Usability
> ##### 5.2 Characters
> ##### 5.3 Environments
> ##### 5.4 Necessary Core - Assets
> ##### 5.5 User Interface
#### 6. Technical
> ##### 6.2 Game Architecture
> ##### 6.3 SFX
> ##### 6.4 Accessibility
> ##### 6.5 User Interface

## 1. Game Concept

#### Game-idea:

> ##### The player is a rat who is hunting for the emperor, both are transferred from their own comic styled world to a completely different world.
> ##### The rat has to fight different enemies in their hunt

#### Genre:

> ##### Action Platformer

#### Art Style: Painterly, cartoonish, steampunk, futuristic, detailed.

> ##### Steampunk - 2D

#### Style references:

> ##### Nine Sols, Hollow Knight, Rain World, Ori and the Blind Forest, Arcane, Subnautica, Old comic books

#### Concept Art:

> ##### www.figma.com/design/H7EBimbynf7OWy2pCMuQ0Q/Ryhmä-5-FORESTPUNK
> ##### Link to Figma containing concept art for the game. 

## 2. Project Management
> ##### Projektinhallinnassa käytetään Trelloa, GitHubia & Discordia. Kommunikaatiovälineenä toimii ryhmän oma Discord kanava.

### 2.2 Monetization

> ##### Marketing plan:
> ##### Target audience: 15-35 years old, fans of retro and indie games, platformers like super mario.
> ##### Platforms: Windows-build, itch.io
> ##### USPs: Unique art style mixing different styles, cartoonish steampunk/futuristic and painterly. Custom made music and SFX, diverse player mechanics and animations.
> ##### Potentional DLC, Forest Punk 2.
> ##### Sending free version of the game to streamers who play and test indie games.
> ##### Teaser trailer of the game that can be uploaded to YouTube and other social media platforms.
> ##### Launch in Twitter, Instagram, Tiktok, Discord, Reddit containing material of progress made during game development, comments and experiences of team members shared before, during and after the project.

### 2.3 Scheduling
> ##### Deadline for all of the code 15.04
> ##### Project leader assembled all of the individual parts of team members in the build 28.04
> ##### Deadline for the initial purku 29.04
> ##### Added functionality to checkpoints in levels and fixed Health UI scaling. 28.05.2025
> ##### Edited GDD to better represent the project, added technical information, (Which editor and tools were used), Link to Figma. 28.05.2025

### 2.4 Risks
> ##### - Only a few deadlines for everything instead of multiple deadlines for progression.
> ##### - Not enough experience in game development.
> ##### - Difficulties with GitHub, Materials went missing and had to be redone and uploaded separately

## Sprint

> ##### Deadline for all of the code, animation, sound and graphics. 15.04
> ##### Assembling of the game 28.04
> ##### Game Project Disassembly (purku) 29.04

## 3. Game Script

#### Story
> ##### The desert rat is hunting for the emperor, both transferred from their own world to a completely different one.
> ##### The rat has to fight different enemies in their hunt.

#### Characters
> ##### - Player (rat)
> ##### - Boss (emperor)

#### World/Levels
> ##### - Fictional Worlds with (old comics, steampunk) and (fantasy, forest, painterly) styles mixed together as the game progresses.
> ##### - Number of Levels: 3

#### Collectable items
> ##### - Hearts

## 4.2 Progression

#### The goal
> ##### - Defeat enemies, collect hearts to restore health, reach win checkpoint to trigger winscreen.

#### Obstacles
> ##### - Three different types of enemies
> ##### - Jumping crab, flying medusa that follows the player, turtle that moves horizontally.
> ##### - Traps and obstacles that do damage


#### What does the player do in the game?
> ##### - Fight enemies, collect health items, reach checkpoints.

## 4.3 Core-loops

#### Core-loop 1.
> - Fight enemies, collect health items, die - repeat
> - Fight enemies, collect health items, reach checkpoints, die - repeat
> - Fight enemies, collect health items, reach win checkpoint, trigger win screen, quit or main menu - repeat

## 4.4 Player movement & Actions

#### Player movement
> ##### - WASD 
> ##### - Basic movement
> ##### - Jump & Doublejump
> ##### - Wallclinging
> ##### - Dash

#### What actions does the player have?
> ##### - Melee attack
> ##### - Shooting
> ##### - Collecting health items
> ##### - Movement, (Jumping, Dashing, Doublejump & Wallcling)

## 4.6 Levels
> ##### - Comic styled world inspired by old comics with steampunk elements.
> ##### - Fantasy forest with a paintetrly art style.
> ##### - These two styles get mixed troughout the game.
 
## 4.7 Collectable items
> ##### - Hearts

## 5.2 Characters
> ##### - Player-character (Desert rat)
> ##### - Minions of the emperor
> ##### - The Emperor


## 5.3 Environments
> ##### - Forest Level
> ##### - Steampunk Level
> ##### - Boss Level


## 5.4 Necessary Core - Assets
> ##### - Player
> ##### - Enemies
> ##### - Hearts
> ##### - Backgrounds

## 6. Technical   
> ##### - Game Engine: Unity 6000.0.43f1
> ##### - File management: Discord, Unity, local files on PC, GitHub repositories for game build and GDD.

## 6.2 Arkkitehtuuri 

#### CameraController 
> ##### - Camera follows the player

#### Player HealthSystem
> ##### - Keeps track of player health
> ##### - Adds and reduces health 

#### PlayerCombat

 #### Player Melee
> ##### - Left Mouse Button

#### Player Shooting
> ##### - Right Mouse Button

#### PlayerController 
> ##### - Player movement
> ##### - Jump, Wallcling, Dash, DoubleJump.

#### EnemyController
> ##### - Enemy movement
> ##### - Jumping crab, horizontally moving turtle, flying medusa.
> ##### - Damage to player

## 6.3 SFX 

#### Music
> ##### - Background music

#### Sound effects
> ##### - Collecting
> ##### - Walking
> ##### - Jumping
> ##### - Mouse click in menus
> ##### - Player attacks
> ##### - Enemy attacks

## 6.4 User Interface

> ##### - Steampunk styled menus
> ##### - StartMenu
> ##### - PauseMenu
> ##### - SettingsMenu
> ##### - Credit page
> ##### - Levels
> ##### - DeathScreen
> ##### - WinScreen
> ##### - DevMenu for displaying BossLevel
