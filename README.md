# Magical Arena: 

This is a simple Java implementation of the Magical Arena game.

## Introduction

The Magical Arena is a turn-based battle game where two players engage in combat until one of them loses all their health points.
This program simulates a magical arena where two players can fight each other. Each player is defined by their health, strength, and attack attributes, all of which are positive integers. The game continues until one player's health reaches 0.

## Features

- Players have attributes such as health, strength, and attack.
- Players take turns attacking and defending using dice rolls.
- Damage calculation is based on attack and defense rolls.
- The game ends when one player's health reaches 0.

## Requirements
- Java Development Kit (JDK)
- Eclipse IDE
- JUnit 4

## Project Structure
- src/main/java (Main.java): Contains the main source code files.
- src/test/java (PlayerTest.java and MagicalArenaTest.java: Contains the test source code files.
- pom.xml: Maven project configuration file.

## How to Build and Run

=>To import the project into Eclipse:
 - Open Eclipse IDE.
 - Select "File" -> "Import" -> "Existing Maven Projects".
 - Browse to the project directory and select it.
 - Click "Finish".

## How to Run:


To run the game, follow these steps:

Run the 'Main.java'(src/main/java) file as a Java application to start the game.

Run the program using `java Main`, Right click on Main.java class => Run as => select Java Application


## How to Play or Rules of the Game:

- Two players are created with initial attributes (health, strength, and attack).
- Players take turns attacking and defending.
- Each player rolls a 6-sided die for attack and defense.
- Players attack in turns.
- Attacking player rolls an attacking dice, and the defending player rolls a defending dice.
- The attack value multiplied by the outcome of the attacking dice roll is the damage created by the attacker.
- The defender's strength value, multiplied by the outcome of the defending dice, is the damage defended by the defender.
- Excess damage reduces the defender's health.
- The player with lower health attacks first at the start of a match.
- Damage is calculated based on the dice rolls and player attributes.
- The game continues until one player's health reaches 0.

## Design :

The program consists of two classes: `Player` and `MagicalArena`.

- `Player`: Represents a player in the game, with methods to handle attacks, defense, and health reduction.
- `MagicalArena`: Manages the fight between two players, determining the attacker and defender for each round until one player wins.


## Unit Tests :
- Unit tests are provided to ensure the correctness of the code. JUnit 4 and Hamcrest libraries are used for testing.

##Steps to do Unit Testing:
- Right click on Testing class Name => Run as => select Junit Test Case =>It will show Unit Test cases

## Evaluation

- The code has a clear and simple design, with well-named methods and variables.
- The code is easy to read and understand, with consistent naming conventions.
- The objects and classes used in the code are appropriate for the problem.
- The code is maintainable and modifiable, with no apparent technical debt.
- Comprehensive unit tests are provided, ensuring a high degree of test coverage.
