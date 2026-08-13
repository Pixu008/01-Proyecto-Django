# 01-Proyecto-Django

## Andres Martinez

A continuación, se detalla la secuencia de comandos de Git junto con la descripción de la función de cada uno:

*   **Verificar la configuración:** Muestra una lista con toda la configuración global actual de Git en tu equipo.
    ```bash
    git config --global --list
    ```

*   **Configurar el nombre de usuario:** Define el nombre que aparecerá como autor de los cambios (commits) que realices.
    ```bash
    git config --global user.name Pixu008
    ```

*   **Configurar el correo electrónico:** Vincula una dirección de correo a tus commits para que queden asociados a tu cuenta.
    ```bash
    git config --global user.email andresmartinez1307a@gmail.com
    ```

*   **Preparar los cambios (Guardar):** Añade todos los archivos nuevos, modificados o eliminados al área de preparación (*staging area*) listos para ser guardados.
    ```bash
    git add .
    ```

*   **Confirmar los cambios (Commit):** Guarda permanentemente los cambios preparados en el historial local de tu proyecto, acompañados de un mensaje que describe lo que hiciste.
    ```bash
    git commit -m "Readme modificado, nombre agregado"
    ```

*   **Subir al repositorio remoto:** Envía tus commits locales a la rama principal (`main`) del repositorio en la nube (`origin`, por ejemplo en GitHub o GitLab).
    ```bash
    git push origin main
    ```