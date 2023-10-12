
//implements 

 interface solution
{
    public void Hello();
    public void Welcome();
}
public class A implements solution{
    public void Hello(){
        System.out.println("Hello world");
    }
    public void Welcome(){
        System.out.println("Welcome to edureka");
    }
    public static void main (String[] args) {
        A a=new A();
        a.Hello();
        a.Welcome();
    }
}
