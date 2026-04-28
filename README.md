# 🏡 Zonaprop Scraper

Script en Python para extraer, procesar y analizar propiedades desde archivos HTML descargados de Zonaprop.

Diseñado para ejecutarse en **Google Colab** o entorno local, procesando múltiples páginas almacenadas en un `.zip`.

---

## 🚀 Funcionalidades

- 📦 Lectura automática de archivos HTML desde un ZIP
- 🏠 Extracción de propiedades:
  - Tipo (Casa / Departamento)
  - Precio en USD
  - m²
  - Ambientes
  - Dormitorios
  - Baños
  - Cocheras
  - Dirección
  - Ubicación (barrio)
- 🧹 Limpieza de datos:
  - Eliminación de duplicados
- 📊 Análisis de mercado:
  - Precio por m²
  - Promedios por zona y tipo
  - Detección de oportunidades (propiedades subvaluadas)
- 📁 Exportación a Excel profesional con múltiples hojas:
  - Propiedades
  - Estadísticas por zona
  - Oportunidades
  - Resumen

---

## 📂 Estructura esperada

El script espera un archivo:
