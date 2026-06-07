# 🧑‍🚀 Day 1: The Lost Astronaut Maze
**Date:** June 17  
**Core Concepts:** X-Y Coordinates, Sequential Execution, Stage Boundaries, and Algorithms.

---

## 🎯 The Mission
Our astronaut is stranded on a distant coordinate grid grid in space! Students will program a spaceship or alien sprite to navigate a dangerous asteroid field using precise numerical coordinates. The goal is to reach the escape portal without hitting any space debris.

---

## 🛠️ Step-by-Step Code Instructions

### Step 1: Set Up the Cosmic Grid Workspace
1. Open your offline **Scratch Desktop App**.
2. Delete the default Scratch Cat sprite by clicking the trash can icon on its thumbnail.
3. Click the **Choose a Backdrop** button in the bottom right corner.
4. Scroll all the way to the bottom of the library and select **X-Y Grid**. 
5. Click **Choose a Sprite**, click **Upload Sprite**, and select your spaceship `.png` file from the USB drive assets.

### Step 2: Set the Initial Launchpad (The Input)
Computers read code from top to bottom. We must tell our sprite exactly where to start every single time the game resets.
1. Go to the yellow **Events** category and drag out the `when green flag clicked` block.
2. Go to the dark orange **Variables** category (or use Motion) to establish starting positions.
3. Go to the blue **Motion** category and snap a `go to x: [ ] y: [ ]` block directly underneath the flag.
4. Change the numbers to `x: -200` and `y: -120` to place your astronaut safely in the bottom-left corner of the stage grid.

### Step 3: Map the Flight Path (The Algorithm)
Now, write a sequential list of steps using coordinates to navigate past the center of the screen `(0,0)`.
1. Drag a blue `glide [1] secs to x: [ ] y: [ ]` block and snap it below your starting position. Set it to `x: -200` and `y: 100` to make the ship fly straight up.
2. Snap another `glide [1] secs to x: [ ] y: [ ]` block and change the coordinates to `x: 150` and `y: 100` to fly horizontally across the top of the grid.
3. Snap a final `glide` block setting it to `x: 150` and `y: -120` to land safely at the destination portal.

### Step 4: The Offline Save Routine
Before shutting down your laptop at the recreation center, back up your progress:
1. Click **File** in the top menu bar of the Scratch App.
2. Select **Save to your computer**.
3. Name your file `Day1_Astronaut_[YourName].sb3` and save it directly to your desktop or your personal folder.

---

## 🏠 Continuous Learning Home Challenge
Don't stop coding just because Wednesday is over! Complete these two "Level-Up" modifications at home before next week's class:

*   **Challenge 1 (The Teleport Patch):** Use a blue `go to x: [ ] y: [ ]` block instead of a glide block somewhere in your sequence. What happens to your character? Write down the difference between "gliding" and "going to" a coordinate.
*   **Challenge 2 (The Artist Backdrop):** Click on the **Stage** thumbnail on the right, click the **Backdrops Tab** at the top left, and use the paint brush tool to draw a customized neon space maze directly over the X-Y grid lines. Make sure your spaceship script still navigates perfectly through your drawn paths!

