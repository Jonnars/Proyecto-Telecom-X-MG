# Proyecto-Telecom-X-MG

📊 Análisis de Evasión de Clientes (Churn) - Telecom X

Este proyecto realiza un Análisis Exploratorio de Datos (EDA) y un estudio estadístico sobre la pérdida de clientes en la empresa Telecom X. El objetivo es transformar datos crudos en insights accionables para reducir la tasa de abandono y mejorar la retención estratégica. 

🚀 Resumen del Proyecto
El análisis identifica una tasa de evasión crítica del 26.54% sobre una base de 7,043 clientes. A través de la estandarización de variables y la creación de métricas como Cuentas_Diarias, se detectaron los patrones financieros y temporales que impulsan la salida de los usuarios.

🎯 Propósito del Análisis
El objetivo de este proyecto es identificar los factores críticos que impulsan la evasión de clientes (Churn) en Telecom X. Mediante el procesamiento de datos y análisis estadístico, buscamos transformar información técnica en estrategias de negocio que reduzcan la pérdida de ingresos y mejoren la retención de usuarios.

📂 Estructura del Proyecto
El repositorio está organizado de la siguiente manera para facilitar su navegación y ejecución:

notebook.ipynb: Cuaderno de Python con el ciclo completo de datos (Limpieza, EDA y Correlación).

data/: Carpeta destinada al almacenamiento del dataset de clientes procesado.

images/: Visualizaciones clave exportadas durante el análisis.

📈 Gráficos e Insights Obtenidos
A partir del análisis de 7,043 registros, se detectaron los siguientes patrones de comportamiento:

Tasa de Evasión Crítica: Se confirmó que el 26.54% de la base de clientes ha abandonado la empresa.

Distribución de Meses_Permanencia: Existe una crisis de retención temprana; la mediana de fuga es de 10 meses, mientras que los clientes leales superan los 38 meses.

Impacto de Cargos_Mensuales: El costo es un detonante directo; los clientes que se van pagan una mediana de $80, frente a los $65 de los activos.

Análisis de Correlación: Se validó estadísticamente que la antigüedad (-0.35) es el factor de protección más fuerte contra la fuga.


🛠️ Instrucciones para Ejecutar el Notebook
Para replicar este análisis en tu entorno:

Clonar el repositorio:
git clone https://github.com/Jonnars/Proyecto-Telecom-X-MG.git

Preparar el entorno:
Asegúrate de tener instaladas las librerías necesarias ejecutando: pip install pandas matplotlib seaborn.

Ejecución:
Carga el archivo .ipynb en Google Colab o Jupyter Notebook y ejecuta las celdas secuencialmente para visualizar los resultados.


🛠️ Tecnologías Utilizadas
Lenguaje: Python 3.12

Librerías: Pandas, Matplotlib, Seaborn

Entorno: Google Colab


Autor: Jonatan M. Andrade
