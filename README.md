#include <stdio.h>
#include <locale.h>

int main(){
    setlocale(LC_ALL,"");
    float velociade, distancia, tempo;
    
    printf("digite a velociade do carro");
    scanf("%f", &velociade);
    
    printf("digite a distancia a ser percorrida em KM: ");
    
    
    tempo = distancia / velociade;
    
    printf("o tempo necessario para percorrer %.2f km %.2f horas/n", distancia, tempo);
    
    return 0;
}
