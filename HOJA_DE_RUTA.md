# 🗺️ Hoja de Ruta: NBA Finals Analysis

Este documento sirve como guía paso a paso para completar el caso de estudio, asegurando cubrir todos los criterios de evaluación.

---

## 🏗️ Fase 1: Configuración y Entorno (10%)
*Objetivo: Tener el repositorio listo y conectado.*

- [ ] **Estructura de Carpetas:** Crear `data/`, `notebooks/`, `images/`.
- [ ] **Datos:** Colocar `champs.csv` y `runnerups.csv` en la carpeta `data/`.
- [ ] **Documentación:** Crear `README.md` con la descripción del proyecto.
- [ ] **Diccionario:** Crear `DATA_DICT.md` con la explicación de las variables.
- [ ] **Git:** Clonar repositorio en local y verificar sincronización con VS Code.
- [ ] **Librerías:** Crear archivo `requirements.txt` (pandas, matplotlib, seaborn, scikit-learn).

---

## ⛏️ Fase 2: Data Mining y Análisis Exploratorio (25%)
*Objetivo: Entender los datos y limpiar el dataset.*

- [ ] **Carga de Datos:** Importar CSVs con Pandas.
- [ ] **Unión:** Concatenar tablas de campeones y subcampeones en un solo DataFrame (`df_all`).
- [ ] **Limpieza:** Verificar valores nulos (`isnull`) y tipos de datos (`dtypes`).
- [ ] **Ingeniería de Características (Feature Engineering):**
    - [ ] Crear variable `Total_Possessions` (Estimación de posesiones por partido).
    - [ ] Crear variable `eFG%` (Porcentaje de tiro efectivo).
    - [ ] Crear variable `Efficiency` (Métrica compuesta simple).
- [ ] **Correlaciones:** Generar mapa de calor (Heatmap) para ver correlación con `Win`.

---

## 🤖 Fase 3: Machine Learning (25%)
*Objetivo: Predecir la victoria (`Win`) usando diversos métodos.*

- [ ] **Preprocesamiento:**
    - [ ] Definir variables predictoras (X) y objetivo (y).
    - [ ] Dividir datos: `train_test_split` (80% entreno, 20% test).
- [ ] **Modelo 1: Regresión Logística:**
    - [ ] Entrenar modelo.
    - [ ] Analizar los coeficientes (pesos) de cada variable.
- [ ] **Modelo 2: Random Forest / Árbol de Decisión:**
    - [ ] Entrenar modelo.
    - [ ] Extraer "Feature Importance".
- [ ] **Evaluación:**
    - [ ] Comparar `Accuracy` de ambos modelos.
    - [ ] Generar Matriz de Confusión.

---

## 📊 Fase 4: Visualización y Storytelling (30%)
*Objetivo: Comunicar los hallazgos con gráficos de alta calidad.*

- [ ] **Evolución Histórica:** Gráfico de línea mostrando el aumento de `TPA` (Intentos de triple) por año.
- [ ] **Factor Ganador:** Boxplot comparando `Asistencias` y `Rebotes` entre ganadores y perdedores.
- [ ] **Importancia de Variables:** Gráfico de barras horizontal con las variables más influyentes del modelo Random Forest.
- [ ] **Exportación:** Guardar las gráficas en la carpeta `images/`.

---

## 🏁 Fase 5: Entrega Final (10%)
*Objetivo: Pulir el repositorio para la evaluación.*

- [ ] **Limpieza de Código:** Añadir comentarios explicativos en el Notebook.
- [ ] **README Final:** Actualizar con las conclusiones principales y enlaces a las gráficas.
- [ ] **Push Final:** Sincronizar todo con GitHub.