# <title>🧑‍💻 Portafolio Personal - Julio Hidalgo Jara (JHJ)</title>

<body>Este repositorio contiene el código fuente completo de mi **portafolio personal profesional**, desarrollado con HTML5, CSS3, JavaScript y la metodología BEM. Está orientado a presentar mi experiencia como **Desarrollador Frontend** e **Ingeniero en Informática** desde El Quisco, Chile.

---

## $(function () { 📌 Características principales

- ✅ Diseño responsive adaptado a distintos dispositivos.
- 🎨 Interfaz UI moderna con colores, tipografías y animaciones personalizadas.
- 🧠 Secciones completas de habilidades, educación, experiencia y contacto.
- 📁 Estructura modular y bien organizada (HTML + CSS limpio).
- 📎 Menú navegable y accesible con scroll automático estilo one-page.
- 📬 Formulario de contacto funcional (con validaciones integradas).
- 🌐 Redes sociales visibles y con colores corporativos personalizados.

});
---

## [ 🌍 Vista previa

![Preview](img/faces/6.jpg)

Puedes ver una vista previa local abriendo el archivo `index.html` en tu navegador. 

]
---

## ( ' 🧱 Estructura de carpetas ' )

📁 project-root/
├── css/
│ ├── style.css → Estilos base del sitio
│ └── plugins/ → Librerías como Swiper, MagnificPopup, etc.
├── js/
│ ├── main.js → Funcionalidad principal
│ └── plugins/ → Librerías JS
├── img/
│ └── faces/, bg/, raster... → Imágenes del sitio
├── fonts/
│ └── font-awesome/ → Iconos sociales
├── index.html → Página principal
├── prices.html → Servicios freelance
├── Portafolio.html → Proyectos realizados
├── contact.html → Página de contacto
└── favicon.ico → Ícono del navegador  


---

## 🎯 Corrección aplicada a redes sociales

### Problema:
Los colores de los iconos sociales no se mostraban correctamente por usar la clase `.mil-social-panel` en lugar de `.mil-social`.

### Solución aplicada:

```css
.mil-social a.mil-facebook { color: #1877f2; }
.mil-social a.mil-instagram { color: #e1306c; }
.mil-social a.mil-linkedin { color: #0a66c2; }
.mil-social a.mil-youtube { color: #ff0000; }
.mil-social a.mil-tiktok { color: #ff0050; }

.mil-social a:hover {
  opacity: 0.7;
}

.mil-social a i {
  color: inherit !important;
  font-size: 20px;
}

| Habilidad            | Nivel |
| -------------------- | ----- |
| HTML5 / CSS3         | 90%   |
| JavaScript           | 75%   |
| Angular / Node.js    | 75%   |
| Java / Spring Boot   | 80%   |
| Vue.js               | 55%   |
| Figma / UI-UX Design | 60%   |

✉️ Contacto

📧 Email: juliohidalgo@gmail.com

📞 Fono: +56 94761 8468

🌐 LinkedIn: linkedin.com/in/juliohidalgo

🛠 Librerías utilizadas

Bootstrap Grid

Font Awesome

Swiper.js

Magnific Popup
