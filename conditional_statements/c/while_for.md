# Online C Compiler Example

Run the following C program online to understand how `while` and `for` loops work with a `switch` statement.

```c
#include <stdio.h>

int main() {
    // Write C code here
    int day = 3;
    int i = 1; // Initial value 

    while (i <= 5) {  // condition 
        switch (day) {
            case 1:
                printf("Monday\n");
                break;
            case 2:
                printf("Tuesday\n");
                break;
            case 3:
                printf("Wednesday\n");
                break;
            case 4:
                printf("Thursday\n");
                break;
            case 5:
                printf("Friday\n");
                break;
            default:
                printf("Weekend\n");
        }
        i = i + 1; // increment 
    }

    // [1,2,3,4,5]
    for (int j = 1; j <= 5; j = j + 1) { 
        switch (day) {
            case 1:
                printf("Monday\n");
                break;
            case 2:
                printf("Tuesday\n");
                break;
            case 3:
                printf("Wednesday\n");
                break;
            case 4:
                printf("Thursday\n");
                break;
            case 5:
                printf("Friday\n");
                break;
            default:
                printf("Weekend\n");
        }
    }

    return 0;
}
