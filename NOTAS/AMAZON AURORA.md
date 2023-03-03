# AMAZON AURORA

- Amazon Aurora es un servicio de base de datos administrado creado por AWS que ofrece una base de datos compatible con MySQL o PostgreSQL.

- Un clúster de Aurora presenta instancias de lectura y escritura con sus propios puntos finales, lo que le permite dividir la carga de trabajo de su aplicación entre lecturas y escrituras.

- No define la capacidad de almacenamiento de Aurora, ya que se puede escalar de forma instantánea y automática. Tampoco necesita definir ninguna operación de entrada/salida por segundo (IOPS) o rendimiento, ya que siempre obtiene el máximo disponible con cualquier instancia de Aurora o tamaño de almacenamiento.

- Puede tener hasta 15 instancias de lectura en cualquier clúster, pero solo una instancia de escritura.

- Aurora automatiza muchas de las funciones administrativas diarias que normalmente lleva a cabo un DBA. Estos incluyen copias de seguridad, rotación de registros y parches del sistema operativo y la base de datos, y pueden incluir el escalado automático del almacenamiento, el tamaño de la instancia de escritura y la cantidad y el tamaño de los nodos lectores.

- Aurora es automáticamente una implementación Multi-AZ con seis copias de sus datos que se almacenan en tres AZ.

- Aurora Serverless le permite aprovisionar un clúster de Aurora sin especificar el tamaño de instancia que necesita. En su lugar, asigna unidades de capacidad máxima y mínima de Aurora y la instancia sin servidor se escalará automáticamente para manejar cualquier carga.

- Global Database le permite ofrecer rápida y fácilmente una implementación en varias regiones para reducir la latencia entre una aplicación global y la base de datos.

- Aurora Backtrack le permite volver a poner la base de datos como estaba en cualquier momento en la ventana Backtrack sin recuperarse de una copia de seguridad.
