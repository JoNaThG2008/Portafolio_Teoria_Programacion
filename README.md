# Universidad Nacional De Loja 
## Facultad de la Energía, las Industrias y los Recursos Naturales No Renovables
### Carrera de Computación

**Asignatura:** Teoría de la Programación - Unidad 2
**Título:** Portafolio Digital de Aprendizaje
**Estudiante:** Jonathan Contento 
**Ciclo:** 1
**Período Académico:** 2026
**Docente:** Lissette Geoconda López Faicán

<details>
  <summary>📂 <b>Unidad 1: Algoritmo, pseudocódigo, diagrama de flujo, prueba de escritorio y lenguajes de programación.</b></summary>
  <br>
  <blockquote>
  
### 1. Contenidos 📖

🔹 Algoritmo

Un algoritmo es un conjunto ordenado, finito y definido de instrucciones o pasos lógicos que permiten solucionar un problema, realizar una tarea o procesar datos. Funciona como una receta de cocina: recibe datos de entrada, los procesa siguiendo reglas claras y produce un resultado (salida).

🔹 Pseudocódigo

Son instrucciones escritas bajo cierta estructura y reglas que inducirán al alumno hacia los lenguajes de programación, utiliza símbolos y describe las instrucciones que debe seguir el algoritmo. También se puede decir que el pseudocódigo es una forma de representar algoritmos utilizando una mezcla de lenguaje natural y estructuras de programación, actuando como un "código falso" intermedio antes de escribir el código real. Su objetivo es facilitar la comprensión de la lógica del programa, centrándose en el flujo y no en las reglas sintácticas.

🔹 Diagrama de Flujo

Un diagrama de flujo (o flujograma) es una representación gráfica de un proceso, algoritmo o sistema, que utiliza símbolos estandarizados conectados por flechas para mostrar la secuencia de pasos de manera ordenada. Es una herramienta visual crucial para simplificar procesos complejos, identificar cuellos de botella y mejorar la eficiencia en áreas como programación, negocios e ingeniería.

🔹 Prueba de Escritorio

Una prueba de escritorio es la simulación manual de un algoritmo o código paso a paso, utilizando papel, lápiz o una hoja de cálculo. Su objetivo es verificar la lógica, flujo y validez del programa, detectando errores tempranos mediante la asignación de valores a las variables sin ejecutarlo en la computadora.

🔹 Lenguajes de Programación

Los lenguajes de programación son formas de comunicarnos con la computadora para decirle qué hacer. Funcionan como un idioma que la máquina entiende, y con ellos se escriben instrucciones llamadas código. Gracias a estos lenguajes, se pueden crear programas, aplicaciones, páginas web y juegos. Algunos ejemplos son C.

🔹 Programación por Bloques

La programación por bloques es una forma sencilla de programar en la que se usan bloques visuales en lugar de escribir código. Estos bloques representan instrucciones y se encajan como piezas de un rompecabezas para decirle a la computadora qué hacer. Es más fácil de aprender porque evita errores de escritura y ayuda a entender la lógica de la programación. Se usa mucho en programas educativos y para principiantes.

---

### 2. Estructura Secuencial 🛠️ 
---
#### Planteamiento del Problema 📝

Un alumno necesita calcular el promedio final de sus tres notas.  
Cada nota tiene una ponderación diferente:  
- Primera nota: 30%  
- Segunda nota: 30%  
- Tercera nota: 40%  

Se desea obtener el promedio final ponderado.

---

 #### Análisis del Problema 🔍

- **Entrada:** nota1, nota2, nota3  
- **Proceso:**  
  promedio = (nota1 * 0.30) + (nota2 * 0.30) + (nota3 * 0.40)  
- **Salida:** Promedio Final

---

#### Diseño del Algoritmo 📐

#### Diagrama de Flujo:

#### Validación (Prueba de escritorio):

| Nota 1 | Nota 2 | Nota 3 |                       Cálculo                        | Promedio |
| ------ | ------ | ------ | ---------------------------------------------------- | -------- |
| 8      | 9      | 10     | (8×0.30=2.4) + (9×0.30=2.7) + (10×0.40=4.0) = 9.1    | 9.1      |
| 7      | 8      | 9      | (7×0.30=2.1) + (8×0.30=2.4) + (9×0.40=3.6) = 8.1     | 8.1      |
| 10     | 10     | 10     | (10×0.30=3.0) + (10×0.30=3.0) + (10×0.40=4.0) = 10.0 | 10       |


### 3.  Principales dificultades y reflexión crítica en la aplicación de los contenidos 🧠

