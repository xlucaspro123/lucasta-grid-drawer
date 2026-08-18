# Lucasta Grid Drawer

**Editor vectorial + prototipo de niveles estilo Geometry Dash.**

Un solo HTML. Sin dependencias. Desktop y mobile. Guarda en `.lgd`.

![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)
![Pure HTML](https://img.shields.io/badge/stack-HTML%20%2B%20JS%20%2B%20SVG-5b9dff)

---

## ¿Qué es?

Una app para:

1. **Dibujar** en una cuadrícula (líneas, formas, lápiz, texto)
2. **Colocar objetos GD** (orbes, pads, portales, bloques, pinchos)
3. **Probar el nivel** con físicas de cubo / nave (▶ Play)

Ideal para prototipar niveles sin perder el progreso.

---

## Archivos

| Archivo | Uso |
|---------|-----|
| `lucasta-grid-drawer.html` | **Desktop** (completo) |
| `lucasta-grid-drawer-mobile.html` | **Tablet / móvil** (touch) |
| `README.md` | Este archivo |
| `LICENSE` | MIT |
| `Lucasta_Grid_Drawer_Ultimate_Guide.txt` | Manual detallado |

---

## Inicio rápido (30 segundos)

1. Abre `lucasta-grid-drawer.html` en el navegador
2. La primera vez verás la **ayuda** (también botón **?**)
3. Elige **Cuadro** → arrastra una plataforma
4. **Objetos GD** → Block / Yellow / Ship…
5. Click en el canvas para colocar
6. **▶ Play** → Espacio para saltar

---

## Herramientas

| Herramienta | Tecla | Qué hace |
|-------------|-------|----------|
| Seleccionar | `V` | Mover, escalar, rotar |
| Lápiz | `P` | Trazo libre (Legacy o Smooth) |
| Línea | `L` | Segmento |
| Bézier | `B` | Curva por puntos |
| Cuadro | `R` | Rectángulo / bloque |
| Triángulo | `T` | Pincho en play |
| Círculo | `C` | Orbe (según color) |
| Dash orb | `D` | Orbe dash con flecha |
| Píxel | — | Una celda |
| **Texto** | `X` | Escribir etiquetas |
| Borrar | `E` | Click o arrastrar |
| Vista | `H` | Panear el canvas |

---

## Texto

1. Herramienta **Texto** (`X`)
2. Click (o arrastra para tamaño) en el canvas
3. Escribe en el diálogo
4. **Doble click** en un texto para editarlo
5. Color = color de trazo actual

---

## Objetos Geometry Dash

Menú **Objetos GD** (sidebar):

- **Orbes:** Yellow, Pink, Red, Blue, Green, Black, Dash
- **Pads:** Y / P / R / B
- **Portales:** Ship, Cube, Gravity
- **Sólidos:** Block, Spike

Flujo: elige del menú → click en canvas (repetible).

En **Play**:

| Objeto | Efecto |
|--------|--------|
| Block / rect / pixel | Suelo sólido |
| Spike / triángulo | Muerte |
| Orbe + salto | Boost / flip / slam |
| Pad | Salto al tocar |
| Portal Ship | Modo nave |
| Portal Cube | Vuelve a cubo |
| Portal Gravity | Invierte gravedad |
| Lápiz / línea | Slopes |

---

## Playtest

- **▶ Play** / **■ Stop**
- **Espacio / W / ↑ / click** = saltar (en nave = volar)
- **R** = respawn
- **Esc** = salir del play

Cubo = 1 bloque del grid. Hitbox = el cuadrado del sprite.

---

## Guardar

- **Guardar .lgd** → proyecto completo
- **Abrir .lgd** → restaurar
- **Exportar PNG** → captura del viewport

---

## Mobile

Abre `lucasta-grid-drawer-mobile.html`:

- Toolbar inferior
- Menús laterales (☰ / ⚙)
- Touch + pinch zoom
- Mismo formato `.lgd`

---

## GitHub Pages

```text
https://TU_USUARIO.github.io/lucasta-grid-drawer/lucasta-grid-drawer.html
```

Custom domain: **vacío**. Source = branch `main` / root.

---

## Licencia

MIT © Lucasta / Absolute Lucasta

---

## Enlaces Utiles
Enlaces útiles

App auto: https://lucasta-grid-drawer.netlify.app
Solo PC: https://lucasta-grid-drawer.netlify.app/lucasta-grid-drawer.html
Solo móvil: https://lucasta-grid-drawer.netlify.app/lucasta-grid-drawer-mobile.html
Forzar PC: https://lucasta-grid-drawer.netlify.app/?v=desktop
Forzar móvil: https://lucasta-grid-drawer.netlify.app/?v=mobile
