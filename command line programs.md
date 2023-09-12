//sume of any number
//Online Java Compiler IDE
//comand line programs
import java.util.Scanner;
public class eg
{
    static int sum =0;
	public static void main(String[] s)
	{
	    for(int i=0;i<s.length;i++)
	    {
	        sum=sum+Integer.parseInt(s[i]);
	        	System.out.println(s[i]);
	    }
		System.out.println("The sum is:- "+sum);

	}
	
}
