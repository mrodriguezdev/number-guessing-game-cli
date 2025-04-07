# Number Guessing Game (CLI - Java)

Este es un pequeño proyecto hecho en Java como parte de [roadmap.sh](https://roadmap.sh/projects/number-guessing-game). La idea es construir un juego de adivinanza de números en la línea de comandos, donde el usuario debe adivinar un número que el computador selecciona aleatoriamente.

## Descripción del Proyecto
Se te solicita construir un juego simple de adivinanza de números donde la computadora selecciona aleatoriamente un número y el usuario debe adivinarlo. Al usuario se le dará un número limitado de intentos para adivinar el número. Si el usuario adivina correctamente, el juego terminará y el usuario ganará. De lo contrario, el juego continuará hasta que el usuario se quede sin intentos.

## Requisitos
Es un juego basado en línea de comandos (CLI), por lo tanto, debes usar la terminal para interactuar con el juego. El juego debe funcionar de la siguiente manera:
* Cuando el juego comience, debe mostrar un mensaje de bienvenida junto con las reglas del juego.
* La computadora debe seleccionar aleatoriamente un número entre 1 y 100.
* El usuario debe seleccionar el nivel de dificultad (fácil, medio, difícil) que determinará la cantidad de intentos que tendrá para adivinar el número.
* El usuario debe poder ingresar su intento.
* Si el intento del usuario es correcto, el juego debe mostrar un mensaje de felicitación junto con la cantidad de intentos que tomó adivinar el número.
* Si el intento del usuario es incorrecto, el juego debe mostrar un mensaje indicando si el número es mayor o menor que el número ingresado por el usuario.
* El juego debe finalizar cuando el usuario adivine el número correcto o se quede sin intentos.

Ejemplo de salida del juego:

```shell
    Welcome to the Number Guessing Game!
    I'm thinking of a number between 1 and 100.
    You have 5 chances to guess the correct number.
    
    Please select the difficulty level:
    1. Easy (10 chances)
    2. Medium (5 chances)
    3. Hard (3 chances)
    
    Enter your choice: 2
    
    Great! You have selected the Medium difficulty level.
    Let's start the game!
    
    Enter your guess: 50
    Incorrect! The number is less than 50.
    
    Enter your guess: 25
    Incorrect! The number is greater than 25.
    
    Enter your guess: 35
    Incorrect! The number is less than 35.
    
    Enter your guess: 30
    Congratulations! You guessed the correct number in 4 attempts.
```

## Características adicionales opcionales
Para hacer el juego más interesante, puedes agregar las siguientes características:

* Permitir que el usuario juegue múltiples rondas del juego (es decir, seguir jugando hasta que el usuario decida salir). Podés hacer esto preguntando al usuario si desea jugar de nuevo después de cada ronda.
* Agregar un temporizador para ver cuánto tiempo tarda el usuario en adivinar el número.
* Implementar un sistema de pistas que proporcione pistas al usuario si está atascado.
* Llevar un registro de la puntuación más alta del usuario (es decir, la menor cantidad de intentos que tomó adivinar el número bajo un nivel de dificultad específico).