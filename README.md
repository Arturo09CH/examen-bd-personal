# Examen Base de Datos SQL - Reto 2025

Este proyecto contiene el script SQL para la creación de una base de datos llamada **PERSONAL**, con sus respectivas tablas, relaciones, consultas y procedimientos almacenados.  
El objetivo es evaluar conocimientos en modelado de datos, creación de estructuras, consultas SQL y uso de procedimientos en MySQL.

---

## 📂 Contenido
- **examen_personal.sql** → Script completo que incluye:
  - Creación de la base de datos y tablas.
  - Inserción de datos de ejemplo.
  - Consultas (SELECT) solicitadas en el examen.
  - Procedimientos almacenados (Stored Procedures) con parámetros de entrada.

---

## 📑 Estructura de Tablas
1. **ALUMNOS**
   - LOGIN (Entero, único)
   - AREA (Entero)
   - ZONA (Entero)
   - PUESTO (Entero)
   - NOMBRE (Cadena, máx. 100 caracteres)

2. **AREA**
   - IDAREA (Entero, autoincrementable, PK)
   - DESCRIPCION (Cadena, máx. 50 caracteres)

3. **ZONA**
   - IDZONA (Entero, autoincrementable, PK)
   - DESCRIPCION (Cadena, máx. 50 caracteres)

4. **PUESTO**
   - IDPUESTO (Entero, autoincrementable, PK)
   - DESCRIPCION (Cadena, máx. 50 caracteres)

---

## ⚙️ Ejecución del Script
1. Abrir MySQL Workbench o consola de MySQL.
2. Ejecutar el siguiente comando:
   ```sql
   SOURCE ruta/al/archivo/examen_personal.sql;
