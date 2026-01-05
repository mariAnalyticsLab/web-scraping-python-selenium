# web-scraping-python-selenium
### Web Scraping - Extracción de usuarios que etiquetaron al usuario de Instagram con Selenium utilizando Python

## Descripción del algoritmo
- Este proyecto implementa un proceso de web scraping utilizando Python y Selenium para la extracción automatizada de información desde sitios web con contenido dinámico.
- El algoritmo se basa en la automatización del navegador, el manejo de eventos dinámicos y la posterior estructuración de los datos obtenidos.

## Funcionamiento básico
El flujo general del scraping es el siguiente:
1. Configuración del navegador mediante `undetected_chromedriver`.
2. Acceso a la página objetivo.
3. Interacción con elementos dinámicos (clics, desplazamiento y esperas explícitas).
4. Obtención del contenido HTML una vez cargada la información.
5. Procesamiento y limpieza de los datos extraídos.
6. Almacenamiento de la información en estructuras adecuadas para su análisis.

## Resultados y aprendizajes obtenidos
A partir del desarrollo del ejercicio se logró:
- Automatizar la navegación web utilizando Selenium.
- Manejar contenido dinámico mediante esperas explícitas.
- Extraer información estructurada desde páginas web.
- Integrar el scraping con herramientas de análisis de datos.
- Extraer usuarios que etiquetaron a otro usuario.

## Herramientas y tecnologías utilizadas
- Python
- Selenium
- undetected_chromedriver
- BeautifulSoup
- pandas
- Jupyter Notebook/Google Colab

## Datos y archivos importantes
- `scraping.ipynb`: notebook principal con la lógica de scraping y procesamiento de datos.
> No se incluyen credenciales, cookies ni datos sensibles en el repositorio.

## Limitaciones
- El scraping depende de la estructura del sitio web analizado.
- Cambios en el DOM pueden requerir ajustes en los selectores.
- El ejercicio tiene fines educativos y de práctica técnica.
