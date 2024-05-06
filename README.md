# Amicable-no
------------------java-------------------------------------------------------------
import java.util.Scanner;
public class Main
    {
      public static void main(String args[]) {
            Scanner sc = new Scanner(System.in);
            int a = sc.nextInt();
            int b = sc.nextInt();
            int sum1= 0, sum2= 0;
            for (int i=1;i<=a;i++) {
                if (a%i==0)
                    sum1+=i;
            }
            for (int i=1;i<=b;i++) {
                if (b%i==0)
                    sum2+=i;
            }
            if (sum1==sum2)
                System.out.println("Yes");
            else
                System.out.println("No");	
    }
}
