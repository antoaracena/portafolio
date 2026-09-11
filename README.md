# Portafolio — Taller de Interfaces (UAI 2026)

Sitio web que reúne y ordena las cuatro entregas del **Taller de Interfaces**. Cada entrega vive en su propio repositorio; este portafolio es el punto de entrada que las documenta y enlaza.

🔗 **Sitio en vivo:** https://antoaracena.github.io/

**Universidad Adolfo Ibáñez · Prof. Jorge Forero · 2026**
Autor: Antonia Aracena

## Entregas

| N° | Entrega | En vivo | Repositorio |
|----|---------|---------|-------------|
| 01 | Lámina de análisis de un electrodoméstico | [Ver](https://antoaracena.github.io/Lamina/) | [GitHub](https://github.com/antoaracena/Lamina) |
| 02 | Escucha & Relaciona — experiencia sonora | [Ver](https://antoaracena.github.io/juego-interactivo-/) | [GitHub](https://github.com/antoaracena/juego-interactivo-) |
| 03 | Instrumento de manipulación sonora en Max/MSP | [Ver](https://antoaracena.github.io/interfaz-interactiva-en-max/) | [GitHub](https://github.com/antoaracena/interfaz-interactiva-en-max) |
| 04 | Sonificación de imagen — Imagen → Música | [Ver](https://antoaracena.github.io/clase-imagen-y-sonido-/) | [GitHub](https://github.com/antoaracena/clase-imagen-y-sonido-) |

## Descripción técnica
Portafolio de **una sola página** (`index.html`) construido con HTML, CSS y JavaScript, sin frameworks ni dependencias externas salvo las tipografías de Google Fonts (Instrument Serif, Instrument Sans, IBM Plex Mono). Presenta las entregas como un índice editorial y enlaza a cada repositorio y sitio publicado.

Características: diseño responsivo (móvil y escritorio), navegación por teclado con foco visible, animación de la onda respetando `prefers-reduced-motion`, y paleta en blanco y baby blue.

## Guía de uso (ver el portafolio localmente)
1. Clonar el repositorio: `git clone https://github.com/antoaracena/antoaracena.github.io.git`
2. Abrir `index.html` en el navegador, o usar la extensión **Live Server** en VS Code para verlo con recarga automática.

## Estructura del repositorio
```
/
├── index.html        # portafolio (página principal)
├── capturas/         # capturas de pantalla del sitio
└── README.md
```

## Publicación en GitHub Pages
En este repositorio: **Settings → Pages → Deploy from a branch**, rama `main`, carpeta `/ (root)`. El sitio queda publicado en `https://antoaracena.github.io/`.

## Capturas de pantalla
Agrega una captura del portafolio en la carpeta `capturas/` y enlázala aquí:
`![Vista del portafolio](capturas/portafolio.png)`

## Créditos
- Tipografías: Instrument Serif, Instrument Sans e IBM Plex Mono (Google Fonts · SIL Open Font License).
- Los recursos de audio, imágenes y datos de cada entrega están documentados en el README de su propio repositorio.
