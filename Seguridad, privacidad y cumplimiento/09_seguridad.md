# Seguridad, Privacidad y Cumplimiento

La seguridad en AWS no es una capa adicional, es un requisito transversal. Cada fase del ciclo de vida de los datos debe estar protegida para garantizar la confidencialidad, integridad y disponibilidad.

## Pilares de Seguridad:
* **Control de Acceso (IAM):** Implementación del principio de "mínimo privilegio" mediante roles y políticas, reforzado con autenticación multifactor (MFA).
* **Protección de Datos (Cifrado):**
    * **En tránsito:** Protocolos TLS/SSL para proteger los datos mientras se mueven.
    * **En reposo:** Cifrado de nivel de servicio (S3, Redshift) utilizando AWS KMS (Key Management Service).
* **Auditoría y Monitoreo:** Uso de **AWS CloudTrail** para el registro detallado de actividades y **Amazon GuardDuty** para la detección proactiva de amenazas.
* **Cumplimiento Normativo:** Adaptación de la arquitectura para cumplir con estándares internacionales (GDPR, HIPAA, PCI-DSS) mediante el uso de herramientas como AWS Artifact.
