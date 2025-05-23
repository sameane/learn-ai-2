# 4D Snake Game

## Concept

This project is an exploration of a classic Snake game implemented in four dimensions (4D).
In a traditional 2D snake game, the snake moves on a plane (X, Y axes). In a 3D snake game, it moves in a volume (X, Y, Z axes).
In this 4D version, the snake navigates a 4-dimensional space, notionally represented by X, Y, Z, and W axes.

The challenge lies in representing and interacting with 4D space on a 2D screen, as well as defining intuitive controls for navigation across four dimensions.

## Goal: Desktop and Mobile Playability

The primary goal is to make this game playable on both desktop and mobile devices. To achieve this broad compatibility, the game is being developed using web technologies:
- **HTML5:** For the basic structure and game canvas.
- **JavaScript:** For all game logic, including 4D mechanics, rendering (projection), and input handling.
- **CSS:** (Potentially) for styling the game page.

This web-based approach allows the game to run in any modern web browser, regardless of the underlying operating system.

## File Structure

- **`index.html`**: The main HTML file that serves as the entry point for the game. It sets up the game canvas and includes the necessary JavaScript files.
- **`game.js`**: Contains the core JavaScript code for the 4D snake game. This includes:
    - Logic for representing 4D coordinates.
    - Snake movement and growth mechanics in 4D.
    - Food placement and collision detection in 4D.
    - Input handling for 4D navigation.
    - The main game loop.
    - Functions for projecting the 4D game state onto the 2D canvas for display.
- **`style.css`**: (Placeholder in `index.html`, not yet created) Will be used for any custom styling of the game's web page.

## Current Status

The project is in its initial setup phase. The basic file structure and placeholder code for the game logic are being established. The core challenges of 4D visualization and control are yet to be implemented.
