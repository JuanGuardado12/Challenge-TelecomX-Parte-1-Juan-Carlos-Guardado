# Challenge-TelecomX-Parte-1-Juan-Carlos-Guardado

# 📡 Análisis de Evasión de Clientes (Churn) - TelecomX 📊

Este proyecto utiliza **Python** y **Pandas** para analizar el comportamiento de los clientes de una empresa de telecomunicaciones. El objetivo principal es identificar patrones que llevan a la cancelación del servicio (Churn) y proponer soluciones estratégicas basadas en datos.

## 🚀 Tecnologías y Herramientas
* **Google Colab** como entorno de desarrollo.
* **Pandas** para manipulación de datos (aplanamiento de JSON y limpieza).
* **Plotly Express** para visualizaciones interactivas.
* **GitHub API** para la carga dinámica de datos.

## 📂 Procesamiento de Datos
El dataset original en formato JSON presentaba una estructura anidada. Los pasos realizados fueron:
1. **Normalización:** Aplanamiento de diccionarios en columnas legibles.
2. **Limpieza:** Conversión de tipos de datos de `object` a `float` para análisis financiero.
3. **Ingeniería de Variables:** Creación de la métrica `Cuentas_Diarias`.
4. **Estandarización:** Traducción de categorías al español y binarización de variables críticas (0 y 1).



## 📈 Hallazgos Principales
* **Contratos:** Los clientes con contratos mensuales tienen una tasa de abandono significativamente mayor que los contratos a largo plazo.
* **Costos:** Existe una correlación directa entre cargos mensuales elevados y la decisión de abandonar el servicio.
* **Métodos de Pago:** El pago mediante cheque electrónico muestra ser un punto de fricción en la retención.



## 💡 Recomendaciones Estratégicas
* Implementar incentivos para la migración de contratos mensuales a anuales.
* Automatizar los métodos de pago manuales para reducir la tasa de fuga.
* Crear un sistema de alertas tempranas para clientes con facturación alta durante sus primeros 6 meses.

---
**Desarrollado por:** [Tu Nombre o Usuario de GitHub]
