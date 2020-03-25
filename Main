import java.util.Scanner;

public class Main {
    public static void main (String[] args) {
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter your score:");
        int score = sc.nextInt();
        String cong = "Congratulations!";
        String cd = "Good!";
        String O = "OH NO!";
        
        if (score < 0 || score > 100) {
            System.out.println("Please enter your score again(0-100)");
        } else if (score >90 && score <= 100) {
            System.out.println(cong+"You got A");
        } else if (score >80 && score <= 90) {
            System.out.println(cd+"You got B");
        } else if (score >70 && score <= 80) {
            System.out.println(cd+"You got C");
        } else if (score >60 && score <= 70) {
            System.out.println(cd+"You got D"); 
        } else {
            System.out.println(O+"You got F");
        }
        
    }
}
