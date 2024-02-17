```java
// Class is called roundFunction
package roundFunction;

import java.util.Scanner;

public class RoundMe {

	public static void main(String[] args) {
		Scanner scanner = new Scanner(System.in);
		System.out.println("+ ROUND CALCULATOR +\nUse this tool to round any integer with a decimal spot!");
		double userInput = scanner.nextDouble();
		
		int result = (int)(userInput + 0.5);
		
		System.out.println("The original input, " + userInput + " has been rounded to: " + result + ".");
	}

}
```
