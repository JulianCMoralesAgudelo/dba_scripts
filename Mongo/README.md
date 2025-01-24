# MongoDB

MongoDB es una base de datos NoSQL orientada a documentos, diseñada para almacenar grandes cantidades de datos semi-estructurados o no estructurados. Utiliza un formato de documento BSON (similar a JSON) para almacenar datos.

## Pros:
- Escalabilidad horizontal: MongoDB es fácil de escalar de manera horizontal (sharding).
- Flexibilidad en el esquema: Los documentos pueden tener diferentes estructuras.
- Ideal para grandes volúmenes de datos no estructurados o semi-estructurados.
- Buen rendimiento en operaciones de lectura y escritura.

## Contras:
- No es ideal para transacciones ACID complejas (aunque soporta transacciones a partir de la versión 4.0).
- Falta de joins y relaciones complejas entre los datos.
- Pueden producirse problemas de consistencia en sistemas distribuidos si no se configura correctamente.
