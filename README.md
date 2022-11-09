# SawMinLwin
Welcome 

package OOP_interface;

import java.util.Scanner;

public class Calculate {
	static int addition(int n1,int n2) {
		return n1+n2;
	}
	static double addition(double a,double b) {
		return a+b;
		}
	static void addition() {
		int sum =0;
		String status = "yes";
		Scanner input = new Scanner(System.in);
		do {
			System.out.println("Enter number :");
			sum+=input.nextInt();
			System.out.println("Do you want to input another number(yes/no)");
			status = input.next();
		
		}while(status.equals("yes")); 
		System.out.println("sum ="+sum);
	}

	public static void main(String[] args) {
		System.out.println("n1+n2 ="+addition(32,32)); //int sum = addition(32,32
		System.out.println("a+b="+addition(32.3,33.3));
		addition();
	}

}

