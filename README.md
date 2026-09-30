# Shaolin Sushi

Shaolin Sushi es una aplicación web de comercio electrónico desarrollada con Python y Django como proyecto académico en Duoc UC para la carrera de Ingeniería en Informática.

El sistema simula la plataforma digital de un restaurante de sushi y permite gestionar productos, usuarios, carrito de compras, inventario y registros de compra.

## Descripción del proyecto

El objetivo del proyecto fue desarrollar una aplicación web que integrara funcionalidades de catálogo y comercio electrónico con herramientas de administración y gestión de usuarios.

La plataforma permite a los clientes explorar el catálogo de productos, registrarse, iniciar sesión, administrar su perfil, agregar productos a un carrito y completar un proceso de compra.

Además, incorpora funcionalidades para administrar los productos disponibles y controlar automáticamente el stock después de cada compra.

## Funcionalidades principales

### Catálogo de productos

- Visualización de productos agrupados por categorías.
- Consulta de información, descripción, precio e imagen de cada producto.
- Visualización del stock disponible.
- Vista individual con los detalles de cada producto.

### Gestión de productos

- Creación de nuevos productos.
- Modificación de productos existentes.
- Eliminación de productos.
- Gestión de imágenes.
- Administración de precios y stock.
- Asociación de productos con categorías.

### Gestión de usuarios

- Registro de nuevos usuarios.
- Inicio y cierre de sesión.
- Gestión de perfiles.
- Edición de información personal.
- Historial de compras asociado a cada usuario.

### Carrito de compras

- Agregar productos al carrito.
- Aumentar o disminuir cantidades.
- Eliminar productos individuales.
- Vaciar completamente el carrito.
- Cálculo del total de la compra.

### Proceso de compra

- Selección entre envío a domicilio o retiro.
- Validación de stock disponible antes de completar la compra.
- Cálculo del subtotal de los productos.
- Cálculo de impuestos.
- Cálculo del costo de envío cuando corresponde.
- Generación de registros de compra.
- Almacenamiento del detalle de los productos comprados.
- Actualización automática del stock después de una compra completada.

## Tecnologías utilizadas

- Python
- Django 5
- HTML
- CSS
- JavaScript
- Bootstrap
- SQLite

## Estructura general

El proyecto utiliza la estructura tradicional de una aplicación Django.

La aplicación principal, `productos`, contiene la lógica relacionada con:

- Modelos de productos y categorías.
- Gestión de compras.
- Carrito de compras.
- Formularios.
- Gestión de usuarios.
- Vistas y navegación.
- Templates de la interfaz.
- Archivos estáticos.

Entre los principales modelos utilizados se encuentran:

- `Envoltura`: categorías de productos.
- `Roll`: productos disponibles en el catálogo.
- `Boleta`: registro general de una compra.
- `detalle_boleta`: detalle de los productos asociados a una compra.

## Instalación

Clonar el repositorio:

```bash
git clone https://github.com/VixoSix/shaolin-sushi-django.git
cd shaolin-sushi-django
```

Crear un entorno virtual:

```bash
python -m venv .venv
```

Activarlo en Windows:

```bash
.venv\Scripts\activate
```

En macOS o Linux:

```bash
source .venv/bin/activate
```

Instalar las dependencias:

```bash
pip install -r requirements.txt
```

Aplicar las migraciones de la base de datos:

```bash
python manage.py migrate
```

Ejecutar el servidor de desarrollo:

```bash
python manage.py runserver
```

La aplicación estará disponible en:

```text
http://127.0.0.1:8000/
```

## Contexto académico

Shaolin Sushi fue desarrollado como proyecto académico en Duoc UC para la carrera de Ingeniería en Informática.

El proyecto permitió aplicar conocimientos relacionados con:

- Desarrollo backend con Python y Django.
- Desarrollo de interfaces web.
- Modelado y persistencia de datos.
- Autenticación y gestión de usuarios.
- Formularios y validaciones.
- Gestión de productos e inventario.
- Carrito de compras.
- Procesamiento de compras.
- Manejo de sesiones.
- Trabajo colaborativo mediante Git y GitHub.

## Autores

- [Hubert Huaman](https://github.com/Hubertjerson)
- [Vicente Riquelme](https://github.com/VixoSix)

## Institución

Duoc UC  
Ingeniería en Informática
