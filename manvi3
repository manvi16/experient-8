import java.util.Scanner;
import java.lang.*;
class Exception
{
    int a,b;
	void setData()
	{
		String x,y;
		Scanner sc=new Scanner(System.in);
		System.out.print("\nEnter the value of x and y");		
		x= sc.next();
		y= sc.next();
		System.out.println();
		try
		{
			a=Integer.parseInt(x);
			b=Integer.parseInt(y);
		}		
		catch(NumberFormatException n)
		{
			System.out.println(n);
			System.out.println("Invalid");
			
		}
	}
	void showResult()
	{
		try
		{
			System.out.println("Divide:"+a/b);
		}
		catch(ArithmeticException e)
		{
			System.out.println(e);
			System.out.println("Not Divisible by 0");
			
		}
	}
	static public void main(String args[])
	{
			
		Exception ex=new Exception();
		ex.setData();
		ex.showResult();
	}
}