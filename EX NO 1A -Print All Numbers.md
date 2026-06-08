
# EX 1A Print All Numbers 
## DATE: 08/06/26
## AIM:
To Write a Java program that takes an integer input N from the user and prints all the numbers from 1 to N, separated by spaces, on a single line..

## Algorithm

1. Start the program and import the Scanner class to take user input.
2. Create a Scanner object to read an integer input N from the user.
3. Check if N is greater than 0; if not, display "Invalid input. N must be greater than 0."
4. Use a for loop to iterate from 1 to N.
5. Print each number separated by a space on the same line.
## Program:
```
/*
Program to implement Reverse a String
Developed by: PRIYADHARSHINI S
Register Number: 212223240129

import java.util.Scanner;
public class PrintNumbers {
    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int N = scanner.nextInt();
        if (N <= 0) {
            System.out.println("Invalid input. N must be greater than 0.");
        } else {
            for (int i = 1; i <= N; i++) {
                System.out.print(i + " ");
            }
        }
        scanner.close();
    }
}
*/
```

## Output:

<img width="491" height="159" alt="image" src="https://github.com/user-attachments/assets/d7a09919-ede9-4cc4-9d9f-bd8242ef79fb" />


## Result:
The program successfully print all the numbers from 1 to N. 
