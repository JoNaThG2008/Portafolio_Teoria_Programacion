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


---

#### 1. Condicionales Simples (Si / if)

Evalúan una condición lógica. Si el resultado de la evaluación es Verdadero, se ejecuta un bloque específico de instrucciones. Si es Falso, el programa ignora dicho bloque y continúa con la siguiente línea secuencial de código.


#### Estructura en Pseudocódigo:

<img width="542" height="126" alt="if" src="https://github.com/user-attachments/assets/aa2a3d89-8ebc-4ffe-8e97-ad83200b1957" />


#### Diagrama de Flujo:
(Espacio reservado para tu imagen)

---

### 2. Condicionales Compuestas (Si-Sino / if-else)

Ofrecen dos caminos o alternativas de ejecución mutuamente excluyentes. Si la condición evaluada resulta Verdadero, se ejecuta el primer bloque de instrucciones; si resulta Falso, se ejecuta obligatoriamente el otro bloque de instrucciones.

#### Estructura en Pseudocódigo:

<img width="596" height="187" alt="if_else" src="https://github.com/user-attachments/assets/2aa4a6bb-e8ef-4f1d-acde-313cdc20edf8" />


#### Diagrama de Flujo:
(Espacio reservado para tu imagen)

--- 

### 3. Condicionales Anidadas y Múltiples (if - else if)

Representan la forma de evaluar múltiples condiciones lógicas en cascada. Se ejecutan secuencialmente de arriba hacia abajo; tan pronto como una de las condiciones resulta verdadera, se procesa su bloque correspondiente y se omite el resto de la estructura.

#### Estructura en Pseudocódigo:

<img width="865" height="345" alt="else_if" src="https://github.com/user-attachments/assets/aa325cbb-9209-43c9-923e-fa55137c03a2" />


#### Diagrama de Flujo:
(cdg)
--- 

🔸 Estructuras Repetitivas (Bucles o Ciclos)

Las estructuras repetitivas permiten ejecutar un bloque de instrucciones de manera recurrente mientras una condición lógica preestablecida se mantenga como verdadera. Son indispensables para simplificar la escritura de código iterativo y procesar grandes volúmenes de datos homogéneos.

--- 

### 1. Bucle Mientras (while)

Es una estructura de control con pre-condición. Evalúa la condición al inicio, antes de entrar al bucle. Si la condición resulta verdadera, se ejecuta el bloque de código y vuelve a comprobarse; si la condición es falsa, las instrucciones internas no se ejecutan ninguna vez.

#### Estructura en Lenguaje C:

<img width="660" height="138" alt="while" src="https://github.com/user-attachments/assets/b8cd67fa-fcbd-4cac-b74a-efcbd9a73039" />


#### Diagrama de Flujo:

<img width="672" height="461" alt="dFw" src="https://github.com/user-attachments/assets/f14f665d-b96e-4a63-b06a-cb90e62dc6fd" />



--- 

### 2. Bucle Repetir-Mientras (do-while)

Es una estructura de control con post-condición. A diferencia del ciclo while, este bloque de instrucciones se ejecuta de manera obligatoria al menos una vez antes de evaluar la condición por primera vez. Si tras la ejecución de prueba la condición es verdadera, el ciclo se repite; de lo contrario, finaliza.

#### Estructura en Lenguaje C:

<img width="597" height="130" alt="do_while" src="https://github.com/user-attachments/assets/d07bf89b-56e6-4518-907e-3a9e31bd412d" />


#### Diagrama de Flujo:

<img width="672" height="466" alt="dFdW" src="https://github.com/user-attachments/assets/8b5cbe78-9a09-47bd-aa14-d05170ec8266" />



--- 

### 3. Bucle Para (for)

Es una estructura de control compacta, diseñada específicamente para escenarios donde se conoce el número de iteraciones de antemano. Agrupa de forma estructurada en su cabecera la inicialización de la variable, la condición y el incremento o decremento de dicha variable.

#### Estructura en Lenguaje C:

<img width="647" height="97" alt="for" src="https://github.com/user-attachments/assets/612ce1ea-d8f1-4b8e-b664-86f1d7b931d0" />


#### Diagrama de Flujo:

<img width="681" height="462" alt="dFf" src="https://github.com/user-attachments/assets/23bb6da4-bc98-4508-8dbb-6f6381c5c8aa" />


--- 

### 4. Bucles Anidados (Anidamiento de Bucles)

El anidamiento de bucles consiste en colocar un ciclo (bucle interno) dentro del cuerpo de otro ciclo (bucle externo). Por cada única vuelta o iteración que realice el bucle externo, el bucle interno se activará y se ejecutará de forma completa (desde su inicio hasta que su condición deje de cumplirse).

#### Estructura en Lenguaje C (Ejemplo con dos bucles for):

<img width="798" height="226" alt="for_for" src="https://github.com/user-attachments/assets/d800f695-ce69-4cc1-a42e-afd8f9776de2" />

#### Diagrama de Flujo:

