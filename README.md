/ # Homework /
/*
 * Author: Fermín
 * fermin112000@gmail.com
 * Created on 22 de agosto de 2018, 09:36 PM
 */
#include <stdio.h>
#include <stdlib.h>

int main()
{
    int num1;
    int num2;
    int mult;
    int suma;
    int division
    int resta;

    printf( "\n   Give me two numbers " );
    printf( "\n   First number: " );
    scanf( "%d", &num1 );
    printf( "\n   Second number: " );
    scanf( "%d", &num2 );

    suma = num1 + num2;
    resta = num1 - num2; 
    mult = num1 * num2;
    division = num1 / num2;
    

    printf( "\n   La suma es: %d", suma );
    printf( "\n La resta es: %d", resta);
    printf( "\n La multiplicacion es: %d", mult );
    printf("\n La division es: %d", division);


    return 0;
}
