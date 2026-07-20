<div align="center">

# 📘 Unidad 2
## Estructuras Condicionales y Repetitivas

</div>

---

## 📑 Contenido de la Unidad

- 📖 Estructuras Condicionales.
  - Condicional Simple (if).
  - Condicional Compuesta (if-else).
  - Condicionales Anidadas y Múltiples (if - else if).
- 📖 Estructuras Repetitivas.
  - Bucle while.
  - Bucle do-while.
  - Bucle for.
  - Bucles Anidados.
- 💻 Desarrollo de un ejercicio utilizando estructuras condicionales y repetitivas.
- 🧠 Reflexión crítica.
- 🤖 Declaración de uso de IA Generativa.

---

# 📖 2.1 Estructuras Condicionales

Las **estructuras condicionales** permiten que un programa tome decisiones a partir de la evaluación de una condición lógica. Dependiendo de si la condición es **verdadera** o **falsa**, el programa ejecutará un conjunto específico de instrucciones.

Estas estructuras son esenciales para desarrollar programas capaces de adaptarse a diferentes situaciones y responder de manera dinámica a los datos ingresados por el usuario.

---

## 🔹 Condicional Simple (if)

La estructura **if** evalúa una condición lógica. Cuando dicha condición es verdadera, se ejecuta un bloque de instrucciones; si es falsa, el programa continúa normalmente sin ejecutar dicho bloque.

Esta estructura se utiliza cuando solamente es necesario realizar una acción en caso de cumplirse una determinada condición.

### 📄 Estructura en Pseudocódigo

<img width="542" height="126" alt="if" src="https://github.com/user-attachments/assets/aa2a3d89-8ebc-4ffe-8e97-ad83200b1957" />

### 🔄 Diagrama de Flujo

<img width="668" height="457" alt="dIf" src="https://github.com/user-attachments/assets/743c9e31-f768-4a2d-bb97-e13fdd6efe66" />

---

## 🔹 Condicional Compuesta (if - else)

La estructura **if-else** ofrece dos caminos posibles de ejecución. Si la condición evaluada resulta verdadera, el programa ejecuta el primer bloque de instrucciones; en caso contrario, ejecutará el segundo bloque.

Este tipo de estructura permite controlar situaciones donde existen únicamente dos posibles respuestas.

### 📄 Estructura en Pseudocódigo

<img width="596" height="187" alt="if_else" src="https://github.com/user-attachments/assets/2aa4a6bb-e8ef-4f1d-acde-313cdc20edf8" />

### 🔄 Diagrama de Flujo

<img width="662" height="460" alt="dIe" src="https://github.com/user-attachments/assets/942fae9a-a9c0-45e7-b97d-780cd62cb3b7" />

---

## 🔹 Condicionales Anidadas y Múltiples (if - else if)

Cuando un problema requiere evaluar varias condiciones diferentes, se utilizan las estructuras **if - else if**. Las condiciones se revisan de forma secuencial hasta encontrar la primera que sea verdadera; una vez encontrada, se ejecuta únicamente ese bloque de instrucciones.

Esta estructura facilita la toma de decisiones múltiples dentro de un mismo algoritmo.

### 📄 Estructura en Pseudocódigo

<img width="865" height="345" alt="else_if" src="https://github.com/user-attachments/assets/aa325cbb-9209-43c9-923e-fa55137c03a2" />

### 🔄 Diagrama de Flujo

<img width="665" height="452" alt="dIeI" src="https://github.com/user-attachments/assets/e5dd64fa-66a4-406a-be7f-02412710fcdc" />

---

# 📖 2.2 Estructuras Repetitivas

Las **estructuras repetitivas**, también conocidas como **bucles o ciclos**, permiten ejecutar un conjunto de instrucciones varias veces mientras se cumpla una condición determinada.

Su utilización evita repetir código innecesariamente y facilita el procesamiento de grandes cantidades de información, haciendo que los programas sean más eficientes y fáciles de mantener.

---

## 🔹 Bucle while

El ciclo **while** es una estructura repetitiva con **precondición**, lo que significa que la condición se evalúa antes de ejecutar el bloque de instrucciones. Si la condición es falsa desde el inicio, el cuerpo del ciclo nunca llegará a ejecutarse.

### 📄 Estructura en Lenguaje C

<img width="660" height="138" alt="while" src="https://github.com/user-attachments/assets/b8cd67fa-fcbd-4cac-b74a-efcbd9a73039" />

### 🔄 Diagrama de Flujo

<img width="672" height="461" alt="dFw" src="https://github.com/user-attachments/assets/f14f665d-b96e-4a63-b06a-cb90e62dc6fd" />

---

## 🔹 Bucle do-while

El ciclo **do-while** posee una **postcondición**, por lo que el bloque de instrucciones se ejecuta obligatoriamente al menos una vez antes de evaluar la condición.

Este tipo de ciclo resulta útil cuando es necesario garantizar que una acción se realice como mínimo una vez.

### 📄 Estructura en Lenguaje C

<img width="597" height="130" alt="do_while" src="https://github.com/user-attachments/assets/d07bf89b-56e6-4518-907e-3a9e31bd412d" />

### 🔄 Diagrama de Flujo

<img width="672" height="466" alt="dFdW" src="https://github.com/user-attachments/assets/8b5cbe78-9a09-47bd-aa14-d05170ec8266" />

---

## 🔹 Bucle for

El ciclo **for** es una estructura diseñada para situaciones donde se conoce previamente el número de repeticiones que realizará el programa.

Su sintaxis reúne en una sola línea la inicialización de la variable de control, la condición de repetición y el incremento o decremento de dicha variable.

