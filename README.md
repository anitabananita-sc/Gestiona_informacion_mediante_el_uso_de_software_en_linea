# Gestiona_informacion_mediante_el_uso_de_software_en_linea
Repositorio para practicas de la materia gestiona informacion
GitHub es una plataforma en la nube que permite alojar, gestionar y colaborar en proyectos de software utilizando Git, un sistema de control de versiones.

En términos simples, GitHub sirve para:

Guardar código de forma segura
Registrar todos los cambios que se realizan en un proyecto
Trabajar en equipo sin perder información ni sobrescribir el trabajo de otros
Cada proyecto en GitHub se almacena en lo que se llama un repositorio, que contiene el código, su historial de versiones y herramientas para coordinar el trabajo entre personas.
Principales Usos de GitHub

GitHub se utiliza para alojar código fuente, gestionar versiones de proyectos, colaborar en equipos de desarrollo, documentar proyectos y automatizar flujos de trabajo como pruebas y despliegues mediante GitHub Actions.

Diferencias entre Git y GitHub

Git es una herramienta de control de versiones que se instala localmente para gestionar el historial de cambios de un proyecto. GitHub, por otro lado, es una plataforma en línea que utiliza Git para alojar repositorios y facilitar la colaboración con funcionalidades adicionales como pull requests, issues y GitHub Pages.

Características Clave de GitHub

Repositorios: Espacios donde se almacena el contenido de un proyecto. Pueden ser públicos o privados.

Colaboración: Herramientas como pull requests para revisar cambios y issues para rastrear errores o ideas.

Automatización: Con GitHub Actions, puedes configurar flujos de trabajo automatizados para pruebas y despliegues.

GitHub Pages: Permite crear sitios web estáticos directamente desde un repositorio.

Ventajas de Usar GitHub

Control de versiones eficiente: Guarda el historial completo del proyecto, facilitando revertir cambios si es necesario.

Colaboración en tiempo real: Ideal para equipos pequeños o grandes.

Red social para desarrolladores: Permite seguir a otros programadores y contribuir a proyectos de código abierto.

Automatización: Simplifica tareas repetitivas como pruebas y despliegues.

GitHub no solo es una herramienta para alojar código, sino un ecosistema que fomenta la colaboración, la automatización y el crecimiento profesional. Es una plataforma imprescindible para cualquier desarrollador que busque trabajar de manera eficiente y en equipo.

DIFERENCIAS entre repoaitory commit branch pull request fork

REPOSITORY:
Un repositorio guarda todos los archivos de tu proyecto en un solo lugar. En lugar de tener el código en un ordenador portátil, las imágenes en un hilo de chat y las notas en un correo electrónico, todo se encuentra en un solo lugar. De esta manera, nunca perderás de vista lo que es importante, y todo tu equipo sabrá siempre dónde encontrar los datos relevantes.

COMMIT:
Un commit en Git es como un punto de guardado en un videojuego. Básicamente, le dices a Git que quieres guardar el estado actual de tus archivos para poder volver a determinado punto si lo necesitas.

BRACH:
es una ramificacion para trabajar es desarrollos sin afectar del proyecto principal
Cómo crear una nueva branch llamada ‘’desarrollo’’;
git checkout -b desarrollo
Cómo navegar entre la branch principal ‘’main’’ y la branch “desarrollo”a través del comando git switch;
git switch " nombre de la rama que deseamos
Cómo enviar todas las modificaciones hechas en la branch “desarrollo” a la branch principal “main” con el merge.
git switch main
git merge desarrollo.
Una branch, o rama, es una línea de desarrollo independiente dentro de un repositorio de Git. Te permite trabajar en cambios o nuevas funcionalidades sin afectar la rama principal del proyecto, generalmente llamada "main" o "master". Esto es muy útil para desarrollar nuevas características, corregir errores o experimentar de manera aislada.

PULL REQUEST:
En esencia, un Pull Request es una solicitud formal para integrar cambios de código (desde una rama secundaria o branch) en otra rama (usualmente la principal, como main o develop). Sin embargo, es mucho más que eso:
Es una oportunidad para la revisión colaborativa: Varios ojos revisan el código propuesto.
Es un mecanismo de aseguramiento de la calidad: Ayuda a detectar errores, inconsistencias o mejoras potenciales antes de la integración.
Es un foro de discusión técnica: Permite debatir sobre la implementación, la arquitectura y la eficiencia del código.
Es una herramienta de aprendizaje y mentoring: Los desarrolladores más experimentados pueden guiar a los más nuevos, y todos aprenden de las revisiones.

Fork:
 Básicamente sirve para crear una copia de un repositorio en tu cuenta de usuario. Ese repositorio copiado será básicamente un clon del repositorio desde el que se hace el fork, pero a partir de entonces el fork vivirá en un espacio diferente y podrá evolucionar de manera distinta, a tu propio cargo.
