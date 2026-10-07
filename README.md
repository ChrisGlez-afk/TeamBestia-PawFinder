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

## Mapa de Navegación

<pre>
[Inicio] ---> [Login] ---> [Dashboard Refugio]
   |            |
   |            +--------> [Registro]
   |
   +--------> [Catálogo de Adopción] ---> [Detalle de Mascota]
</pre>

<h2 id="matriz"> Matriz de Trazabilidad</h2>

<p>Relación directa entre los requerimientos funcionales documentados y su implementación en el prototipo:</p>

<ul>
  <li>
    <strong> RF-01 / RF-02: Gestión de Acceso</strong>
    <ul>
      <li><code>registro.html</code> | Formulario para Adoptantes/Refugios con validaciones en <em>js/validaciones.js</em>.</li>
      <li><code>login.html</code> | Autenticación de usuarios con redirección condicional al área privada.</li>
    </ul>
  </li>
  <br>
  <li>
    <strong> RF-05 / RF-06: Exploración y Catálogo</strong>
    <ul>
      <li><code>inicio.html</code> | Vista principal usando <em>CSS Grid</em> para renderizar las tarjetas (Cards) de las mascotas.</li>
      <li><code>inicio.html</code> | Implementación de barra lateral estática para el filtrado visual.</li>
    </ul>
  </li>
  <br>
  <li>
    <strong> RF-03 / RF-04: Administración (Refugios)</strong>
    <ul>
      <li><code>dashboard.html</code> | Panel de control protegido. Incluye tabla responsiva y modales integrados para la edición y alta de nuevas mascotas.</li>
    </ul>
  </li>
</ul>

<hr>

<h2 id="evidencias"> Evidencias de Diseño Responsivo</h2>

<p>El diseño del prototipo fue estructurado bajo el principio <em>Mobile First</em>, garantizando la accesibilidad en cualquier dispositivo.</p>



<div align="center">
  <img width="1900" height="875" alt="{41F4CDD7-3607-41E3-B8C6-EDE6E3E23344}" src="https://github.com/user-attachments/assets/8825fda6-e44c-453d-a496-87fc1681b589" />
" alt="Vista Móvil - Inicio" width="250"/>
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img width="1896" height="886" alt="{854F4111-A90F-428D-9D1E-20E644E15B65}" src="https://github.com/user-attachments/assets/9e40989f-4d32-4268-9e2e-7a68bd150f5d" />
" alt="Vista Móvil - Catálogo" width="250"/>
</div>

<hr>

<h2 id="ia"> Declaración de Uso de IA</h2>

<p>
  Se emplearon modelos de lenguaje grandes (LLMs) estrictamente como herramientas de apoyo para iterar la estructura de la documentación, afinar la justificación del problema y resolver dudas puntuales de sintaxis en CSS/JS. Todo el código final fue revisado, adaptado y es completamente comprendido por los desarrolladores responsables.
</p>
