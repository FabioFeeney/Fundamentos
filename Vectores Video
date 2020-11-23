//	Escribe un programa que lea la entrada estandar de un vector de numeros y
//	muestre en la salida estandar, los numeros del vector con sus indices asociados.

#include "stdafx.h"
#include "conio.h"
#include <iostream>

using namespace std;

void Guardar(int numeros[], int n);
void Mostrar(int numeros[], int n);

int main ()
{
	int numeros[100], n;
	cout<<"Digite el numero de elementos que va a tener el arreglo"<<endl;
	cin>>n;

	Guardar(numeros, n);
	cout<<"El orden de los elementos es: "<<endl;
	Mostrar(numeros, n);

	getch();
	return 0;
}

void Guardar(int numeros[], int n)
{
	for(int i=0; i<n; i++)
	{
		cout<<"Digite un numero: "<<endl;
		cin>>numeros[i];					//Guarda los elementos del vector
	}
}

void Mostrar(int numeros[], int n)
{
	for(int i=0; i<n; i++)
	{
		cout<<i<<"-->"<<numeros[i]<<endl;
	}
}
