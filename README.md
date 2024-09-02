# 🎮 Doodle Jump Clone

*A clone of the popular mobile game "Doodle Jump" implemented using C++ and the SFML library.*

## 🚀 Features

- **Platforms**: Various types of platforms, including moving, disposable, and static.
- **Enemies**: Challenging enemies that the player must avoid or defeat.
- **Bonuses**: Collectible items that provide temporary boosts, such as invincibility or propeller-powered jumps.
- **Shooting**: The player can shoot bullets to defeat enemies.
- **Dynamic Camera**: The camera follows the character, creating a scrolling effect as the player ascends.
- **Score Tracking**: Keeps track of jumps, distances, and defeated enemies.

## 🛠️ Getting Started

### Prerequisites

- **SFML Library**: This game uses the SFML (Simple and Fast Multimedia Library). Make sure SFML is installed on your system, or include the required `.dll` files in the `libs` folder.

### Installation

1. **Clone the Repository**:
    ```sh
    git clone https://github.com/your-username/doodle-jump-clone.git
    ```
2. **Navigate to the Project Directory**:
    ```sh
    cd doodle-jump-clone/gamerp
    ```
3. **Open the Project in Visual Studio**:
    - Double-click the `gamerp.sln` file to open the solution in Visual Studio.

4. **Set Up Library Paths**:
    - In Visual Studio, go to **Project** > **Properties**.
    - Under **VC++ Directories**, update the `Include Directories` and `Library Directories` to point to the SFML files if necessary.
    - Under **Linker** > **General**, ensure the path to the `libs` directory is added to `Additional Library Directories`.
    - Under **Linker** > **Input**, make sure the SFML libraries (e.g., `sfml-graphics.lib`, `sfml-window.lib`, `sfml-system.lib`) are listed in `Additional Dependencies`.

5. **Build and Run**:
    - Build the solution by selecting **Build** > **Build Solution**.
    - Run the game by pressing `F5` or selecting **Debug** > **Start Without Debugging**.

### Running the Game

After building the game, you can run the executable located in the `x64/Debug` or `x64/Release` directory, depending on your build configuration.

### Controls

- **Arrow Keys**: Move the character left or right.
- **Mouse Click**: Shoot bullets towards the mouse pointer.
- **Spacebar**: Pause/Resume the game.

## 🌟 Future Improvements

- **Additional Power-ups**: Implement more power-ups to enhance gameplay variety.
- **Level Design**: Introduce different levels or game modes with varying difficulties.
- **Sound Effects and Music**: Add sound effects and background music to improve the gaming experience.

## 📄 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the classic "Doodle Jump" game.
- Special thanks to the SFML community for providing an excellent multimedia library.
