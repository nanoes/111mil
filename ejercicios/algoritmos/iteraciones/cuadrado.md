Cuadrado
========

Escribir un programa que nos pida dos numeros _alto_ y _ancho_, y luego dibuje un cuadrado de tales dimensiones utilizando el caracter `#`.

Luego el programa volvera a pedir otros dos numeros, para repetir la operacion. El programa no debe terminar.

Se debera validar que el cuadrado posea como minimo `1` de _alto_ o _ancho_, en cuyo caso se mostrara un mensaje de error.

Finalmente el programa debera tratar correctamente ingresos invalidos, como numeros negativos, letras, y cualquier otro error de usuario, en cuyo caso se mostrara un mensaje de error.

```java
public class Cuadrado {
  public static void main(String[] args) {
    // (tu algoritmo aca)
  }
}
```

#### Ejemplo:

```
> Ingrese ancho: 0
> Ingrese alto: 5

Alto invalido

> Ingrese ancho: 0
> Ingrese alto: cincuenta

Ancho invalido

> Ingrese ancho: 1
> Ingrese alto: 1

#

> Ingrese ancho: 8
> Ingrese alto: 5

#######
#######
#######
#######
#######

```
