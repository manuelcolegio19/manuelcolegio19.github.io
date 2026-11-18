<div align="center">

# 💃 Escuela y Compañía de Flamenco Tatiana Garrido

**Portal web moderno, editorial y responsivo para la Escuela y Compañía de Flamenco Tatiana Garrido en Granada.**

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/es/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)](https://developer.mozilla.org/es/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/es/docs/Web/JavaScript)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-success?style=for-the-badge)](#)
[![Location](https://img.shields.io/badge/Granada-Espa%C3%B1a-C89B3C?style=for-the-badge)](#)

[Ver Demo en Vivo](#despliegue-en-github-pages) • [Características](#-características-principales) • [Arquitectura](#-estructura-del-proyecto) • [Personalización](#-personalización)

</div>

---

## 📖 Sobre el Proyecto

La web oficial original (`tatianagarrido.com`) cuenta con una estructura de blog clásica donde la información sobre la trayectoria de la artista, sus espectáculos internacionales y la oferta formativa de su academia en Granada aparece fragmentada.

Este repositorio contiene el rediseño completo en una **arquitectura Single-File de alto rendimiento (`index.html`)**, pensada para ofrecer una experiencia de usuario fluida, elegante y enfocada tanto a **alumnos locales e internacionales** como a **promotores culturales y teatros**.

### 🔄 Mejoras frente a la versión original

| Aspecto | Web Original (`tatianagarrido.com`) | Nueva Propuesta (`index.html`) |
| :--- | :--- | :--- |
| **Estructura** | Entradas tipo blog dispersas | *Landing page* integral dividida en 5 bloques estratégicos |
| **Diseño Visual** | Estilo web antiguo, poco contraste | Estética editorial andaluza (Negro Azabache, Carmesí y Oro Viejo) |
| **Adaptabilidad** | No optimizada para móviles actuales | **100% Responsive** (Mobile-First con CSS Grid & Flexbox) |
| **Escuela de Baile** | Texto plano sin categorización | Catálogo interactivo con **filtros dinámicos** por nivel y especialidad |
| **Compañía** | Listado estático de obras | **Selector por pestañas** con fichas técnicas, premios y elenco |
| **Conversión** | Datos de contacto poco visibles | Tarjeta de acceso rápido, mapa integrado y formulario inteligente |

---

## ✨ Características Principales

- **🎭 Identidad y Legado:** Sección biográfica dedicada a **Tatiana Garrido Guardia (*«La Españoleta»*)**, heredera artística de la maestra *«Mariquilla»* y docente vinculada a la Cátedra de Flamencología de la Universidad de Granada.
- **🩰 Escuela de Baile con Filtro JS:** Clasificación dinámica de cursos (*Iniciación*, *Intermedio*, *Avanzado/Tablao*, *Bata de cola y Mantón*, *Infantil/Juvenil* e *Intensivos Internacionales*).
- **🎟️ Repertorio de la Compañía:** Fichas interactivas de sus producciones más destacadas:
  - *Fuego y Arena* (Premio Mejor Espectáculo Flamenco en Antalya, Turquía).
  - *Sueños del Flamenco*.
  - *Flamenco Equestrian* (Fusión con Alta Escuela Ecuestre).
  - *Flamenco Íntimo*.
- **📍 Sede y Contacto Directo:** Integración de mapa interactivo en **C/ Santa Clotilde 14 Bajo (Granada)**, enlaces directos de llamada/email y formulario diferenciado para matrícula o contratación artística (*Neptuno Show Management S.L.*).
- **⚡ Rendimiento Extremo:** Cero *frameworks* pesados, cero tiempos de compilación y carga instantánea.

---

## 🎨 Sistema de Diseño

La identidad visual combina la fuerza escénica del tablao flamenco con la sobriedad de una revista cultural:

| Color | Muestra | Hex | Uso principal |
| :--- | :---: | :--- | :--- |
| **Negro Azabache** | ![#0D0B0C](https://via.placeholder.com/16/0D0B0C/0D0B0C.png) | `#0D0B0C` | Fondos principales y atmósfera escénica |
| **Carmesí Flamenco** | ![#A31D24](https://via.placeholder.com/16/A31D24/A31D24.png) | `#A31D24` | Llamadas a la acción (CTA), acentos y badges |
| **Oro Viejo** | ![#C89B3C](https://via.placeholder.com/16/C89B3C/C89B3C.png) | `#C89B3C` | Detalles tipográficos, bordes y estadísticas |
| **Marfil Cálido** | ![#F8F4EE](https://via.placeholder.com/16/F8F4EE/F8F4EE.png) | `#F8F4EE` | Secciones editoriales de lectura (Legado y Compañía) |

- **Tipografía:** `Cormorant Garamond` para titulares con carácter clásico y `Plus Jakarta Sans` para máxima legibilidad en interfaz y párrafos.

---

## 📂 Estructura del Proyecto

```text
tatiana-garrido-flamenco/
├── index.html          # Documento completo (HTML5 semántico + CSS3 Variables + Vanilla JS)
└── README.md           # Documentación del repositorio
```

---

## 🚀 Despliegue en GitHub Pages

Puedes publicar esta web gratuitamente en menos de 1 minuto usando **GitHub Pages**:

1. Sube `index.html` y `README.md` a la rama `main` de tu repositorio.
2. Ve a **Settings** (Configuración) > **Pages** en tu repositorio de GitHub.
3. En **Source**, selecciona `Deploy from a branch`.
4. Elige la rama `main` y la carpeta `/ (root)` y haz clic en **Save**.
5. Tu web estará disponible en `https://<tu-usuario>.github.io/<nombre-del-repo>/`.

---

## 🛠️ Personalización

- **Fotografías Oficiales:** Las imágenes actuales funcionan como *placeholders* de alta resolución. Para usar las fotografías oficiales de la compañía (Paco Sánchez, Miguel Ángel Molina, Arabesco), crea una carpeta `/assets/img/` y reemplaza las URLs de las etiquetas `<img>` y el `background` de `.hero` en `index.html`.
- **Envío real del formulario:** Actualmente el formulario valida los datos y muestra confirmación visual mediante JavaScript. Para recibir los correos directamente en `info@tatianagarrido.com` sin servidor propio, puedes conectar el atributo `action` del `<form>` con servicios gratuitos como [Formspree](https://formspree.io/) o [Web3Forms](https://web3forms.com/).

---

<div align="center">
  <sub>Desarrollado para la difusión cultural de la <strong>Escuela y Compañía de Flamenco Tatiana Garrido</strong> • Granada, España.</sub>
</div>