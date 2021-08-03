# Area---Peri
// Calculation of area and perimeter of rectangle and circle.


#include<stdio.h>

int main() {

    float ln, bd, r;
    float area_r, peri, area_c, circum;
    
    printf("Enter the Length of the Rectangle:\t");
    scanf("%f",&ln);                                           

    printf("ENter the breadth of the rectangle:\t");
    scanf("%f",&bd);

    printf("Enter the radius of the circle:\t");
    scanf("%f",&r);

    area_r = ln * bd;                  // Area of the rectangle
    peri = 2 * (ln + bd);              // Perimeter of the rectangle
    area_c = 3.14 * r * r;             // Area of the circle
    circum = 2 * 3.14 * r;             // Circumference of the circle

    printf("The area of the rectangle is:\t%.2f\n",area_r);
    printf("The perimeter of the rectangle is:\t%.2f\n",peri);
    printf("The area of the circle is:\t%.2f\n",area_c);
    printf("The circumference of the circle is:\t%.2f\n",circum);

    return 0;
}
