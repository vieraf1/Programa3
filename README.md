# Programa 3

Linguagem Utilizada: C++.

Programa que faz a leitura de dois números e retorna a média entre eles.

Programa Desenvolvido no Dev C++.

Código:

#include "iostream"
#include "cstdlib"
#include "math.h"
using namespace std;

int main() {
    float no1, no2, media;
    
    system("cls");
    cout << "Programa media: \n" << endl;
    cout << "Digite nota 1: "; cin >> no1;
    cout << "\nDigite nota 2: "; cin >> no2;
    
    media = (no1 + no2)/2;
    
    cout << "\nMedia: " << media << endl << endl;
    
    system("pause");
    system("cls");
    
    if(media < 6){
        cout << "\nReprovado...\n\n";
             }
    else {
        cout << "\nAprovado!!!\n\n";
    }
    system("pause");
    
    return 0; }
    
