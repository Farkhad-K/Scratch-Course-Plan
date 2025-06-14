# Racing Car 🚗

## Project Overview

The **Racing Car** is a **repetition project** designed for students to revisit and practice the key concepts they’ve already learned in Scratch. In this project, students will create a game where they control a race car, navigating through a track filled with obstacles while avoiding collisions. The goal is to practice concepts such as **sprite creation**, **movement**, **collision detection**, **variables**, and **leveling**.

As this is a repetition project, the game will focus on applying everything students have learned so far. The project reinforces skills like **movement controls**, **if-else statements**, **loops**, and **timer systems** to build a complete and functional racing game.

## Key Concepts to Focus On

- **Sprite Creation**: Students will design their own race car and track sprites.
- **Movement**: Practice moving the car using keyboard inputs (like arrow keys).
- **Collision Detection**: Detect when the car collides with obstacles or track boundaries.
- **Variables**: Use variables to track the score, time, and level progression.
- **Leveling**: Introduce progressively harder levels as the player advances.
- **Timer**: Add a timer to track how long it takes the player to finish the track.
- **Game Flow**: Manage starting, progressing through levels, and ending the game.

## Detailed Plan

### 1. Introduction (10-15 minutes)
- Explain the goal of the project: To build a **Racing Car Game** using previously learned concepts.
- Discuss how this project serves as a **repetition** exercise to solidify the skills learned, including **movement**, **collision detection**, and **leveling**.
- Go over the importance of **using variables** for tracking things like the **score** and **level**, and the role of the **timer** in keeping track of time during the race.

### 2. Step-by-Step Instructions

#### Step 1: Create the Race Car Sprite
- **Design the Race Car**: Students will create or import a **race car sprite** that will be controlled by the player.
- **Control the Race Car**: Use `when key pressed` blocks to control the car’s movement. For example:
  - Left Arrow: Move left
  - Right Arrow: Move right
  - Up Arrow: Move forward
  - Down Arrow: Move backward (optional)

#### Step 2: Design the Track
- **Create a Track Sprite**: Students will design a simple track layout using a **backdrop** or custom **track sprite**. This track should have visible boundaries to show the race area and obstacles along the way.
- **Define Boundaries**: Use collision detection to make sure the player stays on the track. If the car goes off the track, the game should end or the player should lose a life.

#### Step 3: Add Obstacles
- **Design Obstacles**: Create obstacle sprites (e.g., cones, rocks, or other cars) that the player must avoid. These obstacles will be placed along the track, and the player must navigate around them.
- **Collision Detection**: Use the `if <touching [obstacle]>` block to end the game or penalize the player when the car collides with an obstacle.

#### Step 4: Leveling and Increasing Difficulty
- **Create Levels**: After completing a level, the player should be taken to the next level. Each new level should become harder by increasing the speed of the car, adding more obstacles, or changing the track layout.
- **Level Variable**: Use a variable called `level` to track the current level. After the player finishes a level, increase the level by 1 and reset the game’s difficulty.

#### Step 5: Timer and Score
- **Timer**: Use a timer to track how long it takes for the player to finish each level. This can be done by creating a **timer variable** and using `wait` or `forever` blocks to decrease the timer.
- **Score**: Create a variable called `score` to track how well the player performs. This can be based on how quickly they finish the level or if they avoid obstacles.

#### Step 6: Game Flow
- **Start Screen**: Create a start screen where the player can click to begin the game.
- **Game Over**: Display a "Game Over" screen if the player hits an obstacle or goes off the track. Include options to restart the game or return to the start screen.
- **Level Transitions**: When the player successfully finishes a level, transition them to the next level by changing the track, increasing difficulty, and updating the level variable.

### 3. Teacher’s Tips
- **Repetition of Concepts**: This project is meant to help students solidify the concepts they’ve already learned. Encourage them to use what they already know about **variables**, **collision detection**, and **loops** to complete the game.
- **Design Focus**: Remind students that this is also an opportunity for them to get creative with their **sprite designs** and **track layouts**.
- **Debugging**: If students encounter issues with the game, encourage them to check the logic of their **collision detection**, **level progression**, and **timer** systems first.

### 4. Troubleshooting Common Issues

- **Issue**: The car moves too fast or too slow.
  - **Solution**: Adjust the movement blocks by changing the value in `change x by` or `change y by`. You can also adjust the car's speed by increasing or decreasing the time delay between movements.
  
- **Issue**: Obstacles don’t collide correctly with the car.
  - **Solution**: Make sure the `if <touching [obstacle]>` block is properly set up. Ensure the obstacle is not set to hide before the collision check is made.
  
- **Issue**: The level doesn’t reset properly.
  - **Solution**: Double-check that the **level variable** is resetting at the start of each level. Use the `change level by 1` block to increase the level and adjust the difficulty accordingly.

### 5. Extension Ideas

- **Power-ups**: Add power-ups like **speed boosts** or **shields** that can help the player avoid obstacles or move faster.
- **Multiple Tracks**: Create multiple levels with different **track layouts**, **obstacles**, and **backgrounds** to add variety to the game.
- **High Scores**: Track the highest score achieved across all levels, and display the **high score** at the end of the game.
- **Multiplayer Mode**: Add a second car controlled by another player for **split-screen racing**.

## Conclusion

By the end of this project, students will have practiced all the fundamental concepts they’ve learned in Scratch while creating a **Racing Car Game**. This includes skills such as **sprite creation**, **movement controls**, **collision detection**, **timer functions**, and **level progression**. The project serves as a great opportunity to reinforce learning through **hands-on coding**, creativity, and problem-solving.

---
