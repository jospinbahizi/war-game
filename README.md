# War Card Game
This Python script simulates the card game "War" between a player and the computer. The game is played with a standard deck of 52 cards, which are divided equally between the player and the computer. The objective is to win all the cards.

# Table of Contents

- [War Card Game](#war-card-game)
- [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Features](#features)
  - [How to Use](#how-to-use)
    - [To run the game](#to-run-the-game)
    - [Game Rules](#game-rules)

## Introduction
This code creates a simple implementation of the card game "War" using Python. It includes classes for a deck of cards, player's hand, and the game logic to simulate rounds between the player and the computer.

## Features
Creates a deck of 52 cards and shuffles it.
Splits the deck between the player and the computer.
Simulates rounds of the "War" card game.
Handles wars (when cards have the same rank).
Tracks the number of rounds played and the occurrences of wars.

## How to Use

### To run the game
Execute the Python script in your preferred Python environment.
Follow the prompts on the console.
Enter your name when prompted.
Play the game against the computer by following the instructions provided.

### Game Rules
Each player draws a card in each round.
The player with the higher card rank wins both cards and adds them to their pile.
In the case of a tie (same rank), a "war" occurs:
Three additional cards are drawn by each player.
The player with the higher fourth card wins all cards on the table.
The game continues until one player runs out of cards.

Enjoy playing the "War" card game!