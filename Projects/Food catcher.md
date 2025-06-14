# Project : Food Catcher 🍎🍔

## Project Overview

In this project, students will create a fun **game** where the player controls a sprite (the basket) that catches falling food items. The game will introduce students to a variety of essential Scratch concepts, including **cloning**, **sprite movement**, **collision detection**, and **scoring**. This is the first game project in the course, so it’s a great opportunity to get students familiar with using Scratch to build interactive experiences.

The goal of this project is to give students a solid foundation in how to create games, using basic programming concepts like controlling sprites with the keyboard, detecting collisions, and cloning objects.

## Key Concepts to Focus On

- **Cloning**: Teach students how to create clones of food items that fall from the top of the screen.
- **Keyboard Control**: Use arrow keys or other key events to control the movement of the player’s sprite (the basket).
- **Sensing**: Detect when the basket touches the falling food using **`touching`** blocks.
- **Scorekeeping**: Introduce variables to keep track of the score and display it on the screen.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the project: students will create a game where they control a basket to catch falling food items.
   - Introduce the **Scratch interface** and briefly explain key blocks like `when green flag clicked`, `move`, and `if <touching?>`.
   - Discuss **cloning**, **keyboard controls**, and **collision detection**.

2. **Step-by-Step Instructions**
   - **Step 1**: Create two sprites:
     - A **basket** sprite that the player will control.
     - A **food** sprite (such as an apple or hamburger) that will fall from the top of the screen.
   - **Step 2**: Set up the basket:
     - Use the `when green flag clicked` block to start the game.
     - Use the `go to x: [value] y: [value]` block to position the basket at the bottom of the screen.
     - Add keyboard controls to move the basket left and right. You can use `when [left arrow] key pressed` and `when [right arrow] key pressed` blocks, and the `change x by [value]` block to move the basket.
   - **Step 3**: Add clones of the food sprite:
     - Use the `create clone of [food]` block to make the food fall from the top of the screen.
     - The food clones should start at random x positions and fall downward.
     - Use a `forever` loop to make sure the food continues falling.
     - When a food clone touches the bottom of the screen (or the basket), it will disappear.
   - **Step 4**: Handle collisions:
     - Use the `if <touching [basket]> then` block to check when the food clone touches the basket.
     - If it does, increase the score and destroy the clone.
     - If the food clone touches the bottom without being caught, decrease the score or add a "miss" counter.
   - **Step 5**: Add a score counter:
     - Create a **variable** (e.g., "Score") to keep track of the number of food items caught.
     - Use the `change [variable] by [value]` block to increase or decrease the score.
     - Display the score on the screen using the `show variable [variable]` block.
   - **Step 6**: Add sound effects:
     - Play a sound when the basket catches a food item or when the food hits the ground.

3. **Teacher’s Tips**
   - Focus on the main concepts: **sprite movement**, **cloning**, and **sensing**.
   - Explain the basic idea behind clones and how they allow multiple copies of the same sprite to be created.
   - Encourage students to use the **`forever`** and **`if`** loops to ensure that the game runs continuously and checks for collisions throughout the game.

4. **Troubleshooting Common Issues**
   - **Issue**: The basket is not moving smoothly.
     - **Solution**: Double-check the movement controls and make sure that the basket is only moving left or right when the appropriate key is pressed.
   - **Issue**: The food clone is not falling or disappearing.
     - **Solution**: Ensure that the clone’s position is being set correctly at the top of the screen and that the `change y by [value]` block is inside a `forever` loop.
     - Ensure that you are using the `delete this clone` block when the clone is either caught or falls to the bottom.
   - **Issue**: The score is not updating.
     - **Solution**: Check if the `change [score] by [value]` block is correctly placed after the collision detection (`if <touching [basket]> then`).

5. **Extension Ideas**
   - Add **levels** to the game where the food falls faster as the score increases.
   - Include multiple types of food (some could give positive points, while others could take away points or lives).
   - Add a **timer** to challenge students to catch as much food as possible in a limited time.
   - Use **sound effects** for catching food, missing food, or for game-over events.
   - Create a **game over screen** that appears after a certain number of missed items, and give the option to restart the game.

## Conclusion

By the end of this project, students will have created a complete **Food Catcher** game with basic interactive gameplay. They will have used essential **Scratch concepts** such as cloning, sprite movement with keyboard controls, collision detection, and scorekeeping. This project is a great introduction to building interactive games in Scratch and will set the stage for more complex projects later in the course.

---

### **Note**: This project is designed to give students hands-on experience with various important Scratch concepts while creating a fun and engaging game. It is an excellent first game project, as it covers a variety of important features without becoming too complicated.
