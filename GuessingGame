import java.util.Scanner;

public class GuessingGame {

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        // Generate a random number between 1 and 100 (inclusive)
        int randomNumber = (int) (Math.random() * 100) + 1;

        int guessCount = 0;
        int userGuess;

        do {
            guessCount++;

            System.out.print("Enter your guess (1-100): ");
            userGuess = scanner.nextInt();

            if (userGuess < randomNumber) {
                System.out.println("Too low. Try again.");
            } else if (userGuess > randomNumber) {
                System.out.println("Too high. Try again.");
            } else {
                System.out.println("Congratulations! You guessed the number in " + guessCount + " tries.");
            }

        } while (userGuess != randomNumber);
    }
}
