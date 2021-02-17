/*
  Make sure the class is NOT public.
  This program won't run properly without an input. Try with: abc
*/
import java.util.Scanner;

class HelloWorld {
  public static void main(String[] args) {
   Scanner keyboard = new Scanner(System.in);
    
    int a, b;
    System.out.println("Give me a number");
     a = keyboard.nextInt();
    System.out.println("Give me another number");
     b = keyboard.nextInt();
    System.out.println((a+b));
                                  
  }
}
