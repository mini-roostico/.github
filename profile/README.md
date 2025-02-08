# Subjekt

*Subjekt* is a tool for the generation of textual files. The application, given a configuration (es. YAML, forms), which states combinations of parameters as well as pieces of customizable code templates with template expressions, generates all the possible permutations of these parameters and expressions. This application is available through a simple web app, using a simple Vue.js frontend, that communicates with two distinct services, `api` and `auth`, to handle generation, authentication and more. 

*Subjekt* is also available as a software library, making it a testing tool for checking a multitude of testing cases avoiding repetitions. It is developed using Kotlin multiplatform and can therefore be used both in JVM and JS targets. 

## How to use the library

To use *Subjekt* as a library, you can install it from Maven Central as a Gradle dependency:

```kotlin
implementation("io.github.mini-roostico:subjekt:2.0.2")
```
Or install it inside a `npm` project, getting it from npmjs:

```sh
npm i @mini-roostico/subjekt
```

## How to use the web app

To launch the entire *Subjekt* infrastructure, you need to clone the `bootstrap` repository:

```sh
git clone git@github.com:mini-roostico/bootstrap.git
```

And follow the instruction at [this repository](https://github.com/mini-roostico/bootstrap) in order to setup the `docker-compose` environment.

After that, the web app should be available on `http://localhost:80`

## About this project

More information about this project can be found at the [*Subjekt* website](https://mini-roostico.github.io/subjekt-doc/). 

This project was developed for Software Process Engineering a.y. 2023-2024 by Francesco Magnani and Luca Rubboli
