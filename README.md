# Simple-interest-
package simple.interest.java;
import java.util.Scanner;
 
public class SimpleInterestJava {
    public static void main(String[] args) {
                Scanner sc= new Scanner(System .in);
        System.out.println("enter principal amount=");
        double principal=sc.nextDouble();
        System.out.println("enter the annual income:");
        double rate =sc.nextDouble();
        System.out.println(" enter time (in yrs):");
        double time =sc.nextDouble();
        double simpleinterest=(principal*rate*time)/100;
        System.out.println("simpleinterest="+simpleinterest);
              }
    }
    
package electric.bill.java;
import java.util.Scanner;
public class ElectricBillJava {
    public static void main(String[] args) {
                Scanner sc = new Scanner(System.in);
        System.out.println("enter the no of units consumed :)");
        int units=sc.nextInt();
        double rate =1.50;
        double billamount =units*rate;
        System.out.println("electric billamount :rs"+billamount);
             
    }      
             
    
}

Output: enter the no of units consumed :)
58
electric billamount :rs87.0
package pkgclass.object;
import java.util.Scanner;
