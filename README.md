# fallo-coordenadas
fallo de introduccion de cordenadosm  el fallo esta en que el escanf no lee todo los numeros, solo me da 6 decimales cuando son 10
#include <stdio.h>
#include <stdlib.h>

int main(void)
{
    float  a, b;

    printf("{\n");
    printf(" %ctype%c%c %cFeatureCollection%c%c\n", 34, 34, 58, 34,34 ,44);
    printf(" %cfeatures%c: [\n",34 ,34);
    printf("   {\n");
    printf("     %ctype%c: %cFeature%c,\n",34 , 34,34,34);
    printf("     %cproperties%c: {},\n",34 ,34);
    printf("     %cgeometry%c: {\n",34,34);
    printf("       %ctype%C: %cPoint%c,\n",34,34,34,34);
    printf("       %ccoordinates%c: \n",34,34);

    while (scanf("%f , %f [^\n]", &b, &a)==2){

        printf("\t[%f,%f]\n", b, a);
    }
    printf("   }\n");
    printf("  }\n");
    printf(" ]\n");
    printf("}");
    return 0;
}
