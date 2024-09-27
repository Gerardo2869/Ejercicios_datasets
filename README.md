# Ejercicios_datasets
# Machine Learning Project

Este repositorio contiene tres notebooks que implementan diferentes modelos de machine learning para tareas específicas. Los modelos incluyen regresión lineal, KNN, y árboles de decisión, aplicados a datasets de Bitcoin y Pokémon.

## Contenido del repositorio:

- `ArbolDecision_pokemon.ipynb`: Implementa un modelo de árbol de decisión para predecir la clase de un Pokémon (estándar, mítico o legendario).
- `KNN_pokemon.ipynb`: Implementa un modelo K-Nearest Neighbors (KNN) para predecir el tipo de un Pokémon basado en sus atributos.
- `Regresión_lineal_Bitcoin.ipynb`: Utiliza regresión lineal para predecir el precio de Bitcoin en función de datos históricos.

---

## Reporte

### 1. Proceso de selección del dataset

- **Arbol de Decisión y KNN**: Utilizamos un dataset de Pokémon que contiene atributos como ataque, defensa, velocidad, y puntos de vida, entre otros. Para el modelo KNN, se seleccionaron las características relevantes para predecir el tipo de Pokémon (agua, fuego, planta, etc.). En el modelo de árbol de decisión, se utilizaron los mismos atributos, pero el objetivo fue predecir si un Pokémon es de clase estándar, mítico o legendario.
  
- **Regresión Lineal**: El dataset utilizado para la regresión lineal proviene de datos históricos de precios de Bitcoin. Se seleccionaron características como el precio de apertura, el precio máximo, mínimo, y el volumen de transacciones para predecir el precio de cierre de Bitcoin.

### 2. Resultados del entrenamiento del modelo

- **KNN (Pokémon)**: El modelo KNN fue entrenado y probado con una precisión decente al predecir el tipo de Pokémon. Se utilizó una validación cruzada para evaluar el rendimiento del modelo.
  
- **Árbol de decisión (Pokémon)**: El árbol de decisión mostró buenos resultados al clasificar a los Pokémon en las categorías de estándar, mítico y legendario. Se realizó una poda de los nodos para mejorar la precisión y evitar el sobreajuste.
  
- **Regresión Lineal (Bitcoin)**: El modelo de regresión lineal fue capaz de predecir el precio de cierre de Bitcoin con una cierta precisión. El análisis de los residuos mostró que hay ciertas características no lineales que podrían mejorarse en futuros modelos.

### 3. Conclusión

- **KNN**: El modelo KNN funciona bien cuando se trata de predecir el tipo de Pokémon basado en sus características físicas y estadísticas. Sin embargo, la precisión depende mucho de la calidad de los datos y el número de vecinos seleccionados.
  
- **Árbol de decisión**: El árbol de decisión ofrece una forma visual y sencilla de interpretar los resultados. El modelo es útil para hacer clasificaciones de tipo Pokémon, pero puede requerir ajustes adicionales, como la poda de nodos, para mejorar la precisión en datasets más grandes.
  
- **Regresión lineal**: Aunque la regresión lineal es un modelo simple, tiene limitaciones cuando se trata de datos financieros como Bitcoin, donde los precios pueden depender de factores no lineales y externos. Un enfoque más avanzado, como redes neuronales o modelos de series temporales, podría mejorar los resultados.
