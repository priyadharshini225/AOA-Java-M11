
# EX 1C Valid Pairs using Brute Force Approach
## DATE: 08/06/26
## AIM:
To write a Java program to for given constraints.
Given an integer array nums and an integer k, return the number of pairs (i, j) where i < j such that |nums[i] - nums[j]| == k.

The value of |x| is defined as:

x if x >= 0.
-x if x < 0.

## Algorithm
1. Start the program and import the Scanner class to take user input.
2. Read the number of elements n and then input the array elements.
3. Read the integer value k representing the required absolute difference.
4. Use nested loops to compare each pair (i, j) where i < j and check if |nums[i] - nums[j]| == k.
5. Count and display the total number of valid pairs that satisfy the condition.
## Program:
```
/*
Program to implement Reverse a String
Developed by: PRIYADHARSHINI S
Register Number: 212223240129

import java.util.Scanner;
public class CountPairsWithDifference {
    public static int countKDifference(int[] nums, int k) {        
          int count = 0;
          for (int i = 0; i < nums.length; i++)
          {
          for (int j = i + 1; j < nums.length; j++) 
          {
         if (Math.abs(nums[i] - nums[j]) == k) 
         {
            count++;
        }
    }
}
       return count;    
        
    }
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int[] nums = new int[n];
        for (int i = 0; i < n; i++) {
            nums[i] = sc.nextInt();
        }
        int k = sc.nextInt();
        int result = countKDifference(nums, k);
        System.out.println(result);
        sc.close();
    }
}
*/
```

## Output:

<img width="449" height="279" alt="image" src="https://github.com/user-attachments/assets/3ff901b7-0f78-42b5-abe5-0ac4f1eb405c" />


## Result:
The program successfully implemented and the expected output is verified.
