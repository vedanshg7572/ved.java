# armstrong code 
import java.util.Scanner;
public class armstrong {
    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();
        int sum=0;
        int m;
        m=n;
        while (n>0){
            int digit = n%10;
            n=n/10;
            sum+=Math.pow(digit,3);
        } if (m==sum){
            System.out.println("yes");
        }else {
            System.out.println("no");
        }
    }
}
