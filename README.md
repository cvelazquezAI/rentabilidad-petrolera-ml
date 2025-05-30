# 🛢️ Predicción de Rentabilidad Petrolera – Proyecto de Machine Learning

Este proyecto simula una decisión de inversión para la empresa ficticia **OilyGiant**, que busca abrir 200 nuevos pozos petroleros. El objetivo es **seleccionar la región con mayor rentabilidad esperada y menor riesgo**, utilizando **regresión lineal** y la técnica de **bootstrapping**.

---

## 📁 Descripción de los datos

Se trabajó con tres archivos de datos sintéticos que contienen:

- `id`: Identificador único del pozo
- `f0`, `f1`, `f2`: Características numéricas (anónimas) del pozo
- `product`: Volumen de reservas (en miles de barriles)

---

## 🧠 Herramientas utilizadas

- Python 3
- Pandas, NumPy
- Scikit-learn (Regresión lineal)
- Matplotlib
- Técnica de bootstrapping

---

## 🎯 Objetivo del proyecto

- Predecir el volumen de reservas de nuevos pozos con regresión lineal.
- Seleccionar los 200 pozos más prometedores por región.
- Calcular la ganancia esperada total.
- Determinar la región con mejor rentabilidad y menor riesgo.
- Aplicar **bootstrapping** para estimar el beneficio promedio y riesgo de pérdidas.

---

## 📈 Resultados esperados

- Región seleccionada basada en el **mayor beneficio promedio** y **riesgo < 2.5%**.
- Validación del modelo por RMSE.
- Distribución de beneficios y su intervalo de confianza del 95%.

---

## 📂 Estructura del proyecto

- `data/geo_data_0.csv`
- `data/geo_data_1.csv`
- `data/geo_data_2.csv`
- `src/modelo_regresion.py` – entrenamiento y predicción
- `src/bootstrapping.py` – simulación de ganancias y riesgos

---

## 🧾 Notas

- Datos 100% sintéticos generados para fines educativos
- Proyecto realizado como parte del Sprint 11 de TripleTen

