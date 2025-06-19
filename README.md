# JAVA-
import java.util.Scanner;

public class Main {
    public static void main(String[] args) {
        int pen = 10;
        int book = 50;
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter the amount you have:");
        int user = sc.nextInt();
        if (user >= 60)
            System.out.println("You can buy both a pen and a book.");
        else if (user <= 60 && user >= 50)
            System.out.println("You can buy a book.");
        else if (user < 50 && user >= 10)
            System.out.println("You can buy a pen.");
        else
            System.out.println("You cannot buy anything.");
    }
}
