# 📊 Análisis de Empleados - Jupyter Notebook

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter)
![Pandas](https://img.shields.io/badge/Pandas-1.x-green?logo=pandas)
![SQLite](https://img.shields.io/badge/SQLite-3.x-red?logo=sqlite)

Este proyecto en Jupyter Notebook permite realizar un análisis exploratorio sobre datos salariales de empleados públicos, incluyendo beneficios, horas extra y cargos. Se enfoca en obtener estadísticas relevantes como los mejores pagados, cargos más comunes, y promedios por año.

---

## 🚀 Requisitos

Antes de correr este notebook, asegurate de tener lo siguiente instalado:

- 🐍 [Python 3.x](https://www.python.org/downloads/)
- 📦 [Pandas](https://pandas.pydata.org/docs/getting_started/install.html)
- 📘 [Jupyter Notebook](https://jupyter.org/install)

---

## 📥 Clonar el repositorio

Usá este comando para clonar el repositorio.

```bash
git clone https://github.com/Alexis217/pandas_df_tlp3_Alexis_Albarenga.git
```

#### 🚀 Pasos para ejecutar el proyecto

```bash
# Pasos para ejecutar el proyecto
 - [1] crear un entorno virtual
 - # si estas en windows py -m venv env && .\env\Scripts\activate
 - # si estas en linux o mac python3 -m venv env && source env/bin/activate
 - [2] instalar pandas
 - # pip install pandas
 - [3] Abrí el archivo `actividad_df.ipynb`
 - [4] Ejecutá cada celda en orden
 - [4] Analizá los resultados y salidas
```

---

## 📈 Actividades vistas en el proyecto

🔟 **Top 10 empleados con mayor salario total**  
Se extrajeron los 10 empleados con mayor `TotalPayBenefits`, es decir, salario total incluyendo beneficios.

💵 **Filtrar empleados con más de $50,000 en horas extra**  
Se filtraron todos los empleados cuya columna `OvertimePay` supera los 50,000 USD.

🧑‍💼 **Contar empleados únicos por año**  
Se contó la cantidad de empleados únicos registrados en cada año del dataset.

🧾 **Cargos únicos y los 5 más comunes**  
Se contabilizaron los cargos únicos (`JobTitle`) y se listaron los 5 más frecuentes.

📊 **Salario total promedio por año**  
Se calculó el promedio de `TotalPay` para cada año.

📤 **Exportar a CSV y mostrar últimos registros**  
Todos los datos fueron exportados a un archivo CSV. También se mostraron los últimos 10 registros del dataset.

---

## 📌 Créditos

📅 **Fecha de entrega:** 30 Abril 2025
👨‍💻 **Autor:** [Alexis Albarenga](https://github.com/Alexis217)
🏫 **Trabajo práctico - Python para Ciencia de Datos**

---
