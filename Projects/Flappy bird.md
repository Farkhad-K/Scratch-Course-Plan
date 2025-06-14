# Project : Flappy Bird 🐦

## Project Overview

In this project, students will create a simplified version of the **Flappy Bird** game, where a bird must navigate through obstacles (pipes). The main focus of this project is on simulating **gravity** and the mechanics behind it, while also introducing basic **collision detection** and **scoring**.

This project is a **side project** that can be used as an alternative or in addition to other games in the course. The teacher will guide the students in creating the basic mechanics and then encourage them to expand and customize the game. This is a great opportunity for students to understand how gravity works in a 2D game and how it affects character movement.

## Key Concepts to Focus On

- **Gravity Simulation**: Show how gravity can be simulated by applying a constant force that pulls the bird downward.
- **Movement**: Use simple physics to control the bird's upward movement when a key is pressed.
- **Collision Detection**: Detect when the bird hits the pipes or the ground.
- **Score Tracking**: Implement a scoring system where the player earns points by passing through the pipes.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the project: students will create a Flappy Bird-style game with a bird navigating through obstacles.
   - Introduce the concept of **gravity** in games — gravity pulls the bird down when it is not actively pushed up.
   - Discuss how **keyboard controls** will be used to control the bird’s vertical movement.

2. **Step-by-Step Instructions**
   - **Step 1**: Create the basic game elements:
     - Add a **bird sprite** and set its initial position.
     - Add **pipe sprites** and arrange them randomly on the screen (vertical pipes).
     - Set up a **background** that moves continuously to simulate the bird flying forward.
   - **Step 2**: Simulate gravity:
     - Use the `change y by [value]` block to simulate the bird’s movement.
     - Introduce **gravity** by constantly decreasing the bird’s **y position** (downward movement).
     - When the player presses the **space bar** (or another key), the bird should **move upward** (counteracting gravity). Use the `change y by [value]` to make the bird jump.
   - **Step 3**: Add the pipe movement:
     - The pipes should continuously move from right to left, and when they exit the screen, they should be reset to a new position.
     - Use the `forever` loop with the `change x by [value]` to make the pipes move to the left.
   - **Step 4**: Collision detection:
     - Use the `if <touching [pipe]> then` block to detect if the bird hits a pipe.
     - If the bird touches a pipe or the ground, end the game or restart the level.
   - **Step 5**: Add the scoring system:
     - Each time the bird passes through a pair of pipes, increase the score.
     - Use a **score variable** to track the points. When the bird successfully passes through a set of pipes, increase the score by 1.
   - **Step 6**: Add sound effects or animations:
     - Add sound effects when the bird jumps, hits the ground, or collides with a pipe.
     - Optionally, animate the bird to make it flap its wings when jumping.

3. **Teacher’s Tips**
   - **Gravity** is the key feature of this project. Explain how applying constant downward movement simulates gravity, and how the space bar can reverse it temporarily to make the bird jump.
   - Be sure students understand the need for **repeating actions** (using the `forever` loop for continuous movement of the pipes and gravity).
   - Encourage students to experiment with **speed**: Adjusting the gravity and the speed of the pipes can make the game easier or harder.

4. **Troubleshooting Common Issues**
   - **Issue**: The bird is moving too fast or too slow.
     - **Solution**: Adjust the values in the `change y by [value]` block to control the bird's jump height and gravity.
   - **Issue**: The pipes aren’t resetting correctly.
     - **Solution**: Make sure that once the pipes move off-screen, they are reset to a new random position using the `go to x: [value]` and `y: [value]` blocks.
   - **Issue**: The game ends instantly when the bird touches a pipe.
     - **Solution**: Ensure the collision detection is set up correctly, and that the game only ends when necessary.

5. **Extension Ideas**
   - Add **different levels** with faster pipes or more obstacles to increase the difficulty.
   - Add a **high score** system to track the best score across multiple attempts.
   - Create **multiple bird skins** or change the design of the bird using different costumes.
   - Add **power-ups** that temporarily allow the bird to fly higher or slow down the pipes.

## Conclusion

By the end of this project, students will have a functional **Flappy Bird-style game** with basic gravity simulation. They will understand how to apply simple physics concepts, such as gravity and jump mechanics, to make the game interactive. This project gives students valuable experience with **movement**, **collision detection**, and **score tracking**, and serves as a foundation for more complex games in the future.

---

### **Note**: The **Flappy Bird** project is an excellent way to introduce students to the concept of **game physics** in Scratch. It helps students understand how gravity works in games, and gives them the opportunity to implement simple collision detection and scoring mechanics.
