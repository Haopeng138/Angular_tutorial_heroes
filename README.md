# AngularTourOfHeroes

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 14.0.4.

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

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.io/cli) page.

## Some summary of angular:

### Preview:

    - class = file.ts 
    
    - template = file.html
    
    - Create component: "ng generate component componentName"

    - In the class you can have variable , for call the variable in the template you need use "{{}}"

### Cap1:

    - "ng generate component xxx": generates three files:

        - Class file:  

            - @Component:

|Properties| Details |
|-------|------|
|selector | The component's CSS element selector|
|templateUrl| The location of the component's template file|
|styleUrls| The location of the component's private CSS styles| 

        
    - Use "xxx | uppercase " for pipe and make all caracter uppercase

    - Use "ngModel" for two way binding, template with class, and this module should be imported explicitly

### Cap2:

    - Select a element

    - Use ngFor and ngIf

### Cap3:

    - Create a reusable component

    - Use property binding to give the parent control over the child 

    - Use @Input decorator to make soma variable property available

### Cap4:

    - Refactor data access to the service class

    - Register a service 

    - Use Observable and RxJS 

    - Know the function of ngOnInit 

### Cap5: 


    