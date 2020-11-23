#include "stdafx.h"
#include <iostream>
#include "conio.h"
#include "stdlib.h"

using namespace std;

void main()
{
   int a, b,r;
   char opcion;  //Declara opcion como de caracter
   bool bandera=false; // Declara bandera: true o false
   cout << "Ingrese a: " ;
   cin >> a;
   cout << "Ingrese b: " ;
   cin >> b;
   cout << endl;
   do 
   {
	   cout << "a.- Suma" << endl;
	   cout << "b.- Resta" << endl;
	   cout << "c.- Producto" << endl;
	   cout << "d.- División" << endl;
	   cout << "e.- Residuo" << endl;
	   cout << "f.- Salir" << endl;
	   cout << "Elige una opción: " ;
	   cin >> opcion;
	   switch (opcion) {
	   case 'a': r = a + b; break;
	   case 'b': r = a - b; break;
	   case 'c': r = a * b; break;
	   case 'd': r = a / b; break;
	   case 'e': r = a % b; break;
	   case 'f': cout << "Salir";break;
	   default: cout << "Opcion invalida" << endl;
	   }
	   bandera=((opcion=='a') || (opcion=='b')|| (opcion=='c') || (opcion=='d')|| (opcion=='e'));		//bool T o F
	   if (bandera)
		   cout << "El resultado es " << r << endl;
	   getch();
	   system("cls"); // Opcion para limpiar la pantalla
   } 
   while (opcion != 'f');
   getch();
}
