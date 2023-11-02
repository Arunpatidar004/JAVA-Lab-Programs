////printiong even and odd in Thread

class print 
{
    public void printing (int n1, int n2, int n3){
    if(n3==0)
    {
        for(int i=n1;i<=n2;i++)
        {
            if(i%2==0)
            
        System.out.println(i);
    
        }
    }
    if(n3==1)
    {
        System.out.println(n3);
    }
    }
    
}
class Thread1 extends Thread

{
  public void run()
    {
          print p=new print();
          p.printing(1,50,0);
    }
} 
class Thread2 extends Thread
{

  

  public  void run()
    {
        print p= new print();
         p.printing(1,50,0);
    
}
}
class Main {
    public static void main (String[] args) {
        Thread1 t1 = new Thread1();
        t1.start();
         Thread2 t2 = new Thread2();
        t2.start();
    }
}
