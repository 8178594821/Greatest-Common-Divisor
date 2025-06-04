import java.util.*;
public class Main {
 public static void main(String[] args) {
 Scanner scanner = new Scanner(System.in);
 int a = scanner.nextInt();
 int b = scanner.nextInt();
 int gcd = fndGCD(a, b);
 System.out.println(gcd);
 }
 public static int fndGCD(int a, int b) {
 if (b == 0)
 return a;
 return fndGCD(b, a % b);
 }
 }
