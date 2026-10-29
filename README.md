# CPK Ingeniería · Canagro S.A.

Propuesta R05 · 29/10/2026.

## Publicación

1. Descomprimí el ZIP.
2. Subí `index.html`, `.nojekyll`, `README.md` y la carpeta `pdf` a la raíz del repositorio. Conservá los nombres y la estructura. No subas el ZIP en lugar de los archivos.
3. En Settings > Pages, elegí Deploy from a branch, la rama con los archivos (habitualmente main) y / (root). Guardá.
4. Abrí el enlace que GitHub muestre una vez finalizado el despliegue. Verificá su estado en Actions.

Si actualizás un repositorio existente, reemplazá el index y agregá o actualizá toda la carpeta pdf. Los cuatro enlaces deben funcionar.

## Archivos

- index.html: presentación completa con logo e imagen incorporados.
- pdf/: cuatro documentos, uno por frente y un resumen.
- .nojekyll: publicación estática sin procesamiento Jekyll.
- README.md: estas instrucciones.

El HTML descargado por separado es autocontenido para presentar. El index de GitHub incorpora además enlaces relativos a los PDF de la carpeta pdf.

## Verificación

- La portada identifica Canagro S.A. y revisión 05.
- El logo CPK se ve en la presentación y los cuatro PDF.
- Los tres frentes y los ejemplos PQCDS se abren y leen correctamente.
- Los cuatro PDF se descargan desde los enlaces de la página.
- Las imágenes ilustrativas no requieren conexión a otros sitios.
- El botón Imprimir / PDF abre el diálogo del navegador.

Si no ves .nojekyll, activá archivos ocultos. Podés crearlo en GitHub con Add file > Create new file, nombre exacto .nojekyll y texto HTML estático CPK. No agregues .txt.

Los ejemplos numéricos y las imágenes son ilustrativos; alcances y metas se acuerdan con el cliente.

Documentación: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
