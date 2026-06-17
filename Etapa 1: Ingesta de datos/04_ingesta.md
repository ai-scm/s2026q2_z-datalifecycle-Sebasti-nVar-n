# Etapa 1: Ingesta de Datos

La ingesta es el proceso de mover datos desde sus sistemas de origen hacia un entorno de almacenamiento en la nube. La eficiencia en esta etapa determina la calidad y oportunidad de los análisis posteriores.

## Puntos clave:
* **Fuentes de datos:** Captura desde aplicaciones corporativas, sensores IoT, logs de servidores y bases de datos relacionales (RDBMS).
* **Modos de Ingesta:**
    * **Batch (Lotes):** Ideal para procesar volúmenes masivos de datos en intervalos de tiempo programados.
    * **Streaming (Tiempo real):** Crucial para analítica inmediata, permitiendo actuar sobre los datos tan pronto como se generan.
* **Servicios AWS clave:** * **Amazon Kinesis:** Para captura y análisis de datos en tiempo real.
    * **AWS DMS (Data Migration Service):** Migración de bases de datos con tiempo de inactividad mínimo.
    * **AWS Transfer Family:** Transferencia segura de archivos vía protocolos estándar.
