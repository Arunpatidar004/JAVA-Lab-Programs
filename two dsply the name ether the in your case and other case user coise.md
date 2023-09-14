 //two dsply the name ether the in your case and other case user coise

import java.util.Scanner;
 public class Main
{
    public static void main (String[] args) 
    {
        String s1="arun";
        System.out.println(s1);
        Scanner sc=new Scanner (System.in);
        System.out.println("enter choice");
        int choice=sc.nextInt();
        switch(choice)
        {
            case 0: 
                System.out.println(s1.toLowerCase());
            break;
            case 1: 
                System.out.println(s1.toUpperCase());
            break;
            default: 
            System.out.println(" error: ");
            break;
            
        }
    }
}
