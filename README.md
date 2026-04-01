#include <stdio.h>
int main() {
    int a, b, choice;
          printf(“25331A05D6\n”);
printf("Enter two numbers:\n");
    scanf("%d %d", &a, &b);
   printf("Choose operation:\n1. Add\n2. Subtract\n3. Multiply\n4. Divide\n");
    printf("Enter choice:\n");
    scanf("%d", &choice);

    switch(choice) {
        case 1:
            printf("Result = %d\n", a + b);
            break;
        case 2:
            printf("Result = %d\n", a - b);
            break;
        case 3:
            printf("Result = %d\n", a * b);
            break;
        case 4:
            if (b != 0)
                printf("Result = %d\n", a / b);
            else
                printf("Error: Division by zero!\n");
            break;
        default:
            printf("Invalid choice\n");
    }

    return 0;
}
