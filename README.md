# Buscador de Pokemon

Trabajo para la materia de Desarrollo de Servicios Web. Es una pagina web sencilla que busca pokemones consumiendo la PokeAPI usando JavaScript.

## Datos:
* Nombre: Jose Antonio Acevedo Garcia
* Materia: Desarrollo de Servicios Web


## Lo que hace esta pagina
1. Tiene un campo de texto donde puedes escribir el nombre (por ejemplo garchomp) o el numero de ID de cualquier pokemon.
2. Al presionar el boton, hace una peticion con `fetch` a la API de PokeAPI.
3. Si el pokemon existe, te muestra una tarjeta con:
   - Su nombre y numero de la Pokedex.
   - Su imagen.
   - Su peso oficial.
   - Sus tipos.
   - Sus estadisticas de salud (HP) y velocidad yo los puse como extra xd.
4. Si dejas la casilla vacia o escribes mal el nombre, manda una alerta o un mensaje de error en rojo.

## Archivos incluidos
* `index.html`: La interfaz con la caja de texto y el boton de busqueda.
* `style.css`: Los estilos basicos de la pagina.
* `app.js`: La funcion que se conecta a la API y dibuja los resultados en la pantalla.

## Como probarlo o usarlo
1. Descarga o clona todos los archivos en una sola carpeta en tu computadora. Asegurate de que `index.html`, `style.css` y `app.js` estén juntos en el mismo lugar.
2. Da doble clic en el archivo `index.html` para abrirlo directamente en tu navegador web (como Google Chrome, Edge o Firefox). No necesitas instalar servidores ni programas raros.
3. Escribe el nombre de un pokemon (por ejemplo: pikachu) o su numero de la Pokedex (por ejemplo: 25), dale al boton de buscar y listo, te aparecera la tarjeta con toda la info.
