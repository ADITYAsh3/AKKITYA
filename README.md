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





int main(){

  /*  double A = sqrt(9);
    double B = pow(2, 4);
    int C = round(3.14);
    int D = ceil(3.14);
    int E = floor(3.99);
    double F = fabs(-100);
    double G = log(3);
    double H = sin(45);
    double I = cos(45);
    double J = tan(45);
    
    printf("\n%lf", F);

    return 0;
}*/






 /*const double PI = 3.14159;
    double radius;
    double circumference;
    double area;

    printf("\nEnter the radius of a circle: ");
    scanf("%lf", &radius);

    circumference = 2 * PI * radius;
    area = PI * radius * radius;

    printf("\ncircumference: %lf", circumference);
    printf("\narea: %lf", area);

    return 0;
}*/





 /* double A;
    double B;
    double C;

    printf("Enter side A: ");
    scanf("%lf", &A);

    printf("Enter side B: ");
    scanf("%lf", &B);

    C = sqrt(A*A + B*B);

    printf("Side C: %lf", C);

    return 0;
}*/






 /*int age;

    printf("\nEnter your age: ");
    scanf("%d", &age);

    if(age >= 18){
        printf("You are now signed up!");
    }
    else if(age == 0){
        printf("You can't sign up! You were just born!");
    }
    else if(age < 0){
        printf("You haven't been born yet!");
    }
    else{
        printf("You are too young to sign up!");
    }

    return 0;
}*/






   /* // switch = A more efficient alternative to using many "else if" statements
    //          allows a value to be tested for equality against many cases

   char grade;

   printf("\nEnter a letter grade: ");
   scanf("%c", &grade);

   switch(grade){
      case 'A':
         printf("perfect!\n");
         break;
      case 'B':
         printf("You did good!\n");
         break;
      case 'C':
         printf("You did okay!\n");
         break;
      case 'D':
         printf("At least it's not an F!\n");
         break;
      case 'F':
         printf("YOU FAILED!\n");
         break;
      default:
         printf("Please enter only valid grades");
   }

    return 0;
}*/






/* char unit;
    float temp;

    printf("\nIs the temperature in (F) or (C)?: ");
    scanf("%c", &unit);

    unit = toupper(unit);

    if(unit == 'C'){
        printf("\nEnter the temp in Celsius: ");
        scanf("%f", &temp);
        temp = (temp * 9 / 5) + 32;
        printf("\nThe temp in Farenheit is: %.1f", temp);
    }
    else if(unit == 'F'){
        printf("\nEnter the temp in Farenheit: ");
        scanf("%f", &temp);
        temp = ((temp - 32) * 5) / 9;
        printf("\nThe temp in Celsius is: %.1f", temp);
    }
    else{
        printf("\n %c is not a valid unit of measurement", unit);
    }
    return;}*/
    
    
    
    
    
    
     /*char operator;
   double num1;
   double num2;
   double result;

   printf("\nEnter an operator (+ - * /): ");
   scanf("%c", &operator);

   printf("Enter number 1: ");
   scanf("%lf", &num1);

   printf("Enter number 2: ");
   scanf("%lf", &num2);

   switch(operator){
      case '+':
         result = num1 + num2;
         printf("\nresult: %lf", result);
         break;
      case '-':
         result = num1 - num2;
         printf("\nresult: %lf", result);
         break;
      case '*':
         result = num1 * num2;
         printf("\nresult: %lf", result);
         break;
      case '/':
         result = num1 / num2;
         printf("\nresult: %lf", result);
         break;
      default:
         printf("%c is not valid", operator);
   }

   return 0;}*/
   
   
   
   
   
   
   
   /*  // logical operators = && (AND) checks if two or more conditions are true
    
    float temp = 67;
    bool sunny = true;

    if(temp >= 0 && temp <= 30 && sunny){
        printf("\nThe weather is good!");
    }
    else{
        printf("\nThe weather is bad!");
    }
   
    return 0;
} */






/* // logical operators = || (OR) checks if at least one codition is true
    
    float temp = 25;

    if(temp <= 0 || temp >= 30){
        printf("\nThe weather is bad!");
    }
    else{
        printf("\nThe weather is good!");
    }
   
    return 0;
}*/





 /*// logical operators = ! (NOT) reverses the state of a condition
    
    bool sunny = false;
    bool subscribed = true;
    
    if(!sunny){
        printf("\nIt's cloudy outside!");
    }
    else{
        printf("\nIt's sunny outside!");
    }









    #include<stdio.h>
/*void birthday()
{
   printf("\nHappy birthday to you!");
   printf("\nHappy birthday to you!");
   printf("\nHappy birthday dear...YOU!");
   printf("\nHappy birthday to you!\n");
}

int main()
{
   birthday();
   birthday();
   birthday();

   return 0;
}*/





/*void birthday(char x[], int y)
{
   printf("\nHappy birthday dear %s!", x);
   printf("\nYou are %d years old!", y);
}

int main()
{
   char name[] = "Bro";
   int age = 21;

   birthday(name, age);

   return 0;
}*/





/*double square(double x)
{
   double result = x * x;
   return result;
}

int main()
{
   double x = square(3.14);
   printf("%lf", x);

   return 0;
}*/





/*int findMax(int x, int y)
{
   return (x > y) ? x : y;
}

int main()
{
   // ternary operator = shortcut to if/else when assigning/returning a value
   // (condition) ? value if true : value if false

   int max = findMax(3, 7);

   printf("%d", max);
  
   return 0;
}*/





/*void hello(char[], int); //function prototype

int main()
{
   // function prototype

   // WHAT IS IT?
   // Function declaration, w/o a body, before main()
   // Ensures that calls to a function are made with the correct arguments

   // IMPORTANT NOTES
   // Many C compilers do not check for parameter matching
   // Missing arguments will result in unexpected behavior
   // A function prototype causes the compiler to flag an error if arguments are missing

   // ADVANTAGES
   // 1. Easier to navigate a program w/ main() at the top
   // 2. Helps with debugging
   // 3. Commonly used in header files

   char name[] = "Bro";
   int age = 21;

   hello(name, age);

   return 0;
}

void hello(char name[], int age)
{
   printf("\nHello %s", name);
   printf("\nYou are %d years old", age);
}*/





/*int main(){
  
   char string1[] = "ADITYAsh";
   char string2[] = "Code";
 
   strlwr(string1);                              // converts a string to lowercase
   //strupr(string1);                           // converts a string to uppercase
   //strcat(string1, string2);             // appends string2 to end of string1
   //strncat(string1, string2, 1);       // appends n characters from string2 to string1
   //strcpy(string1, string2);             // copy string2 to string1
   //strncpy(string1, string2, 2);      // copy n characters of string2 to string1
   
   //strset(string1, '?');        //sets all characters of a string to a given character
   //strnset(string1, 'x', 1);  //sets first n characters of a string to a given character
   //strrev(string1);             //reverses a string

   //int result = strlen(string1);                          // returns string length as int
   //int result = strcmp(string1, string2);         // string compare all characters
   //int result = strncmp(string1, string2, 1);   // string compare n characters
   //int result = strcmpi(string1, string1);        // string compare all (ignore case)
   //int result = strnicmp(string1, string1, 1);  // string compare n characters (ignore case)

   printf("%s", string1);

   /*
   if(result == 0)
   {
      printf("These strings are the same");
   }
   else
   {
      printf("These strings are not the same");
   }
   

   return 0;
}*/






/*int main()
{
   // for loop = repeats a section of code a limited amount of times

   for(int i = 1; i <= 18; i++)
   {
      printf("%d\n", i);
   }

   return 0;
}*/







/////////////////////////////////////////////////////////////////////////////////////////////////////////////
/*int main()
{
   // while loop = repeats a section of code possibly unlimited times. 
   // WHILE some condition remains true
   // a while loop might not execute at all

   char name[25];

   printf("\nWhat's your name?: ");
   fgets(name, 25, stdin);
   name[strlen(name) - 1] = '\0';

   while(strlen(name) == 0)
   {
      printf("\nYou did not enter your name");
      printf("\nWhat's your name?: ");
      fgets(name, 25, stdin);
      name[strlen(name) - 1] = '\0';
   }

   printf("Hello %s", name);

   return 0;
}*/
///////////////////////////////////////////////////////////////////////////////////////////////////////






/*int main()
{
   // while loop = checks a condition, THEN executes a block of code if condition is true
   // do while loop = always executes a block of code once, THEN checks a condition

   int number = 0;
   int sum = 0;

   do{
      printf("Enter a # above 0: ");
      scanf("%d", &number);
      if(number > 0)
      {
         sum += number;
      }
   }while(number > 0);
   
   printf("sum: %d", sum);
 
   return 0;
}*/






/*int main()
{
   //nested loop = a loop inside of another loop

   int rows;
   int columns;
   char symbol;

   printf("\nEnter # of rows: ");
   scanf("%d", &rows);

   printf("Enter # of columns: ");
   scanf("%d", &columns);

   scanf("%c"); //clears \n from buffer

   printf("Enter a symbol to use: ");
   scanf("%c", &symbol);

   for(int i = 1; i <= rows; i++)
   {
      for(int j = 1; j <= columns; j++)
      {
         printf("%d", j);
      }
      printf("\n");
   }

   return 0;
}*/

    return 0;
}*/










