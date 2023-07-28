# MongoDB

Es un sistema de base de datos noSQL, orientado a documentos ( ya no son tablas, sino colecciones ) y de Código abierto, a diferencia de los sistemas de sql, este guarda estructuras de datos JSON con un esquema dinámico, lo cual genera un app mas rápida y fácil de usar.

## CARACTERÍSTICAS 

1. Basada de documentos: Los datos se almacenan en documentos (JSON).
2. Escalable: Fácil de distribuir datos entre varias maquinas.
3. Flexible: No requiere un esquema de datos del documento, puede tener un numero y tipo de datos diferente.
4. Rendimiento: modelos de datos integrados, indexación, fragmentación, documentos flexibles, duplicación nativa, entre otros.
5. Gratis y código abierto.

## Diferencias noSQL y SQL

<img src="./img/MongoDB-vs-SQL.png">

## Glosario y Definiciones

1. Par Clave-Valor: Los Documentos contendrán pares clave-valor.

```json
 {"Nombre":"Jose","Apellido":"Cabrejo"}
```
2. Documentos: Son la equivalencia a las filas, es decir los objetos que vamos a guardaren las colleciones.
3. Colecciones: Es un grupo de Documentos y es el equivalesnte a las tablas en las bases de datos sql.
4. Base de datos NoSQL: Las bases de datos no relacionales que agrupan las colecciones.

## Operaciones CRUD

Las operaciones en esta base NosQL consta de crear, leer, actualizar y eliminar documentos.

### Crear operaciones

Son las operaciones de creacion e insercion, donde se anexan documentos a una coleccion, ademas si la coleccion no existe, estas operaciones tambien crean la coleccion.

### Leer Operaciones

Estas recuperan documentos de una coleccion, es decir realiza consultas.

### Actualizar Operaciones

Modifican los documentos existentes de una coleccion, ademas se puede actualizar uno o varios documentos en una sola operacion.

### Eliminar Operaciones

Elimina los documentos existentes de una coleccion, ademas se puede eliminar uno o varios documentos en una sola operacion.