<img width="676" height="457" alt="dFa" src="https://github.com/user-attachments/assets/cf3400f1-c6a6-4c7f-9c53-fc2c75f20ef4" />


--- 

🔸 Ejercicio con estructura condicional y repetitiva

#### 📝 Planteamiento del Problema
##### Enunciado: 
Un docente de la Universidad Nacional de Loja requiere un programa para calcular el promedio de la nota final ponderada de múltiples estudiantes (el programa debe preguntar la cantidad de alumnos a procesar).

Para cada estudiante se ingresarán las notas de 4 componentes de evaluación académica: ACD (Aprendizaje en Contacto con el Docente), AA (Aprendizaje Autónomo), APE (Aprendizaje Práctico Experimental), y Examen (Examen de Fin de Unidad/Ciclo).

##### El programa debe cumplir obligatoriamente con los siguientes requisitos lógicos:

- Solicitar el número de estudiantes a los cuales se les calculará la nota final.

- Utilizar bucles de post-condición (do-while) para validar individualmente que cada una de las calificaciones ingresadas se encuentre estrictamente dentro del rango de 0 a 10 puntos (si se introduce una nota fuera del rango, se muestra un mensaje de advertencia y se repite el ingreso).

- Calcular la Nota Final ($nF$) mediante las ponderaciones oficiales del ciclo académico actual:

   -Ponderación ACD: 20% ($0.20$)

   -Ponderación AA: 20% ($0.20$)

   -Ponderación APE: 25% ($0.25$)

   -Ponderación Examen: 35% ($0.35$)

##### Evaluar cualitativamente la calificación de la unidad para cada estudiante con la estructura condicional anidada correspondiente:

- EXCELENTE: $[9.0, 10.0]$

- BUENA: $[7.0, 9.0)$

- REGULAR: $[5.0, 7.0)$

- DEFICIENTE: $[0.0, 5.0)$


#### 🔍 Análisis del Problema

##### Entradas (Datos requeridos):

nEs (Entero: cantidad total de estudiantes a procesar).

Para cada estudiante ingresado en la iteración: notaACD, notaAA, notaAPE, notaES (Números reales).

##### Procesos (Operaciones):

Un ciclo de control for que itera la variable rep desde 1 hasta el total nEs ingresado.

Bucles do-while internos de validación con expresión condicional de rango: (nota < 0 || nota > 10).

##### Cálculos matemáticos de ponderación individual:


$$pACD = notaACD \times 0.20$$

$$pAA = notaAA \times 0.20$$

$$pAPE = notaAPE \times 0.25$$

$$pEs = notaES \times 0.35$$


##### Cálculo de la Nota Final acumulada:


$$nF = pACD + pAA + pAPE + pEs$$

Clasificación lógica anidada (if-else if-else) según las escalas de evaluación cualitativas indicadas en el problema.

##### Salidas:

Desglose detallado de los promedios ponderados obtenidos.

Nota final resultante.

Valoración de la nota de unidad de los  estudianteas ingresadas.


#### 📐 Diseño del Algoritmo

<img width="635" height="428" alt="Codigo1" src="https://github.com/user-attachments/assets/573760d4-a6c0-467f-9945-4b282a2dde31" />
<img width="635" height="409" alt="Codigo2" src="https://github.com/user-attachments/assets/546faf74-5ae9-47b7-902a-60f5e3166f50" />
<img width="573" height="361" alt="Codigo 3" src="https://github.com/user-attachments/assets/ccff304b-ef26-45bb-bfda-68ec07b66b81" />



#### 💻 Representación en Diagrama de Flujo:

<img width="1167" height="899" alt="dF1" src="https://github.com/user-attachments/assets/b71c716e-0e84-4d9f-8214-83cc8c956b55" />
<img width="1171" height="870" alt="dF2" src="https://github.com/user-attachments/assets/1e83d8a2-862a-442e-bb06-b54254b93bf1" />
<img width="1174" height="458" alt="dF3" src="https://github.com/user-attachments/assets/587f9bd9-2e4b-4cba-89c1-05962d218f5c" />


#### 📊 Prueba de Escritorio

<img width="1162" height="550" alt="pE" src="https://github.com/user-attachments/assets/b6e9e6fb-b8bc-4f24-b61c-c0ec0c4684d4" />


#### 📝 Salida en el Programa
<img width="709" height="214" alt="s1" src="https://github.com/user-attachments/assets/c8769a1c-702b-41d4-ad27-1086ff881fb2" />
<img width="608" height="202" alt="s2" src="https://github.com/user-attachments/assets/393b7e0c-f2bf-4862-b506-e532c6ab8c4a" />
<img width="609" height="238" alt="s3" src="https://github.com/user-attachments/assets/f88aeaa9-71d3-4360-9ccf-4d0cda71aaaa" />
<img width="625" height="107" alt="s4" src="https://github.com/user-attachments/assets/a81790f0-0b0e-4562-8430-d9ec459689f8" />




