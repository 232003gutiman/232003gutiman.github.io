# 🎓 Proyecto de Base de Datos Universidad MySQL

![Logo UPJR](logo.png)

Este proyecto implementa un sistema completo de base de datos para una universidad utilizando MySQL, desarrollado como parte de la Estancia I en la Universidad Politécnica de Juventino Rosas.

## 📋 Tabla de Contenidos
- [Autoría](#autoría)
- [Objetivos](#objetivos)
- [Estructura de la Base de Datos](#estructura-de-la-base-de-datos)
- [Consultas Implementadas](#consultas-implementadas)
- [Instalación](#instalación)
- [Uso](#uso)
- [Ejemplos Clave](#ejemplos-clave)
- [Visualización en Línea](#visualización-en-línea)
- [Licencia](#licencia)

## 👨‍💻 Autoría
- **Estudiante:** Jorge Gutiérrez Mancera
- **Asesor:** Luis Rey Lara González
- **Institución:** Universidad Politécnica de Juventino Rosas
- **Fecha:** Abril 2025

## 🎯 Objetivos
1. Modelar una base de datos relacional para una institución universitaria
2. Implementar consultas SQL de complejidad variable
3. Documentar el proceso de desarrollo
4. Proporcionar ejemplos prácticos de operaciones CRUD
5. Generar reportes académicos complejos

## 🗃️ Estructura de la Base de Datos
El sistema contiene las siguientes tablas principales:

| Tabla               | Descripción                          |
|---------------------|--------------------------------------|
| `persona`           | Datos de alumnos y profesores        |
| `departamento`      | Áreas académicas                     |
| `profesor`          | Vinculación profesores-departamentos |
| `grado`             | Programas académicos                 |
| `asignatura`        | Materias ofertadas                   |
| `curso_escolar`     | Periodos académicos                  |
| `alumno_se_matricula_asignatura` | Relación alumnos-asignaturas |

## 📊 Consultas Implementadas
### 1. Consultas Básicas
- Listados de alumnos/profesores
- Filtros por fechas, campos nulos, patrones de texto

### 2. Consultas Multitabla
- Composición interna (INNER JOIN)
- Composición externa (LEFT/RIGHT JOIN)
- Relaciones complejas entre 3+ tablas

### 3. Consultas Resumen
- Conteos y agregaciones (COUNT, SUM, AVG)
- Agrupamientos (GROUP BY)
- Filtros sobre agregaciones (HAVING)

### 4. Subconsultas
- Consultas anidadas
- Operaciones EXISTS/NOT EXISTS
- Comparaciones con resultados de subconsultas

## 🛠️ Instalación
1. Clonar el repositorio:
```bash
git https://github.com/232003gutiman/232003gutiman.github.io
cd proyecto-universidad