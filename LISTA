#include <iostream> // BIBLIOTECA IOSTEAM
#include <list>      // BIBLIOTECA LISTA EN STL
#include <algorithm> // LIBRERIA ALGORITMO COMPONENTE DEL STL

using namespace std;

int main()
{
    list<int>  l;           //LISTA CON CARATERES DE TIPO ENTERO CON NOMBRE L
    l.push_back(0);             // MARCA EL INICIO DE LA LISTA
    for(int i=0;i<10;i++){      ////SE PONE UN FOR PARA OBTENER LOS VALORES DE LA LISTA
        l.push_back(i+1); // INTRODUCE VALORES AL FINAL DE LA LISTA
    }
    list<int>::iterator itr=find(l.begin(),l.end(),8); // ENCONTRAR
    l.insert(itr,5); // SE INSERTA EL VALOR 5
    itr=find(l.begin(),l.end(),7); // CAMBIANDOLO POR EL VALOR 7
    l.erase(itr); // BORRA EL VALOR CAMBIADO

    for(list<int>::iterator it=l.begin();it!=l.end();it++){ // FOR PARA EMPEZAR LA IMPRECION DE LOS VALORES DE LA LISTA
        cout<<*it<<endl; // MUESTRA LA LISTA
    }
    cout << "GRACIAS" << endl;
    return 0;
}
