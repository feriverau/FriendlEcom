# FriendlEcom

**Plataforma de comercio electrónico de productos de computación y electrónica, desarrollada con Django.**

FriendlEcom es una aplicación web orientada al mercado chileno que permite explorar un catálogo de productos tecnológicos, gestionar un carrito de compras y realizar pedidos. El proyecto incorpora, además, funcionalidades de compatibilidad entre componentes de PC para facilitar la selección de hardware.

## Tecnologías

- **Backend:** Python, Django
- **Base de datos:** PostgreSQL
- **Frontend:** HTML, CSS, JavaScript y plantillas de Django
- **Almacenamiento de imágenes:** Amazon S3
- **Despliegue:** Railway
- **Control de versiones:** Git y GitHub

## Funcionalidades

- Catálogo de productos organizado por categorías y subcategorías.
- Búsqueda de productos y visualización de sus detalles.
- Registro y autenticación de usuarios.
- Gestión del carrito de compras.
- Flujo de compra y registro de pedidos.
- Administración de productos e inventario mediante Django Admin.
- Relaciones de compatibilidad entre procesadores, placas madre y memorias RAM.
- Despliegue de la aplicación web con base de datos PostgreSQL y almacenamiento externo de imágenes.

## Compatibilidad de componentes

Una de las funcionalidades distintivas de FriendlEcom es la incorporación de relaciones entre determinados componentes de PC. El sistema utiliza estas relaciones para ayudar a identificar compatibilidades e incompatibilidades entre procesadores, placas madre y memorias RAM durante la exploración de productos.

## Arquitectura

FriendlEcom utiliza una arquitectura monolítica basada en Django. La lógica de negocio, el acceso a datos y la generación de las páginas web se gestionan desde la aplicación, utilizando las plantillas de Django para renderizar la interfaz.

La aplicación utiliza PostgreSQL para la persistencia de datos y servicios externos para el despliegue y el almacenamiento de imágenes.

## Estado del proyecto

Proyecto académico de desarrollo de software, utilizado para aplicar conocimientos de programación backend, bases de datos relacionales, desarrollo web y despliegue de aplicaciones.

## Autor

**Fernando Alberto Rivera Uribe**

Analista Programador Computacional — Duoc UC

GitHub: [@feriverau](https://github.com/feriverau)