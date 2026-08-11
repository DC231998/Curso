# 🥐 Mon Carnet Français

Curso interactivo de francés (nivel A1) con lecciones, ejercicios, ilustraciones, guardado de progreso y sistema de recompensas ("puntos de viaje", rachas e insignias tipo "sellos de pasaporte").

## Cómo publicarlo gratis en GitHub Pages

1. Crea un repositorio nuevo en GitHub (por ejemplo `mon-carnet-francais`).
2. Sube **todo el contenido de esta carpeta** (`index.html`, `css/`, `js/`) a la raíz del repositorio.
3. En GitHub, ve a **Settings → Pages**.
4. En "Source" selecciona la rama `main` y la carpeta `/ (root)`, luego **Save**.
5. Espera 1-2 minutos: GitHub te dará una URL como `https://tu-usuario.github.io/mon-carnet-francais/`.
6. ¡Listo! Ábrela desde tu celular y agrégala a la pantalla de inicio para que se sienta como una app.

## Notas sobre el progreso guardado

El progreso (lecciones completadas, XP, racha, insignias) se guarda con `localStorage` **en el navegador de cada dispositivo**. Esto significa:

- No necesitas cuenta ni internet para que se guarde.
- Si borras los datos de navegación del sitio, se pierde el progreso.
- El progreso **no se sincroniza automáticamente** entre tu celular y tu computadora (cada uno guarda el suyo).

## Cómo seguimos ampliando el curso

Todo el contenido vive en `js/data.js`, en un arreglo `LESSONS`. Para agregar niveles A2, B1, B2, C1 o C2 (o más lecciones de A1), solo hay que añadir nuevos objetos con el mismo formato: título, ícono, vocabulario, gramática y ejercicios. El resto de la app (ruta, XP, insignias) se actualiza automáticamente.
