# Proyecto Urban Routes-es

## Nombre completo y Cohort
- **Nombre**: Ruby Alejandra Carmona Ramirez
- **Cohort**: 22

## Descripcion

En este proyecto se verificará el proceso completo para pedir un taxi en la aplicación Urban Routes.

Para ello se han escrito pruebas automatizadas de acuerdo a las acciones descritas en el ejercicio 1, del Proyecto final del sprint 8.

## Documentacion del proyecto

Tecnologías utilizadas:
- **Python**: Lenguaje principal para le desarrollo de las pruebas.
- **Pytest**: Framework utilizado para escribir y ejecutar pruebas automatizadas.
- **Selenium**: Es una herramienta de código abierto que se utiliza para automatizar en navegadores web en este caso en particular con Google Chrome.
- **Git**: Control de versiones.
- **WebDriver**: Es una parte fundamental de Selenium que se encarga de interactuar directamente con el navegador web en la ejecución de las pruebas.
- **JSON**: Es un formato de intercambio de datos ligero y fácil de usar usado para manejar las respuestas de la API en el proceso de obtención del código de confirmación del número telefónico.

### Prubas implementadas

Se definieron e instanciaron los localizadores y métodos necesarios  y las pruebas en Test.py.

Se generó el script de prueba bajo el Modelo de Objetos de Página (POM), estableciendo los hooks de precondición y postcondición del escenario completo para pedir un taxi de acuerdo con los siguientes pasos:


1. Configurar la dirección.
2. Seleccionar la tarifa Comfort.
3. Rellenar el número de teléfono.
4. Agregar una tarjeta de crédito.
5. Escribir un mensaje para el controlador.
6. Pedir una manta y pañuelos.
7. Pedir 2 helados.
8. Aparece el modal para buscar un taxi.
9. Esperar a que aparezca la información del conductor en el modal.


#### INSTRUCCIONES PARA EJECUTAR LAS PRUEBAS

Instala las dependencias necesarias: Selenium, Pytest

Reemplazar la variable urban_routes_url dentro del archivo data.py, con la URL actualizada del servidor.

Ejecutar (Run) el archivo main.py

Comprobar el resultado de la ejecución en Test.py

PASSED [100%]

Process finished with exit code 0.