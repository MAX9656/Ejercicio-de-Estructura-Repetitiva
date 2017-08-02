# Ejercicio-de-Estructura-Repetitiva
pseudocódigo
// )_ Escriba un algoritmo que permita ingresar un número N positivo y muestre por pantalla la suma de sus dígitos.
INICIO
ENTERO: N, suma, resto
IMPRIMIR: "Ingrese el número de sus dígitos"
TOMAR: N
Suma=0
MIENTRAS (N<=10) HACER
N=N%10
N=N/10
Suma= Suma+N
FIN_MIENTRAS
IMPRIMIR:"la suma de sus dígitos":+ N
FIN
