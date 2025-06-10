# 🃏 Blackjack Game in Python

A command-line implementation of the classic Blackjack (21) card game using Python. Designed for a single player vs dealer (computer).

## 📌 Features

- Play against a computer dealer
- Simulates real Blackjack rules:
  - Hit, Stand
  - Face cards are worth 10, Ace can be 1 or 11
- Shuffled deck
- Simple CLI interface

## 🚀 Prerequisites

- Python 3.x

## 🎮 How to Play

- Start the game by running the script.
- You will be dealt two cards, and the dealer will have one card face-up.
- Your choices:
  - `hit`: Draw another card  
  - `stand`: End your turn
- Dealer will draw cards until they either bust or reach 21.
- Closest to 21 without going over wins.

## 🧠 Game Logic

- Deck is a list of card tuples.
- Cards: 2–10, Jack, Queen, King, Ace
- Ace is handled as 11 unless it would cause a bust (then 1).
- Checks for:
  - Blackjack
  - Player or dealer bust
  - Draw / tie conditions
