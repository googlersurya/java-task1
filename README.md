import java.util.Scanner;

class Input {
    public static void main(String[] args) {
    Scanner input = new Scanner(System.in);
    System.out.print("Enter name: ");
    String a = input.nextLine();
    System.out.println("Your name is " + a);
    input.close();
    }
}
