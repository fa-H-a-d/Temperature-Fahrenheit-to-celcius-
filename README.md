#include <stdio.h>

int main() {
    float F, C;
    printf("Enter a Temp of Fahrenheit: ");
    scanf("%f", &F); 
    
    C = 5 * (F - 32) / 9;
    printf("%f is the Temp of Celsius", C);

    return 0;
}
