# CrystalCollector

Crystal Collector is a third-person maze exploration game built in Unreal Engine 5.  
The player must navigate a custom maze, collect all crystals, and beat the countdown timer before time runs out.

This project focuses on gameplay systems, UI programming, player feedback, and creating a complete game loop from main menu to win/loss states.

---

## Gameplay

- Explore a custom-built maze level
- Search for collectible blue crystals
- Collect all crystals before the timer reaches zero
- Win by collecting every crystal
- Lose if the countdown timer expires

---

## Features

### Main Menu System
- Custom main menu screen
- Play button functionality
- Quit button functionality
- Mouse/UI input handling
- Transition from menu controls to player controls
- Button click sound effects

---

### Player HUD System
- Created with Unreal Motion Graphics (UMG)
- Crystal collection counter
- Countdown timer display
- Timer formatted into minutes and seconds
- HUD updates dynamically during gameplay

---

### Crystal Collection System
- Crystal pickup Blueprint
- Collision-based collection
- Tracks collected crystals
- Updates HUD automatically
- Removes crystals after pickup
- Pickup sound effect

---

### Timer System
- Five-minute countdown timer
- Updates every second
- Stops correctly during win condition
- Triggers lose condition when time reaches zero

---

### Win & Lose System
- Win screen widget
- Lose/game over widget
- Restart button functionality
- Returns player control after restart
- Mouse cursor handling for UI screens
- Win sound effect
- Lose sound effect

---

### How To Play Popup
- Instruction screen when starting level
- Delayed popup after loading
- Pauses gameplay while reading
- Start button resumes gameplay
- Popup sound effect
- Button sound feedback

---

### Audio System
- Main menu sounds
- Button click effects
- Crystal pickup audio
- Win event audio
- Lose event audio
- Background music

---

### Visual Polish
- Custom maze environment
- Sunset lighting setup
- Collectible crystal placement
- UI polish and feedback

---

## Built With

- Unreal Engine 5.7
- Blueprints
- Unreal Motion Graphics (UMG)
- Blueprint Gameplay Systems

---

## Development Focus

This project was created to practice:

- UI programming
- Gameplay programming logic
- Blueprint communication
- Event-driven systems
- Player feedback
- Creating a complete playable experience

---

## Developer

Created by Kye Langer-Freeman  
Game Developer