He usado la IA para agregar imágenes de mis proyectos aun grid (Masonry Grid). Para que se me hiciera más rapido el trabajo. Solo tenía que proporcionarle el link de mis imágenes subidas a imagekit.io.

    Mi petición: "quiero añadir imágenes al grid de branding con el método add forms"

    Respuesta IA: Voy a buscar dónde se usa el método addFromUrls para branding y añadir la imagen allí:

Searched text for branding.*addFromUrls|if.*project.*===.*branding (**/project-editor.html), no results

Déjame buscar dónde están las secciones de addFromUrls para ver el patrón:

Ahora voy a leer esa sección para ver dónde están los bloques de addFromUrls:

Read project-editor.html, lines 515 to 550

Ahora voy a leer un poco más para ver dónde termina y añadir el bloque de branding:

Read project-editor.html, lines 550 to 575

Perfecto, ahora voy a añadir el bloque de branding después del bloque de illustrations:

project-editor.html+7-0
Perfecto! Ahora he añadido la imagen al grid de branding usando el método addFromUrls. Cuando abras el project-editor con ?project=branding, se cargará automáticamente esta imagen en el grid.
