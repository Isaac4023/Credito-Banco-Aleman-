# 🏦 Crédito Banco Alemán  
### Predicción de aprobación de crédito con Machine Learning

Proyecto académico desarrollado en **Google Colab** para analizar datos de clientes y construir modelos de Machine Learning capaces de predecir la probabilidad de aprobación de crédito.

📍 Notebook en Google Colab:  
https://colab.research.google.com/drive/1E9mrxjhF1Pk8cUekRoJulGUH-05e9833?usp=sharing

---

## 📌 Descripción del Proyecto

Este proyecto tiene como objetivo analizar un conjunto de datos financieros y construir modelos predictivos que ayuden a determinar qué clientes tienen mayor probabilidad de recibir un crédito.

El desarrollo se realizó completamente en **Google Colab**, utilizando Python y librerías estándar de ciencia de datos.

El proyecto incluye:

- Análisis exploratorio de datos (EDA)
- Limpieza y preprocesamiento
- Entrenamiento de modelos de clasificación
- Evaluación mediante métricas y visualizaciones

---

## 🚀 Cómo Ejecutar el Proyecto (Deploy)

Este proyecto **no requiere instalación local**.

Para ejecutarlo:

1. Haz clic en el siguiente enlace:
   👉 https://colab.research.google.com/drive/1E9mrxjhF1Pk8cUekRoJulGUH-05e9833?usp=sharing

2. Inicia sesión con tu cuenta de Google.

3. Si deseas modificarlo:
   - Ve a **Archivo → Guardar una copia en Drive**.

4. Ejecuta las celdas en orden presionando:
   - `Shift + Enter`
   o
   - Botón ▶️ de cada celda.

Google Colab ya incluye la mayoría de librerías necesarias, por lo que no es necesario instalar dependencias manualmente.

---

## 🛠 Tecnologías Utilizadas

- Python 3
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- XGBoost (si fue utilizado)

---

## 📊 Flujo de Trabajo en el Notebook

### 1️⃣ Carga de Datos

- Importación de librerías necesarias:
  - pandas
  - numpy
  - sklearn
  - matplotlib
  - seaborn
- Lectura del archivo CSV o DataFrame desde Google Drive.
- Visualización inicial del dataset.
- Revisión de dimensiones y tipos de datos.

---

### 2️⃣ Exploratory Data Analysis (EDA)

En esta etapa se realiza un análisis exploratorio para entender el comportamiento de los datos:

- Estadísticas descriptivas básicas (`mean`, `median`, `std`, etc.).
- Visualización de distribuciones de variables numéricas.
- Análisis de correlaciones.
- Detección de valores faltantes.
- Identificación de posibles outliers.
- Análisis de la variable objetivo (aprobado/no aprobado).

Este paso permite comprender qué variables pueden influir más en la decisión de crédito.

---

### 3️⃣ Preprocesamiento

Antes de entrenar los modelos se realiza:

- Tratamiento de valores nulos.
- Encoding de variables categóricas (Label Encoding o One-Hot Encoding).
- Normalización o estandarización de variables numéricas.
- Separación entre variables independientes (X) y variable objetivo (y).

---

### 4️⃣ Modelado

Se implementan modelos de clasificación para predecir la aprobación de crédito.

Proceso:

- División del dataset en:
  - Conjunto de entrenamiento
  - Conjunto de prueba
- Entrenamiento de uno o varios modelos como:
  - Regresión Logística
  - Random Forest
  - XGBoost
- Ajuste de hiperparámetros cuando es necesario.
- Comparación del desempeño entre modelos.

---

### 5️⃣ Evaluación

Para medir el rendimiento del modelo se utilizan métricas como:

- Accuracy
- Precision
- Recall
- F1-score
- ROC-AUC

También se incluyen visualizaciones como:

- Matriz de confusión
- Curva ROC
- Comparación gráfica entre modelos

Esto permite seleccionar el modelo con mejor desempeño para el problema.

---

## 📈 Resultados

El modelo final permite:

- Identificar clientes con mayor probabilidad de aprobación.
- Analizar qué variables influyen más en la decisión.
- Obtener métricas claras para evaluar la confiabilidad del modelo.

---

## 📚 Aprendizajes del Proyecto

Durante el desarrollo se reforzaron conceptos como:

- Limpieza y preparación de datos
- Análisis exploratorio
- Modelos de clasificación
- Evaluación de métricas
- Interpretación de resultados en problemas financieros

---

## 🔮 Posibles Mejoras Futuras

- Implementar validación cruzada.
- Aplicar técnicas de balanceo como SMOTE.
- Probar modelos adicionales (LightGBM, CatBoost).
- Exportar el modelo entrenado.
- Crear una pequeña API para predicción.

---

## 👨‍💻 Autor

Isaac Delgado  
GitHub: https://github.com/Isaac4023  

---

## 📄 Licencia

Proyecto desarrollado con fines académicos.
