import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) 
	{
		// your code goes here
Scanner sc=new Scanner(System.in);
int N=sc.nextInt();
if(N>=0&&N<=1000)
{
if(N%4==0)
{
System.out.println(++N);
}
else
{
System.out.println(--N);
}
}
}
}
    
    
output:
54
53
