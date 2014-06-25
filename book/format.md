# Formato

GitBook utiliza la convenci�n de archivos **markdown**.

Un libro es un repositoio Git que contiene por lo menos 2 archivos: README.md and SUMMARY.md.

#### README.md

Normalmente, esto deber�a ser la introducci�n de su libro. Que se a�adir� autom�ticamente a la s�ntesis final.

#### SUMMARY.md

El SUMMARY.md define la estructura de su libro. Debe contener una lista de cap�tulos, con enlaces a sus respectivas p�ginas.

Ejemplo:

```
# Summary

This is the summary of my book.

* [section 1](section1/README.md)
    * [example 1](section1/example1.md)
    * [example 2](section1/example2.md)
* [section 2](section2/README.md)
    * [example 1](section2/example1.md)
```

Los archivos que no est�n incluidos en SUMMARY.md no ser�n procesador por gitbook.

#### Multi-Lenguaje

GitBook apoya la construcci�n de libros escritos en varios idiomas. Cada idioma debe ser un subdirectorio con el formato normal de GitBook, y un archivo llamado `LANGS.md` debe estar presente en la ra�z del repositorio con el siguiente formato:

```
* [English](en/)
* [French](fr/)
* [Español](es/)
```

Tiene un ejemplo completo en el libro: [Learn Git](https://github.com/GitbookIO/git).

#### Ignorando archivos y carpetas

GitBook leer� los archivos `.gitignore`, `.bookignore` y `.ignore` para obtener la lista de archivos y carpetas que debe saltar (el formato dentro de esos archivos, sigue la misma convenci�n que `.gitignore`)
