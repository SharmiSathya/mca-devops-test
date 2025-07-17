# Frontend

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.2.11.

To get help on the Angular CLI use `ng help` or go check out the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

## Development

Launch the application:

```shell
ng serve
```

Navigate to `http://localhost:4200/`.

The application will automatically reload if you change any of the source files.

## Production

Set the backend API URL in `src/environments/environment.prod.ts`.

Build the application:

```shell
ng build
```

Expose with a web server (nginx, apache httpd, ...) the folder `dist/frontend/browser/`.

E.g. for local test: `python -m http.server -d dist/frontend/browser/`
