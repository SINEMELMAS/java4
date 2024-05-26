# java4
package lab1;
import java.util.Scanner;
public class Q4 {
	
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);

        System.out.print("Please enter an integer: ");
        int number = scanner.nextInt();

        if (number % 3 == 0) {
            System.out.println(number + " is divisible by 3.");
        } else {
            System.out.println(number + " is not divisible by 3.");
        }

        scanner.close();
    }
}
