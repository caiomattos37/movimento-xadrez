#include <stdio.h>

int main() {

    // ==============================
    //   MOVIMENTO DA TORRE (FOR)
    // ==============================
    int casasTorre = 5;
    printf("=== Movimento da Torre ===\n");

    for(int i = 1; i <= casasTorre; i++) {
        printf("Direita\n"); // Torre anda apenas em linha reta
    }

    // ==============================
    //   MOVIMENTO DO BISPO (WHILE)
    // ==============================
    int casasBispo = 5;
    int contador = 1;
    printf("\n=== Movimento do Bispo ===\n");

    while(contador <= casasBispo) {
        printf("Cima, Direita\n"); // Bispo anda em diagonal
        contador++;
    }

    // ================================
    //   MOVIMENTO DA RAINHA (DO-WHILE)
    // ================================
    int casasRainha = 8;
    int j = 1;
    printf("\n=== Movimento da Rainha ===\n");

    do {
        printf("Esquerda\n"); // Rainha pode andar em todas direções
        j++;
    } while(j <= casasRainha);

    return 0;
}
