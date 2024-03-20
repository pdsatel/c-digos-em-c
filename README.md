#include <iostream>
#include <stdio.h>
#include <stdlib.h>
#include <math.h>
#include <string.h>
#include <locale.h>
#include  <cmath>
using namespace std;


int main()
{
	setlocale(LC_ALL,"Portuguese");
int raio;
float perim,area,PI;
PI = 3.14159;

cout <<"escreva o valor do raio:";
cin >>raio;
	perim = 2 * PI * raio;
area = PI * pow(raio,2) ;
cout<<"O perimetrro da circuferencia do raio é "<<perim;
cout<<"e a area é ",area;
