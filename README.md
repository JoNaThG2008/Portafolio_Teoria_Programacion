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
  📖 1. Desarrollo del Contenido Temático

Haz clic en las secciones a continuación para desplegar la base teórica desarrollada durante esta unidad:

🔸 Estructuras Condicionales

Las estructuras condicionales (o de toma de decisiones) permiten bifurcar el camino de ejecución de un programa dependiendo del valor de verdad de una condición lógica.

Condicionales Simples (if / Si): Evalúan una condición booleana. Si es verdadera, ejecutan un bloque de código exclusivo; si es falsa, el programa continúa ignorando ese bloque.

Condicionales Compuestas (if-else / Si-Sino): Ofrecen dos caminos mutuamente excluyentes. Si la condición es verdadera se ejecuta un bloque; de lo contrario, se ejecuta obligatoriamente un bloque alternativo.

Condicionales Anidadas o Múltiples (if-else if / switch): Permiten anidar condiciones dentro de otras para evaluar múltiples casos posibles de manera secuencial o jerárquica, facilitando la toma de decisiones complejas.

Representación General en Pseudocódigo (Compuesta):

Si (condicion) Entonces
    // Instrucciones si la condición es Verdadera
Sino
    // Instrucciones si la condición es Falsa
FinSi


🔸 Estructuras Repetitivas (Bucles o Ciclos)

Las estructuras repetitivas permiten ejecutar un bloque de instrucciones de manera recurrente mientras una condición lógica preestablecida se mantenga como verdadera.

Bucle Mientras (while / Mientras): Es una estructura de control con pre-condición. Evalúa la condición antes de ejecutar el bloque de instrucciones por primera vez. Si la condición inicialmente es falsa, el ciclo jamás se ejecuta.

Bucle Repetir (do-while / Repetir-Hasta): Es una estructura de control con post-condición. Ejecuta el bloque de código al menos una vez antes de evaluar la condición por primera vez.

Bucle Para (for / Para): Está diseñado para situaciones donde el número de iteraciones se conoce con exactitud de antemano. Utiliza una variable de control o contador interno que se inicializa, valida e incrementa de forma compacta en una sola línea.

Representación General en Pseudocódigo (Bucle Mientras):

Mientras (condicion_de_continuidad) Hacer
    // Bloque de instrucciones a repetir
    // Modificación de la variable de control (para evitar bucles infinitos)
FinMientras


🛠️ 2. Evidencia Práctica o Aplicación (Ejercicio Integrador)

Para evidenciar la comprensión de las estructuras analizadas en esta unidad, se presenta el diseño, diagramación y codificación de un programa que integra estructuras condicionales para evaluar notas y una estructura repetitiva para gestionar múltiples ingresos de estudiantes.

📝 Planteamiento del Problema

Enunciado: Un docente de la Universidad Nacional de Loja requiere un programa para calcular el promedio ponderado de múltiples estudiantes (el programa debe preguntar la cantidad de alumnos a procesar).

Para cada estudiante se ingresarán 3 notas con las mismas ponderaciones de la Unidad 1 (30%, 30% y 40% respectivamente). El programa debe:

Calcular el promedio ponderado de cada alumno.

Utilizar una estructura condicional para determinar si el estudiante aprueba o reprueba la materia (aprueba con una nota final ponderada de $7.0$ o superior).

Utilizar una estructura repetitiva para procesar los datos de los $N$ estudiantes requeridos.

Mostrar al finalizar el proceso el promedio general de todo el curso evaluado.

🔍 Análisis del Problema

Entradas (Datos requeridos):

cantidad_estudiantes (Entero: número total de alumnos a evaluar).

Para cada estudiante $i$: nota1, nota2, nota3 (Números reales).

Procesos (Operaciones):

Ciclo interactivo que se repite $N$ veces.

Cálculo del promedio individual:


$$\text{promedio} = (\text{nota1} \times 0.30) + (\text{nota2} \times 0.30) + (\text{nota3} \times 0.40)$$

Condición de estado:


$$\text{Si } \text{promedio} \ge 7.0 \Rightarrow \text{"Aprobado"}, \text{ Sino } \Rightarrow \text{"Reprobado"}$$

Acumular los promedios individuales para calcular la media del curso:


$$\text{promedio\_general} = \frac{\text{Suma de promedios}}{\text{cantidad\_estudiantes}}$$

Salidas (Resultados en pantalla):

Promedio ponderado y estado (Aprobado/Reprobado) por cada estudiante.

Promedio global del curso.

📐 Diseño del Algoritmo

Representación en Pseudocódigo:

Algoritmo RegistroEstudiantesU2
    Definir cant, i Como Entero
    Definir n1, n2, n3, prom, suma_prom, prom_general Como Real
    
    Escribir "Ingrese la cantidad de estudiantes a registrar:"
    Leer cant
    
    suma_prom <- 0
    i <- 1
    
    Mientras (i <= cant) Hacer
        Escribir "--- Estudiante Nro ", i, " ---"
        Escribir "Ingrese Nota 1 (30%):"
        Leer n1
        Escribir "Ingrese Nota 2 (30%):"
        Leer n2
        Escribir "Ingrese Nota 3 (40%):"
        Leer n3
        
        prom <- (n1 * 0.30) + (n2 * 0.30) + (n3 * 0.40)
        Escribir "Promedio Final del estudiante: ", prom
        
        Si (prom >= 7.0) Entonces
            Escribir "Estado: APROBADO"
        Sino
            Escribir "Estado: REPROBADO"
        FinSi
        
        suma_prom <- suma_prom + prom
        i <- i + 1
    FinMientras
    
    prom_general <- suma_prom / cant
    Escribir "-------------------------------------------"
    Escribir "El promedio general del curso es: ", prom_general
