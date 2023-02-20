# ¿QUE ES JAVA?

* JAVA es un lenguaje de programacion y tecnologia pensada para desarollo de aplicaciones de gran envergadura.

**Tiene caracteristicas que lo diferencias:**

* Lenguaje orientado a objetos
* Es multiplataforma
* Manejo automatico de memoria
* Evolucion permanente 
* Gran demanda en el mercado

### Variables y constantes en JAVA

* Una variable es un nombre que se asocia con una porcion de la memoria de la comptuadora, en la que se guarda un valor determinado
* Las constantes son valores que se mantienen siempre de igual manera y que no dependen de una asignacion para obtener el mismo.

### Tipos de datos en java

* Entero=> **int** 
* Decimales=> **double**
* Booleanos=> **Boolean**
* Caracteres=> **char**
* Cadena de caracteres/texto=> **String**
* Entero Largo=> **long**

#### Declaracion de variables
-  La declaracion de las variables cuenda de dos partes fundamentales:
 int numero; donde "int" es el tipo de dato y "numero" El nombre de la variable.
- Para las variables de tipo **String** se utilizan comillas dobles " ".
- Para las variables de tipo **char** se utilizan comillas simples ' '.

## Ejemplo 
``` Java
        public class Variable{
            public static void main(String[] args) {
                int numero=5;
                String nombre= "hola";
                char letra= 'a';
                double temperatura=5.5;
                boolean siono=false;
                long largo=1212312;
            }
        }
 ```

#### Operadores aritmeticos

* Un operador es un simbolo especial que indica al compilador que debe efectuar una determinada operacion 

**Operadores de java** 

- ARIRTMETICOS: + - * / 
- RELACIONALES: == >,< >=, <= !=
- CONDICIONALES: &&  || !

## EJEMPLO:
 ``` java
        public class Variable{
            public static void main(String[] args) { 
                int n1,n2,re;
    
                n1= 4;
                n2= 5;
                re= n1+n2;
                System.out.println(re);  
            }
        }
 ```
 
## **Condicionales**

* **If** :La estructura de control "**if**" permite decidir entre dos opciones resultantes de la evualuacion de una sentencia.
* **Else**: Este es complemento del if y se ejecuta solo si no se cumple con la sentencia del if.

## Ejemplo del if + else

 ``` java
   public class Condicion{
       public static void main(string[]args)
       {
           int num1=5;
           int num2=10;
           
           if(num2>num1){
               system.out.println("El numero 2 es mayor al numero 1");
           }
           else{
               system.out.println("El numero 1 es mayor al numero 2");
           }
       }
   }
 ```
 
## if + else anidados (condicionales anidadas).
 ``` java
   public class Condicion_anidada{
       public static void main(string[]args)
       {
           int num1=5;
           int num2=10;
           
           if(num2>num1){
               system.out.println("El numero 2 es mayor al numero 1");
           }
           else{
               if(num1==num2){ //ESTO SOLO ES PARA COMPROBAR SI LOS SON O NO SON IGUALES.
                   system.out.println("Los dos numeros son iguales");
               }
               else{
                   system.out.println("el numero 1 es mayor al numero2");
               }
           }
       }
   }
 ```
 
## CONDICIONAL SWITCH
* La estructura **"Switch"** permite multiples caminos a partir de la evaluacion de una sola expresion/condicion.

### EJEMPLO 
```java
public class Switch
{
    public static void main(String()args){
        int dia=5;
        String nombreDia;
        
        switch(dia){
        
            case 1: nombreDia= "Lunes";
            break;
            case 2: nombreDia="Martes";
            break;
            case 3: nombreDia="Miercoles";
            break;
            case 4: nombreDia="Jueves";
            break;
            case 5: nombreDia="Viernes";
            break;
            case 6: nombreDia="Sabado";
            break;
            case 7: nombreDia="Domingo";
            break;
            default: nombreDia="Numero de dia invalido";
            break;
        }
        System.out.println("El dia de la semana seleccionado es: "+ nombreDia);
    }
 }  
```
 

 
 
