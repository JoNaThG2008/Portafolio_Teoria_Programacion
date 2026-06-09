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
    <h3>📖 Contenido de la Unidad 1</h3>
    Unidad 1: Introducción a la Lógica y Estructuras Secuenciales

⬅️ Volver a la Portada Principal

📖 1. Desarrollo del Contenido Temático

Haz clic en las secciones a continuación para desplegar la base teórica desarrollada durante esta unidad:

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

🛠️ 2. Evidencia Práctica o Aplicación (Estructura Secuencial)

En esta sección se documenta el diseño y codificación de un algoritmo estructurado de naturaleza secuencial, donde cada instrucción se ejecuta de manera ordenada una tras otra.

📝 Planteamiento del Problema

Enunciado: Un alumno necesita calcular el promedio final de sus tres notas. Cada nota tiene una ponderación diferente:

Primera nota: 30% ($0.30$)

Segunda nota: 30% ($0.30$)

Tercera nota: 40% ($0.40$)

Se desea obtener el promedio final ponderado del estudiante.

🔍 Análisis del Problema

Entradas (Datos requeridos): * nota1 (Número real: primera calificación).

nota2 (Número real: segunda calificación).

nota3 (Número real: tercera calificación).

Proceso (Fórmulas de cálculo):


$$\text{promedio} = (\text{nota1} \times 0.30) + (\text{nota2} \times 0.30) + (\text{nota3} \times 0.40)$$

Salida (Resultado esperado): * promedio (Número real: promedio final ponderado).

📐 Diseño del Algoritmo

Representación en Pseudocódigo:

Algoritmo CalcularPromedioPonderado
    Definir nota1, nota2, nota3, promedio Como Real
    
    Escribir "Ingrese la calificación de la Nota 1 (30%):"
    Leer nota1
    Escribir "Ingrese la calificación de la Nota 2 (30%):"
    Leer nota2
    Escribir "Ingrese la calificación de la Nota 3 (40%):"
    Leer nota3
    
    promedio <- (nota1 * 0.30) + (nota2 * 0.30) + (nota3 * 0.40)
    
    Escribir "El promedio final ponderado es: ", promedio
FinAlgoritmo


Representación en Diagrama de Flujo (Mermaid):

Este diagrama se genera y renderiza dinámicamente en GitHub:

graph TD
    A([Inicio]) --> B[/Leer nota1, nota2, nota3/]
    B --> C[promedio = nota1 * 0.30 + nota2 * 0.30 + nota3 * 0.40]
    C --> D[/Mostrar promedio/]
    D --> E([Fin])
    
    style A fill:#4CAF50,stroke:#388E3C,stroke-width:2px,color:#fff
    style B fill:#2196F3,stroke:#1976D2,stroke-width:2px,color:#fff
    style C fill:#FF9800,stroke:#F57C00,stroke-width:2px,color:#fff
    style D fill:#2196F3,stroke:#1976D2,stroke-width:2px,color:#fff
    style E fill:#F44336,stroke:#D32F2F,stroke-width:2px,color:#fff


💻 Codificación (Código Fuente en Lenguaje C)

A continuación, se detalla la traducción formal de la lógica del algoritmo secuencial al Lenguaje C:

#include <stdio.h>

int main() {
    // Declaración de variables para almacenar notas y el promedio final
    float nota1, nota2, nota3, promedio;

    printf("===========================================\n");
    printf("     SISTEMA DE CALCULO DE PROMEDIOS UNL    \n");
    printf("===========================================\n\n");

    // Entrada de datos del estudiante
    printf("Ingrese la Nota 1 (Ponderacion 30%%): ");
    scanf("%f", &nota1);

    printf("Ingrese la Nota 2 (Ponderacion 30%%): ");
    scanf("%f", &nota2);

    printf("Ingrese la Nota 3 (Ponderacion 40%%): ");
    scanf("%f", &nota3);

    // Proceso secuencial: Cálculo del promedio ponderado
    promedio = (nota1 * 0.30) + (nota2 * 0.30) + (nota3 * 0.40);

    // Salida de resultados
    printf("\n-------------------------------------------\n");
    printf("El promedio final ponderado es: %.2f\n", promedio);
    printf("===========================================\n");

    return 0;
}


