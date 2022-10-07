# Carbajal-Suarez-Osano-Barale

Repositorio dedicado al obligatorio de Ingeniería de Software Ágil 1.

  

# Product Backlog

  

- Registrar nuevo usuario

- Login de usuario

- Restaurar contraseña

- Editar usuario

- Buscar líneas de ómnibus utilizando filtros

- Filtro por origen y destino

- Filtro por parada

- Filtro por hora y fecha

- Filtro por línea

- Filtro por ómnibus de discapacitado

- Listado de las líneas más cercanas al usuario con información del destino/origen/tiempo estimado, con la información de cantidad de pasajeros en las mismas.

- Modo viaje. El usuario debe poder seguir el trayecto de la línea de ómnibus a la que se subió, pudiendo saber en qué parte del recorrido se encuentra, cuáles son las paradas hasta el próximo destino e información del destino.

- Notificaciones:

	- La línea seleccionada está por llegar a la parada de ómnibus.

	- La siguiente parada es tu destino.

	- Tu línea frecuente llega en X minutos (dependiendo de la distancia del usuario a la parada) a tu parada habitual.

	- La línea seleccionada tiene un retraso y demorará en llegar a tu parada origen.

	- La línea seleccionada tiene un desvío.
	-  Que te avise cuando va a existir un cambio de recorrido por una circunstancia externa.

- Compartir mi viaje con otro usuario (se comparte el viaje con otro usuario para que vea el recorrido del ómnibus en tiempo real)

- Historias de los últimos viajes (líneas de ómnibus utilizadas).



  

## Criterios de aceptación

**Registrar nuevo usuario**

**Dado** un nuevo usuario, **cuando** este se registra **entonces** se le manda un mail de confirmación de registro para que inicie sesión.

**Login de usuario**

 **Dado** un usuario registrado, **cuando** este ingresa sus datos  **entonces**  inicia sesión y es enviado a la página principal

**Restaurar contraseña**
**Dado** un usuario registrado, **cuando** ingresa su email  **entonces** se ke manda un mail de recuperación de contraseña 
  
**Editar usuario**
**Dado** un usuario registrado, **cuando** este cambia sus datos **entonces** se actualiza su información 
  
**Buscar líneas de ómnibus utilizando filtros**
**Dado** un usuario, **cuando** utiliza un filtro **entonces** se muestran los datos filtrados

-  **Filtro por origen y destino**

-  **Filtro por parada**

-  **Filtro por hora y fecha**

-  **Filtro por línea**

-  **Filtro por ómnibus de discapacitado**

**Listado de las líneas más cercanas al usuario con información del destino/origen/tiempo estimado, con la información de cantidad de pasajeros en las mismas.**
**Dado** un usuario,**cuando** este lista las líneas mas cercanas, **entonces** se muestran las lineas mas cercanas y la información de cantidad de pasajeros en las mismas  

**Modo viaje. El usuario debe poder seguir el trayecto de la línea de ómnibus a la que se subió, pudiendo saber en qué parte del recorrido se encuentra, cuáles son las paradas hasta el próximo destino e información del destino.**
**Dado** un usuario, **cuando** este activa el modo viaje **entonces** se le muestra el trayecto de la linea a la que se subió.

**Notificaciones:**
**Dado** un usuario **cuando** este tiene instalada la aplicación y tiene activadas las notificaciones **entonces** recibe notificaciones de la aplicación

-  **La línea seleccionada está por llegar a la parada de ómnibus.**

-  **La siguiente parada es tu destino.**

-  **Tu línea frecuente llega en X minutos (dependiendo de la distancia del usuario a la parada) a tu parada habitual.**

-  **La línea seleccionada tiene un retraso y demorará en llegar a tu parada origen.**

-  **La línea seleccionada tiene un desvío.**

 -  **Que te avise cuando va a existir un cambio de recorrido por una circunstancia externa.**

**Compartir mi viaje con otro usuario (se comparte el viaje con otro usuario para que vea el recorrido del ómnibus en tiempo real)**
**Dado** un usuario **cuando** comparte un viaje **entonces** se genera un enlace para poder compartir el viaje con otros usuarios 

**Historial de los últimos viajes (líneas de ómnibus utilizadas).**
**Dado** un usuario **cuando** este accede al historial de viajes **entonces** se le muestran sus ultimos viajes realizados 