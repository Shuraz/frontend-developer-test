# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

# About

Demonstrating the skills HTML, CSS and JavaScript, and others frontend tech stacks.
User interface to search the courses offered in Sydney University.
Fetching the api data and presenting them in list, and futher displaying the overview of the listed data.


# Tech Stacks used
```
- HTML
- CSS
- Javascript/ ES6
- ReactJS and its hooks
```

# Configuration options
You may need to install the Allow CORS browser plugin for your local development. For example, Chrome “Allow CORS” plugin https://chrome.google.com/webstore/detail/allow-cors-access-control/lhobafahddgcelffkeicbaginigeejlf?hl=en and Firefox “CORS Everywhere” plugin https://addons.mozilla.org/en-US/firefox/addon/cors-everywhere/.


# Folder Structure
```
src
├── assets/
├      ├─── styles/
├                ├─── main.css
├── component/
├      ├──── custom-hooks/
├                ├───── useFetch.jsx
├      ├───── page/
├                ├────── Course.jsx
├                ├────── Error.jsx
├                ├────── Footer.jsx
├                ├────── Layout.jsx
├                ├────── Nav.jsx
├                ├────── NoPage.jsx
├                ├────── Overview.jsx
├── test/
├── App.jsx
├── index.js
```
### Info
1. `Course.jsx`:  This is component has input field to search the course.  This fetches the API data and present them in the list.
2. `Overview.jsx`:  This is component route the with the list of courses and present the over view of the subject.
3. `Footer.jsx` `Layout.jsx` `Error.jsx` `Nav.jsx` `NoPage.jsx` : These component are only for better UI experience and code readable.
4. `useFetch.jsx` : This is a custom hook for code reusability to fetch the api data and return as object. Here I have used axios to perform HTTP requests.
5. `main.css` : This a css file for the presentation of a document.

# Requirements
 1. You’ll need to have Node 14.0.0 or later version on your local development machine (but it’s not required on the server). We recommend using the latest LTS version. You can use nvm (macOS/Linux) or nvm-windows to switch Node versions between different projects.
 2. (npx is a package runner tool that comes with npm 5.2+ and higher, see instructions for older npm versions)
  
# How to Run
1. ` npm install`
2. `npm start`
 Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

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

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
