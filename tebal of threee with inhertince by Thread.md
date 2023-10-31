////tebal of threee with inhertince by Thread

class Table2 extends Thread {
  public void run() {
    for(int i=1; i<=10; i++) {
      System.out.println(2 + " x " + i + " = " + 2*i);
    }
      for(int i=1; i<=10; i++) {
      System.out.println(3 + " x " + i + " = " + 3*i);
    }
  }

}

 class Main {

  public static void main(String[] args) {
  Table2 t1 = new Table2(); 
  t1.start();
    Table2 t2 = new Table2();


   
    t2.start();
  }

}

