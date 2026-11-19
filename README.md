
#include <stdio.h>
#include <stdlib.h>
#include <windows.h>

void esperar(int segundos) {
    Sleep(segundos * 1000);
}

void mostrarMensaje() {
    system("cls");

    printf("================================\n");
    printf("       SYSTEM SECURITY\n");
    printf("================================\n\n");

    printf("[!] ADVERTENCIA\n");
    esperar(2);

    printf("[!] Actividad sospechosa detectada...\n");
    esperar(2);

    printf("[!] Analizando sistema...\n");
    esperar(2);

    printf("\nSimulacion de infeccion iniciada.\n");
    esperar(3);

    system("cls");

    printf("================================\n");
    printf("          ERA UNA BROMA\n");
    printf("================================\n\n");

    printf("Tu dispositivo esta intacto.\n");
    printf("Este programa solo simula una alerta.\n\n");

    printf("Presiona ENTER para salir...");
    getchar();
}

int main() {
    mostrarMensaje();
    return 0;
}
