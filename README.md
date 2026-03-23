# 🌐 Portfolio & Blog Personal

![React](https://img.shields.io/badge/React-18-61DAFB?style=flat&logo=react&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-18-339933?style=flat&logo=node.js&logoColor=white)
![License](https://img.shields.io/badge/Licencia-MIT-green?style=flat)

Aplicación web de portfolio y blog personal desarrollada con React y Node.js. Permite presentar proyectos, publicar artículos y mostrar información profesional de forma clara y atractiva.

---

## ✨ Características

- 📄 Página de presentación personal
- 📝 Sección de blog con artículos
- 💼 Galería de proyectos
- 📱 Diseño responsive
- ⚡ Navegación rápida con React Router

---

## 🛠️ Tecnologías

| Tecnología | Versión | Uso |
|---|---|---|
| React | 18 | Interfaz de usuario |
| Node.js | 18 | Entorno de ejecución |
| CSS Modules | — | Estilos por componente |
| Vite | 5 | Bundler y servidor de desarrollo |

----

## 🚀 Instalación

Sigue estos pasos para ejecutar el proyecto en local:

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

**4. Inicia el servidor de desarrollo**

```bash
npm run dev
```

Abre [http://localhost:3000](http://localhost:3000) en tu navegador.

---

## 📖 Uso

| Ruta | Descripción |
|---|---|
| `/` | Página principal con presentación |
| `/about` | Información personal y habilidades |
| `/blog` | Listado de artículos publicados |

---

## 📁 Estructura del proyecto

```
practica-modulo6/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── Navbar.jsx
│   │   └── Footer.jsx
│   ├── pages/
│   │   ├── Home.jsx
│   │   ├── About.jsx
│   │   └── Blog.jsx
│   ├── App.jsx
│   └── main.jsx
├── .env.example
├── .gitignore
└── README.md
```

---

## 🤝 Contribución

Las contribuciones son bienvenidas. Para contribuir:

1. Haz un fork del repositorio
2. Crea una rama nueva: `git checkout -b feature/nueva-funcionalidad`
3. Realiza tus cambios y haz commit: `git commit -m "feat: nueva funcionalidad"`
4. Sube la rama: `git push origin feature/nueva-funcionalidad`
5. Abre una Pull Request

---

## 📄 Licencia

Este proyecto está bajo la licencia [MIT](LICENSE).

---

> README mejorado con [Claude](https://claude.ai) como parte de la práctica del Módulo 6.