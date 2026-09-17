# 🏀 Minado y predicción del NBA All-Star utilizando Machine Learning y p-valor

### Tesis de Máster en Ciencia de Datos — Tilburg University

## 📌 Sobre el proyecto

Proyecto desarrollado a partir de una idea propia: analizar hasta qué punto los datos de rendimiento permiten predecir qué jugadores serán seleccionados para el NBA All-Star y estudiar, mediante modelos estadísticos, la posible existencia de sesgos en el proceso de selección.
Una parte central del trabajo fue la **construcción del dataset desde cero**, integrando y limpiando distintas fuentes de información sobre jugadores, temporadas y selecciones All-Star entre **1996 y 2022**.

El proyecto abarca el pipeline completo de Ciencia de Datos:

**Obtención de datos → Limpieza e integración → Análisis → Machine Learning → Evaluación → Análisis estadístico**

## 🤖 Resultados

Se compararon **Logistic Regression, Decision Tree y Random Forest**.

El mejor modelo fue **Random Forest**, alcanzando:

- **93% de accuracy** en test
- **0.83 macro average**
- **0.68 de rendimiento en la clase positiva**
- **0.98 de rendimiento en la clase negativa**

Además de la predicción, el proyecto exploró si determinadas características estaban asociadas con diferencias entre las predicciones basadas en datos y las selecciones reales.

El análisis encontró una asociación estadísticamente significativa para **college (p = 0.011)**, abriendo una discusión sobre la relación entre **rendimiento, percepción y decisiones humanas**, y dejando entrever posibles decisiones de selección que van más allá del rendimientos deportivos en determinadas decisiones.

## 🛠️ Tecnologías

**Python · Pandas · Scikit-learn · Matplotlib · SciPy · Machine Learning · Estadística**
