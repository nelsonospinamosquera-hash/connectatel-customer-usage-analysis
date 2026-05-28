# ConnectaTel - Análisis de Clientes y Uso de Servicios
## Objetivo del proyecto
Este proyecto tiene como objetivo analizar el comportamiento de los clientes de ConnectaTel (empresa de telecomunicaciones) para entender cómo utilizan los servicios de llamadas y mensajes, identificar patrones de consumo, detectar valores atípicos y generar segmentos de clientes útiles para la toma de decisiones comerciales.
El propósito final es apoyar la optimización de planes y mejorar la experiencia del usuario mediante decisiones basadas en datos.
## Datasets utilizados
Se trabajó con tres fuentes principales de información:
- plans.csv: información de los planes disponibles (minutos incluidos, mensajes, costos adicionales).
- users_latam.csv: información de los clientes (edad, ciudad, plan contratado, fechas de registro y churn).
- usage.csv: registros de uso del servicio (llamadas y mensajes).
## Etapas del análisis
### 1. Carga y exploración de datos
- Revisión de estructura, tipos de datos y dimensiones.
- Identificación de variables numéricas y categóricas.
### 2. Calidad de datos
- Detección de valores nulos.
- Identificación de sentinels (ej: -999, "?").
- Detección de fechas fuera de rango.
### 3. Limpieza de datos
- Reemplazo de valores inválidos.
- Corrección de tipos de datos (fechas).
- Imputación de valores faltantes cuando corresponde.
### 4. Análisis descriptivo
- Estadísticas generales de uso por usuario.
- Medidas de tendencia central y dispersión.
### 5. Segmentación de clientes
- Segmentación por nivel de uso:
  - Bajo uso
  - Uso medio
  - Alto uso
- Segmentación por edad:
  - Joven
  - Adulto
  - Adulto Mayor
### 6. Análisis de outliers
- Uso del método IQR.
- Identificación de usuarios de alto consumo.
### 7. Visualización de datos
- Histogramas por variable.
- Boxplots para detección de outliers.
- Comparación por segmentos.
### 8. Insights y recomendaciones
- Interpretación de resultados.
- Propuestas de mejora para planes y estrategia comercial.
### 9. Cómo ejecutar el notebook
Para ejecutar este proyecto en Jupyter Notebook, sigue los siguientes pasos:
1. Instala las dependencias necesarias:
```bash
pip install pandas numpy matplotlib seaborn
### Opción 2: Jupyter Notebook local
Instalar dependencias:

```bash
pip install pandas numpy matplotlib seaborn
