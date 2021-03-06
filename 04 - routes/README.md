# Component

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.7.3.

## What will we learn in this tutorial
- Basic routing 
- Routing with params
- Child routes
- Default selection - Programatically clicking DOM elements.
- ngAfterViewInit
- Click
- ngClass
- routerLink
- routerLinkActive
- ElementRef
- dispatchEvent
- Test cases:
    - Stub the param value and check the initialized data
    - Other test cases 
- End to test cases 


## Steps to run the app:
- Clone the folder and run <b>npm i</b> to use the app.
- run <b>ng serve</b>
- run <b>ng serve --port 9000</b> if you want to run of a specific port
- run <b>ng test</b> to unit test using karma
- run <b>ng e2e</b> for end to end testing using protractor

## Excercise
- Add a child route under Primary section which should have a unique URL for its children
- Reloading the URL should highlight all affected routes
- Write unit test cases for Primary section childern with route params 
- Write e2e test cases for newly added components

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
