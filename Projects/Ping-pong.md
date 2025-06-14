# Project : Ping Pong (2-Player Game) 🏓

## Project Overview

In this project, students will create a **2-player Ping Pong** game, similar to the classic Pong game. This game allows two players to control paddles on either side of the screen and hit a ball back and forth. The goal is to keep the ball in play and score points by getting the ball past the opponent’s paddle.

This project introduces students to the concept of **multi-player interaction**, teaching them how to handle **two sets of controls**, **collision detection** with multiple paddles, and managing the **score system** for both players.

## Key Concepts to Focus On

- **Sprite Interaction**: Handling interactions between two paddles and a bouncing ball.
- **Movement Control**: Managing player input for both paddles using keyboard controls.
- **Collision Detection**: Detecting when the ball touches the paddles or edges of the screen.
- **Scoring System**: Creating a score variable to keep track of each player’s points.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the basic idea of the project: a 2-player ping pong game where players try to score points by hitting the ball past the opponent’s paddle.
   - Discuss the key concepts: sprite interactions, collision detection, and using multiple control schemes.
   - Introduce the necessary blocks for **movement**, **collision detection**, and **scoring**.

2. **Step-by-Step Instructions**
   - **Step 1**: Set up the backdrop and paddles:
     - Create two **paddles** (one for each player) and position them on opposite sides of the stage.
     - Set the initial position of the **ball** at the center of the stage.
   - **Step 2**: Control the paddles:
     - Use the `when key pressed` blocks for the first paddle (e.g., W and S keys for Player 1) and the second paddle (e.g., Up and Down arrow keys for Player 2).
     - Use `change y by` blocks to move the paddles up and down based on the key press.
   - **Step 3**: Ball movement and collision detection:
     - Use the `glide` block to move the ball. Make sure the ball continuously bounces off the edges of the stage (top and bottom).
     - Add collision detection using `if <touching [paddle]> then` blocks to make the ball bounce off the paddles.
   - **Step 4**: Scoring:
     - Create a **score** variable for both players.
     - Set the score to increase when the ball passes one of the paddles (i.e., if the ball goes off the left or right edge of the stage).
     - Display both players' scores on the screen using the **score variables**.
   - **Step 5**: Restart the game:
     - After a player scores a point, reset the ball to the center and allow the game to continue.

3. **Teacher’s Tips**
   - Emphasize the **coordination** between both players and the ball. Ensure students understand how the paddles interact with the ball, and how the ball’s direction changes after a bounce.
   - Focus on using **repeat** or **forever** loops to handle the continuous movement of the ball and paddles.
   - Encourage students to **test and debug** their game frequently. For example, make sure the ball bounces correctly and that the paddles move smoothly without glitches.
   - If students struggle with paddle movement, guide them through adjusting their control blocks for smoother movement.

4. **Troubleshooting Common Issues**
   - **Issue**: The paddles move too fast or too slow.
     - **Solution**: Adjust the `change y by` block values to control how fast the paddles move. Test different values to find a suitable speed.
   - **Issue**: The ball gets stuck or doesn’t bounce off the paddles correctly.
     - **Solution**: Double-check that the `if <touching [paddle]> then` block is correctly set up, and ensure the ball bounces off the paddles at the right angle.
   - **Issue**: The score doesn’t reset when a point is scored.
     - **Solution**: Make sure the score is set to reset after a point is scored, and that the ball’s position is reset to the center after each point.

5. **Extension Ideas**
   - Add a **sound effect** when the ball hits a paddle or when a point is scored.
   - Create **different difficulty levels** by making the ball move faster as the game progresses.
   - Implement a **timer** to limit the game time and declare a winner when the time runs out.
   - Include **custom paddle designs** and backgrounds to make the game visually appealing.
   - Allow for **computer-controlled players** as an option for single-player mode.

## Conclusion

By the end of this project, students will have created a fun and interactive 2-player Ping Pong game, helping them understand how to manage multiple controls, detect collisions, and keep track of scores in a game. They will also gain experience in game design, sprite interaction, and debugging, which are essential skills in Scratch programming.

---

### **Note**: The **Ping Pong Game** helps students practice all the key concepts learned up to this point, including sprite control, collision detection, and scoring. It is also an excellent introduction to multi-player game logic, giving students the opportunity to create games with two interacting players.
