CAVIA - Sitio web estático listo para publicar en Vercel
====

Descripción:
- Sitio estático pensado para enseñanza infantil del idioma Cavineño.
- Contiene: index.html, carpeta assets/hero.png (imagen), y una carpeta audios/ donde puedes colocar archivos mp3 reales.

Cómo desplegar en Vercel (pasos rápidos):
1. Crea una cuenta en GitHub y sube todo el contenido de esta carpeta a un nuevo repositorio (ej: cavia-site).
2. Crea una cuenta en Vercel (https://vercel.com) e inicia sesión.
3. Elige 'Import Project' -> 'Import Git Repository' -> conecta con GitHub -> selecciona tu repo.
4. Vercel detecta sitio estático y publica automáticamente. En minutos tendrás: https://<tu-nombre>.vercel.app
5. Para reemplazar voces IA por audios reales: coloca archivos mp3 en la carpeta /audios/ con los nombres que aparecen en el código (por ejemplo 'sol.mp3' para la palabra Sol, o 'fr1.mp3' para la frase 1).

Notas técnicas:
- El sitio usa la Web Speech API para generar voz por IA en el navegador (si no hay archivos mp3 disponibles).
- Para un hosting sin internet (aula local), sirve los archivos desde un servidor local o copiar la carpeta en una máquina que actúe como servidor.
- Si deseas, puedo preparar una versión con React y Tailwind para funcionalidades más avanzadas.
