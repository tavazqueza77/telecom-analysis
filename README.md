Análisis de Comportamiento de Clientes - ConnectaTel 2024
Este proyecto tiene como objetivo evaluar el comportamiento de los clientes de ConnectaTel, una empresa de telecomunicaciones en Latinoamérica, utilizando técnicas avanzadas de análisis de datos con Python para identificar patrones de consumo y oportunidades de negocio.

🎯 Objetivo del Proyecto
El propósito central es transformar datos crudos en insights accionables para:

Construir un perfil estadístico detallado de los clientes.

Detectar comportamientos atípicos (outliers) y validar la calidad de la información.

Segmentar a los usuarios según su nivel de uso y demografía.

Sugerir mejoras estratégicas en la oferta de planes (Smart vs. Ultra).

📊 Datasets Utilizados
El análisis se basa en tres fuentes de datos principales:

plans.csv: Información técnica de las tarifas (precios, minutos/GB incluidos y costos por excedentes).

users.csv: Datos demográficos (edad, ciudad, fecha de registro y estatus de cancelación).

usage.csv: Registro transaccional del uso real de servicios (llamadas y mensajes).

🚀 Etapas del Análisis
Siguiendo un flujo de trabajo profesional, el proyecto se divide en:

Inicialización y Carga: Importación de librerías (Pandas, Matplotlib, Seaborn) y lectura de archivos.

Preparación y Limpieza: Tratamiento de valores ausentes (como churn_date), conversión de tipos de datos y manejo de valores "centinela".

Análisis de Calidad: Evaluación de la cardinalidad de las variables y consistencia de los IDs.

Cálculos Agregados: Creación de métricas mensuales de consumo e ingresos por usuario.

EDA (Análisis Exploratorio): Visualización de distribuciones y comparativa entre planes.

Tratamiento de Outliers: Aplicación del método IQR para identificar y gestionar consumos extremos.

Insights Ejecutivos: Redacción de conclusiones estratégicas para stakeholders.

🔄 Guía de Reproducción
Para asegurar que los resultados sean consistentes:

Entorno: Asegúrate de tener instalada la versión de Python 3.x.

Librerías: Instala las dependencias necesarias ejecutando:

Bash
pip install pandas matplotlib seaborn
Orden: Ejecuta las celdas del notebook en orden secuencial para evitar errores de referencia de variables.

Datos: Si utilizas tus propios datos, asegúrate de que los nombres de las columnas coincidan con los esquemas definidos en la sección de Datasets.

Analista: Tania Alejandra Vazquez Aguilar

Bootcamp: TripleTen - Data Analyst Training (2026)
