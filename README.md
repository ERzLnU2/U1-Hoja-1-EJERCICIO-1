# EJERCICIO-1-Hoja-1
Modificar variables de programa JAVA

/**
 * @author DAW120
 * 📌 EJERCICIO 1, Hoja 1.
 
  • Dado el siguiente programa, modifícalo para utilizar las variables que se indican. 
  
  • El tipo de dato elegido debe ser el de menos bits posibles que puedan representar 
    el valor. Justifica tu elección.
  
    public class Ejercicio1 {
      public static void main(String[ ] args) {
      }
    } 

     🏴 a. Nombre de la variable: casado, Si un empleado está casado o no. 
           Inicializamos con valor verdadero
     🏴 b. Nombre de la variable: MAXIMO, Valor máximo no modificable: 999999.
     🏴 c. Nombre de la variable: diasem, Día de la semana. Inicializamos con 1
     🏴 d. Nombre de la variable: diaanual, Día del año. Inicializamos con 300
     🏴 e. Nombre de la variable: sexo: con dos valores posibles 'V' o 'M'. Inicializamos con ‘M’
     🏴 f. Nombre de la variable: miliseg, Milisegundos transcurridos desde el 01/01/1970 
           hasta nuestros días. Inicializamos con 1298332800000
     🏴 g. Nombre de la variable: totalfactura, Almacenar el total de una factura. 
           Inicializamos con 10350.678
     🏴 h. Nombre de la variable: población, Población mundial del planeta tierra. 
           Inicializamos con 6775235741
 * 
 */
package com.solomongo.ejercicio1_hoja1;
public class Ejercicio1_Hoja1 {
    public static void main(String[] args) { 
         boolean casado=true; 
         final int MAXIMO=999999;
         byte diasem=1;
         short diaanual=300;
         char sexo='M';
         long miliseg = 1298332800000L;
         float totalfactura=10350678f;        
         long poblacion = 6775235741L;   
    }
}
