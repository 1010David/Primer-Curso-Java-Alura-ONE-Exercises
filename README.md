Proyecto Java: Introducción y Fundamentos
Este proyecto tiene como objetivo guiarte a través de la configuración de tu entorno de desarrollo en Java y presentarte algunos de los conceptos fundamentales de la programación en este lenguaje. Aquí aprenderás desde la instalación del JDK y el IDE IntelliJ, hasta la creación de tu primer programa en Java. También exploraremos temas esenciales como variables, tipos primitivos, estructuras de control y bucles.

Contenidos
Configuración del entorno de desarrollo
Instalación del JDK 17 y el IDE IntelliJ.
Diferencias entre JVM, JRE y JDK
¿Qué son y para qué sirven?
Tu primer programa en Java: "¡Hola, mundo!"
Crear y ejecutar un programa básico en IntelliJ.
Variables y tipos de datos primitivos
Enteros, punto flotante, booleanos y más.
Condicionales y estructuras de repetición
Control de flujo usando if/else, for, y while.
Entrada del teclado con Scanner
Leer datos del usuario en la consola.
1. Configuración del entorno de desarrollo
Instalación de JDK 17
El primer paso es instalar el Java Development Kit (JDK) 17, que puedes descargar desde el sitio oficial de Oracle. El JDK contiene las herramientas necesarias para compilar y ejecutar programas Java.

Después de instalarlo, puedes verificar si está correctamente instalado ejecutando el siguiente comando en tu terminal o consola:

bash
Copiar código
java -version
Esto debería mostrar la versión de Java que tienes instalada.

Instalación de IntelliJ IDEA
A continuación, instala IntelliJ IDEA, un IDE (Entorno de Desarrollo Integrado) que facilita mucho la escritura, compilación y ejecución de código Java. Puedes descargarlo desde el sitio oficial de JetBrains. Durante la configuración inicial, selecciona el JDK 17 que instalaste anteriormente para que IntelliJ lo utilice como entorno de desarrollo.

2. JVM, JRE y JDK: Diferencias
Es importante conocer las diferencias entre los componentes clave del entorno Java:

JVM (Java Virtual Machine): Es la máquina virtual encargada de ejecutar el bytecode generado al compilar tu programa. En otras palabras, es el motor que hace que tu programa corra en cualquier plataforma que tenga una JVM instalada.

JRE (Java Runtime Environment): Es el entorno de ejecución que proporciona las bibliotecas necesarias para que la JVM funcione, permitiendo que los programas Java se ejecuten. Sin embargo, no incluye herramientas para el desarrollo.

JDK (Java Development Kit): Es el kit de desarrollo que incluye el compilador para convertir el código fuente en bytecode, herramientas para desarrollar, depurar y monitorear programas, así como el JRE.

3. Tu primer programa en Java: "¡Hola, mundo!"
Una vez que tienes IntelliJ configurado, el siguiente paso es crear tu primer programa en Java.

Abre IntelliJ y crea un nuevo proyecto.
Crea una nueva clase Java llamada Main.
Dentro de la clase, escribe el siguiente código:

4. Variables y tipos de datos primitivos
En Java, las variables se utilizan para almacenar información en la memoria del programa. Los tipos primitivos disponibles en Java incluyen:

Enteros: byte, short, int, long
Punto flotante: float, double
Carácter: char (almacena un solo carácter)
Booleano: boolean (puede ser true o false)
Por ejemplo, puedes declarar y utilizar variables de la siguiente manera:

java
Copiar código
int numeroEntero = 10;
double numeroDecimal = 20.5;
boolean esVerdadero = true;
char letra = 'A';
Además, la clase String te permite trabajar con cadenas de texto:

java
Copiar código
String saludo = "¡Hola, Java!";
5. Condicionales y estructuras de repetición
Condicionales
Las condicionales permiten que el programa decida qué bloque de código ejecutar en función de una condición. Las más comunes son:

Igualdad: ==
Diferente: !=
Mayor que: >
Menor que: <
Por ejemplo:

java
Copiar código
int numero = 5;
if (numero > 0) {
    System.out.println("El número es positivo");
} else {
    System.out.println("El número es negativo o cero");
}
Estructuras de repetición
Las estructuras de repetición nos permiten ejecutar un bloque de código varias veces. En Java, los bucles más comunes son:

For: Se utiliza cuando conoces el número de iteraciones.

java
Copiar código
for (int i = 0; i < 5; i++) {
    System.out.println("Iteración: " + i);
}
While: Se utiliza cuando quieres repetir un bloque de código mientras una condición sea verdadera.

java
Copiar código
int i = 0;
while (i < 5) {
    System.out.println("Iteración: " + i);
    i++;
}
6. Trabajar con el teclado y Scanner
La clase Scanner permite leer datos del teclado en Java. Es útil cuando quieres que tu programa interactúe con el usuario.


7. Próximos pasos
En este proyecto introductorio hemos aprendido:

Cómo configurar el entorno de desarrollo Java con el JDK y IntelliJ.
Las diferencias entre JVM, JRE y JDK.
Cómo crear y ejecutar un programa básico en Java.
Cómo trabajar con variables y tipos de datos primitivos.
Cómo usar condicionales y bucles para controlar el flujo de un programa.
Cómo interactuar con el usuario mediante la clase Scanner.
