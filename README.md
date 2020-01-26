# Angular Micro Frontends

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 8.2.1.

## Build flight-booking sub project
```
cd flight-booking
ng build --prod --output-hashing none --single-bundle true
http-server ./dist/flight-booking -p 8081
```

## Run train-booking sub project
```
cd train-booking
ng build --prod --output-hashing none --single-bundle true
http-server ./dist/train-booking -p 8082
```

## Run travel-booking main project
```
cd travel-booking
ng serve
```

Navigate to `http://localhost:8080/`. The app will automatically reload if you change any of the source files.

## Further help

To get more help on the Angular CLI use `ng help` or go check out the [Angular CLI README](https://github.com/angular/angular-cli/blob/master/README.md).
