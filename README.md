# Fundamentos de Bases de Datos

## 1. Conceptos básicos

- _Base de datos:_ Conjunto organizado de datos almacenados electrónicamente, diseñado para facilitar su acceso y manipulación.
- _Sistema de gestión de bases de datos (DBMS):_ Software que permite interactuar con la base de datos. Ejemplos: MySQL, PostgreSQL, Oracle, MongoDB.
- _Datos:_ Información sin procesar que puede ser organizada para obtener significado.
- _Información:_ Resultado del procesamiento y análisis de datos.

## 2. Modelos de bases de datos

- _Modelo relacional:_ Organiza los datos en tablas (o relaciones). Es el modelo más común y utiliza SQL para interactuar con los datos.
- _Modelo jerárquico:_ Representa los datos en una estructura tipo árbol.
- _Modelo en red:_ Estructura más flexible que permite relaciones en red entre los datos.
- _Modelo orientado a documentos:_ Usado en bases de datos NoSQL (ej.: MongoDB), almacena datos como documentos JSON o XML.

## 3. Componentes principales

1. _Tablas (relacional):_
   - Filas (tuplas): Representan un registro único.
   - Columnas (atributos): Representan las propiedades de los datos.
2. _Llaves:_
   - _Primaria:_ Identifica de manera única una fila.
   - _Foránea:_ Relaciona una tabla con otra.
3. _Índices:_ Estructuras que mejoran la velocidad de búsqueda de datos.
4. _Esquema:_ Estructura lógica que define cómo se organizan las tablas y relaciones.

## 4. Lenguajes de bases de datos

- _SQL (Structured Query Language):_ Lenguaje estándar para interactuar con bases de datos relacionales.
  - _DDL (Data Definition Language):_ Define y modifica la estructura (CREATE, ALTER, DROP).
  - _DML (Data Manipulation Language):_ Manipula los datos (INSERT, UPDATE, DELETE, SELECT).
  - _DCL (Data Control Language):_ Controla el acceso (GRANT, REVOKE).

## 5. Normalización

Proceso para organizar datos en tablas para reducir redundancia y mejorar integridad. Incluye:

- _1FN (Primera Forma Normal):_ Eliminar grupos repetidos.
- _2FN (Segunda Forma Normal):_ Eliminar dependencias parciales.
- _3FN (Tercera Forma Normal):_ Eliminar dependencias transitivas.

## 6. Integridad de datos

- _Integridad de entidad:_ Garantiza que cada fila tiene una identificación única.
- _Integridad referencial:_ Asegura que las relaciones entre tablas sean consistentes.
- _Integridad de dominio:_ Restringe los valores en una columna a un rango específico.

## 7. Transacciones

Una transacción es un conjunto de operaciones que se ejecutan como una unidad lógica. Deben cumplir las propiedades _ACID_:

- _Atomicidad:_ Todas las operaciones se completan o ninguna.
- _Consistencia:_ La base de datos permanece en un estado válido.
- _Aislamiento:_ Las transacciones no interfieren entre sí.
- _Durabilidad:_ Los cambios persisten incluso ante fallos.

## 8. Bases de datos relacionales vs. NoSQL

| _Relacional_           | _NoSQL_                  |
| ---------------------- | ------------------------ |
| Estructura fija        | Flexible                 |
| Usa SQL                | Usa APIs específicas     |
| Escalabilidad vertical | Escalabilidad horizontal |

## 9. Casos de uso

- _Relacionales:_ Sistemas financieros, ERP, CRM.
- _NoSQL:_ Aplicaciones en tiempo real, big data, redes sociales.
