# Análisis de Datos de Embarazadas - Feedback 2

## 📋 Descripción del Proyecto

Análisis exploratorio de datos clínicos y demográficos de embarazadas en Asturias (España). Este trabajo forma parte del Máster en Inteligencia Artificial de la Universidad Alfonso X el Sabio, específicamente de la asignatura **Programación y entorno de trabajo para la IA** (Unidades 4, 5 y 6).

El proyecto responde a una solicitud ficticia de un hospital que requiere integrar datos demográficos con parámetros de laboratorio y realizar un análisis descriptivo completo.

## 🎯 Objetivos

- Unir dos datasets (demográficos + laboratorio) mediante un identificador común
- Limpiar y recodificar variables categóricas según diccionario de datos
- Calcular variables derivadas (colesterol total, tipo de seguimiento ginecológico)
- Generar estadísticas descriptivas completas
- Visualizar distribuciones de parámetros analíticos
- Analizar factores asociados a cesáreas
- Explorar relaciones entre variables antropométricas y hemodinámicas

## 📁 Estructura del Proyecto

.
├── Feedback2-Final.qmd # Documento Quarto con análisis completo
├── Feedback2-Final.html # Informe compilado (output)
├── datos entregable.xlsx # Dataset principal (2 hojas + diccionario)
├── README.md # Este archivo
└── .gitignore # Archivos excluidos de control de versiones

## 🔧 Requisitos

### Software
- **R** ≥ 4.0.0
- **RStudio** (recomendado)
- **Quarto** ≥ 1.3.0

### Paquetes de R
```r
install.packages(c(
  "tidyverse",    # Manipulación y visualización de datos
  "readxl",       # Lectura de archivos Excel
  "janitor",      # Limpieza de nombres de columnas
  "gtsummary",    # Tablas descriptivas profesionales
  "knitr"         # Generación de tablas
))
