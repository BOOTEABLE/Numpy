# 🐍 Dominando NumPy: De Listas a Computación Científica

Este repositorio contiene un cuaderno de Google Colab detallado con la teoría y práctica esencial para dominar **NumPy**, la librería fundamental para el análisis de datos y computación científica en Python.

## 🚀 Contenido del Notebook

El material está organizado de forma progresiva, ideal para estudiantes de Ingeniería o Ciencia de Datos:

### 1. Fundamentos y Creación
* **Listas vs Arrays:** Comparativa de rendimiento y gestión de memoria contigua.
* **Constructores:** Uso de `np.array()`, `np.zeros()`, `np.ones()`, `np.eye()` y `np.full()`.
* **Secuencias y Aleatoriedad:** Diferencias entre `arange` y `linspace`, y generación de números aleatorios con semillas reproducibles (`np.random.seed`).

### 2. Atributos y Estructura
Exploración de las propiedades internas de los objetos `ndarray`:
* `.shape`, `.ndim`, `.size` para dimensiones.
* `.dtype`, `.itemsize`, `.nbytes` para el control del consumo de memoria.
* La transpuesta con `.T`.

### 3. Manipulación de Datos
* **Slicing Avanzado:** Extracción de sub-matrices y elementos específicos.
* **Máscaras Booleanas:** Filtrado de datos mediante condiciones lógicas.
* **Broadcasting:** Cómo NumPy realiza operaciones entre arrays de diferentes dimensiones de forma eficiente.
* **Reshape y Concatenación:** Reorganización de datos en matrices y tensores, y unión de bloques con `hstack` y `vstack`.

### 4. Vistas vs. Copias
* Explicación crítica sobre por qué modificar un *slice* afecta al original y cómo evitarlo usando `.copy()` de forma explícita.

## 🛠️ Buenas Prácticas Incluidas
El código sigue estándares profesionales como:
* Reinicio de runtime para asegurar integridad.
* Uso de semillas para resultados reproducibles.
* Verificación constante de `.shape` y `.dtype`.
* Preferencia de `.ravel()` sobre `.flatten()` para optimización de memoria.

---
*Apuntes desarrollados para la materia de Programación - Universidad Politécnica Salesiana (UPS).*
