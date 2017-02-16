# Assignment-2.6
1.
import java.util.*;
public class Main {
public static void main(String args[])
{
	
	Scanner sc=new Scanner(System.in);
	int n1=sc.nextInt();					
	int n2=sc.nextInt();	
	System.out.println("The even numbers are:");
	for(int i=n1;i<=n2;i++)
	{
		if(i%2==0)
		{
			System.out.println(i);
		}
	}
	System.out.println("The odd numbers are:");
	for(int j=n1;j<=n2;j++)
	{
		if(j%2!=0)
		{
			System.out.println(j);
		}
	}
	

}
}

2.
import java.util.*;
public class Main {
public static void main(String args[])
{
	
	Scanner sc=new Scanner(System.in);
	int n=sc.nextInt();                           		
	int a=0;	                                   
	for(int i=1;i<=10;i++)
	{
		 a=i*n;
		 System.out.println(n+"x"+i+"="+a);         	
	}	
	
}
}
3.

import java.util.Scanner;

public class acad {
	public static void sum(int a , int b)			
    {
         System.out.println(a+b);
         
    }
    public static void  sum(String s1 ,String s2)  		
    {
    	String s3 = s1+s2;
         System.out.println(s3);
    }
	
	public static void main(String args[])
	{
		Scanner sc= new Scanner(System.in);
		
		int a = sc.nextInt();
		int b = sc.nextInt();
		String s1 = sc.next();
		String s2 = sc.next();
		sum(a,b);					
		sum(s1,s2);					
		}
	}
