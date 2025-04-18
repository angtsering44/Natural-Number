# Natural-Number
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        int loop, i;
        System.out.println("Enter the number:");

        Scanner input = new Scanner(System.in);
        loop = input.nextInt();

        for (i = 0; i <= loop; i++) {
            System.out.println("Your number is " + i);
        }

    }
}
