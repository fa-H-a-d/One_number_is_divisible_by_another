#include <stdio.h>

int main() {
    int num1, num2;

    // Input the two numbers
    printf("Enter the first number: ");
    scanf("%d", &num1);

    printf("Enter the second number: ");
    scanf("%d", &num2);

    // Check if num1 is divisible by num2
    if (num2 != 0 && num1 % num2 == 0) {
        printf("%d is divisible by %d.\n", num1, num2);
    } else {
        printf("%d is not divisible by %d.\n", num1, num2);
    }

    return 0;
}
