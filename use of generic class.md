//////use of generic class
class MyData<E>
{
     E i;
    public void set (E i1)
    {
        i=i1;
        
    }
    public E get()
    {
        return  i;
    }
}
    public class Example
    {
        public static void main (String[] args) 
        {
            MyData<Integer> m= new MyData<Integer>();
            MyData<String> m1=new MyData<String>();
            // Integer k=new Integer(5);
            m1.set("rohit");
            m1.get();
        }
    }
