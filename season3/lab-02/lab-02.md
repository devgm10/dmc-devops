## Taller 2: Creación de Issues (Epic, Story, Task, Bug)

### 📌 Objetivo: 

Aprender a crear los diferentes tipos de "issues" (incidencias) en Jira y entender su jerarquía.
Crearemos la estructura fundamental de nuestro Espacio.

### 📄 Conceptos Clave: 

```bash
    -   Epic (Épica): Una gran iniciativa o cuerpo de trabajo que se descompone en historias.
    -   Story (Historia de Usuario): Un requerimiento que aporta valor al usuario.
    -   Task (Tarea): Una actividad técnica específica necesaria para el Espacio. Es una acción concreta.
    -   Bug (Error): Un defecto que impide que el software funcione como se espera.
```

### Paso 01: Crear las Épicas

```bash
    1.  Ve al Backlog y activa el panel de Épicas. (O pulsa el botón "e" para abrirlo)
    2.  Crea las 3 épicas:
        -   Épica 1:
            (*) Nombre: Estructura y Contenido Base de la Documentación
            
            (*) Descripción: Esta épica agrupa todo el trabajo necesario para crear el esqueleto y el
                contenido fundamental de nuestra documentación. El objetivo es que cualquier persona
                que llegue al Espacio pueda entender de qué se trata y cómo empezar a usarlo
                rápidamente.

        -   Épica 2:
            (*) Nombre: Guías para Contribuidores y Desarrolladores
            (*) Descripción: Esta épica se centra en crear los recursos necesarios para que otros
                desarrolladores puedan contribuir al Espacio de manera efectiva y estandarizada. Cubre
                desde cómo configurar el entorno hasta las guías de estilo y el proceso de Pull Request.

        -   Épica 3:
            (*) Nombre: Automatización y Despliegue de la Documentación
            (*) Descripción: El objetivo de esta épica es establecer un sistema automatizado que
                construya y publique el sitio de la documentación cada vez que se realizan cambios,
                asegurando que siempre esté actualizada sin intervención manual.
```

<p align="center">
  <img src="./img/lab-02/answer-01A.png" alt="answer-01A" width="900">
</p>

<p align="center">
  <img src="./img/lab-02/answer-01B.png" alt="answer-01B" width="900">
</p>

<p align="center">
  <img src="./img/lab-02/answer-01C.png" alt="answer-01C" width="900">
</p>


### Paso 02: Poblar la Épica "Estructura y Contenido Base"

```bash
    Crea las siguientes incidencias y asígnalas a la Épica 1:

    1.  Story:
        -   Título:
            Como nuevo visitante del repo, quiero un README claro y
            conciso para entender el propósito del Espacio en 1 minuto.
        
        -   Descripción / Criterios de Aceptación:
            "Dado" que abro la página principal del repositorio en GitHub.
            "Cuando" leo el archivo README.md.
            "Entonces" debo encontrar claramente:
                *   El nombre del Espacio.
                *   Una descripción de 1-2 frases sobre qué problema resuelve.
                *   Un enlace a la guía de "Instalación Rápida".
                *   Un badge que muestre el estado del build (CI).

    2.  Story:
        -   Título:
            Como usuario no técnico, quiero una guía de "Instalación
            Rápida" para poder usar el Proyecto sin ser un experto.
        
        -   Descripción / Criterios de Aceptación:
            "Dado" que estoy en el sitio de la documentación.
            "Cuando" navego a la sección "Instalación Rápida".
            "Entonces" la guía debe contener:
                *   Los prerrequisitos de software (ej. Node.js v18+).
                *   Comandos exactos que pueda copiar y pegar para instalar y ejecutar el espacio.
                *   Una captura de pantalla que muestre el resultado esperado tras la ejecución

    3.  Task:
        -   Título: Investigar y elegir una herramienta para generar la documentación.

        -   Descripción: Realizar un análisis comparativo entre MkDocs, Docusaurus y VitePress.
            La comparación debe evaluar: facilidad de uso, personalización, ecosistema de plugins y
            rendimiento. El entregable será un documento breve en Confluence o un comentario en
            esta misma tarea con la decisión final y su justificación.

    4.  Task:
        -   Título: Definir la estructura de carpetas para los archivos de documentación.

        -   Descripción: Proponer una estructura de directorios lógica para almacenar los archivos
            fuente de la documentación (ej. Markdown). La estructura debe ser escalable y separar
            claramente guías de usuario, tutoriales y referencias de API. El entregable es un
            esquema de la estructura de carpetas en formato de texto.
```

<p align="center">
  <img src="./img/lab-02/answer-02.png" alt="answer-02" width="900">
</p>
