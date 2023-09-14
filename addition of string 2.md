//addition of string
import java.util.Scanner;
public class Main 
{
    public static void main (String[] args) {
        //create first string
        String first ="java";
        System.out.println("First String:- "+first);
        //creat secund string
        String secund="programming";
        System.out.println("secund String:- "+secund);
        //join two string
        String joinedString = first.concat(secund);
        System.out.println("joined String:- "+joinedString);
        System.out.println(first.substring(0,2));
    }
}
