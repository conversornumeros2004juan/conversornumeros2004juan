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

    
