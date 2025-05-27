
Suggor - 2D Platform Game
Introduction
Suggor is a 2D platformer game created as part of an engineering team project during studies. The game follows the journey of the protagonist who navigates through various levels. The game offers classic platformer mechanics, with additional features such as lives, checkpoints.

Key Features
Lives System
Lives: The player starts the game with a certain number of lives. Each death results in the loss of one life.
Losing a life: The player loses a life if they fall into a pit, hit a trap, or are defeated by an enemy.
Life loss response: After losing a life, the player returns to the last activated checkpoint.
Lives Remaining: The number of remaining lives is displayed on the screen, allowing the player to monitor their resources.
Checkpoints
Checkpoint System: The game features a checkpoint system that saves the player's progress at various points throughout the level.
Activating Checkpoints: The player activates a checkpoint by reaching certain areas on the level (e.g., touching a flag or entering a special zone).
Returning to Checkpoints: After losing a life, the player is respawned at the last activated checkpoint, preserving collected points and items.
Levels and Progression
Multi-level Structure: The game consists of multiple levels.
Endgame: After completing all levels, the player faces the final challenge – a powerful boss.
Game Screenshots and Demo
Game Screenshot 1
Game Screenshot 2
Demo
Suggor Game Demo on YouTube
Technologies Used in the Project
Unity Engine – The main game engine used to develop the project.
C# – The programming language used for scripting and game logic.
Unity Packages:
2D Animation – For creating animations in a 2D environment.
TextMeshPro – For advanced text rendering and customization.
Cinemachine – For dynamic camera controls and smooth transitions.
Physics and Physics2D – For handling in-game physics and collision detection.
Tilemap – For creating and managing 2D grid-based levels.
Installation Instructions:
Download Unity Hub and Unity 2020.3.25

Unity Hub
Unity 2020.3.25
Open Unity Hub

Add the project folder to Unity Hub as a project from disk.
Click on the added project in Unity Hub to resolve all required packages and files.
Refresh Assets

In Unity Editor, right-click on the Assets folder in the Project window and select Refresh and Reimport All.
This ensures all project files and dependencies are up-to-date.
Open C# Project

After refreshing, go to the top menu bar in Unity, select Assets > Open C# Project.
This will open the scripts in your IDE (e.g., Visual Studio), ensuring all script files are correctly synchronized.
After completing these steps, the project should be running successfully in your local environment.
