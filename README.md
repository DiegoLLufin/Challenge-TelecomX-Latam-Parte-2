# Challenge-TelecomX-Latam-Parte-2

Aplicar técnicas de Machine Learning para predecir si un cliente cancelará el servicio (**Churn**) y evaluar diferentes modelos de clasificación.

## Archivos del repositorio  

- `TelecomX_Part2.ipynb` → Notebook con el flujo completo de modelamiento.
- `df_limpo.csv` → Dataset utilizado.  

---

## Flujo de trabajo  

1. **Carga y exploración de datos**  
   - Lectura del dataset.  
   - Análisis de la distribución de la variable objetivo (`Churn`).  
   - Visualizaciones de variables categóricas y numéricas.  

2. **Preparación de datos**  
   - Eliminación de columnas irrelevantes (`customerID`).  
   - Transformación de variables categóricas a numéricas con OneHotEncoding.  
   - Separación en conjuntos de entrenamiento y prueba.  

3. **Modelado**  
   - Entrenamiento con Regresión Logística.  
   - Entrenamiento con Random Forest.  
   - Comparación con y sin balanceo de clases mediante **SMOTE**.  

4. **Evaluación de modelos**  
   - Métricas: Accuracy, Precision, Recall, F1 y AUC.  
   - Curvas ROC comparativas.  
   - Tabla resumen de resultados.  

5. **Predicciones**  
   - Selección aleatoria de registros del dataset.  
   - Predicción de probabilidad de churn para cada uno.  

6. **Conclusiones**  
   - Identificación del modelo con mejor desempeño.  
   - Observaciones sobre el desbalance de clases y el impacto de SMOTE.  

---

## Requisitos  

- Python 3.10+  
- Librerías:  
  - `pandas`  
  - `numpy`  
  - `scikit-learn`  
  - `imbalanced-learn`  
  - `matplotlib`  
  - `seaborn`
  - `statsmodels`

---

## Ejecución  

1. Abrir el notebook `TelecomX_Part2.ipynb` en Google Colab o Jupyter.  
2. Cargar el archivo `df_limpo.csv`.  
3. Ejecutar las celdas siguiendo el flujo del notebook.
