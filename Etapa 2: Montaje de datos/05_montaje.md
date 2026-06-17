# Etapa 2: Montaje de Datos

El montaje es la base de la arquitectura de datos. Consiste en definir dónde y cómo residirán los datos, asegurando que sean escalables, duraderos y accesibles.

## Puntos clave:
* **Arquitectura de almacenamiento:**
    * **Data Lakes (Amazon S3):** Depósito centralizado para almacenar datos en su formato original (estructurados o no).
    * **Data Warehouses (Amazon Redshift):** Optimizado para analítica compleja sobre datos estructurados de gran volumen.
    * **Bases de datos especializadas:** Uso de Amazon RDS o DynamoDB según los requerimientos de la aplicación.
* **Gobierno y Catálogo:**
    * **AWS Glue Data Catalog:** Inventario de metadatos que permite buscar, descubrir y entender qué datos existen en el lago.
    * **Clasificación:** Etiquetado de datos para facilitar su gestión y posterior análisis.
* **Eficiencia:** Implementación de formatos columnares (como Parquet) para acelerar las consultas y reducir costos de almacenamiento.
