# Redes_Neuronales_Mantenimiento_Flotas.
Predicción de mantenimiento para flotas usando redes neuronales. Entrena un modelo con variables como kilometraje, horas motor y vibración. Cuaderno listo para Google Colab.
# Redes Neuronales para Mantenimiento Predictivo de Flotas

Este repositorio contiene un cuaderno interactivo para **Google Colab** donde se aplica un modelo de **red neuronal artificial** para predecir si un vehículo de una flota requiere mantenimiento próximo. El modelo está entrenado con variables operativas como kilometraje, horas del motor, temperatura, vibración y tiempo desde el último mantenimiento.

---

##  Objetivo

- Aplicar machine learning para mantenimiento predictivo.
- Entrenar un modelo de red neuronal utilizando `TensorFlow/Keras`.
- Evaluar el desempeño con métricas de clasificación.
- Facilitar el análisis a partir de datos operativos históricos de flotas.

---

##  Dataset requerido

El archivo CSV debe incluir al menos las siguientes columnas:

- `Vehiculo_ID`
- `Kilometraje`
- `Horas_motor`
- `Temperatura_motor`
- `Vibracion_promedio`
- `Ultimo_mantenimiento`
- `Falla_proxima` *(etiqueta: 0 o 1)*

> Puedes usar el archivo de ejemplo disponible aquí:  
>  [flota_mantenimiento.csv](https://...)

---

##  Tecnologías utilizadas

- Python 3
- Google Colab
- TensorFlow / Keras
- Scikit-learn
- Pandas, NumPy, Matplotlib, Seaborn

---

##  ¿Cómo usar este proyecto?

1. **Clona o descarga este repositorio.**

```bash
git clone https://github.com/tuusuario/Mantenimiento_Predictivo_Flotas.git
