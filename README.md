# Reverse-no.
Reverse no. in java
import java.util.Scanner;

public class reverseno {
    public reverseno() {
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int n = sc.nextInt();

        int r;
        for(r = 0; n > 0; n /= 10) {
            r *= 10;
            r += n % 10;
        }

        System.out.println(r);
    }
}
