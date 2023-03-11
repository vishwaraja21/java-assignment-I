# java-assignment-I
#1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.
#Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int a,b,c;
        Scanner num = new Scanner(System.in);
        a = num.nextInt();
        b = num.nextInt();
        c = a+b;
        System.out.println(a+"+" +b+ "=" +c );
        System.out.println("multiply of two numbers: " +(a*b));
        System.out.println("Subtraction of two numbers: " +(a-b));
        System.out.println("Division of two numbers: " +(a/b));
        System.out.println("Remainder of two numbers: " +(a%b));
    }
}
~~~
#Output:
#2. Write a Java program to compare two numbers
#Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        int a,b;
        Scanner num = new Scanner(System.in);
        a = num.nextInt();
        b = num.nextInt();
        if(a>b) {
            System.out.println("a is greater");
        } else if (a==b) {
            System.out.println("both are equal");
        } else {
            System.out.println("b is greater");
        }
    }
}
~~~
#Output:
#3. Write a Java program to convert a string to an integer
#Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        String abc = ("143");
        int xyz = Integer.parseInt(abc);
        System.out.println(xyz);

    }
}
~~~
#Output:
#4. Java Program to find area of rhombus
#Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args) {
        Scanner haha = new Scanner(System.in);
        int a = haha.nextInt();
        int b = haha.nextInt();
        int c = (a*b)/2;
        System.out.println(c);
    }
}
~~~
#Output:

#5. Write a Java program to find the number of days in a month
#Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        Scanner s=new Scanner(System.in);
        int month=s.nextInt();
        int year=s.nextInt();
        if((month==1)||(month==3)||(month==5)||(month==7)||month==8||month==10||month==12)
        {
            System.out.println("This month has 31 Days.");
        }
        else if((month==4)||(month==6)||(month==9)||(month==11))
        {
            System.out.println("This month has 30 Days.");
        }
        else
        {
            if ((year % 400 == 0) || ((year % 4 == 0) && (year % 100 != 0)))
            {
                System.out.println("This month has 29 Days.");
            }
            else
            {
                System.out.println("This month has 28 Days.");
            }

        }
    }
}
~~~
#Output:


