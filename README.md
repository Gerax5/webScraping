Integrantes:
Sebastian Juárez - 21471 
Gabriel García - 21352 
Gerardo Pineda - 22880 

Link Del Video
https://youtu.be/VtaTndUXcJY

Extracción de Productos desde HTML

Este proyecto consiste en la extracción automatizada de nombres de productos y URLs de imágenes desde una página web descargada, utilizando Python y expresiones regulares. El objetivo es generar un archivo CSV con los datos obtenidos.

Requisitos

- Python 3.x
- Módulo re (incluido en Python)
- Módulo csv (incluido en Python)

Instrucciones

Descargar una página web que contenga productos de una tienda de comercio electrónico o de videojuegos.
Guardar el archivo HTML de la página en la carpeta data/ bajo el nombre SteamNovedades.html (o el nombre correspondiente).

Ejecutar el script Python que:
Carga el archivo HTML.
Utiliza expresiones regulares para extraer los nombres de productos y las URLs de sus imágenes.
Guarda los resultados en un archivo CSV llamado productos.csv.

Notas

Se recomienda utilizar páginas con pocos productos o editar el HTML para simplificar las pruebas.

El script usa expresiones regulares para extraer la información de manera eficiente.

Se pueden modificar los patrones de expresión regular según la estructura HTML de la página seleccionada.

Resultados

El archivo productos.csv generado contiene dos columnas:

Nombre del Producto: Nombre extraído del HTML.

URL de la Imagen: Dirección de la imagen del producto.

