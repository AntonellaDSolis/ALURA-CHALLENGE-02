# 📊 TelecomX - Proceso ETL con Python

## 📖 Descripción del proyecto

Este proyecto tiene como objetivo desarrollar un proceso de **ETL (Extract, Transform, Load)** utilizando Python para preparar datos de clientes de la empresa ficticia **TelecomX**.

Los datos se encuentran disponibles en formato **JSON** a través de una API. Debido a que el dataset presenta una estructura jerárquica con múltiples niveles de información, fue necesario realizar un proceso de normalización y transformación para convertir los datos en un formato tabular adecuado para análisis posteriores.

El resultado final es un **dataset limpio, estructurado y listo para análisis**, que permite estudiar el comportamiento de los clientes y analizar factores relacionados con la cancelación del servicio (churn).

---

## 🎯 Objetivos del proyecto

* Extraer datos desde una API en formato JSON
* Transformar estructuras de datos anidadas en un formato tabular
* Limpiar y preparar los datos para análisis
* Convertir tipos de datos y tratar valores nulos
* Generar un dataset estructurado listo para análisis exploratorio

---

## ⚙️ Tecnologías utilizadas

* **Python**
* **Pandas**
* **Requests**
* **Matplotlib**
* **Google Colab / Jupyter Notebook**

---

## 🔄 Proceso ETL

### 1️⃣ Extract (Extracción)

Los datos fueron obtenidos desde una API que contiene información de clientes de TelecomX en formato JSON.

Se utilizó la biblioteca **requests** para realizar la solicitud a la API y **pandas.json_normalize()** para convertir la estructura jerárquica del JSON en un DataFrame.

---

### 2️⃣ Transform (Transformación)

Durante la etapa de transformación se realizaron las siguientes tareas:

* Normalización de datos anidados
* Limpieza y estandarización de nombres de columnas
* Conversión de variables numéricas
* Identificación y tratamiento de valores nulos
* Creación de nuevas variables derivadas

Estas transformaciones permitieron estructurar el dataset en un formato adecuado para análisis y visualización.

---

### 3️⃣ Load (Carga)

Una vez completado el proceso de limpieza y transformación, el dataset final fue almacenado como un archivo **CSV**.

Esto permite reutilizar el dataset limpio para análisis exploratorios, visualizaciones o modelos de machine learning.

---

## 📊 Análisis inicial

Como validación del proceso de ETL, se realizó una visualización básica de la variable **Churn**, que representa si un cliente canceló o no el servicio.

Este análisis preliminar permite observar la distribución de cancelaciones dentro del dataset y confirma que los datos se encuentran preparados para futuros análisis más profundos.

---

## 🧠 Conclusiones

El proceso ETL es una etapa fundamental en cualquier flujo de trabajo de análisis de datos. En este proyecto se demostró cómo transformar un dataset con estructura jerárquica en un formato tabular limpio y organizado.

Las principales transformaciones incluyeron la normalización del JSON, la limpieza de datos y la conversión de tipos de variables. Estas tareas permiten mejorar la calidad del dataset y facilitan el análisis posterior.

El dataset resultante proporciona una base sólida para estudiar el comportamiento de los clientes de TelecomX y analizar factores asociados a la cancelación del servicio.

---

## 📂 Estructura del proyecto

```
TelecomX-ETL/
│
├── TelecomX_LATAM.ipynb
├── TelecomX_clean.csv
├── README.md
```

---

## 👩‍💻 Autor

Proyecto desarrollado como parte del **Challenge de Data Science de Alura LATAM**, enfocado en la práctica del proceso ETL utilizando Python.
