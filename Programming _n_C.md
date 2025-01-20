# Low Level VS High Level Languages
Machine Language
Assembly Language
# Language Translators
Assembly Language->**assembler**->machine code
HLL->**Compiler**->machine code  *translation, linking and loading*
HLL->**Interpreter**->output  *easy debugging*
# Features of C Language
1. High Level Language
2. Small Language 32 keywords only
3. Core language
4. Portable
5. Buit in functions and Operators
6. Structured language, Modular
7. Pointers used
8. Extensible
9. Fast Compilation and Execution
10. Dynamic Memory Allocation
11. Case Senstive
12. Embedded System
# Structure of C Program
1. Documentation Section
2. Link Section
3. Definition Section
4. Global Declaration Section
5. Main Function
6. Sub Program Section
```//Author:Asha
/* Program for addition */
#include<stdio.h>
#include<canio.h>
#define MAX 100
int a=15;
void display();
void main(){
  Declaration;
  Executable;
}
void display(){
  printf("Asha");
}
[User defined function]
```
# Execution Process of C Program
# Constants in C
## Numeric
- Integer->Decimal 5.234, Ocatal 05, Hexadecimal 0X7F
- Floating/ Real Constant
## Character
- Single Character Constant
- String Constant
`printf("%d %c",'a',97);`
```
#define A 10;
void main(){
const int a=10;
a=50;

}
```
# Variables in C
```void main(){
clrsrc();
int a=10;
printf("%d",a);
getch();
}
```
# Identifiers and Keywords
32 keywords
Keywords can't be identifiers
# Data types in C
1. Fundamental Data Types including integer, float, double, and character
2. User-Defined Data Types such as structures and unions
# Operators in C
1. Unary->(+5,-5),(++,--),!,&,sizeof
2. Binary->
     - Arithmetic  +,_,*,/,%
     - Relational  <,>,<=,>=
     - Logical  && ,||
     - Bitwise  &,|,<<,>>,^,~  *^->gives 1 if both are different*  *>>->10/2 power n*  *<<->nx10 power a*
     - Equality operator  ==,!=
     - Assignment operator  =
     - Comma operator  ,
3. Ternary  ?=  `expression1?expression2:expression3`
