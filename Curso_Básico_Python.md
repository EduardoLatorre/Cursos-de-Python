# Curso Básico de Python

Python es un lenguaje de programación **interpretado** cuya filosofia se centra en la legibilidad del código. Fue creado por Guido  Van  Rossum con una sintaxis muy limpia, ideado para enseñar a la gente a programar bien.

Es un lenguaje de alto nivel, lo que significa que esta al nivel mas alto de abtracción del lenguaje máquina, es decir que su sintaxis es mas parecida al lenguaje humano que al lenguaje máquina, lo que lo hace muy fácil de aprender.

## ¿Qué es un programa?

Un **programa de computadora** es una secuencia de instrucciones que se le dan a la computadora para que esta realice un trabajo especifico y la programación es el proceso iterativo de escribir y editar estas intrucciones en lo que se conoce como el **código fuente**. El código fuente es traducido a lenguaje máquina y finalmente ejecutado por la computadora.

## Especialidades del desarrollo de sofware

Para elegir un lenguaje de programación debemos primero pensar en lo que queremos realizar. Existen distintas áreas de especialización en la tecnología y en cada una de estas hay ciertos lenguajes de programación predilectos debido a su desempeño en ciertas tareas que demanda dicha especialidad.

Algunas de estas especialidades son:

- **Frontend**: Es el campo que se encarga de llevar el diseño de una aplicación o de un sitio web a código.

- **Internet of Things (IOT)**: Se encarga de darle la capacidad de conectarse a internet a los objetos cotidianos, como los electrodomésticos o robots.

- **Backend**: Es el campo a partir del cual se crea la lógica a través de la que funciona una aplicación, esta lógica se hospeda en un servidor.

- **DevOps**: Área encargada de manejar el servidor. Controlan toda la infraestructura en base a la cual funciona una una aplicación

- **Data science**:  Consiste en la toma de grandes volúmenes de información para de esa manera resolver problemas de la manera más eficiente posible.

- **Inteligencia artificial**: Se centra en enseñarle a la computadora a aprender a resolver problemas, de esta manera se logra cierto nivel autonomía frente a los humanos.

- **Desarrollo móvil**: Se encarga de crear aplicaciones que serán almacenadas en la PlayStore o AppStore, y que podremos hacer uso de ellas desde nuestros smartphones.

- **Video juegos**: Se encarga de combinar la programación, el diseño y la música para generar grandes experiencias a los usuarios.

En partícular Python destaca en **IOT**, **Inteligencia artificial**, **Backend** y **Data science**. Es uno de los lenguajes de programación mas usado estando presente en companias como Google, Spotify, Platzi etc.

Sus principales ventajas son la fácilidad de su aprendizaje, el fomento de las buenas prácticas de programación y la elegancia de su sintaxis.

## ¿Qué es un algoritmo?

Un algoritmo es una serie de pasos ordenados para resolver un problema. En programación los algoritmos son la base fundamental del programa, pues en última intancia un programa de computadora es un conjunto de algoritmos diseñados para ser interpretados y ejecutados por una computadora.

Los algoritmos son creados con el fin de explicar un proceso que tiene un inicio y un fin, dicho de otra forma, un algoritmo es una serie finita de instrucciones que produce el mismo resultado. Esta serie de instrucciones debe estar expresada en términos concretos, de tal forma que no quede duda de lo que haya que hacer para que la ejecución sea exitosa.

Un algorimo se divide en tres partes:

- **Entrada**: son los requerimientos esenciales para llevar a cabo las instrucciones.
- **Proceso**: se trata del conjunto de instrucciones o pasos a seguir para ejecutar el algoritmo.
- **Salida**: es la resolución o fin del proceso.

Los algoritmos pueden expresarse de forma gráfica mediante un **diagrama de flujo**, o no gráfica escribiendolos de forma literal.

## La termnal

La terminal es una interfaz gráfica basada en texto que se usa para interactuar con una computadora. Esta interfaz grafica recibe comandos de parte del usuario y sé los pasa a un **shell**. El **shell** interpreta lo que el usuario ha introducido y lo traduce en instrucciones concretas para el computador. Es decir, la terminal nos permite dar ordenes al computador por medio de comandos. 

