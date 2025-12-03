# el-martillo-ocr-cesar-alexandra

## Análisis OCR y Digitalización del Periódico Histórico "El Martillo" (Chiclayo, 1903-1919)

Este repositorio contiene los entregables del proyecto de digitalización y análisis exploratorio de una página escaneada del periódico peruano **"El Martillo"**, publicado en Chiclayo a principios del siglo XX.

El objetivo principal fue transformar el contenido visual de una página histórica en datos estructurados utilizando herramientas de Visión/OCR, y luego obtener perspectivas breves sobre el contenido de la época.

---

## 🎯 Objetivo del Proyecto

1.  **Digitalizar** una página escaneada del periódico "El Martillo" (1903–1919) a texto estructurado.
2.  **Estructurar** el contenido extraído en un formato de datos (`.csv`).
3.  **Analizar** la distribución de secciones y tipos de contenido (artículos, publicidad, otros).
4.  **Generar un informe breve** con insights y desafíos del proceso OCR.

---

## 📂 Contenido del Repositorio

| Archivo | Descripción |
| :--- | :--- |
| **`el_martillo_ocr_notebook.ipynb`** | Cuaderno de Python con el proceso completo: carga de la imagen, (simulación de) extracción OCR, normalización de datos y generación del gráfico de distribución. |
| **`el_martillo_data.csv`** | Conjunto de datos estructurado final, listo para el análisis, con las columnas requeridas (`date`, `headline`, `section`, `type`, etc.). |
| **`short_report.md`** | Informe breve que detalla la selección de la página, los desafíos del OCR, un gráfico sencillo de distribución de contenido y 2-3 insights clave. |
| **`el_martillo.jpg`** | La página escaneada original seleccionada para el análisis (Edición: **Enero 15 de 1916**). |
| **`distribution_chart.png`** | Imagen del gráfico de distribución de tipos de contenido generado por el Notebook. |
| **`README.md`** | Este archivo. |


