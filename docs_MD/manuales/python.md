
![Símbolo representativo de Python](img/python.png)

# Introducción

**Python** es un lenguaje de programación versátil y fácil de aprender, ideal para principiantes. Se caracteriza por su sintaxis clara y legible, similar al lenguaje natural, lo que facilita su comprensión y uso. Este manual te guiará a través de los conceptos básicos de Python, permitiéndote escribir tus propios programas y explorar el mundo de la programación.

## Entorno de desarrollo

Para comenzar a programar en Python, necesitas un entorno de desarrollo. Puedes usar el intérprete interactivo de Python, disponible en la mayoría de los sistemas operativos, o un IDE (Integrated Development Environment) como PyCharm, Visual Studio Code o Jupyter Notebook.

## Tipos de datos

En Python, existen diferentes tipos de datos para almacenar información. Los tipos de datos más comunes son:

>**Numéricos:** enteros (`int`), decimales (`float`) y complejos (`complex`)  
**Texto:** cadenas de caracteres (`str`)  
**Booleanos:** `True` o `False`.  
**Colecciones:** listas (`list`), tuplas (`tuple`), diccionarios (`dict`)  
**Conjuntos:** (`set`).

## Entrada y salida

Para interactuar con el usuario, Python ofrece funciones para leer y escribir datos. Las funciones más comunes son:

>`input()`: lee una línea de texto del usuario.  
`print()`: imprime texto en la pantalla.

## Condicionales

Las estructuras condicionales permiten ejecutar diferentes acciones dependiendo de una condición. Las estructuras condicionales más comunes son:

>`if`: ejecuta un bloque de código si la condición se cumple.  
`elif`: ejecuta un bloque de código si la condición anterior no se cumple y la actual sí.  
`else`: ejecuta un bloque de código si ninguna de las condiciones anteriores se cumple.

## Bucles

Los bucles permiten ejecutar un bloque de código de forma repetitiva. Los bucles más comunes son:

> `for`: ejecuta un bloque de código para cada elemento de una secuencia.  
> `while`: ejecuta un bloque de código mientras una condición se cumpla.

## Funciones

Las funciones son bloques de código reutilizables que encapsulan una tarea específica. Las funciones permiten organizar el código y hacerlo más modular.

## Módulos

Los módulos son archivos que contienen código Python que puede ser importado y utilizado en otros programas. Los módulos permiten compartir código y reutilizarlo en diferentes proyectos.

## Estructuras de datos más avanzadas

Además de las estructuras de datos básicas, Python ofrece estructuras más avanzadas como:

>**Listas**: son colecciones ordenadas y mutables de datos.  
**Tuplas**: son colecciones ordenadas e inmutables de datos.  
**Diccionarios**: son colecciones de pares clave-valor.  
**Conjuntos**: son colecciones no ordenadas de elementos únicos.

## Programación orientada a objetos

Python es un lenguaje de programación orientado a objetos, lo que significa que permite crear objetos que encapsulan datos y comportamiento. La programación orientada a objetos facilita el desarrollo de programas complejos y modulares.

## Ejemplos de código de Python

**1. Imprimir un mensaje en pantalla:**

```Python

print("Hola, mundo!")

```



**2. Calcular la suma de dos números:**

```Python
num1 = 10
num2 = 20

suma = num1 + num2

print("La suma de", num1, "y", num2, "es", suma)
```


**3. Usar una estructura condicional:**

```Python

numero = 5

if numero > 0:
  print("El número", numero, "es positivo")
else:
  print("El número", numero, "es negativo")

```

**4. Usar un bucle for:**

```Python

lista_numeros = [1, 2, 3, 4, 5]

for numero in lista_numeros:
  print(numero)

```

**5. Definir una función:**

```Python

def saludar(nombre):
  print("Hola", nombre, "!")

saludar("Ana")
```


**6. Importar un módulo:**
```Python

import math

print(math.pi)
```


**7. Crear una clase:**
```Python

class Persona:
  def __init__(self, nombre, edad):
    self.nombre = nombre
    self.edad = edad

  def saludar(self):
    print("Hola, me llamo", self.nombre)

persona1 = Persona("Juan", 30)

persona1.saludar()
```


**8. Leer un archivo:**
```Python

with open("archivo.txt", "r") as archivo:
  contenido = archivo.read()

print(contenido)
```


**9. Escribir en un archivo:**
```Python

with open("archivo.txt", "w") as archivo:
  archivo.write("Hola, mundo!")

```

**10.  Usar expresiones regulares:**
```Python

import re

texto = "Hola, mundo!"

resultado = re.search("Hola", texto)

if resultado:
  print("La palabra 'Hola' se encuentra en el texto")
```


>Estos son solo algunos ejemplos de código de Python. Puedes encontrar muchos más ejemplos en Internet o en libros de programación.


## Recursos adicionales:

1. https://www.freecodecamp.org/espanol/news/python-ejemplos-de-codigo-tutorial-de-programacion-en-python-desde-cero-para-principiantes/  
2. https://aprendeconalf.es/docencia/python/ejercicios/  
3. https://www.freecodecamp.org/espanol/news/25-proyectos-en-python-para-principiantes/

## Consejos para principiantes:

Comienza con proyectos sencillos y ve aumentando la dificultad gradualmente.
No tengas miedo de cometer errores. La mejor forma de aprender es experimentando.
Busca ayuda en Internet o en foros de programación si te encuentras con dificultades.
Practica con regularidad para mejorar tus habilidades.


## Conclusión

Este manual te ha proporcionado una base sólida para comenzar a programar en Python. Con la práctica y la dedicación, podrás desarrollar tus habilidades y convertirte en un programador experto.