Hello_World
===========

// Hello World code fro cmpr 112 class

import java.util.Scanner;

class HelloWorld {
    public static void main(String[] args) {
       
        System.out.println("Hello special agent. Type your username :) ");
        Scanner user_input = new Scanner( System.in );
        String Username;
     
        Username = user_input.next( );
 
        System.out.println("Oh hello agent " + Username + " We have a new mission for you");
    }
}
