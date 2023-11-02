//// Banking in Thread
import java.util.Scanner;

class Banking 
{
    String account = "1233546";
    int balance = 10000;

    public static void printing(String account, int amount, int balance)
    {
        if (balance > amount)
        {
            balance = balance - amount;
            System.out.println(balance);
        }
        if (balance < amount) 
        {
            balance = balance + amount;
            System.out.println(balance);
        }
    }
}

class Withdraw extends Thread
{
    public void run() 
    {
        Banking b = new Banking();
        b.printing("1233546", 0, 0);
    }
}

class Deposit extends Thread
{
    public void run() {
        Banking b = new Banking();
        b.printing("1233546", 0, 10000);
    }
}

class Main {
    public static void main(String[] args)
    {
        Withdraw t1 = new Withdraw();
        t1.start();
        Deposit t2 = new Deposit();
        t2.start();
    }
}
