# 🧪 Examen Final – Estadística Descriptiva

> **Estudiante:** Guz  
> **Fecha:** Sábado  
> **Formato:** Mixto (conceptual + práctico + interpretativo)  
> **Base de datos:** `Nuevos_datos_ML.txt`  

---

## 📘 Sección I: Fundamentos Conceptuales

**Objetivo:** Evaluar tu comprensión teórica sobre las principales medidas descriptivas.

1. ¿Qué representan los grados de libertad en el cálculo de la varianza muestral?
2. ¿Por qué la Mediana de las Desviaciones Absolutas (MAD) es más resistente que la desviación estándar en presencia de outliers?
3. ¿Cómo interpretar el rango intercuartílico en un conjunto de ingresos?
4. Describe la relación entre moda, mediana y media en distribuciones simétricas y asimétricas.
5. Explica la diferencia conceptual entre varianza poblacional y varianza muestral.

---

## 💻 Sección II: Prueba Técnica en Python

**Objetivo:** Aplicar conocimientos con Pandas, Seaborn y Scipy sobre el archivo `Nuevos_datos_ML.txt`.

1. Calcula la media, mediana y moda del `Ingreso` por `Sexo`. Usa `groupby()` y `.agg()`.
2. Agrupa los datos por rangos de `Edad` utilizando `pd.cut()` con la regla de Sturges. Calcula el ingreso promedio por grupo.
3. Genera un boxplot del ingreso de personas con menos de 5000 pesos, comparado por `Sexo`.
4. Calcula la DMA y la MAD del `Ingreso` para personas con más de 12 años de estudio.
5. Extrae una muestra aleatoria de 20 registros. Calcula media, mediana, desviación estándar y visualiza con `histplot()` y `boxplot()`.

---

## 📊 Sección III: Interpretación Visual

**Objetivo:** Analizar gráficos como herramientas de diagnóstico estadístico.

### 🔍 Pregunta 1

<img width="540" height="149" alt="Image" src="https://github.com/user-attachments/assets/9aa7f6ff-708c-450c-aeab-75fd3fe005f6" />

<img width="540" height="212" alt="Image" src="https://github.com/user-attachments/assets/94546de6-63a2-4211-9c5b-f2fdeccf7415" />

> A partir del gráfico, identifica cuál de los tres tipos de distribución representa mejor los ingresos en el archivo `Nuevos_datos_ML.txt`.
>
> Justifica tu respuesta utilizando media, mediana, moda y rango intercuartílico.

---

### 📚 Pregunta 2

<img width="1114" height="497" alt="Image" src="https://github.com/user-attachments/assets/6417fee0-599e-44ed-9c9a-e94dc512f6da" />

> Observa el gráfico. ¿Cuáles materias están por debajo del estándar de 8?  
> ¿Qué materia tiene mayor dispersión?  
> ¿Qué tipo de visualización en Python replicaría mejor esta gráfica?

---

## 🧭 Sección IV: Análisis Aplicado + Reflexión

**Objetivo:** Vincular técnica estadística con visión social.

> A partir del archivo `Nuevos_datos_ML.txt`, identifica un grupo de personas que presente desigualdad económica.  
>
> Apóyate en medidas de tendencia, dispersión y visualización para sostener tu análisis.  
>
> Finaliza con una reflexión sobre cómo este tipo de análisis podría usarse para influir en políticas públicas o decisiones educativas.

---

## ✅ Indicaciones Finales

- Puedes acompañar tus respuestas con código, gráficos y explicaciones escritas.  
- Usa Markdown para organizar respuestas si lo haces en GitHub.  
- Si usas Jupyter, exporta el archivo como `.html` o `.pdf`.

---
## 🤖 Nota del autor:
Esta evaluación fue creada por la IA de Copilot con base a los temas vistos durante las sesiones de estudio del curso "Estadística con Python: frecuencias y medias"
