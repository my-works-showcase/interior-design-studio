# Interior Design Studio

**Live demo:** https://my-works-showcase.github.io/interior-design-studio/  
**Repository:** https://github.com/my-works-showcase/interior-design-studio

---

## Overview

A responsive multi-page website for an interior design studio. The project focuses on clean UI, smooth page/section animations, and a structured SCSS architecture. It includes a Services flow with a multi-step survey UI and reusable components.

---

## Key features

- **Multi-page navigation** with React Router
- **Smooth transitions & animations** (page and section) using Framer Motion
- **Responsive layout** (mobile-first approach)
- **Services survey flow** (multi-step UI with progress/status)
- **Reusable UI components** with consistent styling conventions
- **SCSS architecture** with variables, mixins, and layout utilities
- **Code quality**: ESLint + Prettier scripts

---

## Tech stack

- React
- React Router
- Framer Motion
- Sass (SCSS)
- ESLint, Prettier
- GitHub Pages (gh-pages)

---

## Project structure

```text
src/
  components/        # shared UI components
  pages/             # route-level pages (Home, Services, Projects, etc.)
  routes/            # AnimatedRoutes / routing helpers
  styles/            # SCSS architecture (variables, mixins, reset, grid, etc.)
  utils/             # utilities (api helpers, etc.)
