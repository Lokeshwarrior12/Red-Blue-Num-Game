🔴🔵 Red-Blue Nim Game
Author: Lokeshwar Kodipunjula
Student ID: 1002175121

🧠 Overview
This project implements a command-line version of the Red-Blue Nim game in Java—a strategic two-pile marble game inspired by the classic game of Nim. Players alternate turns removing marbles from red and blue piles, with gameplay variations based on standard and misère rules:

Standard Version: The player who removes the last marble loses.

Misère Version: The player who removes the last marble wins.

🎮 Features
Simple command-line interface for interactive gameplay.

Support for standard and misère versions.

Option to choose the starting player: human or computer.

Adjustable search depth for computer AI using game tree evaluation.

⚙️ Command-Line Arguments
Run the program with the following arguments:
java RedBlueNim <red-marbles> <blue-marbles> [version] [first-player] [search-depth]

Arguments:
<red-marbles>: (int) Initial number of red marbles.

<blue-marbles>: (int) Initial number of blue marbles.

[version]: (Optional) Game mode: standard (default) or misere.

[first-player]: (Optional) Who plays first: computer (default) or human.

[search-depth]: (Optional) Depth of the computer’s move search. Default is 1.

🛠️ How to Compile and Run
✅ Requirements:
Java Development Kit (JDK) must be installed.

Download from Oracle or use OpenJDK.

📦 Compilation:
javac RedBlueNim.java

This will generate RedBlueNim.class.

▶️ Execution:
Run the game with your chosen arguments:
java RedBlueNim 5 7 standard computer 10

📝 Example:
javac RedBlueNim.java


java RedBlueNim 3 4 misere human 2
This command starts the game with:

3 red marbles

4 blue marbles

Misère version

Human goes first

Search depth of 2 for the computer
