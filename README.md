

## Overview

Blackjack Game is a simple Python script that allows you to play the classic card game Blackjack against the computer in your terminal. The game follows standard Blackjack rules, including scoring, dealer behavior, and win/loss conditions.

## Features

- Play Blackjack against a computer dealer.
- Automatic card dealing and score calculation.
- Handles Blackjack and bust conditions.
- Dealer draws cards until reaching at least 17.
- User-friendly prompts for drawing or passing cards.
- Game can be replayed multiple times in a session.

## Requirements

- Python 3.x
- A `clear.py` file in the same directory to clear the terminal screen (optional, for better UX).

## How to Use

1. **Ensure all files are present:** Place `main.py` and `clear.py` in the same directory.
2. **Run the script:**
   ```bash
   python main.py
   ```
3. **Follow the prompts:**
   - Type `'y'` to draw another card.
   - Type `'n'` to pass and let the dealer play.
   - After each round, you can choose to play again.

## Example

```plaintext
your cards: [10, 7], current score: 17
computer's first card: 8
Type 'y' to get another card, type 'n' to pass: n
Your final hand is [10, 7], final score: 17
computer's final hand: [8, 9], final score: 17
Draw
Do you want to play a game of Blackjack? Type 'y' or 'n': y
```

## Notes

- An Ace is counted as 11 unless it would cause a bust, in which case it counts as 1.
- The dealer (computer) draws cards until their score is at least 17.
- The game automatically checks for Blackjack and busts after each action.
- The `clear()` function (from `clear.py`) is used to clear the terminal for a cleaner experience.

## License

This project is provided for educational purposes. Feel free to modify and use it as needed.

Citations:
[1] main.py https://ppl-ai-file-upload.s3.amazonaws.com/web/direct-files/attachments/67086525/de092a85-e6bf-41c0-9668-9bdd681a1c2f/main.py
.
