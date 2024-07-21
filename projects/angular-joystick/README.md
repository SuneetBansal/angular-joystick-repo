# AngularJoystick

This library was generated with [Angular CLI](https://github.com/angular/angular-cli) version 18.1.0.

## Build

Run `ng build angular-joystick` to build the project. The build artifacts will be stored in the `dist/` directory.

## Installation
For Angular 18 projects

```
npm install angular-joystick
```

## Example Usage

Import `NgxJoystickModule` in your module. For example,
```typescript
import { NgxJoystickModule } from 'angular-joystick';

@NgModule({
  declarations: [
    AppComponent
  ],
  imports: [
    BrowserModule,
    NgxJoystickModule
  ],
  providers: [],
  bootstrap: [AppComponent]
})
export class AppModule { }