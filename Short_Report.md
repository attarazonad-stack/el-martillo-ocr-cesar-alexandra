## 📄 Reporte Breve: Análisis OCR de "El Martillo" (Enero 15 de 1916)

### 1. Razón de la Selección de la Página

La página seleccionada corresponde a la edición del **15 de Enero de 1916**. Se eligió por su buen balance entre diferentes tipos de contenido: presenta **artículos** sobre la vida política local ("DESDE ETEN"), contenido de **entretenimiento** ("CUENTO DE LA GUERRA") y una variedad de **anuncios** de negocios locales (fotografía, moda), ofreciendo un panorama amplio de los intereses de la época en Chiclayo.

---

### 2. Desafíos y Distorsiones del OCR

El principal desafío en el proceso de OCR (simulado en este caso, pero común en documentos históricos) es la **calidad de impresión y escaneo**. Distorsiones típicas incluyen:
* **Texto borroso o desvanecido:** La tinta irregular en algunas secciones dificulta la precisión del reconocimiento de caracteres.
* **Tipografía antigua y compacta:** Las fuentes utilizadas en 1916, a menudo con poco espacio entre líneas, pueden llevar a que el OCR combine palabras o mezcle líneas adyacentes (ej. la ortografía y puntuación irregular en el texto).
* **Reconocimiento de caracteres especiales y acentos:** Los errores en la detección de caracteres acentuados o la letra 'ñ' (comunes en textos en español) requieren una fase de normalización intensiva.

---

### 3. Gráfico Sencillo: Distribución de Contenido

A continuación se muestra la distribución de los tipos de contenido por tipo de publicación en la página, utilizando los datos extraídos:

| Tipo de Contenido | Cantidad de Entradas |
| :--- | :--- |
| **article** | 3 |
| **advertisement** | 2 |
| **other** | 2 |

*Nota: La imagen del gráfico de barras se genera en el Notebook de Python y se guarda como `distribution_chart.png`.*

![Gráfico de Distribución de Contenido](distribution_chart.png)

---

### 4. Perspectivas (Insights)

1.  **Enfoque Local y Participación Cívica:** La mayoría de las entradas de tipo 'article' se centran en la sección 'Local', abordando temas de administración pública y asuntos comunitarios (ej. la cooperativa Wizard y la nota "DESDE ETEN"), lo que sugiere que el periódico tenía un rol activo en la **discusión cívica** local.
2.  **Publicidad de Servicios y Consumo:** Las dos entradas de 'advertisement' se centran en servicios de **fotografía** ("FOTOGRAFIA "América"") y artículos de **moda** ("SOMBREROS Ade señora..."), destacando áreas clave de consumo en la sociedad de Chiclayo de principios del siglo XX.
3.  **Contenido de Variedades como Espejo Global:** La sección 'Variedades' incluye una entrada titulada "CUENTO DE LA GUERRA", que, aunque es ficción, probablemente refleja el **interés o la preocupación** de la población chiclayana por los grandes conflictos mundiales de la época (Primera Guerra Mundial).
