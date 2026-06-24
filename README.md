# Erick Larrainzar — sitio personal

Página de una sola pantalla hecha con HTML, CSS y JavaScript puro. Sin frameworks ni build: se sube tal cual.

Incluye foco que sigue el cursor, marquesina animada, botones magnéticos y reveals al hacer scroll. Todo se desactiva solo si el sistema tiene activado "reducir movimiento".

## Verla en local

Abre `index.html` en el navegador, o sirve la carpeta:

```bash
python3 -m http.server 8000
```

Luego entra a `http://localhost:8000`.

## Estructura

```
mi-pagina/
├── .github/workflows/deploy.yml   # despliegue automático a Pages
├── index.html                     # contenido y estructura
├── styles.css                     # estilos
├── script.js                      # interacciones
├── .gitignore
└── README.md
```

## Qué editar

- Tu rol, descripción, proyectos y enlaces están en `index.html` (busca los textos que dicen "edita" o "Reemplaza").
- Los colores y tipografías están al inicio de `styles.css`, en el bloque `:root`.

## Publicar en GitHub Pages

El repo incluye un workflow en `.github/workflows/deploy.yml` que despliega solo en cada push a `main`.

En Settings → Pages → Source, elige **GitHub Actions**. En unos minutos queda en `https://TU-USUARIO.github.io/mi-pagina/`.
