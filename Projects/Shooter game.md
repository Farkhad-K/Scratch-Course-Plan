# Project : Shooter Game 🦅🔫

## Project Overview

In this project, students will create a **shooter game** where the goal is to hunt down flying birds. The game will introduce the concept of **broadcasting** and **receiving messages** in Scratch. Players will control a shooter sprite that can shoot at birds that fly across the screen. When the bird is hit, it disappears, and the player earns points.

This is a simple **hunting game** where students will apply the concepts of **sprite interaction**, **broadcasting**, and **cloning** to create a dynamic game. It’s a great introduction to managing game events like starting a new round, scoring, and updating the screen.

## Key Concepts to Focus On

- **Broadcasting**: Teach students how to send and receive messages between sprites to coordinate actions (e.g., making the bird disappear when hit).
- **Cloning**: Guide students to use cloning to make multiple birds appear and fly across the screen.
- **Collision Detection**: Explain how to detect when the bullet touches the bird and trigger actions (like making the bird disappear).
- **Score System**: Help students implement a score system to track how many birds the player has successfully hit.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the game: to hunt down birds flying across the screen by shooting at them.
   - Introduce the **broadcast** and **receive** blocks that will allow sprites to communicate with each other.
   - Discuss how clones will be used for creating multiple birds and how collision detection works.

2. **Step-by-Step Instructions**
   - **Step 1**: Set up the shooter and bird sprites:
     - Create a **shooter sprite** that will be controlled by the player.
     - Create a **bird sprite** that will fly across the screen.
   - **Step 2**: Control the shooter sprite:
     - Use the `when key pressed` blocks to move the shooter left and right (for example, using the left and right arrow keys).
     - Use the `when space key pressed` block to shoot a bullet.
   - **Step 3**: Create the bullet sprite:
     - Design a simple bullet sprite.
     - Make the bullet move upwards when the player presses the spacebar.
     - Use `if <touching [bird]>` blocks to detect when the bullet hits a bird.
   - **Step 4**: Set up broadcasting:
     - When the bullet hits a bird, use the `broadcast [Bird Hit]` block to send a message that the bird has been hit.
     - Use the `when I receive [Bird Hit]` block in the bird sprite to hide the bird and increase the score.
   - **Step 5**: Implement the score system:
     - Create a **score variable** to track the player's score.
     - When the bird is hit, increase the score using the `change score by 1` block.
   - **Step 6**: Use cloning for multiple birds:
     - Use the `create clone of [myself]` block to create new birds that will move across the screen.
     - Set each cloned bird to fly in random directions.
     - Use the `when I start as a clone` block to initialize the bird’s movement and position when cloned.

3. **Teacher’s Tips**
   - Emphasize the use of **broadcasting** to make different sprites work together, such as making the bird disappear when the bullet hits it.
   - Ensure students understand how **cloning** works, especially when using it to create multiple birds that fly across the screen.
   - If students struggle with broadcasting and receiving messages, walk them through the process of creating and receiving a message in a simple example, such as having one sprite say something when another sprite sends a message.
   - Remind students to check that their **collision detection** (bullet hitting the bird) works properly by using the `if <touching [bird]>` block.

4. **Troubleshooting Common Issues**
   - **Issue**: The bullet doesn't disappear when it hits the bird.
     - **Solution**: Check that the bullet's code includes a `hide` block when it touches the bird and that the `broadcast [Bird Hit]` block is used correctly to trigger the hiding.
   - **Issue**: The birds don’t clone or move randomly.
     - **Solution**: Ensure that the `create clone of [myself]` block is placed in the correct spot (likely in a loop) to continually create birds, and that the clones use `go to random position` and `glide` blocks to move.
   - **Issue**: The score doesn’t update when the bird is hit.
     - **Solution**: Double-check the `change score by 1` block and make sure it is inside the `when I receive [Bird Hit]` block in the bird sprite, after it has been hit.

5. **Extension Ideas**
   - Add **sound effects** for when the player shoots the bullet and when the bird is hit.
   - Include a **timer** that limits the game to a certain duration, and declare a winner when the time is up.
   - Introduce **multiple levels** by making the birds move faster or spawn more frequently as the game progresses.
   - Create a **game-over screen** that shows the player’s final score after they miss too many birds or after the timer runs out.
   - Add **background music** or a **scoreboard** to enhance the overall experience of the game.

## Conclusion

By the end of this project, students will have built a **hunting game** where they control a shooter to hunt down birds using broadcasting and cloning. They will understand how to make different sprites communicate using broadcasts, and how to create clones to handle multiple enemies in the game. This project will help students gain experience in **game flow management**, **event handling**, and **scorekeeping**, which are crucial skills in game design.

---

### **Note**: The **Shooter Game** provides a solid introduction to more advanced concepts like **broadcasting** and **cloning**, preparing students for future projects that involve more complex sprite interactions and event-driven programming.
