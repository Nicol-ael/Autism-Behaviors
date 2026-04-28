

## 📸 Demo

(demoo.png)


---

## 📊 Descripción del proyecto

Este proyecto consiste en un **análisis exploratorio de datos (EDA)** enfocado en el Trastorno del Espectro Autista (ASD), integrando procesamiento en Python y modelado analítico en Power BI.

Se analizan variables demográficas, clínicas y comportamentales con el objetivo de identificar patrones diferenciales entre población con ASD y sin ASD.

---

## 🎯 Objetivo

Analizar y comparar características entre individuos con ASD y sin ASD, explorando cómo variables como edad, sexo, tipo de evaluador y comportamientos influyen en el diagnóstico.

---

## 🧩 Flujo del proyecto

1. Limpieza y transformación de datos en Python
2. Modelado de datos (modelo estrella) en Power BI
3. Creación de métricas analíticas en DAX
4. Construcción de dashboard interactivo

---

## 🗂️ Modelo de datos

Se implementó un **modelo estrella** para optimizar el análisis:

* **dim_demographic**

  * Edad, sexo, etnia, ictericia
  * Clasificación ASD
  * Total de traits y nivel

* **dim_Who_take_test**

  * Tipo de evaluador

* **facts_behaviors**

  * Variables comportamentales (10)
  * Valores binarios (1/0) por individuo

---

## 🐍 Procesamiento en Python

El procesamiento en Python se centró en la preparación y calidad de los datos:

* Selección de variables relevantes
* Limpieza y estandarización de datos
* Eliminación de duplicados
* Transformación de variables
* Creación de nuevas estructuras de datos
* Preparación del dataset para Power BI

---

## 📊 Modelado y análisis en Power BI

### 🔹 Métricas en DAX

* Prevalencia de ASD
* Comparaciones ASD vs No ASD
* Promedios de traits
* Distribución de comportamientos

### 🔹 Dashboard interactivo

* KPIs principales
* Comparación entre grupos
* Segmentación por edad, sexo, etnia y evaluador

---

## 📈 Hallazgos clave

* Los individuos con ASD presentan **valores más altos en todos los rasgos evaluados**
* Las mayores diferencias se observan en **contacto visual, gestos y comportamiento social**
* Mayor concentración de casos ASD alrededor de los **2 años**
* Mayor prevalencia en **niños**
* El tipo de evaluador influye en los resultados (familia vs profesional)
* Los niveles medio y alto concentran la mayoría de casos ASD

---

## 🛠️ Tecnologías utilizadas

* Python (pandas, numpy)
* Power BI (modelo estrella, DAX, visualización)

---

## 📌 Conclusiones

El análisis muestra diferencias claras entre ASD y No ASD, tanto en rasgos como en comportamientos y variables demográficas.

La integración de múltiples dimensiones permite una visión más completa del diagnóstico y su comportamiento.

---

## 🚧 Futuras mejoras

* Modelos predictivos de clasificación ASD
* Análisis más profundo de comportamientos
* Integración de nuevas variables clínicas

---

## 👤 Autor

**Nicol Escobar**

* 🐙 GitHub: https://github.com/Nicol-ael
* 💼 LinkedIn: https://www.linkedin.com/in/nicolescobardatayhealthcare/
* ✉️ Email: [nicolescobar3330@gmail.com](mailto:nicolescobar3330@gmail.com)

---
