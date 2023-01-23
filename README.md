<h1 align="center">Sorteador</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/LeticiaFarias/sorteador?color=6200EE">
  <img alt="Github language count" src="https://img.shields.io/github/languages/count/LeticiaFarias/sorteador?color=6200EE">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/LeticiaFarias/sorteador?color=6200EE">
  <img alt="License" src="https://img.shields.io/github/license/LeticiaFarias/sorteador?color=6200EE">
  <img alt="Github stars" src="https://img.shields.io/github/stars/LeticiaFarias/sorteador?color=6200EE" />
</p>

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#pushpin-code">Code</a> &#xa0; | &#xa0;
  <a href="#construction-future-features">Future Features</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/LeticiaFarias" target="_blank">Author</a>
</p>

<div align="center" id="top"> 
  <img src="./.github/app.gif" alt="Sorteador" width="300px" />
</div>

<br>

## :dart: About

The developed application is a simple draw that allows the user to draw a random number from 0 to 100 with the touch of a button.

## :sparkles: Features

:heavy_check_mark: Draw a random number between 1 and 100;\
:heavy_check_mark: Show on screen the randomly drawn number in the range from 1 to 100;\
:heavy_check_mark: Change the state of the text by clicking on the raffle button.

## :rocket: Technologies

The following tools were used in this project:

- [Kotlin](https://kotlinlang.org/)
- [Android Jetpack](https://developer.android.com/jetpack)
- [Android Studio](https://developer.android.com/studio)

## :pushpin: Code

```kotlin
 fun sortear(view: View){
        var resultado: TextView = findViewById(R.id.numeroResultado)
        var numero: Int = (1..100).random()

        resultado.setText("O número sorteado é: $numero")
    }
```

## :construction: Future Features
:round_pushpin: Implement a button to reset the drawn number;\
:round_pushpin: Allow the user to choose the range of numbers that will be drawn;\
:round_pushpin: Dark theme for application.

## :memo: License

This project is under license from Apache 2.0. For more details, see the [LICENSE](LICENSE.md) file.

Made with :heart: by <a href="https://github.com/LeticiaFarias" target="_blank">Letícia Farias</a>

&#xa0;

<a href="#top">Back to top</a>
