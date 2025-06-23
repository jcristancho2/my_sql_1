# MySQL - Prácticas Iniciales

[![MySQL](https://img.shields.io/badge/MySQL-8.0+-4479A1?style=for-the-badge&logo=mysql&logoColor=white)](https://www.mysql.com/)
[![SQL](https://img.shields.io/badge/SQL-Query-336791?style=for-the-badge&logo=sql&logoColor=white)](https://www.w3schools.com/sql/)
[![Database](https://img.shields.io/badge/Database-Relational-336791?style=for-the-badge&logo=database&logoColor=white)](https://en.wikipedia.org/wiki/Relational_database)
[![License](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)](https://github.com/yourusername/taller-mysql)


Repositorio desarrollado como parte de ejercicios prácticos del curso de bases de datos. Aquí encontrarás las estructuras y sentencias necesarias para la creación de una base de datos relacional en MySQL, incluyendo sentencias `CREATE`, `INSERT`, `SELECT`, y uso de `FOREIGN KEYS`, junto con relaciones normalizadas.


## 📁 Estructura del Proyecto

El proyecto contiene los siguientes archivos y carpetas:

- `01_creacion_base_datos.sql`: Script con las sentencias `CREATE DATABASE`, creación de tablas con claves primarias y foráneas, y definición de relaciones.
- `02_inserts.sql`: Sentencias `INSERT INTO` con datos de prueba para poblar las tablas.
- `03_consultas.sql`: Consultas SQL para extracción de datos relevantes.
- `diagramas/`: Diagramas entidad-relación exportados desde herramientas como MySQL Workbench o StarUML.

## 🛠️ Tecnologías Utilizadas

- MySQL
- dbdiagram


## 🔗 Enlaces de Interés

- [Pdf](https://github.com/jcristancho2/my_sql_1/blob/main/Taller%20Mysql.pdf)
- [Modelo E-R y normalización](https://dbdiagram.io/d/68599f89f039ec6d36862fda)

## 📌 Temas Abordados

- Creación de base de datos y tablas
- Relaciones 1 a 1, 1 a N y N a N
- Normalización hasta 3NF
- Claves primarias y foráneas
- Consultas con `JOIN`, `GROUP BY`, `ORDER BY`
- Inserción de datos estructurados
- Integridad referencial

## ✅ Requisitos para Ejecutar

- Tener instalado MySQL Server
- Editor de SQL o consola MySQL
- Clonar el repositorio y ejecutar los scripts en orden:

## ⚙️ Instalación y Configuración

### 📋 Prerrequisitos

- [MySQL](https://www.mysql.com/downloads/) 8.0 o superior
- [MySQL Workbench](https://www.mysql.com/products/workbench/) (opcional)
- Conocimientos básicos de SQL

### 🚀 Instalación Rápida

1. **Clonar el repositorio**
```bash
git clone [https://github.com/yourusername/taller-mysql.git](https://github.com/jcristancho2/my_sql_1.git)
cd taller-mysql-1
```

2. **Crear la base de datos**
```bash
mysql -u root -p < vtaszfs.sql
```

3. **Verificar la instalación**
```sql
USE vtaszfs;
SHOW TABLES;
```


## 💻 Autor

[**Jorge Andrés Cristancho Olarte**]  (https://github.com/jcristancho2)

## 📄 Licencia

Este proyecto está bajo la Licencia MIT - ver el archivo [LICENSE](LICENSE) para más detalles.

---

<div align="center">

**¡Gracias por visaulizar el proyecto 👽️**


</div>
