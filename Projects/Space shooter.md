# Space Shooter 🚀🌑

## Project Overview

In this project, students will create a **Space Shooter** game where the player controls a space rocket and must dodge falling rocks. The game will be vertical-scrolling, meaning that the screen will move downward as the player avoids obstacles. The goal of the game is to survive as long as possible while dodging the falling rocks, and the player will earn points for each second they survive.

This game will serve as a **repetition** and **refinement** exercise for all the **code blocks** that students have learned so far, including:

- **Movement and Control**: Moving the rocket with arrow keys.
- **Randomization**: Making the rocks fall at random positions and speeds.
- **Collision Detection**: Detecting when the rocket collides with a rock.
- **Score System**: Tracking how long the player survives.
- **Cloning**: Creating multiple falling rocks.

## Key Concepts to Focus On

- **Movement**: Use `when key pressed` blocks for controlling the rocket with arrow keys.
- **Randomization**: Use the `pick random` block for randomizing rock speeds, positions, and spawn rates.
- **Collision Detection**: Detect when the rocket collides with a rock using `if <touching [rock]>` blocks.
- **Cloning**: Use cloning to create multiple falling rocks.
- **Score System**: Implement a score system that tracks the player’s survival time.
- **Game Flow**: Introduce a game-over condition when the rocket hits a rock.

## Detailed Plan

### 1. Introduction (10-15 minutes)
- Explain the purpose of the game: Control a rocket to dodge falling rocks.
- Discuss how the game will use **movement**, **collision detection**, **randomization**, and **cloning** to create a dynamic experience.

### 2. Step-by-Step Instructions

#### Step 1: Set Up the Rocket Sprite
- Create the **rocket sprite** that the player will control.
- Use `when key pressed` blocks to move the rocket left and right (using the left and right arrow keys).
- Limit the rocket's vertical movement (to keep it in the game view) by using the `y` position.
  
#### Step 2: Set Up the Rock Sprite
- Create a **rock sprite** that will fall from the top of the screen.
- Use the `create clone of [myself]` block to make multiple rocks appear.
- Use `go to x: [pick random] y: [pick random]` to spawn rocks at random horizontal positions and give them a starting point off-screen at random vertical heights.
  
#### Step 3: Make the Rocks Fall
- Use the `glide` or `change y by` blocks to make the rocks fall at a random speed.
- Randomize the speed of each rock using `pick random` blocks (e.g., `pick random -5 to -10` for downward speed).

#### Step 4: Collision Detection and Game Over
- Use the `if <touching [rock]>` block to detect when the rocket collides with a rock.
- If a collision is detected, stop the game and display a **Game Over** message.
  
#### Step 5: Implement the Score System
- Create a **score variable** to track the time the player survives.
- Increase the score by 1 every second (using a `wait 1 second` block inside a loop).
- If the rocket collides with a rock, stop increasing the score and display the final score.

#### Step 6: Use Cloning for Multiple Rocks
- Use the `create clone of [myself]` block to create multiple rocks at different positions.
- Each cloned rock will fall at a random speed, and when it reaches the bottom of the screen, it should be deleted or respawned.

### 3. Teacher’s Tips
- **Movement**: Remind students that the rocket’s movement should be constrained to the horizontal axis, so the `if` block can help to keep the rocket within the game view.
- **Randomization**: Emphasize how to use `pick random` to vary rock speeds and spawn points. Randomized gameplay adds unpredictability to the game.
- **Cloning**: Ensure students are comfortable with the `create clone of [myself]` block and that they know how to reset the cloned rock’s position after it falls off the screen.

### 4. Troubleshooting Common Issues

- **Issue**: The rocket moves off the screen.
  - **Solution**: Use the `if <x position > [value]>` and `if <x position < [value]>` blocks to keep the rocket within certain horizontal limits.
  
- **Issue**: Rocks are not falling properly or too fast.
  - **Solution**: Adjust the speed by modifying the `pick random` block for the `change y by` block. Test different random ranges for more variety in the speeds.

- **Issue**: The score does not increase correctly.
  - **Solution**: Ensure the score is increased in the correct place (inside a loop) and that it only stops when the game is over. Make sure there are no conflicting `stop all` blocks affecting the score.

### 5. Extension Ideas

- Add **sound effects** for when the rocket moves, when a rock hits the rocket, and when the game is over.
- Introduce **power-ups** (such as shields or speed boosts) that appear randomly and temporarily help the rocket avoid rocks.
- Make the **rocks spawn faster** over time to increase the difficulty of the game as the player survives longer.
- Add **background music** to create a more immersive experience.
- Introduce **levels** where the rocks fall at different speeds or new obstacles are introduced.

## Conclusion

By the end of this project, students will have built a **Space Shooter** game where the goal is to dodge falling rocks. They will have revisited and applied key concepts like **movement**, **collision detection**, **randomization**, **cloning**, and **scorekeeping**. This project is an excellent opportunity to practice their skills in **game design** and **event handling** while building an engaging and fun vertical-scrolling game.

---

### **Note**: The **Space Shooter** game provides an excellent review of many of the concepts learned throughout previous projects. Students will gain further experience with handling random events, sprite interactions, and maintaining game flow—all of which are crucial in game development.
