# Java-Basic-Code
All interview basic question
import java.util.Scanner;
class Fibonacci{
	public static void main(String[] args)
	
	{
		int a=1;
		Scanner sc=new Scanner(System.in);
		System.out.println("Enter the value");
		int n=sc.nextInt();
		for(int i=n;i>=1;i--)
		{
			
			a=a*i;
			
			
		}
		System.out.println("Anns: "+ a);
		
	}
}
