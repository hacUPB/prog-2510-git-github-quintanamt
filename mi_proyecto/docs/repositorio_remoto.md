
---

## `repositorio_remoto.md`

```markdown
# Crear un Repositorio Remoto en GitHub y Sincronizarlo con el Local

GitHub es una plataforma en la nube que permite almacenar y colaborar en repositorios Git. Aquí se explica cómo crear un repositorio remoto y sincronizarlo con un repositorio local.

### Comandos Básicos

1. **Crear un repositorio remoto en GitHub:**
   - Usa la interfaz web de GitHub para crear un nuevo repositorio.
   - O usa la CLI de GitHub: `gh repo create <nombre_repositorio> --public --source=. --push --remote=upstream`.

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