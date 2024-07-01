<!-- Encabezado -->
[![Colaboradores][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Estrellas][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]

<!-- Título -->
<br />
<div align="center">

<h3 align="center">Automatización de la Compilación de Archivos LaTeX</h3>
  <p align="center">
    Script de GitHub Actions para automatizar la compilación de documentos LaTeX. GitHub Actions script to automate the compilation of LaTeX documents.
    <br />
    <a href="https://github.com/andres-merino/GitHub-Action-LaTeX/issues">Reportar un Problema</a>
    ·
    <a href="https://github.com/andres-merino/GitHub-Action-LaTeX/issues">Solicitar cambio</a>
  </p>
</div>

<!-- Cuerpo -->
## Sobre el Proyecto

Este proyecto proporciona un script de GitHub Actions que permite la automatización de la compilación de archivos LaTeX. Cada vez que se realiza un push en la rama `main`, el script se ejecuta para compilar los documentos LaTeX cambiados y generar los correspondientes archivos PDF y XML (generados para Moodle).

## About the Project

This project provides a GitHub Actions script that automates the compilation of LaTeX files. Whenever a push is made to the main branch, the script runs to compile the changed LaTeX documents and generate the corresponding PDF and XML files.

### Construido con

[![GitHub Actions][github-actions]][github-actions-url]
[![LaTeX][LaTeX]][LaTeX-url]

## Descripción

El script realiza las siguientes acciones:
- Verifica los archivos modificados y filtra aquellos con extensión `.tex`.
- Compila los archivos `.tex` utilizando `latexmk` con `xelatex`.
- Mueve los archivos PDF y XML generados a sus directorios originales.
- Realiza un commit y push de los archivos PDF y XML compilados al repositorio.

### Pruebas

El script ha sido probado en un entorno Ubuntu utilizando GitHub Actions y LaTeX.

## Últimos cambios

```
- 2024-07-01
   - Se agrega el script de GitHub Actions para automatizar la compilación de archivos .tex.
```

## Créditos

**Andrés Merino** (aemerinot@gmail.com)

- Docente-Investigador en Pontificia Universidad Católica del Ecuador
- Fundador del [Proyecto Alephsub0](https://www.alephsub0.org/about/)
  
  [![LinkedIn][linkedin-shield]][linkedin-url-aemt]

## Licencia

Distribuido bajo la licencia Creative Commons Attribution-ShareAlike 4.0 International. 

[![MIT License][license-shield]][license-url]

<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/andres-merino/GitHub-Action-LaTeX.svg?style=for-the-badge
[contributors-url]: https://github.com/andres-merino/GitHub-Action-LaTeX/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/andres-merino/GitHub-Action-LaTeX.svg?style=for-the-badge
[forks-url]: https://github.com/andres-merino/GitHub-Action-LaTeX/forks
[stars-shield]: https://img.shields.io/github/stars/andres-merino/GitHub-Action-LaTeX?style=for-the-badge
[stars-url]: https://github.com/andres-merino/GitHub-Action-LaTeX/stargazers
[issues-shield]: https://img.shields.io/github/issues/andres-merino/GitHub-Action-LaTeX.svg?style=for-the-badge
[issues-url]: https://github.com/andres-merino/GitHub-Action-LaTeX/issues
[license-shield]: https://img.shields.io/github/license/andres-merino/GitHub-Action-LaTeX.svg?style=for-the-badge
[license-url]: https://es.wikipedia.org/wiki/Licencia_MIT
[linkedin-shield]: https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white
[linkedin-url-aemt]: https://www.linkedin.com/in/andrés-merino-010a9b12b/
[LaTeX]: https://img.shields.io/badge/LaTeX-008080?logo=latex&logoColor=fff&style=for-the-badge
[LaTeX-url]: https://www.latex-project.org/
[github-actions]: https://img.shields.io/badge/GitHub%20Actions-2088FF?logo=github-actions&logoColor=fff&style=for-the-badge
[github-actions-url]: https://github.com/features/actions
