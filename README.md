# interpretabilidad_Lime_Shap

## Proyecto 2: Interpretabilidad de Modelos con LIME y SHAP

### Descripción General:
Este proyecto se enfoca en la Interpretabilidad de Modelos Predictivos (XAI). Se utilizó un dataset de salud cardíaca (heart.csv) para construir un modelo de clasificación y luego aplicar las herramientas LIME y SHAP para obtener explicaciones locales (predicciones individuales) y globales (importancia de las características), fundamentales para la confianza en contextos de toma de decisiones sensibles.

### Objetivos del Proyecto:
* Construir, entrenar y evaluar un modelo de clasificación predictiva.
* Aplicar la librería SHAP para entender la contribución marginal y global de cada característica a las predicciones.
* Utilizar la herramienta LIME para generar explicaciones fáciles de entender a nivel de instancias individuales.
* Analizar el modelo desde una perspectiva de sesgo y ética, proponiendo medidas concretas para mejorar la equidad.

### Tecnologías Clave:
* Categoría	Herramientas Específicas
* Lenguaje	Python
* ML & Análisis	scikit-learn, pandas, numpy
* Explicabilidad	LIME, SHAP
* Deep Learning	torch

### Características Destacadas:
* Análisis Dual de XAI: Aplicación y comparación de dos de las metodologías de interpretabilidad más importantes: LIME (explicaciones locales, basadas en perturbaciones) y SHAP (explicaciones basadas en Teoría de Juegos).
* Balance Ético-Predictivo: Evaluación de la eliminación de variables sensibles ('Sexo', 'Edad') para mitigar el sesgo, sopesando el trade-off con el rendimiento predictivo.
* Propuestas de Mitigación: Generación de un análisis de las implicaciones éticas y una propuesta estructurada para mejorar la justicia del sistema.

### Reflexión: Desafíos y Aprendizaje:
* El principal desafío fue navegar el dilema ético del trade-off entre rendimiento (precisión) y equidad (mitigación de sesgos). Se aprendió que la simple eliminación de variables sensibles rara vez resuelve el sesgo, ya que otras variables pueden actuar como proxies. Las herramientas como SHAP no solo explican la predicción, sino que también son cruciales para identificar estos proxies de sesgo indirecto. Este proyecto reforzó la necesidad de una vigilancia constante sobre la equidad y la transparencia en la IA de salud.

[Ir al Código en Colab] → https://colab.research.google.com/drive/11PfECUwWIEDLgV6kec3bLNssCib4Ej1u?usp=sharing
