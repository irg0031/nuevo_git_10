# nuevo_git_10
# Definición de Comandos Git y Archivos Relacionados

- **git init**: Inicializa un nuevo repositorio local de Git en el directorio actual. Para comenzar el control de versiones en un proyecto nuevo o existente que no está bajo Git.  
- **git clone**: Crea una copia local completa de un repositorio remoto existente. Para obtener una copia de un proyecto de GitHub o Bitbucket y comenzar a contribuir.  
- **git add**: Añade archivos a la zona de preparación (staging area) para el próximo commit. Prepara cambios específicos para ser guardados en el historial.  
- **git commit**: Registra una instantánea de los cambios preparados en el historial del repositorio. Guardar de forma permanente el progreso del trabajo realizado. Ejemplo: `git commit -m "mensaje descriptivo"`.  
- **git status**: Muestra el estado actual del directorio de trabajo y de la zona de preparación. Verifica qué archivos han sido modificados o preparados antes de un commit.  
- **git branch**: Lista, crea o elimina ramas dentro del repositorio. Gestiona diferentes líneas de desarrollo de forma aislada. Ejemplo: `git branch nombre-de-rama`.  
- **git switch**: Cambia de rama de una forma más intuitiva y clara que `checkout`. Recomendado en entornos modernos y educativos.  
- **git checkout**: Cambia entre ramas o restaura archivos del árbol de trabajo (método clásico). Navegar entre diferentes ramas existentes.  
- **git merge**: Fusiona la historia de una rama específica en la rama actual. Integrar características completas (features) en la rama principal (`main`).  
- **git fetch**: Descarga los últimos cambios, ramas y un historial actualizado desde un repositorio remoto. Permite inspeccionar cambios de forma segura y mantener el repositorio local sincronizado.  
- **git push**: Envía los commits locales al repositorio remoto. Comparte los cambios realizados localmente con el equipo en la nube. Ejemplo: `git push origin`.  
- **git pull**: Descarga y fusiona los cambios del repositorio remoto en la rama actual. Mantener el repositorio local actualizado con el trabajo de otros colaboradores.  
- **git rebase**: Vuelve a aplicar commits sobre otra base de rama para mantener un historial lineal. Mantiene las ramas actualizadas con la rama principal sin crear commits de merge.  
- **git log**: Muestra el historial de commits para la rama activa. Permite revisar la evolución del proyecto y quién realizó cada cambio. Ejemplo: `git log --oneline --graph`.  
- **README.md**: Archivo de texto que presenta y explica el propósito de un proyecto. Primer archivo a crear para documentar instalación, uso y colaboración.  
- **markdown**: Lenguaje de marcado usado para dar formato al `README.md`.  
- **.git**: Subdirectorio que contiene todos los archivos necesarios del repositorio (esqueleto). Creado automáticamente por Git; no debe ser modificado manualmente por el usuario.
