
import java.util.Scanner;

/**
 * this is <b>olive press</b> application, and <i>olives</i>
 */

public class Main {
    /**
     * the main
     * @param args application
     */

    public static void main (String[] args){

        Scanner scan = new Scanner (System.in);

        int a=2, b=10;
        System.out.println("2a:");
        System.out.println("a+b=" + (a+b));
        System.out.println("a-b=" + (a-b));
        System.out.println("a*b=" + (a*b));
        System.out.println("b/a=" + (b/a));

        System.out.println("2b:");

        int r=b/a;
        r++;
        System.out.println(r);
        int i=5, j;
        j=-i;
        System.out.println(j);
        j+=10;
        System.out.println(j);

        System.out.println("2c:");
        int k=10;
        System.out.println(k==20);
        System.out.println(k!=10);

        System.out.println("2d:");

        System.out.print("c=");
        int c = scan.nextInt();
        System.out.print("d=");
        int d = scan.nextInt();

        if ((c > 0) && (d > 0) || (c > 0) && (d < 0)){
            System.out.println("true");
        }
        else {
            System.out.println("false");
        }

        int num1=2, num2=5;
        System.out.println("!(2>5)=" + !(num1>num2));

        System.out.println("3:");
        System.out.print("num3=");
        int num3 = scan.nextInt();
        System.out.print("num4=");
        int num4 = scan.nextInt();
        if (num3>num4){
            System.out.println(num3);
        }
        else {
            System.out.println(num4);
        }

        System.out.println("4:");
        int num=2, n=1, l=1;
        while (l<=10){
            n*=num;
            System.out.println(num + "^" + l + "=" + n);
            l++;
        }
        int q=12;
        do {
            System.out.println(q);
            q++;
        }while (q<10);

        for (int ir=0; ir<10; ir+=2 ){
            System.out.println(ir);
        }

        System.out.println("5:");
        for (int it=0; it<10; it++){
            if (it==7){
                break;
            }
            System.out.println(it);
        }

        for (int it=0; it<10; it++){
            if (it==3){
                continue;
            }
            System.out.println(it);
        }


    }
}
