# Rectangle
//area of rectangle in c programming language
#include <stdio.h>

int main() {
    printf("Calculate the area of a rectangle.\n");

    float length, width;
    
    printf("Enter the length of the rectangle: ");
    scanf("%f", &length);
    
    printf("Enter the width of the rectangle: ");
    scanf("%f", &width);
    
    float area = length * width;
    printf("The area of the rectangle is: %.2f\n", area);
    
    return 0;
}
