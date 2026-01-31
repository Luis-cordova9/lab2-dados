## Descripción del proyecto

La aplicación implementa una interfaz basada en componentes de Material 3 utilizando Jetpack Compose.  
Cada estadística (VIT, DEX, WIS) se muestra en una fila que contiene:

- El nombre de la estadística
- El valor actual
- Un botón para volver a lanzar el valor

Los valores se generan de forma aleatoria dentro de un rango típico de juegos de rol.  
Al final de la pantalla se calcula automáticamente el total de las tres estadísticas y se muestra un mensaje según el resultado:

- Si el total es bajo, se recomienda volver a lanzar
- Si el total es alto, se muestra un mensaje de resultado sobresaliente

El manejo de estado se realiza con remember y rememberSaveable, lo que permite que los valores se mantengan al rotar la pantalla.  

---

## Video

https://youtu.be/TQyIpoVEffU