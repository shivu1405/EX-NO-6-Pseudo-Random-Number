# EX-NO-6-Pseudo-Random-Number

# AIM: 
Implementation of Pseudorandom Number Generation Using Standard library

# ALGORITHM:
Start the program and import the required libraries.
Seed the random number generator using the current time(i.e) rand(time(0));
Get the number of randon number to generate.
Pass the value for number of iterations and print the numbers.
End the program.

# PROGRAM:
```
#include <stdio.h>
#include <stdlib.h>
#include <time.h>

int main() 
{
    int i, n;

    // Seed the random number generator
    srand(time(0));

    // Get the number of random numbers to generate
    printf("Enter the number of random numbers to generate: ");
    scanf("%d", &n);

    printf("Generated Random Numbers:\n");

    // Generate and print random numbers
    for(i = 0; i < n; i++) 
    {
        printf("%d\n", rand());
    }

    return 0;
}

```
# OUTPUT:
<img width="1633" height="855" alt="image" src="https://github.com/user-attachments/assets/1b16e0b5-2fab-4bff-a288-d3074f2a6d8f" />


# RESULT:
Thus, the program to generate pseudorandom numbers using the standard C library functions was implemented and executed successfully.
