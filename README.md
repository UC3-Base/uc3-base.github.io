# 🚀 Web Oficial UC3-BASE

Plataforma web oficial de **UC3-BASE**, la asociación de estudiantes de ingeniería espacial, cohetería y radiofrecuencia de la Universidad Carlos III de Madrid (Campus de Leganés).

Este repositorio contiene el código fuente del sitio web, diseñado con una estética "Dark Future / Space Engineering" y optimizado para ser responsivo e interactivo.

---

## 🛠️ Últimas Actualizaciones (Changelog)

### 1. Nueva Página de Equipo ("Mission Control") 👨‍🚀
Hemos transformado la lista estática en un panel de mando interactivo dividido por especialidades:
* **División Lógica:** Separación en dos grandes bloques: **Modulación** (Software/SDR) y **Estación** (Hardware/Antenas).
* **Animaciones CSS:**
    * *Modulación:* Ecualizador de barras dinámico.
    * *Estación:* Radar de pulso expansivo.
* **Carrusel de Miembros:** Slider horizontal con flechas de navegación personalizadas (JavaScript + CSS Scroll Snap).
* **Tarjetas Interactivas:**
    * Efecto *Hover* que revela descripción técnica y stack tecnológico.
    * **Botón de Correo "Píldora":** Al hacer clic, se expande suavemente para mostrar la dirección de email.
* **Modo Ultra-Compacto (Móvil):** Rediseño total para pantallas pequeñas (tarjetas de 220px de altura) para evitar scroll excesivo.

### 2. Página de Proyectos Técnica 🛰️
Nuevo diseño orientado a la documentación técnica sin saturar visualmente:
* **Layout Bipartito:** Imagen destacada a la izquierda + Información técnica a la derecha.
* **Sistema de Acordeón:** Desplegables interactivos ("¿Qué buscamos?", "Especificaciones") para mantener la limpieza visual y revelar datos al hacer clic.
* **Status Tags:** Etiquetas visuales para el estado del proyecto ("En Construcción", "Fase de Diseño").

### 3. Footer Profesional & UX 👣
* **Logos Unificados:** Fusión visual del logo de la asociación y la UC3M con ajuste de márgenes negativos para cohesión de marca.
* **Contactos UI:** Los enlaces (Maps, Mail, LinkedIn) ya no parecen hipervínculos antiguos. Ahora son elementos de interfaz gris/blanco con iconos en burbujas.
* **Redes Sociales:** Botones con gradientes específicos (Instagram, GitHub, LinkedIn).

---

## 📂 Estructura del Proyecto

```text
/
├── index.html          # Portada (Hero, Resumen, CTA)
├── README.md           # Documentación del proyecto
├── css/
│   └── style.css       # Hoja de estilos global (Variables, Grid, Responsive)
├── js/
│   └── (Scripts inline en HTML por el momento)
├── img/
│   ├── LOGO_UC3M-BASE.png
│   ├── member_placeholder.webp  # Imagen genérica para miembros
│   ├── planeta.jpg              # Fondo de cabeceras
│   └── (Otras imágenes de proyectos)
└── pages/
    ├── equipo.html     # Panel de miembros (Sliders + Animaciones)
    ├── proyectos.html  # Fichas técnicas con acordeones
    └── contacto.html   # Formulario y vías de contacto