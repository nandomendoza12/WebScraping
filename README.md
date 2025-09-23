Descripción del Proyecto
Este proyecto de web scraping utiliza Python para extraer datos de películas populares de un sitio web. La herramienta recolecta información como el título, el año de lanzamiento y la calificación de cada película, demostrando habilidades en la extracción, limpieza y almacenamiento de datos web. Los datos extraídos se guardan en un archivo CSV para su posterior análisis.

🌟 Características Principales
Extracción de Datos: Utiliza la librería Beautiful Soup para navegar y raspar datos de tablas HTML de un sitio web.

Manejo de Solicitudes: Emplea la librería requests para realizar peticiones HTTP a la página web de destino.

Limpieza de Datos: Procesa y convierte datos de texto (str) a tipos numéricos (int y float) para su correcto almacenamiento y análisis.

Manejo de Errores: Incluye bloques try-except para gestionar posibles errores de conexión y de conversión de datos, haciendo el script más robusto.

Almacenamiento de Datos: Utiliza la librería pandas para estructurar los datos extraídos en un DataFrame y los exporta a un archivo .csv, un formato ideal para análisis y visualización.
