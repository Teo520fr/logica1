Ejercicio #1

inicio

declaraciones

nombreProducto string
costoBase real
porcentajeGanancia real 
IVA = 0.19 const
valorGanancia real
subTotal real
valorIVA real
precioFinal real

datos entrada


imprima "ingrese nombre del producto"
nombreProducto, leer;

imprima "cual es el costo base del producto"
costoBase, leer;

imprima "cual es el porcentaje de ganancia esperado, en decimales, ej= 0.10"
porcentajeGanancia, leer;

datos proceso

valorGanancia = costoBase * porcentajeGanancia

subTotal = costoBase + valorGanancia

valorIVA = IVA * subTotal

precioFinal = subTotal + valorIVA


datos salida 

imprima "recibo"

imprima "producto ", nombreProducto
imprima "ganancia ", valorGanancia
imprima " el subtotal es " ,subTotal
imprima "valor IVA ", valorIVA
imprima "el precio del producto es", precioFinal

fin 



