///interfece with thread

 public class Main implements Runnable
{
    public static void main (String[] args) {
        Main Object=new Main();
        Thread thread=new Thread(Object);
        thread.start();
        System.out.println("this code is outside of the thread");
    }
    public void run ()
    {
        System.out.println(" this code is runnimg in a thread ");
    }
}
