# React Tutorial Pt 2: A Comprehensive Guide to Building Apps with React.js

Implementation of [A Comprehensive Guide to Building Apps with React.js codelab](https://tylermcginnis.com/reactjs-tutorial-a-comprehensive-guide-to-building-apps-with-react/), a serie of tutorials for the first steps in React.

This part will show how to use the Gulp and Browserify to build the app in React. It will convert the JSX to JS and concatenate all the components of the project

## How to Setup

First you need:

* [Node.js with npm](https://nodejs.org/en/)

After you clone this code, you need to install some packages, so select the project folder in the cmd prompt:

```
$ npm install
```
To run the developer watcher, use:
```
$ gulp
```
This way, every change you make in the original project, will update the version on the `/dist` folder.

To generate the built version use:
```
$ gulp production
```
It will also create a version in the `/dist` folder.

## Built with

* [Visual Studio Code 1.11.2](https://code.visualstudio.com/)

## Also see

See the other parts of this tutorial:
* [Part 1](https://github.com/jfbaraky/Building-Apps-with-React.js-PT.1-)
* [Part 1.5](https://github.com/jfbaraky/Building-Apps-with-React.js-PT.1.5-)