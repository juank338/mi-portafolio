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

- [ ] Dado el pie de página, cuando realizo scroll hasta el final, entonces puedo visualizar el año actual y mis redes sociales.
- [ ] Dado el pie de página, cuando hago clic sobre las redes sociales, entonces seré redireccionado a la página correspondiente por medio de una URL.
- [ ] Dado el pie de página en dispositivos móviles, cuando lo visualizo, entonces los iconos y sus respectivos enlaces se acomodan de forma legible y cómoda.

**Issue:** #4

---

## HU-04 · Enlace al repositorio en cada proyecto ✅

**Historia:** Como reclutador, quiero que cada tarjeta de proyecto tenga un enlace a su repositorio en GitHub, para revisar el código que escribió el aprendiz.

**Etiquetas:** historia, frontend · **Estimación:** S

**Criterios de aceptación:**

- [ ] Dado un proyecto, cuando visualizo su ficha, entonces encuentro un enlace que me redirecciona al repositorio en GitHub.
- [ ] Dado un proyecto, cuando hago clic en el enlace del repositorio, entonces se abrirá una nueva pestaña en el navegador.
- [ ] Dado un proyecto, cuando realizo la redirección, entonces estoy informado de que voy a un enlace externo de GitHub.

**Issue:** #6

---

## HU-05 · Portafolio adaptable al celular

**Historia:** Como visitante que usa el celular, quiero que el portafolio se vea bien en pantallas pequeñas, para leerlo sin hacer zoom ni scroll horizontal.

**Etiquetas:** historia, frontend, prioridad-alta · **Estimación:** M

**Criterios de aceptación:**

- [ ] Dado el sitio web en celular, cuando lo navego, entonces visualizo todos los elementos sin desplazamientos horizontales.
- [ ] Dado el sitio web en versión mobile, cuando hago un tap sobre el botón de menú, entonces se despliegan las secciones de forma vertical.
- [ ] Dado el uso en celular, cuando interactúo con la página, entonces las acciones son fáciles de realizar con "swiping" y "tap".

**Issue:** #7

---

## HU-06 · (RETO) Adaptación al modo oscuro / claro

**Historia:** Como visitante del sitio web, quiero poder seleccionar un modo claro/oscuro según mi preferencia para evitar la fatiga visual lo más posible.

**Etiquetas:** historia, frontend · 
**Estimación:** M

**Criterios de aceptación:**

- [ ] Dado el sitio web, cuando hago clic o tap sobre el icono de sol/luna, entonces cambia el modo de visualización de forma dinámica.
- [ ] Dado que recargo la página, cuando vuelvo a ingresar, entonces recuerda la última configuración de modo claro/oscuro aplicada.
- [ ] Dado el sistema operativo, cuando está configurado en modo oscuro/claro, entonces el sitio web se iguala a dicha configuración.

**Issue:** #8
