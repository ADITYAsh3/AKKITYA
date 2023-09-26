# AKKITYA


my first git repository


author:ADITYA KUMAR


i am learning programming languages and also documenting it for further seeing it










#include <stdio.h>
#include<stdbool.h>
#include<string.h>
int main() {
    // Write C code here
  // #     printf("I like pizza!\n");
 //   printf("It's really good!\n");
    


    



//# This is a comment
    /*
        This
        is
        a
        multiline
        comment
    */
    /* escape sequence = character combination consisting of a backslash \ 
                         followed by a letter or combination of digits.
                         They specify actions within a line of text (string)
                         \n = newline
                         \t = tab 
                         \\ = display \
                         \' = display '
                         \" = display "
    */

   // printf("1\t2\t3\n4\t5\t6\n7\t8\t9\n");
    //printf("\"I like Pizza\" -Abraham Lincoln probably");
  //  return 0;
  
  
  
  
  
   // variable =   Allocated space in memory to store a value.
    //              We refer to a variable's name to access the stored value.
    //              That variable now behaves as if it was the value it contains.
    //              BUT we need to declare what type of data we are storing.

   /* int x;            //declaration
    x = 123;       //initialization
    int y = 321; //declaration + initialization

    int age = 21;              //integer
    float gpa = 2.05;       //floating point number
    char grade = 'C';        //single character
    char name[] = "Bro";  //array of characters
    
    // % = format specifier
    printf("Hello %s\n", name);
    printf("You are %d years old\n", age);
    printf("Your average grade is %c\n", grade);
    printf("Your gpa is %f\n", gpa);

    return 0;}*/
    
    
    
    
    /* char a = 'C';                  // single character    %c
    char b[] = "Bro";            // array of characters %s  

    float c = 3.141592;                         // 4 bytes (32 bits of precision) 6 - 7 digits %f
    double d = 3.141592653589793; // 8 bytes (64 bits of precision) 15 - 16 digits %lf

    bool e = true;                        // 1 byte (true or false) %d
 
    char f = 120;                         // 1 byte (-128 to +127) %d or %c
    unsigned char g = 255;       // 1 byte (0 to +255) %d or %c

    short h = 32767;                  // 2 bytes (−32,768 to +32,767) %d
    unsigned short i = 65535;  // 2 bytes (0 to +65,535) %d

    int j = 2147483647;                    // 4 bytes (-2,147,483,648 to +2,147,483,647) %d
    unsigned int k = 4294967295;  // 4 bytes (0 to +4,294,967,295) %u

    long long int l = 9223372036854775807;                         // 8 bytes (-9 quintillion to +9 quintillion) %lld
    unsigned long long int m = 18446744073709551615U; // 8 bytes (0 to +18 quintillion) %llu

    printf("%c\n", a);  // char
     printf("%s\n", b);  // character array
    printf("%f\n", c);  // float
    printf("%lf\n", d); // double
    printf("%d\n", e);  // bool
    printf("%d\n", f);  // char as numeric value
    printf("%d\n", g);  // unsigned char as numeric value
    printf("%d\n", h);  // short
    printf("%d\n", i);  // unsigned short
    printf("%d\n", j);  // int
    printf("%u\n", k);  // unsigned int
    printf("%lld\n", l);  // long long int
    printf("%llu\n", m);  // unsigned long long int

    return 0;
}*/





 /*// format specifier % = defines and formats a type of data to be displayed

    // %c = character
    // %s = string (array of characters) 
    // %f = float
    // %lf = double
    // %d = integer

    // %.1 = decimal precision
    // %1 = minimum field width
    // %- = left align
    
    float item1 = 5.75;
    float item2 = 10.00;
    float item3 = 100.99;

    printf("Item 1: $%8.2f\n", item1);
    printf("Item 2: $%8.2f\n", item2);
    printf("Item 3: $%8.2f\n", item3);
    
    return 0;
}*/
    
    
    
    
    
    
    
/*    // constant = fixed value that cannot be altered by the program during its execution

    const float PI = 3.14159;

    //PI = 420.69; YOU CAN'T CHANGE THIS

    printf("%f", PI);
    
    return 0;
}  */
   // const float PI=56.87;
   // printf("%f",PI);
  //  return 0;}
  
  
  
  
  
 /*  // arithmetic operators
 
    // + (addition)
    // - (subtraction)
    // * (multiplication)
    // / (division)
    // % (modulus)
    // ++ increment
    // -- decrement
 
    int x = 5;
    int y = 2;
    
    // int z = x + y;
    // int z = x - y;
    // int z = x * y;
    // float z = x / (float) y;
    // int z = x % y;
    // x++;
    // y--;

    printf("%d\n", x);
    printf("%d", y);
    return 0;}*/
    
    
    
    
    
      // augmented assignment operators = used to replace a statement where an operator
    //                                  takes a variable as one of its arguments
    //                                  and then assigns the result back to the same variable
    //                                  x = x + 1
    //                                  x+=1
 
  //  int x = 10;
 
    // x = x + 2;
    // x+=2;
 
    // x = x - 3;
    // x-=3;
 
    // x = x * 4;
    // x*=4;
 
    // x = x / 5;
    // x/=5;
 
    // x = x % 2;
    // x%=2;
 
    //printf("%d", x);
    
    //return 0;
    






 /* char name[25]; //bytes
    int age;

    printf("\nWhat's your name?");
    //scanf("%s", &name);
    fgets(name, 25, stdin);
    name[strlen(name)-1] = '\0';

    printf("How old are you?");
    scanf("%d", &age);

    printf("\nHello %s, how are you?", name);
    printf("\nYou are %d years old", age);

    return 0;
}*/
//fgets help you to take inputs having whitespaces which is not in scanf