### 📄 Estructura en Lenguaje C

<img width="647" height="97" alt="for" src="https://github.com/user-attachments/assets/612ce1ea-d8f1-4b8e-b664-86f1d7b931d0" />

### 🔄 Diagrama de Flujo

<img width="681" height="462" alt="dFf" src="https://github.com/user-attachments/assets/23bb6da4-bc98-4508-8dbb-6f6381c5c8aa" />

---

## 🔹 Bucles Anidados

Los **bucles anidados** consisten en colocar un ciclo dentro de otro. Por cada iteración del ciclo externo, el ciclo interno se ejecuta completamente.

Esta técnica es ampliamente utilizada para recorrer matrices, generar patrones y resolver problemas que requieren múltiples niveles de repetición.

### 📄 Estructura en Lenguaje C

<img width="798" height="226" alt="for_for" src="https://github.com/user-attachments/assets/d800f695-ce69-4cc1-a42e-afd8f9776de2" />

### 🔄 Diagrama de Flujo

<img width="676" height="457" alt="dFa" src="https://github.com/user-attachments/assets/cf3400f1-c6a6-4c7f-9c53-fc2c75f20ef4" />

---
# 💻 Desarrollo del ejercicio

## 📝 Planteamiento del problema

Desarrollar un programa que permita al usuario ingresar la posición de un número en la sucesión de **Fibonacci** y mostrar el valor correspondiente.

El programa debe validar que la posición ingresada sea un número entero **mayor o igual a cero**, garantizando así que el cálculo pueda realizarse correctamente utilizando una estructura repetitiva.

---

## 🔍 Análisis del problema

| Elemento | Descripción |
|:---------|-------------|
| **Entrada** | Posición del número Fibonacci (**n**). |
| **Proceso** | Validar el dato ingresado. Si **n = 0**, mostrar 0; si **n = 1**, mostrar 1; en cualquier otro caso calcular el término utilizando un ciclo **for**. |
| **Salida** | Número correspondiente a la posición **n** de la sucesión de Fibonacci. |

---

## 📐 Diseño del algoritmo

El algoritmo utiliza una estructura repetitiva **for**, permitiendo calcular cada término de la sucesión a partir de la suma de los dos valores anteriores.

### 📄 Pseudocódigo

<img width="761" height="627" alt="efibo" src="https://github.com/user-attachments/assets/69fda244-c2f4-4c5d-88be-7b200ad184ff" />

---

## 🔄 Diagrama de Flujo

El siguiente diagrama representa gráficamente el proceso utilizado para calcular el número de Fibonacci solicitado por el usuario.

<img width="702" height="701" alt="dfor" src="https://github.com/user-attachments/assets/6e855ed2-7683-4130-862d-214c0261c93a" />

---

## ✔️ Validación (Prueba de escritorio)

### Datos de entrada

```text
n = 6
```

### Desarrollo

| Paso | Contador | Anterior 1 | Anterior 2 | Resultado |
|:----:|:---------:|:----------:|:----------:|:---------:|
| Inicialización | — | 0 | 1 | — |
| Iteración 1 | 2 | 1 | 1 | 1 |
| Iteración 2 | 3 | 1 | 2 | 2 |
| Iteración 3 | 4 | 2 | 3 | 3 |
| Iteración 4 | 5 | 3 | 5 | 5 |
| Iteración 5 | 6 | 5 | 8 | **8** |

### Resultado obtenido

```text
Salida: 8
```

---

## 📊 Verificación

La sucesión de Fibonacci inicia de la siguiente manera:

| Posición | Valor |
|:--------:|:-----:|
| 0 | 0 |
| 1 | 1 |
| 2 | 1 |
| 3 | 2 |
| 4 | 3 |
| 5 | 5 |
| 6 | **8** |

Por lo tanto, para la entrada **n = 6**, el programa devuelve correctamente el valor **8**, confirmando que el algoritmo funciona según lo esperado.

---

# 🧠 Reflexión crítica

Durante el desarrollo de esta unidad, la principal dificultad fue comprender el funcionamiento de las estructuras condicionales y repetitivas, ya que cada una responde a situaciones diferentes dentro de un programa. Al inicio resultó complejo identificar cuál era la estructura más adecuada para resolver cada problema y controlar correctamente el flujo de ejecución.

Con la práctica constante fue posible fortalecer el razonamiento lógico y comprender la importancia de analizar previamente un problema antes de escribir el código. La resolución de ejercicios utilizando **if**, **if-else**, **while**, **do-while** y **for** permitió desarrollar una mejor capacidad para construir algoritmos organizados, eficientes y fáciles de comprender.

Esta unidad representó un paso importante dentro del aprendizaje de la programación estructurada, ya que introdujo herramientas fundamentales para resolver problemas de mayor complejidad.

---

# 🤖 Declaración de uso de Inteligencia Artificial Generativa

Durante la elaboración de esta unidad se utilizaron herramientas de Inteligencia Artificial, principalmente **Gemini** y **ChatGPT**, como apoyo al proceso de aprendizaje.

Su utilización estuvo orientada a:

- Resolver dudas sobre los contenidos estudiados en clase.
- Verificar la lógica de los programas desarrollados en lenguaje **C**.
- Comprobar la correcta elaboración de las pruebas de escritorio.
- Mejorar la organización y presentación del portafolio digital utilizando **Markdown**.

El uso de estas herramientas tuvo únicamente fines educativos y de apoyo, respetando en todo momento los principios de integridad académica.

---

<div align="center">

### ✔️ Fin del contenido de la Unidad 2

</div>
