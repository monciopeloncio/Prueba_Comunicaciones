# PROTOCOLO DE EMEGENCIA REBELDE 2.1.3
Prueba de nivel con el problema del centro de comunicaciones rebelde

En caso de que el centro de comunicaciones sea destruido y para volver a tener una comunicación activa entre toda la flota de la alianza rebelde, se deberá desarrollar una aplicación donde el comandante de cada nave pueda registrar en un sistema el nombre de su nave, el tipo de nave y las coordenadas espaciales de su posición. 

Unos viejos servidores de la alianza escondidos en el planeta Dagobah pueden servirte para crear esta aplicación y pueda ser accedida por las distintas naves de la alianza. Para ello deberás realizar las siguientes tareas:

1. Hay una base de datos Mysql disponible en el conjunto de servidores. Las credenciales se proporcionarán de forma externa. Comprobar su estado, ya que el servidor lleva abandonado mucho tiempo, y realizar una conexión para poder trabajar en la construcción de un modelo de datos. La conexión se podrá realizar a través de cualquier cliente Mysql (consola y programa externo).

2. Diseñar e implementar un modelo de datos para almacenar los datos necesarios para la aplicación. Se proporciona dentro de la documentación un listado de los distintos modelos de naves espaciales para que sea más fácil realizar su clasificación.

3. Implementar un API que realice las siguientes operaciones sobre la base de datos:

 - Insertar nueva información (nombre nave, tipo nave, coordenadas actuales)
 - Dado el nombre de una nave, recuperar sus coordenadas actuales.
 - Listar toda la información de la flota rebelde.

4. Desarrollar un front que permita interactuar con las funciones de la API previamente implementadas. El diseño debe ser simple para no perder demasiado tiempo.

Una vez finalizado el desarrolo, se deberá subir la aplicación a un repositorio para que pueda ser accededido por el equipo de QA.

Importante:
 - Todo el desarrollo se realizará en local, excepto la base de datos que estará alojada fuera
 - Todo el código desarrollado tiene que estar correctamente documentado.
 - Existe libertad para elegir las tecnologías, paquetes o patrones usados.
 - Se valorará realizar alguna tarea extra a parte de las anteriormente mencionadas para mejorar la aplicación en algún aspecto.
