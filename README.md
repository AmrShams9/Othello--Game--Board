🎲 AI-Othello-Board-Game 🎲
Welcome to Smart Othello
Dive into the timeless challenge of Othello with this Python implementation featuring a robust AI opponent driven by the powerful minimax algorithm with alpha-beta pruning. Challenge your friends in classic head-to-head matches with our human vs. human mode.

📜 About Othello
Othello is a strategic board game designed for two players, played on an 8x8 grid. Each player controls pieces, known as disks, which are identical and have one white side and one black side. Players select their color at the beginning of the game and take turns placing their disks on empty squares of the board. Upon placing a disk, any of the opponent's disks that are sandwiched between the newly placed disk and another disk of the current player's color are flipped to the current player's color. The game continues until there are no valid moves left for both. The player with the most disks of their color facing up at the end of the game is declared the winner.

🛠️ Game Setup
At the beginning of the game, the board is arranged by positioning 2 black disks and 2 white disks at the center, with each color placed diagonally from the other. This setup is consistent at the start of every game.
Subsequently, the remaining 60 disks are distributed evenly between the two players, ensuring each player possesses 30 disks.
🌟 Features
Flexible Interface: Smart Othello can be played in both GUI and console interfaces, providing flexibility for your preferred gaming experience.
Game Modes: Enjoy various game modes to suit your preferences, including Human vs. AI with adjustable AI difficulty settings, or Human vs. Human matches.
🎮 How to Play
During a player's turn, they must identify an empty square adjacent to one of the opponent's pieces. The player then places their disk in that square, with their color facing upwards.
If the newly placed disk creates a contiguous horizontal row or vertical column of the opponent's pieces between two disks of the player's color, it forms a legal move called outflanking.
After outflanking the opponent's disks, they are flipped to the player's color, effectively capturing them. These flipped disks now belong to the player, regardless of who originally placed them on the board.
Subsequently, the player passes the turn to their opponent to continue the game.
When neither player can make any more moves, the game ends. The number of disks belonging to each player is counted, and the player with the majority of their color showing on the board is declared the winner.
📏 Game Rules
A player with black disks always makes the first move.
If a player cannot flip at least one opposing disk by outflanking, they skip their turn, and their opponent moves next.
A disk can outflank any number of opponent's disks in one or more rows, either horizontally or vertically, simultaneously.
Players cannot jump over their color disks to outflank an opponent's disk.
Disks can only be outflanked as a direct consequence of a move and must align directly with the newly placed disk.
The game ends if a player runs out of all of their disks or if both of the players can't make any valid moves on the board.
Enjoy strategic gameplay and challenge your skills with Smart Othello! ♟️
