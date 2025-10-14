## Taller 2: Flujo de Colaboración: Forks y Pull Requests

### 📌 Objetivo: 

Aprender el estándar de la industria para contribuir a proyectos en los que no tienes permiso de
escritura directo gestionandolos con Pull Requests (PRs).

### Paso 01: Configura Ruleset en Github Actions

```bash
    1.  Ve a la página de del Repositorio en GitHub

    2.  Ve a Settings > Rules > Rulesets

    3.  Click en New ruleset > New branch ruleset

    4.  Completar con los siguientes datos
        °   Ruleset Name: master
        °   Enforcement status: Active
        °   En la sessión Target Branches > Add Target > Include by pattern > coloca main > Add Inclusion patter
        °   Marca la casilla: Require a pull request before merging (Esta es la configuración necesaria para que
            cualquier cambio a la branch main deba ser realizado a través de un pullrequest)
        °   Navega hasta la parte inferior del formulario y haz click en Create para crear la Ruleset.
```

<p align="center">
  <img src="./img/lab-01/answer-01A.png" alt="answer-01A" width="800">
</p>

<p align="center">
  <img src="./img/lab-01/answer-01B.png" alt="answer-01B" width="800">
</p>