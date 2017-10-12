# Sample Backend API

A sample SailsJS (Node,Express) application.

* [Installation](#installation)
* [Starting App](#starting-app)
* [Testing](#testing)
* [Docker](#docker)

## Installation

These instructions are for use without docker

* Make sure that [Node.js](https://nodejs.org/) is installed.
* Install Node.js modules with `yarn`:
```shell
yarn install
```

## Starting App

* To run the app, copy the file `config/env/development.js` to `config/local.js` and substitute the settings to match your develoment environment.
* Start the app with `yarn`:
```shell
yarn start
```
* Navigate to [localhost:1500](http://localhost:1500). Please note `1500` is the default port used, you can change this in `config/local.js` or the corresponding enviroment file in `config/env` depending on your NODE_ENV os eniroment variable.
