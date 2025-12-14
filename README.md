# 🐦 Twimba: Clon Funcional de Twitter en JavaScript

## 🚀 Simulación de Red Social y DOM Dinámico

### 📝 Descripción del Proyecto

**Twimba** es una aplicación web funcional que simula una plataforma de microblogging similar a Twitter. Fue construida exclusivamente con **JavaScript Vanilla, HTML y CSS**.

Este proyecto sirvió como una demostración completa de habilidades en el **desarrollo frontend dinámico**, enfocándose en la **manipulación del Modelo de Objetos del Documento (DOM)** y la gestión de la lógica de la aplicación completamente separada de la estructura HTML.

---

## 🌟 Funcionalidades Clave y Habilidades Técnicas

| Característica | Detalle Técnico / Implementación | Archivos Clave |
| :--- | :--- | :--- |
| **Lógica Central** | Gestión completa de la data (interacciones, posts) y renderizado de la interfaz mediante **JavaScript Vanilla**. | `index.js`, `data.js` |
| **Interactividad** | Implementación de las funcionalidades **Like** (Incremento/Decremento), **Retweet**, y **Reply** con manejo de eventos delegado. | `index.js` |
| **Delegación de Eventos** | Uso de `data-attributes` para identificar la acción (`data-like`, `data-retweet`) y el ID del post (`data-tweet`) con un único *event listener*. | `index.js` |
| **Generación de Contenido** | Renderizado dinámico de la *feed* completa a partir de un Array de objetos (`data.js`) y su actualización inmediata tras las interacciones. | `index.js`, `data.js` |
| **Borrado Condicional** | Lógica implementada para mostrar el icono de borrado funcional (`data-delete`) solo en los posts del usuario `@Scrimba`. | `index.js` |
| **Validación de Posts** | Implementación de límite de **180 caracteres** y **contador visual** para mejorar la experiencia de usuario (UX). | `index.js` |

---

## 💻 Stack Tecnológico

* **Lógica Principal:** JavaScript (Vanilla)
* **Estructura:** HTML5
* **Estilos:** CSS3
* **Desarrollo/Servidor:** Vite
* **Gestor de Paquetes:** npm

---

## 🚀 Cómo Empezar (Guía de Ejecución Local)

Para visualizar y ejecutar el proyecto en tu máquina local:

### Instalación y Ejecución

Asegúrate de tener [Node.js](https://nodejs.org/) instalado y sigue los siguientes comandos en tu terminal:

```bash
# 1. Instala las dependencias (Vite)
npm install

# 2. Inicia el proyecto en modo de desarrollo
npm start
# o npm run dev
```
### 👨‍💻 Nota del Desarrollador

Este proyecto fue un ejercicio crucial para solidificar la separación entre la **Vista** (HTML/CSS) y el **Modelo/Controlador** (JavaScript). El manejo de eventos centralizado mediante **data-attributes** y la **delegación de eventos** (`e.target.dataset.`) es la clave de la aplicación. Esto minimiza la necesidad de añadir *listeners* a cada elemento individual y demuestra un entendimiento sólido de cómo construir interfaces complejas y eficientes con JavaScript puro.
