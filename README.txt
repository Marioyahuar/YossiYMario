INVITACIÓN DE BODA — Yossi & Mario
====================================

CONTENIDO
---------
- index.html ............ La invitación (autocontenida, imágenes ya incrustadas).
- uploads/ .............. Imágenes comprimidas (por si luego quieres usarlas aparte)
                          y donde debes colocar la música: uploads/cancion.mp3

MÚSICA
------
El botón de música apunta a  uploads/cancion.mp3.
Copia tu pista con ese nombre exacto dentro de la carpeta uploads/ y funcionará.
(Empieza en pausa: los navegadores no permiten audio automático; suena al tocar el botón.)

SUBIR A VERCEL (paso a paso)
----------------------------
Opción A — Con repositorio Git (lo que estás haciendo):
  1. Crea el repo en GitHub/GitLab.
  2. Copia dentro del repo TODO el contenido de esta carpeta:
        index.html
        uploads/  (con las imágenes y tu cancion.mp3)
  3. Haz commit y push.
  4. En Vercel: "Add New… > Project" > importa el repo.
  5. Framework Preset: "Other". Root Directory: la raíz (donde está index.html).
     No hay build command; es un sitio estático.
  6. Deploy. Vercel te dará una URL pública y permanente (p. ej. yossi-mario.vercel.app).

Opción B — Sin Git (arrastrar y soltar):
  1. Instala la CLI:  npm i -g vercel
  2. Dentro de esta carpeta ejecuta:  vercel
     (o simplemente arrastra la carpeta en vercel.com/new si tu plan lo permite).

COMPARTIR POR WHATSAPP
----------------------
Comparte la URL de Vercel. WhatsApp mostrará una vista previa tipo tarjeta;
al tocarla se abre la web real y los botones de mapa, WhatsApp y música funcionan.

DATOS QUE PUEDES EDITAR EN index.html
-------------------------------------
- Cuentas bancarias (Interbank / BBVA)
- Teléfono de confirmación (wa.me/51986355732)
- Fecha del countdown (busca 2026-09-05T16:00:00-05:00)
