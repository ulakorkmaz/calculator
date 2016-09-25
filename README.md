import java.util.*;
public class Calculator;
{
public static void main (String[] args)
{
int x,y;
Scanner klavye=new Scanner(System.in);
System.out.println("Enter two numbers :");
x=klavye.nextInt();
y=klavye.nextInt();
System.out.println("Addition:"+(x+y));
System.out.println("Subtraction:"+(x-y));
System.out.println("Multiplication:"+(x*y));
System.out.println("Division:"+(x/y));
}
}
