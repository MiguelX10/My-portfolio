# Miguel Cabral - Portfolio

Un portafolio personal interactivo, moderno y responsivo para mostrar mis habilidades, proyectos y experiencia como Full Stack Developer.

## Características

- Diseño moderno con efectos visuales como partículas interactivas de fondo.
- Totalmente responsivo para dispositivos móviles, tablets y escritorio.
- Animaciones fluidas al hacer scroll para una mejor experiencia de usuario.
- Secciones estructuradas: Inicio, Sobre Mí, Habilidades, Proyectos y Contacto.
- Formulario de contacto integrado.

## Tecnologías Utilizadas

- **HTML5**: Semántico y estructurado.
- **CSS3**: Diseño moderno, Flexbox, variables CSS y estilos personalizados.
- **JavaScript (Vanilla)**: Lógica de interactividad, filtrado de proyectos y validación de formulario.
- **Herramientas de Terceros**:
  - [Particles.js](https://vincentgarreau.com/particles.js/) para el efecto animado en el fondo.
  - [AOS (Animate On Scroll)](https://michalsnik.github.io/aos/) para mostrar elementos al desplazar.
  - [Typed.js](https://mattboldt.com/demos/typed-js/) para el efecto de máquina de escribir en el inicio.
  - [Font Awesome](https://fontawesome.com/) para todos los iconos utilizados.
  - [Google Fonts](https://fonts.google.com/) (Inter y Outfit).

## Cómo ejecutar el proyecto localmente

Este proyecto utiliza archivos estáticos (HTML, CSS y JS puro), por lo que puedes probarlo de diferentes maneras:

### Opción 1: Abrir directamente (Más fácil)
Simplemente haz doble clic en el archivo `index.html` o arrástralo hacia la ventana de tu navegador de preferencia.

### Opción 2: Servidor Local con Python (Recomendado)
Para evitar problemas con CORS al cargar recursos o abrir enlaces locales, es recomendable usar un servidor local. Si usas Mac (o tienes Python instalado):
1. Abre tu terminal.
2. Navega hacia el directorio del portafolio.
3. Corre el este comando:
   ```bash
   python3 -m http.server 8080
   ```
4. Abre el navegador y visita [http://localhost:8080](http://localhost:8080).

### Opción 3: Extensión de VS Code
1. Abre tu proyecto en Visual Studio Code.
2. Instala la extensión **Live Server**.
3. Haz clic derecho en `index.html` y selecciona **"Open with Live Server"**.

## Estructura de Archivos

```text
/My-portfolio
│
├── index.html       # Página principal con toda la estructura de la web
├── css/             # Carpeta de hojas de estilo
│   └── styles.css   # Estilos globales y específicos del portafolio
├── js/              # Carpeta de scripts
│   └── main.js      # Script principal (Typed.js, animaciones, filtros, etc.)
└── README.md        # Documentación del proyecto
```

## Autor

**Miguel Cabral** - Full Stack Developer
- Email: cabrito2012s@gmail.com
- [GitHub](https://github.com/) 
- [LinkedIn](https://linkedin.com/)
- Teléfono: +52 332 793 9021
