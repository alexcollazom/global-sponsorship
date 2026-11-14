# Global Sponsorship Group — rediseño

Propuesta de rediseño del sitio de Global Sponsorship Group con motion graphics: estadio animado en canvas, puente marcas ↔ propiedades, marcador tipo odómetro, canchas dibujadas en línea y ciclo 360°.

Es un solo archivo, `index.html`, sin dependencias ni build (las fuentes cargan desde Google Fonts).

## Ver en local

```bash
python -m http.server 5181
```

Abre http://localhost:5181

## Despliegue en Render

`render.yaml` define un sitio estático. En Render: **New → Blueprint**, elige este repositorio y aplica. Cada push a `main` vuelve a publicar el sitio.
