# So Long

## 🚀 Project Overview
So Long is a 2D game created using C and the MiniLibX library. The game challenges players to navigate through a labyrinthine map, collect valuable items, and make their way to the exit while dodging obstacles. Inspired by classic arcade-style gameplay, this project is a testament to a deep dive into game development fundamentals and essential C programming skills.

<video width="600" controls>
  <source src="./so_long.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>

[![Game Preview](https://github.com/AndrePortfolio/so_long/blob/main/so_long_img.png)](https://github.com/AndrePortfolio/your-repo/blob/main/so_long.mov)


## 🛠 Skills and Knowledge Gained
### Core Programming Skills
- **Mastering C Language**: Strengthened proficiency in writing clear, modular C code, emphasizing proper memory management, and debugging.
- **Error Handling**: Developed a keen understanding of handling errors gracefully, ensuring that the program exits cleanly with informative error messages.
- **Memory Management**: Used dynamic memory allocation to manage resources effectively and prevent memory leaks.

### Game Development Foundations
- **Graphics and UI Development**: Leveraged MiniLibX to create an interactive window, manage textures, and render game elements smoothly.
- **User Input Handling**: Implemented key event handling for character movement, including W, A, S, D keys, or alternative Z, Q, S, D keys.
- **Game Mechanics**: Built the logic for collecting items, tracking the number of movements, and determining win/lose conditions.
- **Collision Detection**: Designed algorithms to ensure the player avoids walls and interacts with collectibles and exits as intended.

### Algorithmic Problem Solving
- **Map Parsing and Validation**: Created algorithms to parse and validate a custom map format, ensuring all essential game rules are met (e.g., surrounded by walls, valid characters).
- **Pathfinding Fundamentals**: Developed basic algorithms to enable smooth movement and check for valid paths.
- **Move Counting**: Displayed the number of moves made by the player in the shell, showcasing an ability to handle real-time game metrics.

### Build and Deployment
- **Makefile Construction**: Wrote an automated Makefile to build and compile the project efficiently, ensuring reproducible builds.
- **Cross-Platform Compatibility**: Managed dependencies and external library integration to make sure the project runs on the designated development environment.

## 📜 Installation and Setup

### Prerequisites
Ensure you have the following installed:
- A C compiler like `gcc`
- The MiniLibX library (instructions provided by your school)
- `make` to build the project

## How to Use
   ```bash
   git clone https://github.com/AndrePortfolio/so_long.git
   cd so_long
   make bonus
   ./so_long_bonus maps/map4.ber
   ```
