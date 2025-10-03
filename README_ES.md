📖 Descripción

Este proyecto tiene como objetivo desarrollar modelos de aprendizaje automático capaces de identificar automáticamente si una reseña de película es positiva o negativa utilizando técnicas de Procesamiento de Lenguaje Natural (NLP).  
Se probaron y compararon diferentes algoritmos de clasificación, logrando un F1-score superior a 0.85 en el conjunto de prueba.

## 🗂️ Conjunto de Datos

- Tamaño: 50.000 reseñas etiquetadas (positivas = 1, negativas = 0)  
- División: conjuntos de entrenamiento y prueba ya definidos  

## ⚙️ Etapas del Proyecto

**Carga y Limpieza de Datos**

- Eliminación de stopwords y caracteres especiales  
- Tokenización y lematización  

**Vectorización de Texto**

- Bag of Words (BoW)  
- TF-IDF  

**Entrenamiento de Modelos**

- Regresión Logística  
- Random Forest  
- Gradient Boosting (LightGBM)  

**Evaluación**

- Métrica principal: F1-score  
- Comparación de desempeño entre modelos  

**Validación con Ejemplos Reales**

- Creación de reseñas ficticias para validación práctica  

## 📊 Resultados

- Mejor desempeño: Gradient Boosting  
- F1-score en la prueba: > 0.85  
- Los modelos demostraron buena generalización a nuevos textos  

## 🛠️ Tecnologías Utilizadas

- Python 3.10  
- Pandas, NumPy  
- Scikit-learn  
- NLTK / SpaCy  
- LightGBM  

## ✍️ Autor

Proyecto desarrollado como parte de la formación en Data Science de TripleTen.