#include<stdio.h>
#include<string.h>
#include<stdlib.h>
#include<time.h>
//int main()
/*{
   // continue = skips rest of code & forces the next iteration of the loop
   // break = exits a loop/switch

   for(int i = 1; i <= 20; i++)
   {
      if(i == 13)
      {
         //continue;
         break;
      }
      printf("%d\n", i);
   }
  
   return 0;
}*/





/*{
   // array = a data structure that can store many values of the same data type.

   //double prices[] = {5.0, 10.0, 15.0, 25.0, 20.0};
   double prices[5];

   prices[0] = 5.0;
   prices[1] = 10.0;
   prices[2] = 15.0;
   prices[3] = 25.0;
   prices[4] = 20.0;

   printf("$%.2lf", prices[5]);
  
   return 0;
}*/





/*{

   double prices[] = {5.0, 10.0, 15.0, 25.0, 20.0, 30.0};
   
   //printf("%d bytes\n", sizeof(prices));

   for(int i = 0; i < sizeof(prices)/sizeof(prices[0]); i++)
   {
      printf("$%.2lf\n", prices[i]);
   }

   return 0;
}*/






/*{
   // 2D array = an array, where each element is an entire array
   //            useful if you need a matrix, grid, or table of data
   /*
   int numbers[2][3] = {
                        {1, 2, 3},
                        {4, 5, 6}
                       };
   */
  /*int numbers[2][3];

   int rows = sizeof(numbers)/sizeof(numbers[0]);
   int columns = sizeof(numbers[0])/sizeof(numbers[0][0]);

   printf("rows: %d\n", rows);
   printf("columns: %d\n", columns);

   numbers[0][0] = 1;
   numbers[0][1] = 2;
   numbers[0][2] = 3;
   numbers[1][0] = 4;
   numbers[1][1] = 5;
   numbers[1][2] = 6;

   for(int i = 0; i < rows; i++)
   {
      for(int j = 0; j < columns; j++)
      {
         printf("%d ", numbers[i][j]);
      }
      printf("\n");
   }

   return 0;
}*/






