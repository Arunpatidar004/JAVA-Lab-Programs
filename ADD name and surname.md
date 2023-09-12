//ADD name and surname
import java.util.Scanner;
 class Name
{
   String name;
   String surname;
  Name(String name,String surname)
    {
        this.name=name;
        this.surname=surname;
    }
   static Name funct(Name x,Name y)
   {
        return new Name (x.name+y.name ,x.surname+y.surname);
    }
}
    class ex
    {
        public static void main (String[] args) 
        {
            Name x=new Name("Aishwaraya","Rai");
            Name y=new Name("Abhishek","Bachan");
           Name z=Name.funct(x,y);
            System.out.print(z.name +" "+ z.surname);
        }
    }
