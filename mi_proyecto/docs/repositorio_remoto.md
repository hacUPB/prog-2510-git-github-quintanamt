#AI
Crear un repositorio remoto en GitHub y sincronizarlo con el repositorio local
Para crear un repositorio remoto en GitHub y sincronizarlo con tu repositorio local, sigue estos pasos:

Crear un repositorio en GitHub:

Inicia sesión en GitHub.

Haz clic en "New" para crear un nuevo repositorio.

Asigna un nombre al repositorio y elige la visibilidad (público o privado).

2. **Vincular un repositorio local con uno remoto:**
   - `git remote add origin <url_repositorio>`: Asocia el repositorio local con el remoto.
   - `git remote -v`: Verifica la URL del repositorio remoto.

3. **Subir cambios al repositorio remoto:**
   - `git push origin main`: Sube los commits locales al repositorio remoto.

4. **Clonar un repositorio remoto:**
   - `git clone <url_repositorio>`: Descarga un repositorio remoto en tu computadora.

5. **Sincronizar cambios:**
   - `git pull origin main`: Descarga los cambios del repositorio remoto y los fusiona con el local.

### Ejemplo de Uso

```bash
# Crear repositorio remoto
gh repo create mi_proyecto --public --source=. --push --remote=upstream

# Vincular repositorio local con remoto
git remote add origin https://github.com/usuario/mi_proyecto.git

# Subir cambios
git push origin main

# Clonar un repositorio
git clone https://github.com/usuario/mi_proyecto.git

# Sincronizar cambios
git pull origin main