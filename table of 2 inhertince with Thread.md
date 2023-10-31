///table of 2 inhertince with Thread


class MultiplicationTable2 extends Thread {

  public void run() {
    for(int i=1; i<=10; i++) {
      System.out.println(2 + " x " + i + " = " + 2*i);
    }
  }

}

public class Main {

  public static void main(String[] args) {
    MultiplicationTable2 t1 = new MultiplicationTable2();
    MultiplicationTable2 t2 = new MultiplicationTable2();

    t1.start();
    t2.start();
  }

}


