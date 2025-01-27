# PERFORMING-VARIOUS-OPERATIONS
package operations.java;
import java.util.Scanner;
public class OperationsJava {
    public static void main(String[] args) {
        // TODO code application logic here
        Scanner sc = new Scanner (System.in);
        System.out.println("Enter the first number:");
        int a= sc.nextInt();
        System.out.println("Enter the second number:");
        int b= sc.nextInt();
        System.out.println("Enter the third number:");
        int c= sc.nextInt();
        //ARITHMETIC OPERATIONS
        System.out.println("Arithmetic operations!");
        System.out.println("Addition:"+(a+b+c));
        System.out.println("Subtraction:"+(a-b-c));
        System.out.println("Multiplication:"+(a*b*c));
        if (b!=0 && c!=0){
            System.out.println("Divisioin :"+(a/b/c));
        }
        else{
            System.out.println("Division: cannot divide by zero");
        }
        System.out.println("Modulus:"+(a%b%c));
        //RELATION OPERATIONS
        System.out.println("\nRelational operations!");
        System.out.println("a>b:"+(a>b));
        System.out.println("b<c:"+(b<c));
        System.out.println("a==c:"+(a==c));
        //LOGICAL OPERATIONS
        System.out.println("\nLogical operations!");
        System.out.println("(a>b)&&(b<c):"+((a>b)&&(b<c)));
        System.out.println("(a>b)||(b>c):"+((a>b)||(b>c)));
        System.out.println("!(a<b):"+(!(a<b)));
        //TENARY OPERATIONS
        System.out.println("\nTenary operations:");
        String result;
        if(a>b){
            result="a is greater than b";
        }
        else{
            result="a is not greater than b";
        }
        System.out.println("Result:"+result);
        }
        
        }
O/P
run:
Enter the first number:
5
Enter the second number:
3
Enter the third number:
2
Arithmetic operations!
Addition:10
Subtraction:0
Multiplication:30
Divisioin :0
Modulus:0

Relational operations!
a>b:true
b<c:false
a==c:false

Logical operations!
(a>b)&&(b<c):false
(a>b)||(b>c):true
!(a<b):true

Tenary operations:
Result:a is greater than b
BUILD SUCCESSFUL (total time: 7 seconds)

