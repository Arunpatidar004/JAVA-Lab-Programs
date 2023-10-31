///inheritence with Thread


 public class Main extends Thread
{
	public static void main(String[] args)
	{
		Main thread=new Main();
		thread.start();
		System.out.println(" this code is outside of the thread");
	}
	 public void run()
     {
         System.out.println(" this cod is runnimg in a thread");
     }
}
