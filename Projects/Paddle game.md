# Project : Paddle Game 🏓

## Project Overview

In this project, students will create a simple **Pong-like game** where they control a paddle to bounce a ball back and forth. This project is designed to reinforce several key concepts learned earlier in the course, such as **sprite movement**, **keyboard controls**, **sensing collisions**, and **variables** for tracking the score. The game may not be very advanced, but it is an excellent exercise to practice the skills students have learned up to this point.

This is a great project for revisiting and consolidating the basics while having fun!

## Key Concepts to Focus On

- **Sprite Movement**: Use the keyboard to move the paddle.
- **Collision Detection**: Detect when the ball touches the paddle and the edges of the screen.
- **Scorekeeping**: Create and update a score variable.
- **Repetitive Loops**: Use loops to keep the game running and repeating actions.
- **Direction Control**: Learn how the ball’s direction can be controlled by bouncing off walls and the paddle.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the project: students will create a basic Pong game where they control a paddle to bounce a ball back and forth.
   - Review the key concepts that will be used: **sprite movement**, **keyboard controls**, **sensing** blocks, **collision detection**, and **variables**.
   - Briefly go over the **Scratch interface** and where the important blocks are located.

2. **Step-by-Step Instructions**
   - **Step 1**: Create two sprites:
     - A **paddle** sprite that the player will control.
     - A **ball** sprite that will bounce around the screen.
   - **Step 2**: Set up the paddle:
     - Use the `when green flag clicked` block to start the game.
     - Position the paddle at the bottom of the screen with the `go to x: [value] y: [value]` block.
     - Add movement controls to the paddle using the `when [left arrow] key pressed` and `when [right arrow] key pressed` blocks. Use `change x by [value]` to move the paddle left and right.
   - **Step 3**: Set up the ball:
     - Create a simple ball sprite that starts in the middle of the screen.
     - Use a `forever` loop to make the ball move continuously. The ball should use the `glide` block to move across the screen.
     - Introduce **random direction** for the ball at the start using the `point in direction` block.
   - **Step 4**: Add collision detection for the paddle:
     - Use the `if <touching [paddle]> then` block to check when the ball touches the paddle.
     - When the ball touches the paddle, reverse its **y-direction** using the `point in direction` block (e.g., change the ball’s direction to bounce it back).
   - **Step 5**: Add boundary conditions:
     - Use the `if <y position > [value]` block to detect when the ball hits the top of the screen and reverse its direction.
     - Use the `if <y position < [value]` block to detect when the ball hits the bottom and create a point-loss condition or game-over condition.
   - **Step 6**: Scorekeeping:
     - Create a **score variable** that increases each time the ball hits the paddle.
     - Display the score on the screen using the `show variable [score]` block.
     - Add a **missed ball** counter that decreases the score if the ball falls below the paddle.
   - **Step 7**: Add sound effects:
     - Play a sound effect when the ball bounces off the paddle or the top of the screen.
     - Optionally, add a sound effect when the ball misses the paddle.

3. **Teacher’s Tips**
   - Emphasize the use of **sensing blocks** for detecting collisions between the ball and the paddle.
   - Teach students how to **reverse direction** using the `point in direction` block to make the ball bounce.
   - Encourage students to use **forever loops** to continuously check for conditions (like collisions or score updates).
   - Focus on helping students debug their code if the ball is not bouncing correctly or the paddle isn't moving as expected.

4. **Troubleshooting Common Issues**
   - **Issue**: The ball doesn’t bounce when it hits the paddle.
     - **Solution**: Ensure that the ball is correctly detecting the paddle using the `if <touching [paddle]> then` block and that the `point in direction` block is correctly changing the ball’s direction.
   - **Issue**: The paddle moves too quickly or slowly.
     - **Solution**: Adjust the value of the `change x by [value]` block to make the paddle move at the right speed.
   - **Issue**: The ball moves too fast or doesn’t bounce properly.
     - **Solution**: Check the ball’s `glide` speed and adjust it. Make sure the **bounce** effect is triggered at the right time.

5. **Extension Ideas**
   - Add **levels** to the game: Make the ball go faster after every point scored or after a set time.
   - Add **multiple paddles** or a second player (for a 2-player mode).
   - Introduce **lives**: Give the player a set number of lives, and if the ball falls below the paddle a certain number of times, the game ends.
   - Implement a **timer**: Add a countdown timer, and when the time runs out, the game ends and displays the final score.

## Conclusion

By the end of this project, students will have created a simple but functional **Pong-like game**. They will have practiced essential programming concepts such as sprite movement, collision detection, scorekeeping, and working with variables. This project will reinforce their understanding of key Scratch blocks and provide a solid foundation for creating more complex games.

---

### **Note**: The Paddle Game project is a great way for students to practice what they've learned so far in the course. While the mechanics are simple, students can get creative with adding extra features and customizing the game to make it their own.
