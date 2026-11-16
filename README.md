# ARIFURETA // HUD

Sistema personal de enfoque con estética anime/HUD, en un solo `index.html` con HTML, CSS y JavaScript vanilla.

## Qué incluye

- **Núcleo:** saludo, frase, racha, reactor de productividad, resumen del día y registro reciente.
- **Pomodoro:** enfoque, descansos, ciclos, sonido y configuración persistente.
- **Cronómetro:** vueltas, tiempo persistente y exportación a `.txt`.
- **Libreta:** notas con etiquetas, búsqueda y autoguardado.
- **Metas:** hitos, progreso, prioridad, fecha límite y línea de tiempo.
- **Inspiración:** retrato de Hajime Nagumo, Nelson Quest, Dark Mode (PDF ES/EN), Iron Man y galería personal.
- **Respaldo:** medidor de almacenamiento, último respaldo, exportar/importar JSON y copiar al portapapeles.

## Publicar en GitHub Pages

1. Crea un repositorio en GitHub.
2. Sube **todo el contenido de esta carpeta**, no solo `index.html`:
   - `index.html`
   - `img/` (Hajime, Iron Man, reactor, Nelson Quest y portadas de Dark Mode)
3. Ve a **Settings → Pages → Build and deployment**.
4. En **Source** elige **Deploy from a branch**.
5. Selecciona la rama `main` y la carpeta `/ (root)`.
6. Guarda y espera uno o dos minutos.

Tu app quedará en:

```text
https://TU-USUARIO.github.io/TU-REPOSITORIO/
```

## Fotos y almacenamiento

- El retrato del dashboard y las fotos de la galería se guardan en `localStorage`, solo en el dispositivo y navegador donde las subes.
- Las imágenes se comprimen antes de guardarse. Aun así, ocupan espacio: si el navegador avisa que está lleno, elimina alguna foto o exporta el respaldo y limpia los datos del sitio.
- `localStorage` no se sincroniza entre dispositivos. Para mover todo, usa **Exportar JSON** e **Importar** en el otro equipo.
- Claves usadas: `arifureta_notas`, `arifureta_metas`, `arifureta_pomodoro`, `arifureta_cronometro`, `arifureta_prefs`, `arifureta_retrato`, `arifureta_galeria`.

## Recursos enlazados

- Dark Mode en español: <https://nelsonquest.com/guide/Dark-Mode-2020-Spanish.pdf>
- Dark Mode en inglés: <https://nelsonquest.com/guide/Dark-Mode-2020-English.pdf>
- Sitio oficial de Nelson Quest: <https://nelsonquest.com/es/>

## Créditos y derechos

Proyecto personal de fans, sin fines comerciales. Las imágenes de Hajime Nagumo, Iron Man, Nelson Quest y Dark Mode pertenecen a sus respectivos autores y propietarios. Si eres titular de algún derecho y quieres que se retire una imagen, sustituye el archivo correspondiente en `img/` o elimina la tarjeta desde el código.

Fondo del dashboard: Unsplash.
