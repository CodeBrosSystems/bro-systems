# Bro Systems - Comunidad Tech Colaborativa

![Bro Systems Logo](/public/favicon/logo.jpg)

## 🚀 Descripción del Proyecto

Bro Systems es una comunidad tech colaborativa donde developers, diseñadores y entusiastas de la tecnología se reúnen para aprender, compartir y construir proyectos open source. Este sitio web es nuestra landing page comunitaria, construida con un hermoso efecto de estrellas en movimiento.

### ✨ Características Principales

- **Diseño Responsivo**: Adaptado perfectamente a dispositivos móviles, tablets y escritorio
- **Fondo Animado de Estrellas**: Animación de estrellas en movimiento con efecto parallax
- **Secciones Completas**: Hero, Áreas de la comunidad, Proyectos, Fundadores, FAQ y Contacto
- **Modo Oscuro/Claro**: Soporte para preferencias de tema del usuario
- **Animaciones de Scroll**: Elementos que se animan al hacer scroll
- **Enfoque Comunitario**: Transparencia, open source y colaboración

## 🛠️ Tecnologías Utilizadas

- [Astro](https://astro.build/) - Framework web para sitios estáticos de alto rendimiento
- [TailwindCSS](https://tailwindcss.com/) - Framework CSS utilitario
- [TypeScript](https://www.typescriptlang.org/) - Para una experiencia de desarrollo robusta
- [React](https://react.dev/) - Para componentes interactivos (cuando se necesitan)

## 📁 Estructura del Proyecto

```text
/
├── public/               # Archivos estáticos
│   ├── images/           # Imágenes del sitio
│   │   └── Logo.jpg      # Logo de Bro Systems
│   └── favicon/          # Favicons
├── src/
│   ├── components/       # Componentes reutilizables
│   │   ├── Header.astro  # Barra de navegación
│   │   ├── Hero.astro    # Sección principal
│   │   ├── Services.astro # Áreas de la comunidad
│   │   ├── Prices.astro  # Estadísticas comunitarias
│   │   ├── Projects.astro # Proyectos colaborativos
│   │   ├── Founders.astro # Información sobre fundadores
│   │   ├── Faq.astro     # Preguntas frecuentes
│   │   ├── Contact.astro # Formulario de contacto
│   │   └── Footer.astro  # Pie de página
│   ├── layouts/
│   │   └── Layout.astro  # Plantilla principal con el fondo estrellado
│   ├── pages/
│   │   └── index.astro   # Página principal
│   └── styles/
│       └── global.css    # Estilos globales y configuración de TailwindCSS
└── package.json          # Dependencias y scripts
```

## 🚀 Cómo Empezar

### Prerrequisitos

- Node.js 18 o superior
- npm o yarn

### Instalación

1. Clona el repositorio
   ```sh
   git clone https://github.com/NachoOFC/bro-systems.git
   cd bro-systems
   ```

2. Instala las dependencias
   ```sh
   npm install
   ```

3. Inicia el servidor de desarrollo
   ```sh
   npm run dev
   ```

4. Abre [http://localhost:4321](http://localhost:4321) en tu navegador

## 🧞 Comandos Disponibles

| Comando                   | Acción                                           |
| :------------------------ | :----------------------------------------------- |
| `npm install`             | Instala dependencias                             |
| `npm run dev`             | Inicia servidor local en `localhost:4321`        |
| `npm run build`           | Construye el sitio para producción en `./dist/`  |
| `npm run preview`         | Previsualiza la build localmente                 |

## 🌟 Características del Fondo Estrellado

El sitio cuenta con un impresionante fondo de estrellas en movimiento que crea una experiencia inmersiva:

- **Efecto Parallax**: Múltiples capas de estrellas moviéndose a diferentes velocidades
- **Estrellas Fugaces**: Animación ocasional de estrellas fugaces
- **Optimizado para Rendimiento**: Implementado con CSS y JavaScript optimizados
- **Responsive**: Se adapta a cualquier tamaño de pantalla

## 👥 Fundadores

- **Ignacio Pérez** - Desarrollador Junior & Co-Fundador
  - [GitHub](https://github.com/NachoOFC)
  - [Portafolio](https://nachoportafolio.me/)

## 🤝 Contribuir

¡Las contribuciones son bienvenidas! Revisa nuestros [issues](https://github.com/NachoOFC/bro-systems/issues) para encontrar cómo puedes ayudar.

## 📝 Licencia

Este proyecto está bajo licencia privada. Todos los derechos reservados para Bro Systems.

---

Desarrollado con ❤️ por Bro Systems - Comunidad tech colaborativa.
