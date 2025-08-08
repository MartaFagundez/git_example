# 📌 Comandos esenciales de Git

| #  | Comando                         | Descripción |
|----|---------------------------------|-------------|
| 1  | `git init`                      | Inicializa un nuevo repositorio en la carpeta actual. |
| 2  | `git clone <url>`               | Clona un repositorio remoto en tu máquina. |
| 3  | `git status`                    | Muestra el estado de los archivos (modificados, nuevos, en stage). |
| 4  | `git add <archivo>`             | Añade un archivo al área de *staging*. Usa `git add .` para todos. |
| 5  | `git commit -m "mensaje"`       | Crea un commit con los cambios en el *staging area*. |
| 6  | `git log`                        | Muestra el historial de commits. |
| 7  | `git diff`                       | Muestra las diferencias entre archivos modificados y el último commit. |
| 8  | `git branch`                     | Lista las ramas existentes. Con `git branch <nombre>` creas una nueva. |
| 9  | `git checkout <rama>`            | Cambia a una rama o commit específico. |
| 10 | `git checkout -b <rama>`         | Crea y cambia a una nueva rama en un paso. |
| 11 | `git merge <rama>`               | Fusiona la rama indicada con la rama actual. |
| 12 | `git pull`                       | Descarga y fusiona cambios del repositorio remoto. |
| 13 | `git push`                       | Sube tus commits locales al repositorio remoto. |
| 14 | `git remote -v`                  | Muestra las direcciones de los repositorios remotos configurados. |
| 15 | `git fetch`                      | Descarga cambios del remoto **sin** fusionarlos. |
| 16 | `git stash`                      | Guarda cambios temporales para limpiar el área de trabajo. |
| 17 | `git reset --hard <hash>`        | Restablece el repositorio al commit indicado, eliminando cambios. |
| 18 | `git revert <hash>`              | Crea un commit que revierte los cambios de un commit anterior. |

💡 **Tip:** Usa `git help <comando>` para ver la documentación oficial de cualquier comando.
