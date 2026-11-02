// 1.print a string in java-----------------------------------------------------------
/*public class Hello{

public static void main(String[] args) {
    System.out.println("hello world");
    System.out.println("sumit Yaduvanshi");
    
}}  */
// for output Command------------------------------------------------------------
/*public class Hello{
    public static void main(String[] agrs){
        System.out.println("*");
        System.out.println("**");
        System.out.println("***");
        System.out.println("****");
        System.out.println("*****");
    }
}*/
// Sum of Two Numbers // Variable Declaration----------------------------------------------
/*public class Hello{
    public static void main(String[] args){
        int a = 15;
        int b = 30;
        int sum = (a+b);
        System.out.println(sum);
    }
}*/
//input from user in java----------------------------------------------------------------
/*import java.util.Scanner;
public class Hello{
    public static void main(String[] args){     
    
    Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        int sum = (a+b);
        System.out.println(sum);
    }
}*/
//Mini calculator using java-------------------------------------------------------------
/*import java.util.Scanner;
public class Hello{
    public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        int sum = (a+b);
        int diff = (a-b);
        int mul = (a*b);
        int div = (a/b);
        int rem = (a%b);


        System.out.println("The sum of numbers are:"+sum);
        
        System.out.println("The diff of numbers are:"+diff);
        
        System.out.println("The multiplication of numbers are:"+mul);
        
        System.out.println("The division of numbers are:"+div);

        System.out.println("The remainder of numbers are:"+rem);

    }
}*/
//Swap to numbers program--------------------------------------------------------

/*import java.util.Scanner;

public class Hello{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        int a = sc.nextInt();
        int b = sc.nextInt();
        a = a+b;
        b = a-b;
        a = a-b;
        System.out.println("AfterSwapping: a = "+  a  +" , b = " +b);

         

    }
}*/
//Conditional Statements Programs----------------------------------------------------
// Eligible to vote or not-----------------------------------------------------------------
/*import java.util.Scanner;

public class Hello{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter Your Age:");
        int age = sc.nextInt();
        if (age>=18){
            System.out.println("you are eligible to vote Samajwadi party");
        }else{
            System.out.println("you are not eligible to vote Samajwadi party");
        }


    }
}*/
// if else lader problem-----------------------------------------------------------------

/*import java.util.Scanner;

public class Hello{
public static void main(String[] args){
    Scanner sc = new Scanner(System.in);
    System.out.println("enter Your Percentage");
    int per = sc.nextInt();
    if(per < 0 || per > 100){
    System.out.println("invalid Percentage");
    }
    else if(per >= 90){
        System.out.println("Grade A");
    }
     else if(per>=80){
        System.out.println("Grade B");
    }
     else if(per>=70){
        System.out.println("Grade C");
    }
     else if(per>=60){
        System.out.println("Grade D");
    }else{
        System.out.println("Fail");
    }

}
}*/
// Even or odd program----------------------------------------------------------------------

/*import java.util.Scanner;

public class Hello{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter Number:");
        int n = sc.nextInt();
        if(n%2==0){
            System.out.println("even Number");
        }else{
            System.out.println("odd Number");
        }


    }
}*/
//leap or not Leap Year---------------------------------------------------------
/* 
import java.util.Scanner;
 
public class Hello{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.println("enter Year:");
        int year = sc.nextInt();
        if(year%400==0 || (year%4==0 && year%100!=0)){
            System.out.println("Leap Year");}
            
                else{
                    System.out.println("not Leap year");
                }
            
        }
    }*/
//-----Switch Case----------------------------------------------------------------------------
//week Days using switch case
/*import java.util.*;
public class Hello{
    public static void main(String[] args){
        Scanner sc = new Scanner(System.in);
        System.out.println("Enter days from 1 to 7");
        int day = sc.nextInt();
        switch(day) {
        case 1:
            System.out.println("Monday");
            break;

            case 2:
            System.out.println("Tuesday");
            break;
            case 3:
            System.out.println("Wednesday");
            break;
            case 4:
            System.out.println("Thursday");
            break;
            case 5:
            System.out.println("Friday");
            break;
            case 6:
            System.out.println("saturday");
            break;
            case 7:
            System.out.println("Sunday");
            break;
            default:
                System.out.println("invalid Input From The user");
            }
    }
}*/
//-------------month name using Switch case---------------------------------------------------

