![banner](https://github.com/diegocab27/mi-primer-repo/assets/162330383/1eb4826e-7948-46a2-8abc-bf04263647d0)

# PROYECTO 1: Algoritmo de Sistema de Costos


En este proyecto se logra
## **ÍNDICE**
* [1. Planteamiento](##Planteamiento)



## Planteamiento

Construir un algoritmo en pseudocódigo que simule un sistema para calcular el costo de un producto con base en su precio original y el porcentaje de descuento aplicado. El algoritmo debe cumplir con los siguientes requisitos:

## Requerimientos

- Leer el precio original del producto.
- Aplicar un descuento al producto si es aplicable (por ejemplo, si el cliente tiene un cupón de descuento).
- Aplicar impuestos al producto (por ejemplo, el IVA u otros impuestos).
- Si el cliente compra más de un artículo, aplicar un descuento por cantidad.
- Calcular el costo de envío basado en el destino y el peso del paquete.
- Calcular el costo final del producto sumando el precio con descuento, impuestos, descuento por cantidad y costo de envío.
- Mostrar el costo final del producto, desglosando los diferentes componentes (descuentos, impuestos, descuento por cantidad y costo de envío).

 ## Solución explicada paso a paso

 1. Primero, se declaran las variables que se utilizarán en el programa:

 - `preciopais` es un arreglo unidimensional de enteros el cual contiene los valores de costo de envio para 
       cada ciudad
 - `precio,cupdescuento,i,cantidad,peso,destino` son enteros que se usarán para controlar los bucles y 
      realizar cálculos.
```scss
  Dimension preciopais[3]
	preciopais[1]=2
	preciopais[2]=3
	preciopais[3]=4
	Definir precio,cupdescuento,i,cantidad,peso,destino como entero
```

 2.Se solicita ingresar el precio original del producto

- Se muestra en pantalla que ingrese el precio
- Se precio se lee y se guarda en la variable `precio` 

 ```scss
Escribir "Ingrese el precio de producto"
Leer precio
```
