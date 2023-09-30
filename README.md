Here's a simple README file for the code:

# Guess The Number Game

This is a Java program that implements a "Guess The Number" game. In this game, the computer generates a random number between 1 and 50, and the player has to guess that number. The player is given 5 chances to make the correct guess.

## How to Play

1. The program generates a random number between 1 and 50.
2. The player is prompted to enter a number between 1 and 50.
3. The player has 5 chances to guess the correct number.
4. After each guess, the program provides feedback:
   - If the guess is correct, the player wins.
   - If the guess is too high, the program informs the player and allows them to guess again.
   - If the guess is too low, the program informs the player and allows them to guess again.
5. If the player runs out of chances (5 incorrect guesses), the game ends, and the program reveals the correct number.

## How to Run

1. Make sure you have Java installed on your computer.
2. Compile the Java file: `javac GuessTheNumber.java`
3. Run the program: `java GuessTheNumber`

## Example Gameplay

```
Welcome to Guess The Number!
Enter a number between 1 and 50:
25
Your guess is too low. Try again:
35
Your guess is too high. Try again:
30
Your guess is too low. Try again:
32
Your guess is too high. Try again:
31
You won!
```

```
Welcome to Guess The Number!
Enter a number between 1 and 50:
40
Your guess is too high. Try again:
30
Your guess is too low. Try again:
35
Your guess is too low. Try again:
37
Your guess is too low. Try again:
38
You ran out of chances. The number was 39
```

Enjoy playing the game!
