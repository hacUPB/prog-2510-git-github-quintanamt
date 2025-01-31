
---

## `repositorio_remoto.md`


# Crear un Repositorio Remoto en GitHub y Sincronizarlo con el Local

GitHub es una plataforma en la nube que permite almacenar y colaborar en repositorios Git. Aquí se explica cómo crear un repositorio remoto y sincronizarlo con un repositorio local.

### Comandos Básicos

1. **Crear un repositorio remoto en GitHub:**
   - Usa la interfaz web de GitHub para crear un nuevo repositorio.


2. **Vincular un repositorio local con uno remoto:**
   - `git remote add origin <url_repositorio>`: Asocia el repositorio local con el remoto.
   - `git remote -v`: Verifica la URL del repositorio remoto.



3. **Subir cambios al repositorio remoto:**
   - `git push origin main`: Sube los commits locales al repositorio remoto.

![Imagen](../images/2.png)

4. **Clonar un repositorio remoto:**
   - `git clone <url_repositorio>`: Descarga un repositorio remoto en tu computadora.

![Imagen](../images/1.png)

5. **Sincronizar cambios:**
   - `git pull origin main`: Descarga los cambios del repositorio remoto y los fusiona con el local.

![Imagen](../images/2.png)
