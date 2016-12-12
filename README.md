# ecrandeveille
#include <stdio.h>
#include <stdlib.h>

typedef struct log
{
struct tm time; //appel à la fonction tm time pour l'inclure dans les logs
char* additional; /* selon le type de screensaver, contient :
l'image, la taille de l'horloge ou la position initila de l'avion. */
int typesaver; //type de l'image.
}log;

int main()
{
}
