# Arena - The Battle Ground

## Object-Oriented Programming Concepts Implemented

1. **Classes and Objects**: The core building blocks of the project are defined as classes. Each class represents an entity with attributes and methods pertinent to that entity.
   - **Example**: `Character` class represents game players and has attributes like health, attack power, etc.

2. **Inheritance**: This project utilizes inheritance to create a hierarchy of classes that share common characteristics while allowing for specialized behavior.
   - **Example**: `Warrior` and `Mage` classes inherit from the `Character` class.

3. **Polymorphism**: Methods can be redefined in derived classes, allowing objects to be treated as instances of their parent class.
   - **Example**: The `attack()` method behaves differently for `Warrior` and `Mage` classes.

4. **Encapsulation**: All attributes of a class are kept private or protected, and public methods are provided to manipulate them.
   - **Example**: Health points are updated only through specific methods.

## Project Structure

```
Arena-the-battle-ground/
├── src/
│   ├── characters/
│   │   ├── Character.js
│   │   ├── Warrior.js
│   │   └── Mage.js
│   ├── game/
│   │   ├── Game.js
│   │   └── GameManager.js
│   └── utils/
│       ├── Helper.js
│       └── Constants.js
├── tests/
└── README.md
```

- **src/**: Contains the source code of the project.
- **characters/**: Directory for character-related classes.
- **game/**: Contains game logic and management.
- **utils/**: Utility functions and constants used throughout the project.

## How to Run the Project

1. **Clone the Repository**:  
   ```bash
   git clone https://github.com/vidyajain20/Arena-the-battle-ground.git
   cd Arena-the-battle-ground
   ```
2. **Install Dependencies**:  
   Make sure you have Node.js installed. Then run:  
   ```bash
   npm install
   ```
3. **Start the Game**:
   ```bash
   npm start
   ```

## Features

- **Multiplayer Support**: Fight against other players or AI characters.
- **Character Customization**: Choose between different classes and customize your character's abilities.
- **In-depth Combat System**: Each class has a unique combat style and special abilities.
- **Dynamic Game Environment**: The game features interactive environments that change based on player actions.
- **Leaderboard System**: Track player scores and compare them with others.

For more details, please refer to the documentation or explore the source code directly.
