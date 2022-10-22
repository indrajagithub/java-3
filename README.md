# java-3
package com;
import java.util.Scanner;
class Problem1 {
	public static void main(String[] args) {
		Scanner scan=new Scanner(System.in);
		
		double a=scan.nextDouble();
		double b=scan.nextDouble();
		String ope=scan.next();
		
		if(ope.equals("+")){
			System.out.println(a+b);
		}
		else if(ope.equals("-")){
			System.out.println(a-b);
		}
		else if(ope.equals("*")){
			System.out.println(a*b);
		}
		else if(ope.equals("/")){
			System.out.println(a/b);
		}
		
	}
}
