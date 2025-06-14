# Project : Jump Chick 🐣

## Project Overview

In this project, students will create a simple jumping game where the main character, a chick, must jump over eggs that fall from the top of the screen. The game is inspired by the **Chrome Dino** game but much simpler. The goal of the project is to introduce basic game mechanics like **collision detection**, **key press events**, and **movement control** using **Scratch**.

Students will learn how to use the **`forever`** block, **`if`** blocks, and **`key space pressed`** blocks for more responsive gameplay. The project also focuses on **using sprites** effectively, with the chick and the egg being the main interactive elements in the game.

## Key Concepts to Focus On

- **Forever Loop**: Teach students how to use the `forever` block to make sure the game runs continuously.
- **If Condition**: Use the `if` block to detect when the chick presses the space key and jumps.
- **Collision Detection**: Demonstrate how to detect if the chick has collided with the falling egg.
- **Key Space Pressed**: Introduce the `key [space] pressed?` block (from sensing) for making the chick jump.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the project: creating a jumping game where the chick must avoid falling eggs.
   - Discuss the basic mechanics of the game, such as jumping and detecting collisions with the egg.
   - Introduce the Scratch **forever loop** and **if statements** for continuous gameplay and decision-making.

2. **Step-by-Step Instructions**
   - **Step 1**: Create two sprites:
     - A **chick** sprite that will move up and down.
     - An **egg** sprite that will fall from the top of the screen.
   - **Step 2**: Position the chick and egg at their starting points.
     - Position the chick at the bottom of the screen.
     - Place the egg at a random position at the top of the screen.
   - **Step 3**: Set up the chick’s jump mechanic:
     - Use the `if <key [space] pressed?> then` block (from sensing) inside a `forever` loop to make the chick jump when the space bar is pressed.
     - For better responsiveness, demonstrate how using `forever` with `if` inside it is much faster than the `when [space] key pressed` block.
     - Use `change y by [value]` to move the chick upwards when the space bar is pressed and simulate the jump.
   - **Step 4**: Make the egg fall:
     - Use a `forever` loop to make the egg fall continuously.
     - Use `change y by [-10]` to move the egg downward.
     - When the egg touches the ground, reset its position to fall again from the top.
   - **Step 5**: Collision detection:
     - Use the `if <touching [chick]> then` block to detect when the egg touches the chick.
     - When a collision is detected, end the game or show a "Game Over" message.
   - **Step 6**: Add a simple score system:
     - Create a variable to track how many eggs the chick has successfully avoided.
     - Increase the score whenever the egg is missed.

3. **Teacher’s Tips**
   - Emphasize how the **forever loop** works in this project, and why it's better to use it with the `key [space] pressed` block rather than `when [space] key pressed`.
   - Make sure students understand the importance of **collision detection** and how it adds interactivity to the game.
   - Encourage students to experiment with the falling speed of the egg, the jump height of the chick, and the difficulty level of the game.

4. **Troubleshooting Common Issues**
   - **Issue**: The chick is jumping too slowly or not responding quickly enough.
     - **Solution**: Show students how using `forever` with `if` blocks is much faster than the `when [space] key pressed` event block. Adjust the jump speed to make it more responsive.
   - **Issue**: The egg is not falling correctly or resetting.
     - **Solution**: Double-check the position of the egg sprite and make sure it resets to a random position at the top when it reaches the bottom.
   - **Issue**: The chick is not detecting the collision with the egg.
     - **Solution**: Ensure the collision detection block (`if touching [egg] then`) is working correctly and that the egg sprite is touching the chick sprite when it falls.

5. **Extension Ideas**
   - Add a **score counter** that increases when the chick successfully jumps over an egg.
   - Introduce **multiple levels** with faster egg falling speeds.
   - Add **sound effects** when the chick jumps or when the game is over.
   - Allow the chick to move left and right by pressing arrow keys to avoid eggs more effectively.

## Conclusion

By the end of this project, students will have created a simple yet fun jumping game, where they can control the chick’s jumps and avoid falling eggs. This project will teach them how to use the **forever loop**, **if** conditions, and key press events for creating interactive gameplay. Additionally, students will gain a deeper understanding of collision detection and how to create basic game mechanics in Scratch.

---