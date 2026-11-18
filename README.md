# Lexicón Inglés

Diccionario inglés–español para estudiantes de habla hispana. Escribes una palabra o frase en inglés y la página muestra:

- Pronunciación (IPA) con botón para escucharla.
- Tipo de palabra (noun, verb, adjective…).
- Significados en español, con imagen (emoji) y un ejemplo de uso con su traducción y botón para escucharlo.
- Barra de frecuencia de uso en el día a día.
- Raíz y origen de la palabra.
- Sinónimo más usado cuando la palabra es poco común.
- Familia de palabras con significados principales y alternativos, ordenada por frecuencia de uso.
- Búsquedas recientes (guardadas en el navegador).

## Cómo funciona

Todo está en `index.html` (HTML, CSS y JavaScript sin dependencias).

Las búsquedas y la voz usan las capacidades de los Artifacts de claude.ai (`window.claude.use("sample")` y `window.claude.use("tts")`). Fuera de claude.ai la página se abre y muestra la ficha de ejemplo, pero las búsquedas no funcionan; la pronunciación usa la voz del navegador.
