# CsgTableLibrary

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 15.0.0.
This library is an implementation of the Angular material mat-table with additional functionalities to keep your code dry and clean.
The library uses the dynamic component injection, to inject any components instances to the table columns, The table and the component instances
are linked together to manipulate all the operations needed for the data.

## Advantages

* Keep your code clean and dry, no need to repeat the mat-table HTML code.
* The dynamic component injection will divide your code to clean blocks easy to track and manipulate.
* Csg table provides the loading skeleton animation when loading the data.
* Csg table provides i18 translations, you can provide enums, and translation keys to the columns configurations to render the correct record attribute value.
* Csg table can be connected to all types of data by using the getAllDataObs or paginationObservable inputs, by using these inputs you can inject
  arrays of objects or observables.
* Csg table provides the functionalities to pass a filtrationModel or a paginationModel to be passed to the injected data Observable when calling the retrieve function.
* The filtrationModel and paginationModel are passed by reference, which allows the library to manage the inputs in a dynamic way.
* Csg table provides all the functionalities to manipulate the paginationObservable and getAllDataObs.

## Run
Run the application by using the npm start command.



