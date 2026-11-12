# Bitacoras
Bitácoras de desarrollo y proyectos (PDFs, carpetas y fichas).

## Estructura

```
proyectos/
└── <proyecto>/
    └── AAAA-MM-DD-<tema>/
        ├── README.md      ← ficha (copiada de PLANTILLA.md)
        ├── informe.pdf
        └── anexos/        ← subcarpetas si hacen falta
```

## Cómo subir una entrada desde GitHub web

1. Entra a `proyectos/<proyecto>/` (si el proyecto no existe, créalo con
   **Add file → Create new file** escribiendo `<proyecto>/AAAA-MM-DD-<tema>/README.md`).
2. Dentro de la carpeta de la entrada, pulsa **Add file → Upload files**.
3. Arrastra los PDFs **o carpetas completas**: GitHub conserva la estructura.
4. Rellena la ficha `README.md` con el resumen y la lista de archivos.

## Límites de GitHub
- Subida web: máx. **25 MB por archivo** y **100 archivos por subida**.
- Por git: máx. **100 MB por archivo** (aviso a partir de 50 MB).
- Si un PDF supera eso, comprímelo o divídelo antes de subirlo.

## Convenciones
- Nombres en minúsculas, con guiones y sin tildes ni espacios: `acta-reunion-cliente.pdf`.
- Fechas en formato ISO (`2026-11-12`) para que se ordenen solas.
- Toda entrada lleva su ficha `README.md`: el contenido de un PDF no es buscable en GitHub.
