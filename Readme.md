# Guía Actividad #1

---

# 🚀 PROYECTO MOBIXA

> **Sistema Web para la Visualización y Gestión de Diseños y Muebles**
Fecha de entrega: 22 de enero 2026
> 

---

## 1. FICHA DEL EQUIPO

Esta sección formaliza la constitución del grupo de trabajo.

| Nombre del Estudiante | Rol Principal (Frontend/Backend/Lead/Fullstack/Acelerador/QA) | GitHub/GitLab User |
| --- | --- | --- |
| Adriana Orbe | QA / Documentación | @acostaadry66 |
| Heiler | Diseño UI/UX y Frontend | @usuario |
| Wander Vasquez | Lead / Fullstack (Backend + Frontend + BD) | @usuario |

---

## 2. Definición del Negocio

### 🏢 La Empresa (Cliente)

- **Nombre: MOBIXA**
- **Tipo:** Empresa ficticia creada con fines académicos
- **Sector:** Comercio minorista - Mueblería y diseño de interiores

**Descripción de la empresa:**

MOBIXA es una mueblería dedicada a la venta de muebles y accesorios para el hogar y la oficina, con una oferta variada que incluye salas, comedores, recámaras, mobiliario de oficina y artículos decorativos. Se distingue por la calidad de sus productos, diseños modernos y funcionales, y una atención personalizada orientada a las necesidades y gustos de cada cliente. No obstante, la empresa carece de presencia digital, lo que limita su alcance comercial. MOBIXA es una empresa ficticia creada con fines académicos, pero refleja el funcionamiento real de una mueblería.

### ⚠️ El Problema

MOBIXA presenta una baja competitividad debido a la ausencia de presencia digital, lo que impide mostrar su catálogo completo y limita el alcance a nuevos clientes. Esta situación obliga a los consumidores a realizar visitas físicas innecesarias solo para obtener información básica, genera una comunicación desorganizada y restringe las oportunidades de venta al horario comercial. Además, la falta de una plataforma en línea coloca a la empresa en desventaja frente a la competencia, que ya capta clientes a través de medios digitales, mientras MOBIXA pierde visibilidad y eficiencia comercial.

### 💡 La Solución Propuesta

Se propone desarrollar un sistema web moderno y funcional que permita a MOBIXA exhibir su catálogo de forma digital, disponible 24/7 y accesible desde cualquier dispositivo. La plataforma contará con una página de inicio atractiva, un catálogo organizado por categorías, búsqueda en tiempo real y vistas detalladas de cada producto con imágenes y especificaciones completas.

Además, incluirá un carrito para guardar productos de interés y una integración directa con WhatsApp Business para facilitar la comunicación inmediata con los clientes, sin requerir registro de usuarios. El sistema será responsive y dispondrá de un panel de administración sencillo para que el personal de MOBIXA gestione el catálogo de manera eficiente, mejorando así su visibilidad, comunicación y competitividad en el mercado.

---

## 3. Alcance del Proyecto (Scope)

*Debido a que solo tenemos 11 semanas, debemos definir claramente qué SÍ haremos y qué NO haremos.*

### ✅ Dentro del Alcance (MVP)

*Funcionalidades críticas que estarán listas para la presentación final.*

1. Página de inicio con carrusel de productos destacados.

2. Catálogo completo organizado por categorías.

3. Búsqueda y filtrado de productos en tiempo real.

4. Vista detallada de cada producto con imágenes y especificaciones.

5. Carrito para guardar productos de interés.

6. Integración directa con WhatsApp Business para consultas.

7. Diseño responsive adaptable a todos los dispositivos.

8. Panel de administración básico para gestión de productos.

9. Sistema de categorización con navegación intuitiva.

10. Base de datos para la gestión completa del catálogo.

### 🚫 Fuera del Alcance

*Cosas que NO se desarrollarán en este curso por tiempo* 

1. Pagos en línea o pasarela de cobro.
2. Gestión de envíos, logística y rastreo de pedidos.
3. Aplicaciones móviles nativas (iOS/Android).
4. Control de inventario en tiempo real.
5. Facturación electrónica.
6. Reseñas, calificaciones o comentarios de usuarios.
7. Chat en vivo dentro del sitio web.
8. Sistema de ofertas, descuentos o cupones.
9. Integración avanzada con redes sociales.
10. Sistema CRM para gestión de clientes.
11. Marketing digital, SEO avanzado y analítica compleja.
12. Registro o gestión de usuarios.

---

## 4. Stack Tecnológico

*Herramientas seleccionadas por el equipo.*

- **Lenguaje(s) de Programación:**
- **Framework Frontend:** React y Javascrip
- **Framework Backend:**  node.js
- **Base de Datos:** MySQL
- **Herramientas Extra:** Ninguna por el momento

---

## 5. Requerimientos

### ⚙️ Requerimientos Funcionales (RF)

*Lo que el sistema debe HACER.*

| ID | Título | Descripción Breve | Prioridad (Alta/Media) |
| --- | --- | --- | --- |
| RF-01 | Carrusel destacados | Mostrar productos destacados en página principal con navegación automática | Alta |
| RF-02 | Catálogo por categorías | Organizar productos en: salas, comedores, recámaras, oficina, decoración | Alta |
| RF-03 | Búsqueda en tiempo real | Filtrar productos mientras el usuario escribe | Alta |
| RF-04 | Vista detallada | Mostrar galería, descripción, dimensiones, materiales y colores | Alta |
| RF-05 | Carrito temporal | Guardar productos de interés para consulta posterior | Media |
| RF-06 | Integración WhatsApp | Botón que abre WhatsApp con mensaje pregenerado del producto | Alta |
| RF-07 | Diseño responsive | Adaptación a móviles , tablets  y desktop | Alta |
| RF-08 | Panel administrativo | CRUD completo de productos y categorías | Alta |
| RF-09 | Gestión de imágenes | Cargar múltiples imágenes por producto | Media |
| RF-10 | Filtrado por categoría | Seleccionar categoría específica del menú | Alta |
| RF-11 | Navegación libre | Acceso total sin registro ni login | Alta |

### 🛡️ Requerimientos No Funcionales (RNF)

**Seguridad:**

- Contraseñas encriptadas con bcrypt
- Protección contra SQL Injection con consultas preparadas
- Validación en frontend (React) y backend (Node.js)
- Protección CSRF y XSS
- Variables de entorno para datos sensibles

**Rendimiento:**

- Búsqueda en tiempo real < 1 segundo
- Soportar mínimo 200 productos
- Lazy loading de imágenes
- Consultas SQL optimizadas con índices

**Usabilidad:**

- Máximo 3 clics para llegar a cualquier producto
- Mensajes de error claros
- Confirmaciones visuales de acciones

**Disponibilidad:**

- Uptime mínimo 95%
- Compatible con Chrome, Firefox, Edge, Safari (últimas 2 versiones)

**Mantenibilidad:**

- Código limpio siguiendo convenciones JavaScript
- Arquitectura MVC
- Componentes reutilizables en React
- Documentación completa con JSDoc

---