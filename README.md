# Proyecto de Análisis de Usuarios de Telecomunicaciones

## Objetivo del proyecto
Analizar datos de usuarios de un servicio de telecomunicaciones para identificar patrones de comportamiento, segmentar clientes por edad y nivel de uso, y generar insights que apoyen decisiones de negocio, marketing y retención.

## Datasets utilizados
- **user_profile**: información de usuarios (edad, ciudad, plan contratado).
- **usage**: registros de uso (mensajes, llamadas, minutos de llamada).
- Variables clave: `age`, `city`, `plan`, `type`, `cant_mensajes`, `cant_llamadas`, `cant_minutos_llamada`.

## Etapas del análisis
1. **Limpieza de datos**: corrección de valores inválidos, tratamiento de nulos y outliers.
2. **Exploración estadística**: cálculo de medidas descriptivas y detección de valores atípicos con IQR.
3. **Segmentación**: creación de columnas `grupo_edad` y `grupo_uso` para clasificar usuarios.
4. **Visualización**: gráficos de distribución por edad y nivel de uso.
5. **Insights ejecutivos**: interpretación de patrones y recomendaciones de negocio.

## Cómo ejecutar el notebook
1. Abrir el archivo `.ipynb` en **Google Colab** o Jupyter Notebook.
2. Subir los datasets al entorno de ejecución.
3. Ejecutar las celdas en orden para reproducir el análisis.

##  Guía de reproducción
- Descargar el repositorio.
- Asegurarse de tener instaladas las librerías: `pandas`, `numpy`, `matplotlib`, `seaborn`.
- Abrir el notebook en Colab/Jupyter.
- Ejecutar paso a paso para obtener los mismos resultados y visualizaciones.


