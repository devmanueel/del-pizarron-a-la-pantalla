# Del pizarrón a la pantalla — presentación web

## Abrir
Doble clic en `index.html` (necesita internet para fuentes, íconos y Reveal.js).

## Teclas
- → / ← / Espacio: avanzar y retroceder · F: pantalla completa · S: notas del orador · ?: ayuda
- T: cronómetro 40:00 (mostrar/ocultar) · R: reiniciar cronómetro
- I: iniciar/pausar el temporizador de práctica (diapositiva 9)
- M: sonidos · A: narrador (lee la diapositiva en voz alta) · Q: código QR · X: puntero láser
- PDF: abrir `index.html?print-pdf` en Chrome → Imprimir → Guardar como PDF (márgenes: ninguno, gráficos de fondo activados)

En el celular se ve automáticamente como lectura vertical. Para forzar un modo: `?modo=presentacion` o `?modo=celular`.

## Subir a Vercel
Opción A (sin instalar nada): subí esta carpeta a un repositorio de GitHub → en vercel.com, "Add New → Project" → importá el repo → Framework: "Other" → Deploy.
Opción B (con Node instalado): abrí una terminal en esta carpeta y ejecutá `npx vercel --prod`.

Una vez publicada, la tecla Q muestra un QR con el enlace para que el público la abra en el celular.
