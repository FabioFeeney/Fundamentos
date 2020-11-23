#include "stdafx.h"
#include "math.h"
#include <iostream>
#include "conio.h"

using namespace std;

void sumadigitos(int N, int &suma); //int sumadigitos (int N);

void main()
{
	int N, suma=0;
	cout<<"Ingrese el numero: "<<endl;
	cin>>N;
	sumadigitos (N, suma);
	cout<<"La suma de los digitos es: "<<suma<<endl;
	getch();
}

void sumadigitos(int N, int &suma)
{
	int d;
	while(N>0)
	{
		d=N%10;   //3=13%10
		suma=suma+d;
		N=N/10;
	}
}
