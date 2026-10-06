<div align="center">

# PawFinder: Plataforma de Adopción de Mascotas

Plataforma web para centralizar y facilitar la adopción de mascotas de refugios locales, optimizando su visibilidad y proceso de reubicación.

[![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)](#)
[![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)](#)
[![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)](#)
[![Bootstrap](https://img.shields.io/badge/bootstrap-%238511FA.svg?style=for-the-badge&logo=bootstrap&logoColor=white)](#)
[![Figma](https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white)](#)

</div>

---

## Descripción del Proyecto

PawFinder es el proyecto final para la materia de Desarrollo de Aplicaciones Web. Su objetivo es mitigar la saturación de refugios de animales en la región mediante una plataforma web que unifica la oferta de adopción, conectando a los refugios con adoptantes potenciales.

## Equipo de Desarrollo (TeamBestia)

*   **Christian Alexis González Ayala:** Coordinador y gestor del repositorio.
*   **Víctor Javier Romo Castro:** Diseñador UX/UI.
*   **Christopher Williams Ponce:** Desarrollador Front-End 1 (Vistas públicas de acceso).
*   **Diego Armando Araujo García:** Desarrollador Front-End 2 (Vistas internas y módulos).

## Instrucciones de Ejecución Local

Para visualizar el prototipo Front-End de manera local:

1.  Clonar el repositorio: `git clone https://github.com/TU-USUARIO/TeamBestia-PawFinder.git`
2.  Navegar al directorio del proyecto: `cd TeamBestia-PawFinder`
3.  Abrir el archivo `index.html` en un navegador web o ejecutar mediante un servidor local (ej. Live Server).

**Credenciales de Demostración:**
*   Usuario: demo@pawfinder.com
*   Contraseña: password123

## Mapa de Naveg

```text
[Inicio] ---> [Login] ---> [Dashboard Refugio]
   |            |
   |            +--------> [Registro]
   |
   +--------> [Catálogo de Adopción] ---> [Detalle de Mascota]


## 🔗 Matriz de Trazabilidad

A continuación se muestra la relación directa entre los requerimientos funcionales documentados y su implementación en las vistas del prototipo.

| Requerimiento | Vista (Archivo HTML) | Componentes / Lógica |
| :--- | :--- | :--- |
| **RF-01** Registro de usuarios (Adoptante/Refugio) |  `registro.html` | Formulario estructurado, validaciones en `js/validaciones.js`. |
| **RF-02** Inicio de sesión |  `login.html` | Formulario de autenticación con redirección a `dashboard.html`. |
| **RF-05** Visualización del catálogo de mascotas |  `inicio.html` | Componente de tarjetas (Cards) iteradas para la galería. |
| **RF-06** Filtrado de mascotas |  `inicio.html` | Barra lateral con opciones de filtrado. |
| **RF-03 / RF-04** Gestión de mascotas por el refugio |  `dashboard.html` | Panel de control (Dashboard) con tabla de registros y modales de edición. |

<br>

##  Evidencias de Diseño Responsivo

El diseño del prototipo fue desarrollado bajo el enfoque *Mobile First*. 

> **Nota:** Reemplazar las siguientes líneas con las imágenes correspondientes de la carpeta `docs/`.

*   `![Vista Móvil - Inicio](docs/mobile-inicio.png)`
*   `![Vista Móvil - Catálogo](docs/mobile-catalogo.png)`

<br>

## Declaración de Uso de IA

Se utilizaron herramientas de inteligencia artificial exclusivamente como apoyo para la estructuración de la documentación y consulta de sintaxis, cumpliendo con la capacidad técnica del equipo para explicar y defender el código desarrollado.
