# JAVA-WEIGHT-CONVERSION
A lightweight Java application that converts between various weight units such as kilograms, pounds, grams, and ounces. Designed for educational use and beginner-level Java practice.

    import java.util.Scanner;

    public class Main {

    public static void main(String[] args){

        Scanner scan = new Scanner(System.in);

        double weight;
        double newWeight;
        int choice;

        System.out.println("********************");
        System.out.println("WEIGHT CONVERSION");
        System.out.println("1. Convert lgs to kgs");
        System.out.println("2. Convert kgs to lgs");
        System.out.println("********************");

        System.out.print("Enter Your Choice(1 or 2): ");
        choice = scan.nextInt();

        if(choice == 1)
        {

            System.out.print("Enter The Weight Of lgs: ");
            weight = scan.nextDouble();
            newWeight = weight * 0.4525;
            System.out.println("The New Weight Of lgs is: " +newWeight);
        }

        else if(choice == 2){

            System.out.print("Enter The Weight Of kgs: ");
            weight = scan.nextDouble();
            newWeight = weight * 2.0243;
            System.out.println("The New Weight Of kgs is: " +newWeight);

        }
        else
        {
            System.out.println("No More Choice Are Given");

        }
     }
    }
