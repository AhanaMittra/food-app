# FoodApp

## Steps to setup:
1. In the terminal write `git clone git@github.com:AhanaMittra/food-app.git` . This command will clone the project in your local machine.
2. Go into the folder where the project is cloned by `cd food-app`.
3. Enter the command `npm install` in the terminal to download the node dependencies (stored in `node_modules` folder).
4. Enter `ng serve --open` in the terminal to run the web application.
5. For adding new features to this project, please create a new branch by entering `git checkout -b <branch-name>`. Example: Let us assume we are developing a login page feature. Then we can create a branch by `git checkout -b feature/login-page`
6. After making modifications, when the feature is ready enter `git add .`, `git commit -m "<meaningful message for which the commit is made>`
7. After commit, please push the branch to the remote origin by entering `git push origin <branch-name>`. Example: for our login-page branch mentioned above, we should write `git push origin feature/login-page`
8. Then we can merge this feature to our master branch, if everything is good. 

Note: Please do not push anything directly to the master branch as a good practice. Please use `git status` command to see the current status of the project (and it also provides valuable information about next steps to be taken).


This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.0.3.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Code scaffolding

Run `ng generate component component-name` to generate a new component. You can also use `ng generate directive|pipe|service|class|guard|interface|enum|module`.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.
