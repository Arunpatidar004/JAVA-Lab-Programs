// calc in interface
interface Calc
{
    public void Add(int a,int b);
    public void Sub(int a,int b);
    public void Mult(int a,int b);
    public void Div(int a,int b);
    
}
 class U1 implements Calc
{
    public void Add(int a,int b)
    {
        System.out.println(a+b);
    }
    public void Sub(int a,int b)
    {
        System.out.println(a-b);
    }
    public void Mult(int a,int b)
    {
        System.out.println(a*b);
    }
    public void Div(int a,int b)
    {
        System.out.println(a/b);
    }
    
}
 class U2 implements Calc
{
    public void Add(int a,int b)
    {
        System.out.println(a+b);
    }
    public void Sub(int a,int b)
    {
        System.out.println(a-b);
    }
    public void Mult(int a,int b)
    {
        System.out.println(a*b);
    }
    public void Div(int a,int b)
    {
        System.out.println(a/b);
    }
    
}
public class Test
{
public static void main(String args[])
    {
        U1 t=new U1();
        U2 t1=new U2();
        
        t.Add(4,2);
        t.Sub(4,2);
        t.Mult(4,2);
        t.Div(4,2);
        
        t1.Add(4,2);
        t1.Sub(4,2);
        t1.Mult(4,2);
        t1.Div(4,2);
    }
}
