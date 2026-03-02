# 📘 Introducción a Angular

## ¿Qué es Angular?

Angular es un framework para desarrollo web mantenido por Google, diseñado para construir aplicaciones web dinámicas y escalables. Está basado en **TypeScript**, lo que proporciona una estructura más sólida y organizada para desarrollar interfaces complejas.

Angular permite crear aplicaciones rápidas y fiables mediante un conjunto de herramientas, APIs y bibliotecas que facilitan la construcción de interfaces bien estructuradas y fáciles de mantener (UNIR, 2025).

---

## 🔑 Conceptos Claves de Angular

### 🧩 Arquitectura basada en componentes
Cada parte de la aplicación (botones, formularios, vistas completas) es un componente reutilizable que contiene:
- Lógica (TypeScript)
- Plantilla (HTML)
- Estilos (CSS)

Esto facilita la lectura, pruebas y mantenimiento del código.

---

### 🔄 Enlace de datos y directivas
Angular permite enlazar datos entre la lógica y la vista (Data Binding), además de utilizar directivas para extender el comportamiento de los elementos HTML.

---

### 🛣️ Sistema de Rutas (Router)
Permite gestionar la navegación dentro de la aplicación y organizar las vistas de forma estructurada.

---

### ⚙️ Angular CLI (Command Line Interface)
Herramienta de línea de comandos que permite:
- Crear proyectos
- Generar componentes y servicios
- Ejecutar pruebas
- Compilar aplicaciones

---

### 📝 Validación y formularios
Angular soporta formularios reactivos con validación integrada, permitiendo crear formularios más robustos y escalables.

---

## 🚀 ¿Por qué usar Angular?

Angular no es solo una biblioteca, es una plataforma integral con arquitectura definida que:

- Permite escalar proyectos grandes
- Estandariza el código y mantenimiento
- Reduce errores y tiempo de desarrollo
- Facilita pruebas automáticas
- Integra navegación avanzada y mejoras de rendimiento

Por ello, Angular es ideal para:
- Aplicaciones empresariales complejas
- Paneles administrativos
- Sistemas internos
- Proyectos que requieren mantenimiento a largo plazo

(UNIR, 2025)

---

# 🛠 Instalación de Angular

Para comenzar a trabajar con Angular, es necesario instalar las siguientes herramientas:

## 1️⃣ Node.js
Permite ejecutar el entorno de desarrollo y administrar paquetes.

Descargar desde:
https://nodejs.org/

Verificar instalación:
```bash
node -v
npm -v


# HolaMundoAngular

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 21.2.0.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Vitest](https://vitest.dev/) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
