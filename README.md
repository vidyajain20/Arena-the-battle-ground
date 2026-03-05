# OOP Concepts in Arena-the-battle-ground

## Enemy.py
- **Class Inheritance**: The `Enemy` class inherits from a base class. This allows for code reusability and a hierarchical structure within the game.
- **Encapsulation**: Attributes of the enemy are kept private, modifying them through public methods to maintain control over their values.
- **Polymorphism**: Different types of enemies may override methods, providing specific functionality, while maintaining a common interface.

## Hero.py
- **Abstraction**: The `Hero` class abstracts details of hero functionalities by providing a clean interface to interact with skills and abilities.
- **Encapsulation**: Hero attributes such as health and armor are protected, ensuring they can only be modified through predefined methods.
- **Inheritance**: Specific hero types may extend the base hero class, adding unique abilities or properties.

## Zombie.py and Ogre.py
- **Class Inheritance**: These classes inherit from `Enemy`, allowing them to share common methods while introducing unique attributes or behaviors.
- **Polymorphism**: Each enemy type implements its attack methods that might differ in logic or outcome.

## Weapon.py
- **Encapsulation**: The weapon’s damage and type are encapsulated, and unique methods manage their state.
- **Abstraction**: Abstracts the notion of different weapon types, providing clear cut usage references while hiding implementation details.

## Main.py
- **Composition**: The game uses composition to create complex objects like the hero or enemy instances using smaller building blocks (weapons, abilities).
- **Polymorphism**: Various methods can handle different objects (e.g., weapon types) interchangeably as long as they share a base interface.

This documentation summarizes the key OOP principles applied in the related modules of the Arena-the-battle-ground project.