# Project : Word Animation ✨

## Project Overview

In this project, students will create an animation where each letter of a word (ideally "ILMHUB") moves across the screen. This simple project will help students understand how to animate objects individually using the **`glide`** block and coordinate the movement of multiple sprites (letters) at once. Students will also learn how to break a word into individual letters, animate them one by one, and make the word appear as if it's moving.

## Key Concepts to Focus On

- **Glide Block**: Teach students how to use the `glide [x] secs to [x] [y]` block to smoothly move the letters across the screen.
- **Sprite Positioning**: Use the `go to x: [x] y: [y]` block to position letters at their starting points.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the purpose of the project: animating the word "ILMHUB" by moving each letter across the screen.
   - Introduce the **glide block** and explain how it moves the sprite smoothly to a new position over a specified amount of time.
   - Discuss how students will break the word into individual letters and animate them one by one.

2. **Step-by-Step Instructions**
   - **Step 1**: Create individual sprites for each letter of the word "ILMHUB".
     - You can create separate sprites for each letter or use the same sprite and clone it.
   - **Step 2**: Position each letter at its starting point.
     - Use the `go to x: [x] y: [y]` block to place each letter at a different position on the screen.
   - **Step 3**: Use the **`glide`** block to animate each letter.
     - For example: Use `glide 2 secs to x: [new x] y: [new y]` to move each letter to the next position smoothly.
   - **Step 4**: Use **broadcasting** to trigger the animation of the letters in sequence.
     - Each letter will glide to its new position, triggered by the broadcasted message.
   - **Step 5**: Add a small pause between each glide to create a sequential animation.
     - Use the `wait [time] seconds` block between the glides to control the timing of the letter movements.

3. **Teacher’s Tips**
   - Emphasize the use of **glide** to create smooth animations, and encourage students to experiment with different glide times to see how it affects the movement speed.
   - Ensure that students understand how to break down a word into individual letter sprites and use them to create a seamless animation.
   - Encourage creativity! Students can change the word to something else (their name, a favorite phrase, etc.) or add more effects like changing colors or sizes.

4. **Troubleshooting Common Issues**
   - **Issue**: Letters are not moving
