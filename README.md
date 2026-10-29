# CPK Ingeniería · Canagro / El Gauchito

Propuesta inicial de trabajo conjunto. Revisión 03 · 29/10/2026.

## Contenido

- `index.html`: presentación completa, adaptable a celular e impresión.
- `.nojekyll`: indica a GitHub Pages que publique los archivos sin procesarlos con Jekyll.
- `README.md`: instrucciones para publicar.

Las imágenes y los estilos están incluidos en `index.html`. No requiere instalación, compilación, servidor de aplicación ni claves. Los enlaces a fuentes técnicas se consultan en los sitios de los fabricantes.

## Publicar desde la web de GitHub

1. Descomprimí el ZIP en tu computadora.
2. Creá un repositorio. Nombre sugerido: `cpk-canagro` (podés elegir otro).
3. Dentro del repositorio, elegí **Add file → Upload files**.
4. Subí los archivos de esta carpeta directamente en la raíz del repositorio. Debe verse `index.html` al abrir el repositorio, sin entrar en otra carpeta. No subas el ZIP como sustituto de los archivos.
5. Confirmá la carga con **Commit changes**.
6. Entrá en **Settings → Pages**.
7. En **Build and deployment → Source**, seleccioná **Deploy from a branch**.
8. Seleccioná la rama que contiene los archivos (habitualmente `main`) y la carpeta **/ (root)**. Presioná **Save**.
9. Esperá a que termine la publicación y abrí la dirección que GitHub muestre en esa misma pantalla. También podés revisar el resultado de la publicación en **Actions**.

Dirección habitual para un repositorio de proyecto: `https://TU-USUARIO.github.io/NOMBRE-DEL-REPOSITORIO/`.
Usá el enlace que devuelva GitHub como referencia definitiva.

## Si no se carga `.nojekyll`

El archivo ya está incluido en el ZIP y tiene contenido para facilitar su carga. Si tu explorador no lo muestra, activá la visualización de archivos ocultos. También podés crearlo dentro de GitHub mediante **Add file → Create new file**, con el nombre exacto `.nojekyll` y el texto `HTML estático CPK`. El nombre lleva punto inicial y no lleva `.txt` al final.

## Verificación después de publicar

- La portada debe indicar Canagro / El Gauchito y revisión 03.
- Deben abrirse los tres frentes desde la navegación superior.
- La imagen del robot y las dos ilustraciones termográficas deben verse sin descargas externas.
- La sección PQCDS debe incluir la tabla numérica «cumple / no cumple».
- El botón **Imprimir / PDF** debe abrir el diálogo de impresión del navegador. Para guardar un PDF, seleccioná el destino correspondiente en ese diálogo.
- Si aparece un error 404, revisá que `index.html` esté en la raíz y que la rama/carpeta configuradas sean las que contienen los archivos. Verificá el estado del despliegue en Actions antes de volver a cargar.

## Actualizar la propuesta

Reemplazá `index.html` por la versión actualizada y confirmá el cambio en la misma rama. GitHub Pages publicará ese cambio según la configuración del repositorio. No cambies el nombre del archivo de inicio.

## Alcance del documento

Los ejemplos numéricos son ilustrativos. Las funciones de catálogo no certifican la configuración instalada en Canagro. Las imágenes generadas son ilustrativas y no representan mediciones reales. Los alcances y metas se acuerdan con el cliente.

## Documentación oficial

https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site
