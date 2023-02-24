# AWS RDS

- AWS RDS es un servicio de base de datos administrado para los motores de bases de datos relacionales MySQL, PostgreSQL, Oracle, SQL Server y MariaDB.

- RDS automatiza muchas de las funciones administrativas diarias que normalmente lleva a cabo un DBA. Esto incluye copias de seguridad, rotación de registros, aplicación de parches en el sistema operativo y la base de datos, y almacenamiento de escalado automático.

- Puede realizar copias de seguridad manuales llamadas instantáneas, que se pueden usar para crear copias de su base de datos en diferentes regiones o en una cuenta diferente si se comparten.

- RDS admite el cifrado en reposo y puede imponer el tráfico cifrado entre el cliente y la base de datos mediante SSL/TLS.

- El uso de una implementación multi-AZ reducirá en gran medida cualquier tiempo de inactividad durante un período de falla, actualización o mantenimiento de la base de datos que requiera que se reinicie la instancia. Esto se debe a que RDS cambiará automáticamente al modo de espera para mantener el servicio de la base de datos.

- Las réplicas de lectura se pueden usar para escalar horizontalmente la base de datos para descargar algunas consultas de solo lectura fuera de la instancia principal.
