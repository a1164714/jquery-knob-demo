# JqueryKnobDemo

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 1.6.0.

## Development server

Run `ng serve` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.

## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory. Use the `-prod` flag for a production build.

## Develop flow
- yarn add jquery OR npm install jquery --save
- yarn add @types/jquery
- yarn add jquery-knob
- yarn add @types/jquery-knob

```
import * as $ from 'jquery';
import 'jquery-knob';

ngOnInit(): void {
    $(function() {
      $(".dial").knob();
    });
}
<input type="text" value="75" class="dial">
```
