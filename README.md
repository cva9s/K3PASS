# K3PASS
//code starts from here
import java.util.*;
import java.lang.*;
import java.io.*;

/* Name of the class has to be "Main" only if the class is public. */
class Codechef
{
	public static void main (String[] args) throws java.lang.Exception
	{
		// your code goes here
		int n,sum=0;
		Scanner sc=new Scanner(System.in);
		n=sc.nextInt();
		int s[]=new int[n];
		for(int i=0; i<n; i++){
		    s[i]=sc.nextInt();
		    sum+=s[i];
		}
		 int a=sum/n;
		 System.out.println(a);
	}
}
