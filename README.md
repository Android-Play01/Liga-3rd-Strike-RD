# Liga 3rd Strike — Ranking

Esta es una aplicación web para llevar un registro del ranking y el historial de partidas de la comunidad de Street Fighter III: 3rd Strike en República Dominicana. La página carga los datos desde un archivo JSON alojado en GitHub y se actualiza de forma automática.

### Características

- **Ranking de Jugadores**: Muestra una lista de jugadores ordenada por puntos y estadísticas.
- **Herramienta Versus**: Compara a dos jugadores cara a cara, analizando su historial de sets, rondas y enfrentamientos por personaje.
- **Historial de Partidas**: Guarda y muestra el historial completo de todas las partidas.
- **Perfiles de Jugador**: Puedes ver las estadísticas detalladas de cada jugador.
- **Actualización en Vivo**: Los cambios en la base de datos se reflejan en la página web al instante.

### Cómo Usar

Para usar la aplicación, simplemente abre el archivo `index.html` en tu navegador web. Si deseas registrar nuevos jugadores o partidas, puedes exportar tu archivo JSON desde la sección de Ajustes. (Ten en cuenta que el archivo JSON no es editable directamente desde la página web).

Para crear tu propia base de datos, descarga el archivo `index.html`. Una vez que hayas agregado a todos los jugadores, ve a Ajustes y luego a Exportar JSON. De esta forma, obtendrás tu propio ranking, el cual será independiente y actualizable a tu gusto.

### Archivos Clave

- `index.html`: El archivo principal de la aplicación.
- `liga-3rd-strike-visitante`: La base de datos de la liga con todos los jugadores y partidas.
- `logo.ico`: El ícono de la página.
