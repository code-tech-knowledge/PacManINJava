<p align="center">
  <img src="./pacman.svg" alt="Pac-Man" width="160"/>
</p>

# Pac-Man Java Game

A classic Pac-Man game implemented in Java using Swing. Control Pac-Man, eat all the food, and avoid the ghosts!

## Features
- Classic Pac-Man gameplay
- Multiple ghost types with unique colors and behaviors
- Score tracking and lives system
- Simple keyboard controls
- Retro-inspired graphics
- Customizable assets

## Gameplay Mechanics
Pac-Man navigates a maze, eating all the food pellets while avoiding ghosts. Eating a power pellet turns ghosts blue for a short time, allowing Pac-Man to eat them for extra points. The game ends when all lives are lost or the maze is cleared.

### Ghost Behaviors
- **Red Ghost (Blinky):** Aggressively chases Pac-Man.
- **Pink Ghost (Pinky):** Tries to ambush Pac-Man by predicting his path.
- **Blue Ghost (Inky):** Uses a combination of Pac-Man and Blinky's positions for unpredictable movement.
- **Orange Ghost (Clyde):** Alternates between chasing Pac-Man and wandering randomly.

Each ghost has a unique movement pattern, making the game challenging and engaging.

### Scoring System
- Small food pellet: 10 points
- Power pellet: 50 points
- Eating a ghost (after power pellet): 200, 400, 800, 1600 points (doubles with each consecutive ghost)
- Bonus fruit (cherry): 100 points

Your score and remaining lives are displayed at the top of the game window.

## How to Run
1. Ensure you have Java installed (JDK 8 or higher).
2. Compile the source code:
   ```
   javac -d bin src/PacMan.java src/App.java
   ```
3. Run the game:
   ```
   java -cp bin App
   ```

## Controls
- **Arrow Keys**: Move Pac-Man (Up, Down, Left, Right)
- **Close Window**: Exit the game

## Customizing Assets
All game graphics are included in the `src` and `bin` folders (PNG format). To customize:
1. Replace any PNG file (e.g., `pacmanUp.png`, `redGhost.png`) with your own image, keeping the same filename and dimensions.
2. Restart the game to see your changes.

## Troubleshooting
- **Game does not start:** Ensure Java is installed and the classpath is set correctly.
- **Graphics not displaying:** Check that all PNG files are present in the `src` and `bin` folders.
- **Controls not working:** Make sure the game window is focused when using the keyboard.

## Development & Contribution
Contributions are welcome! To get started:
- Fork the repository
- Make your changes in a new branch
- Submit a pull request with a clear description

### Code Structure
- `src/PacMan.java`: Main game logic and rendering
- `src/App.java`: Entry point for launching the game
- `src/*.png`: Game assets

Feel free to add new features, improve AI, or enhance graphics.

## Credits
- Developed by [Your Name]
- Inspired by the original Pac-Man arcade game

Enjoy playing Pac-Man!
