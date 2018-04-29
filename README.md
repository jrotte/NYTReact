##NYTReact App

https://ancient-wave-62126.herokuapp.com/

https://github.com/jrotte/NYTReact

https://jrotte.github.io/NYTReact/


## Cloning the repository
If you wish to clone the app down to your local machine...
  1. Ensure that you have MongoDB set up on your laptop
    * An amazing repo to get you started with that can be found [here](https://github.com/dannyvassallo/mongo_lesson).
  2. Once you are set up, `cd` into this repo and run `npm install`.
  3. Then open another bash or terminal window and run `mongod`
  4. Run the script with `node server.js`.
  5. Navigate to `localhost:3000` in your browser.

Note that if you made changes to the JSX code in the `/app` folder, you must transpile it to see your changes. When `cd`-ed into this repo, enter `npm run bundle` in the command line to trigger my `webpack` script.

The `/test` folder can be disregarded since its files were made just for laying out the design of the app.

## Functionality
On the backend, the app uses `express` to serve routes and `mongoose` to interact with a `MongoDB` database.

On the frontend, the app uses `ReactJS` for rendering components, `axios` for internal/external API calls, and `bootstrap` as a styling framework.

In order to transpile the JSX code, `webpack` and `babel` were utilized. All of the JSX  code in the `/app` folder was transpiled into the `bundle.js` file located in the `/public` folder.

