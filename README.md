# Addition
#include <stdio.h>
int main() {    

    int number1, number2, sum;
    
    printf("Enter two integers: ");
    // taking inputs
    scanf("%d %d", &number1, &number2);

    // calculating sum
    sum = number1 + number2;      
    
    // printing outpt i.e. sum of 2 digits
    printf("%d + %d = %d", number1, number2, sum);
    return 0;
}
