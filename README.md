# 🐍 Proyecto 3 — Katas Python

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?style=flat-square&logo=python&logoColor=white)](https://www.python.org/)
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?style=flat-square&logo=jupyter&logoColor=white)](https://jupyter.org/)
[![Ejercicios](https://img.shields.io/badge/Ejercicios-40-success?style=flat-square)]()
[![Estado](https://img.shields.io/badge/Estado-Completado-brightgreen?style=flat-square)]()
[![ASIR](https://img.shields.io/badge/Formación-ASIR-0078D4?style=flat-square)]()

Colección de **40 katas y ejercicios prácticos en Python** desarrollados en un Jupyter Notebook interactivo. Este proyecto forma parte de la formación en **ASIR (Administración de Sistemas Informáticos en Red)** y cubre desde funciones básicas hasta programación orientada a objetos, programación funcional y manejo de excepciones.

---

## 📂 Estructura del Proyecto

```
Proyecto-3-Katas-Python/
│
├── 📓 Katas_Python.ipynb   # Notebook con los 40 ejercicios resueltos
└── 📄 README.md
```

---

## 📋 Ejercicios — Índice Completo

### 🔹 Funciones y Estructuras de Datos

| # | Descripción | Conceptos clave |
|---|---|---|
| 01 | Frecuencia de letras en una cadena | `dict`, bucles, condicionales |
| 03 | Buscar palabras que contengan una subcadena | listas, `in` operator |
| 05 | Calcular media y estado aprobado/suspenso | funciones con parámetro opcional, tuplas |
| 06 | Factorial de un número | **recursividad** |
| 25 | Contar caracteres en un texto | `len()` |
| 27 | Calcular el promedio de una lista | `sum()`, `len()` |
| 28 | Encontrar el primer elemento duplicado | `set`, bucles |
| 29 | Enmascarar texto (estilo tarjeta bancaria) | slicing de strings, `str()` |
| 30 | Determinar si dos palabras son anagramas | `sorted()`, comparación |
| 32 | Buscar empleado en lista de diccionarios | listas de dicts, búsqueda |

### 🔹 Programación Funcional — `map()`

| # | Descripción |
|---|---|
| 02 | Duplicar valores de una lista con `map()` |
| 04 | Diferencia entre elementos de dos listas con `map()` |
| 07 | Convertir lista de tuplas a lista de strings con `map()` |
| 12 | Longitud de cada palabra de una frase con `map()` |
| 13 | Tuplas (mayúscula, minúscula) de caracteres únicos con `map()` |
| 33 | Sumar elementos de dos listas con `map()` (lambda) |

### 🔹 Programación Funcional — `filter()`

| # | Descripción |
|---|---|
| 09 | Filtrar mascotas prohibidas en España con `filter()` |
| 14 | Palabras que comienzan por una letra con `filter()` |
| 16 | Palabras más largas que n caracteres con `filter()` |
| 18 | Estudiantes con calificación ≥ 90 con `filter()` |
| 19 | Filtrar números impares con `filter()` (lambda) |
| 20 | Filtrar solo enteros de una lista mixta con `filter()` |

### 🔹 Programación Funcional — `reduce()`

| # | Descripción |
|---|---|
| 17 | Convertir lista de dígitos a número con `reduce()` |
| 22 | Producto total de una lista con `reduce()` |
| 23 | Concatenar lista de palabras con `reduce()` |
| 24 | Diferencia acumulada de una lista con `reduce()` |

### 🔹 Funciones Lambda

| # | Descripción |
|---|---|
| 15 | Lambda que suma 3 a cada número de una lista |
| 21 | Lambda que calcula el cubo de un número |
| 26 | Lambda que calcula el resto de una división |
| 33 | Lambda que suma elementos de dos listas |

### 🔹 Manejo de Excepciones

| # | Descripción | Tipo de excepción |
|---|---|---|
| 08 | División de dos números con gestión de errores | `ValueError`, `ZeroDivisionError` |
| 10 | Promedio con excepción para lista vacía | Excepción personalizada `ListaVaciaError` |
| 11 | Validar edad del usuario (0–120) | `ValueError`, rango inválido |
| 31 | Buscar nombre en lista o lanzar excepción | Excepción personalizada `NombreNoEncontradoError` |

### 🔹 Programación Orientada a Objetos

| # | Clase | Descripción |
|---|---|---|
| 34 | `Arbol` | Gestión de tronco y ramas: crecer, añadir, quitar |
| 35 | `UsuarioBanco` | Operaciones bancarias: retirar, transferir, agregar dinero |

### 🔹 Lógica y Condicionales

| # | Descripción |
|---|---|
| 36 | `procesar_texto()` — contar, reemplazar y eliminar palabras |
| 37 | Determinar si es día, tarde o noche según la hora |
| 38 | Convertir calificación numérica a texto (Insuficiente → Excelente) |
| 39 | Calcular área de figuras geométricas (rectángulo, círculo, triángulo) |
| 40 | Calcular precio final de una compra aplicando cupón de descuento |

---

## 🚀 Tecnologías Utilizadas

| Tecnología | Uso |
|---|---|
| **Python 3.x** | Lenguaje principal |
| **Jupyter Notebook** | Entorno interactivo con código y salidas visibles |
| **`functools.reduce`** | Ejercicios de reducción funcional |
| **`math`** | Cálculo de áreas con `math.pi` |

---

## ▶️ Cómo Usar el Proyecto

### Opción 1 — Ejecutar en local con Jupyter

```bash
# 1. Clonar el repositorio
git clone https://github.com/diegofonterosa/Proyecto-3-Katas-Python.git
cd Proyecto-3-Katas-Python

# 2. Instalar Jupyter (si no lo tienes)
pip install notebook

# 3. Lanzar el notebook
jupyter notebook Katas_Python.ipynb
```

### Opción 2 — Ejecutar en Google Colab ☁️

Sin instalación, directo desde el navegador:

[![Abrir en Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/diegofonterosa/Proyecto-3-Katas-Python/blob/main/Katas_Python.ipynb)

---

## 🎯 Objetivos de Aprendizaje

- ✅ Dominar funciones, parámetros opcionales y recursividad
- ✅ Aplicar programación funcional con `map()`, `filter()` y `reduce()`
- ✅ Crear y usar funciones `lambda` de forma efectiva
- ✅ Manejar excepciones estándar y personalizadas
- ✅ Diseñar clases con atributos y métodos (POO)
- ✅ Trabajar con strings, listas, diccionarios y conjuntos
- ✅ Desarrollar lógica aplicada a problemas reales

---

## 📋 Requisitos

- [Python 3.8+](https://www.python.org/downloads/)
- [Jupyter Notebook](https://jupyter.org/install) o [JupyterLab](https://jupyterlab.readthedocs.io/)
- Editor recomendado: [VS Code](https://code.visualstudio.com/) con extensión Jupyter

---

## 👨‍💻 Autor

**Diego Pérez Fonterosa**

[![GitHub](https://img.shields.io/badge/GitHub-diegofonterosa-181717?style=flat-square&logo=github)](https://github.com/diegofonterosa)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Diego%20Pérez-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/diegofonterosa)

> Cursando ASIR y Máster en Ciberseguridad

---

## 📄 Licencia

Este proyecto tiene fines educativos. Puedes usar, modificar y distribuir el código con libertad mencionando al autor original.
