#include <stdio.h>

int main() {
    float F, C;
    printf("Enter a Temp of Fahrenheit: ");
    scanf("%f", &F); // Use %f for reading a float value.
    
    C = 5 * (F - 32) / 9;
    printf("%f is the Temp of Celsius", C);

    return 0;
}
