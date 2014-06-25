# Ejercicios y Test

#### Ejercicios

Un libro puede contener ejercicios interactivos (actualmente s�lo en Javascript). Un ejercicio es un c�digo proporcionado para el lector, que se da un editor de c�digo para escribir una soluci�n que se comprueba con el c�digo de validaci�n del libro del autor.

Un ejercicio se define en 4 partes:

* Ejercicio **Mensaje**/Objetivos (en markdown/texto)
* **C�digo inicial** para mostrar al usuario, proporcionando un punto de partida
* **Soluci�n** del c�digo, una soluci�n correcta para el ejercicio
* **Validaci�n** del c�digo que pone a prueba la exactitud de la entrada del usuario

Los ejercicios tienen que empezar y terminar con una barra de separaci�n (``` ---``` o ```***```). Debe contener 3 elementos de c�digo (**base**, **soluci�n** y **validaci�n**). Puede contener un cuarto elemento que proporcione el c�digo de **contexto** (funciones, importaciones de librerias, etc... que no deben ser mostrados al usuario).


    ---

    Define a variable `x` equal to 10.

    ```js
    var x =
    ```

    ```js
    var x = 10;
    ```

    ```js
    assert(x == 10);
    ```

    ```js
    // This is context code available everywhere
    // The user will be able to call magicFunc in his code
    function magicFunc() {
        return 3;
    }
    ```

    ---

#### Cuestionarios

Un libro tambi�n puede contener cuestionarios interactivos.

El cuestionario se define de la misma manera que un ejercicio.


    ---

    Here is the introduction for the quiz

    This is Question 1:
    - [x] This is the proposition 1 (the correct one)
    - [ ] This is the proposition 2

    > This is a help message when the answer to question 1 is wrong

    This is Question 2:
    - [ ] This is the proposition 1
    - [x] This is the proposition 2 (correct)
    - [x] This is the proposition 3 (correct)

    > This is a help message when the answer to question 2 is wrong

    ---

