# 👁️ Detección de Retinopatía Diabética

![Streamlit](https://img.shields.io/badge/Streamlit-App%20Deployment-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-Deep%20Learning-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Keras](https://img.shields.io/badge/Keras-Neural%20Networks-D00000?style=for-the-badge&logo=keras&logoColor=white)
![Python](https://img.shields.io/badge/Python-3.9%2B-blue?style=for-the-badge&logo=python&logoColor=white)

## 🏥 Contexto Médico y Problema

La **Retinopatía Diabética (RD)** es una complicación de la diabetes que daña los vasos sanguíneos de la retina y es una de las principales causas de ceguera irreversible a nivel mundial.

El diagnóstico tradicional es manual, lento y requiere oftalmólogos altamente especializados, lo que dificulta el cribado masivo (screening) en zonas con recursos limitados.

**El Objetivo:** Desarrollar un modelo de Inteligencia Artificial capaz de analizar datos clínicos/imágenes y clasificar automáticamente la presencia de la enfermedad, sirviendo como una herramienta de apoyo al diagnóstico (**CDSS**) para agilizar el tratamiento.

---

## 🛠️ Metodología y Flujo de Trabajo

### 1. Procesamiento de Datos Médicos
* **Limpieza y Preprocesamiento:** Normalización de las características extraídas de los exámenes de fondo de ojo para eliminar ruido y valores atípicos.
* **Análisis Exploratorio (EDA):** Estudio de la distribución de clases (Sano vs. Enfermo) para detectar desequilibrios que pudieran sesgar el modelo.

### 2. Modelado Predictivo
Se implementó un clasificador supervisado para distinguir entre pacientes sanos y con retinopatía.
* **Enfoque:** Se priorizó la capacidad del modelo para generalizar patrones complejos asociados a lesiones retinianas (como microaneurismas o exudados).
* **Validación:** Uso de validación cruzada para asegurar que el modelo sea robusto ante nuevos pacientes.

### 3. Métricas de Evaluación (Enfoque Clínico)
En medicina, no todos los errores pesan igual. Se optimizó el modelo priorizando el **Recall (Sensibilidad)**.
* **¿Por qué Recall?** Es crítico minimizar los *Falsos Negativos*. Decirle a un paciente enfermo que está "Sano" podría costarle la visión por falta de tratamiento. Es preferible tener una falsa alarma (Falso Positivo) que dejar pasar un caso real.

---

## 💡 Impacto Social

Este proyecto demuestra el potencial de la IA en la salud pública:
1.  **Democratización del Acceso:** Permite realizar pre-diagnósticos en áreas rurales sin especialistas permanentes.
2.  **Eficiencia Hospitalaria:** Actúa como filtro para que los oftalmólogos se concentren en los casos positivos detectados por el algoritmo.
3.  **Prevención:** Facilita la detección temprana, clave para evitar la ceguera.

---

## 🚀 Tecnologías Utilizadas

* **Lenguaje:** Python 3.x
* **Análisis de Datos:** Pandas, NumPy.
* **Machine Learning:** Scikit-Learn (Clasificación y Métricas).
* **Visualización:** Matplotlib, Seaborn.

---

### 👤 Autor

**Stephany Marilyn Toribio Alvarado**
* *Data Scientist | HealthTech Enthusiast*
* [LinkedIn](https://www.linkedin.com/in/stephany-marilyn-toribio-alvarado-47080b303/) | [Portafolio](https://stephany-toribio.github.io/MWeb/)