/*{
   char cars[][10] = {"Mustang","Corvette","Camaro"};

   //cars[0] = "Tesla";
   strcpy(cars[0], "Tesla");

   for(int i = 0; i < sizeof(cars)/sizeof(cars[0]); i++)
   {
      printf("%s\n", cars[i]);
   }

   return 0;
}*/




/*{ 
   //------- Example 1 -------
   //char x = 'X';
   //char y = 'Y';
   //char temp;

   //temp = x;
   //x = y;
   //y = temp;

   //printf("x = %c\n", x);
   //printf("y = %c\n", y);

   //------- Example 2 -------
   char x[15] = "water";
   char y[15] = "soda";
   char temp[15];

   strcpy(temp, x);
   strcpy(x, y);
   strcpy(y, temp);

   printf("x = %s\n", x);
   printf("y = %s\n", y);
 
   return 0; 
}*/







/*void sort(char array[], int size)
{
   for(int i = 0; i < size - 1; i++)
   {
      for(int j = 0; j < size - i - 1; j++)
      {
         if(array[j] > array[j+1])
         {
            int temp = array[j];
            array[j] = array[j+1];
            array[j+1] = temp;
         }
      }
   }
}

void printArray(char array[], int size)
{
   for(int i = 0; i < size; i++)
   {
      printf("%c ", array[i]);
   }
}

int main()
{ 
   //int array[] = {9, 1, 8, 2, 7, 3, 6, 4, 5};
   char array[] = {'F', 'A', 'D', 'B', 'C'};
   int size = sizeof(array)/sizeof(array[0]);

   sort(array, size);
   printArray(array, size);
 
   return 0; 
}*/







