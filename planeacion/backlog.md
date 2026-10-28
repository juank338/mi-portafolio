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

- [ ] Dado que realizo scroll hasta el pie de página, puedo visualizar el año actual y mis redes sociales.
- [ ] Dado que me encuentro sobre el pie de página al hacer clic sobre las redes sociales, seré redireccionado a la página correspondiente por medio de una URL.
- [ ] Dado que estoy visualizando el pie de página desde mi dispositivo móvil, los iconos de las redes sociales y sus respectivos enlaces se acomodarán de forma legible y cómoda para la apropiada navegación.

**Issue:** #4

---

## HU-04 · Enlace al repositorio en cada proyecto ✅

**Historia:** Como reclutador, quiero que cada tarjeta de proyecto tenga un enlace a su repositorio en GitHub, para revisar el código que escribió el aprendiz.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado que estoy visualizando la ficha de un proyecto que es de mi interés, cuando reviso su contenido puedo encontrar un enlace que me redirecciona al repositorio en GitHub de dicho proyecto.
- [ ] Dado que estoy visualizando la ficha del proyecto, al hacer clic en el enlace del repositorio se abrirá una nueva pestaña en el navegador.
- [ ] Cuando realizo la redirección al repositorio del proyecto, debo estar claramente informado de que se me está redirigiendo a un enlace externo de GitHub.

**Issue:** #6

---

## HU-05 · Portafolio adaptable al celular

**Historia:** Como visitante que usa el celular, quiero que el portafolio se vea bien en pantallas pequeñas, para leerlo sin hacer zoom ni scroll horizontal.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** M

**Criterios de aceptación:**

- [ ] Dado que estoy navegando desde mi celular, debo visualizar todos los elementos del sitio web sin realizar desplazamientos horizontales pese a la diferencia en la relación de aspecto entre las versiones desktop y mobile.
- [ ] Dado que me encuentro navegando en la versión mobile de la aplicación, al hacer un tap sobre el botón de menú se deben desplegar las secciones de forma vertical.
- [ ] Dado que me encuentro usando un celular, todas las interacciones entre la página y el usuario deben ser fáciles de realizar únicamente con "swiping" y "tap".

**Issue:** #7

---

## HU-06 · (RETO) Adaptación al modo oscuro / claro

**Historia:** Como visitante del sitio web, quiero poder seleccionar un modo claro/oscuro según mi preferencia para evitar la fatiga visual lo más posible.

**Etiquetas:** historia, frontend · 
**Estimación:** M

**Criterios de aceptación:**

- [ ] Dado que estoy visualizando cualquier sección del sitio web, debo poder cambiar el modo de visualización de forma dinámica haciendo clic o tap sobre el icono de sol/luna.
- [ ] Dado que recargo o vuelvo a ingresar a la página, esta tendrá la función de recordar cuál fue la última configuración de modo claro/oscuro que he aplicado.
- [ ] Dado que mi sistema operativo está por defecto configurado en modo oscuro/claro, el sitio web tiene la capacidad de identificar esto e igualarse con la configuración actual del sistema.

**Issue:** #8
