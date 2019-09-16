# -java-hello-world-
package helloword;
import java.util.Scanner;

public class DisplayTime {

	public static void main(String[] args) {
		Scanner input = new Scanner (System.in);
		//prompt the user for input
		// TODO Auto-generated method stub
		System.out.print("Enter an integer for seconds:");
		int second = input.nextInt();
 
		//Find minutes in seconds
		int remainingSecond = seconds % 60;//Second remaining
		System.out.println(second+"seconds is "+minutes+"minutes and"+ remainingSeconds +"seconds");

	}

}
