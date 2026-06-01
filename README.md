# Documentación del Proyecto Escolar: Sistema de Reservas de Cine

**Nombre:** Christopher Sanchez  
**Materia:** Administración de base de datos  
**Tema:** Documentación profesional con Markdown  
**Fecha:** 1 de junio, 2026  

---

## Índice

1. [Introducción](#introducción)
2. [Objetivo del proyecto](#objetivo-del-proyecto)
3. [Herramientas utilizadas](#herramientas-utilizadas)
4. [Estructura del proyecto](#estructura-del-proyecto)
5. [Funcionalidades principales](#funcionalidades-principales)
6. [Tabla de módulos](#tabla-de-módulos)
7. [Imagen del proyecto](#imagen-del-proyecto)
8. [Ejemplo de código](#ejemplo-de-código)
9. [Enlaces de referencia](#enlaces-de-referencia)
10. [Conclusión](#conclusión)

---

## Introducción

Este documento presenta la documentación básica de un proyecto escolar llamado **Sistema de Reservas de Cine**. El propósito de esta documentación es explicar de manera clara la estructura, las herramientas utilizadas y las funciones principales del sistema.

Para organizar la información se utiliza Markdown, ya que permite crear documentos limpios, ordenados y fáciles de leer. Además, Markdown es muy utilizado en el área de programación y tecnología porque facilita la creación de documentación técnica.

---

## Objetivo del proyecto

El objetivo principal del proyecto es crear un sistema que permita consultar películas disponibles, visualizar funciones, seleccionar asientos y registrar reservas de manera sencilla.

Esta documentación sirve como guía para entender cómo está organizado el proyecto, qué herramientas se utilizan y cuáles son sus funcionalidades principales.

---

## Herramientas utilizadas

Para el desarrollo y documentación del proyecto se utilizaron las siguientes herramientas:

- GitHub
- Markdown
- Visual Studio Code
- Python
- MySQL
- Navegador web

---

## Estructura del proyecto

La estructura básica del proyecto puede organizarse de la siguiente manera:

```txt
sistema-reservas-cine/
│
├── backend/
│   ├── main.py
│   └── database.py
│
├── frontend/
│   ├── home.py
│   └── components/
│
├── imagenes/
│   └── cine.png
│
└── README.md
```

---

## Funcionalidades principales

El sistema de reservas de cine cuenta con varias funcionalidades importantes que permiten organizar el proceso de consulta y reserva de una película. Estas funciones ayudan a que el usuario pueda ver la información disponible y realizar una reserva de manera sencilla.

Entre sus funcionalidades principales se encuentran:

- Mostrar las películas disponibles.
- Consultar los horarios de las funciones.
- Visualizar la sala correspondiente.
- Seleccionar los asientos disponibles.
- Registrar los datos del cliente.
- Calcular el total de la reserva.
- Guardar la información de la reserva.
- Mostrar una confirmación final de la reserva realizada.

---

## Tabla de módulos

| Módulo | Descripción | Estado |
|---|---|---|
| Películas | Muestra la lista de películas disponibles en el sistema. | Completado |
| Funciones | Permite consultar horarios, fechas, salas e idioma de cada película. | Completado |
| Asientos | Permite seleccionar los asientos disponibles para una función. | En proceso |
| Reservas | Registra los datos del cliente y la información de la reserva. | En proceso |
| Confirmación | Muestra el resumen final de la reserva realizada. | Pendiente |

---

## Imagen del proyecto

La siguiente imagen representa el concepto general del sistema de reservas de cine:

![Imagen del proyecto](https://images.unsplash.com/photo-1489599849927-2ee91cede3ba)

---

## Ejemplo de código

El siguiente código muestra un ejemplo simple para calcular el total de una reserva según el precio de la boleta y la cantidad de asientos seleccionados:

```python
def calcular_total(precio, cantidad_asientos):
    total = precio * cantidad_asientos
    return total

precio_base = 250
cantidad = 3

print("Total a pagar:", calcular_total(precio_base, cantidad))
```

Este ejemplo representa una parte básica del proceso de reserva, ya que el sistema debe calcular cuánto debe pagar el cliente según la cantidad de asientos elegidos.

---

## Enlaces de referencia

Estos enlaces fueron utilizados como apoyo para comprender mejor el uso de Markdown y la documentación de proyectos:

- [GitHub](https://github.com)
- [Markdown Guide](https://www.markdownguide.org/)
- [Documentación de GitHub sobre Markdown](https://docs.github.com/github/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)

---

## Conclusión

En conclusión, esta documentación muestra cómo Markdown puede utilizarse para crear documentos claros, organizados y profesionales. A través de títulos, subtítulos, listas, tablas, imágenes, enlaces y bloques de código, es posible presentar la información de un proyecto de manera sencilla y entendible.

Markdown es una herramienta muy útil en el área de la tecnología, especialmente para documentar proyectos de programación y bases de datos. Además, al utilizar GitHub, la documentación puede publicarse fácilmente y compartirse mediante un enlace.

Este trabajo permitió practicar la creación de documentación profesional y comprender la importancia de organizar correctamente la información de un proyecto.
