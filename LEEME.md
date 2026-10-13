# Portafolio · David Morán Pérez

## Cómo verlo
1. Abre esta carpeta en Visual Studio Code (Archivo > Abrir carpeta).
2. Instala la extensión **Live Server** (VS Code te la sugiere al abrir la carpeta).
3. Clic derecho en `index.html` > **Open with Live Server**. Se abre en el navegador y se recarga solo cada vez que guardas.

## Dónde van tus archivos
Todo va en la carpeta `media/` con estos nombres exactos. Mientras falte un archivo, su espacio muestra una guía punteada.

| Archivo | Dónde aparece | Estado |
|---|---|---|
| portada.mp4 / .webm / .jpg | Portada | Incluido |
| documental.mp4, comunicacion.mp4, tecnologia.mp4 | Disciplinas | Incluidos |
| (Datos) | Disciplina: Datos | Animación hecha en código, no lleva archivo |
| caracol-1/2/3.jpg | Álbum: El camino del caracol | Incluidos |
| raices.jpg | Álbum: Raíces y Los maestros | Incluido |
| los-maestros.jpg | Álbum: Raíces y Los maestros | Incluido (fotograma del documental) |
| foto-*.jpg | Álbum: Retrato, Territorio y Escena; reconocimientos | Incluidos |
| matices.jpg | Reconocimientos: publicación en Matices | Incluido |
| maristas-1.mp4, maristas-2.mp4, maristas-3.jpg | Álbum: Provincia Marista | Incluidos |
| voluntariadomx-1/2/3/4.jpg | Álbum: VoluntariadoMx | Incluidos |
| guajira-1/2.jpg | Álbum: Corazón Sin Fronteras | Incluidos |
| tecnologia.mp4, conecta.mp4 | Álbum: ChampiAwards y Conecta + | Incluidos |
| retrato.jpg | Perfil | Incluido |
| cv-david-moran-perez.pdf | Botones "Descargar CV" | Incluido |
| champileaks-dashboard.jpg | Álbum: ChampiLeaks (captura real al tocar el tablero) | Incluido |

ChampiLeaks usa un tablero animado (al tocarlo abre la captura real). El cineforo usa una visualización hecha con las respuestas del formulario. La automatización con IA local usa un diagrama SVG interactivo.

## Publicación
- Repositorio: https://github.com/David2000-mp/PortafolioDavidMoran
- El sitio es HTML estático: `index.html` en la raíz y los archivos en `media/`. No necesita compilación.
- En Vercel: **Add New… > Project**, importa el repositorio y usa **Framework Preset: Other**, sin comando de build y con el directorio de salida vacío (la raíz). Cada `git push` a `main` vuelve a publicar el sitio.
