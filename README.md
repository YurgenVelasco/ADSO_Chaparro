# 💜 OmniSwipe | Interactive Swipe Experience

### Una experiencia interactiva de descubrimiento de perfiles

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Status](https://img.shields.io/badge/Status-Academic_Prototype-blue?style=for-the-badge)

## 📖 Descripción

**OmniSwipe** es un prototipo frontend interactivo inspirado en las aplicaciones de descubrimiento de perfiles mediante tarjetas deslizables.

El proyecto busca explorar el desarrollo de interfaces dinámicas utilizando HTML5, CSS3 y JavaScript puro, sin depender de frameworks.

Ofrece una experiencia visual enfocada en interacciones, animaciones, navegación entre vistas y presentación de perfiles.

## ✨ Características principales

- **Tarjetas interactivas:** exploración de perfiles mediante movimientos horizontales.
- **Gestos de deslizamiento:** aceptación o descarte de perfiles.
- **Sistema de acciones:** Like, Super Like, Boost y deshacer la última decisión.
- **Perfiles ampliables:** información adicional sobre intereses, ocupación y ubicación.
- **Galería de fotografías:** navegación entre imágenes de un perfil.
- **Navegación inferior:** acceso a diferentes secciones de la interfaz.
- **Exploración:** vista dedicada al descubrimiento de intereses.
- **Likes y matches:** visualización de información demostrativa.
- **Mensajes:** listado visual de conversaciones de ejemplo.
- **Perfil personal:** presentación de un perfil demostrativo.
- **Animaciones:** transformaciones, rotaciones y transiciones durante las interacciones.

> **Nota:** OmniSwipe es un prototipo frontend. Los perfiles, mensajes y conexiones son datos de demostración. No dispone de autenticación real, backend ni servicio de mensajería conectado.

---

## 🛠️ Tecnologías utilizadas

| Tecnología | Uso |
|---|---|
| HTML5 | Estructura de la aplicación |
| CSS3 | Estilos, efectos y animaciones |
| JavaScript ES6+ | Interactividad, eventos y lógica |
| DOM API | Renderización dinámica de componentes |
| Pointer Events | Interacciones de arrastre y deslizamiento |

No se utiliza React, Angular, Vue ni otro framework frontend.

## 📁 Estructura del proyecto

```text
ADSO_Chaparro/
│
├── index.html
│
├── css/
│   └── styles.css
│
├── js/
│   └── index.js
│
├── imgs/
│   └── ... recursos gráficos y fotografías
│
├── scripts/
│   ├── prepare-assets.mjs
│   └── Revision
│
└── README.md
```

**Archivos principales:**

- `index.html`: estructura principal y vistas de la aplicación.
- `css/styles.css`: diseño visual, componentes y animaciones.
- `js/index.js`: lógica de perfiles, gestos, navegación y acciones.
- `imgs/`: recursos visuales utilizados por la interfaz.
- `scripts/`: archivos auxiliares relacionados con la preparación de recursos.

## 🚀 Instalación y ejecución

### 1. Clonar el repositorio

```bash
git clone https://github.com/YurgenVelasco/ADSO_Chaparro.git
```

### 2. Acceder al proyecto

```bash
cd ADSO_Chaparro
```

### 3. Ejecutar la aplicación

Abra `index.html` utilizando un navegador moderno.

También puede ejecutar el proyecto mediante la extensión **Live Server** de Visual Studio Code para disponer de un entorno local de desarrollo.

No requiere instalar dependencias para utilizar la interfaz principal.

---

## 🎮 Funcionamiento

### Descubrimiento de perfiles

La aplicación presenta tarjetas con información de diferentes perfiles.

Cada tarjeta puede mostrar:

- Nombre y edad.
- Fotografías.
- Descripción personal.
- Ubicación.
- Ocupación y estudios.
- Intereses.

### Interacciones

El usuario puede interactuar mediante botones o gestos:

| Acción | Comportamiento |
|---|---|
| Deslizar a la derecha | Aceptar el perfil |
| Deslizar a la izquierda | Descartar el perfil |
| Like | Ejecutar la acción de aceptación |
| Super Like | Ejecutar una aceptación visual |
| Boost | Ejecutar una aceptación visual |
| Deshacer | Recuperar la última tarjeta procesada |
| Expandir perfil | Visualizar información adicional |

En la implementación actual, Like, Super Like y Boost comparten la misma acción básica de aceptación; no cuentan con sistemas independientes de prioridad o visibilidad.

### Navegación

La interfaz incluye las siguientes vistas:

- Descubrimiento.
- Explorar.
- Likes recibidos.
- Matches y mensajes.
- Perfil personal.

Algunas secciones presentan información estática de demostración y no están conectadas a servicios externos.

---

## 🧠 Conceptos técnicos aplicados

Este proyecto permite practicar diferentes conceptos de programación frontend:

**Manipulación del DOM:** generación dinámica de tarjetas y actualización de vistas.

**Manejo de eventos:** utilización de eventos de puntero, clics y acciones del usuario.

**Gestión de estado:** administración de una cola de perfiles y un historial de decisiones en memoria.

**Animaciones CSS:** aplicación de transformaciones, rotaciones y transiciones visuales.

**Programación modular:** organización de funcionalidades dentro del archivo JavaScript principal.

**Diseño de interfaces:** creación de componentes visuales inspirados en aplicaciones móviles.

---

## ⚠️ Limitaciones actuales

El proyecto está orientado a la demostración de una interfaz y presenta las siguientes limitaciones:

- No existe un backend conectado.
- Los perfiles son ficticios y están definidos en el código.
- Los matches y mensajes son datos de demostración.
- No existe un sistema real de registro o autenticación.
- Las decisiones se mantienen en memoria durante la sesión de la página.
- Las funciones Super Like y Boost no tienen lógica diferenciada de un Like convencional.
- La información del perfil personal es demostrativa.

El proyecto no debe considerarse una plataforma de citas lista para producción.

---

## 🗺️ Posibles mejoras

- [ ] Implementar persistencia mediante almacenamiento local o una API.
- [ ] Crear un sistema de autenticación seguro.
- [ ] Permitir crear y editar perfiles reales.
- [ ] Desarrollar un algoritmo de coincidencias basado en intereses.
- [ ] Diferenciar la lógica de Like, Super Like y Boost.
- [ ] Implementar un sistema de mensajería funcional.
- [ ] Mejorar la accesibilidad y navegación por teclado.
- [ ] Incorporar pruebas automatizadas.
- [ ] Publicar una demostración en GitHub Pages.
- [ ] Mejorar la documentación visual con capturas de pantalla.

---

## 👨‍💻 Autor

**Yurgen Andrey Velasco Rojas**

Aprendiz de Análisis y Desarrollo de Software (ADSO) del SENA.

Desarrollador en formación, interesado en ingeniería de software, backend, bases de datos y creación de aplicaciones web.

**GitHub:** [@YurgenVelasco](https://github.com/YurgenVelasco)

---

## 📄 Licencia

Este repositorio no tiene una licencia de software registrada actualmente.

Los permisos de reutilización y distribución dependerán de la licencia que se incorpore posteriormente.

---

## ⭐ Sobre el proyecto

OmniSwipe representa un ejercicio práctico de desarrollo de interfaces dinámicas y experiencias interactivas mediante tecnologías web fundamentales.

Su propósito es fortalecer habilidades de programación, diseño de componentes y manejo de interacciones en el navegador.

**Desarrollado con dedicación, creatividad y JavaScript.**
