🎮 lifewood-2d-minigame

![Image](https://github.com/user-attachments/assets/524d72f0-2932-4e3d-ae63-4c300c10470c)

lifewood-2d-minigame is a polished, modern 2D Snake game generated entirely by Gemini AI in a single HTML file based on a one-shot prompt I personally crafted using prompt engineering.

By crafting a detailed and structured prompt, I guided the AI to build everything: gameplay mechanics, responsive UI with glowing visuals, and local storage features, all bundled into one lightweight file.

Prompt engineering is a key skill that unlocks the power of AI tools for rapid, high-quality project development with minimal effort.


▶️ How to Run

    •Download or clone the repository.
    •Open the file lifewood-2d-minigame.html in any modern web browser.
    •Play instantly — no installation or server needed!

✅ No dependencies, no setup — just one file and it's ready to go!


My Prompt:

🎮 ROLE

You are a Senior Game Developer building SNAKE, a 2D arcade-style game in a single HTML file. The player guides a snake on a grid to eat foods, grow longer, and avoid self-collision. The design should feel modern, smooth, and visually engaging—optimized through working CDN libraries for layout and gradients.

---

✅ TASK (short and high-level)

• Build classic Snake gameplay: movement, food collection, growth, and self-collision detection.

• Use local storage for score tracking.

• Implement UI using a centered card layout and Bootstrap (CDN).

• Include subtle glowing gradients using CDN assets only.

• Everything must exist in a single HTML file, HTML, CSS, and JS bundled.

---

🔍 SPECIFICS (detailed game features)

Gameplay

• Snake moves on a grid.

• Select difficulty first before starting the game.

• Add difficulty by speeding up the snake movement (Easy (Default), Medium, Hard). Difficulty can’t be changed if game starts already.

• Eats food to grow.

• Wrap-around mechanic: snake reappears on the opposite side of the screen.

• Snake dies if it collides with itself.

• Automatically pauses the game when controls guide button is clicked.

• Allows difficulty selection when restarting the game.

• Food count is saved in local storage as high score (Default High Score: 0).

Controls

• Arrow keys or WASD for movement.

• S for start button.

• R for restart button.

• C for controls button.

• SPACE to pause/resume.

• ENTER or SPACE close modals.

UI & Layout

• Canvas, score, and buttons inside a centered Bootstrap card.

• Use glowing gradient effects for:

 – Snake body
 
 – Food
 
 – Grid background
 
 – Buttons and cards
 
• Game Over modal: shows final score and a “Play Again” button.

• Pause modal: shows control guide.

Visual

• Subtle lighting gradients for depth and visual appeal.

• Smooth animations, full responsiveness across devices.

• Ensure the text colors are clear based on the color used for the UI.

---

📝 CONTEXT

• The game must feel polished, modern, and lightweight.

• All assets and logic should be CDN-delivered and bundled into one file.

• Use concise comments to explain functionality in the code.

• Maintain consistent styling, performance, and layout across screen sizes.
