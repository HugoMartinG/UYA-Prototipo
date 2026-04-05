# Prototipo Frontend · Tenerife Taxi Transfers

## Descripción del proyecto

Este proyecto es un **prototipo frontend** para una **aplicación web** de reserva de **traslados en taxi** desde los **aeropuertos de Tenerife** hacia cualquier destino de la isla.
El **objetivo** es mostrar la **estructura**, **navegación** y **diseño** de la **interfaz**, cumpliendo los **requisitos** de **accesibilidad WCAG 2.1 AA**.

El prototipo incluye cuatro interfaces obligatorias:

* **Landing Page** (Inicio)

* **Formulario de Solicitud de Reserva**

* **Gestión de Reservas Existentes** (código + email)

* **Formulario de Contacto**


## Tecnologías utilizadas

* **Astro** (framework principal)

* **TailwindCSS**

* **Componentes propios en Astro**

* **HTML accesible**

* **CSS global**

## Estructura del proyecto

```
src/
├── assets/              // Recursos gráficos
├── components/          // Componentes reutilizables (Hero, Formularios, Navbar…)
├── images/              // Imágenes del prototipo
├── layouts/             // Layout global
├── pages/               // Páginas principales del prototipo
│   ├── index.astro      // Landing page
│   ├── booking.astro    // Formulario de reserva
│   ├── manage.astro     // Gestión de reservas
│   └── contact.astro    // Formulario de contacto
└── styles/              // Estilos globales
```
## Cómo ejecutar el proyecto

1. **Instalar dependencias:**

   ```
   npm install
   ```
2. **Iniciar el servidor de desarrollo:**

    ```
   npm run dev
   ```
3. **Abrir en el navegador:**

   ```
   http://localhost:***
   ```
## Accesibilidad (WCAG 2.1 AA)

El prototipo incorpora varias **técnicas de accesibilidad**:

* **Skip link** para saltar al contenido principal.

* Un **h1** por página para jerarquía correcta.

* **Formularios accesibles** con:

   * **label** asociado a cada control

   * **name**, **autocomplete**, **aria-describedby**

   * estructura preparada para **aria-invalid** y **mensajes de error**

* Foco visible mediante **.focus-ring**

* Imágenes decorativas con **alt=""**

* **Componentes semánticos** (header, main, footer)

* **Contraste** adecuado en botones y textos principales

Estas técnicas se describen en detalle en el informe de accesibilidad adjunto.

## Autores

Proyecto desarrollado por **Iker Martín Gámez**, **Hugo Martín Gámez** y **Samuel Megolla Expósito**.

Asignatura: **Usabilidad y Accesibilidad Web** (UYA)  
**Universidad de La Laguna**
