# Dice Game in C#

## Description

This is a simple dice game implemented in C#. The game pits the player against an AI opponent. Each round, both the player and the AI roll a six-sided die. The higher roll wins the round, and the first to 10 rounds wins the game.

## How to Play

1.  The game prompts you to press any key to roll the dice.
2.  Press a key to roll. Your roll and the AI's roll will be displayed.
3.  The game determines the winner of the round and updates the score.
4.  This process repeats for 10 rounds.
5.  After 10 rounds, the game declares the overall winner based on the total score.

## Features

*   Simple and intuitive gameplay.
*   Random dice rolls for both the player and the AI.
*   Clear display of round results and overall score.
*   A one-second delay between the player's roll and the AI's roll to enhance the user experience.

## Technologies Used

*   C#
*   .NET 10

## How to Run

1.  Make sure you have the .NET 10 SDK installed.
2.  Save the `Program.cs` file.
3.  Open a terminal or command prompt.
4.  Navigate to the directory where you saved the file.
5.  Run the command `dotnet run`.

## Code Explanation

*   `Random random = new Random();`: Creates a new random number generator.
*   `random.Next(1, 7);`: Generates a random integer between 1 (inclusive) and 7 (exclusive), simulating a dice roll.
*   `System.Threading.Thread.Sleep(1000);`: Pauses the program for 1000 milliseconds (1 second).
*   The `for` loop iterates 10 times, representing the 10 rounds of the game.
*   `Console.WriteLine()` is used to display messages to the player in the console.
*   `Console.ReadKey()` waits for the player to press a key.

## Potential Improvements

*   Implement a graphical user interface (GUI) for a more visually appealing experience.
*   Allow the player to customize the number of rounds.
*   Add more sophisticated AI logic.
*   Implement error handling for invalid user input.
