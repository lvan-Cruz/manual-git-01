 CONCEPTOS DE GIT

## 1. ¿Qué es Git?

**Git es un sistema de control de versiones distribuido que permite registrar, administrar y controlar los cambios realizados en los archivos de un proyecto.**

**Es una herramienta muy utilizada en el desarrollo de software porque permite trabajar de manera organizada y facilita la colaboración entre varios desarrolladores.**

---

## 2. ¿Para qué sirve Git?

Git sirve principalmente para:

* Guardar diferentes versiones de un proyecto.
* Registrar los cambios realizados en los archivos.
* Recuperar versiones anteriores.
* Trabajar en equipo.
* Crear ramas para desarrollar nuevas funcionalidades.
* Unir los cambios realizados por diferentes personas.
* Mantener un historial del proyecto.


## 3. Repositorio

Un repositorio es el espacio donde Git almacena los archivos del proyecto y el historial de cambios realizados.

Puede ser:

* **Repositorio local:** se encuentra en el computador del desarrollador.
* **Repositorio remoto:** se encuentra en una plataforma como GitHub, GitLab o Bitbucket.

---

## 4. Git y GitHub

Aunque están relacionados, Git y GitHub no son lo mismo.

### Git

Es el sistema de control de versiones que se instala y utiliza en el computador.

### GitHub

Es una plataforma en línea que permite almacenar repositorios Git y colaborar con otros desarrolladores.


## 7. Commit

Un **commit** es un registro que guarda los cambios realizados en el proyecto.

Ejemplo:

```bash
git commit -m "Agregada pantalla de inicio"
```

Es recomendable utilizar mensajes claros para identificar qué cambios se realizaron.

---

## 8. Branch o Rama

Una rama permite trabajar en una versión independiente del proyecto sin afectar directamente la rama principal.

Por ejemplo:

```bash
git branch nueva-funcionalidad
```

Para crear una rama y cambiarse a ella:

```bash
git checkout -b nueva-funcionalidad
```

También se puede utilizar:

```bash
git switch -c nueva-funcionalidad
```

---

## 9. Main

`main` normalmente es la rama principal de un proyecto.

En ella se suele mantener una versión estable del código.

Para cambiar a la rama principal:

```bash
git switch main
```

## 12. Push

`git push` permite enviar los commits realizados en el repositorio local hacia un repositorio remoto.

Ejemplo:

```bash
git push origin main


## 25. Conclusión

Git es una herramienta fundamental para el desarrollo de software porque permite controlar las diferentes versiones de un proyecto y organizar el trabajo de los desarrolladores.

Con conceptos como **repositorio, commit, branch, merge, push, pull y staging area**, es posible administrar proyectos de manera más segura, organizada y eficiente.

# Resumen
Git es una herramienta que permite controlar y organizar las diferentes versiones de un proyecto. Facilita el trabajo en equipo y permite guardar, consultar y recuperar cambios realizados en los archivos.

Entre sus comandos básicos se encuentran git init para crear un repositorio, git add para preparar cambios, git commit para guardarlos, git status para revisar el estado del proyecto, git push para enviar cambios a un repositorio remoto y git pull para obtener cambios de otros usuarios.

En general, Git ayuda a trabajar de forma más segura, organizada y eficiente, siendo una herramienta fundamental para el desarrollo de software.