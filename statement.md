// { autofold
public class Main {

public static void main(String[] args) {
// }
//first time learning Java language

String message = "Hello World!";
System.out.println(message);


//2.Print the sum of two numbers

int num1= 74;
int num2 = 36;
int sum = num1 + num2;

System.out.println(sum);

//divide two numbers and print on the screen

int a = 50;
int b = 3;

int divide = a/b;

System.out.println(divide);

//4. print the result of the following operations.
// a.-5 + 8 * 6; b. (55+9)%9; c. 20+ -3*5/8; d. 5+15/3*2-8%3
int number1 = -5,
number2 = 8,
number3 = 6,
number4 = 55,
number5 = 9,
number6 = 20,
number7 = -3,
number8 = 5,
number9 = 15,
number10 = 3,
number11 = 2;

int Qa = number1 + number2 * number3;
int Qb = (number4 + number5) % number5;
int Qc = number6 + number7 * number8 / number2;
int Qd = number8 + number9 / number10 * number11 - number2 % number10;

System.out.println(Qa);
System.out.println(Qb);
System.out.println(Qc);
System.out.println(Qd);

//5. takes two numbers as input and display the product of two number

int input1 = 25,
input2 = 5;
int times = input1 * input2;

System.out.println("5." + input1 + " x " + input2 + " = "+ times); 

//6.print the sum (addition), multiply, subract, divide and remainder of two number, input first number: 125, second input : 24

int input1 = 125;
int input2 = 24;
int sum = input1 + input2;
int sub = input1 - input2;
int time = input1 * input2;
int div = input1 / input2;
int mod = input1 % input2;

System.out.println("6." + input1 + " + " + input2 + " = " + sum);
System.out.println(input1 + " - " + input2 + " = " + sub);
System.out.println(input1 + " * " + input2 + " = " + time);
System.out.println(input1 + " / " + input2 + " = " + div);
System.out.println(input1 + " % " + input2 + " = " + mod);

//7. Takes a number as input and prints its multiplication table upto 10

int num = 8;


for( int a = 0; a < 11; a++)
{
    int total = num * a;
    
    System.out.println( num + " * " + a + " = " + total);

}

//Display the following pattern
//Sample Pattern :
//   J    a   v     v  a
//   J   a a   v   v  a a
//J  J  aaaaa   V V  aaaaa
// JJ  a     a   V  a     a

System.out.println("    J    a   v     v  a");
System.out.println("    J   a a   v   v  a a");
System.out.println(" J  J  aaaaa   V V  aaaaa");
System.out.println("  JJ  a     a   V  a     a");

//9. compute the specified expressions and print the output 
// 25.5 * 3.5 - 3.5 * 3.5 / 40.5 - 4.5

System.out.println((25.5 * 3.5 - 3.5 * 3.5) / (40.5 - 4.5));
 

//{ autofold
}

}
//}
