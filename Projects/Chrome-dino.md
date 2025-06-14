# Project : Chrome Dino 🦖

## Project Overview

In this project, students will create a game similar to the Chrome Dino game, which appears when the user is offline in the Google Chrome browser. The project is a bit more advanced compared to the **Chick & Egg** project. It involves more dynamic interactions, like jumping over obstacles (cacti) and managing a game that increases in difficulty over time. This project can also serve as an alternative to the **Chick & Egg** project if preferred by the teacher.

## Key Concepts to Focus On

- **Sprite Movement**: Guide students on making the dino sprite jump when a key is pressed.
- **Collision Detection**: Teach students how to detect if the dino collides with obstacles like cacti or other objects.
- **Score Tracking**: Introduce a score system to track how long the player survives or how many obstacles they avoid.
- **Increasing Difficulty**: Show students how to increase the speed of obstacles as the game progresses to make it more challenging.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the game: to control a dino character that jumps over cacti, similar to the offline Chrome Dino game.
   - Introduce the Scratch interface and key blocks, such as `when key pressed` and `if touching [sprite]` for handling movement and collision detection.

2. **Step-by-Step Instructions**
   - Step 1: Set up the dino sprite and create a simple background (desert or plain).
   - Step 2: Program the dino to jump when the player presses a key (usually the spacebar).
   - Step 3: Create obstacles (cacti) that move from right to left.
   - Step 4: Add collision detection to end the game if the dino touches the cactus.
   - Step 5: Implement a score system that tracks the player's progress based on the time survived or the number of obstacles avoided.
   - Step 6: Gradually increase the speed of the cacti to make the game harder as the score increases.

3. **Teacher’s Tips**
   - Help students with setting up the controls and collision detection, as this may be tricky.
   - Ensure that the game increases in difficulty gradually by adjusting the speed of obstacles based on the score or time.
   - Encourage students to add sound effects for jumping and collisions for a more dynamic experience.

4. **Troubleshooting Common Issues**
   - Issue: The dino jumps too high or too low.
     - Solution: Adjust the "change y by" value in the jump script to make the dino's jump more realistic.
   - Issue: Obstacles stop moving or don’t restart after a game over.
     - Solution: Use a `clone` block to create new obstacles after the current ones finish their movement or hit the edge.
   - Issue: The collision detection is not working properly.
     - Solution: Double-check that the `if touching [obstacle]` block is correctly placed within the game loop.

5. **Extension Ideas**
   - Allow students to add more obstacle types (e.g., birds flying across the screen).
   - Add a "game over" screen that appears when the dino collides with an obstacle.
   - Challenge students to improve the game's graphics or add a starting screen with instructions.

## Conclusion

By the end of this project, students will have created a fully functional game similar to the Chrome Dino game. This project will help them further understand the concepts of sprite movement, collision detection, score tracking, and creating interactive experiences in Scratch.

---

### **Note**: This project could be used as a more advanced alternative to the **Chick & Egg** project.
