# Mis Frascos — 30 preferencias para adultos

Aplicación web estática e interactiva en español. Marca las 30 preferencias con la escala **Pendiente, 0, 1, 2, 3, 4, 5**, visualiza el resultado y descarga o comparte el póster en PNG.

**Sitio previsto:** https://marcosadelacruz.github.io/Frascos-de-los-deseos/

## Publicar en GitHub Pages

1. Abre [Settings → Pages](https://github.com/marcosadelacruz/Frascos-de-los-deseos/settings/pages).
2. En **Build and deployment**, escoge **Deploy from a branch**.
3. Selecciona **main** y **/(root)**.
4. Pulsa **Save** y espera que aparezca el enlace publicado.

El archivo `index.html` en la raíz es la aplicación. `.nojekyll` evita el procesamiento Jekyll.

## Características

- 30 frascos fijos y animados con diseño adaptable a móviles.
- Selección pendiente / nivel 0 / niveles 1–5.
- Vista previa, descarga de póster PNG y posibilidad de compartirlo en navegadores compatibles.
- Botón para compartir el enlace del sitio: **no comparte las respuestas**.
- Guardado local en el navegador.
- Exportación y restauración de copias JSON cifradas con AES-256-GCM y PBKDF2-SHA-256.
- Bloqueo opcional del almacenamiento local con contraseña.

## Privacidad y seguridad

Las respuestas se almacenan en el navegador del visitante, no en una base de datos del sitio. Por defecto los datos locales no están cifrados hasta activar el bloqueo con contraseña. Los pósteres PNG no están cifrados. Compartir uno revela sus respuestas. Las visitas al alojamiento pueden generar registros técnicos gestionados por GitHub.

La página está dirigida a **personas adultas**. Una preferencia no representa consentimiento.

## Tecnología

HTML, CSS y JavaScript sin backend ni dependencias externas. GitHub Pages hospeda contenido estático gratuitamente en este repositorio público.
