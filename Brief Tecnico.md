# Brief Técnico Definitivo - Netprotech S.A.S.
**Versión:** 3.0 (Integración de catálogo histórico, RUT y Tema Claro)
**Descripción:** Documento maestro de arquitectura, contenido, diseño y requerimientos legales para el desarrollo del sitio web corporativo.

---

## 1. Contexto Legal y Comercial
La página web representa a una entidad comercial constituida, por lo que debe cumplir con normativas de transparencia comercial para operaciones B2B.

* **Razón Social:** NETPROTECH SAS
* **NIT:** 901967653-8
* **Representación Legal:** * Principal: Jose David Rodriguez Lugo
  * Suplente: Diego Alejandro Rodriguez Gutierrez
* **Ubicación de Operaciones:** CL 152 NO. 56-72 TO 10 AP 303, Bogotá D.C., Colombia
* **Contacto Oficial:** netprotechsas@gmail.com | Tel: 3108679120
* **Horario de Atención:** Lunes a Viernes de 9:00 AM a 6:00 PM.
* **Actividades Económicas (CIIU):** 6209 (Soporte TI, Redes, CCTV) y 6201 (Desarrollo Web/Software).

---

## 2. Objetivo del Proyecto y Propuesta de Valor
Desarrollar una *landing page* multicapa orientada a la generación de *leads*. El sitio debe proyectar alto rendimiento, transparencia y estabilidad corporativa bajo la premisa principal: **"Conectamos y protegemos tu negocio con soluciones integrales"**. El diseño debe permitir a la empresa licitar con clientes B2B (infraestructura) y captar clientes B2C/Comerciales (seguridad).

---

## 3. Arquitectura de la Información y Catálogo de Servicios
El sitio consta de 5 rutas principales. Los servicios se han categorizado para mejorar la navegación y el SEO local en Bogotá:

1. **`/` (Inicio):** * **Hero Section:** Titular enfocado en soluciones integrales y seguridad.
   * **Por qué elegirnos:** Destacando 4 pilares (Experiencia y Profesionalismo, Soluciones a Medida, Soporte Confiable, Cobertura Integral).
2. **`/infraestructura-ti` (Pilar 1 - Redes y Energía):**
   * Redes informáticas y servidores.
   * Cableado estructurado (Voz, datos y video).
   * Alambrado eléctrico normativo.
3. **`/seguridad-electronica` (Pilar 2 - Protección):**
   * Sistemas de videovigilancia (CCTV) de alta definición.
   * Control de acceso peatonal y vehicular.
4. **`/soporte-y-desarrollo` (Pilar 3 - Software y Mantenimiento):**
   * Soporte IT (remoto y presencial) y mantenimiento.
   * Desarrollo Web moderno y funcional.
   * Consultoría y soluciones en la nube.
5. **`/contacto`:** * Formulario de captura (Nombre, Correo, Teléfono opcional, Mensaje).
   * Información de contacto, ubicación y horarios.

---

## 4. Guía de Estilo y UI/UX (Design System)
El diseño sigue una estética "Corporativa/Limpia" utilizando un tema claro (*Light Mode*) que prioriza la legibilidad, la confianza institucional y el minimalismo moderno.

### Tipografía
* **Primaria:** Sans-serif geométrica moderna (Ej. *Inter*, *Roboto* o *Plus Jakarta Sans*).

### Paleta de Colores
* **Colores de Marca (Intactos desde el logo):**
  * `Primary (Azul Netprotech)`: `#08559B` (Botones principales, acentos de marca, iconos destacados).
  * `Secondary (Gris Protech)`: `#545454` (Subtítulos, bordes fuertes).
* **Colores de Interfaz (Modo Claro):**
  * `Background`: `#F8FAFC` (Un gris-azulado levísimo, casi blanco. Da un aspecto muy moderno y no cansa la vista).
  * `Surface`: `#FFFFFF` (Blanco puro para las tarjetas de servicios y contenedores, acompañados de una sombra sutil `box-shadow` para crear elevación).
  * `Dark Text`: `#0F172A` (Azul medianoche casi negro para Títulos H1, H2, H3. Contraste perfecto).
  * `Muted Text`: `#475569` (Gris medio para Párrafos y descripciones, manteniendo buena accesibilidad).
  * `Accent/Hover`: `#064075` (Una versión más oscura del Azul Netprotech para interacciones al pasar el mouse).

---

## 5. Requerimientos Técnicos
* **Performance:** Core Web Vitals optimizados.
* **SEO Local:** Meta etiquetas y estructuración orientada a Bogotá.
* **Integraciones:** Botón flotante de WhatsApp.
* **Compliance Legal:** El *Footer* debe actualizarse al año 2026 y contener obligatoriamente: NETPROTECH SAS, NIT 901967653-8, y la dirección física.