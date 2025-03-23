# Platzi - Curso de Bases de Datos con SQL

Este proyecto contiene los ejercicios, scripts y notebooks creados durante el curso de **Bases de Datos con SQL** dictado por Platzi. Se enfoca en el uso de **SQLite** como motor de base de datos para propósitos educativos y de prototipado.

---

## 🔗 Badges

![Python Version](https://img.shields.io/badge/python-3.12-blue)
![License](https://img.shields.io/badge/license-Apache%202.0-green)

---

## 📁 Estructura del Proyecto

```
platzi-db-sql/
│
├── data/                  # Archivos de datos crudos o procesados (CSV, JSON, etc.)
├── db/                    # Base de datos SQLite (ej. mi_base.db) y esquemas .sql
├── notebooks/             # Notebooks de Jupyter con consultas SQL y código Python
├── src/                   # Código fuente Python para carga, limpieza y queries
├── tests/                 # Scripts o pruebas relacionadas al uso de la base de datos
├── .gitignore             # Archivos y carpetas excluidos de git
├── LICENSE                # Licencia del proyecto
└── README.md              # Documentación general del proyecto
```

---

## 🚀 Tecnologías usadas

- **SQLite 3** como base de datos embebida
- **Python 3.12** para consultas y manejo de datos
- **Jupyter Notebook** para exploración y práctica
- **pandas** para transformaciones en notebooks
- **ipython-sql** para ejecutar SQL directamente en celdas
- **conda** como gestor de entorno virtual

---

## 📖 Tablas principales

- `students`: Información de los estudiantes
- `instructors`: Profesores o instructores
- `courses`: Cursos disponibles y su instructor
- `students_courses`: Relación muchos-a-muchos entre estudiantes y cursos

---

## ✨ Objetivos del curso

- Comprender los conceptos básicos de bases de datos relacionales
- Aprender a modelar tablas y relaciones
- Aplicar comandos SQL: `CREATE`, `INSERT`, `SELECT`, `JOIN`, `WHERE`, `GROUP BY`
- Consultar una base de datos desde Python
- Desarrollar un mini sistema de estudiantes, cursos e inscripciones

---

## ✍️ Instrucciones para correr el proyecto localmente

1. Clona este repositorio:
   ```bash
   git clone git@github.com:jasonssdev/platzi-db-sql.git
   ```

2. Crea el entorno con conda:
   ```bash
   conda env create -f environment.yml
   conda activate platzi-sql
   ```

3. Inicia Jupyter:
   ```bash
   jupyter notebook
   ```

4. Abre los notebooks en la carpeta `notebooks/` y ejecuta celdas paso a paso.

---

## 💡 Notas

- Se recomienda usar `db/schema.sql` para reconstruir la base de datos.

---

## 💼 Licencia

Este proyecto se distribuye bajo la licencia **Apache 2.0**. Consulta el archivo `LICENSE` para más información.