📊 Validación (Prueba de Escritorio)

Iteración / Caso

Nota 1

Nota 2

Nota 3

Cálculo Realizado

Promedio Final

Caso 1

8.0

9.0

10.0

$(8 \times 0.30) + (9 \times 0.30) + (10 \times 0.40) = 2.4 + 2.7 + 4.0$

9.1

Caso 2

7.0

8.0

9.0

$(7 \times 0.30) + (8 \times 0.30) + (9 \times 0.40) = 2.1 + 2.4 + 3.6$

8.1

Caso 3

10.0

10.0

10.0

$(10 \times 0.30) + (10 \times 0.30) + (10 \times 0.40) = 3.0 + 3.0 + 4.0$

10.0

🧠 3. Reflexión Crítica

Principales dificultades y reflexión crítica en la aplicación de los contenidos:
Durante el desarrollo de la unidad se presentaron diversas dificultades, como la comprensión inicial de algunos de los conceptos básicos, además de que en un inicio, resultó complicado diferenciar entre la forma teórica (pseudocódigo) y la forma práctica (código en lenguaje C).

Otra dificultad fue la correcta interpretación de los problemas, ya que no siempre era sencillo identificar las entradas, procesos y salidas. Esto ocasionaba errores al momento de diseñar el algoritmo o realizar la prueba de escritorio.

Sin embargo, a medida que se avanzó con la práctica, se logró mejorar la capacidad de análisis y la organización lógica de las soluciones. El uso de ejercicios secuenciales permitió comprender mejor la estructura básica de un programa y la importancia de seguir un orden adecuado en las instrucciones.

Importancia formativa:
Como reflexión, estos contenidos son importantes porque son la base de la programación. Aprender a organizar un algoritmo antes de programar ayuda a hacer programas más claros y ordenados. Además, el uso de herramientas digitales y la inteligencia artificial ayudó a entender mejor los temas y resolver dudas.

🤖 4. Declaración de Uso de IA Generativa

De conformidad con los lineamientos éticos de la Carrera de Computación de la Universidad Nacional de Loja, se declara formalmente:

💡 Se utilizó Gemini (modelo de lenguaje de Google) como tutor de acompañamiento durante el desarrollo de esta unidad. Su intervención se limitó a brindar soporte en el aprendizaje de la sintaxis Markdown, organizar visualmente los componentes del portafolio digital, estructurar el diagrama dinámico mediante Mermaid, y actuar como herramienta de verificación lógica para corroborar el correcto cálculo de los casos de prueba de escritorio planteados.

📚 5. Bibliografía (Formato IEEE)

[1] Material de clase de la asignatura Teoría de la Programación, proporcionado por la docente, UNL, 2026.

[2] Apuntes personales del estudiante, elaborados durante el desarrollo de la asignatura Teoría de la Programación, 2026.

[3] Universidad Internacional de La Rioja, "¿Qué es un algoritmo?", Revista de Ingeniería y Tecnología. [En línea]. Disponible en: https://unirfp.unir.net/revista/ingenieria-y-tecnologia/que-es-algoritmo/

[4] Ciberaula, "Pseudocódigo: qué es y cómo escribirlo con ejemplos claros". [En línea]. Disponible en: https://www.ciberaula.com/cursos/java/pseudolenguaje_1.php

[5] Universidad Internacional de La Rioja (UNIR México), "¿Qué es un diagrama de flujo y para qué sirve?". [En línea]. Disponible en: https://mexico.unir.net/noticias/ingenieria/diagrama-flujo/

[6] Scribd, "¿Qué es la prueba de escritorio en seudocódigo?". [En línea]. Disponible en: https://es.scribd.com/document/463660396/Que-Es-La-Prueba-de-Escritorio-en-Seudocodigo

<details>
  <summary>📂 <b>Unidad 2: Estructuras Condicionales y Repetitivas</b></summary>
  <br>
  <blockquote>
