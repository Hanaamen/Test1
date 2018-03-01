package ma;

import java.util.Scanner;

public class mar {

	
	
	
	

	public static  void main(String[] args) {
		// TODO Auto-generated method stub
		
		{
		
			   float x=0 ; 
				float y=0;
				System.out.println("**** Hello Java group this is my calculator**** ");
				System.out.println("please enter the first number:");
				System.out.println("please enter the secound number ");
				Scanner in = new Scanner(System.in);
				x=in.nextInt();
				y=in.nextInt();
				System.out.println("for addition press--- 1 ( +)");
				System.out.println("for sudtraction press -- 2 (-)");
				System.out.println("for devision press--- 3 (/)");
				System.out.println("for multiplucation press---- 4 (*)");
				int ope = 0 ;
				ope=in.nextInt();
				float z = 0;
				 ; 
				
				 
				if (ope ==1) {
					
					z=x+y ;}
					else if ( ope ==2 ) {
						z=x-y;
					}
					else if
					 (ope ==3) {
						z=x/y ;}
					else if
					 (ope ==4) {
						z=x*y ;}
		System.out.println(+z);

	}
}}
