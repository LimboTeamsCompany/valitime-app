# VALITIME

Didactic games for kids!

## Stack used for this project

The Front-End of this project is developed with:

- [React Native](https://reactnative.dev/)
- [Expo](https://expo.io/)
- [Redux](https://redux.js.org/)
- [Tailwind](https://www.nativewind.dev)

## How to run this project

1. Clone this repository
2. Install the dependencies with `npm install`
3. Run the project with `npm run start`

## How to contribute

1. Create a new branch from `main` with your changes: `git checkout -b ticket-123`
2. Save your changes and create a commit message telling what you did: `git commit -m "feature: My new feature"`
3. Submit your changes: `git push origin my-feature`

## Standards

- Every task or ticket you have to do, you should create a new branch from `main` with the name of the ticket, for example: `git checkout -b ticket-123`, the commits must to be small and with a good description, the commits cannot be bigger than 10 files, except special cases.

- Components files should have a maximum recommended size of 100 lines. This can be achieved by dividing the component into other Components, which in turn improves performance.
  A file with more than 100 lines becomes a complicated file to read, it should always be trimmed.

- One of the most important parts of maintaining good code are the variable names, these are some of the standards we use at LimboTeams:

  Use readable and descriptive names, avoiding abbreviations and short names.

  - Variable names can be in camelCase or snake_case.
  - Avoid reusing variables for different purposes in the same code.
  - Avoid excessively long names and be consistent in naming.
    Use "is", "has", and "can" to express boolean values in variable names.

- All the UI components should be created using the Tailwind classes, this is a good practice to maintain the consistency of the UI. If you have a special case, you can create a new class in .css in the `styles` folder.

- The code should be written in English, including the comments.

- The code should be well organized, the files should be in the correct folders, and the code should be well indented.

- The main folder organization should be: `src` for the source code, `assets` for the images, `styles` for the global styles, `components` for the components, `screens` for the screens, `services` for the services, `store` for the redux store, `utils` for the utilities, and `hooks` for the custom hooks.
