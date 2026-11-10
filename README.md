# plataforma_educativagoo

Sitio estático con `index.html` y las imágenes en la raíz del repositorio.

Netlify usa el archivo `netlify.toml` de la raíz para publicar esta carpeta
(`publish = "."`) sin ejecutar un comando de compilación (`command = ""`).
No se genera ni se necesita una carpeta `_site`.

Si un despliegue indica que falta `_site`, comprueba que está desplegando una
revisión que incluya este archivo `netlify.toml` y que el directorio base de
Netlify apunte a la raíz del repositorio. Después, vuelve a desplegar esa revisión.
