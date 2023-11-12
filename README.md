# costos-medicos-LinearRegression
analisis de gastos Médicos

Proyecto de Análisis y Predicción de Costos Médicos
Este proyecto utiliza técnicas de análisis exploratorio de datos (EDA) y regresión lineal para explorar y predecir los costos médicos en función de diversas variables. El conjunto de datos utilizado es el archivo insurance.csv, que contiene información sobre pacientes, incluyendo edad, género, índice de masa corporal (BMI), número de hijos, si son fumadores, región y costos médicos.

Contenido del Proyecto
Exploración de Datos (EDA):

Visualización de la distribución de la edad y costos médicos.
Identificación y manejo de valores atípicos en los costos médicos.
Exploración de las relaciones entre variables utilizando un pairplot y un mapa de calor de correlación.
Preprocesamiento de Datos:

One-Hot Encoding para las variables categóricas.
Escalado de variables numéricas utilizando StandardScaler.
Modelo de Regresión Lineal:

Entrenamiento de un modelo de regresión lineal utilizando variables preprocesadas.
Evaluación del modelo utilizando el Error Cuadrático Medio (MSE) y R cuadrado (R²).
Feature Engineering:

Creación de nuevas variables como age^2, sobrepeso y sobrepeso*fumador.
Reentrenamiento del modelo y evaluación de su desempeño.
Análisis Adicional:

Exploración de la relación entre las variables sobrepeso*fumador, smoker, age^2, children y los costos médicos.
Reentrenamiento del modelo y evaluación del desempeño con el nuevo conjunto de variables.

Instrucciones de Uso:

1. Clona el repositorio en tu máquina local

2. Abre el notebook Proyecto_Machine_Learning.ipynb en Jupyter Notebook o Jupyter Lab.

3. Ejecuta cada celda en secuencia para reproducir los resultados.

Dependencias
pandas
seaborn
matplotlib
numpy
scikit-learn
regressors

Instala las dependencias utilizando   pip install pandas seaborn matplotlib numpy scikit-learn regressors

¡Espero que disfrutes explorando y desarrollando este proyecto! Siéntete libre de hacer ajustes y mejoras según sea necesario.