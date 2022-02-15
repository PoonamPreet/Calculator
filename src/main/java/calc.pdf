import java.io.*;
import java.util.Scanner;


public class Calculators {
	public void add (){
		try {
		int a,b;
		Scanner sc=new Scanner(System.in);
		System.out.println("-***************Addition of numbers****************-");
		System.out.println("Enter the value of a");
		a=sc.nextInt();
		System.out.println("Enter the value of b");
		b=sc.nextInt();
		int add=a+b;
		System.out.println("Added value is "+add);
		}
		catch(Exception ex)
		{
			System.out.println("Excpetion raised"+ex);
			System.out.println("Please enter valid input");
		}
	}
	public void subtract() 
	{
		try {
			int a,b;
			System.out.println("-***************Subtraction of numbers****************-");
			Scanner sc=new Scanner(System.in);
			System.out.println("Enter the value of a");
			a=sc.nextInt();
			System.out.println("Enter the value of b");
			b=sc.nextInt();
			int sub=a-b;
			System.out.println("Subtracted value is "+sub);
			}
			catch(Exception ex)
			{
				System.out.println("Excpetion raised"+ex);
				System.out.println("Please enter valid input");
			}
	}
	public void mutiply() 
	{
		try {
			int a,b;
			System.out.println("-***************Multiplication of numbers****************-");
			Scanner sc=new Scanner(System.in);
			System.out.println("Enter the value of a");
			a=sc.nextInt();
			System.out.println("Enter the value of b");
			b=sc.nextInt();
			int mul=a*b;
			System.out.println("Multiplied value is "+mul);
			}
			catch(Exception ex)
			{
				System.out.println("Excpetion raised"+ex);
				System.out.println("Please enter valid input");
			}
	}
	public void divide() 
	{
		try {
			int a,b;
			System.out.println("-***************Division of numbers****************-");
			Scanner sc=new Scanner(System.in);
			System.out.println("Enter the value of a");
			a=sc.nextInt();
			System.out.println("Enter the value of b");
			b=sc.nextInt();
			int div=a/b;
			System.out.println("Divided value is "+div);
			}
			catch(Exception ex)
			{
				System.out.println("Excpetion raised"+ex);
				System.out.println("Please enter valid input");
			}
	}
	public void modulus() 
	{
		try {
			int a,b;
			System.out.println("-***************Modulus of numbers****************-");
			Scanner sc=new Scanner(System.in);
			System.out.println("Enter the value of a");
			a=sc.nextInt();
			System.out.println("Enter the value of b");
			b=sc.nextInt();
			int mod=a%b;
			System.out.println("Modulo value is "+mod);
			}
			catch(Exception ex)
			{
				System.out.println("Excpetion raised"+ex);
				System.out.println("Please enter valid input");
			}
	}
	public static void main(String args[])
			{
		System.out.println("Added");
		Calculators cal=new Calculators();
		Scanner sc1=new Scanner(System.in);
		//cal.add();
		//cal.subtract();
		//cal.divide();
		//cal.modulus();
		//cal.mutiply();
		int choice=0;
		do 
		{
			System.out.println("Select your choice");
			System.out.println("1.Add");
			System.out.println("2.Subtract");
			System.out.println("3.Divide");
			System.out.println("4.Multiply");
			System.out.println("5.Modulos");
			System.out.println("6.Exit");
			choice=sc1.nextInt();
			switch(choice) 
			{
			case 1:cal.add();
			break;
			case 2: cal.subtract();
			break;
			case 3: cal.divide();
			break;
			case 4: cal.mutiply();
			break;
			case 5:cal.modulus();
			break;
			case 6:
				System.out.println("Than you for using calculator");
				System.exit(0);
			}
		}
		while(true);
			}
	
}
