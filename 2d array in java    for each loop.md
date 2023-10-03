// 2d array in java    ---for each loop
import java.util.Scanner;
class twoDloop
{
    public static double getAvg(int[][]a)
    {
        double total=0;
        for(int[] i:a)
        {
            for(int val:i)
            {
                System.out.println(val);
                total=total+val;
            }
        }
        return total/(a.length*a[0].length);
    }
    public static void main (String[] args) {
        int[][]theArray={{80,90,70},{20,80,75}};
        System.out.println(getAvg(theArray));
    }
}
