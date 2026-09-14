# Portfolio · Jhojahn Ramírez

Portfolio personal desarrollado para presentar mi perfil como **desarrollador Backend y DevOps Junior**, junto con mi experiencia, tecnologías y proyectos.

## Sobre el proyecto

Este portfolio nace como un proyecto personal orientado a centralizar mi experiencia, formación y proyectos relacionados principalmente con **desarrollo backend, automatización, DevOps y cloud**.

Además de funcionar como carta de presentación profesional, el proyecto me ha permitido seguir practicando desarrollo web, diseño responsive, organización por componentes e interacciones de interfaz con Astro.

## Características

- Diseño responsive para escritorio, tablet y móvil.
- Navegación por secciones con indicador de sección activa.
- Menú adaptado a dispositivos móviles.
- Animaciones de entrada al hacer scroll.
- Hero con animaciones, nodos flotantes y parallax suave.
- Barra de progreso de lectura.
- Efectos hover y transiciones moderadas.
- Timeline de experiencia y formación.
- Sección de tecnologías organizada por categorías.
- Tarjetas de proyectos con interacción visual.
- Enlaces a GitHub, LinkedIn y contacto.
- Respeto de `prefers-reduced-motion` para usuarios que prefieren menos animación.

## Stack

- **Astro**
- **Tailwind CSS**
- **HTML**
- **CSS**
- **JavaScript**
- **npm**

## Estructura principal

```text
portfolio-jhojahn/
├── public/
├── src/
│   ├── components/
│   │   ├── About.astro
│   │   ├── Contact.astro
│   │   ├── Experience.astro
│   │   ├── Footer.astro
│   │   ├── Hero.astro
│   │   ├── Navbar.astro
│   │   ├── Projects.astro
│   │   └── Skills.astro
│   ├── pages/
│   │   └── index.astro
│   └── styles/
│       └── global.css
├── astro.config.mjs
├── package.json
├── package-lock.json
├── tsconfig.json
└── README.md
```

## Ejecución local

### Requisitos

- **Node.js 22.12.0 o superior**
- **npm**

### 1. Clonar el repositorio

```bash
git clone https://github.com/jhojahnS/portfolio-jhojahn.git
```

### 2. Entrar al proyecto

```bash
cd portfolio-jhojahn
```

### 3. Instalar dependencias

```bash
npm install
```

### 4. Iniciar el servidor de desarrollo

```bash
npm run dev
```

Astro iniciará por defecto el proyecto en:

```text
http://localhost:4321
```

## Scripts disponibles

| Comando | Descripción |
| --- | --- |
| `npm run dev` | Inicia el servidor de desarrollo. |
| `npm run build` | Genera la versión de producción en `dist/`. |
| `npm run preview` | Permite previsualizar localmente la build de producción. |
| `npm run astro -- ...` | Ejecuta comandos de la CLI de Astro. |

## Secciones del portfolio

El portfolio incluye:

- **Inicio** — presentación y enfoque profesional.
- **Sobre mí** — perfil y áreas de interés.
- **Tecnologías** — stack organizado por categorías.
- **Experiencia** — formación y experiencia profesional.
- **Proyectos** — proyectos completados y planificados.
- **Contacto** — acceso a email, LinkedIn y GitHub.

## Proyectos destacados

Actualmente el portfolio presenta proyectos relacionados con:

- Desarrollo backend con **FastAPI, PostgreSQL, JWT y Docker**.
- Infraestructura y CI/CD en **AWS**.
- Desarrollo del propio portfolio con **Astro**.
- Automatizaciones con **Python**.
- Nuevos proyectos backend y DevOps planificados para seguir ampliando conocimientos.

## Objetivo

El objetivo de este proyecto es disponer de una carta de presentación técnica que muestre no solo las tecnologías que conozco, sino también **dónde las he aplicado, cómo he ido evolucionando y qué tipo de proyectos estoy construyendo**.

## Estado

El portfolio se encuentra en desarrollo activo y seguirá evolucionando con nuevos proyectos, mejoras y futuras publicaciones.

## Autor

**Jhojahn Ramírez**

- GitHub: [jhojahnS](https://github.com/jhojahnS)
- LinkedIn: [Jhojahn Ramírez](https://www.linkedin.com/in/jhojahn-sebastian-ram%C3%ADrez-mar%C3%ADn-9494a12b2)
