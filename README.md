# Deploy Angular App to local server for pre-production testing

Before deploying your application to a remote server, you can run a pre-production test from a local web server.

This method is for development and testing only.
It is not a supported or secure way of deploying an application.

This way you make sure it will work fine when you deploy it to a remote server.

## Compile the application to the dist folder in a terminal

```ts
ng build
```

## Install a web server and run it against the output folder

```ts
npm install lite-server --save-dev
lite-server --baseDir="dist/project-name"
```
