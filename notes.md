#  Notes on Angular

## Steps

- install angular: sudo npm install -g npm
- create angular project: ng new todo-list
- Make sure npm is version 6 ... npm install --global npm@6
  - I tried to run angular and I got the following error message:  
    - npm version 7.5.2 detected.
    - The Angular CLI currently requires npm version 6.
- ng serve --open
- To use css files with angular, open angular.json and add the styles to the styles section
- NgModule, in /src/app/app.module.ts, is the root app module.
- Install VDSCODE live share and live share extension 
- create a new component: ng generate component folderName/ComponentName