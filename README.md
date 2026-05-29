
## Análisis de Movilidad vs. Desarrollo Económico (PIB)
Este proyecto analiza la relación entre el Producto Interno Bruto (PIB) y los indicadores de movilidad, específicamente el retraso en minutos, para identificar cómo el desarrollo económico impacta (o se ve impactado por) la eficiencia en el transporte.

<img width="1408" height="768" alt="banner_proyecto" src="https://github.com/user-attachments/assets/db2ead30-0937-478e-b3bf-b99bfc1c65b1" />

### 📊 Descripción del Proyecto

El objetivo principal es realizar un Análisis Exploratorio de Datos (EDA) para visualizar la distribución del PIB frente a las métricas de retraso, buscando patrones o correlaciones significativas que ayuden a la toma de decisiones estratégicas.

### 🛠️ Herramientas Utilizadas
Lenguaje: Python 3.x

Librerías de Datos: Pandas, NumPy

Visualización: Matplotlib, Seaborn

Base de Datos: Python (Extracción y limpieza inicial)

Documentación: Markdown

### 📁 Estructura del Repositorio
data/: Contiene los datasets originales (o enlaces a las fuentes).

notebooks/: Jupyter Notebooks con el proceso de limpieza y análisis.

visuals/: Gráficos de barras, histogramas y boxplot generados.

### 📈 Hallazgos Principales 
<p align="center">
  <img width="846" height="317" alt="grafica" src="https://github.com/user-attachments/assets/e3635070-754f-40d0-ab37-bf9a93892098" />
</p>
No se encontró una relación directa entre el PIB per cápita y la congestión vehicular. 
<p align="center">
  <img width="520" height="476" alt="boxplot" src="https://github.com/user-attachments/assets/7c2ecf12-273c-4941-a152-781e1745d9f6" />
  <br>
  <b>Gráfico: Distribución de retrasos en movilidad (Minutos)</b>
</p>

Existen ciudades con alto PIB y alta congestión vehicular, así como ciudades con menor PIB pero distintos niveles de tráfico. 
<p align="center">
  <img width="1001" height="634" alt="Histograma" src="https://github.com/user-attachments/assets/dd7d192e-0ab6-4cc8-9c62-2114f09b8097" />
</p>
Destacan ciudades como Lima y Ciudad de México, donde hay altos niveles de congestión vehicular pero un PIB per cápita que no es de los más altos, lo que sugiere que la congestión no depende únicamente del nivel económico, sino de factores como infraestructura, planeación urbana y transporte público. 

Por otro lado, ciudades como Santiago muestran baja congestión vehicular y alto PIB, funcionando como un caso más eficiente.

### 🚀 Cómo Ejecutar el Proyecto
Abre el archivo ![Proyecto en Notebook](notebook/mobility_economy_project.ipynb) para ver el paso a paso.
