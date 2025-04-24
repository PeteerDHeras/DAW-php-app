# Botiga de Productes

Esta es una aplicación web básica desarrollada en PHP que permite gestionar productos de una tienda. Utiliza una base de datos MySQL y Bootstrap para el diseño visual.

## Características

- Muestra una lista de productos con su nombre, descripción, precio y categoría.
- Permite modificar o eliminar productos existentes.
- Incluye la opción para agregar un nuevo producto.
- Interfaz visual responsiva gracias a Bootstrap.

## Estructura del proyecto

- `Principal.php`: Página principal donde se listan los productos.
- `Connexio.php`: Clase que gestiona la conexión a la base de datos.
- `Nou.php`: Página para crear un nuevo producto.
- `Modificar.php`: Página para editar un producto.
- `Eliminar.php`: Página para eliminar un producto.
- `Header.php` y `Footer.php`: Plantillas para la cabecera y pie de página comunes.

## Requisitos

- Servidor web con soporte PHP (por ejemplo, XAMPP, WAMP, etc.)
- MySQL o MariaDB
- Navegador moderno

## Cómo usar

1. Clona el repositorio o copia los archivos al servidor local.
2. Configura la base de datos en `Connexio.php`.
3. Asegúrate de que la base de datos contiene las tablas `productes` y `categories`.
4. Accede a `Principal.php` desde tu navegador para comenzar a usar la aplicación.

## Autor

Proyecto de ejemplo creado con fines educativos.
