# Decision-Trees-in-Machine-Learning-Classification-Regression-
Exploración práctica de árboles de decisión en Machine Learning. Se incluyen dos notebooks:  Clasificación multiclase de fármacos según características de pacientes.  Regresión de propinas en taxis de NYC. Con métricas, gráficas y análisis interpretables.

## 📊 Proyecto 1: Clasificación de Fármacos  

**Dataset:** `drug200.csv`  
**Objetivo:** Predecir qué medicamento es el más adecuado para un paciente en función de características como **edad, sexo, presión arterial, colesterol y Na/K en sangre**.  

🔹 Técnicas aplicadas:  
- Preprocesamiento de datos categóricos con `LabelEncoder`.  
- Entrenamiento de un **Árbol de Decisión de Clasificación**.  
- Evaluación del modelo con **accuracy, matriz de confusión y classification report**.  
- Visualización del árbol de decisión para interpretar las reglas aprendidas.  

📌 **Resultados:**  
El modelo alcanzó una **precisión del 98%**, mostrando que los árboles de decisión pueden capturar de forma muy eficiente las reglas de decisión en problemas de clasificación multiclase.  

---

## 💵 Proyecto 2: Regresión de Propinas en Taxis NYC  

**Dataset:** Subconjunto público de viajes de taxi en NYC.  
**Objetivo:** Predecir el **importe de la propina (`tip_amount`)** con base en variables como **distancia del viaje, tarifa, peajes, cantidad de pasajeros, localizaciones de origen/destino, entre otras**.  

🔹 Técnicas aplicadas:  
- Análisis de correlación entre variables de entrada y `tip_amount`.  
- Entrenamiento de un **Árbol de Decisión de Regresión**.  
- Evaluación del modelo con métricas de regresión: **MSE, RMSE, MAE y R²**.  
- Gráfica de dispersión entre valores reales y predichos para visualizar la calidad del ajuste.  

📌 **Resultados:**  
El modelo obtuvo un **R² ≈ 0.0**, indicando que las variables disponibles **no explican bien la variabilidad de las propinas**. Esto refleja la naturaleza altamente aleatoria del problema (las propinas dependen de factores externos no capturados en los datos, como comportamiento del pasajero o servicio del conductor).  

---

## 🚀 Conclusiones  

- Los **árboles de decisión** son fáciles de interpretar y útiles tanto en clasificación como en regresión.  
- En problemas de **clasificación estructurada** (como el de los fármacos), los árboles ofrecen resultados excelentes.  
- En problemas con alta variabilidad no explicada (como las propinas), los árboles de regresión muestran limitaciones, pero sirven como punto de partida para probar modelos más robustos (Random Forest, XGBoost).  

---

## 🛠️ Tecnologías utilizadas  

- Python 🐍  
- Scikit-learn  
- Pandas  
- Matplotlib / Seaborn  

---
## Notebooks en Google Colab

- Clasificación de Fármacos  
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mau-lozada/Decision-Trees-in-Machine-Learning-Classification-Regression-/blob/main/Decision_drugTree_.ipynb)

- Regresión de Propinas NYC  
  [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/mau-lozada/Decision-Trees-in-Machine-Learning-Classification-Regression-/blob/main/Decision_taxiTree.ipynb)


---


✍️ *Autor: Mauricio Lozada*  
📌 *Repositorio en construcción para portafolio de Machine Learning.*
