# Bases de datos

## Tabla de Contenidos

---

## Dato, Informacion y Bases de datos

### ¿Que es un dato?

Elmasri & Navathe. (2016), p.4. Definen un dato es un hecho que es reconocido y que pueden ser registrados con un significado implicito. Un ejemplo de dato podrian ser: un nombre, numeros de telefono, ubicaciones, direcciones de correo electronico, entre muchos mas.

Gene, Durval & Anthony. (2003), p.1. Define que los datos no tienen un significado aparente mas alla de su propia existencia, y estos pueden ser o no utilizables para con distintos fines.

Por ambas partes los autores nos dan a entender que los datos son trozos de informacion que se pueden utilizar con distintos fines, Gene nos dice que mas alla de su existencia no tienen otro significado.


### Informacion

Elmasri & Navathe. (2016), p.5. Una base de datos se constituye por medio de una serie de datos relacionados entre si de manera logica y coherente, una  base de datos genera informacion con los datos que este almacena, de esta forma no es posible contruir una base de datos con una variedad aleatoria de datos sin una conexion entre si.

Gene, Durval & Anthony. (2003), p.1. La información son datos a los que se les ha dado significado a través de una conexión relacional.

Ambos autores nos dicen que los datos tienden a tener una conexion racional y logica para generar informacion y que este mismo principio es fundamental que constituye a las bases de datos.
Un ejemplo de esto podria ser una calle: "calle 1" por si sola no tiene sentido, pero si se le relaciona con una persona se puede decir que esa persona vive en la "calle 1"

### Base de datos

Date. (2000), p.2. Una base de datos es un sistema computarizado que se utiliza para llevar el registro electronico de informacion (concepto que se habia planteado anteriormente). Los usarios y administradores pueden realizar acciones enfocadas en la informacion que almacenan, por ejemplo estos pueden agregar mas informacion, modificar la informacion existente, recuperarla, eliminar informacion o datos.

Silberschatz, Korth & Sudarshan. (2002), p.4. Los autores nos definen diferencias entre un sistema de procesamiento de datos y una base de datos donde se nos dice que un sistema gestos de bases de datos coordina sistemas fisicos y accesos logicos, este mismo garantiza el correcto uso de la informacion en aplicaciones por medio de consultas.

El autor Date nos da una version mas figurada y sencilla de lo que es una base de datos, mientras que Abraham, Henry y Sudarsha ofrecen una vision mas tecnica y detallada sobre las diferencias principales que tiene una base de datos frente a un sistema de procesamiento de datos 

## Caracteristicas de una base de datos

### 1. Integracion

Elmasri & Navathe. (2016), p.10. Los autores nos dicen que una base de datos funciona como un unico repositorio donde se unifica las estructuras de los datos y la informacion, de esta forma reemplaza a los archivos independientes e inconexos.

Silberschatz, Korth & Sudarshan (2002), p.3. La integracion es la consolidacion y la centralizacion de la informacion dispersa o descentralizada en multiples archivos, de forma que la integracion permite el acceso unificado de la informacion.

Ambos autores nos dicen la misma idea, donde los archivos independientes o descentralizados se conectan de forma conexa en la base de datos.

### 2. Persistencia

Elmasri & Navathe (2016), p.20. Los datos almacenados tienen la propiedad de persistir de forma duradera en los medios de almacenamiento no volatiles, sobreviviendo a la finalizacion o ejecucion de los programas que los crearon.

Date. (2002), p.9 & 10. De forma precisa decimos que los datos de la base de datos "persisten" debido a que una vez son aceptados por el SGBD solo pueden ser removidos por una peticion al SGBD, pero no como un efecto lateral (por ejemplo) algun programa termine su ejecucion

En ambas citas los autores nos plantean ideas simirales, que dentro de un SGBD los datos y la informacion persisten y esta persistencia siempre estara presente sin importar las ejecuciones que haga la aplicacion donde se aloja el SGBD, y esta persistencia solo cambiara por medio de peticiones directas al SGBD.

### 3. Redundancia controlada

Elmasri & Navathe. (2016). p.17 & 18. Aunque la norma es eliminar la duplicacion mediante la normalizacion, cuando es necesario duplicar datos de forma intencional para acelerar las consultas el SGBD aplica una redundancia ontrolada para asegurar que el cambio se haga correctamente por igual entre sus copias

