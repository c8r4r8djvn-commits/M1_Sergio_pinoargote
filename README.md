# 🎨 Colorfly · Generador de paletas

Aplicación web para generar paletas de colores aleatorias de forma rápida.
Creada como MVP para **Colorfly Studio**, una agencia de branding que necesita
acelerar las propuestas visuales iniciales para sus clientes.

🔗 **Ver la app en vivo:** [pendiente, se publicará con GitHub Pages]



## ✨ Funcionalidades

- [ ] Botón "Generar paleta"
- [ ] Elegir el tamaño de la paleta: 6, 8 o 9 colores
- [ ] Elegir el formato del código: HEX o HSL
- [ ] Mostrar cada color con su código
- [ ] Aviso (toast) al generar una paleta


## 🛠️ Tecnologías

- **HTML5** semántico
- **CSS3** en una hoja de estilos externa
- **JavaScript** sin librerías
- **Git y GitHub** para el control de versiones
- **GitHub Pages** para publicarla



## ♿ Accesibilidad

- Cada selector tiene un `<label>` conectado (`for` / `id`).
- Etiquetas semánticas: `<header>`, `<main>`, `<section>` y `<footer>`.
- El aviso usa `aria-live="polite"` para que los lectores de pantalla lo lean.
- [pendiente: contraste del texto y foco visible]



## 📁 Estructura del proyecto

    M1_Sergio_pinoargote/
    ├── index.html     → estructura de la página
    ├── style.css      → diseño
    ├── script.js      → lógica e interactividad
    ├── README.md      → este archivo
    └── docs/
        └── prompts.md → registro de cómo usé la IA para aprender


## 🚀 Cómo usarla en tu computadora

1. Descarga o clona este repositorio.
2. Abre el archivo `index.html` en tu navegador.

No hace falta instalar nada.

### Extras
- [ ] Copiar el código al hacer clic en un color
- [ ] Bloquear colores
- [ ] Guardar paletas en el navegador (localStorage)


## 🤖 Uso de IA

Usé Claude como **tutor**: le pedí que me explicara cada paso con lenguaje
sencillo en vez de darme el código hecho. Escribí el código yo mismo y lo
comenté con mis palabras. El detalle de los prompts y de lo que aprendí está en
[docs/prompts.md](docs/prompts.md).



## 👤 Autor

**Sergio Pinoargote** · Desarrollador Frontend Junior · 2026