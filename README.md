# Proyecto-Telecom-X-MG

📊 Análisis de Evasión de Clientes (Churn) - Telecom X
Este proyecto realiza un Análisis Exploratorio de Datos (EDA) y un estudio estadístico sobre la pérdida de clientes en la empresa Telecom X. El objetivo es transformar datos crudos en insights accionables para reducir la tasa de abandono y mejorar la retención estratégica.

🚀 Resumen del Proyecto
El análisis identifica una tasa de evasión crítica del 26.54% sobre una base de 7,043 clientes. A través de la estandarización de variables y la creación de métricas como Cuentas_Diarias, se detectaron los patrones financieros y temporales que impulsan la salida de los usuarios.

🛠️ Tecnologías Utilizadas
Lenguaje: Python 3.12

Librerías: Pandas, Matplotlib, Seaborn

Entorno: Google Colab

📈 Hallazgos Clave (Insights)
Distribución de Meses_Permanencia: Existe una "barrera del primer año"; la mediana de fuga es de 10 meses, mientras que los clientes leales superan los 38 meses.

Distribución de Cargos_Mensuales: El precio es un detonante; los clientes evadidos pagaban una mediana de $80, frente a los $65 de los activos.

Evasión por Tipo_Contrato: El contrato "Mensual" concentra la gran mayoría de las bajas (1,655 casos).

Evasión por Metodo_Pago: El pago manual por "Electronic check" es el de mayor riesgo (1,071 bajas).

Análisis de Correlación: Se confirmó estadísticamente que la antigüedad es el principal factor de retención (corr: -0.35), mientras que el costo diario elevado tiene una relación directa con el abandono.

💡 Recomendaciones Estratégicas
Fidelización Temprana: Implementar programas de beneficios específicos entre el mes 3 y el mes 9 de antigüedad.

Migración Contractual: Incentivar el paso de contratos mensuales a anuales mediante ofertas comerciales.

Automatización de Pagos: Promover el uso de débito automático para reducir la fricción en el proceso de pago manual.

Revisión de Planes Premium: Evaluar la satisfacción en cuentas con cargos superiores a $90/mes.

📂 Cómo utilizar este repositorio
Clona el repositorio: git clone https://github.com/Jonnars/Proyecto-Telecom-X-MG.git

Abre el archivo .ipynb en Google Colab o Jupyter Notebook.

Asegúrate de tener instaladas las dependencias: pip install pandas matplotlib seaborn

Autor: Jonatan M. Andrade
