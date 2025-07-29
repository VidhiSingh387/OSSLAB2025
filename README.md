# 0SSLab2025

This repository contains lab exercises for the Open Souce Software Lab-2025.

\## Lab Exercise 1

Name: Vidhi Singh

Roll Number: 231B387

Email: 231b387@juetguna.in



import java.util.Scanner;



public class GreatestOfTwo {

    public static void main(String\[] args) {

        Scanner sc = new Scanner(System.in);

        System.out.print("Enter the first number: ");

        int number1 = sc.nextInt();

        System.out.print("Enter the second number: ");

        int number2 = sc.nextInt();



        int greatest = Math.max(number1, number2);

        System.out.println("The greatest number is: " + greatest);

    }

}



