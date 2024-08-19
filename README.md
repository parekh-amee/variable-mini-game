# Color Guessing Game 🎨

This project is a simple **Color Guessing Game** that demonstrates the basic use of variables in JavaScript: `let`, `const`, and `var`. The game is ideal for beginners who want to learn how to use and scope variables effectively.

## Purpose

The purpose of this project is to help you understand:

- When to use `const`, `let`, or `var`
- How variable scoping works in JavaScript
- The difference between constant values and variables that change during the game

## How to Play

1. A random color is selected from a list of colors: `red`, `blue`, `green`, `yellow`, `orange`, `purple`, `pink`, or `brown`.
2. The player enters a color guess in the input field.
3. The game checks if the guess matches the secret color and displays feedback.
4. A new game can be started by clicking "New Game," which resets the game state.

## Key Concepts Explained

### `const`
- **Usage**: Used for values that should **not change** after initialization.
- **Example in Game**: The `colors` array is defined using `const` because the list of possible colors remains constant throughout the game.
  
### `let`
- **Usage**: Used for variables whose values **can change** over time within a certain scope.
- **Example in Game**: The `secretColor` variable is declared with `let` because it needs to be reassigned a new value every time a new game starts.
  
### `var`
- **Why Not Used**: We avoid `var` because it has function-scoped behavior, which can lead to unexpected issues. Instead, `let` and `const` are preferred for better block-scoping and predictability.

## Project Structure

index.html  # Contains HTML structure and inline JavaScript
The entire game logic is embedded in the HTML file, making it easy for beginners to follow along.

Getting Started
Simply open the index.html file in a browser to play the game. No installations or setups are required.

Learning Objectives
By studying this simple project, you'll learn:

The difference between constant and mutable data in JavaScript
How to manage game state using let and const
Why let is better suited for reassignable values than var
This is a great introduction to JavaScript variables and their scope in a real-world application.
