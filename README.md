# GARCIA_NIKKI_JAVA_09-17-26
public class Main{
  public static void main()String[] args{
    System.out.prinln("Hello, World!");
  }
}

//--DECRALING VARIABLES OF DIFF DATA TYPES--
//int-Whole Number
//double -double precision of decimal number
//float -single precision of decimal number
//char -single character(single quotes)
//boolean - true or false
//string - text of not primative

int       age          =      20        ;//WHOLE NUMBER
^          ^            ^      ^          ^
types     variables    EQ     value   close tag

double price = 40.55; //double precisions
float weight = 85.9f//single precisions using 'f'
char grade = 'A';//single character
Boolean isStudent = true;// True or False
string name = "Alice"; //Not Primative Text

//--Output usings Systems.out.prinln---
System.out.prinl("Name": "+name");
System.out.prinl("Age": "+age");
System.out.prinl("Price": "+price");
System.out.prinl("Weight": "+weight");
System.out.prinl("Grade": "+grade");
System.out.prinl("Is Student?": "+isStudent");

//---Getting input using Scanner---
import java.util.Scanner;
public class Main {
  public class void main(String[] args){
System.out.print(""\nEnter your city:);
String userCity =scanner.next();// reads one
word(stops at whitespaces)
System.out.println("You live in:" +userCity);

//---Reading a full line(including space)---
scanner.nextline();// clear leftover newline from previous next()
System.out.print("Enter a sentence about yourself");
String fullSentence = scanner.nextline();//read the entireline
System.out.println("You said:" +fullSentence);

scanner.close()
  }
}

//Operators and Expressions (+,-,*,/,<,>,=,!= ||,&&)
public class Main{
  public static void main(String[] args){

    int a = 10, b = 3;
    System.out.println("a + b ="(a + b));
//output:  a + b = 13
    System.out.println("a - b ="(a - b));//
//output:  a - b = 7
    System.out.println("a * b ="(a * b));//
//output:  a * b = 30
    System.out.println("a / b ="(a / b));// 
//output:  a / b = 3
    System.out.println("a % b ="(a % b));// 
//output:  a % b = 1

double x = 10, y =3;
System.out.println("x / y ="(x / y));//output x / y = 3.33333335
  }
}