Durante el desarrollo de la unidad se presentaron diversas dificultades, como la comprensión inicial de algunos de los conceptos básicos, ademas de que en un inicio, resultó complicado diferenciar entre la forma teórica (pseudocódigo) y la forma práctica (código en lenguaje C).
Otra dificultad fue la correcta interpretación de los problemas, ya que no siempre era sencillo identificar las entradas, procesos y salidas. Esto ocasionaba errores al momento de diseñar el algoritmo o realizar la prueba de escritorio.
Sin embargo, a medida que se avanzó con la práctica, se logró mejorar la capacidad de análisis y la organización lógica de las soluciones. El uso de ejercicios secuenciales permitió comprender mejor la estructura básica de un programa y la importancia de seguir un orden adecuado en las instrucciones.

Como reflexión, estos contenidos son importantes porque son la base de la programación. Aprender a organizar un algoritmo antes de programar ayuda a hacer programas más claros y ordenados. Además, el uso de herramientas digitales y la inteligencia artificial ayudó a entender mejor los temas y resolver dudas.



### 4. Declaración de Uso de IA Generativa 🤖

De conformidad con los lineamientos éticos de la Carrera de Computación de la Universidad Nacional de Loja, se declara formalmente:

💡 Se utilizó Gemini (modelo de lenguaje de Google) como tutor de acompañamiento durante el desarrollo de esta unidad. Su intervención se limitó a brindar soporte en el aprendizaje de la sintaxis Markdown, organizar visualmente los componentes del portafolio digital, estructurar el diagrama dinámico mediante Mermaid, y actuar como herramienta de verificación lógica para corroborar el correcto cálculo de los casos de prueba de escritorio planteados.

</details>

<details>
  <summary>📂 <b>Unidad 2: Estructuras Condicionales y Repetitivas</b></summary>
  <br>
  <blockquote>
    
 🔸 Estructuras Condicionales
    
Las estructuras condicionales son aquellas que nos permiten dividir el camino de ejecución de un programa dependiendo del valor de verdad de una condición lógica, permiten que el software tome decisiones basándose en los datos de entrada o cálculos anteriormente realizados.

A continuación, se detallan los tipos de estructuras condicionales vistos en clases junto con su sintaxis en pseudocódigo y sus representaciones en diagrama de flujo:

---
#### 1. Condicionales Simples (Si / if)

Evalúan una condición lógica. Si el resultado de la evaluación es Verdadero, se ejecuta un bloque específico de instrucciones. Si es Falso, el programa ignora dicho bloque y continúa con la siguiente línea secuencial de código.


#### Estructura en Pseudocódigo:

if (condicion_logica) {
    // Esto se ejecutará si la condición es verdadera
    printf("La condición es verdadera.\n");
}

#### Diagrama de Flujo:
(Espacio reservado para tu imagen)

---
### 2. Condicionales Compuestas (Si-Sino / if-else)

Ofrecen dos caminos o alternativas de ejecución mutuamente excluyentes. Si la condición evaluada resulta Verdadero, se ejecuta el primer bloque de instrucciones; si resulta Falso, se ejecuta obligatoriamente el otro bloque de instrucciones.

#### Estructura en Pseudocódigo:

if (condicion_logica) {
    // "Bloque A": Se ejecuta si la condición es verdadera
    printf("Se cumple la condición (Caso A).\n");
} else {
    // "Bloque B": Se ejecuta si la condición es falsa
    printf("No se cumple la condición (Caso B).\n");
}


#### Diagrama de Flujo:
(Espacio reservado para tu imagen)

--- 
### 3. Condicionales Anidadas y Múltiples (if - else if)

Representan la forma de evaluar múltiples condiciones lógicas en cascada. Se ejecutan secuencialmente de arriba hacia abajo; tan pronto como una de las condiciones resulta verdadera, se procesa su bloque correspondiente y se omite el resto de la estructura.

#### Estructura en Pseudocódigo:

if (condicion_1) {
    // Se ejecutará si se cumple la primera condición
    printf("Se cumple la primera condición.\n");
} else if (condicion_2) {
    // Se ejecutará si no se cumple la primera, pero sí la segunda
    printf("No se cumple la primera, pero se cumple la segunda.\n");
} else if (condicion_3) {
    // Se ejecutará si no se cumplen las anteriores, pero sí la tercera
    printf("No se cumple ni la primera ni la segunda, pero se cumple la tercera.\n");
} else {
    // Se ejecutará si no se cumple ninguna de las condiciones anteriores
    printf("No se cumple ninguna de las condiciones.\n");
}

#### Diagrama de Flujo:
(cdg)

🔸 Estructuras Repetitivas (Bucles o Ciclos)

Las estructuras repetitivas permiten ejecutar un bloque de instrucciones de manera recurrente mientras una condición lógica preestablecida se mantenga como verdadera. Son indispensables para simplificar la escritura de código iterativo y procesar grandes volúmenes de datos homogéneos.

