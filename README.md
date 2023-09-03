# BTXF, plataforma de inscripción y clasificación ciclista.

![BTXF](https://github.com/robmab/Proyect-BTFX/assets/56076087/de7d088c-9cce-4c36-a344-79aaaf1082cc)

BTXF es una plataforma donde cualquier persona puede inscribirse a las distintas pruebas ciclistas disponibles por la misma, al mismo tiempo que ver los resultados de los torneos. Así mismo cuenta con un panel de administrador donde cualquiera con el rol de manager pueda gestionar las inscripciones para asignar dorsales, así como registrar los resultados de las pruebas.

## Características:
- **Home** con una pequeña presentación de la plataforma, así como un **localizador** de la sede por **GoogleMaps**
- Lista de **eventos ciclistas** con descripción disponibles para **inscripción** de los usuarios registrados, así como un formulario de registro para los mismos.
- Vista de la **clasificación** de todos los torneos y eventos correspondientes al mismo, con un **sistema de filtros dinánimo** que permite buscar por categoría si se desea.
- Sistema completo para usuarios, que permite tanto el **registro, login y visualización/ edición de perfil**. Sistema de **recuperación de contraseña** por email incorporada también.
- **Panel de control** para *managers* y *administradores*, permitiendo la **gestión de inscripciones de usuarios** entrantes pàra asignar el equipo, categoría y dorsal del mismo. Solo permitirá asignar dorsales disponibles para la ese prueba.
  - Solo para usuarios *administradores* - tendrán una opción para **registrar los resultados de las pruebas**, tanto tiempo como puntuación, que se verán reflejadas al momento en la vista de clasificación.
- **Políticas de uso, privacidad** y **aviso legal**

## Responsive:
Esta página web ha sido diseñada tanto tanto para escritorio, como para tablet/móvil.

## Tecnologías:
- Frontend
React, Javascript, HTML, CSS, Bootstrap
- Backend
Python, Flask, Flask SQLAlchemy
