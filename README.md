# QA-Automation-2026-X-Academy - Curso de Automatización con Cypress

¡Bienvenido/a a mi repositorio de aprendizaje de QA Automation! Este espacio está destinado a almacenar todas las actividades, prácticas y tareas realizadas durante el curso de automatización de pruebas, utilizando **Cypress** como framework principal de pruebas y **Visual Studio Code** como entorno de desarrollo (IDE).

---

## 🚀 Propósito del Repositorio

El objetivo de este repositorio es consolidar los conocimientos teóricos y prácticos adquiridos a lo largo del curso, sirviendo como bitácora de progreso y portafolio personal. Aquí encontrarás desde pruebas de UI básicas hasta flujos de integración avanzados.

---

## 🛠️ Tecnologías y Herramientas Utilizadas

- **Lenguaje de Programación:** JavaScript
- **Framework de Testing:** [Cypress](https://www.cypress.io/) (Última versión estable)
- **Entorno de Desarrollo (IDE):** [Visual Studio Code](https://code.visualstudio.com/)
- **Entorno de Ejecución:** [Node.js](https://nodejs.org/) (Gestor de paquetes npm)

---

## 📋 Contenido del Repositorio

```
QA-Automation-2026-X-Academy/
├── cypress/
│   ├── e2e/                  # Tests end-to-end organizados por tema
│   │   ├── 01-fundamentos/
│   │   ├── 02-selectores/
│   │   ├── 03-assertions/
│   │   ├── 04-comandos-custom/
│   │   ├── 05-page-object-model/
│   │   ├── 06-fixtures/
│   │   ├── 07-intercept-api/
│   │   └── 08-advanced/
│   ├── fixtures/             # Datos de prueba en JSON
│   ├── support/
│   │   ├── commands.js       # Comandos personalizados
│   │   └── e2e.js            # Configuración global
│   └── pages/                # Page Object Model
├── cypress.config.js
├── package.json
└── README.md
```

---

## 📚 Temas Cubiertos

### Fundamentos
- [ ] Instalación y configuración de Cypress
- [ ] Primeros tests: `cy.visit()`, `cy.get()`, `cy.click()`
- [ ] Selectores: CSS, atributos `data-cy`, XPath
- [ ] Assertions con Chai: `should`, `expect`, `assert`

### Interacción con Formularios
- [ ] `cy.type()`, `cy.clear()`, `cy.select()`, `cy.check()`
- [ ] Upload de archivos
- [ ] Validación de campos

### Comandos y Helpers
- [ ] Comandos personalizados (`Cypress.Commands.add`)
- [ ] Aliases con `.as()`
- [ ] Variables y closures en Cypress

### Patrones de Diseño
- [ ] Page Object Model (POM)
- [ ] Fixtures para datos de prueba
- [ ] Hooks: `before`, `beforeEach`, `after`, `afterEach`

### Testing de APIs
- [ ] `cy.intercept()` para mockear requests
- [ ] `cy.request()` para pruebas de API REST
- [ ] Validación de responses y status codes

### Avanzado
- [ ] Variables de entorno con `cypress.env.json`
- [ ] Retry logic y manejo de flaky tests
- [ ] Reportes con Mochawesome
- [ ] Integración con CI/CD (GitHub Actions)

---

## ⚙️ Instalación

```bash
git clone https://github.com/JBjuliobotta/QA-Automation-2026-X-Academy.git
cd QA-Automation-2026-X-Academy
npm install
```

---

## ▶️ Cómo Ejecutar los Tests

```bash
# Abrir la interfaz gráfica de Cypress
npx cypress open

# Ejecutar todos los tests en modo headless
npx cypress run

# Ejecutar un archivo específico
npx cypress run --spec "cypress/e2e/01-fundamentos/primer-test.cy.js"

# Ejecutar en un navegador específico
npx cypress run --browser chrome
```

---

## 📖 Recursos

- [Documentación oficial de Cypress](https://docs.cypress.io/)
- [Best Practices — Cypress](https://docs.cypress.io/guides/references/best-practices)
- [Cypress Real World App](https://github.com/cypress-io/cypress-realworld-app) — proyecto de práctica oficial
- [Node.js Docs](https://nodejs.org/en/docs)

---

## 👤 Autor

**Carina Giacoletti**
Repositorio personal de aprendizaje — Curso QA Automation 2026 · X Academy
Cada carpeta dentro de `cypress/e2e/` corresponde a un tema o concepto específico con ejemplos prácticos.
