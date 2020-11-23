//1. Colocar el numero de elementos con constantes 
//#define MAX 100

#include "stdafx.h"
#include <iostream>
#include "conio.h"
#define MAX 100

using namespace std;

double promedio (double a[], int tamanio);

int main ()
{
	double x[MAX];
	cout<<"Ingrese 5 valores: "<<endl;
	for (int i=0; i<5; i++)
	{
		cout<<"valor: "<<endl;
		cin>>x[i];
	}
	
	cout<<"El promedio es: "<<promedio(x, 5)<<endl;
	getch();
	return 0;
}

double promedio (double a[], int tamanio)
{
	double suma=0;
	for (int i=0; i<tamanio; i++)
	{
		suma=suma+a[i];
	}
	return suma/tamanio;
}
