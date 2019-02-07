week2

import java.util.Scanner;

/*author: CaylaKlein
         * Created: 2.7.19
         *description: This program will calculate the average of three numbers
         */
public class TestZero {

           public static void main(String [] args){
           Scanner scnr = new Scanner (System.in);
           System.out.print("Enter three numbers: ");
           
           double num1;
           num1 = scnr.nextDouble();
           
           double num2;
           num2 = scnr.nextDouble();
           
           double num3;
           num3 = scnr.nextDouble();
           
           double Avg;
           
           Avg = (num1 + num2 + num3) / 3;
           
           System.out.print("The average is: " + Avg);
           }
}
