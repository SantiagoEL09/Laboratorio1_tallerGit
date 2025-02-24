# Laboratorio 1: Ejercicio Básico de Control de Versiones con Git

Este repositorio contiene un ejercicio básico para aprender los fundamentos de Git, incluyendo la configuración inicial, creación y fusión de ramas, uso de `.gitignore` y conexión con un repositorio remoto en GitHub.

## Objetivos

1.  **Objetivo 1. Configurar Git y crear repositorio:**
    ![git config --list](https://github.com/user-attachments/assets/f3da86ee-87fe-4413-b124-1f00d6ba65e5)

    ![#1](https://github.com/user-attachments/assets/54864b13-c56d-47df-a520-57627a66d5df)

2.  **Objetivo 2. Crear ramas:**
    ![#2](https://github.com/user-attachments/assets/49eac924-1402-431e-bbc0-41c86e80380a)

3.  **Objetivo 3. Crear ramas y modificar el archivo:**
    ![#3](https://github.com/user-attachments/assets/ece753c1-1b7e-4881-ad65-272dfa2b30b1)

4.  **Objetivo 4. Crear ramas y eliminar archivo:**
    ![#4](https://github.com/user-attachments/assets/217c4aab-0903-4870-a425-5c9941466141)

5.  **Objetivo 5. Crear ramas y eliminar el archivo:**
    ![#5](https://github.com/user-attachments/assets/614bd5c3-c169-477e-a4a8-06448a258cd1)

6.  **Objetivo 6. .gitignore:**
    ![#6](https://github.com/user-attachments/assets/44c09e79-2b37-499e-b1d2-353356fcea84)

>   [!NOTE]
> Al intentar implementrar .gitignore, hubo un error que se intento corregir, por eso hubo un commit adicional

8.  **Objetivo 6. Subir al repositorio remoto:**
    ![#7](https://github.com/user-attachments/assets/d9834d5a-48c4-43e3-acad-c0ef1540289b)

    ![#8](https://github.com/user-attachments/assets/8d49c920-5529-4a0f-8015-f91310c835f5)

9. **Hitorial de comandos:**
   ![image](https://github.com/user-attachments/assets/9d736e52-5101-4552-9357-a1795aee641a)

  
## Comandos Utilizados

* `git init`: Inicializa un nuevo repositorio Git.
* `git config --global user.name "Tu Nombre"`: Configura el nombre de usuario de Git.
* `git config --global user.email "tu@email.com"`: Configura el correo electrónico de Git.
* `git add .`: Agrega todos los cambios al área de preparación.
* `git commit -m "Mensaje del commit"`: Crea un nuevo commit con un mensaje descriptivo.
* `git branch <nombre_de_la_rama>`: Crea una nueva rama.
* `git switch <nombre_de_la_rama>`: Cambia a la rama especificada.
* `git merge <nombre_de_la_rama>`: Fusiona la rama especificada con la rama actual.
* `git remote add origin <URL_del_repositorio_remoto>`: Agrega un repositorio remoto.
* `git push -u origin <nombre_de_la_rama>`: Sube la rama al repositorio remoto y configura el seguimiento.
* `git push`: Sube los cambios al repositorio remoto.
* `git status`: Muestra el estado del repositorio.
* `git log`: Muestra el historial de commits.

## Pasos Realizados

1.  **Configuración inicial:**
    * Se inicializó un repositorio local con `git init`.
    * Se configuró el nombre de usuario y correo electrónico.
2.  **Creación de ramas:**
    * Se crearon varias ramas para simular diferentes funcionalidades.
3.  **Modificación de archivos:**
    * Se realizaron cambios en archivos en ramas específicas y se fusionaron a la rama principal.
4.  **Eliminación de archivos:**
    * Se eliminaron archivos en ramas específicas y se fusionaron los cambios.
5.  **.gitignore:**
    * Se creó un archivo `.gitignore` para ignorar archivos y directorios innecesarios.
6.  **Conexión remota:**
    * Se conectó el repositorio local con un repositorio remoto en GitHub.
    * Se subieron los cambios al repositorio remoto.

## Conclusión

Este ejercicio proporciona una introducción práctica a los conceptos básicos de Git y cómo utilizarlos en un flujo de trabajo de desarrollo simple.
