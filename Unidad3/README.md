<div align="center">

# 📘 Unidad 3
## Modularidad y Arreglos en Lenguaje C

</div>

---

## 📑 Contenido de la Unidad

- 📖 3.1 Modularidad.
  - Concepto.
  - Ventajas.
  - Paso de parámetros por valor.
  - Paso de parámetros por referencia.
  - Ejemplos prácticos.
- 📖 3.2 Arreglos.
  - Arreglos unidimensionales.
  - Arreglos bidimensionales.
  - Arreglos tridimensionales.
  - Ejemplos prácticos.
- 🧠 Principales dificultades y reflexión crítica.
- 🤖 Declaración de uso de Inteligencia Artificial Generativa.

---

# 📖 3.1 Modularidad

La **modularidad** es una técnica de programación que consiste en dividir un programa en funciones o módulos independientes, donde cada uno cumple una tarea específica. Este enfoque permite desarrollar programas más organizados, fáciles de comprender y mantener, además de favorecer la reutilización del código.

Al utilizar funciones, el programa principal se vuelve más claro, ya que cada proceso se ejecuta mediante llamadas a módulos previamente definidos. Esta metodología es ampliamente utilizada en el desarrollo de software debido a que facilita la corrección de errores, la ampliación del programa y el trabajo colaborativo.

## ✅ Ventajas de la modularidad

- Facilita la organización del código.
- Permite reutilizar funciones en diferentes programas.
- Reduce la duplicación de instrucciones.
- Simplifica la detección y corrección de errores.
- Favorece el trabajo en equipo al dividir un programa en módulos independientes.

---

## 🔹 Paso de parámetros por valor

En el **paso por valor**, la función recibe una copia del dato enviado desde el programa principal. Esto significa que cualquier modificación realizada dentro de la función **no afecta** a la variable original.

Este mecanismo resulta útil cuando únicamente se desea utilizar el valor recibido sin alterar la información almacenada en la variable del programa principal.

### 💻 Ejemplo en Lenguaje C

<img width="731" height="522" alt="i1" src="https://github.com/user-attachments/assets/2acf3961-a8a2-44c6-9cae-3416b2bff889" />


### 🖥️ Ejecución del programa
<img width="256" height="67" alt="i6" src="https://github.com/user-attachments/assets/4bf18cae-9bab-4cf7-a636-dc96429ae0ae" />



<p align="center">

---

## 🔹 Paso de parámetros por referencia

En el **paso por referencia**, la función recibe la dirección de memoria de la variable utilizando punteros. Gracias a ello, cualquier modificación realizada dentro de la función afecta directamente al valor original almacenado en el programa principal.

Este tipo de paso de parámetros resulta especialmente útil cuando se desea modificar variables desde una función o trabajar con estructuras de datos de gran tamaño sin realizar copias innecesarias.

### 💻 Ejemplo en Lenguaje C

<img width="682" height="487" alt="i2" src="https://github.com/user-attachments/assets/d04d06b9-7370-4991-af05-c579d52dc5ad" />


### 🖥️ Ejecución del programa

<img width="252" height="47" alt="i7" src="https://github.com/user-attachments/assets/953c2f30-8396-4cbf-b218-e291d856ff2f" />


<p align="center">

---

# 📖 3.2 Arreglos

Los **arreglos** son estructuras de datos que permiten almacenar varios elementos del mismo tipo bajo un único nombre de variable. Cada elemento ocupa una posición específica denominada **índice**, lo que facilita el acceso y manipulación de grandes cantidades de información.

En lenguaje C existen diferentes tipos de arreglos dependiendo del número de dimensiones utilizadas, siendo los más comunes los arreglos unidimensionales, bidimensionales y tridimensionales.

---

## 🔹 Arreglos unidimensionales

Un arreglo unidimensional corresponde a una lista de elementos almacenados de forma consecutiva en memoria. Cada dato puede accederse mediante un único índice, comenzando desde la posición **0**.

Se utilizan principalmente para almacenar listas de números, nombres, calificaciones y otros conjuntos de datos lineales.

### 💻 Ejemplo en Lenguaje C

<img width="497" height="360" alt="i3" src="https://github.com/user-attachments/assets/82530183-79f5-4bb1-91bf-f2007fc89bf0" />


### 🖥️ Ejecución del programa

<img width="212" height="51" alt="i8" src="https://github.com/user-attachments/assets/ce73dae0-e415-4c64-bb48-877babf8f4a0" />


<p align="center">


---

## 🔹 Arreglos bidimensionales

Los arreglos bidimensionales organizan la información en forma de filas y columnas, formando una estructura similar a una tabla o matriz.

Son ampliamente utilizados para representar información tabular, operaciones matemáticas y diferentes problemas donde es necesario trabajar con dos dimensiones.

### 💻 Ejemplo en Lenguaje C

<img width="667" height="641" alt="i4" src="https://github.com/user-attachments/assets/cdec9660-e5fc-41c4-b519-3835bc0f6dfe" />


### 🖥️ Ejecución del programa

<img width="141" height="92" alt="i9" src="https://github.com/user-attachments/assets/7ad7ef91-6678-42ab-8ac7-70f84fdcc698" />


<p align="center">

---

## 🔹 Arreglos tridimensionales

Los arreglos tridimensionales permiten organizar datos en tres dimensiones, agregando un nuevo nivel de almacenamiento respecto a las matrices bidimensionales.

Este tipo de estructura suele utilizarse para representar conjuntos de matrices, imágenes, datos espaciales y otros problemas donde intervienen múltiples niveles de información.

### 💻 Ejemplo en Lenguaje C

<img width="557" height="855" alt="i5" src="https://github.com/user-attachments/assets/89b311bf-ff3f-4d7f-801b-430c7718af09" />


### 🖥️ Ejecución del programa

<img width="295" height="190" alt="i10" src="https://github.com/user-attachments/assets/e959d98a-3249-45d6-84fe-a6afd0bc4437" />


<p align="center">

---

# 🧠 Principales dificultades y reflexión crítica

Durante el desarrollo de esta unidad, una de las principales dificultades fue comprender la forma correcta de dividir un programa en funciones y determinar cuándo utilizar el paso de parámetros por valor o por referencia. Asimismo, el manejo de arreglos bidimensionales y tridimensionales requirió una mayor atención debido a la utilización de múltiples índices para acceder correctamente a cada elemento.

Con la práctica constante fue posible fortalecer la comprensión de estos temas y reconocer la importancia de escribir programas organizados mediante funciones y estructuras de datos adecuadas. Estos conocimientos permiten desarrollar soluciones más claras, reutilizables y eficientes, constituyendo una base fundamental para proyectos de programación de mayor complejidad.

---

<div align="center">

### ✔️ Fin del contenido de la Unidad 3

</div>
