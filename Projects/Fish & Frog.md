# Project : Fish & Frog 🐟🐸

## Project Overview

In this project, students will create an interactive game where a **fish** and a **frog** interact. The goal is to introduce students to the concept of **sprite direction**, as this is the first time the direction of sprites will be manipulated. Students will learn how to control the direction of sprites using the `point in direction` and `turn` blocks. The game also uses basic collision detection and movement mechanics.

This project is a great opportunity for students to understand how direction works in Scratch, and how to create engaging interactions between characters using simple logic.

## Key Concepts to Focus On

- **Sprite Direction**: Understanding how to manipulate the direction of sprites to control their movement (using `point in direction` and `turn`).
- **Collision Detection**: Detecting when the fish and frog meet or interact.
- **Movement**: Moving the fish and frog using the arrow keys and controlling their direction in the game.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the project: students will create a simple game where a fish and frog interact.
   - Introduce the **direction** concept — how sprites can be rotated and how to control their movement using `point in direction`.
   - Show examples of how `turn`, `move`, and `point in direction` blocks can affect sprite movement.

2. **Step-by-Step Instructions**
   - **Step 1**: Create two sprites:
     - A **fish** sprite that moves across the screen.
     - A **frog** sprite that the player can control using the arrow keys.
   - **Step 2**: Set up the fish sprite:
     - Use the `when green flag clicked` block to initialize the game.
     - Use the `go to [x: 0, y: 0]` block to set the fish's starting position.
   - **Step 3**: Manipulate the direction of the fish sprite:
     - Use the `point in direction [90]` block to point the fish in a specific direction.
     - Students should experiment with different directions (e.g., `point in direction [180]` for moving left, `point in direction [90]` for moving right).
     - Make the fish change direction when it reaches the edge of the screen using the `if <touching edge>` block.
   - **Step 4**: Set up the fish sprite:
     - The fish will be controlled by the player using the **arrow keys**.
     - Use the `when [right arrow] key pressed` and `when [left arrow] key pressed` blocks to move the fish left or right.
   - **Step 5**: Add sound effects or animation:
     - Add a sound effect when the frog catches the fish, using the `play sound [sound] until done` block.
     - Optionally, add a small animation for both the fish and the frog when they collide, such as making the frog “jump” or the fish change color.

3. **Teacher’s Tips**
   - **Direction** is the most important concept here, so make sure students understand how to change the direction of the fish and frog sprites.
   - Remind students that **sprite movement** isn’t just about moving in one direction — they should experiment with using `point in direction` to move sprites in different ways.

4. **Troubleshooting Common Issues**
   - **Issue**: The fish doesn’t change direction when it touches the edge.
     - **Solution**: Ensure that the `if <touching edge>` block is set up correctly, and the `point in direction` block is used to change direction when needed.
   - **Issue**: The frog moves too fast.
     - **Solution**: Adjust the `change x by [value]` block to make the frog's movement slower and more controlled.
   - **Issue**: The fish doesn’t catch the frog.
     - **Solution**: Double-check the collision detection logic to make sure the `if <touching [frog]>` block is in the right place and is detecting the correct sprites.

5. **Extension Ideas**
   - Add a **timer** that counts down, and when the time is up, the game ends.
   - Create **multiple levels** where the fish moves faster as the game progresses.
   - Introduce **new characters or obstacles**, like adding a shark or other creatures that the frog must avoid.
   - Add **sound effects** when the frog catches the fish or when the fish escapes.

## Conclusion

By the end of this project, students will have learned how to manipulate the **direction** of sprites using the `point in direction` block, which is a crucial skill for creating dynamic and interactive games. They will also have practiced **sprite movement**, **collision detection**, and **keyboard controls**. This project sets the stage for more complex game mechanics and reinforces important programming concepts.

---

### **Note**: The **Fish & Frog** project is perfect for practicing sprite movement and direction. While the gameplay itself is simple, understanding how to control the direction of sprites will help students when they start working with more complex projects.
