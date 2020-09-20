package com.company;

import java.util.Scanner;

public class Main {

    public static void main(String[] args) {

        Scanner input = new Scanner(System.in);

        System.out.println("Welcome to ElizaChats! My name is Eliza. What is your name?");

        String name = input.nextLine();
        System.out.println("My name is " +name);

        System.out.println("Nice to meet you " +name+ ". How has your day been?");

        String day = input.nextLine();
        System.out.println("My day has been " +day);

        System.out.println("Why has been your day been " + day+ "?");

        String day_reason= input.nextLine();
        System.out.println("My day has been " +day+ " because " +day_reason);

        System.out.println("Here are your responses: " +name+ " " +day+ " " +day_reason);

    }
}