A continuación, se detallan los tres tipos de estructuras iterativas nativas en el lenguaje de programación C con sus diagramas de flujo estilizados:

### 1. Bucle Mientras (while)

Es una estructura de control con pre-condición. Evalúa la condición booleana al inicio, antes de entrar al bucle. Si la condición resulta verdadera, se ejecuta el bloque de código y vuelve a comprobarse; si la condición es inicialmente falsa, las instrucciones internas no se ejecutan ninguna vez.

#### Estructura en Lenguaje C:

while (condicion_de_continuidad) {
    // Instrucciones que se repetirán cíclicamente
    // Es mandatorio modificar la variable de control aquí dentro
}


#### Diagrama de Flujo:



### 2. Bucle Repetir-Mientras (do-while)

Es una estructura de control con post-condición. A diferencia del ciclo while, este bloque de instrucciones se ejecuta de manera incondicional al menos una vez antes de evaluar la condición por primera vez. Si tras la ejecución de prueba la condición es verdadera, el ciclo se repite; de lo contrario, finaliza.

#### Estructura en Lenguaje C:

do {
    // Instrucciones que se ejecutarán al menos una vez
    // Actualización de la variable de control
} while (condicion_de_continuidad);


#### Diagrama de Flujo:



### 3. Bucle Para (for)

Es una estructura de control iterativa compacta, diseñada específicamente para escenarios donde se conoce con precisión el número de iteraciones de antemano. Agrupa de forma estructurada en su cabecera la inicialización de la variable contadora, la evaluación de continuidad y el incremento o decremento de dicha variable.

#### Estructura en Lenguaje C:

for (inicializacion; condicion_evaluada; incremento_decremento) {
    // Bloque de instrucciones a repetir N veces
}


#### Diagrama de Flujo:
jgh

### 4. Bucles Anidados (Anidamiento de Bucles)

El anidamiento de bucles consiste en colocar un ciclo (bucle interno) dentro del cuerpo de otro ciclo (bucle externo). Por cada única vuelta o iteración que realice el bucle externo, el bucle interno se activará y se ejecutará de forma completa (desde su inicio hasta que su condición deje de cumplirse).

Esta combinación es sumamente útil para trabajar con estructuras bidimensionales (como filas y columnas en una matriz), recorrer bases de datos complejas o dibujar patrones en consola.

#### Estructura en Lenguaje C (Ejemplo con dos bucles for):

for (int i = 1; i <= limite_externo; i++) {
    // Bloque de código del bucle externo (se ejecuta N veces)
    
    for (int j = 1; j <= limite_interno; j++) {
        // Bloque de código del bucle interno (se ejecuta M veces por cada 'i')
        printf("Fila i = %d | Columna j = %d\n", i, j);
    }
}


#### Diagrama de Flujo:
jhf

🔸 Ejercicio con estructura condicional y repetitiva

#### 📝 Planteamiento del Problema
##### Enunciado: 
Un docente de la Universidad Nacional de Loja requiere un programa para calcular el promedio de la nota final ponderada de múltiples estudiantes (el programa debe preguntar la cantidad de alumnos a procesar).

Para cada estudiante se ingresarán las notas de 4 componentes de evaluación académica: ACD (Aprendizaje en Contacto con el Docente), AA (Aprendizaje Autónomo), APE (Aprendizaje Práctico Experimental), y Examen (Examen de Fin de Unidad/Ciclo).

##### El programa debe cumplir obligatoriamente con los siguientes requisitos lógicos:

- Solicitar el número de estudiantes a los cuales se les calculará la nota final.

- Utilizar bucles de post-condición (do-while) para validar individualmente que cada una de las calificaciones ingresadas se encuentre estrictamente dentro del rango de 0 a 10 puntos (si se introduce una nota fuera del rango, se muestra un mensaje de advertencia y se repite el ingreso).

- Calcular la Nota Final ($nF$) mediante las ponderaciones oficiales del ciclo académico actual:

Ponderación ACD: 20% ($0.20$)

Ponderación AA: 20% ($0.20$)

Ponderación APE: 25% ($0.25$)

Ponderación Examen: 35% ($0.35$)

##### Evaluar cualitativamente la calificación de la unidad para cada estudiante con la estructura condicional anidada correspondiente:

- EXCELENTE: $[9.0, 10.0]$

- BUENA: $[7.0, 9.0)$

- REGULAR: $[5.0, 7.0)$

- DEFICIENTE: $[0.0, 5.0)$


#### 🔍 Análisis del Problema


#### 📐 Diseño del Algoritmo




#### Representación en Diagrama de Flujo (Mermaid):



💻 Codificación (Código Fuente en Lenguaje C)


📊 Validación (Prueba de Escritorio)




