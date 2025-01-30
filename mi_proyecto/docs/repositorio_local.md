#AI
Crear un repositorio remoto en GitHub y sincronizarlo con el repositorio local
Para crear un repositorio remoto en GitHub y sincronizarlo con tu repositorio local, sigue estos pasos:

Crear un repositorio en GitHub:

Inicia sesión en GitHub.

Haz clic en "New" para crear un nuevo repositorio.

Asigna un nombre al repositorio y elige la visibilidad (público o privado).

No inicialices el repositorio con un archivo README si ya tienes un repositorio local.

Conectar el repositorio local con el remoto:

Copia la URL del repositorio remoto (HTTPS o SSH).

En tu consola, navega al directorio del repositorio local.

Usa el comando git remote add para vincular el repositorio local con el remoto:

bash
Copy
git remote add origin [URL_del_repositorio]
Por ejemplo:

bash
Copy
git remote add origin https://github.com/usuario/repositorio.git
Subir cambios al repositorio remoto:

Usa git push para enviar los commits locales al repositorio remoto:

bash
Copy
git push -u origin main
(Nota: main es la rama principal. Si usas master, cambia el nombre).

Sincronizar cambios futuros:

Para subir cambios adicionales, usa:

bash
Copy
git add .
git commit -m "Nuevos cambios"
git push
Para descargar cambios del repositorio remoto, usa:

bash
Copy
git pull
Con estos pasos, habrás creado y sincronizado un repositorio local con uno remoto en GitHub.
