# Racing Game 🏎️🏁

## Project Overview

In this project, students will create a **Racing Game** where they design all the sprites (cars, track, obstacles) and backdrops themselves. The player will control a race car that must navigate through a series of tracks, avoiding obstacles and trying to complete laps within a time limit. As the player progresses, the game will introduce **leveling**, where each new level is more difficult than the last.

This project will allow students to demonstrate their creativity and coding skills, while also practicing concepts such as **sprite design**, **leveling**, **collision detection**, and **game flow management**.

## Key Concepts to Focus On

- **Sprite Creation**: Students will create their own **race car sprite**, **track sprite**, and any **obstacles** or **power-ups** that appear in the game.
- **Leveling**: The game will increase in difficulty with each level by making the track harder, increasing the speed of the car or obstacles, and limiting the time for the race.
- **Movement**: Students will use **arrow keys** or **tilt controls** to move their race car and avoid obstacles.
- **Collision Detection**: The car must avoid obstacles on the track, and if it hits an obstacle, the game ends or the player loses time.
- **Score System**: A score will track how fast the player completes each level and how many levels they have passed.

## Detailed Plan

### 1. Introduction (15-20 minutes)
- Explain the purpose of the game: To control a race car, avoid obstacles, and finish each race within the set time.
- Discuss how students will **design their own sprites** and **create the backdrop** for each level of the game.
- Introduce the concept of **leveling**, where the game will increase in difficulty after each successful race.

### 2. Step-by-Step Instructions

#### Step 1: Set Up the Race Car Sprite
- **Create the Race Car Sprite**: The students will design their own race car using the Scratch drawing tools or import an image. It will be the main sprite controlled by the player.
- **Control the Race Car**: Use the `when key pressed` blocks to allow the car to move up, down, left, and right using the arrow keys. If using tilt controls, this can be done using **sensor blocks** or custom controls.
  
#### Step 2: Design the Track and Obstacles
- **Design the Track**: The students will create a **track sprite** or multiple track sprites that form a path for the car to follow. This can include a **start line**, **finish line**, and turns or curves.
- **Add Obstacles**: Design obstacle sprites (e.g., cones, rocks, or other cars) that will appear on the track. The player must avoid these obstacles as they race.

#### Step 3: Add Leveling and Increasing Difficulty
- **Track Difficulty**: As the player progresses, the track can change to become harder. For example, the track might include more **sharp turns**, **obstacles**, or **narrow paths** in later levels.
- **Car Speed**: As the player advances, the race car might increase in speed or the obstacles could move faster to make the game harder.
- **Time Limit**: Introduce a **time limit** for each level. If the player finishes the track within the time, they proceed to the next level. If they run out of time, they lose the game.
- **Level Progression**: After completing a level, the player is automatically moved to the next level, where the difficulty increases. Use a **level variable** to track the current level.

#### Step 4: Implement Collision Detection
- **Collision with Obstacles**: Use the `if <touching [obstacle]>` block to detect when the car hits an obstacle. If this happens, either stop the game or reduce the player's time or score.
- **Collision with Track Boundaries**: Ensure the player can't go off the track by using boundary checks with the `x` and `y` positions. If the car crosses the boundary, the game can end or restart.

#### Step 5: Add a Score System
- **Score**: Create a **score variable** to track the player’s performance. This can be based on how quickly they finish each race or how many levels they pass.
- **Level Completion**: When the player finishes a level, increase the score based on the time taken and the level reached.

#### Step 6: Set Up a Timer and Game Over Conditions
- **Timer**: Use a **timer** to give the player a limited amount of time to complete each level. Display the timer on the screen.
- **Game Over**: If the player’s time runs out, display a **Game Over** screen and show the final score.

### 3. Teacher’s Tips
- Encourage students to be **creative** with their track designs and obstacle placements. The difficulty should ramp up naturally as the player progresses.
- Remind students that **collision detection** is key to making the game challenging. Obstacles should be spaced out in a way that is challenging but not impossible.
- **Leveling**: Help students think about how they want the game to evolve as the player moves to higher levels. They can increase the speed, add more obstacles, or change the track layout.

### 4. Troubleshooting Common Issues

- **Issue**: The car moves too quickly or too slowly.
  - **Solution**: Adjust the speed by changing the values in the movement code. You can add acceleration over time or adjust the `change x by` or `change y by` values.
  
- **Issue**: Obstacles don’t behave as expected.
  - **Solution**: Double-check the cloning of obstacles and ensure they’re moving in the correct direction. You can use `glide` or `move steps` blocks to control their speed and behavior.

- **Issue**: The timer doesn’t reset after each level.
  - **Solution**: Ensure the timer is reset at the start of each new level and starts counting down from the correct value.

### 5. Extension Ideas

- **Power-ups**: Add **boosts** or **shields** that temporarily increase the car’s speed or protect it from obstacles.
- **Multiple Tracks**: Create multiple track designs with different themes and backgrounds. Change the backdrop for each level to make it feel like the player is racing in a different environment.
- **Leaderboard**: Create a **leaderboard** to track the player’s highest score and display it on the main menu or after the game ends.
- **Multiplayer Mode**: Add a second car controlled by another player. The players can race against each other, and the first to the finish line wins.

## Conclusion

By the end of this project, students will have built a **Racing Game** where they can race through a custom-designed track, avoid obstacles, and progress through increasingly difficult levels. Students will practice key concepts such as **sprite creation**, **leveling**, **movement**, **collision detection**, and **game flow management**. This project will also allow them to showcase their creativity through custom-designed sprites and backdrops.

---