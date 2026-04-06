# Práctica II — Control de Versiones y Administración de Paquetes

## Descripción
Proyecto desarrollado para la Práctica II que incluye control de versiones con Git/GitHub y administración de paquetes con Node.js.

## Requisitos
- Node.js
- npm

## Instalación
```bash
npm install
```

## Compilar Sass
```bash
# Una vez
npm run sass

# Modo watch (detecta cambios automátticos)
npm run sass:watch

# Producción (minificado)
npm run build
```

## Estructura
```
proyecto-practica2/
├── src/
│   ├── scss/          # Archivos Sass fuente
│   ├── js/            # JavaScript
│   └── img/           # Imágenes originales
├── dist/
│   ├── css/           # CSS compilado (generado por Sass)
│   ├── js/            # JS procesado
│   └── img/           # Imágenes optimizadas
├── index.html
├── package.json
└── .gitignore
```

## Ramas del repositorio
- `main` / `master` — Rama principal de producción
- `MAESTRO` — Rama de desarrollo
