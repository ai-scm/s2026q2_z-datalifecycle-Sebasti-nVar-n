# Etapa 3: Limpieza de Datos

La limpieza de datos (Data Cleansing) es el proceso crítico que asegura la veracidad y consistencia de la información. Un análisis realizado sobre datos "sucios" llevará inevitablemente a conclusiones erróneas.

## Puntos clave:
* **Calidad de datos:**
    * **Normalización:** Ajustar formatos de fechas, divisas y unidades de medida a un estándar global.
    * **Deduplicación:** Eliminar registros redundantes que inflan métricas y sesgan resultados.
    * **Integridad:** Validación de reglas de negocio para asegurar que los datos sean coherentes y lógicos.
* **Manejo de datos incompletos:** Estrategias de imputación (relleno de valores faltantes) o filtrado de registros que no cumplen los umbrales mínimos de calidad.
* **Transformación (ETL/ELT):** Conversión de estructuras de datos para adaptarlas a los requerimientos de las herramientas de análisis.
* **Herramientas AWS:**
    * **AWS Glue DataBrew:** Interfaz visual para limpiar y transformar datos sin necesidad de código (no-code).
    * **AWS Glue ETL:** Ejecución de jobs escalables para transformaciones complejas.