FinAlgoritmo


Representación en Diagrama de Flujo (Mermaid):

graph TD
    A([Inicio]) --> B[/Leer cant/]
    B --> C[suma_prom = 0 <br> i = 1]
    C --> D{¿i <= cant?}
    D -- No --> E[prom_general = suma_prom / cant]
    E --> F[/Mostrar prom_general/]
    F --> G([Fin])
    
    D -- Sí --> H[/Leer n1, n2, n3/]
    H --> I[prom = n1*0.30 + n2*0.30 + n3*0.40]
    I --> J[/Mostrar prom/]
    J --> K{¿prom >= 7.0?}
    K -- Sí --> L[/Mostrar Aprobado/]
    K -- No --> M[/Mostrar Reprobado/]
    L --> N[suma_prom = suma_prom + prom <br> i = i + 1]
    M --> N
    N --> D

    style A fill:#4CAF50,stroke:#388E3C,stroke-width:2px,color:#fff
    style D fill:#FF9800,stroke:#F57C00,stroke-width:2px,color:#fff
    style K fill:#FF9800,stroke:#F57C00,stroke-width:2px,color:#fff
    style G fill:#F44336,stroke:#D32F2F,stroke-width:2px,color:#fff


💻 Codificación (Código Fuente en Lenguaje C)

#include <stdio.h>

int main() {
    int cantidad_estudiantes, i;
    float nota1, nota2, nota3, promedio, suma_promedios = 0.0, promedio_general;

    printf("====================================================\n");
    printf("  SISTEMA REGISTRO DE NOTAS DE LA ASIGNATURA (C)    \n");
    printf("====================================================\n\n");

    printf("Ingrese la cantidad de estudiantes a evaluar: ");
    scanf("%d", &cantidad_estudiantes);

    // Estructura Repetitiva (Controlada por contador)
    for (i = 1; i <= cantidad_estudiantes; i++) {
        printf("\n----------------------------------------------------\n");
        printf("Datos del Estudiante Nro %d:\n", i);
        printf("----------------------------------------------------\n");
        
        printf("Ingrese Nota 1 (30%%): ");
        scanf("%f", &nota1);
        printf("Ingrese Nota 2 (30%%): ");
        scanf("%f", &nota2);
        printf("Ingrese Nota 3 (40%%): ");
        scanf("%f", &nota3);

        // Proceso matemático
        promedio = (nota1 * 0.30) + (nota2 * 0.30) + (nota3 * 0.40);
        printf("-> Promedio Ponderado: %.2f\n", promedio);

        // Estructura Condicional Compuesta
        if (promedio >= 7.0) {
            printf("-> Estado: APROBADO\n");
        } else {
            printf("-> Estado: REPROBADO\n");
        }

        // Acumulación de promedios para el cálculo global
        suma_promedios += promedio;
    }

    // Proceso secuencial final
    if (cantidad_estudiantes > 0) {
        promedio_general = suma_promedios / cantidad_estudiantes;
        printf("\n====================================================\n");
        printf("RESUMEN GENERAL DEL CURSO:\n");
        printf("Total Estudiantes Evaluados: %d\n", cantidad_estudiantes);
        printf("Promedio General del Curso: %.2f\n", promedio_general);
        printf("====================================================\n");
    }

    return 0;
}


📊 Validación (Prueba de Escritorio)

Prueba simulada para $2$ estudiantes registrados (cantidad_estudiantes = 2)

Paso

Cant

i

nota1

nota2

nota3

promedio (Cálculo)

Estado

suma_promedios

Prom. General

Salida en Pantalla

Inicio

2

-

-

-

-

-

-

0.0

-

"Ingrese cant: 2"

1

2

1

8.0

7.0

6.0

$(8 \times 0.3) + (7 \times 0.3) + (6 \times 0.4) = \mathbf{6.9}$

REPROBADO

6.9

-

"Promedio: 6.90. Estado: REPROBADO"

2

2

2

9.0

9.0

10.0

$(9 \times 0.3) + (9 \times 0.3) + (10 \times 0.4) = \mathbf{9.4}$

APROBADO

16.3

-

"Promedio: 9.40. Estado: APROBADO"

3

2

3

(Fin bucle)









16.3

8.15

"Promedio General del Curso: 8.15"

🧠 3. Reflexión Crítica (Unidad 2)

Principales dificultades experimentadas:
Durante la Unidad 2, el grado de abstracción se incrementó significativamente. La principal dificultad consistió en asimilar la lógica de control detrás de los bucles repetitivos y evitar caer en bucles infinitos por omisión de incremento en la variable de control, o por condiciones mal planteadas.

Adicionalmente, comprender las diferencias operativas entre un bucle while (donde la condición puede que nunca se cumpla) y un do-while (que garantiza al menos una ejecución) fue un reto conceptual muy valioso.

Aporte al proceso formativo:
La implementación conjunta de condiciones y repeticiones permitió ver la programación real y dinámica. La asimilación de estos conceptos es trascendental porque abre paso a la creación de aplicaciones versátiles, funcionales e interactivas. Organizar y estructurar la lógica mediante diagramas interactivos antes de plasmar el código final redujo notablemente los errores semánticos en el compilador.

🤖 4. Declaración de Uso de IA Generativa

De conformidad con las políticas éticas y de honestidad académica de la Carrera de Computación de la UNL:

💡 Se declara el uso de la Inteligencia Artificial Generativa Gemini (de Google) como tutor virtual personalizado para esta Unidad 2. Su uso se focalizó en resolver dudas de estructuración del flujo repetitivo, optimizar el diseño adaptativo del portafolio digital, renderizar diagramas de secuencia lógica con Mermaid y guiar el correcto formateo de las fórmulas matemáticas empleando notación científica $\LaTeX$.
