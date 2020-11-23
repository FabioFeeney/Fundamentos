/*	Matrices 
	Diagonal --> Filas y columnas iguales (nxn)
*/

#include "stdafx.h"
#include <iostream>
#include "conio.h"
#define MAX 10

using namespace std; 

void Cargar(int MATRIZ[MAX][MAX], int n, int m);
//void Mostrar(int MATRIZ[MAX][MAX], int n, int m);
void Diagonal(int MATRIZ[MAX][MAX], int n, int m);

void main()
{
	int n, m;
	int MATRIZ[MAX][MAX];
	do
	{
		cout<<"Ingrese el tamaño de la matriz: "<<endl;
		cin>>n;
	}
	while ((n<=0)||(n>MAX));
	do
	{
		cout<<"Ingrese el columnas de la matriz: "<<endl;
		cin>>m;
	}
	while ((m<=0)||(m>MAX));
	if (n==m)
	{
		Cargar(MATRIZ, n, m);
		Diagonal(MATRIZ, n, m);
	}
	else 
	{
		cout<<"No se puede procesar la diagonal porque no es cuadrada."<<endl;
	}

	getch();
}

void Cargar(int MATRIZ[MAX][MAX], int n, int m)
{
	for(int i=0; i<n; i++)
	{
		for(int j=0; j<n; j++)
		{
			cout<<"Ingrese el valor de MATRIZ["<<i<<"]["<<j<<"] = ";
			cin>>MATRIZ[i][j];
		}
	}
}

void Diagonal(int MATRIZ[MAX][MAX], int n, int m)
{
	cout<<"Los elementos de la diagonal son: ";
	for (int i=0; i<n; i++)
	{
		cout<<"Para el elemento ["<<i<<"],["<<i<<"] = ";
		cout<<MATRIZ[i][i]<<endl;
	}

}
