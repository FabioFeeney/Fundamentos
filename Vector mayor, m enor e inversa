//	Escribe un programa que ordene los valores de menor a mayor de un vector

#include "stdafx.h"
#include "conio.h"
#include <iostream>
#define MAX 100

using namespace std;

void cargar(int vec[], int n);
void burbuja(int vec[], int n);	//devuelve clasificado.
void mostrar(int vec[], int n);

void burbuja2(int vec[], int n);
void mostrar2(int vec[], int n);


int main()
{
	int vec[MAX], n, min[MAX];			//Cuando se declara el vector, se declara el tamaño.
	do
	{
		cout<<"Ingrese el tamaño del vector: "<<endl;
		cin>>n;
	}
	while ((n>MAX)||(n<0));

	cargar(vec, n);
	burbuja(vec, n);
	cout<<"El orden del vector es: "<<endl;
	mostrar(vec, n);

	burbuja2(vec, n);
	cout<<"El orden del vector es: "<<endl;
	mostrar2(vec, n);
	
	

	getch ();
}

void cargar(int vec[], int n)
{
	for (int i=0; i<n; i++)
	{
		cout<<"vec["<<i<<"] = ";
		cin>>vec[i];
	}
}

void burbuja(int vec[], int n)
{
	int aux1;
	for (int i=0; i<n-1; i++)
	{
		for (int j=i+1; j<n; j++)
		{
			if (vec[i]>vec[j])
			{
				aux1=vec[j];
				vec[j]=vec[i];
				vec[i]=aux1;
			}
		}
	}

}

void burbuja2(int vec[], int n)
{
	int aux1;
	for (int i=0; i<n-1; i++)
	{
		for (int j=i+1; j<n; j++)
		{
			if (vec[i]<vec[j])
			{
				aux1=vec[j];
				vec[j]=vec[i];
				vec[i]=aux1;
			}
		}
	}
}

void mostrar(int vec[], int n)
{
	for (int i=0; i<n; i++)
	{
		cout<<"vec["<<i<<"] = "<<vec[i]<<endl;
	}
}

void mostrar2(int vec[], int n)
{
	for (int i=0; i<n; i++)
	{
		cout<<"vec["<<i<<"] = "<<vec[i]<<endl;
	}
}
