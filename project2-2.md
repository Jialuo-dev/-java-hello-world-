# -java-hello-world-
public class ComputerAreaWithConsoleInput {
public static void main(String[] args) {
	// Creat a Scanner object 
	Scanner input = new Scanner(System.in);
	//Prompt the user to enter a radius
	System.out.print("Enter a number for radius: ");
	double radius = input.nextDouble();
	//Compute area
	double area =radius * radius *3.14159;
	//Display result 
	System.out.println("The area for the circle of radius "+radius +"is"+area);	
}
}
