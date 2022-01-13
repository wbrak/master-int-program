Title: Guía para el master de introducción a la programación.  
Author: Iván López ([Webmasterbrak](https://www.informaticocoruna.com))
Date: 14 de septiembre de 2021
# Master Introducción a la Programación
El presente máster de introducción a la programación está desarrollado siguiendo varios cursos y lenguajes distintos, es el resultado de la recopilación y estructuración de los contenidos que tenía dispersos. Espero que te sea de ayuda e inspiración.  
Se realizarán los ejemplos básicos en Python, PHP, JavaScript y C, ya que son los que conozco en mayor o menor medida.  
>Al ser varios los lenguajes y sistemas operativos que se pueden usar en está guía, no definiremos áqui los entornos de desarrollo, por diversas razones uso tanto Linux como Windows en los desarrollos.  
Puedes encontrar los distintos entornos para cada lenguaje en el documento [ENTORNOS.md](https://github.com/wbrak/master-intro-programing/blob/main/ENTORNOS.md) (en construcción) de este repositorio.
### Contenidos del master de programación
#### 1º. Curso de introducción a la programación.
En este curso se verán las definiciones de programación, los tipos de lenguajes, y los conceptos básicos de la programación.
- [¿Qué es la programación?](#Qué-es-la-programación)
- [¿Qué es un lenguaje de programación?](#Qué-es-un-lenguaje-de-programación)
- [Lenguajes de alto y bajo nivel](#Lenguajes-de-bajo-y-alto-nivel)
- [Lenguajes interpretados y compilados](#Lenguajes-interpretados-y-compilados)
- [Algoritmos](#Algoritmos)
- [Metodologías en programación](#Metodologías-en-programación)
- [Tipos de datos](#Tipos-de-datos)
- [Constantes y variables](#Constantes-y-variables)
- [Imprimir datos](#Imprimir-datos)
- [Leer datos](#Leer-datos)
- [Primer Hola Mundo](#Primer-Hola-Mundo)
#### 2º. Curso de introducción a los algoritmos
- [Inicio](#Master-Introducción-a-la-Programación)
### ¿Qué es la programación?
Es el proceso de diseñar, codificar, depurar y mantener el código fuente de un programa.  
Es el arte que nos permite reflejar en código las múltiples soluciones para resolver un problema mediante unos pasos o instrucciones ordenadas.
### ¿Qué es un lenguaje de programación?
Es un lenguaje que contiene reglas específicas que nos permiten realizar o controlar ciertas acciones en una computadora.  
Es el puente de comunicación entre la máquina y la persona, después entra en juego el compilador o el intérprete que permite traducir lo escrito a lenguaje máquina (binario, 1 y 0).  
Existen los lenguajes de bajo nivel y de alto nivel
### Lenguajes de alto y bajo nivel
Los lenguajes de alto nivel son más fácilmente entendibles por las personas, son portables, legibles y su código resulta más fácil de mantener. Ej. Python, PHP, Ruby, Java o C#.  
Los lenguajes de bajo nivel se compilan más rápido y se puede optimizar la memoria, el más conocido es ensamblador y se encargan de traducir a código binario.
Existen algunos lenguajes como C, que se encuentran en un nivel medio, no son de bajo nivel, ya que su sintaxis es legible y se puede manejar de forma fácil el hardware de un equipo y permite escribir código optimizado. Es por esto que aún se usa para crear cualquier tipo de software.
### Lenguajes interpretados y compilados
- `Interpretados`: Hacen uso de un programa llamado intérprete para traducir lo escrito al lenguaje máquina además de verificar la sintaxis y estructura del código para su correcta ejecución, lee línea por línea y para la ejecución si encuentra errores.
- `Compilados`: Hacen uso de un programa llamado compilador para traducir lo escrito al lenguaje máquina además de verificar la sintaxis y estructura del código para su correcta ejecución, lee todo el código y si está correcto lo compila en un archivo ejecutable.
### Algoritmos
Conjunto de reglas ordenadas, definidas y finitas que nos permiten realizar una actividad. Siempre tiene que tener un principio y un fin, pudiendo ser muy simples o muy complejos.  
En matemáticas, lógica, ciencias de la computación y disciplinas relacionadas, un algotitmo es un conjunto de instrucciones o reglas definidas y no ambiguas, ordenadas y finitas que permiten, típicamente, solucionar un problema, realizar un cómputo, procesar datos y llevar a cabo otras tareas o actividades.  
Dado un estado inicial y una entrada, siguiendo los pasos sucesivos se llega a un estado final y se obtiene una solución.  
En la vida cotidiana, se emplean algoritmos frecuentemente para resolver problemas determinados.  
Ej: Manuales de usuarios, muestran algoritmos para usar un aparato. En matemáticas son el algoritmo de la multiplicación, para calcular el producto, el algoritmo de la división para calcular el cociente de dos números, el algoritmo de euclides para obtener el máximo común divisor de dos números enteros positivos, o el método de Gauss para resolver un sistema de ecuaciones lineales.  
**En términos de programación, un algoritmo es una secuencia de pasos lógicos que permiten solucionar un problema.**  
Los algoritmos pueden ser expresados de muchas maneras, incluyendo al **lenguaje natural, pseudocódigo (código falso), diagramas de flujo y lenguajes de programación** entre otros. Las descripciones en lenguaje natural tienden a ser ambiguas y extensas. El usar pseudocódigo y diagramas de flujo evita muchas ambigüedades del lenguaje natural. Dichas expresiones son formas más estructuradas para representar algoritmos; no obstante, se mantienen independientes de un lenguaje de programación específico.  
La descripción de un algoritmo usualmente se hece en tres niveles:
- Descripción de alto nivel: Se establece el problema, se selecciona un modelo mátematico y se explica el algoritmo de manera verbal, posiblemente con ilustraciones y omitiendo detalles.
- Descripción formal: Se usa pseudocódigo para describir la secuencia de pasos que encuentran la solución.  
- Implementación: Se muestra el algoritmo expresado en un lenguaje de programación específico o algún objeto capaz de llevar a cabo instrucciones.

También es posible incluir un teorema (proposición cuya verdad se demuestra) que demuestre que el algoritmo es correcto, un análisis de complejidad o ambos.  



**Ventajas del pseudocódigo sobre los diagramas de flujo**  
1. Ocupan mucho menos espacio en el desarrollo del problema.
2. Permite representar de forma fácil operaciones repetitivas complejas.
3. Es más sencilla la tarea de pasar de pseudocódigo a un lenguaje de programación formal.
4. Si se siguen las reglas de indentación se puede observar claramente los niveles en la estructura del programa.
5. En los procesos de aprendizaje de los alumnos de programación, estos están más cerca del paso siguiente (codificación en un lenguaje determinado), que los que se inician en esto con la modalidad de diagramas de flujo.
6. Mejora la claridad de la solución de un problema.
### Metodologías en programación
Son una serie de pasos para llegar a un objetivo planteado, es un camino estructurado que nos ayudará a resolver cualquier problema.
- `Objetivo`: El problema a resolver
- `Algoritmo`: La solución al problema
- `Testing`: Probar la solución al problema
- `Deploy`: Desplegar el algoritmo

Programación estructurada: Es un paradigma de programación orientado a mejorar la claridad y el tiempo de desarrollo de un programa recurriendo únicamente a subrutinas y a tres estructuras básicas.
- Secuencial: Ejecuta una a una todas las líneas de un proceso hasta finalizar.  
[Diagrama secuencial](/diagramas/Secuencial.png "Diagrama secuencial")  
- Condicional: Ejecuta un proceso dependiendo de una serie de condiciones que se puedan dar.  
[Diagrama condicional](/diagramas/Condicional.png "Diagrama condicional")
- Iterativa: Un proceso puede ser ejecutado un número indeterminado de veces basado en condiciones.  
[Diagrama iterativo](/diagramas/Iterativa.png "Diagrama iterativo")

La intención clara de la programación estructurada es la de evitar el **código espagueti,** un lastre durante muchos años en el mundo de la programación que provocaba errores y código defectuoso imposible de mantener.
### Tipos de datos
#### ¿Qué es un tipo de dato?  
Un dominio, un conjunto.  
Conjunto: colección de elementos no repetidos y no ordenados.  
Ejemplos claros matemáticos: el dominio de números enteros, de números reales, de números pares...  
Podemos definir un conjunto de datos por extensión(enumerando los elementos) o por comprensión(una expresión que defina la colección).  
#### ¿Para que sirve un tipo de dato?  
Para declarar expresiones, variables, funciones... y hacer comprobaciones de datos semánticas básicas en tiempo de compilación.  
Un mayor nivel de seguridad/control/gestión se puede implementar mediante comprobaciones dentro de funciones.  
#### Tipos de datos básicos  
Cada lenguaje de programación tiene sus propios tipos de datos.  
En C tenemos predefinidos los siguientes:
- int: Cantidad entera
- char: Carácter
- float: Almacena valores reales en punto flotante
- double: Almacena valores reales en doble precisión
- void: Se utiliza para definir una función que no devuelve ningún valor o declarar punteros genéricos  

En PHP tenemos los tipos de datos escalares:
- boolean: true o false
- integer: Cantidad entera
- float: Almacena valores reales en doble precisión
- string: Cadena de caracteres  

Los tipos de datos compuestos:
- Array: Almacena diferentes valores en una variable
- Object: Agrupa los datos de una clase  

Y los tipos de datos especiales:
- Null: Representa una variable sin valor asignado
### Constantes y variables

### Imprimir datos

### Leer datos

### Primer Hola Mundo
~~~~
Código de prueba
~~~~

~~~~
 Markdown
: Herramienta de conversión de texto plano a HTML.
: Lenguaje de marcado que facilita la escritura de documentos y artículos web.
~~~~
| Primera columna | Segunda columna | Tercera columna |
| -- | -- | -- |
| Contenido 1-1 | Contenido 1-2 | Contenido 1-3 |
| Contenido 2-1 | Contenido 2-2 | Contenido 2-3 |
| Contenido 3-1 | Contenido 3-2 | Contenido 3-3 |
