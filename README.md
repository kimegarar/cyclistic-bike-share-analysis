{\rtf1\ansi\ansicpg1252\cocoartf2513
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fmodern\fcharset0 Courier;}
{\colortbl;\red255\green255\blue255;\red0\green0\blue0;}
{\*\expandedcolortbl;;\cssrgb\c0\c0\c0;}
\paperw11900\paperh16840\margl1440\margr1440\vieww10800\viewh8400\viewkind0
\deftab720
\pard\pardeftab720\partightenfactor0

\f0\fs24 \cf2 \expnd0\expndtw0\kerning0
\outl0\strokewidth0 \strokec2 # An\'e1lisis de Patrones de Uso y Modelado Predictivo: Caso Cyclistic\
\
## Descripci\'f3n del Proyecto\
Este proyecto de Ciencia de Datos analiza los patrones de comportamiento de los usuarios del servicio de bicicletas compartidas Cyclistic (basado en datos reales de Divvy Bikes, Chicago). El objetivo estrat\'e9gico es proporcionar inteligencia de negocio accionable para maximizar la tasa de conversi\'f3n de usuarios ocasionales (Casual) a miembros de suscripci\'f3n anual (Member).\
\
El an\'e1lisis procesa m\'e1s de 6 millones de registros hist\'f3ricos, abarcando un ciclo anual completo (septiembre 2025 - agosto 2026), e integra t\'e9cnicas de miner\'eda de datos, an\'e1lisis geoespacial y modelado predictivo mediante Machine Learning.\
\
## Objetivos\
1. **An\'e1lisis Exploratorio (EDA):** Cuantificar las diferencias en los patrones de uso temporal (duraci\'f3n, demanda semanal y estacionalidad) entre los distintos segmentos de usuarios.\
2. **Topolog\'eda Geoespacial:** Identificar y mapear las estaciones de mayor demanda para focalizar esfuerzos log\'edsticos y de marketing.\
3. **Modelado Predictivo:** Entrenar un algoritmo de clasificaci\'f3n interpretable para predecir el tipo de usuario basado en la telemetr\'eda del viaje y extraer la importancia param\'e9trica de las variables.\
\
## Tecnolog\'edas y Librer\'edas Utilizadas\
* **Lenguaje:** Python 3\
* **Manipulaci\'f3n de Datos:** pandas\
* **Visualizaci\'f3n:** matplotlib, seaborn, folium (mapas interactivos)\
* **Machine Learning:** scikit-learn (DecisionTreeClassifier, LabelEncoder, undersampling)\
* **Entorno de Desarrollo:** Kaggle Notebooks\
\
## Estructura y Metodolog\'eda\
El proyecto se divide en las siguientes fases metodol\'f3gicas:\
* **Fases 1-4 (Ingenier\'eda de Datos):** Ingesta din\'e1mica de m\'faltiples CSVs (glob), consolidaci\'f3n del dataset (>6M filas), limpieza de valores nulos, conversi\'f3n de tipos de datos temporales (datetime) y feature engineering.\
* **Fases 5-7 (An\'e1lisis Descriptivo):** Evaluaci\'f3n de m\'e9tricas volum\'e9tricas y temporales. Generaci\'f3n de cartograf\'eda interactiva para el estudio de cl\'fasteres de demanda.\
* **Fases 8-10 (Machine Learning):** Entrenamiento de un \'c1rbol de Decisi\'f3n. Identificaci\'f3n de sesgo por clases desbalanceadas. Optimizaci\'f3n del modelo mediante t\'e9cnicas de submuestreo (undersampling) y extracci\'f3n del Feature Importance.\
\
## Hallazgos Clave\
* **Dos Arquetipos Inconfundibles:** Se identific\'f3 al "Commuter" (Miembro Anual, trayectos cortos, d\'edas laborables, zonas financieras) frente al "Explorador" (Usuario Ocasional, trayectos largos, fines de semana, zonas costeras y tur\'edsticas).\
* **Validaci\'f3n Predictiva:** El modelo de Machine Learning confirm\'f3 que la **duraci\'f3n del viaje** (47.6%) y el **d\'eda de la semana** (32.7%) son los predictores absolutos del comportamiento del usuario.\
\
## Recomendaciones Estrat\'e9gicas\
Basado en los datos predictivos y descriptivos, se recomienda a la gerencia:\
1. Creaci\'f3n de un "Pase de Fin de Semana" (Flex Pass) para captar al usuario tur\'edstico.\
2. Lanzamiento de campa\'f1as de marketing hiper-localizadas mediante geofencing en las 10 estaciones de mayor demanda ocasional durante los fines de semana de primavera y verano.\
3. Optimizaci\'f3n log\'edstica proactiva de la flota de bicicletas basada en los flujos descubiertos.\
\
## Autor\
**Enrique Medina Gal\'e1n**\
*Especializaci\'f3n en Inteligencia Artificial y Data Science*\
}