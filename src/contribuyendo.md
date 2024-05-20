# Contribuyendo al libro
Si quieres realizar un aporte al libro, puedes hacerlo clonando el repositorio del libro
y enviando un pull request con tus cambios.

## Clonar el repositorio
Para clonar el repositorio, debes tener instalado [Git](https://git-scm.com/). Una vez
instalado, puedes clonar el repositorio con el siguiente comando:

```bash
git clone git@github.com:CrawKatt/japones_para_brotecitos.git
```

## Estructura del repositorio
El repositorio está estructurado de la siguiente manera:

```bash
├── README.md
├── SUMMARY.md
├── src
│   ├── chapter_1.md
│   ├── formas_de_escritura.md
│   ├── chapter_3.md
│   ├── gramatica.md
│   ├── particula_wa.md
│   ├── particula_ga.md
│   ├── particula_ka.md
│   ├── particula_no.md
│   ├── particula_wo.md
```

El archivo `README.md` es el archivo que contiene la información general del libro, como
el título, el autor, la descripción, etc. El archivo `SUMMARY.md` es el archivo que
contiene el índice del libro. Los archivos dentro de la carpeta `src` son los capítulos
del libro.

## Añadir un capítulo
Para añadir un capítulo, debes crear un archivo dentro de la carpeta `src` con el nombre
del capítulo, por ejemplo, si quieres añadir un capítulo llamado "Introducción", debes
crear un archivo llamado `introduccion.md` dentro de la carpeta `src`. Luego, debes
añadir el capítulo al índice del libro, para ello, debes editar el archivo `SUMMARY.md`
y añadir el capítulo al final de la lista, por ejemplo:

```markdown
# Summary

- [Chapter 1](./introduccion.md)
```