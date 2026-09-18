
# Analisis de Patrones de Uso y Modelado Predictivo: Caso Cyclistic
\
## Descripcion del Proyecto\
Este proyecto de Ciencia de Datos analiza los patrones de comportamiento de los usuarios del servicio de bicicletas compartidas Cyclistic (basado en datos reales de Divvy Bikes, Chicago). El objetivo estrategico es proporcionar inteligencia de negocio accionable para maximizar la tasa de conversion de usuarios ocasionales (Casual) a miembros de subcripcion anual (Member).\
\
El analisis procesa mas de 6 millones de registros historicos, abarcando un ciclo anual completo (septiembre 2025 - agosto 2026), e integra tecnicas de mineria de datos, analisis geoespacial y modelado predictivo mediante Machine Learning.\
\
## Objetivos\
1. **Analisis Exploratorio (EDA):** Cuantificar las diferencias en los patrones de uso temporal (duraci\'f3n, demanda semanal y estacionalidad) entre los distintos segmentos de usuarios.\
2. **Topología Geoespacial:** Identificar y mapear las estaciones de mayor demanda para focalizar esfuerzos logísticos y de marketing.
3. **Modelado Predictivo:** Entrenar un algoritmo de clasificación interpretable para predecir el tipo de usuario basado en la telemetría del viaje y extraer la importancia paramétrica de las variables.
\
## Tecnologías y Librerías Utilizadas
* **Lenguaje:** Python 3
* **Manipulación de Datos:** pandas
* **Visualización:** matplotlib, seaborn, folium (mapas interactivos)
* **Machine Learning:** scikit-learn (DecisionTreeClassifier, LabelEncoder, undersampling)
* **Entorno de Desarrollo:** Kaggle Notebooks

## Estructura y Metodología
El proyecto se divide en las siguientes fases metodológicas:
* **Fases 1-4 (Ingeniería de Datos):** Ingesta dinámica de múltiples CSVs (glob), consolidación del dataset (>6M filas), limpieza de valores nulos, conversión de tipos de datos temporales (datetime) y feature engineering.
* **Fases 5-7 (Análisis Descriptivo):** Evaluación de métricas volumétricas y temporales. Generación de cartografía interactiva para el estudio de clústeres de demanda.
* **Fases 8-10 (Machine Learning):** Entrenamiento de un Árbol de Decisión. Identificación de sesgo por clases desbalanceadas. Optimización del modelo mediante técnicas de submuestreo (undersampling) y extracción del Feature Importance.
\
## Hallazgos Clave
* **Dos Arquetipos Inconfundibles:** Se identificó al "Commuter" (Miembro Anual, trayectos cortos, días laborables, zonas financieras) frente al "Explorador" (Usuario Ocasional, trayectos largos, fines de semana, zonas costeras y turísticas).
* **Validación Predictiva:** El modelo de Machine Learning confirmó que la **duración del viaje** (47.6%) y el **día de la semana** (32.7%) son los predictores absolutos del comportamiento del usuario.

## Recomendaciones Estratégicas
Basado en los datos predictivos y descriptivos, se recomienda a la gerencia:
1. Creación de un "Pase de Fin de Semana" (Flex Pass) para captar al usuario turístico.
2. Lanzamiento de campañas de marketing hiper-localizadas mediante geofencing en las 10 estaciones de mayor demanda ocasional durante los fines de semana de primavera y verano.
3. Optimización logística proactiva de la flota de bicicletas basada en los flujos descubiertos.

## tags
data-cleaning, eda, data-visualization, machine-learning, classification, decision-tree

## Autor
**Enrique Medina Galán**
*TFM Especialización en Inteligencia Artificial y Data Science*
