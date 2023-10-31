////multipal object by interface with Thread

public class Main extends Thread
{
     public void run (){System.out.println(" welcome to csit");}

public static void main (String[] args) {
    Thread n1=new Thread();
     Thread n2=new Thread();
  Thread n3=new Thread();
      n1.start();
      n2.start();
      n3.start();
}
}
