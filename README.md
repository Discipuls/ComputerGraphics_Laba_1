- Site is available on https://laba-1.vercel.app/
- Screenshot - https://raw.githubusercontent.com/Discipuls/ComputerGraphics_Laba_1/refs/heads/main/Screenshot_1.png

# Task

To study the color models: RGB, HSV, LAB, the transition from one model to another, to explore the color graph of the MCO.

Create a web application that allows the user to select and then interactively change the color, while showing its components in three models simultaneously.

## They are being checked:

- a web application hosted in the public domain;
- The source code of the application on **GitHub**;
- Accompanying documentation.

## Basic application requirements

- In the interface, allow the user to set exact colors (input fields), select colors from the palette (similar to graphic editors), smoothly change colors (for example, sliders).
- When any color component is changed, all other representations of that color in the other two color models are recalculated automatically.
- In case of "incorrect colors" (for example, when switching from XYZ to RGB, your calculation turned out to go beyond the boundaries of the calculated parameter change), issue an unobtrusive warning that cropping-rounding occurs, etc.

## Points

- Correctness of the transfer from one model to another: **40 points**.
- Friendly and user-friendly interface: **30 points**.
- The ability to set the color in each of the three models in three ways: **20 points**.
- Automatic recalculation of the color in all models when changing any of the coordinates: **20 points**.

## Dependencies:
- "@types/react": "^18.3.5",
- "@types/react-color": "^3.0.12",
- "@types/react-dom": "^18.3.0",
- "autoprefixer": "^10.4.20",
- "postcss": "^8.4.44"

# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).