/*struct Player
{
   char name[12];
   int score;
};

int main()
{
   // struct = collection of related members ("variables") 
   //          they can be of different data types
   //          listed under one name in a block of memory
   //          VERY SIMILAR to classes in other languages (but no methods)

   struct Player player1;
   struct Player player2;

   strcpy(player1.name
, "Bro");
   player1.score = 4;

   strcpy(player2.name
, "Bra");
   player2.score = 5;

   printf("%s\n", player1.name);
   printf("%d\n", player1.score);

   printf("%s\n", player2.name);
   printf("%d\n", player2.score);

   return 0;
}*/






/*//typedef char user[25];

typedef struct
{
   char name[25];
   char password[12];
   int id;
} User;

int main() 
{
   // typedef = reserved keyword that gives an existing datatype a "nickname"

   User user1 = {"Bro", "password123", 123456789};
   User user2 = {"Bruh", "password321", 987654321};

   printf("%s\n", user1.name);
   printf("%s\n", user1.password);
   printf("%d\n", user1.id);
   printf("\n");
   printf("%s\n", user2.name);
   printf("%s\n", user2.password);
   printf("%d\n", user2.id);

   return 0; }*/







/*struct Student
{
   char name[12];
   float gpa;
};

int main()
{
   struct Student student1 = {"Spongebob", 3.0};
   struct Student student2 = {"Patrick", 2.5};
   struct Student student3 = {"Sandy", 4.0};
   struct Student student4 = {"Squidward", 2.0};

   struct Student students[] = {student1, student2, student3, student4};

   for(int i = 0; i < sizeof(students)/sizeof(students[0]); i++)
   {
      printf("name:%-12s\t", students[i].name);
      printf("gpa: %.2f\n", students[i].gpa);
   }

   return 0;
}*/  





/*enum Day{Sun = 1, Mon = 2, Tue = 3, Wed = 4, Thu = 5, Fri = 6, Sat = 7};

int main()
{
   // enum = a user defined type of named integer identifiers
   //               helps to make a program more readable

   enum Day today;
   today = Sun;

   if(today == Sun || today == Sat)
   {
      printf("\nIt's the weekend! Party time!");
   }
   else
   {
      printf("\nI have to work today :(");
   }
 
   return 0;
}*/






/*int main()
{
   //pseudo random numbers = A set of values or elements that is statistically random
   //                        (Don't use these for any sort of cryptographic security)
 
   // Use current time as a seed for random # generator
   srand(time(0));
 
   // rand() generates a pseudo random # between 0 - 32,767
   int number1 = (rand() % 6) + 1;
   int number2 = (rand() % 6) + 1;
   int number3 = (rand() % 6) + 1;
 
   printf("%d\n", number1);
   printf("%d\n", number2);
   printf("%d\n", number3);
 
   return 0;
}*/





/*int main()
{
   // BITWISE OPERATORS = special operators used in bit level programming
   //                                          (knowing binary is important for this topic)

   // & = AND
   // | = OR
   // ^ = XOR
   // <<  left shift
   // >>  right shift

   int x = 6;  //    6 = 00000110
   int y = 12; // 12 = 00001100 
   int z = 0;  //    0 = 00000000

   z = x & y;
   printf("AND = %d\n", z);

   z = x | y;
   printf("OR = %d\n", z);

   z = x ^ y;
   printf("XOR = %d\n", z);

   z = x << 2;
   printf("SHIFT LEFT = %d\n", z);

   z = x >> 2;
   printf("SHIFT RIGHT = %d\n", z);

   return 0;
}*/






/*int main()
{
   // memory = an array of bytes within RAM (street)
   // memory block = a single unit (byte) within memory (house), used to hold some value (person)
   // memory address = the address of where a memory block is located (house address)

   char a;
   char b[1];

   printf("%d bytes\n", sizeof(a));
   printf("%d bytes\n", sizeof(b));

   printf("%p\n", &a);
   printf("%p\n", &b);

   return 0;
}*/



