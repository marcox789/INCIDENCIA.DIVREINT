# DIVREINT La Libertad — Dashboard

## Publicar en GitHub Pages

1. Descomprime este archivo ZIP en tu computadora.
2. Crea un repositorio en GitHub (por ejemplo, `divreint-la-libertad`).
3. Sube `index.html` y este `README.md` a la raíz del repositorio.
4. Abre **Settings → Pages**.
5. En **Build and deployment**, selecciona **Deploy from a branch**.
6. Selecciona la rama `main` y la carpeta `/(root)`, y guarda.
7. Espera a que GitHub Pages termine la publicación. La dirección aparecerá en la sección **Pages**.

## Importante

- El dashboard carga las bibliotecas Tailwind CSS, Chart.js y SheetJS desde CDN; al abrirlo necesita conexión a Internet.
- Si la aplicación almacena la base en el navegador, los datos no se comparten automáticamente entre distintos equipos o navegadores.
- La contraseña incrustada en una página HTML estática no ofrece autenticación segura real. No uses esta publicación para datos policiales sensibles o personales sin implementar autenticación del lado del servidor y almacenamiento protegido.
