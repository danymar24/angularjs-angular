# Prepare environments

To Install npm packages, run from the root folder:

```bash
$: cd angular2
$: npm install
$: cd angularjs
$: npm install

## Run Angular development server

To run the development server you have to run:

```bash
$: cd angular2 && ng serve
```

## Build angular app

To Build the angular app you have to run inside the angular2 folder:

```bash
$: ng build --prod
```

## Run angularjs

Run:

```bash
$: cd angularjs && node server
```

## Deploy angular app to angularjs server

1) Build angular app
2) Copy angular2 folder located inside angular2/dist to the angularjs folder and rename it to ng-app
3) add /ng-app/ to the scripts src inside ng-app/index.html file
4) Restart angularjs server