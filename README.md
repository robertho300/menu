
#include <stdio.h>
#include <stdlib.h>
#include <string.h>
#include <windows.h>
void main()
{

    int categoria;
    int marca;
    int modelo;
    int principal;
    int secundario;
    int tercero;
    char buscar[21];

    do
    {
        system("cls");
        system("color 4");
    principal=0;
    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
    printf("%c                           %c\n",186,186);
    printf("%c                           %c\n",186,186);
    printf("%c    Menu  Principal        %c\n",186,186);
    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
    printf("%c                           %c\n",186,186);
    printf("%c       Vehiculo            %c\n",186,186);
    printf("%c                           %c\n",186,186);
    printf("%c 1\) Automovil              %c\n",186,186);
    printf("%c 2\) Motocicleta            %c\n",186,186);
    printf("%c 3\) Buscar modelo          %c\n",186,186);
    printf("%c 4\) Salir                  %c\n",186,186);
    printf("%c                           %c\n",186,186);
    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
    scanf("%d",&categoria);

    switch (categoria)
        {
        case 1:

            do
            {
                system("cls");
                system("color 3");
            secundario=0;
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
            printf("%c                           %c\n",186,186);
            printf("%c                           %c\n",186,186);
            printf("%c       Automovil           %c\n",186,186);
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
            printf("%c                           %c\n",186,186);
            printf("%c          Marca            %c\n",186,186);
            printf("%c                           %c\n",186,186);
            printf("%c 1\) Ferrari                %c\n",186,186);
            printf("%c 2\) Lamborghini            %c\n",186,186);
            printf("%c 3\) Mclaren                %c\n",186,186);
            printf("%c 4\) koenigsegg             %c\n",186,186);
            printf("%c 5\) Tesla                  %c\n",186,186);
            printf("%c 6\) Atras                  %c\n",186,186);
            printf("%c                           %c\n",186,186);
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
            scanf("%d", &marca);
            switch (marca)
                {
//Eva
                case 1:
                    do
                    {
                    tercero=0;
                    system("cls");
                    system("color 7");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                           %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c       Ferrari             %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);printf("%c                           %c\n",186,186);
                    printf("%c          Modelos          %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c 1\) 599 GTO                %c\n",186,186);
                    printf("%c 2\) Laferrari              %c\n",186,186);
                    printf("%c 3\) Atras                  %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    scanf("%d", &modelo);
                    switch (modelo)
                    {
                        case 1:
                            system("cls");
                            system("color 2");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                 599 GTO               %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 3.1 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: 6.5 seg     %c\n",186,186);
                            printf("%c Velocidad maxima: 305 km/h            %c\n",186,186);
                            printf("%c (limitada electronicamente)           %c\n",186,186);
                            printf("%c Frenado de 100-0km/h en 32.5 metros   %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 2:
                            system("cls");
                            system("color 5");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c               LaFerrari               %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 2.5 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: 4.8 seg     %c\n",186,186);
                            printf("%c Velocidad maxima: 351 km/h            %c\n",186,186);
                            printf("%c (estimacion por mfr)                  %c\n",186,186);
                            printf("%c Frenado de 113-0km/h en 20.7 metros   %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 3:
                            secundario=3;
                            break;
                    }
                    }while (tercero==3);
                    break;

                case 2:
                    do
                    {
                        system("cls");
                        system("color 2");
                    tercero=0;
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                           %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c       Lamborghini         %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                           %c\n",186,186);
                    printf("%c          Modelos          %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c 1\) Murcielago LP670-4 SV  %c\n",186,186);
                    printf("%c 2\) Aventador LP750-4 SV   %c\n",186,186);
                    printf("%c 3\) Atras                  %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    scanf("%d", &modelo);
                    switch (modelo)
                    {

                        case 1:
                            system("cls");
                            system("color 1");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c        Murcielago LP670-4 SV          %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 3.2 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: 7.2 seg     %c\n",186,186);
                            printf("%c Velocidad maxima: 309 km/h            %c\n",186,186);
                            printf("%c (aclamado por el fabricante)          %c\n",186,186);
                            printf("%c Frenos: discos de 15 pulgadas         %c\n",186,186);
                            printf("%c de ceramica de carbon con caliper     %c\n",186,186);
                            printf("%c de 6 pistones (100-0km/h no especif.) %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 2:
                            system("cls");
                            system("color 7");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c        Aventador LP 750-4 SV          %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 2.8 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-124 mph: 8.6 seg     %c\n",186,186);
                            printf("%c Velocidad maxima: 350 km/h            %c\n",186,186);
                            printf("%c (aclamado por el fabricante)          %c\n",186,186);
                            printf("%c Frenado de 100-0km/h en 30 metros     %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 3:
                            secundario=3;
                            break;
                    }
                    }while (tercero==3);
                    break;

                case 3:
                    do
                    {
                    tercero=0;
                    system("cls");
                    system("color 4");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                           %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c         Mclaren           %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                           %c\n",186,186);
                    printf("%c          Modelos          %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c 1\) P1                     %c\n",186,186);
                    printf("%c 2\) 12C spider             %c\n",186,186);
                    printf("%c 3\) Atras                  %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    scanf("%d", &modelo);
                    switch (modelo)
                    {

                        case 1:
                            system("cls");
                            system("color 9");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                  P1                   %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 2.7 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: 5.1 seg     %c\n",186,186);
                            printf("%c Velocidad maxima: 349 km/h            %c\n",186,186);
                            printf("%c (limitado electronicamente)           %c\n",186,186);
                            printf("%c Frenado 100-0km/h: 2.9 en 30 metros   %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 2:
                            system("cls");
                            system("color 6");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c              12C spider               %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 3.1 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: 6.1 seg     %c\n",186,186);
                            printf("%c Velocidad maxima: 329 km/h            %c\n",186,186);
                            printf("%c (aclamado por el fabricante)          %c\n",186,186);
                            printf("%c Frenado de 100-0km/h en 30.7 metros   %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 3:
                            secundario=3;
                            break;
                    }
                    }while (tercero==3);
                    break;

                case 4:
                    do
                    {
                    tercero=0;
                    system("cls");
                    system("color 1");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                           %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c       Koenigsegg          %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                           %c\n",186,186);
                    printf("%c          Modelos          %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c 1\) One:1                  %c\n",186,186);
                    printf("%c 2\) Agera R                %c\n",186,186);
                    printf("%c 3\) Atras                  %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    scanf("%d", &modelo);
                    switch (modelo)
                    {
                        case 1:
                            system("cls");
                            system("color 8");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                One:1                  %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-400km/H: 20 seg      %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: no especif. %c\n",186,186);
                            printf("%c Velocidad maxima: 439 km/h            %c\n",186,186);
                            printf("%c (teoricamente segun el fabricante)    %c\n",186,186);
                            printf("%c Frenado 100-0km/h: 28 metros          %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 2:
                            system("cls");
                            system("color 3");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c               Agera R                 %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 2.8 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-124 mph: 7.8 seg     %c\n",186,186);
                            printf("%c Velocidad maxima: 439 km/h            %c\n",186,186);
                            printf("%c (maxima alcanzada hasta el momento)   %c\n",186,186);
                            printf("%c Frenado 100-0km/h: 30.5 metros        %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 3:
                            secundario=3;
                            break;
                    }
                    }while (tercero==3);
                    break;
                case 5:
                    do
                    {

                    tercero=0;
                    system("cls");
                    system("color 2");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                           %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c          Tesla            %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                           %c\n",186,186);
                    printf("%c          Modelos          %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c 1\) Model S P85D           %c\n",186,186);
                    printf("%c 2\) Model X                %c\n",186,186);
                    printf("%c 3\) Atras                  %c\n",186,186);
                    printf("%c                           %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    scanf("%d", &modelo);
                    switch (modelo)
                    {
                        case 1:
                            system("cls");
                            system("color 8");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c               Model S P85D            %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 3.1 seg     %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: no especif. %c\n",186,186);
                            printf("%c Velocidad maxima: 249 km/h            %c\n",186,186);
                            printf("%c (limitada electronicamente)           %c\n",186,186);
                            printf("%c Frenado 100-0km/h: no especificado    %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 2:
                            system("cls");
                            system("color 3");
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                            printf("%c                                       %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c               Model X                 %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                            printf("%c                                       %c\n",186,186);
                            printf("%c Aceleracion de 0-100km/H: 5 seg       %c\n",186,186);
                            printf("%c Aceleracion de 0-100 mph: no especif. %c\n",186,186);
                            printf("%c Velocidad maxima: 249 km/h            %c\n",186,186);
                            printf("%c (aproximada)                          %c\n",186,186);
                            printf("%c Frenado 100-0km/h: no especificado    %c\n",186,186);
                            printf("%c                                       %c\n",186,186);
                            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                            getch();
                            tercero=3;
                            break;
                        case 3:
                            secundario=3;
                        break;
                    }
                    }while (tercero==3);
            case 6:
                    principal=6;
                    break;
                }
            }while (secundario==3);
            break;

        case 2:
            do
            {
            secundario=0;
            system("cls");
            system("color 6");
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
            printf("%c                           %c\n",186,186);
            printf("%c                           %c\n",186,186);
            printf("%c      Motocicleta          %c\n",186,186);
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
            printf("%c                           %c\n",186,186);
            printf("%c          Marca            %c\n",186,186);
            printf("%c                           %c\n",186,186);
            printf("%c 1\) Ducati                 %c\n",186,186);
            printf("%c 2\) Honda                  %c\n",186,186);
            printf("%c 3\) Yamaha                 %c\n",186,186);
            printf("%c 4\) Suzuki                 %c\n",186,186);
            printf("%c 5\) Kawasaki               %c\n",186,186);
            printf("%c 6\) Atras                  %c\n",186,186);
            printf("%c                           %c\n",186,186);
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
            scanf("%d",&marca);
            switch (marca)
                {
//demon
                    case 1:
                        do
                        {
                        tercero=0;
                        system("cls");
                        system("color 2");
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                        printf("%c                           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Ducati           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Modelo           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c 1\) Monster 821            %c\n",186,186);
                        printf("%c 2\) Streetfighter 848      %c\n",186,186);
                        printf("%c 3\) Atras                  %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                        scanf("%d",&modelo);
                        switch (modelo)
                        {
                            case 1:
                                system("cls");
                                system("color 9");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c               Monster 821             %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 112 hp a 9,500 RPM   %c\n",186,186);
                                printf("%c Torque maximo: 89.4 Nm a 7750 RPM     %c\n",186,186);
                                printf("%c Relacion de compresion: 12.8:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso con todos los liquidos: 205.5 kg %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                            break;
                            case 2:

                                system("cls");
                                system("color 1");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c             Streetfighter 848         %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 132 hp a 10,000 RPM  %c\n",186,186);
                                printf("%c Torque maximo: 93.5 Nm a 9500 RPM     %c\n",186,186);
                                printf("%c Relacion de compresion: 13.2:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso con todos los liquidos: 199 kg   %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                            break;
                            case 3:
                                secundario=3;
                                break;
                        }
                        }while (tercero==3);
                        break;

                    case 2:
                        do
                        {
                        tercero=0;
                        system("cls");
                        system("color 5");
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                        printf("%c                           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c            Honda          %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Modelo           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c 1\) Shadow 750             %c\n",186,186);
                        printf("%c 2\) CRF450X                %c\n",186,186);
                        printf("%c 3\) Atras                  %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                        scanf("%d",&modelo);
                        switch (modelo)
                        {
                            case 1:
                                system("cls");
                                system("color 8");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                Shadow 750             %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 45.19 hp a 5,500 RPM %c\n",186,186);
                                printf("%c Torque maximo: 64.2 Nm a 3000 RPM     %c\n",186,186);
                                printf("%c Relacion de compresion: 9.6:1         %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso en seco: 237.9 kg                %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 2:
                                system("cls");
                                system("color 5");

                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                 CRF450X               %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 44.8 hp a 7,500 RPM  %c\n",186,186);
                                printf("%c Torque maximo: 43 Nm a 7000 RPM       %c\n",186,186);
                                printf("%c Relacion de compresion: 12.0:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso con todos los liquidos: 118 kg   %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 3:
                                secundario=3;
                                break;
                        }
                        }while (tercero==3);
                        break;

                    case 3:
                        do
                        {
                        tercero=0;
                        system("cls");
                        system("color 2");
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                        printf("%c                           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Yamaha           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Modelo           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c 1\) XJ6 Diversion S        %c\n",186,186);
                        printf("%c 2\) YZF R1                 %c\n",186,186);
                        printf("%c 3\) Atras                  %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                        scanf("%d",&modelo);
                        switch (modelo)
                        {
                            case 1:
                                system("cls");
                                system("color 3");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c              XJ6 Diversion S          %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 78 hp a 10,000 RPM   %c\n",186,186);
                                printf("%c Torque maximo: 59.7 Nm a 8500 RPM     %c\n",186,186);
                                printf("%c Relacion de compresion: 12.2:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso en seco: 211 kg                  %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 2:
                                system("cls");
                                system("color 7");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                YZF R1                 %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 152 hp a 10,500 RPM  %c\n",186,186);
                                printf("%c Torque maximo: 104.9 Nm a 8500 RPM    %c\n",186,186);
                                printf("%c Relacion de compresion: 11.8:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso con todos los liquidos: 192 kg   %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 3:
                                secundario=3;
                                break;
                        }
                        }while (tercero==3);
                        break;
                    case 4:
                        do
                        {
                        tercero=0;
                        system("cls");
                        system("color 9");
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                        printf("%c                           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Suzuki           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Modelo           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c 1\) GSX-R 750              %c\n",186,186);
                        printf("%c 2\) GSX1300R Hayabusa      %c\n",186,186);
                        printf("%c 3\) Atras                  %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                        scanf("%d",&modelo);
                        switch (modelo)
                        {
                            case 1:
                                system("cls");
                                system("color 8");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                 GSX-R 750             %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 148 hp a 12,800 RPM  %c\n",186,186);
                                printf("%c Torque maximo: 86.3 Nm a 11,200 RPM   %c\n",186,186);
                                printf("%c Relacion de compresion: 12.5:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso en seco: 163 kg                  %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 2:
                                system("cls");
                                system("color 1");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c             GSX1300R Hayabusa         %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 195.7 hp a 9,800 RPM %c\n",186,186);
                                printf("%c Torque maximo: 154.9 Nm a 10,200 RPM  %c\n",186,186);
                                printf("%c Relacion de compresion: 12.5:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso con todos los liquidos: 266 kg   %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 3:
                                secundario=3;
                                break;
                        }
                        }while (tercero==3);
                        break;

                    case 5:
                        do
                        {
                        tercero=0;
                        system("cls");
                        system("color 1");
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                        printf("%c                           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Kawasaki         %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                        printf("%c                           %c\n",186,186);
                        printf("%c          Modelo           %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c 1\) Ninja 650R             %c\n",186,186);
                        printf("%c 2\) ER6N                   %c\n",186,186);
                        printf("%c 3\) Atras                  %c\n",186,186);
                        printf("%c                           %c\n",186,186);
                        printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                        scanf("%d",&modelo);
                        switch (modelo)
                        {
                            case 1:
                                system("cls");
                                system("color 6");

                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c               Ninja 650R              %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 72 hp a 8,500 RPM    %c\n",186,186);
                                printf("%c Torque maximo: 66 Nm a 7000 RPM       %c\n",186,186);
                                printf("%c Relacion de compresion: 11.3:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso con todos los liquidos: 208 kg   %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 2:
                                system("cls");
                                system("color 9");
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c                  ER6N                 %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                                printf("%c                                       %c\n",186,186);
                                printf("%c Potencia Maxima: 72.1 hp a 8,500 RPM  %c\n",186,186);
                                printf("%c Torque maximo: 66 Nm a 7000 RPM       %c\n",186,186);
                                printf("%c Relacion de compresion: 11.3:1        %c\n",186,186);
                                printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                                printf("%c Peso con todos los liquidos: 196 kg   %c\n",186,186);
                                printf("%c                                       %c\n",186,186);
                                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                                getch();
                                tercero=3;
                                break;
                            case 3:
                                secundario=3;
                                break;
                        }
                        }while (tercero==3);
                        break;
                    case 6:
                        principal=6;
                        break;
                    }
            }while (secundario==3);
            break;
        case 3:
            do
            {
            secundario=0;
            system("cls");
            system("color 3");
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
            printf("%c        Ingresa el modelo:             %c\n",186,186);
            printf("%c                                       %c\n",186,186);
            printf("%c                                       %c\n",186,186);
            printf("%c                                       %c\n",186,186);
            printf("%c                                       %c\n",186,186);
            printf("%c                                       %c\n",186,186);
            printf("%c                                       %c\n",186,186);
            printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
            fflush(stdin);
            scanf("%[^\n]s",buscar);
            if (strcmp(buscar,"599")==0 || strcmp(buscar,"599 GTO")==0)
                {
                    system("cls");
                    system("color 7");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c            Ferrari 599 GTO            %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 3.1 seg     %c\n",186,186);
                    printf("%c Aceleracion de 0-100 mph: 6.5 seg     %c\n",186,186);
                    printf("%c Velocidad maxima: 305 km/h            %c\n",186,186);
                    printf("%c (limitada electronicamente)           %c\n",186,186);
                    printf("%c Frenado de 100-0km/h en 32.5 metros   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"LaFerrari")==0 || strcmp(buscar,"laferrari")==0 || strcmp(buscar,"Laferrari")==0)
                {
                    system("cls");
                    system("color 2");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c               LaFerrari               %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 2.5 seg     %c\n",186,186);
                    printf("%c Aceleracion de 0-100 mph: 4.8 seg     %c\n",186,186);
                    printf("%c Velocidad maxima: 351 km/h            %c\n",186,186);
                    printf("%c (estimacion por mfr)                  %c\n",186,186);
                    printf("%c Frenado de 113-0km/h en 20.7 metros   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Murcielago")==0 || strcmp(buscar,"murcielago")==0)
                {
                    system("cls");
                    system("color 5");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c        Murcielago LP670-4 SV          %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                printf("%c Aceleracion de 0-100km/H: 3.2 seg     %c\n",186,186);
                printf("%c Aceleracion de 0-100 mph: 7.2 seg     %c\n",186,186);
                printf("%c Velocidad maxima: 309 km/h            %c\n",186,186);
                printf("%c (aclamado por el fabricante)          %c\n",186,186);
                printf("%c Frenos: discos de 15 pulgadas         %c\n",186,186);
                printf("%c de ceramica de carbon con caliper     %c\n",186,186);
                printf("%c de 6 pistones (100-0km/h no especif.) %c\n",186,186);
                printf("%c                                       %c\n",186,186);
                printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                getch();
                secundario=3;
                }
            else if (strcmp(buscar,"Aventador")==0 || strcmp(buscar,"aventador")==0)
                {
                    system("cls");
                    system("color 2");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c        Aventador LP 750-4 SV          %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 2.8 seg     %c\n",186,186);
                    printf("%c Aceleracion de 0-124 mph: 8.6 seg     %c\n",186,186);
                    printf("%c Velocidad maxima: 350 km/h            %c\n",186,186);
                    printf("%c (aclamado por el fabricante)          %c\n",186,186);
                    printf("%c Frenado de 100-0km/h en 30 metros     %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"P1")==0 || strcmp(buscar,"p1")==0)
                {
                    system("cls");
                    system("color 4");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                  P1                   %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 2.7 seg     %c\n",186,186);
                    printf("%c Aceleracion de 0-100 mph: 5.1 seg     %c\n",186,186);
                    printf("%c Velocidad maxima: 349 km/h            %c\n",186,186);
                    printf("%c (limitado electronicamente)           %c\n",186,186);
                    printf("%c Frenado 100-0km/h: 2.9 en 30 metros   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"12C")==0 || strcmp(buscar,"12c")==0)
                {
                    system("cls");
                    system("color 8");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c              12C spider               %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 3.1 seg     %c\n",186,186);
                    printf("%c Aceleracion de 0-100 mph: 6.1 seg     %c\n",186,186);
                    printf("%c Velocidad maxima: 329 km/h            %c\n",186,186);
                    printf("%c (aclamado por el fabricante)          %c\n",186,186);
                    printf("%c Frenado de 100-0km/h en 30.7 metros   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"One:1")==0 || strcmp(buscar,"one:1")==0)
                {
                    system("cls");
                    system("color 5");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                One:1                  %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-400km/H: 20 seg      %c\n",186,186);
                    printf("%c Aceleracion de 0-100 mph: no especif. %c\n",186,186);
                    printf("%c Velocidad maxima: 439 km/h            %c\n",186,186);
                    printf("%c (teoricamente segun el fabricante)    %c\n",186,186);
                    printf("%c Frenado 100-0km/h: 28 metros          %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Agera")==0 || strcmp(buscar,"agera")==0)
                {
                    system("cls");
                    system("color 3");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c               Agera R                 %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 2.8 seg     %c\n",186,186);
                    printf("%c Aceleracion de 0-124 mph: 7.8 seg     %c\n",186,186);
                    printf("%c Velocidad maxima: 439 km/h            %c\n",186,186);
                    printf("%c (maxima alcanzada hasta el momento)   %c\n",186,186);
                    printf("%c Frenado 100-0km/h: 30.5 metros        %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Model S")==0 || strcmp(buscar,"model s")==0)
                {
                    system("cls");
                    system("color 5");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c               Model S P85D            %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 3.1 seg     %c\n",186,186);
                    printf("%c Aceleracion de 0-100 mph: no especif. %c\n",186,186);
                    printf("%c Velocidad maxima: 249 km/h            %c\n",186,186);
                    printf("%c (limitada electronicamente)           %c\n",186,186);
                    printf("%c Frenado 100-0km/h: no especificado    %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Model X")==0 || strcmp(buscar,"model x")==0)
                {
                    system("cls");
                    system("color 2");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c               Model X                 %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Aceleracion de 0-100km/H: 5 seg       %c\n",186,186);
                    printf("%c Aceleracion de 0-100 mph: no especif. %c\n",186,186);
                    printf("%c Velocidad maxima: 249 km/h            %c\n",186,186);
                    printf("%c (aproximada)                          %c\n",186,186);
                    printf("%c Frenado 100-0km/h: no especificado    %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Monster")==0 || strcmp(buscar,"monster")==0)
                {
                    system("cls");
                    system("color 9");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c               Monster 821             %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 112 hp a 9,500 RPM   %c\n",186,186);
                    printf("%c Torque maximo: 89.4 Nm a 7750 RPM     %c\n",186,186);
                    printf("%c Relacion de compresion: 12.8:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso con todos los liquidos: 205.5 kg %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Streetfighter")==0 || strcmp(buscar,"streetfighter")==0)
                {
                    system("cls");
                    system("color 1");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c             Streetfighter 848         %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 132 hp a 10,000 RPM  %c\n",186,186);
                    printf("%c Torque maximo: 93.5 Nm a 9500 RPM     %c\n",186,186);
                    printf("%c Relacion de compresion: 13.2:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso con todos los liquidos: 199 kg   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Shadow")==0 || strcmp(buscar,"shadow")==0)
                {
                    system("cls");
                    system("color 6");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                Shadow 750             %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 45.19 hp a 5,500 RPM %c\n",186,186);
                    printf("%c Torque maximo: 64.2 Nm a 3000 RPM     %c\n",186,186);
                    printf("%c Relacion de compresion: 9.6:1         %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso en seco: 237.9 kg                %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"CRF450X")==0 || strcmp(buscar,"crf450x")==0)
                {
                    system("cls");
                    system("color 1");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                 CRF450X               %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 44.8 hp a 7,500 RPM  %c\n",186,186);
                    printf("%c Torque maximo: 43 Nm a 7000 RPM       %c\n",186,186);
                    printf("%c Relacion de compresion: 12.0:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso con todos los liquidos: 118 kg   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"XJ6")==0 || strcmp(buscar,"xj6")==0)
                {
                    system("cls");
                    system("color 6");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c              XJ6 Diversion S          %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 78 hp a 10,000 RPM   %c\n",186,186);
                    printf("%c Torque maximo: 59.7 Nm a 8500 RPM     %c\n",186,186);
                    printf("%c Relacion de compresion: 12.2:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso en seco: 211 kg                  %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"YZF")==0 || strcmp(buscar,"yzf")==0)
                {
                    system("csl");
                    system("color 8");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                YZF R1                 %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 152 hp a 10,500 RPM  %c\n",186,186);
                    printf("%c Torque maximo: 104.9 Nm a 8500 RPM    %c\n",186,186);
                    printf("%c Relacion de compresion: 11.8:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso con todos los liquidos: 192 kg   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"GSX-R")==0 || strcmp(buscar,"gsx-r")==0)
                {
                    system("cls");
                    system("color 6");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                 GSX-R 750             %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 148 hp a 12,800 RPM  %c\n",186,186);
                    printf("%c Torque maximo: 86.3 Nm a 11,200 RPM   %c\n",186,186);
                    printf("%c Relacion de compresion: 12.5:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso en seco: 163 kg                  %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"GSX1300R")==0 || strcmp(buscar,"gsx1300r")==0)
                {
                    system("cls");
                    system("color 1");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c             GSX1300R Hayabusa         %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 195.7 hp a 9,800 RPM %c\n",186,186);
                    printf("%c Torque maximo: 154.9 Nm a 10,200 RPM  %c\n",186,186);
                    printf("%c Relacion de compresion: 12.5:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso con todos los liquidos: 266 kg   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"Ninja")==0 || strcmp(buscar,"ninja")==0)
                {

                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c               Ninja 650R              %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 72 hp a 8,500 RPM    %c\n",186,186);
                    printf("%c Torque maximo: 66 Nm a 7000 RPM       %c\n",186,186);
                    printf("%c Relacion de compresion: 11.3:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso con todos los liquidos: 208 kg   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else if (strcmp(buscar,"ER6N")==0 || strcmp(buscar,"er6n")==0)
                {
                    system("cls");
                    system("color 4");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                  ER6N                 %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",204,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,185);
                    printf("%c                                       %c\n",186,186);
                    printf("%c Potencia Maxima: 72.1 hp a 8,500 RPM  %c\n",186,186);
                    printf("%c Torque maximo: 66 Nm a 7000 RPM       %c\n",186,186);
                    printf("%c Relacion de compresion: 11.3:1        %c\n",186,186);
                    printf("%c Enfriamiento: Por liquido             %c\n",186,186);
                    printf("%c Peso con todos los liquidos: 196 kg   %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    getch();
                    secundario=3;
                }
            else
                {
                    system("cls");
                    system("color 5");
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n", 201,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,187);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c           Modelo Inexistente          %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c 1\)Volver a intentar                   %c\n",186,186);
                    printf("%c 2\)Atras                               %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c                                       %c\n",186,186);
                    printf("%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c%c\n",200,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,205,188);
                    scanf("%d", &tercero);
                    switch (tercero)
                        {
                            case 1:
                                secundario=3;
                                break;
                            case 2:
                                principal=6;
                                break;
                        }
                }
            fflush(stdin);
            }while (secundario==3);
            break;
        case 4:
            system("cls");
            system("color 3");
            printf("Fin del Programa\n");
            getch();
            break;

    }

    }while (principal==6);
}


