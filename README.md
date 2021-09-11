# mastermind
The classic game of Mastermind is played on a tray on which the Mastermind conceals a code and the Guesser has 10 tries to guess it. 
The code is a sequence of 4 (or 6, sometimes more) pegs of different colors. 
Each guess is a corresponding sequence of 4 (or more) pegs of different colors. 
A guess is "correct" when the color of every peg in the guess exactly matches the corresponding peg in the Mastermind's code.
After each guess by the Guesser, the Mastermind will give a score comprising black & white pegs, not arranged in any order:
- Black peg == guess peg matches the color of a code peg in the same position. ",
- White peg == guess peg matches the color of a code peg in another position. ",

# Code
This code creates a function mastermind() that will execute the game of Mastermind
