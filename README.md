# Number Guessing Game

The Number Guessing Game is a simple Java console-based game where the player tries to guess a randomly generated number within a given range. The game provides features such as limiting the number of attempts, adding more rounds, displaying the score, and giving points based on the number of attempts.

## Features

1. **Limiting the number of attempts:** The player has a maximum number of attempts to guess the correct number. If the maximum attempts are reached without a successful guess, the game ends.

2. **Adding more rounds:** After a successful guess or when the maximum attempts are reached, the player is given the option to play again. Starting a new round generates a new random number and resets the attempt counter.

3. **Displaying score:** The player's score is displayed at the end of each round. The score is calculated based on the number of attempts made in each round.

4. **Giving points based on the number of attempts:** The player earns points based on the number of attempts made. The fewer attempts used to guess the number, the more points are earned.

## Usage

1. Make sure you have Java installed on your system.

2. Download the `NUMBER_GUESSING_GAME.java` file.

3. Open a command prompt or terminal and navigate to the directory where the file is located.

4. Compile the Java file using the following command:
   ```
   javac NUMBER_GUESSING_GAME.java
   ```

5. Run the compiled Java program using the following command:
   ```
   java NUMBER_GUESSING_GAME
   ```

6. Follow the instructions displayed in the console to play the game.

7. Enter your guess for the randomly generated number within the specified range.

8. You will be notified if your guess is too low or too high.

9. Keep guessing until you either guess the correct number or reach the maximum number of attempts.

10. At the end of each round, your score will be displayed based on the number of attempts made.

11. Choose whether you want to play another round or exit the game when prompted.

## Customization

You can customize the game by modifying the following variables in the code:

- `range`: Sets the range of numbers for the game. By default, it is set to 100.
- `maxAttempts`: Sets the maximum number of attempts allowed for each round. By default, it is set to 10.

Feel free to adjust these variables to suit your preferences.

## Example

Here's an example of how the game may look when played:

```
Welcome to the Number Guessing Game!

Guess the number between 1 and 100.
You have 10 attempts.
Enter your guess: 50
Your guess is too low. Try again.
Enter your guess: 75
Your guess is too high. Try again.
Enter your guess: 63
Congratulations! You guessed the number in 3 attempts.
Your current score is: 7
Do you want to play again? (yes/no): yes

Guess the number between 1 and 100.
You have 10 attempts.
Enter your guess: 80
Your guess is too high. Try again.
Enter your guess: 60
Your guess is too low. Try again.
Enter your guess: 70
Congratulations! You guessed the number in 3 attempts.
Your current score is: 14
Do you want to play again? (yes/no): no

Thank you for playing the Number Guessing Game!
```

That's it! Enjoy playing the Number Guessing Game and have fun guessing the numbers!
