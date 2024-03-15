# GIT

## ¿Qué es GIT?
- Un sistema de control de versiones distribuido, rápido y escalable que ayuda a crear el código con diferentes versiones y un historial de cambios

## ¿Por que usar GIT?
- Git permite rastrear y documentar cada cambio realizado en el código a lo largo del tiempo.

## Ventajas de usar Git

- **Control de Versiones:**
  - Permite rastrear cambios en el código y revertir a versiones anteriores si es necesario.

- **Colaboración:**
  - Facilita el trabajo colaborativo permitiendo a múltiples desarrolladores trabajar en el mismo proyecto.

- **Ramas (Branches):**
  - Posibilidad de trabajar en ramas independientes para desarrollar nuevas características sin afectar la rama principal.

- **Distribuido:**
  - Cada desarrollador tiene una copia completa del repositorio, lo que facilita el trabajo sin conexión.

- **Historial Detallado:**
  - Proporciona un historial detallado de cambios, quién los realizó y cuándo.

## Comandos Básicos de Git

- **git init:**
   - Inicia un nuevo repositorio Git en el directorio actual.

- **git clone [URL]:**
   - Clona un repositorio remoto en tu máquina local.

- **git add [archivo(s)]:**
   - Agrega cambios al área de preparación (staging) para ser incluidos en el próximo commit.

- **git commit -m "mensaje":**
   - Crea un nuevo commit con los cambios en el área de preparación y añade un mensaje descriptivo.

- **git status:**
   - Muestra el estado actual del repositorio, incluyendo archivos sin seguimiento, modificados y en el área de preparación.

- **git log:**
   - Muestra un historial de commits con información detallada.

- **git pull:**
   - Obtiene cambios desde un repositorio remoto y los fusiona con la rama actual.

- **git push:**
   - Envía commits locales a un repositorio remoto.

- **git branch:**
   - Muestra una lista de ramas y resalta la rama actual.

- **git branch [nombre_rama]:**
    - Crea una nueva rama.

- **git checkout [nombre_rama]:**
    - Cambia a la rama especificada.

- **git merge [nombre_rama]:**
    - Fusiona la rama especificada con la rama actual.

- **git remote -v:**
    - Muestra las URLs de los repositorios remotos configurados.

- **git fetch:**
    - Descarga cambios desde un repositorio remoto, pero no los fusiona con tu rama actual.

- **git diff:**
    - Muestra las diferencias entre los cambios sin preparar y la última versión guardada.

## Comandos Básicos de Git
- **git reflog:**
    -Muestra un registro detallado de las referencias de Git, útil para recuperar cambios perdidos.

- **git stash:**
    -Guarda temporalmente los cambios locales sin commit para trabajar en otra tarea.

- **git submodule:**
    -Gestiona submódulos dentro del repositorio principal.

## Tipos de Usuarios en Git

En Git, hay varios tipos de usuarios que interactúan con un repositorio. Estos roles definen los niveles de acceso y las responsabilidades que cada usuario tiene en el proyecto.

### 1. Usuario Anónimo:
- Accede al repositorio sin autenticación.

### 2. Colaborador:
- Miembro del equipo que contribuye al desarrollo del proyecto.

### 3. Propietario del Repositorio:
- Persona o equipo que posee el repositorio.

### 4. Revisor:
-  Responsable de revisar y aprobar cambios propuestos.

### 5. Contribuidor Externo:
- Persona externa que realiza contribuciones ocasionales.

### 6. Administrador del Sistema:
- Persona encargada de la administración del sistema que aloja el repositorio.

### 7. Usuario de Solo Lectura:
- Tiene permisos solo de lectura en el repositorio.

### 8. Desarrollador Principal:
- Miembro clave del equipo, a menudo responsable de la toma de decisiones importantes.
