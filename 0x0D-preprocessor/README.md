Object-like Macro
mandatory

spades Create a header file that defines a macro named SIZE as an abbreviation for the token 1024. diamonds julien@ubuntu:~/0x0c. macro, structures$ cat 0-main.c

#include "0-object_like_macro.h" #include "0-object_like_macro.h" #include <stdio.h>

/**

main - check the code

Return: Always 0. */ int main(void) { int s;

s = 98 + SIZE; printf("%d\n", s); return (0); } julien@ubuntu:~/0x0c. macro, structures$ ./a 1122

clubs 1. Pi

mandatory

diamonds Create a header file that defines a macro named PI as an abbreviation for the token 3.14159265359.

julien@ubuntu:~/0x0c. macro, structures$ cat 1-main.c

#include "1-pi.h" #include "1-pi.h" #include <stdio.h>

/**

main - check the code
Return: Always 0. */
int main(void) { float a; float r;

r = 98;
a = PI * r * r;
printf("%.3f\n", a);
return (0);
} julien@ubuntu:~/0x0c. macro, structures$ ./b 30171.855

spades 2. File name

mandatory

diamonds Write a program that prints the name of the file it was compiled from, followed by a new line.

You are allowed to use the standard library

julien@ubuntu:~/0x0c. macro, structures$ ./c 2-main.c

clubs 3. Function-like macro

mandatory

diamonds Write a function-like macro ABS(x) that computes the absolute value of a number x.

julien@ubuntu:~/0x0c. macro, structures$ cat 3-main.c

#include <stdio.h> #include "3-function_like_macro.h" #include "3-function_like_macro.h"

/**

main - check the code

Return: Always 0. */ int main(void) { int i; int j;

i = ABS(-98) * 10; j = ABS(98) * 10; printf("%d, %d\n", i, j); return (0); } julien@ubuntu:~/0x0c. macro, structures$ ./d 980, 980

spades 4. SUM

mandatory

diamonds Write a function-like macro SUM(x, y) that computes the sum of the numbers x and y.

julien@ubuntu:~/0x0c. macro, structures$ cat 4-main.c

#include <stdio.h> #include "4-sum.h" #include "4-sum.h"

/**

main - check the code

Return: Always 0. */ int main(void) { int s;

s = SUM(98, 1024); printf("%d\n", s); return (0); } julien@ubuntu:~/0x0c. macro, structures$ ./e 1122
