# EvenOddcheck
Using this code check any Integer number is Even or  Odd.//
package mypackage;
import java.util.Scanner;
public class evenoddcheck {

	public static void main(String[] args) {
		
		// TODO Auto-generated method stub
		Scanner sc= new Scanner(System.in);
		System.out.print("Enter the value :");
		int n =sc.nextInt();
		
		if(n%2==0) {
			System.out.println("The given number is even"+n);
		}
		else {
			System.out.println("the given number is odd"+n);
		}

	}

}
