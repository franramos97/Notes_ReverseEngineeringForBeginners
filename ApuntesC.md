# Punteros

Un puntero es una variable cuyo valor es la dirección de otra variable. Nomenclatura: `type *var-name`. Ejemplos:

`` 
int *ip #puntero de tipo int llamado 'ip'
char *ch #puntero de tipo char llamado 'ch'

int main () {

  int var = 20;
  int *ip;
  
  ip = &var; #guardo en 'ip' la dirección de memoria de 'var'
  
  printf("DIRECCIÓN de memoria de var: %x", &var); #bffd9bc3
  printf("DIRECCIÓN guardada en variable ip: %x", ip); #bffd9bc3
  printf("Acceso al VALOR usando el puntero: %d", *ip); #20
  


