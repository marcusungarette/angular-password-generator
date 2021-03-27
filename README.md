# Password Generator

Steps Angular do to generate password :

[1] - Users enters a password length.

[2] - Event handler triggered, we store the value as a property on our component
class instance.

[3] - User checks the 'Include Letters' checkbox.

[4] - Event handler triggered, we store the value as a property on our component
class instance.

[5] - User checks the 'Include Numbers' checkbox.

[6] - Event handler triggered, we store the value as a property on our component
class instance.

[7] - User checks the 'Include Symbols' checkbox.

[8] - Event handler triggered, we store the value as a property on our component
class instance.

[9] - User clicks the 'Generate' button.

[10] - Event handler triggered, we generate a password using the properties collected
earlier.

[11] - We update a 'password' property on the component class instance, which causes
an update of the 'output' input.

## Installing and Development server

[1] - Clone this repo.

[2] - Inside this project folder run `npm install`.

[3] - Run `ng serve` or `npm start` for a dev server. Navigate to `http://localhost:4200/`. The app will automatically reload if you change any of the source files.
