# Backlog de mi-portafolio

Este archivo es el **plan** del proyecto. Cada historia de usuario (HU) de aquí
se convierte en un **issue** en GitHub, se pone en el **tablero** de GitHub
Projects y se cierra con un **commit** que diga `closes #número`.

Formato de cada criterio de aceptación:

> `- [ ] Dado <contexto>, cuando <acción>, entonces <resultado esperado>.`

Cuando crees el issue en GitHub, escribe su número en la línea **Issue:**
(por ejemplo `**Issue:** #4`).

---

## HU-01 · Menú de navegación fijo  ✅ (ejemplo resuelto)

**Historia:** Como visitante del portafolio, quiero un menú fijo en la parte superior, para ir a cualquier sección sin hacer scroll.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que abro el portafolio, cuando miro la parte superior, entonces veo un menú con enlaces a "Sobre mí", "Proyectos" y "Contacto".
- [ ] Dado que estoy en la parte de arriba, cuando hago clic en "Proyectos", entonces la página baja hasta la sección de proyectos.
- [ ] Dado que hice scroll hasta el final, cuando miro la parte superior de la pantalla, entonces el menú sigue visible.

**Issue:** #2

---

## HU-02 · Sección de habilidades  ✅ (ejemplo resuelto)

**Historia:** Como reclutador, quiero ver las habilidades técnicas del aprendiz en una lista, para evaluar rápidamente si su perfil encaja con la vacante.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que abro el portafolio, cuando llego a la sección "Habilidades", entonces veo al menos 6 habilidades técnicas.
- [ ] Dado que estoy en la sección "Habilidades", cuando la leo, entonces las habilidades están agrupadas en "Frontend" y "Herramientas".
- [ ] Dado que estoy en el menú, cuando hago clic en "Habilidades", entonces la página baja hasta esa sección.

**Issue:** #3

---

## HU-03 · Pie de página con redes ✅

**Historia:** Como visitante, quiero un pie de página con el año y los enlaces a las redes del aprendiz, para contactarlo desde cualquier parte de la página.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado relizo scroll hasta el pie de pagina puedo visualizar el año actual y mis redes sociales.
- [ ] Dado que me encuentro sobre el pie de pagina al realizar click sobre las redes sociales, sere redireccionado a la pagina correspondiente por medio de un URL.
- [ ] Dado que estoy vizulisando el pie de pagina desde mi dispositivo movil, los iconos de las redes sociales y sus respecticos enlaces se acomadaran de forma legible y comoda para la apropiada navegación.

**Issue:** 4

---

## HU-04 · Enlace al repositorio en cada proyecto ✅

**Historia:** Como reclutador, quiero que cada tarjeta de proyecto tenga un enlace a su repositorio en GitHub, para revisar el código que escribió el aprendiz.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que estoy visualizando la ficha de un proyecto que es de mi interes cuando reviso su contenido puedo encontrar un link que me redirecciona al repositorio en gitthub de dicho proyecto.
- [ ] Dado que estoy visualizando la ficha del proyecto al hacer click en link del repositorio de dicho proyecto, se abrira una nueva pesataña en el navegador.
- [ ] Cuando relizo la reficción al repositorio del proyecto debo estar claramente informado de que se me esta redirigiendo a un enlace externo de github.


**Issue:** 5

---

## HU-05 · Portafolio adaptable al celular

**Historia:** Como visitante que usa el celular, quiero que el portafolio se vea bien en pantallas pequeñas, para leerlo sin hacer zoom ni scroll horizontal.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** M

**Criterios de aceptación:**

- [ ] Dado que estoy navegando desde mi celular debo visualizar todos los elementos del sitio web sin realizar desplazamientos horizontales pese a la enorme diferencia en la relación de aspecto entre las versiones deskpot y mobile.
- [ ] Dado que me encuentro navegando el versión mobile de la aplicación al hacer un tap sobre el boton de menú, se deben desplegar las secciones de forma vertical.
- [ ] Dado que me encuentro usando un celular todas interacciones entre la pagina y el usuario deben ser faciles de realizar unicamente con el "swiping" y "tap"

**Issue:** 6

---

## HU-06 · (RETO) Adaptación al modo oscuro / claro

**Historia:** Como visitante que del sitio web, quiero poder seleccionar en un modo claro/oscuro que yo requiera segun mi preferencia para evitar la fatiga visual lo mas posible.

**Etiquetas:** historia, frontend · 
**Estimación:** M

**Criterios de aceptación:**

- [ ] Dado que estoy visualizando cualquier selección de sitio web debo poder cambiar el modo de visualización de forma dinamica haciendo click o tap sobre el icono de sol/luna.
- [ ] Dado que recargo o vuelvo a ingresar a la pagina, esta tendra la función de recordar cual fue la ultima configuración de modo claro/oscuro que he aplicado.
- [ ] Dado que a que mi sistema operativo esta por defecto configurado en modo oscuro/claro, el sitio web tiene la capacidad de identificar esto e igualarse con la configuración actual del sistema operativo.

**Issue:** 7