/*import java.util.*
public class Hello{
    public static void main(String[]args){
        Scanner sc = new Scanner(System.in);
        System.out.println(" Enter month name from 1 to 12");
        int month= sc.nextInt();
        switch(month){
    
             case 1:
            System.out.println("January");
            break;
             case 2:
            System.out.println("Feburary");
            break;
             case 3:
            System.out.println("March");
            break;

             case 4:
            System.out.println("April");
            break;
             case 5:
            System.out.println("May");
            break;
            case 6:
            System.out.println("June");
            break;
            case 7:
            System.out.println("JUly");
            break;
             case 8:
            System.out.println("August");
            break;
             case 9:
            System.out.println("September");
            break;
             case 10:
            System.out.println("Octover");
            break;
             case 11:
            System.out.println("November");
            break;
            case 12:
                System.out.println("December");
                break;
             default:
                System.out.println("invalid month number entered");   


            

        }
    }
}*/
//Wap to print the no of days in month---------------------------------------------------
// rectangle pattern-----------------------------------------------
// public class Hello{
//     public static void main(String[] args){
//         int n=5;
//         int m=4;
//         for(int i=1;i<=n;i++){
//             for (int j=1;j<=m; j++){
//                 System.out.print("*");


//             }
//             System.out.println();
//         }
        
//     }
// }
//forward ----- traingle pattern---------------------------------------------------------------
// import java.util.*;
// public class pattern{
//     public static void main(String[] args){
//      int n =10;
//      for(int i=1;i<=n;i++){
// for(int j=1;j<=i;j++){
//     System.out.print("*");
// }
// System.out.println();
// }
// }}
// reverse traingle pattern---------------------------------------------------------------
// import java.util.*;
// public class reversepattern{
//     public  static void main(String[] args){
//         Scanner sc = new Scanner(System.in);
//         System.out.print("Enter the number of rows: ");
//         int n = sc.nextInt();
//         for (int i=n;i>=1;i--){
//             for(int j =1;j<=i;j++)
//             {
//                 System.out.print("*");

//             }
//             System.out.println();
//         }

//     }

// }
// Array -----------------------------------------------------------------
// sum of array elements---------------------------------------------------------------
// public class Hello{
//     public static void main(String[] args){
//         int arr[] = {1,2,3,4,5};
//         int sum = 0;
//         for(int i=0; i<arr.length ; i++){
//             sum = sum + arr[i];
//         }
//         System.out.println("Sum of array elements: " + sum);
//     }
// }
// Average of array elements---------------------------------------------------------------
// public class Hello2{
//     public static void main(String[] args){
//         int arr[] = {1,2,3,4,5};
//         int sum = 0;
//         for(int i=0; i<arr.length ; i++){
//             sum = sum + arr[i];
//         }
//         double average = (double)sum / arr.length; // Calculate average
//         System.out.println("Average of array elements: " + average);
//     }
// }
// Array length using length property---------------------------------------------------------------
//    public class Hello3{
//     public static void main(String[] args){
//         int arr[] = {0,2,3,4,5,12,34,54,67};
//         System.out.println("Length of array: " + arr.length);
//     }
//    }
// Array legth without using length property---------------------------------------------------------------
// public class Hello4{
//     public static void main(String[] args){
//         int arr[] = {0,2,3,4,5,12,34,54,67};
//         int count = 0;
//         for(int i = 0; i < arr.length; i++){
//             count++;
//         }
//         System.out.println("Length of array: " + count);
        
//     }
// }
//wap to replace 0 with 5-------------------
/* 
public class hello5{
    public static void main(String[] args) {
        int num = 1004;
        int result = 0;
        int place = 1;
        while(num>0){
            int digit = num % 10;
            if(digit==0) digit = 5;
            result = result+digit*place;
            place =place*10;
            num = num %10;
          
        }
System.out.println(result);
    }
    }
*/
--------------------------------------------------------------------------
public class hello {
    Public Static void main(String[] args){
        int [] arr = {12,22,123,13};
        sum = 0;
        for ( i = 0 ; i< arr.length ; i++)
    }
}
