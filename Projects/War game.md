# War Game ⚔️🎮

## Project Overview

In this project, students will create a **shooter war game** where the player controls a character or vehicle that must battle against waves of enemies. The goal of the game is to shoot down enemy sprites while avoiding being hit by them. This project will introduce concepts like **sprite interaction**, **randomization**, **collision detection**, and **game flow management**.

This is a slightly more complex project that will provide students with a deeper understanding of **game mechanics**, especially when it comes to using **if-else** statements for decision-making and **pick random** blocks to generate unpredictable events.

## Key Concepts to Focus On

- **If-Else Statements**: Teach students how to use **if-else** blocks for decision-making, such as determining if a bullet hits an enemy, or if the player's health reaches zero.
- **Pick Random**: Guide students to use the **pick random** block for generating random behaviors like enemy movements, spawning rates, or attack patterns.
- **Collision Detection**: Explain how to check if a bullet hits an enemy and what actions should occur, such as the enemy disappearing and the player gaining points.
- **Health System**: Help students implement a health system for the player character, where the player loses health when hit by an enemy and can gain health back through power-ups.
- **Score System**: Implement a score system that tracks the number of enemies the player has destroyed.

## Detailed Plan

### 1. Introduction (15-20 minutes)
- Introduce the idea of a **war game** where the player controls a character or vehicle to battle against enemies.
- Discuss the concept of **if-else** statements for handling various game events, like checking if the player has collided with an enemy.
- Explain how **pick random** can be used for random enemy movements, enemy spawns, and generating unpredictable events in the game.

### 2. Step-by-Step Instructions

#### Step 1: Set up the Player and Enemy Sprites
- **Player Sprite**: Create a sprite for the player (e.g., a tank, spaceship, or soldier) that the player will control.
- **Enemy Sprite**: Create multiple enemy sprites that will move across the screen and try to collide with the player.

#### Step 2: Control the Player Sprite
- Use the `when key pressed` blocks to allow the player to move the character or vehicle up, down, left, or right.
- Use `when space key pressed` to shoot bullets or other projectiles.

#### Step 3: Create the Bullet Sprite
- Design a simple bullet sprite and make it move upwards (or forward, depending on the player's character) when the player presses the spacebar.
- Use **if-else** blocks to detect when the bullet hits an enemy sprite.
  - If the bullet hits the enemy, the enemy should disappear and the score should increase.

#### Step 4: Use the Pick Random Block for Enemy Behavior
- Use the `pick random` block to make the enemies move in random directions, spawn at random intervals, or randomly choose attack patterns (such as shooting back at the player).
- The `pick random` block can also be used to randomly select the speed of enemy movements or to vary the number of enemies that appear on the screen.

#### Step 5: Implement the Score and Health System
- **Score**: Create a score variable to track how many enemies the player has destroyed. When an enemy is hit, increase the score.
- **Health**: Create a health variable for the player. If the player is hit by an enemy, decrease the health. If health reaches zero, the game ends.

#### Step 6: Add Game Over and Win Conditions
- When the player’s health reaches zero, display a **Game Over** screen and show the final score.
- You can also create a **win condition** where the player wins after defeating a certain number of enemies or completing a mission.

### 3. Teacher’s Tips
- Emphasize the use of **if-else** blocks for decision-making in games. For example, checking if the player's bullet touches an enemy or if the player's health reaches zero.
- Ensure students understand how to use the **pick random** block for generating random behaviors and creating an unpredictable gaming experience.
- Encourage students to test different combinations of random values and behaviors to see how it affects gameplay.

### 4. Troubleshooting Common Issues

- **Issue**: The bullets don’t disappear when they hit an enemy.
  - **Solution**: Ensure the bullet sprite includes a `hide` block after the collision and the `broadcast [Enemy Hit]` block to notify the enemy to disappear.
  
- **Issue**: Enemies spawn too quickly or too slowly.
  - **Solution**: Adjust the random range in the `pick random` block that controls the spawning rate or movement speed of the enemies. You can also introduce a delay between spawns using the `wait` block.
  
- **Issue**: The player doesn’t lose health when hit by an enemy.
  - **Solution**: Double-check the collision detection logic and ensure that the `change health by -1` block is triggered when the player is hit.

### 5. Extension Ideas

- Add **power-ups** that can heal the player or temporarily increase their damage or speed.
- Introduce **boss enemies** that require multiple hits to destroy, providing more challenging gameplay.
- Add **sound effects** for actions like shooting, hitting an enemy, and the game-over sequence.
- Include a **level system** where each level has more enemies, faster speeds, or different attack patterns.
- Create **multiple backgrounds** to simulate different environments for each level, such as a battlefield, space, or jungle.

## Conclusion

By the end of this project, students will have built a **shooter war game** where they can control a character to fight against enemies. They will have learned how to use **if-else** statements for decision-making, and how to implement **random events** to keep the game dynamic and unpredictable. Additionally, they will understand how to handle **collision detection**, implement a **score system**, and create game-over conditions. This project helps students build foundational skills in **game design**, **event handling**, and **randomization**.

---

### **Note**: The **War Game** introduces more complex logic and randomization, preparing students for more advanced projects involving multiple variables, decision-making, and game flow management.
