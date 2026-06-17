# Etapa 5: Archivado de Datos

El archivado de datos permite mover información menos utilizada hacia niveles de almacenamiento de bajo costo, sin sacrificar la durabilidad ni la disponibilidad legal de la misma.

## Puntos clave:
* **Estrategia de Ciclo de Vida:** Implementación de políticas automáticas (S3 Lifecycle Policies) para transicionar objetos entre niveles de almacenamiento basados en su antigüedad o frecuencia de acceso.
* **Niveles de Almacenamiento (Storage Tiers):**
    * **Standard:** Acceso frecuente.
    * **Standard-IA:** Acceso poco frecuente.
    * **Glacier (Instant Retrieval, Flexible, Deep Archive):** Niveles de costo optimizado para almacenamiento de largo plazo (frío).
* **Cumplimiento y Gobernanza:** Garantizar que los datos archivados cumplan con las normativas de retención legal y auditoría antes de cualquier proceso de destrucción segura.
* **Optimización de Costos:** Reducción drástica del TCO (Total Cost of Ownership) al mover datos "fríos" fuera de los sistemas de análisis de alto rendimiento.
