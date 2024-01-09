# Base-de-datos-II---Project
# Proyecto de Base de Datos II con Apache Cassandra

Este proyecto se centra en la implementación y uso de Apache Cassandra, una base de datos NoSQL orientada a columnas.

## Modelo de Datos

El modelo de datos se basa en un espacio de nombres llamado 'tienda', que contiene una familia de columnas denominada 'Productos'. Esta familia de columnas almacena información sobre los productos que vende la empresa, incluyendo el id, el nombre, la cantidad de unidades, el precio, el rango etario, el sexo y el crédito. El atributo 'id' se ha definido como la clave primaria de la familia de columnas, lo que significa que no puede haber dos filas con el mismo 'id'.

## Tareas Realizadas

Las tareas realizadas en este proyecto incluyen:

1. Configuración de Apache Cassandra.
2. Carga de datos en la base de datos con un conjunto de diferentes productos.
3. Realización de consultas para generar información del conjunto.
4. Asimilación de los conceptos de Keyspace y Familia de Columnas.
5. Definición de un Keyspace y una familia en Cassandra.
6. Realización de operaciones CQL, incluyendo creación, inserción, actualización y eliminación.

## Operaciones Realizadas

Las operaciones específicas realizadas incluyen:

1. Creación del espacio de nombres 'tienda'.
2. Creación de la familia de columnas 'Productos'.
3. Inserción de 10 registros en la familia de columnas 'Productos'.
4. Actualización de un registro en la familia de columnas 'Productos'.
5. Eliminación de un registro en la familia de columnas 'Productos'.
6. Consulta de los datos de la familia de columnas 'Productos'.

## Resultados Obtenidos

Los resultados obtenidos incluyen:

1. Creación exitosa del espacio de nombres 'tienda'.
2. Creación exitosa de la familia de columnas 'Productos'.
3. Inserción exitosa de 10 registros en la familia de columnas 'Productos'.
4. Actualización exitosa de un registro en la familia de columnas 'Productos'.
5. Eliminación exitosa de un registro en la familia de columnas 'Productos'.
6. Consulta exitosa de los datos de la familia de columnas 'Productos'.
