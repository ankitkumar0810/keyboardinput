# keyboardinput
Write a java program to read two numbers and print their sum.

import java.util.*;

public class KeybRead {

    public static void main(String[] args) {
        
        Scanner sc = new Scanner(System.in);
        
        int a, b, sum;
        
        a = sc.nextInt();
        b = sc.nextInt();
        
        sum = a+b;
        System.out.println(sum);
    }
    
}
