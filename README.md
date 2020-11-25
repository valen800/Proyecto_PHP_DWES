# Proyecto_PHP_DWES
Web que contiene información de películas en general, toda esa información es recogida de una API, tiene su propia BBDD para almacenar los datos en caso de que se registre.

- Usuarios anónimos
	- Ver lista de películas.
  - Ver secciones de peliculas destacadas o top, películas recomendadas.
  - Al pulsar en película ver todos sus datos y puede reproducir trailer.
	
- Usuarios Registrados
  -Puede hacer todo lo anteriormente dicho con los usuarios anónimos.
  -Tiene perfil y puede modificar todos los datos introducidos en el registro.
  -Puede añadir películas a visto, pendiente, favoritos, para tener registro de las películas.
  -Quitar las películas de las secciones anteriomente nombradas.
  
- Usamos BBDD No relacional Firebase para guardar los datos del usuario logueado, los datos de las películas lo obtenemos de la API.
