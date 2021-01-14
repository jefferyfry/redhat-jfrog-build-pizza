# Pizza Delivery VS. DevOps Pipeline on Openshift

This repository contains the code for the [Pizza Delivery VS. DevOps Pipeline on Openshift webinar](https://leap.jfrog.com/WN-2021-01-Pizza-Delivery-Devops-Pipelines-on-Openshift-US-LP.html). This webinar is jointly presented by Red Hat and JFrog. It contains a npm application, dockerfile and openshift pipeline/tekton pipelines, resources and tasks to build and deploy the application.

## DevOps Pipeline Workflow
![workflow](https://drive.google.com/uc?export=view&id=1MGqX0B0Kr_DQ-wjOYXaVJDe6Q0DZE6a8)

## High-level Architecture
![arch](https://drive.google.com/uc?export=view&id=1n_LFBkaVivMIknK14PIWKNf9_ohzlcuy)


# Pizza App

![pizza app](https://drive.google.com/uc?export=view&id=1hYRFPvocVR0uj3v2NmdtubEFNaSNASmJ)

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 10.1.7.

## Build and Run Docker Image Locally

```
$ docker build -t pizza-app . 
$ docker run -p 443:443 -p 80:80 docker.io/library/pizza-app
```

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `--prod` flag for a production build.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via [Protractor](http://www.protractortest.org/).

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
