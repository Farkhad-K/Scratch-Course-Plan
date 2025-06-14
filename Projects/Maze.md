# Project : Maze Game 🌀

## Project Overview

The **Maze Game** is the most challenging and complex game in this course. It is designed to be completed towards the end of the course, after students have gained a solid understanding of Scratch and its capabilities. In this project, students will create a maze with a character that navigates through it, avoiding obstacles and reaching the finish point.

This game involves a combination of multiple concepts, including **collision detection**, **level design**, **sprite movement**, and **game logic**. The goal of this project is to show students how complex and interactive games can be created using Scratch. Students will work through creating a fully functional maze, where they can customize levels and include additional game features, such as timers, scoring, and power-ups.

## Key Concepts to Focus On

- **Collision Detection**: Detecting collisions between the player and walls, as well as handling when the player touches the maze boundaries.
- **Movement Control**: Using arrow keys (or WASD) to move the character around the maze.
- **Level Design**: Setting up and designing the maze, including walls, paths, and start/end points.
- **Game Logic**: Implementing win conditions (reaching the end), time limits, and score tracking.

## Detailed Plan

1. **Introduction (15-20 minutes)**
   - Explain the goal of the project: students will create a **maze game** where a character has to navigate through a maze and reach the end point.
   - Discuss **collision detection** and how it works in a maze (i.e., detecting when the player touches walls).
   - Introduce the **movement control system** and how to move the character using keyboard arrows or other keys.
   - Explain how to design the maze layout, and the importance of creating **clear paths** and **obstacles**.

2. **Step-by-Step Instructions**
   - **Step 1**: Create the Maze:
     - Use a **backdrop** to draw the maze or design walls with the **paint editor**.
     - Add **wall sprites** to the stage (one for each wall section) or use a simple backdrop and detect collision with these walls.
   - **Step 2**: Character Setup:
     - Create a **player sprite** (e.g., a character that the user controls).
     - Set the initial position of the sprite at the **start point** of the maze.
     - Use **arrow keys** or **WASD keys** for character movement (`when key pressed` block).
   - **Step 3**: Movement Logic:
     - Use **`change x by`** and **`change y by`** blocks to control the character's movement based on keyboard inputs.
     - Limit movement so that the character cannot go through walls (use collision detection).
   - **Step 4**: Collision Detection:
     - Use the `if <touching [wall]> then` block to stop the player when they hit a wall.
     - Optionally, you can create visual effects (like changing the player’s costume or playing a sound) when the player collides with a wall.
   - **Step 5**: Win Condition:
     - Create a **finish point** (a specific area or sprite).
     - Use the `if <touching [finish]> then` block to detect when the player reaches the end of the maze and display a **win message** or play a sound.
   - **Step 6**: Timer and Scoring:
     - Add a **timer** to track how long it takes for the player to finish the maze.
     - Add a **score** variable that decreases with time, rewarding players for faster completion.
   - **Step 7**: Additional Features (Optional):
     - Add multiple levels with increasing difficulty (larger mazes, more obstacles, or timed challenges).
     - Include **power-ups** that temporarily make the player invincible or move faster.
     - Add sound effects and music to make the game more engaging.

3. **Teacher’s Tips**
   - **Start simple**: The maze doesn’t have to be overly complex at first. Focus on getting the basic mechanics down before adding extra features.
   - **Collision detection** is critical: Ensure that the player can’t cheat by going through walls, and make sure all the wall and finish point sprites are set up correctly.
   - Encourage students to **experiment with levels**: The more creative they get with maze design, the more challenging and fun the game will be.
   - **Use broadcast messages** to transition between levels or when the game is over.
   - Explain how to **debug** issues with wall collisions, such as making sure the player sprite stays within bounds.

4. **Troubleshooting Common Issues**
   - **Issue**: The player sprite can walk through walls.
     - **Solution**: Ensure that the `if <touching [wall]> then` block is correctly implemented to stop the player from moving through the walls.
   - **Issue**: The player is not moving smoothly.
     - **Solution**: Make sure that the `change x by` and `change y by` blocks are used correctly and that the sprite is not moving too fast or too slow.
   - **Issue**: The finish point is not being detected.
     - **Solution**: Check that the finish area is properly set up, and use `touching [finish point]` for collision detection.

5. **Extension Ideas**
   - Create multiple **maze designs** that students can choose from, each with a unique layout.
   - Introduce **randomly generated mazes**: After finishing one level, a new maze is created each time.
   - Add **enemies or obstacles** that move around the maze, making it more difficult for the player to reach the end.
   - Include a **timer** that challenges players to complete the maze within a set amount of time.
   - Add a **score system** that rewards players for each level completed, and tracks high scores.

## Conclusion

By the end of this project, students will have a fully functional maze game that showcases their ability to create complex interactions and game mechanics in Scratch. They will understand **collision detection**, **movement control**, **level design**, and **game logic**—key skills that will help them with more advanced game development.

---

### **Note**: The **Maze Game** is an excellent culmination of all the skills learned throughout the course. It challenges students to use their creativity and problem-solving skills to build a fully interactive game. It also shows them the potential of Scratch to create real, complex games that can be as intricate as those made with more advanced programming languages.
