/*	Dado un número combinatorio con parámetros n y r, 
	obtener su valor numérico. Un número combinatorio se 
	define de la siguiente forma:
						         n!
	Combi (n, r) = -----------
					        r!(n-r)!
*/

#include "stdafx.h"
#include <iostream>
#include "conio.h"

using namespace std;

int Combi (int n, int r); 

int main ()
{
	int n, r, respuesta;
	cout<<"Dado los parametros n y r, obtener un numero combinatorio"<<endl;
	cout<<"Ingrese n: "<<endl;
	cin>>n;
	cout<<"Ingrese r: "<<endl;
	cin>>r; 

	respuesta=Combi (n, r);
	cout<<"El resultado es: "<<respuesta<<endl;
	getch ();
	return 0;
}

int Combi (int n, int r)
{
	int factorial=1, fact=1, fa=1, Combinacion; 
	for (int i=1; i<=n; i++)			//n!
	{
		factorial = factorial*i;
	}
	for (int j=1; j<=r; j++)			//r!
	{
		fact=fact*j; 
	}
	for (int k=1; k<=n-r; k++)			//(n-r)!
	{
		fa=fa*k;
	}
	Combinacion=factorial/(fact*fa);
	return Combinacion;
}
