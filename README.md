# EXP -3 Java program to find the number of day in a month
# AIM:
To find the number of days in a month in java.
# PROCEDURE:
## Step 1:
## Step 2:
## Step 3:
## Step 4:
## Step 5:

# PROGRAM:
```
import java.util.Scanner;

public class days {
        public static void main(String[] args) {
            Scanner sc=new Scanner(System.in);
            System.out.println("Enter the month number");
            int Month=sc.nextInt();
            switch(Month)
            {
                case 1:
                    System.out.println("31 days");
                    break;
                case 2:
                    System.out.println("28 days");
                    break;
                case 3:
                    System.out.println("31 days");
                    break;
                case 4:
                    System.out.println("30 days");
                    break;
                case 5:
                    System.out.println("31 days");
                    break;
                case 6:
                    System.out.println("30 days");
                    break;
                case 7:
                    System.out.println("31 days");
                    break;
                case 8:
                    System.out.println("31 days");
                    break;
                case 9:
                    System.out.println("30 days");
                    break;
                case 10:
                    System.out.println("31 days");
                    break;
                case 11:
                    System.out.println("30 days");
                    break;
                case 12:
                    System.out.println("31 days");
                    break;
                default:
                    System.out.println("Invalid month number");
                    break;

        }
    }
}

```
# OUTPUT:
![image](https://github.com/Evangelin-Ruth/days-in-month/assets/94219798/0d7077d3-f4dc-4d44-b276-e1dc16cf6bd9)

