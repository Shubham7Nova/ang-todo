# AngTodo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Setup details

- Download npm and Node.js
- Download Angular CLI using: `npm install -g @angular/cli`
- Created project using: `ng new ang-todo`
- Added Bootstrap to the project using: `npm install bootstrap`
- Added jquery to the project using: `npm install jquery`
- Added Bootstrap min css in angular.json -> architect -> build -> styles : `"node_modules/bootstrap/dist/css/bootstrap.min.css"`
- Added Bootstrap min js in angular.json -> architect -> build -> scripts : `"scripts": ["node_modules/bootstrap/dist/js/bootstrap.min.js"]`
- Added jquery.js in angular.json -> architect -> build -> scripts
- Generated new component todo in components folder: `ng generate component components/todo`
- Added prettier using: `npm install --save-dev --save-exact prettier`
- Run prettier using; `npx prettier --write .`
