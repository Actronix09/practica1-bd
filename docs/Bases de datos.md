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