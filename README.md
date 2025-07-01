# Slot-Machine

# 🎰 Slot Machine Game (Python CLI)

A simple command-line slot machine game written in Python. This interactive project lets users deposit money, place bets on multiple lines, and spin the slot machine to win based on symbol alignment.

## 📋 Features

- Deposit money and manage your balance.
- Bet on 1 to 3 lines at once.
- Symbols `A`, `B`, `C`, and `D` with varying frequencies and payouts.
- Random slot machine spins using Python’s `random` module.
- Automatically checks for winning lines and calculates payouts.

## 🧠 Game Rules

- **Slot Machine Layout:** 3x3 grid (3 rows and 3 columns).
- **Symbols:**
  - `A` – Rare (2 instances), High reward (5x)
  - `B` – Uncommon (4 instances), Reward (4x)
  - `C` – Common (6 instances), Moderate reward (3x)
  - `D` – Very common (8 instances), Low reward (2x)
- A win occurs when the same symbol appears across a horizontal line.
- Bet amount is multiplied by symbol's value when winning.

How to Run

- Clone the repository :

   git clone https://github.com/yourusername/slot-machine-game.git
   cd slot-machine-game

Run the game :

- Make sure you have Python 3 installed.

python slot_machine.py

📝 Code Structure
- main() – Entry point of the game.

- deposit() – Handle user deposit.

- get_number_of_lines() – Ask how many lines the user wants to bet on.

- get_bet() – Take a bet amount from the user.

- get_slot_machine_spin() – Simulate a random spin of the slot machine.

- check_winnings() – Evaluate the spin and calculate the win.

- print_slot_machine() – Display the slot machine in a 3x3 format.

- spin() – Coordinates a single round of play.

✅ Example Gameplay

What would you like to deposit? $100
Enter the number of lines to bet on (1-3)? 2
What would you like to bet on each line? $10
You are betting $10 on 2 lines. Total bet is equal to: $20
A | B | A
B | B | D
D | D | C
You won $10.
You won on lines: 2
Current balance is $90

📌 Requirements
- Python 3.x

- No external dependencies

Screenshots

![1](https://github.com/user-attachments/assets/4cb3e299-2d08-4e80-955f-cb201e4d8a84)


🛠️ Customization Ideas
- Add more symbols or larger grid sizes.

- Introduce vertical or diagonal win lines.

- Include a graphical interface with libraries like tkinter or pygame.

📄 License

This project is licensed under the MIT License.

👨‍💻 Author

Abhinav Dixit
