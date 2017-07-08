# angular2
Angular2- Creating component and routing

Installation

BEFORE YOU INSTALL: please read the prerequisites

npm install -g @angular/cli
Usage

ng help
Generating and serving an Angular project via a development server
ng new PROJECT-NAME
cd PROJECT-NAME
ng serve
Navigate to http://localhost:4200/. The app will automatically reload if you change any of the source files.

You can configure the default HTTP host and port used by the development server with two command-line options :

ng serve --host 0.0.0.0 --port 4201
Generating Components, Directives, Pipes and Services
You can use the ng generate (or just ng g) command to generate Angular components:

ng generate component my-new-component
ng g component my-new-component # using the alias
 
# components support relative path generation
# if in the directory src/app/feature/ and you run
ng g component new-cmp
# your component will be generated in src/app/feature/new-cmp
# but if you were to run
ng g component ../newer-cmp
# your component will be generated in src/app/newer-cmp
# if in the directory src/app you can also run
ng g component feature/new-cmp
# and your component will be generated in src/app/feature/new-cmp
