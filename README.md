# Análisis del Consumo con Tarjetas de Crédito y Débito en Ecuador

## 🎯 Objetivo

Analizar el comportamiento temporal del consumo realizado mediante tarjetas de crédito y débito en Ecuador durante el período 2021–2025, mediante la construcción y validación de un modelo de series temporales ARIMA que permita describir la dinámica histórica del consumo y generar pronósticos que apoyen el análisis del sistema de pagos electrónicos y la toma de decisiones en el sector financiero.

---

## 📚 Contexto

En la última década, el sistema financiero ecuatoriano ha experimentado una transformación progresiva impulsada por la digitalización de los medios de pago y la creciente adopción de tarjetas de crédito y débito. Este cambio ha reducido gradualmente el uso del efectivo y ha incrementado el volumen de transacciones electrónicas, especialmente en comercios y servicios.

No obstante, a pesar del crecimiento sostenido del consumo con tarjetas, aún persisten desafíos relacionados con la adopción de pagos electrónicos, la planificación financiera y la formulación de políticas basadas en información transaccional confiable y oportuna. En este contexto, el análisis cuantitativo del comportamiento temporal del consumo con tarjetas se convierte en una herramienta clave para comprender tendencias, identificar patrones y anticipar escenarios futuros.

Este proyecto utiliza información estadística oficial publicada por la Superintendencia de Bancos del Ecuador y aplica modelos ARIMA, ampliamente utilizados en el análisis de series temporales financieras, para aportar evidencia empírica sobre la evolución del consumo electrónico en el país.

---

## 🛠️ Metodología

El análisis se desarrolló siguiendo la metodología Box–Jenkins para modelos de series temporales:

- **Datos utilizados**  
  Información mensual del monto facturado por consumos con tarjetas de crédito y débito en Ecuador, correspondiente al período 2021–2025, obtenida de fuentes oficiales.

- **Preprocesamiento de datos**  
  - Extracción y consolidación de datos desde archivos Excel oficiales.  
  - Construcción de una serie temporal mensual.  
  - Verificación de consistencia temporal y valores faltantes.

- **Análisis exploratorio**  
  - Visualización de la serie temporal.
  - Identificación de tendencias y comportamiento general del consumo.

- **Evaluación de estacionariedad**  
  - Aplicación de la prueba de Dickey-Fuller aumentada (ADF).
  - Diferenciación de primer orden para lograr estacionariedad.

- **Identificación y estimación del modelo**  
  - Análisis de correlogramas ACF y PACF.
  - Estimación de distintos modelos ARIMA.
  - Selección del modelo óptimo mediante criterios estadísticos y análisis de residuos.

- **Diagnóstico y validación**  
  - Evaluación del comportamiento de los residuos.
  - Verificación de ruido blanco y ausencia de autocorrelación.

- **Pronóstico**  
  - Generación de proyecciones de consumo para períodos futuros.
  - Visualización de valores históricos, predichos e intervalos de confianza.

---

## 📈 Resultados

El modelo ARIMA seleccionado presentó un ajuste estadísticamente adecuado, con residuos que se comportan como ruido blanco, lo que confirma su validez para describir la dinámica temporal del consumo con tarjetas de crédito y débito en Ecuador.

Los pronósticos generados mantienen la tendencia creciente observada en los datos históricos, lo que refleja la consolidación de los pagos electrónicos como un medio de consumo cada vez más relevante en el sistema financiero nacional. Estos resultados constituyen un insumo valioso para el análisis del sistema de pagos y para la planificación estratégica de las organizaciones financieras.

---

## 📂 Estructura del repositorio

```text
├── ProyectoMBDCapstone.ipynb
├── data/
│   └── Consumos_Tarjetas_Consolidado_2021_2025.xlsx
├── README.md
