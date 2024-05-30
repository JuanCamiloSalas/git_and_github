
# Introducción a Git

## ¿Por qué usar un sistema de control de versiones como Git?
1. Historial de Cambios: Permite guardar un registro completo y detallado de todas las modificaciones, facilitando revertir errores y rastrear cambios.
2. Colaboración: Permite a múltiples desarrolladores trabajar en paralelo mediante ramas (branches) y facilita la integración de cambios sin conflictos.
3. Ramas Flexibles: Soporta diversos flujos de trabajo, permitiendo desarrollo paralelo y gestión eficiente de nuevas funcionalidades y correcciones.
4. Eficiencia: Realiza operaciones rápidas localmente sin necesidad de conexión a internet y maneja proyectos grandes de manera eficiente.
5. Integración y Automatización: Se integra con herramientas de CI/CD, permitiendo automatizar pruebas y despliegues, y facilita revisiones de código.
6. Distribución y Seguridad: Al ser distribuido, cada copia del repositorio actúa como respaldo, permitiendo trabajar sin conexión y sincronizar cambios más tarde.
7. Popularidad: Amplio soporte y compatibilidad con numerosas herramientas, gracias a su popularidad y una comunidad activa.

## ¿Qué es Git?
Git es un sistema de control de versiones distribuido que te permite registrar los cambios que haces en tus archivos y volver a versiones anteriores si algo sale mal. Fue diseñado por Linus Torvalds para garantizar la eficiencia y confiabilidad del mantenimiento de versiones de aplicaciones que tienen un gran número de archivos de código fuente.

Git está optimizado para guardar cambios de forma incremental.

Permite contar con un historial, regresar a una versión anterior y agregar funcionalidades.

Lleva un registro de los cambios que otras personas realicen en los archivos.

Git fue diseñado para operar en un entorno Linux. Actualmente, es multiplataforma, es decir, es compatible con Linux, MacOS y Windows. En la máquina local se encuentra Git, se utiliza bajo la terminal o línea de comandos y tiene comandos como merge, pull, add, commit y rebase, entre otros.

### Para qué proyectos sirve Git
Con Git se obtiene una mayor eficiencia usando archivos de texto plano, ya que con archivos binarios no puede guardar solo los cambios, sino que debe volver a grabar el archivo completo ante cada modificación, por mínima que sea, lo que hace que incremente demasiado el tamaño del repositorio.

“Guardar archivos binarios en el repositorio de Git no es una buena práctica, únicamente deberían guardarse archivos pequeños (como logos) que no sufran casi modificaciones durante la vida del proyecto. Los binarios deben guardarse en un CDN”.

### Características de Git

Git te ayuda a trabajar de manera más organizada y colaborativa en proyectos de desarrollo de software. Estas son algunas de sus principales características:

- **Control de versiones:** Git almacena la información como un conjunto de archivos. Te permite llevar un registro de los cambios que haces en tus archivos, lo que significa que siempre puedes volver a versiones anteriores si algo sale mal.

- **Ramificación:** Puedes crear ramas en tu proyecto, lo que te permite trabajar en diferentes características o aspectos del mismo sin afectar el trabajo de los demás.

- **Colaboración:** En Git, varias personas pueden trabajar en diferentes aspectos del proyecto al mismo tiempo.

- **Seguridad:** No existen cambios, corrupción en archivos o cualquier alteración sin que Git lo sepa. Git cuenta con 3 estados en los que es posible localizar archivos: Staged, Modified y Committed.

- **Flexibilidad:** Casi todo en Git es local. Es difícil que se necesiten recursos o información externos, basta con los recursos locales con los que cuenta.

- **Comandos:** Git tiene una sintaxis de comandos bastante sencilla y fácil de aprender, lo que lo hace accesible incluso para principiantes en programación.

### ¿Qué es un sistema de control de versiones?
El SCV o VCS (por sus siglas en inglés) es un sistema que registra los cambios realizados sobre un archivo o conjunto de archivos a lo largo del tiempo, de modo que puedas llevar el historial del ciclo de vida de un proyecto, comparar cambios a lo largo del tiempo, ver quién los realizó o revertir el proyecto entero a un estado anterior.

Cualquier tipo de archivo que se encuentre en un ordenador puede ponerse bajo control de versiones.
