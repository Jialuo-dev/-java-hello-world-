# -java-hello-world-
package hello;
import java.util.Scanner;
public class ComputerAreswWithConstant {

	public static void main(String[] args) {
		// TODO Auto-generated method stub
		final double PI = 3.14159;//Declare a constant
		// Create a Scanner object 
		Scanner input = new Scanner(System.in);
		//prompt the user to enter a radius
		System.out.print("Enter a number for radius:");
		double radius = input.nextDouble();
		//Compute area
        double area =radius * radius* PI;
        //Display result 
        System.out.println("The area for the circle of radius"+radius+"is"+area);
	}

}
