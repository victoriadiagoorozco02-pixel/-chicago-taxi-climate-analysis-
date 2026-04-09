# 🚕 Análisis de duración de viajes de taxi según condiciones climáticas

## 📌 Descripción del proyecto
Este proyecto analiza cómo las condiciones climáticas afectan la duración de los viajes de taxi en la ciudad de Chicago, con el objetivo de identificar patrones relevantes que puedan impactar la operación y la experiencia del usuario.

---

## 🎯 Objetivo
Evaluar si existe una diferencia significativa en la duración de los viajes los sábados en función del clima (lluvioso vs. no lluvioso).

---

## 📊 Dataset
El dataset incluye información sobre:
- Duración de viajes
- Condiciones climáticas
- Fechas y días de la semana

Los datos fueron preprocesados para asegurar su calidad antes del análisis.

---

## 🛠 Herramientas utilizadas
- Python  
- Pandas  
- Matplotlib / Seaborn  
- SciPy  

---

## 🔍 Proceso de análisis

1. Limpieza de datos:
   - Eliminación de valores nulos y duplicados
   - Validación de formatos

2. Análisis exploratorio (EDA):
   - Distribución de duración de viajes
   - Comparación entre condiciones climáticas

3. Análisis estadístico:
   - Formulación de hipótesis
   - Prueba de hipótesis para comparar medias

---

## 📈 Resultados e insights

- Se encontró una diferencia estadísticamente significativa en la duración de los viajes los sábados según las condiciones climáticas.
- En días lluviosos, los viajes duran en promedio **7.1 minutos más** (≈ 427 segundos) en comparación con días sin lluvia.
- Este incremento sugiere un impacto del clima en factores como tráfico y demanda del servicio.

---

## 🚀 Recomendaciones

- Implementar estrategias de **pricing dinámico** en días lluviosos.
- Ajustar la **disponibilidad de conductores** en función de la demanda.
- Mejorar la precisión de los **tiempos estimados de llegada (ETA)** considerando el clima.

---

## 🧪 Conclusión

Las condiciones climáticas tienen un impacto significativo en la duración de los viajes. Este hallazgo permite anticipar cambios en la operación y tomar decisiones para optimizar la eficiencia del servicio y mejorar la experiencia del usuario.

---

## ⚠️ Limitaciones

- El análisis se basa en datos históricos y no considera eventos externos.
- No se incluyeron variables como tráfico en tiempo real o eventos especiales.

---

## 🔮 Próximos pasos

- Incluir variables adicionales como ubicación geográfica y hora del día.
- Analizar patrones de demanda en diferentes zonas.
- Integrar datos en tiempo real para mejorar predicciones.
