# Project : Paint 🎨

## Project Overview

In this project, students will create a simple drawing application that simulates a paint program, similar to the classic Paint app in Windows. The project introduces the use of the **Pen extension** in Scratch, which allows students to draw on the screen with their sprite, creating an interactive and creative experience. This is one of the first projects where students will actively use Scratch's extensions to expand the capabilities of their projects.

## Key Concepts to Focus On

- **Pen Extension**: Teach students how to use the Pen extension to draw on the screen. This involves using blocks like `pen down`, `pen up`, and `set pen color`.
- **Mouse Input**: Use the `mouse x` and `mouse y` blocks to track the position of the mouse and draw at that location.
- **Variables**: Students can create variables to keep track of pen color or line thickness.
- **Conditional Statements**: Use `if` blocks to switch between drawing and erasing.

## Detailed Plan

1. **Introduction (10-15 minutes)**
   - Explain the goal of the project: to create a simple drawing app.
   - Introduce the **Pen extension** and explain how it allows sprites to draw on the screen.
   - Discuss the basic layout and controls of a paint program (e.g., choosing colors, drawing, erasing).

2. **Step-by-Step Instructions**
   - Step 1: Add the **Pen extension** to the Scratch project.
     - Show students how to find the **Pen** category in the Scratch blocks palette and drag the required blocks into the code area.
   - Step 2: Set up the pen to draw.
     - Use the `when green flag clicked` block to start the project.
     - Add `clear` to reset the screen.
     - Use `pen down` to start drawing and `pen up` to stop.
   - Step 3: Draw with the mouse.
     - Use the `go to [mouse pointer]` block to move the sprite to the mouse’s current position and `pen down` to draw as the sprite moves.
   - Step 4: Create a simple button to change the pen color.
     - Use a `when this sprite clicked` block to change the pen’s color.
   - Step 5: Add an eraser feature.
     - Create a new sprite for the eraser and use `pen up` to stop drawing when the eraser is selected.

3. **Teacher’s Tips**
   - **Pen Extension**: Emphasize how to use the Pen extension properly, especially how the pen must be “down” to draw and “up” to stop.
   - **Mouse Interaction**: Make sure students understand how the mouse’s position is tracked and how it’s used to control the sprite’s movements.
   - **Color Change**: Allow students to explore different colors and experiment with making their paint program more dynamic.
   - Encourage students to personalize their projects by adding extra features, such as a **clear screen** button or different brush sizes.

4. **Troubleshooting Common Issues**
   - Issue: The drawing is not smooth.
     - Solution: Ensure that the sprite is constantly moving to the mouse position. You might need to use `go to [mouse pointer]` more frequently.
   - Issue: The pen won’t start drawing.
     - Solution: Check if `pen down` is in the right place, and ensure it is triggered when the green flag is clicked.
   - Issue: The drawing doesn’t reset when the green flag is clicked.
     - Solution: Add the `clear` block at the start of the script to clear the screen every time the project starts.

5. **Extension Ideas**
   - Create buttons to switch between different **pen colors** or change **pen sizes** using variables.
   - Add a **clear button** to reset the drawing.
   - Allow the student to add a **save option** (to save the current drawing) or even simulate drawing different shapes like circles and squares.
   - Challenge students to design a **mini game** where they draw specific objects based on prompts.

## Conclusion

By the end of this project, students will have created a fully functional drawing app that simulates the basic features of a paint program. They will also gain experience with the **Pen extension**, mouse control, and event handling. This project serves as a great introduction to more interactive Scratch projects and builds confidence in using extensions and more advanced Scratch features.

---

### **Note**: This project will allow students to gain creative experience with Scratch and understand the importance of extensions in adding new features to their projects.
