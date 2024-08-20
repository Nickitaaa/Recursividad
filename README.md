Define una funcion llamada nDescendentes que toma un entero n como argumento:
 
 *fun nDescendentes(n:Int)* {

  Verifica si el valor de n es menor o igual a 0:
    
    *if(n<=0) {

Si n es menor o igual a 0 imprime el valor de n:

  *print(n)*

Llama la funcion nDescendentes con el argumento n-1 para continuar con el descenso:
  
  *nDescendentes(n-1)*
  }

    Define la funcion principal main que se ejecuta al inicar el programa:
    
*fun main()* {

 Define una variable llamada numero con el valor 5:
 
  *val numero=5*

  Llama a la funcion nDescendentes con la variable numero como argumento:
  
  *nDescendentes(numero)*
 }
