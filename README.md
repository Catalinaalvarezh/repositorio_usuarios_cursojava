# Panel de Usuarios — JSONPlaceholder

Aplicación web que consume el endpoint público [`https://jsonplaceholder.typicode.com/users`](https://jsonplaceholder.typicode.com/users) y permite explorar la información de los usuarios mediante una clase JavaScript (`GestorUsuarios`) y una interfaz con botones.

## Objetivos de la aplicación

- Practicar el consumo de servicios web (API REST) usando **`XMLHttpRequest`** desde una clase JavaScript.
- Encapsular el manejo de la data recibida (almacenamiento y consultas) dentro de una clase, separando claramente la lógica de datos de la interfaz.
- Implementar métodos que permitan:
  - Listar los nombres de todos los usuarios.
  - Buscar un usuario por nombre (mediante `prompt`) y mostrar su información básica (username y correo).
  - Buscar un usuario por nombre y listar todos los campos de su dirección.
  - Buscar un usuario por nombre y mostrar su información avanzada (teléfono, sitio web y compañía completa).
  - Listar todas las compañías junto a su *catchphrase*.
  - Listar los nombres de todos los usuarios ordenados alfabéticamente.
- Conectar cada método a un botón en la interfaz HTML, de modo que el resultado se pueda observar tanto en la consola del navegador como en un panel visual en la propia página.

## Tecnologías utilizadas

- HTML5 / CSS3
- JavaScript (ES6, clases)
- `XMLHttpRequest` para el consumo del servicio web
- API pública [JSONPlaceholder](https://jsonplaceholder.typicode.com/)

## Cómo ejecutar el proyecto

1. Clona este repositorio o descarga el archivo `index.html`.
2. Ábrelo directamente en cualquier navegador (no requiere servidor ni instalación de dependencias).
3. Espera a que el estado en la parte superior indique que los datos fueron cargados.
4. Usa los botones para probar cada funcionalidad. Los resultados se muestran en la consola del navegador (F12) y en el panel inferior de la página.

## Autora

**Catalina Álvarez H.**
GitHub: [@Catalinaalvarezh](https://github.com/Catalinaalvarezh)

## URL del repositorio

[https://github.com/Catalinaalvarezh/repositorio_usuarios_cursojava](https://github.com/Catalinaalvarezh/repositorio_usuarios_cursojava)
