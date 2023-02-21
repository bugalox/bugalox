<a href="https://es.cooltext.com"><img src="https://images.cooltext.com/5643346.png" width="664" height="119" alt="Bienvenidos" /></a>|
![](imagen/Descargas/SP.png)
### Hola :+1:
* Nombre del alumno :Alejandro Martinez Reyes
* No. Control: 20210593
### SistemasProgramables
* El siguiente apartado es para la materia de sistemas programables.
* En estos momentos me encuentro trabajando en la compañia Avery CCL :)
* Me gusta la musica , tengo licenciatura trunca en Solista Trompeta de Bellas Artes CD Mexico
* Quisiera terminar pronto la carrera.


### Herramientas para cursos
* arduino clasico
* STM32
* FrambuesaPi
* kit de sensores y herramientas de soldadura

### Horario de clases


| HRS | LUNES          | MARTES         | MIERCOLES      | JUEVES         | VIERNES       |
|:---:|:--------------:|:--------------:|:--------------:|:--------------:|:-------------:|
| 2PM | REDES          | REDES          | REDES          | REDES          | REDES         |
| 3PM | P. LOGICA      | P. LOGICA      | P. LOGICA      | P. LOGICA      | P. LOGICA     |
| 4PM | GESTION        | GESTION        | GESTION        | GESTION        | GESTION       |
| 5PM | S.PROGRAMABLES | S.PROGRAMABLES | S.PROGRAMABLES | S.PROGRAMABLES |               |
| 6PM | LYAII          | LYAII          | LYAII          | LYAII          | LYAII         |
| 7PM | F.PROFESIONAL  | F.PROFESIONAL  | F.PROFESIONAL  | F.PROFESIONAL  | F.PROFESIONAL |



### Codigo Fuente:
```ruby
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace ConsoleApp1
{
  class Program 
  {
     static void Main(string[] args)
        {
          Console.WriteLine("Hola Mundo!!")
        }
  }

}
```
<a href="https://es.cooltext.com"><img src="https://images.cooltext.com/5643347.png" width="790" height="119" alt="Buen Curso!!!" /></a>

