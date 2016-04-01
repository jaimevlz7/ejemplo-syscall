# ejemplo-syscall
Ejemplo de syscall - Universidad Icesi - Sistemas operativos

#Ejemplo Llamada al sistema

Las llamadas más tipicas de un sistema son:
*Open 
*Read
*Write
*Close
*Wait
*Exec
*Fork
*Exit
*Kill

Para syscl_04 : 

#include<stdio.h>
int main()
{
  printf("Hola, soy un proceso \n");
  fork();
  printf("Fin \n");
}

Llamada al sistema fork()

En un sistema operativo, hace referencia a la creación de una copia de sí mismo por parte de un programa, que entonces actúa como un "proceso hijo" del proceso originario, ahora llamado "padre". Los procesos resultantes son idénticos, salvo que tienen distinto número de proceso.
