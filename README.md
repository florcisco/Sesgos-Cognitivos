# 🧠 Sesgos Cognitivos en Razonamientos Lógicos

![Python](https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data_Analysis-150458?logo=pandas)
![Scikit-learn](https://img.shields.io/badge/Scikit--Learn-Machine_Learning-F7931E?logo=scikitlearn)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-0A0A0A?logo=plotly)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical_Plots-4C9A2A?logo=seaborn)
![Google Colab](https://img.shields.io/badge/Google_Colab-Notebook-FFCB2B?logo=googlecolab&logoColor=black)

---

## 🎯 Descripción General
En cada momento, nuestras decisiones se ven afectadas por distintos motivos, algunos que poco tienen que ver con la decisión en sí.
En este proyecto, analizamos como el conocimiento previo que uno puede tener lleva a generar algunos errores.
Los errores debido a estos motivos se encuadran dentro de los llamados **sesgos cognitivos**, que afectan el **razonamiento lógico**
La intención del trabajo es evidenciar como este conocimiento previo lleva a la **aceptación de premisas falsas** y el **rechazo de premisas verdaderas**.  
El objetivo fue explorar la relación entre **creencias**, **validez**, **modalidad de resolución** y **respuestas correctas**, aplicando técnicas de análisis de datos y modelado predictivo.

---

## ⚙️ Flujo de Trabajo
El proyecto fue desarrollado íntegramente en **Python**, siguiendo un pipeline analítico completo:

1. **Carga y limpieza de datos**
   - Normalización de nombres, tipos y categorías  
   - Tratamiento de valores ausentes

2. **Análisis exploratorio (EDA)**
   - Identificación de tipos de variables  
   - Cálculo de medidas de **tendencia**, **dispersión** y **distribución**
   - Visualizaciones con **Matplotlib** y **Seaborn**

3. **Feature Engineering**
   - Conversión entre variables categóricas y numéricas  
   - Creación de un **índice de creencia** cuantitativo  
   - Reducción de casos comunes para resaltar variaciones significativas

4. **Modelado predictivo**
   - Construcción de un **modelo base**  
   - Optimización de hiperparámetros con **Grid Search** y **Random Search**
   - Evaluación de desempeño mediante métricas:
     - **MAE (Mean Absolute Error)**  
     - **MSE (Mean Squared Error)**  
     - **RMSE (Root Mean Squared Error)**

5. **Comparación y selección**
   - Comparativa entre modelos  
   - Selección final según error y capacidad de generalización

---

## 🧠 Conocimientos Aplicados
- Exploratory Data Analysis (EDA)
- Ingeniería de características (*Feature Engineering*)
- Modelado y evaluación de predicciones
- Optimización de hiperparámetros
- Visualización de relaciones entre variables
- Análisis de desempeño con métricas estadísticas

---

## 🧰 Stack Tecnológico
| Categoría | Librerías |
|------------|------------|
| Manipulación de datos | `pandas`, `numpy` |
| Visualización | `matplotlib`, `seaborn` |
| Modelado y evaluación | `scikit-learn` |
| Optimización | `GridSearchCV`, `RandomizedSearchCV` |

---

📊 Resultados Destacados

Identificación de la relación entre creencia y validez lógica

Construcción de un índice de creencia medible y predecible

Mejora en el desempeño del modelo tras la optimización de hiperparámetros

Comparativa de modelos según métricas de error (MAE, MSE, RMSE)
