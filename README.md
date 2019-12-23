# Incidencias-Python

Proyecto de Incidencias en su versión Python

## Descripción

Este proyecto, es una versión en Python no terminada de la aplicación Incidencias realizado en JAVA, también disponible en esta cuenta.
Se utilizó el lenguaje de programación Python3. Para la interfaz gráfica se utilizó Qt5 (para la versión aquí disponible). La conexión y consulta a la base de datos se lleva a cabo mediante SQLite.

La base de datos incidencias tiene 2 tablas: alfabetico y vaclic. Las tablas alfabetico y vaclic están relacionadas por el campo "id"
* alfabetico - sirve para administrar todos los datos generales de los empleados.
* vaclic - sirve para administrar las incidencias de tipo vacaciones y licencias asociadas a cada empleado.

## Particularidades en la interfaz gráfica

* Los datos se despliegan en QTableView
* En la clase Alfabetico se cuenta con un QLabel para filtrar los registros considerando tres campos como valores de condición. La tabla se va filtrando mientras se escribe en el campo de búsqueda.
* Para el ingreso y actualización de datos se utiliza validación de datos.
* En el caso del cuadro de diálogo para administrar los registros de la tabla alfabetico, se resaltan en color rojo los campos "NumEmp" y "Nombre" cuando se tienen valores repetidos.
