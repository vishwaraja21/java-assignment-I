# Java-Weekly-Assignment-I
# VISHWARAJA.R
# 212221220060
# 1.Write a Java program to print the sum, multiply, subtract, divide and remainder of two numbers.

# Program:
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
# Output:

![image](https://user-images.githubusercontent.com/102411421/224492940-c6bccb8e-2cd4-40a7-96d3-c57981726778.png)



# 2. Write a Java program to compare two numbers

# Program:
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
# Output:

![image](https://user-images.githubusercontent.com/102411421/224493021-532342e9-14db-4a58-8248-e8941f681b35.png)


# 3. Write a Java program to convert a string to an integer

# Program:
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
# Output:

![image](https://user-images.githubusercontent.com/102411421/224493277-98779208-6d0a-4839-b37e-170726cefaa7.png)


# 4. Java Program to find area of rhombus

# Program:
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
# Output:

![image](https://user-images.githubusercontent.com/102411421/224493058-bf004fdf-a305-411e-a6e8-414dd89d8a6b.png)


# 5. Write a Java program to find the number of days in a month

# Program:
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
# Output:

![image](https://user-images.githubusercontent.com/102411421/224493083-849e17b5-5b38-4d79-bdc8-4df1f10e9750.png)


# 6. Write a Java program to print the even numbers from 1 to 20

# Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        int i;
        for(i=1;i<=20;i++)
        {
            if(i%2 == 0)
            {
                System.out.println(i+"\t");
            }
        }
    }
}
~~~
# Output:

![image](https://user-images.githubusercontent.com/102411421/224493114-ebee0af6-ec80-4f35-aa0a-a6721380fa7b.png)


# 7. Write a Java program to create a simple calculator

# Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        System.out.println("Enter Choice(1-add,2-sub,3-div,4-mul");
        Scanner s = new Scanner(System.in);
        int choice = s.nextInt();
        System.out.println("Enter 1st number: ");
        int a = s.nextInt();
        System.out.println("Enter 2nd number: ");
        int b = s.nextInt();
        switch(choice)
        {
            case 1:
            {
                System.out.println(a+b);
                break;
            }
            case 2:
            {
                System.out.println(a-b);
                break;
            }
            case 3:
            {
                System.out.println(a/b);
                break;
            }
            case 4:
            {
                System.out.println(a*b);
                break;
            }
            default:
            {
                System.out.println("Enter choice range btw 1-4");
                break;
            }
        }
    }
}
~~~
# Output:

![image](https://user-images.githubusercontent.com/102411421/224493173-0a65d1b1-69e7-4597-9b69-a715b81aa3e5.png)


# 8. Write a Java program to print multiplication table of given number

# Program:
~~~
import java.util.Scanner;
public class Main {
    public static void main(String[] args)
    {
        System.out.print("Enter a number: ");
        Scanner s = new Scanner(System.in);
        int a = s.nextInt();
        for(int i=1;i<=10;i++)
        {
            System.out.println(a+ " * " +i+ " = " +(a*i));
        }
    }
}
~~~
# Output:


![image](https://user-images.githubusercontent.com/102411421/224493252-1e000b77-919f-4637-b0fd-d80852dee32d.png)

