# Playwright Template

Este repositorio es una plantilla base para escribir pruebas E2E con [Playwright](https://playwright.dev/) y TypeScript. La plantilla es fácil de escalar y personalizar.

## Instalación

1. Clona este repositorio:
   ```bash
   git clone https://github.com/ejlh/playwright-template-ts.git
   cd playwright-template-ts
   ```
2. Instala las dependencias:
   ```bash
   npm install
   ```

## Comandos

- Ejecutar pruebas:
  ```bash
  npx playwright test
  ```
- Ver reportes:
  ```bash
  npx playwright show-report
  ```

## Estructura

- `src/pages/`: Define los Page Objects para modularizar las pruebas.
- `src/tests/`: Contiene las pruebas organizadas por características.
- `.github/workflows/playwright.yml`: Configuración para ejecutar pruebas en GitHub Actions.

## Contribuir

Consulta `changelog.md` para más detalles sobre los cambios realizados.