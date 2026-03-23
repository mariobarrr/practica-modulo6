# 🌐 Portfolio & Blog Personal

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18-339933?style=flat&logo=node.js&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-5-646CFF?style=flat&logo=vite&logoColor=white)
![License](https://img.shields.io/badge/Licencia-MIT-green?style=flat)
![Status](https://img.shields.io/badge/Estado-En%20desarrollo-yellow?style=flat)

## 📌 Descripción

**Portfolio & Blog Personal** es una aplicación web fullstack desarrollada con **React** y **Node.js** que permite mostrar proyectos, habilidades y publicar artículos técnicos de forma profesional.

El objetivo del proyecto es servir como carta de presentación digital para procesos de selección, con un diseño limpio, navegación rápida y contenido fácil de mantener.

### ¿Qué problema resuelve?
- Centraliza la presencia profesional en una sola aplicación
- Permite publicar artículos técnicos en el blog integrado
- Facilita el contacto con reclutadores y colaboradores

---

## ✨ Características principales

- 🏠 **Página de inicio** — presentación personal y resumen profesional
- 💼 **Sección de proyectos** — galería con descripción y enlaces a cada proyecto
- 📝 **Blog integrado** — artículos técnicos organizados por categorías
- 👤 **Página About** — experiencia, habilidades y formación
- 📱 **Diseño responsive** — adaptado a móvil, tablet y escritorio
- ⚡ **Rendimiento optimizado** — carga rápida con Vite como bundler

---

## 🛠️ Tecnologías

| Tecnología | Versión | Descripción |
|---|---|---|
| [React](https://reactjs.org/) | 18 | Librería principal para la interfaz de usuario |
| [Node.js](https://nodejs.org/) | 18 | Entorno de ejecución de JavaScript |
| [Vite](https://vitejs.dev/) | 5 | Bundler y servidor de desarrollo ultrarrápido |
| [React Router](https://reactrouter.com/) | 6 | Enrutamiento del lado del cliente |
| CSS Modules | — | Estilos encapsulados por componente |

---

## 🚀 Instalación y puesta en marcha

### Prerrequisitos

Asegúrate de tener instalado:
- [Node.js](https://nodejs.org/) v18 o superior
- [Git](https://git-scm.com/)

### Pasos

**1. Clona el repositorio**

```bash
git clone https://github.com/mariobarrr/practica-modulo6.git
cd practica-modulo6
```

**2. Instala las dependencias**

```bash
npm install
```

**3. Configura las variables de entorno**

```bash
cp .env.example .env
```

Edita el archivo `.env` con tus valores:

```env
PORT=3000
NODE_ENV=development
```

**4. Inicia el servidor de desarrollo**

```bash
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000) en tu navegador. 🎉

---

## 📖 Uso

| Ruta | Página | Descripción |
|---|---|---|
| `/` | Inicio | Presentación personal y proyectos destacados |
| `/about` | Sobre mí | Habilidades, experiencia y formación |
| `/blog` | Blog | Listado de artículos publicados |

### Scripts disponibles

```bash
npm run dev      # Inicia el servidor de desarrollo
npm run build    # Genera la build de producción
npm run preview  # Previsualiza la build de producción
```

---

## 📁 Estructura del proyecto

```
practica-modulo6/
├── .github/
│   ├── PULL_REQUEST_TEMPLATE.md
│   └── ISSUE_TEMPLATE/
│       └── feature.md
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Navbar.jsx        # Barra de navegación principal
│   │   └── Footer.jsx        # Pie de página
│   ├── pages/
│   │   ├── Home.jsx          # Página de inicio
│   │   ├── About.jsx         # Página sobre mí
│   │   └── Blog.jsx          # Página del blog
│   ├── App.jsx               # Componente raíz
│   └── main.jsx              # Punto de entrada
├── .env.example              # Variables de entorno de ejemplo
├── .gitignore
└── README.md
```

---

## 🤝 Contribución

Las contribuciones son bienvenidas. Para contribuir:

1. Haz un fork del repositorio
2. Crea una rama nueva: `git checkout -b feature/nueva-funcionalidad`
3. Realiza tus cambios y haz commit: `git commit -m "feat: descripción del cambio"`
4. Sube la rama: `git push origin feature/nueva-funcionalidad`
5. Abre una Pull Request describiendo los cambios

Por favor, sigue el formato de commits [Conventional Commits](https://www.conventionalcommits.org/).

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE). Puedes usarlo libremente para tus propios proyectos.

---

## 👤 Autor

**mariobarrr** — [GitHub](https://github.com/mariobarrr)

---

> README generado con ayuda de [Claude](https://claude.ai) como parte de la práctica del Módulo 6.

Co-authored-by: Claude <claude@anthropic.com>