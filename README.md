# Ejercicio01
Ejercicio 01

## Etapa 01. Descripción del problema.
Se requiere un programa en Java para convertir una cantidad de dinero en otros tipos de monedas (al menos a cinco tipos de monedas distintas).

## Etapa 02.  Definición de la solución.

~~~
- Entrada
  float cantidad
  string moneda1, moneda2, moneda3, moneda4, moneda5
  double conversion
  
- Proceso
  Solicitar moneda a convertir
  Solicitar cantidad a convertir
  Solicitar moneda para procesar conversion
  
  Si el monto es mayor o igual que cero entonces se convertira a la moneda deseada
  Si el montyo es menor que cero entonces se cancela la operación

- Salida
  
  +----------+---------------+---------------------+----------------+
  | CANTIDAD | MONEDA ORIGEN | CANTIDAD CONVERTIDA | MONEDA DESTINO |
  +----------+---------------+---------------------+----------------+
  |    10    |     DLLS      |       189.79        |       MXN      |
  +----------+---------------+---------------------+----------------+
  |    10    |     DLLS      |       0.00043       |       BTC      |
  +----------+---------------+---------------------+----------------+
  
  ~~~
  ## Etapa 03. Diseño de la solución.
  ![](https://github.com/avm0402045632/Ejercicio01/blob/master/Diagrama%20de%20clases.png)
 
