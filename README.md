# How to create Angular PWA

## Project creation

Create new project using:
```bash
ng new 'project-name'
```
Navigate inside the project and then add Angular Material (optional)
```bash
ng add @angular/material
```

## PWA configuration

Run the command below
```bash
ng add @angular/pwa
```
Then, to test it, it's necessary to run it with angular-http-server:
```bash
ng build --prod
npm i -g angular-http-server
```
And then, after navigating to the dist folder...
```bash
angular-http-server
```
If it works, it can now be deployed via Netlify :)

## License
[MIT](https://choosealicense.com/licenses/mit/)