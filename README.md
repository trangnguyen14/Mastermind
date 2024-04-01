# Mastermind
User Interface Design:
The user interface will be a program running on a server.
The user inputs their guess by choosing a sequence of colors.
For example, the user may input "R B Y P" for a guess.
The interface will provide feedback on the correctness of the guess by entering the number of pegs in the correct position and the number of pegs with correct colors but in the wrong position.
For example, if the user guesses "R B Y P" and 2 pegs are in the correct position and 1 peg has the correct color but in the wrong position, the interface outputs 2 red pegs and 1 white peg.
The game continues until the user guesses the correct code or until the maximum number of attempts is reached.
The result is displayed at the end of the game, indicating whether the user won, along with the secret code.

Features Supported
Number of Pegs:
  The game will support 4 pegs. 
Number of Colors:
  The game will support 6 colors 
Number of Users:
  The game will only support single player mode.
Computer Picks Colors:
  The computer will generate a random secret code based on the specified number of pegs and colors.
  The user will make guesses to try and deduce the secret code.
  The user will receive feedback after each guess, indicating the correctness of the guessed colors and positions.
