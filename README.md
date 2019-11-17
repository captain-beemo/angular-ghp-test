# AngularTest2

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.1.1.

## deploy angular app on github pages

```Text
1.npm install -g angular-cli-ghpages

2.ng build --prod --base-href https://<profile_name>.github.io/<repo_name>/ --deploy-url=https://<profile_name>.github.io/<repo_name>/

3.ngh --dir=dist/<repo_name>

4. .angular-cli.json project name should be the same as <repo_name>

5.git remote repo should be marked as public too, otherwise, it won't be able to post the project.

6.make sure to delete dist folder in the project and gh-pages branch in the remote repo before you go to the through step 1, 2 and 3.

```

## Links to other project
[captain-beemo/angular-deploy-demo: The complete angular guide - deploy practice, deploy this angular app on github-pages.](https://github.com/captain-beemo/angular-deploy-demo)

[Images are not loading after deploying angular app on github pages - Stack Overflow](https://stackoverflow.com/questions/56379595/images-are-not-loading-after-deploying-angular-app-on-github-pages)

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
