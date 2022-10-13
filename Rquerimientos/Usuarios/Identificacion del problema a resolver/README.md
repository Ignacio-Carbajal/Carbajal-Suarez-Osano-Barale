# Identificación del problema a resolver

## Identificación de interesados

Vamos a tener interesados con diferentes propósitos.. Los interesados en el proyecto son personas y organizaciones que están activamente involucrados en el proyecto , o cuyos intereses pueden verse afectados de manera positiva o negativa por la ejecución o terminación del proyecto.
A continuación pasamos a detallar los distintos interesados que fuimos identificando a lo largo de la iteración:

**Compañías de transporte:** Son empresas de transporte que operan en Montevideo, las cuales contienen la mayoría de las líneas de recorrido en Montevideo. Son interesados porque el uso de la aplicación es una mejora al servicio de dichas empresas, además ellos nos aportan los horarios de los recorridos de las líneas de transporte, sabiendo así los horarios del mismo. Algunos ejemplos son: CUTCSA, COME, COETC, UCOT.

Dentro de las líneas de colectivos podemos identificar varios roles de subinteresados, éstos pueden ser tanto los choferes, los guardas o los inspectores, ya que el uso de la aplicación facilita sus trabajos.

**Pasajeros:** Es el principal interesado, ya que va a ser quien va a usar la mayoría de las funcionalidades ofrecidas por la aplicación. 

**Google:** Es la compañía que nos va a brindar los mapas necesarios para el funcionamiento de la aplicación.

**Plataformas de descargas de aplicaciones:** Es donde los usuarios podrán conseguir la aplicación. Como por ejemplo: Play Store, AppStore, etc.

**Intendencia de Montevideo:** Presta el servicio de la tarjeta STM.


## Lista de funcionalidades por interesado

**Compañías de transporte:** Estadísticas sobre concurrencia en los ómnibus en distintos horarios y zonas.

Dentro de la compañía de transporte como ya identificamos, tenemos gente que trabaja para la misma, entonces va a utilizar la aplicación para facilitar sus tareas dentro de la empresa.
 - Choferes: Pueden usar la aplicación para ser notificados sobre cambios de rutas, o como guía para inexpertos.
 - Inspectores: Pueden usar la aplicación para agilizar sus tareas diarias dentro y fuera de los ómnibus, como controlar a los pasajeros y los horarios de los ómnibus.

**Pasajeros**: 

 - Buscar líneas de ómnibus utilizando filtros.
 - Listado de las líneas mas cercanas al usuario con información del origen, destino y tiempo estimado.
 - Cantidad de pasajeros en una unidad.
 - Modo viaje: El usuario puede seguir el trayecto de la línea a la que se subió, sabiendo en tiempo real donde se encuentra y cuales son las siguientes paradas hasta su destino.
 - Notificaciones: 
	 - El ómnibus está por llegar a la parada de origen
	 - El ómnibus está por llegar a la parada de destino
	 - Tu línea frecuente llega en x minutos
	 - El ómnibus tiene un retraso y tardará en llegar a la parada
	 - La línea seleccionada tiene un desvío

 - Compartir mi viaje con otro usuario.
 - Historial de los últimos viajes.
 - Modo no vidente.
 - Modo daltónico.
 
 **Google:**
 En éste caso nosotros no le vamos a brindar un servicio a Google, si no, ellos a nosotros. Como sería la de los mapas que utilizaremos en la aplicación.
 También vamos a contar con el inicio de sesión con la cuenta de Google, utilizando OAuth.
 
**Plataformas de descargas de aplicaciones:** Son los intermediarios entre la aplicación y el usuario, ya que nos ofrecen un lugar donde los clientes pueden descargar la aplicación.

**Intendencia de Montevideo:** Nos brinda la posibilidad de tener una boletera virtual, en lugar de utilizar la tarjeta STM.

# Estudio de Competidores

A continuación vamos a detallar el estudio de las competencias, comentando los puntos a favor y en contra que encontramos.

## Moovit

### Cosas a Favor

* Poder guardar los lugares favoritos a los que concurre

* Notificación de actualizaciones tanto en la aplicación, como así también en los recorridos

* Siguiendo con el primer punto, también se puede guardar las paradas y las líneas favoritas

### Cosas en Contra

* Existe una versión paga, en la cual las publicidades no existen

* No tiene un horario en tiempo real que podemos verificar por donde se encuentra la línea

*

## Cómo ir

### Cosas a Favor

* Podemos verificar por donde se encuentra nuestra linea, ya que existe la opcion de ver el recorrido en tiempo real independientemente de la empresa en la cual se quiere viajar

* Muestra las líneas que cuentan con lugares para discapacitados

* No contiene una versión paga

### Cosas En Contra

* Mala optimización lo que genera tener que reiniciarla

* No contiene un historial de viajes. Lo que implica tener que volver a ingresar los datos de viajes frecuentes

* Funcionalidades no útiles

## STM Montevideo

### Cosas a Favor

* Contiene un diseño simple pero funcional

* No contiene una versión paga

### Cosas en Contra

* Parece una versión en la cual no pasó por múltiples etapas de testing. Por lo tanto tiene varios errores de diseño.

## Cutcsa

### Cosas a Favor

* Diseño simple en la sección principal

* Información en tiempo real sobre las líneas que viene en camino

### Cosas en Contra

* Funcionalidades extras que no están a la vista y no se especifica su uso

* Algunas funciones están ocultas y mal implementadas

* Solamente podes ver la ubicación en tiempo real de los ómnibus de la empresa Cutcsa.