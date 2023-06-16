# mutiples
quiz
/*
 * a Java program that displays multiples of 2, 3, and 7 within the range of 71 and 150:
 */
import java.util.Scanner;
public class Mutiples {

	public class DivisibilityTest {
	    public static void main(String[] args) {
	        try (Scanner Scanner = new Scanner(System.in)) {
				System.out.print("Enter an integer: ");
				int number = Scanner.nextInt();

				for (int i = 0; i <= 9; i++) {
				    if (number % i == 0) {
				        System.out.println(number + " is divisible by " + i);
				    } else {
				        System.out.println(number + " is not divisible by " + i);
				    }
				}
			}
	    }
	}
}
