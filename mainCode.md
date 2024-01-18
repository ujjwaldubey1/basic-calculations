


import java.util.Scanner;

public class Calculator {
    public static void main(String[] args) {
        // Create a Scanner object to read input from the user
        Scanner scanner = new Scanner(System.in);
        // Input the first number
        System.out.print("Enter the first number: ");
        double num1 = scanner.nextDouble();
        // Input the second number
        System.out.print("Enter the second number: ");
        double num2 = scanner.nextDouble();
        // Perform calculations
        double sum = num1 + num2;
        double difference = num1 - num2;
        double product = num1 * num2;
        double quotient = num1 / num2;
        // Display the results
        System.out.println("Sum: " + sum);
        System.out.println("Difference: " + difference);
        System.out.println("Product: " + product);
        System.out.println("Quotient: " + quotient);
        // Close the scanner to prevent resource leak
        scanner.close();
    }
}
