## 📚 Bitácora de Aprendizaje — Resumen Detallado

---

## ✅ 1) Git y GitHub — Manejo de versiones y flujo colaborativo

- Aprendiste a clonar repositorios desde GitHub a tu PC usando `git clone` y `gh repo clone`.
- Entendiste la diferencia entre usar **HTTPS** y **SSH**, y por qué SSH es más seguro y práctico.
- Configuraste llaves SSH (`id_ed25519`), usando `ssh-agent` y `ssh-add` para evitar escribir la passphrase cada vez.
- Probaste tu conexión con `ssh -T git@github.com` y verificaste tu usuario correcto.
- Cambiaste URLs remotas de HTTPS a SSH con `git remote set-url origin ...` para resolver errores de permisos.
- Eliminaste credenciales viejas desde el **Administrador de Credenciales de Windows**.
- Usaste `git branch` y `git checkout` para trabajar en ramas correctas.
- Ejecutaste `git pull origin main` para traer cambios del remoto a local.
- Resolvieron errores comunes como ramas sin upstream y conflictos de merge.
- Usaste **GitHub CLI (`gh`)** para autenticarte, subir tu llave SSH y crear repos desde la terminal (`gh repo create`).
- Aprendiste a manejar carpetas con nombre que empieza con guion usando `cd ./-carpeta` o `cd -- -carpeta`.

---

## ✅ 2) Creación de repositorio de presentación — Pequeña página usando HTML + CSS

- Creaste un repositorio con tu nombre de usuario que se convierte en la portada del perfil de GitHub.
- Estructuraste un archivo `index.html` con `<head>` bien formado, meta etiquetas, Bootstrap y favicon.
- Organizaste el `<body>` con contenedores, botones y enlaces a LinkedIn, tu máster y la hackathon.
- Aprendiste la diferencia entre `<img src=\"...\">` y `background-image` en CSS.
- Corregiste rutas absolutas a rutas relativas (`assets/perfil.jpg`).
- Usaste `border-radius` y `box-shadow` para dar estilo redondeado a la imagen de perfil.
- Aplicaste animaciones CSS (`@keyframes Gradient`) y efectos `.shake` para estilo dinámico.

---

## ✅ 3) Uso de Dependabot para monitoreo de los archivos del repositorio

- Verificaste tu SDK con `dotnet --list-sdks` y comprendiste la diferencia entre SDK y runtime.
- Usaste `dotnet add package` para agregar `Newtonsoft.Json` después de corregir un error de nombre.
- Interpretaste advertencias de seguridad (`NU1903`) y buscaste versiones seguras.
- Restauraste paquetes y entendiste la actualización de tu `.csproj`.
- Corregiste errores de configuración en `dependabot.yml` (campo `package-ecosystem`).
- Configuraste Dependabot: esta herramienta permite monitorear tu repositorio y los archivos que se suben, entregar alertas de seguridad, además de notificar y crear un pull request automáticamente con las correcciones necesarias si detecta que no se trabaja con la versión más actualizada.

---

## ✅ 5) Documentación clara y profesional

- Redactaste un `README.md` en inglés bien estructurado: **About us**, **How to get involved**, **Useful resources**, **Fun fact** y **Connect**.
- Explicaste cómo nació tu proyecto (hackathon + Celerix + Platzi).
- Usaste buenas prácticas de Markdown para mantener la presentación clara y amigable.
- Configuraste para que en este perfil se muestre de manera automática tu actividad más reciente en GitHub.
- Creaste una organización (con fines educativos) a la cual también se le realizó su respectivo documento de presentación.
- Introducción a los documentos `.gitignore`: aprendiste que se pueden utilizar para definir qué archivos (basado en su extensión) o qué carpetas (basadas en su ubicación) no deben subirse al repositorio cuando no son necesarias para su funcionamiento.

---

