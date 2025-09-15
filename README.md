# Challenge-Amigo-Secreto

Este proyecto es una aplicación web sencilla que permite agregar nombres de amigos y realizar un sorteo aleatorio para seleccionar el "Amigo Secreto".  
El sistema asegura que no se repitan nombres sorteados y muestra un mensaje cuando todos los nombres ya fueron elegidos.


## Funcionalidades

- Agregar nombres a la lista de amigos.
- Validar entradas (no se permiten nombres vacíos o repetidos).
- Visualizar la lista de amigos agregados.
- Sortear un amigo de manera aleatoria.
- Evitar que un nombre salga más de una vez en el sorteo.
- Mostrar un mensaje cuando todos los nombres fueron sorteados.


## Tecnologías utilizadas

- HTML5 → estructura del proyecto.  
- CSS3 → estilos personalizados.  
- JavaScript (Vanilla) → lógica del juego.  


## Estructura del proyecto

┣ assets/
┃ ┗ amigo-secreto.png
┣ index.html
┣ app.js
┣ style.css

##Ejecución

- Escribe el nombre de tus amigos en el campo de texto y presiona "Añadir".
- La lista se irá llenando automáticamente.
- Presiona "Sortear amigo" para seleccionar uno al azar.
- El nombre sorteado se eliminará de la lista y no podrá repetirse.
- Cuando ya no queden nombres, se mostrará el mensaje:
- "Todos los nombres fueron sorteados."

##Posibles problemas y soluciones

- No aparece el resultado del sorteo:
 - Verifica que hayas agregado al menos un nombre antes de presionar "Sortear".
- Los nombres no se muestran en la lista:
 - Revisa que no estés agregando cadenas vacías o duplicadas.
