# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

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

## Example :

Include three CDN's in your HTML file:

     <!DOCTYPE html>
     <html>
     <head>
     <script src="https://unpkg.com/react@18/umd/react.development.js" crossorigin></script>
     <script src="https://unpkg.com/react-dom@18/umd/react-dom.development.js" crossorigin><script>
     <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
     </head>
     <body>

     <div id="mydiv"></div>

     <script type="text/babel">
       function Hello() {
         return <h1>Hello World!</h1>;
       }

       const container = document.getElementById('mydiv');
       const root = ReactDOM.createRoot(container);
       root.render(<Hello />)
     </script>

     </body>
     </html>

# output :
![alt text](/public/image1.png)

## Learning by Examples
Our "Show React" tool makes it easy to demonstrate React. It shows both the code and the result.

Here is an example of how to use it:

     import React from 'react';
     import ReactDOM from 'react-dom/client';

     function Hello(props) {
     return <h1>Hello World!</h1>;
     }

     const container = document.getElementById("root");
     const root = ReactDOM.createRoot(container);
     root.render(<Hello />);


output:

![output](/public/output.png "Text to show on mouseover")
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


## Modify the React Application

So far so good, but how do I change the content?

Look in the `my-react-app` directory, and you will find a `src` folder. Inside the `src` folder there is a file called `App.js`, open it and it will look like this:

`/myReactApp/src/App.js:`

```
          import logo from './logo.svg';
          import './App.css';

          function App() {
          return (
          <div className="App">
          <header className="App-header">
          <img src={logo} className="App-logo" alt="logo" />
          <p>
          M Kiran Kumar
          </p>
          <a
          className="App-link"
          href="https://reactjs.org"
          target="_blank"
          rel="noopener noreferrer">
          Learn React
          </a>
          </header>
          </div>
          );
          } 

          export default App;
``` 

Try changing the HTML content and save the file.

## For this repository project output:

![output-2](/public/image.png)
