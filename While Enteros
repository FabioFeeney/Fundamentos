/******************************************************************************
Elaborar un programa que pida al usuario un entero positivo n. Luego, el programa
debe pedir al usuario n enteros usando un ciclo. El programa deberá encontrar el
mayor, menor, y promedio de los valores dados por el usuario e imprimirlos al final.
Entrada: n y enteros
Salida: mayor menor promedio
*******************************************************************************/

#include <iostream>
#include "conio.h"

using namespace std;

int main ()
{
    cout<<"Mayor, menor y promedio de valores."<<endl;
    int n, mayor, menor, i, numero;
    float promedio, suma;
    cout<<"Ingrese n enteros"<<endl; 
    cin>>n;
    i=1;
    suma=0;
    cout<<"Ingrese un valor: "<<endl;
    cin>>numero;
    
    mayor=numero;
    menor=numero;
    
    while (i<=n)
{
    i=i+1;                  //Aumentar el contador.
    suma=suma+numero;       //Acumulador de la suma.
    if (mayor<numero)
        mayor=numero;
                            //Son ifs paralelos.    
    if (menor>numero);
        menor=numero;
    
    if (i<=n)
    {
    cout<<"Ingrese un valor: "<<endl;
    cin>>numero;
    }
}
    cout<<"El mayor es: "<<mayor<<endl;
    cout<<"El menor es: "<<menor<<endl;
    cout<<"El promedio es: "<<suma/n<<endl;
    
    getch();
    return 0;
}
