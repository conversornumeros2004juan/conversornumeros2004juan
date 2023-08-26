// bienvenidos a mi conversor  centimetros.
 
#include <iostream>
using namespace std;
int main (){

    float metros, yardas, varas, pulgadas, pies,centimetros;
    int Opcion;
    float resultado;

    cout<< "te presento mi conversion de numeros, ojo solo se puede convertir centimetros" <<endl;
    cout<< "ingrese una opcion" <<endl;
    cout<< "1.- convertir a metros: " <<endl;
    cout<< "2.- convertir a yardas: " <<endl;
    cout<< "3.-convertir a varas: " <<endl;
    cout<< "4.- convertira  pulgadas:"  <<endl;
    cout<< "5.-convertir a  pies:" <<endl;

    cin>> Opcion;
      
    switch (Opcion)
    {
    case 1: 
        cout<< "centimetros a metros:" <<endl;
        cout<< "ingrese la cantidad en centimetros:" <<endl;
        cin>> centimetros; 
        metros = centimetros / 100;
        cout<< centimetros << " centimetros equivalen a " << metros << " metros: " <<endl;
        break;
    case 2: 
        cout<< "centimetros a yardas: " <<endl;
        cout<< "ingrese la cantidad en centimetros:" <<endl;
        cin>> centimetros;
        yardas = centimetros / 91.44;
        cout<< centimetros<< " centimetros equivalen a " << yardas << " yardas: " <<endl;
        break;
    case 3: 
        cout<< "centimetros a varas: " <<endl;
        cout<< "ingrese la cantidad en centimetros: " <<endl;
        cin>> centimetros;
        varas = centimetros / 84;
        cout<< centimetros<< " centimetros equivalen a " << varas << " varas: " <<endl;
        break;
    case 4: 
        cout<< "centimetros a pulgadas:" <<endl;
        cout<< "ingrese la cantidad en centimetros: " <<endl;
        cin>> centimetros;
        pulgadas = centimetros / 2.54;
        cout<< centimetros<< " centimetros equivalen a " << pulgadas << " pulgadas: " <<endl;
        break;
    case 5: 
        cout<< "centimetros a pies:" <<endl;
        cout<< "ingrese la cantidad en centimetros:" <<endl;
        cin>> centimetros;
        pies = centimetros / 30.48;
        cout<< centimetros<< " centimetros equivalen a " << pies << " pies: " <<endl;
        break;

    default:
        cout<< " te falta poner atencion a las instrucciones, vuelve a intentarlo";
        break;
    }

    return 0;
}





    Algoritmo conversion 
	definir centimetros, metros, yardas, varas, pulgadas, pies como real 
	definir variable como entero 
	escribir " hola, buenas noches compañero"
	escribir "te presento mi conversion de numeros, ojo solo se puede convertir centimetros"
	escribir "elija lo que quiera que los centimetros se coviertan "
	escribir "1-. convertir a metros "
	escribir "2.- convertir a yardas"
	escribir "3.- convertir a varas"
	escribir "4.-convertir a pulgadas"
	escribir "5.-convertir a pies"
	leer variable
	si variable = 1 entonces escribir "usted eligió convertir centimetros a metros"
		escribir "ingrese la cantidad en centimetros"
		leer centimetros 
		metros = centimetros / 100
		escribir " equivalente en metros es " , metros
		fin si 
	si variable = 2 entonces escribir "usted eligio convertir centimetros a yardas"
		escribir "ingrese la cantidad en centimetros"
		leer centimetros 
		yardas = centimetros * 0.0109361
		escribir "equivalente en yardas es " , yardas
	fin si 
	si variable = 3 entonces escribir "usted eligio convertir centimetros a varas"
		escribir "ingrese la cantidad en centimetros"
		leer centimetros 
		varas = centimetros / 84
		escribir "equivalente en varas es " , varas
	FinSi
	si variable = 4 entonces escribir "usted eligio convertir centimetros a pulgadas "
		escribir "ingrese la cantidad en centimetros"
		leer centimetros 
		pulgadas = centimetros * 0.39370
		escribir "equivalente en pulgadas es " , pulgadas
	FinSi
	
	si variable = 5 entonces escribir "usted eligio convertir centimetros a pies "
		escribir "ingrese la cantidad en centimetros"
		leer centimetros 
		pies =  centimetros * 0.0328084
		escribir " equivalente en pies es ", pies
		
	sino escribir "  no prestas atencion a las instrucciones, vuelve a intentarlo"
	FinSi


	
	
	
	
FinAlgoritmo