Esta herramienta es usada por programadores por que permite interactuar de una forma más profunda controlada y eficiente, pudiendo automatizar tareas repetitivas a una mayor velocidad que con una interfaz gráfica.

Algunos comandos básicos de la terminal son:

- **clear** ó **Crl + l**: Limpia la pantalla.
- **cd {dir}**: (Change directory) Mueve la terminal al directorio indicado. Si no se indica se mueve al home.
- **ls**: Lista (muestra) los archivos y carpetas del directorio.
- **mkdir {name}**: Crea una nueva carpeta o directorio con el nombre indicado.
- **touch {name.ext}**: Crea un nuevo archivo con el nombre y la extensión indicados.

Algunos comandos presentan distintas formas o variaciones las cuales son accesibles añadiendo **flags** o banderas al comando original, por ejemplo el comando **ls** tiene las siguientes variaciones:

- **ls -l**: Lista los archivos y carpetas con toda la información de cada uno.
- **ls -lh**: Lista los archivos y carpetas con toda la información de cada uno de una forma más legible para el ser humano.
- **ls -la**: Lista los archivos y carpetas incluyendo los archivos ocultos.
- **ls -lS**: Lista los archivos y carpetas comenzando con los más pesados.
- **ls -lr**: Lista todos los elementos de forma inversa.

## Operadores en Python

Los operadores son símbolos que le indican a Python que realice una operación específica, como aritmética, comparación, lógica, etc.

En Python existen los siguientes tipos de operadores:

- Operadores aritm´rticos
- Operadores relacionales
- Operadores lógicos
- Operadores Bit a Bit
- Operadores de asignación
- Operadores de pertenencia
- Operadores de identidad

### Operadores aritméticos

Los operadores aritméticos realizan operaciones matemáticas basicas como la suma, resta, multiplicación división etc. En Python estos operadores son:

- **+**: Realiza la suma de dos números. Ejemplo 2 + 3 = 5
- **-**: Realiza la resta de dos números. Ejemplo 2 - 3 = -1
- **\***: Realiza la multiplicación de dos números. Ejemplo 2 * 3 = 6
- **\*\***: Realiza la potencia de un número.  Ejemplo 2 ** 3 = 8. En este ejemplo se esta elevando 2 a la tercera potencia. (También pueden usarse potencias fraccionarias)
- **/**: Realiza la división de dos números. Ejemplo 3 / 2 = 1.5 
- **//**: Realiza la división entera de dos números.  Ejemplo 3 // 2 = 1. En el ejemplo 3 // 2 es 1 ya que 3 / 2 = 1.5 por lo que la parte entera es 1.
- **%**: Realiza el módulo de un número con respecto a otro. La operación módulo devuelve el residuo de una división.   Ejemplo 3 % 2 = 1. En el ejemplo 3 % 2 es 1 ya que al dividir 3 entre 2 nos da 1 y como residuo nos queda 1.

Para determinar el orden de las operaciones Python obedece la regla de la precedencia de operadores.

Primero paréntesis , potencias y raíces , multiplicaciones y divisiones , al final sumas y restas

## Operadores Relacionales

Un operador relacional compara y establece una relación entre operandos. Si el resultado de la comparación es correcto se devuelve el valor booleano **True**, en caso contrario se devuelve el valor booleano **False**. Estos operadores son:

- **>**: Devuelve **True** si el operador de la izquierda es mayor al de la derecha. Ejemplo 3 > 2 = True
- **<**: Devuelve **True** si el operador de la derecha es mayor al de la izquierda. Ejemplo 2 < 3 = True
- **==**: Devuelve **True** si ambos operadores son iguales. Ejemplo (2 + 2) == 4 = True
- **>=**: Devuelve **True** si el operador de la izquierda es mayor o igual al de la derecha. Ejemplo 3 >= 3 = True
- **<=**: Devuelve **True** si el operador de la derecha es mayor o igual al de la izquierda. Ejemplo 2 <= 3 = True
- **!=**: Devuelve **True** si ambos operadores no son iguales. Ejemplo (2 + 2) != 5 = True

## Operadores lógicos



## Operadores Bit a Bit

## Operadores de asignación

## Operadores de pertenencia

## Operadores de identidad
