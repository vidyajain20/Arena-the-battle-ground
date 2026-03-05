# Arena The Battle Ground

## Introduction
Welcome to Arena The Battle Ground! This project is a simple interactive game designed to demonstrate key programming concepts through object-oriented programming (OOP). In this README, we will showcase the four pillars of OOP: Abstraction, Polymorphism, Encapsulation, and Inheritance.

## OOP Pillars

### 1. Abstraction
Abstraction is the concept of hiding the complex reality while exposing only the necessary parts. In our game, we abstract various elements such as characters, weapons, and arenas to simplify interactions.

#### Code Example:
```java
abstract class Character {
    String name;
    abstract void attack();
}

class Warrior extends Character {
    void attack() {
        System.out.println(name + " attacks with a sword!");
    }
}
```

### 2. Polymorphism
Polymorphism allows for methods to do different things based on the object it is acting upon. This is utilized in our game for different character types that behave uniquely under the same action.

#### Code Example:
```java
Character warrior = new Warrior();
Character mage = new Mage();

warrior.attack(); // Output: Warrior attacks with a sword!
mage.attack();    // Output: Mage casts a fireball!
```

### 3. Encapsulation
Encapsulation involves bundling the data with the methods that operate on that data. Our game encapsulates player statistics and behaviors using classes.

#### Code Example:
```java
class Player {
    private int health;
    private int score;

    public void setHealth(int health) {
        this.health = health;
    }

    public int getHealth() {
        return health;
    }
}
```

### 4. Inheritance
Inheritance is the mechanism of creating new classes based on existing ones. In our game, various types of characters inherit from a base character class.

#### Code Example:
```java
class Mage extends Character {
    void attack() {
        System.out.println(name + " casts a spell!");
    }
}

class Archer extends Character {
    void attack() {
        System.out.println(name + " shoots an arrow!");
    }
}
```

## Project Architecture
The project is organized into several packages, each handling a different aspect of the game:
- **models**: Contains classes defining game entities such as characters and items.
- **services**: Logic for game mechanics, such as combat and inventory management.
- **ui**: User interface components.

## How to Run the Game
1. Clone the repository:
   ```bash
   git clone https://github.com/vidyajain20/Arena-the-battle-ground.git
   cd Arena-the-battle-ground
   ```
2. Compile the code:
   ```bash
   javac src/**/*.java -d out/
   ```
3. Execute the main class:
   ```bash
   java -cp out/ MainClassName
   ```

## Features
- **Multiple Character Classes**: Choose between several character types, each with unique abilities.
- **Combat Mechanics**: Engaging battles with dynamic attack options.
- **Leaderboard**: Keep track of player scores and achievements.
- **User-Friendly Interface**: Simple navigation and game controls.

## Conclusion
This README serves as a comprehensive overview of the Arena The Battle Ground project. It highlights the four pillars of OOP with code examples directly from the codebase, project architecture, and instructions on how to run the game. By showcasing these features, we hope to impress potential recruiters with both technical knowledge and practical implementation!