### 1.Escribir un programa que acepte 25 enteros positivos como datos y describir cada uno como impar o par 
```python
numeros = []
for i in range(25):
    numero = int(input("Ingrese un número entero positivo: "))
    numeros.append(numero)
for numero in numeros:
    if numero % 2 == 1:
        print(f"El número {numero} es impar.")
    else:
        print(f"El número {numero} es par.") 
```
### 2.Determinar cual cantidad es mayor : 375 o 2100
```python
cantidad1 = 375
cantidad2 = 2100

if cantidad1 > cantidad2:
    print("La cantidad", cantidad1, "es mayor que la cantidad", cantidad2)
else:
    print("La cantidad", cantidad2, "es mayor que la cantidad", cantidad1)
```
### 3.una pulgada equivalente a 2.5 cm , calcular el numero de cm en 32 pulgadas
```python
/Definimos una constante para la equivalencia entre pulgadas y centímetros
PULGADA_A_CM = 2.5

/ Calculamos el número de centímetros en 32 pulgadas
pulgadas = 32
cm = pulgadas * PULGADA_A_CM

/ Imprimimos el resultado
print(f"{pulgadas} pulgadas son equivalentes a {cm} centímetros.")
```
### 4.Encontrar la suma de 35 enteros
```python
/Creamos una lista de 35 enteros
numeros = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19, 20, 21, 22, 23, 24, 25, 26, 27, 28, 29, 30, 31, 32, 33, 34, 35]

/ Inicializamos la variable de suma
suma = 0

/ Iteramos a través de los números y los sumamos
for numero in numeros:
    suma += numero

/ Imprimimos el resultado
print("La suma de los 35 enteros es:", suma)
```
### 5.imprimir la tabla de multiplicar hasta 12x12
```python
/ Iteramos a través de los números del 1 al 12 para la columna
for i in range(1, 13):
    / Iteramos a través de los números del 1 al 12 para la fila
    for j in range(1, 13):
        / Multiplicamos la columna y la fila para obtener el resultado
        resultado = i * j
        / Imprimimos el resultado en formato de tabla
        print(f"{i} x {j} = {resultado}")
    / Agregamos un espacio en blanco para separar las tablas de multiplicar
    print()
```
### 6.imprimir la tabla de sumar hasta 12+12
```python
/Iteramos a través de los números del 1 al 12 para la columna
for i in range(1, 13):
    / Iteramos a través de los números del 1 al 12 para la fila
    for j in range(1, 13):
        / Sumamos la columna y la fila para obtener el resultado
        resultado = i + j
        / Imprimimos el resultado en formato de tabla
        print(f"{i} + {j} = {resultado}")
    / Agregamos un espacio en blanco para separar las tablas de sumar
    print()
```
### 7.Encontrar la suma de los enteros del 1 al 1000
```python
/ Inicializamos la variable de suma en cero
suma = 0

/Iteramos a través de los números del 1 al 1000 y los sumamos
for i in range(1, 1001):
    suma += i

/Imprimimos el resultado
print("La suma de los enteros del 1 al 1000 es:", suma)
```
### 8.Encontrar la suma de todos los enteros pares del 2 al 2000
```python
/Inicializamos la variable de suma en cero
suma = 0

/ Iteramos a través de los números del 2 al 2000 y sumamos los pares
for i in range(2, 2001, 2):
    suma += i

/ Imprimimos el resultado
print("La suma de los enteros pares del 2 al 2000 es:", suma)
```
### 9.de dos numero cualquiera , encontrar la suma e indicar si es positiva , negativa o cero
```python
/ Pedimos al usuario que ingrese dos números
numero1 = float(input("Ingresa el primer número: "))
numero2 = float(input("Ingresa el segundo número: "))

/ Sumamos los dos números
suma = numero1 + numero2

/ Verificamos si la suma es positiva, negativa o cero
if suma > 0:
    print("La suma es positiva")
elif suma < 0:
    print("La suma es negativa")
else:
    print("La suma es cero")
```
### 10.Introducir un entero positivo N , Encontrar la suma de los N enteros .Imprimir cada uno de los enteros y la suma
```python
/ Pedimos al usuario que ingrese un número entero positivo
N = int(input("Ingresa un número entero positivo: "))

/ Inicializamos la variable de suma en cero
suma = 0

/ Iteramos a través de los números del 1 al N y los sumamos
for i in range(1, N + 1):
    suma += i
    print(i)

/ Imprimimos el resultado de la suma
print("La suma de los", N, "enteros es:", suma)
```
### 11.introducir n entero.Calcular e imprimir el producto de os numeros pares
```python
/ Pedimos al usuario que ingrese un número entero positivo
N = int(input("Ingresa un número entero positivo: "))

/ Inicializamos el producto en 1
producto = 1

/ Iteramos a través de los números del 1 al N y multiplicamos los pares
for i in range(1, N + 1):
    if i % 2 == 0:
        producto *= i

/ Imprimimos el resultado del producto
print("El producto de los números pares hasta", N, "es:", producto)
```
### 12.calcular la suma de las raices cuadradas de los numeros impares que hay entre 1 y 1000
```python
import math

/ Inicializamos la variable de suma en cero
suma = 0

/ Iteramos a través de los números del 1 al 1000 y sumamos las raíces cuadradas de los impares
for i in range(1, 1001):
    if i % 2 != 0:
        suma += math.sqrt(i)

/ Imprimimos el resultado de la suma
print("La suma de las raíces cuadradas de los números impares entre 1 y 1000 es:", suma)
```
### 13.Determinar si un entero dado es divisible entre 2 y 5
```python
# Pedimos al usuario que ingrese un número entero
numero = int(input("Ingresa un número entero: "))

# Verificamos si el número es divisible entre 2 y 5
if numero % 2 == 0 and numero % 5 == 0:
    print(numero, "es divisible entre 2 y 5.")
else:
    print(numero, "no es divisible entre 2 y 5.")
```
14.imprimir la suma y el producto de todos los posibles pares diferentes de enteros del 15 al 20
```python
# Inicializamos la suma y el producto en cero
suma = 0
producto = 1

# Generamos todas las combinaciones de pares de enteros del 15 al 20
for i in range(15, 21):
    for j in range(15, 21):
        if i != j:  # Nos aseguramos de que los enteros sean diferentes
            # Imprimimos los pares de enteros
            print(i, j)
            # Sumamos y multiplicamos los pares de enteros
            suma += i + j
            producto *= i * j

# Imprimimos la suma y el producto de todos los pares de enteros
print("La suma de todos los pares de enteros es:", suma)
print("El producto de todos los pares de enteros es:", producto)
```
15.converti libras y onzas a kilogramos
```python
# Convertir 5 libras y 8 onzas a kilogramos
libras = 5
onzas = 8
peso_total_en_libras = libras + onzas/16

# Convertir a kilogramos
peso_en_kg = peso_total_en_libras * 0.45359237 + onzas * 0.0283495231

# Imprimir el resultado
print("El peso es:", peso_en_kg, "kg")
```
16.calcular e imprimir el numero de segundos que hay en una semana  , en tres semanas , en un mes y tres dias
```python
# Calcular el número de segundos en una semana
segundos_en_semana = 86400 * 7
print("Hay", segundos_en_semana, "segundos en una semana")

# Calcular el número de segundos en tres semanas
segundos_en_tres_semanas = segundos_en_semana * 3
print("Hay", segundos_en_tres_semanas, "segundos en tres semanas")

# Calcular el número de segundos en un mes
segundos_en_mes = 86400 * 30
print("Hay", segundos_en_mes, "segundos en un mes")

# Calcular el número de segundos en un mes y tres días
segundos_en_mes_y_tres_dias = segundos_en_mes + 86400 * 3
print("Hay", segundos_en_mes_y_tres_dias, "segundos en un mes y tres días")
```
17.Enontrar el promedio de N numero .Insertar en primer lugar el valor de n , seguido por los N numero 
```python
# Leer el valor de N desde el usuario
n = int(input("Ingrese el valor de N: "))

# Inicializar la variable suma a cero
suma = 0

# Leer los N números y sumarlos a la variable suma
for i in range(n):
    num = float(input("Ingrese un número: "))
    suma += num

# Calcular el promedio dividiendo la suma entre N
promedio = suma / n

# Imprimir el promedio
print("El promedio de los", n, "números es:", promedio)
```
18.invertir un numero es escribirlo hacia atras e imprimirlo
```python
# Leer el número desde el usuario
num = int(input("Ingrese un número: "))

# Convertir el número a una cadena de texto
cadena = str(num)

# Invertir la cadena de texto
cadena_invertida = cadena[::-1]

# Convertir la cadena de texto invertida a un número entero
num_invertido = int(cadena_invertida)

# Imprimir el número invertido
print("El número invertido es:", num_invertido)
```
19.Encontrar el valor absoluto de -6,0,25,-143,-42
```python
print("El valor absoluto de -6 es:", abs(-6))
print("El valor absoluto de 0 es:", abs(0))
print("El valor absoluto de 25 es:", abs(25))
print("El valor absoluto de -143 es:", abs(-143))
print("El valor absoluto de -42 es:", abs(-42))
```
20.Nancy presneto cuatro pruebas , sus calificaciones fuero 95,88,84,70 , cual es la calificacion final ?
```python
promedio = (95 + 88 + 84 + 70) / 4
print("El promedio de Nancy es:", promedio)
```
21.Generar 20 conjuntos de 50 numeros al azar , cado uno con valor de 1 a 55 . imprimir el numero mayor al azar , obtenido en cada conunto de 10
```python
import random

maximos = []

for i in range(20):
    conjunto = [random.randint(1, 55) for j in range(50)]
    maximo = max(conjunto)
    maximos.append(maximo)
    print(f"El máximo del conjunto {i+1} es: {maximo}")
    
print("Los máximos son:", maximos)-
```
22.Generar x numeros de dos digitos al azar e imprimir todos los numeros menores a su edad  , dodnde x y su edad sean entradas
```python
import random

x = 10 # número de valores a generar
valores = [] # lista para almacenar los valores generados

for i in range(x):
    valor = random.randint(10, 99) # generar valor aleatorio entre 10 y 99 (dos dígitos)
    valores.append(valor) # agregar valor a la lista

print("Valores generados:", valores)

edad = int(input("Ingresa tu edad: "))

print("Números menores a tu edad:")
for valor in valores:
    if valor < edad:
        print(valor)
```
23.Encontrar la media aritmetica de los numeros de 80 y 63
```python
num1 = 80
num2 = 63

media = (num1 + num2) / 2

print("La media aritmética de", num1, "y", num2, "es:", media)
```
24.Encontrar las raices cuadradas de los enteros del 9 al 25 imprimir el entero y su raiz cuadrada
```python
import math

for i in range(9, 26):
    raiz_cuadrada = math.sqrt(i)
    print("La raíz cuadrada de", i, "es", raiz_cuadrada)
```
25.calcular el cuadrado , cubo ,raiz cuadrada y raiz cubica de los enteros del 1 al 1000 , imprimir los resultados en forma tabular
```python
import math

# Imprimir encabezado de tabla
print("Número\tCuadrado\tCubo\tRaíz cuadrada\tRaíz cúbica")

# Recorrer números del 1 al 1000
for i in range(1, 1001):
    # Calcular cuadrado, cubo, raíz cuadrada y raíz cúbica
    cuadrado = i ** 2
    cubo = i ** 3
    raiz_cuadrada = math.sqrt(i)
    raiz_cubica = i ** (1/3)
    
    # Imprimir resultados en forma tabular
    print("{}\t{}\t\t{}\t{}\t\t{}".format(i, cuadrado, cubo, raiz_cuadrada, raiz_cubica))
```
