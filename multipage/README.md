# Multipage React App

This is a multipage React application built with React Router and styled-components.

## Project Structure

This is the project structure of the React Multipage application:

multipage/
├── .gitignore
├── package.json
├── public/
│ ├── index.html
├── src/
│ ├── App.js
│ ├── components/
│ │ ├── Navbar.js
│ │ ├── NavbarElements.js
│ ├── index.js
│ ├── pages/
│ │ ├── about.js
│ │ ├── contact.js
│ │ ├── index.js

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

## Project Components

### `Navbar`

The `Navbar` component is located in `src/components/Navbar.js`. It contains navigation links to different pages.

### `NavbarElements`

The `NavbarElements` component is located in `src/components/NavbarElements.js`. It contains styled-components for the `Navbar`.

### Pages

- `About` page is located in `src/pages/about.js`.
- `Contact` page is located in `src/pages/contact.js`.
- `Home` page is located in `src/pages/index.js`.

## Dependencies

- `react`: ^18.0.0
- `react-dom`: ^18.0.0
- `react-icons`: ^5.4.0
- `react-router-dom`: ^7.1.5
- `react-scripts`: 5.0.1
- `styled-components`: ^6.1.15

## License

This project is licensed under the MIT License.

Reference : https://github.com/gitname/react-gh-pages