Silberschatz, Korth & Sudarshan. (Año: 2002), p.4. Consiste en evitar la duplicación innecesaria de información propia de los sistemas de archivos tradicionales para prevenir inconsistencias; si existe redundancia por diseño, el SGBD mantiene la sincronización

Los autores Elmasri y Navathe profundizan mas en el aspecto de como funciona dicha duplicidad y en la otra cita se profundicza como se mantiene una sincronizacion dentro del SGBD

### 4. independencia de datos

Elmasri & Navathe, (2016), pp. 19–20: Garantiza que los datos cumplan con las restricciones de integridad como la clave primaria definidas en el catálogo del sistema, las cuales el SGBD valida automáticamente en cada actualización

(Silberschatz et al., 2002, p. 5): La integridad asegura la corrección y consistencia de los datos mediante el cumplimiento estricto de reglas de validación como claves primarias especificadas por el administrador.

En este caso loa autores dan la misma idea, donde cierta informacion especifica (describen la clave primaria como ejemplo) tienen que cumplir con la caracteristica de integridad

### 5. Independencia de datos

Elmasri & Navathe, (2016), p12, 36–38. Es la separación entre los programas de aplicación y los datos gracias a la abstracción. Incluye la independencia física (modificar el almacenamiento sin alterar el esquema conceptual) y la independencia lógica (alterar el esquema conceptual sin modificar las aplicaciones externas)

**Silberschatz, Korth &amp; Sudarshan [Año: 2002, p. 11]** *(Silberschatz et al., 2002, p. 11)*: Capacidad de alterar el esquema físico o lógico sin requerir la reescritura ni modificación de los programas de aplicación que acceden a la base de datos

En la primer cita profundiza mas sobre cuales son las partes del sistema no interfieren con los datos, ya sea de forma fisica y/o logica, en la segunda cita es mas clara y directa.

### 6. Seguridad

*Elmasri &amp; Navathe, 2016, p. 21)*: Protección del sistema contra accesos no autorizados o malintencionados mediante controles de acceso discrecionales (`GRANT`/`REVOKE`), obligatorios (por niveles), cifrado de datos y defensa contra amenazas como la inyección SQL

*(Silberschatz et al., 2002, p. 5)*: Mecanismos del SGBD que restringen el acceso a la información únicamente a los usuarios autorizados, otorgando privilegios específicos de lectura, modificación o ejecución

Ambos autores nos hablan de como el SGBD tiene diferentes mecanismos de seguridad para con el usuario, en la primera profundiza mas en los controles de acceso.

### 7. Concurrencia

**Elmasri &amp; Navathe [Año: 2016, pp. 13–14, 21]** *(Elmasri &amp; Navathe, 2016, pp. 13–14, 21)*: Permite que múltiples usuarios y transacciones modifiquen la base de datos simultáneamente. El subsistema de control de concurrencia aplica bloqueos o marcas de tiempo para garantizar la atomicidad y el aislamiento de las operaciones

**Silberschatz, Korth &amp; Sudarshan [Año: 2002, p. 5]** *(Silberschatz et al., 2002, p. 5)*: Supervisión del acceso simultáneo a los datos que evita anomalías o inconsistencias (como lecturas sucias o actualizaciones perdidas), logrando que las ejecuciones concurrentes equivalgan a ejecuciones seriales

En la segunda cita se describe las consecuencias concretas que pueden pasar en caso de una falta de supervision del sistema. En la primer cita se describe mejor la caracteristica

### 8. Recuperacion

**Elmasri &amp; Navathe [Año: 2016, p. 21]** *(Elmasri &amp; Navathe, 2016, p. 21)*: Capacidad del SGBD para restaurar la base de datos a un estado consistente tras un fallo de hardware, software o sistema, utilizando registros en bitácora (*log*), operaciones `UNDO`/`REDO` e hitos de control

**Silberschatz, Korth &amp; Sudarshan [Año: 2002, p. 5]** *(Silberschatz et al., 2002, p. 5)*: Conjunto de algoritmos que garantizan las propiedades de atomicidad y durabilidad, deshaciendo los cambios de transacciones no terminadas y asegurando la persistencia de las transacciones confirmadas ante fallos

Ambas citas describen muy bien la caracteristica, pero en la primera se describen las operaciones concretas para ponerlas en practica

