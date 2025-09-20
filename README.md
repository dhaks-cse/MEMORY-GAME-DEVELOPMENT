Memory Game (with Leaderboard & Database Integration)

This is a two-player memory card-matching game built using Python (Tkinter) for the graphical interface and MySQL for storing game history and leaderboard tracking.

Gameplay:
Players take turns flipping two cards on a 4×4 grid. If the cards match, the player scores a point and gets another chance. If not, the turn passes to the other player. The game ends when all pairs are matched.

Player Input:
Both players enter their names before the game begins. The system validates inputs to ensure names are not empty and only contain letters.

Database Integration:
A MySQL database (card_game) stores player details, match outcomes, and winners. After every game, the winner (or draw) is recorded automatically.

Leaderboard:
After finishing a game, players can view the Leaderboard, which shows winners and their total number of wins across all sessions, sorted by ranking.

Interface:
The game uses card images with a hidden “back” side. Clicking a card flips it to reveal its face. The GUI includes a score tracker, turn indicator, and a post-game screen with options to view the leaderboard or exit.

Special Feature:
A “cheat code” (printed in the console) reveals the hidden card arrangement for debugging or testing.

IT IS A TEAM PROJECT.
