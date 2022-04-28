# au2-webpack-azure-stapp

Aurelia 2 Webpack based skeleton configured to be used with Azure Static Web Apps

This project is bootstrapped by [aurelia/new](https://github.com/aurelia/new).

## Start dev web server

    npm start

## Build the app in production mode

    npm run build

It builds all files to dist folder. To deploy to production server, copy all the `dist/*` files to production root folder.

For example

```
dist/index.html
dist/foo.12345.js
```

Copy to production root folder

```
root_folder/index.html
root_folder/foo.12345.js
```

## Analyze webpack bundle

    npm run analyze

## Using the Azure Static Web App CLI

Start the app with the Azure Static Web App CLI

```
npx @azure/static-web-apps-cli start http://localhost:9000 --run "npm start"
```
