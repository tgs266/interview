# Interview

This project is intended to test your skills in react. 

## Requirements

Using the [National Weather Service](https://www.weather.gov/documentation/services-web-api) api, create a single page application that will display weather alerts for a given location. Documentation for the active alerts endpoint can be found [here](https://www.weather.gov/documentation/services-web-api#/default/alerts_active) Specifically, the page needs to

1. Accept user input providing a state to get alerts for
2. Display the alerts in a clean and understandable format
3. Have clean and maintainable code with minimal code smells
    * Common code smells in JS are things like console logs, string concatenation instead of formatting, etc.
4. On page input validation and error handling

Based on the requirements, we are not expecting you to create a professionally designed page, just a functional one that gets the job done. However, if you want to extend it, see below.

### Required packages

We are only requiring that you use `Axios` for sending and recieving requests. Outside of that, any package you think you need, go ahead and use it

## Nice to haves

These are not strictly required, however they are nice to have
1. Use of MUI v5 as the component package to improve the display of the data
2. Ability to accept different types of input
    * The API specification allows input of lat/lng points, regions, zones, etc. No need to cover every single input type but it would be nice to extend it a little

## Lastly

Have a little fun with it. If you think you can extend it even further, feel free to go ahead and do so. Developers sometimes need to thrive in ambiguity, and be able to deliver when the specifications aren't perfect. So while a requirement may give a high level overview of what to do, the specifics of implementation are up to you.

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

#### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

#### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

#### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

#### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

#### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

#### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
