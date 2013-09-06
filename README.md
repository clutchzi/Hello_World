Hello_World
===========

Cmpr 112 Java homework 2

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
