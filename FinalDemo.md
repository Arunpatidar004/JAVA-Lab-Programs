// FinalDemo
final class FinalDemo
{
    public final void display()
    {
        System.out.println("this is a final methord ");
        
    }
}
class Main extends finalDemo{
    public void display()
    {
        System.out.println("the finalmethor is");
        
    }
    public static void main (String[] args) {
        Main obj =new Main();
        obj.display();
    }
}

//  Constructor
public class ConstructorChain
{
    ConstructorChain()
    {
        this("hello");
        System.out.println("default Constructor called");
    }
    ConstructorChain(String str)
    {
        System.out.println("Parmetraized Constructor called");
    }
    public static void main (String[] args) {
        ConstructorChain cc=new ConstructorChain();
    }
}// FinalDemo
final class FinalDemo
{
    public final void display()
    {
        System.out.println("this is a final methord ");
        
    }
}
class Main extends finalDemo{
    public void display()
    {
        System.out.println("the finalmethor is");
        
    }
    public static void main (String[] args) {
        Main obj =new Main();
        obj.display();
    }
}

//  Constructor
public class ConstructorChain
{
    ConstructorChain()
    {
        this("hello");
        System.out.println("default Constructor called");
    }
    ConstructorChain(String str)
    {
        System.out.println("Parmetraized Constructor called");
    }
    public static void main (String[] args) {
        ConstructorChain cc=new ConstructorChain();
    }
}
