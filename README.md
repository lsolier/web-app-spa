# SpaClient

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.11.

## Run App Locally

Run
```bash
npm install
npm run build
npm run start
```
## Run app on container

- Build docker image with `docker build -t web-app-spa:1.0 .`
- Verify docker image with `docker image ls web-app-spa`
- Run container locally with `docker run -d --rm -p 9898:4200 --name web-app-spa-container web-app-spa:1.0` . Navigate to `http://127.0.0.1:9898/`
- Interact with container `docker exec -i web-app-spa-container sh`



## Development server

Run `ng serve` for a dev server. Navigate to `http://127.0.0.1:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.
