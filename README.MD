# 🎨 Geoportal UI Kit - Sistema de Diseño

> Implementación de componentes de interfaz (UI) para el Sistema Nacional Espacial, trasladando el diseño desde Figma a código limpio y responsivo.

## 🚀 Demo en Vivo
¡Puedes ver el proyecto funcionando aquí! 👇
**[Ver Geoportal UI Kit](https://gromand3v.github.io/UI-KIT-GEOPORTAL/)**

---

## 📄 Descripción
Este repositorio contiene la documentación y desarrollo de los componentes visuales base para el Geoportal. El objetivo fue crear una librería de componentes reutilizables, asegurando la consistencia visual y la adaptabilidad a dispositivos móviles.

**Puntos clave:**
- **Diseño a Código:** Fidelidad visual basada en prototipos de alta calidad.
- **Arquitectura CSS:** Uso de metodologías modernas para distribución y espaciado.
- **Responsive Design:** Adaptable a Desktop, Tablet y Móvil.

## 🧩 Componentes Desarrollados
El UI Kit incluye los siguientes módulos:

1.  **Barra de Navegación (Navbar):**
    - Distribución con Flexbox (Logo, Enlaces, Utilidades).
    - Integración de iconografía SVG (Carrito de compra y Badges).
2.  **Cards Verticales (Noticias/Alertas):**
    - Diseño de tarjetas con imagen destacada y call-to-action.
    - Efectos de *Hover* y transiciones suaves.
3.  **Cards Horizontales (Aplicaciones):**
    - Layout flexible para destacar herramientas específicas (DRP Hurricane).
4.  **Grilla de Íconos (Servicios):**
    - Uso de **CSS Grid** (`minmax`, `auto-fit`) para una grilla totalmente fluida y responsiva.

## 🛠️ Tecnologías Utilizadas
- **HTML5:** Semántico (`<nav>`, `<article>`, `<main>`, `<section>`).
- **CSS3:**
    - **Flexbox:** Para alineaciones unidimensionales (Navbar, Cards).
    - **CSS Grid:** Para estructuras bidimensionales (Grilla de íconos).
    - **Media Queries:** Para la adaptación móvil.
- **Git & GitHub Pages:** Para control de versiones y despliegue continuo.

## 📂 Estructura del Proyecto

```text
.
├── index.html          # Documentación y vista previa de componentes
├── styles.css          # Hoja de estilos global y responsiva
├── img-alerta.png      # Assets de imágenes
├── sne.png             # Logo corporativo
└── icons/              # Imagotipos del sistema (PNG/SVG)
    ├── geoportal.png
    ├── geoprocesos.png
    └── ...