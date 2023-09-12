//ADD COMPLEX NO.
import java.util.Scanner;
 class Complex
{
    int real;
    int imag;
    Complex(int real,int imag)
    {
        this.real=real;
        this.imag=imag;
    }
    public static Complex add(Complex x,Complex y)
    {
        return new Complex (x.real+y.real,x.imag+y.imag);
    }
}
    class ex
    {
        public static void main (String[] args) {
            Complex x=new Complex(3,4);
            Complex y=new Complex(2,3);
            Complex z=Complex.add(x,y);
            System.out.print(z.real+"+"+z.imag+"i");
        }
    }
