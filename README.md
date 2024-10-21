# JornadaMilhas

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 16.0.0.

# Para criar o projeto Angular

Crie uma pasta em seu computador para armazenar o projeto, criei com o nome angular
Depois abra o terminal de sua preferência na pasta criada, e execute o comando: `ng new jornada-milhas`
Abra a IDE, estou usando o VSCode, importe o projeto, e faça um teste para verificar se a aplicação abriu corretamente, no terminal já na pasta do projeto criado execute o comando `ng serve --open`
A página será aberta na URL: `http://localhost:4200/`


# Explicando a arquitetura do projeto

Analisando a UX da aplicação, percebemos que o header, o footer e alguns outros elementos se repetem nas telas,
assim vamos criar uma pasta chamada `shared` dentro de `src/app` execute o seguinte comando para criar a pasta já com a estrutura de arquivos: `ng g c shared/header`

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The application will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build


## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
