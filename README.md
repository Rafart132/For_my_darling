# Para ti — Regalo de cumpleaños

Página en verde y amarillo con cinco imágenes, una carta y texto que se revela al bajar. No requiere instalar programas, compilar código ni conectarse a ChatGPT.

## Archivos

- `index.html`: la página, sus estilos y las animaciones.
- `assets/`: los cinco dibujos y fotografías.
- `.nojekyll`: permite que GitHub Pages sirva los archivos directamente.

## Verla en tu computadora

Descomprime el ZIP y abre `index.html` en tu navegador. Conserva la carpeta `assets` junto a ese archivo.

## Subirla a GitHub

1. Crea un repositorio, por ejemplo `para-ti`. Elige su visibilidad teniendo en cuenta que un repositorio público deja visibles las imágenes y la carta.
2. Abre el repositorio y elige **Add file → Upload files**. En un repositorio vacío puedes usar el enlace **uploading an existing file**.
3. Sube el contenido descomprimido: `index.html`, `assets`, `README.md` y `.nojekyll`. El archivo `index.html` debe quedar en la raíz del repositorio, junto a `assets`. Sube los archivos extraídos, no el ZIP.
4. Guarda la carga con **Commit changes** en la rama principal.

## Publicarla con GitHub Pages

1. En el repositorio, abre **Settings → Pages**.
2. En **Build and deployment → Source**, elige **Deploy from a branch**.
3. Selecciona la rama **main** (o la que contenga tus archivos), la carpeta **/(root)** y pulsa **Save**.
4. Cuando finalice la publicación, abre el enlace que muestre esa misma sección.

Con GitHub Free, Pages está disponible para repositorios públicos. Publicar con Pages normalmente deja la web pública: un repositorio privado no garantiza que la página también sea privada. Este paquete no incluye contraseña ni control de acceso.

## Cambiar texto, colores o imágenes

Abre `index.html` en un editor de texto. Los colores están al comienzo, en `:root`; las frases aparecen dentro del contenido HTML. Las imágenes se cargan desde `assets/`. Si sustituyes una, actualiza también su descripción (`alt`) y sus dimensiones (`width` y `height`).

## Ayuda oficial

- [Subir archivos a un repositorio](https://docs.github.com/es/repositories/working-with-files/managing-files/adding-a-file-to-a-repository)
- [Configurar GitHub Pages](https://docs.github.com/es/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)
