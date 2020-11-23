//Ejercicio Mostrar y Cargar Vectores

#include "stdafx.h"
#include <iostream>
#include "conio.h"
#define MAX 100		//Variable global.

using namespace std;

void cargarVector(int vecX[], int x);		//Parametro x.
void mostrarVector(int vecX[], int x);

int main ()
{
	int n, vec[100];
	cout<<"Ejercicio de Vectores"<<endl;
	cout<<"Ingrese el tamaño del vector: "<<endl;
	cin>>n;

	cargarVector(vec, n);
	mostrarVector(vec, n);
	getch ();
	return 0;
	
}

void cargarVector(int vecX[], int x)
{
	for (int i=0; i<x; i++)
	{
		cout<<"Ingrese el valor en la posición vec["<<i<<"]: "<<endl; //Vec[i] posicion del vector donde se almacena los valores.
		cin>>vecX[i];
	}
}

void mostrarVector(int vecX[], int x)
{
	for (int i=0; i<x; i++)
	{
		cout<<"vec["<<i<<"]="<<vecX[i]<<endl;
	}
}
