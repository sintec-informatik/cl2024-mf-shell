# MfShell

This is the shell project.

## Build and Run
* Build with `npm install`
* Run with `ng serve` 
* Navigate to `http://localhost:4200/`

## How the project was created
* Create the project: `ng new mf-shell --defaults`
* Navigate into project folder: `cd mf-shell`
* Configure host module federation: `ng add @angular-architects/module-federation --project mf-shell --port 4200 --type host`

## Configure a micro frontend
* Declare Module in  `/src/app/decl.d.ts`
* Configure exposed routes for WebPack in `webpack.config.js`
