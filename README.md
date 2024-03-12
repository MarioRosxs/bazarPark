# Clases Java: Articulo, Inventario y Usuario

Este repositorio contiene tres clases Java diseñadas para gestionar artículos, inventario y usuarios.

## Clase Articulo

La clase `Articulo` representa un artículo con un identificador único (`idArt`) y un nombre (`nombreArt`). Posee los siguientes métodos:

- `getIdArt()`: Retorna el identificador del artículo.
- `setIdArt(int idArt)`: Establece el identificador del artículo.
- `getNombreArt()`: Retorna el nombre del artículo.
- `setNombreArt(String nombreArt)`: Establece el nombre del artículo.

## Clase Inventario

La clase `Inventario` representa un inventario que contiene un artículo. Posee un atributo `articulos` del tipo `Articulo` y los siguientes métodos:

- `getArticulos()`: Retorna el artículo presente en el inventario.
- `setArticulos(Articulo articulos)`: Establece el artículo presente en el inventario.

## Clase Usuario

La clase `Usuario` representa un usuario con un identificador único (`idUser`), un nombre, una contraseña y una dirección de correo electrónico. Posee los siguientes métodos:

- `getIdUser()`: Retorna el identificador del usuario.
- `setIdUser(int idUser)`: Establece el identificador del usuario.
- `getNombre()`: Retorna el nombre del usuario.
- `setNombre(String nombre)`: Establece el nombre del usuario.
- `getContraseña()`: Retorna la contraseña del usuario.
- `setContraseña(String contraseña)`: Establece la contraseña del usuario.
- `getCorreo()`: Retorna la dirección de correo electrónico del usuario.
- `setCorreo(String correo)`: Establece la dirección de correo electrónico del usuario.
