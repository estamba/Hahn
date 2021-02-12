
## Features not implemented
I tried to get the localization to work but I couldn't I ran into issues and couldn't find proper documentation. The rest of the requirements have been implemented


# `Web API Project`

1. Open the project in Visual studio 2019
2. Make sure you have .net 5 installed 

3. Start the web api project 
4. Take note of the port number that its listening on you might need to update the frontend app if the port number is
   is not 5001






# `FrontEndApp`

This project is bootstrapped by [aurelia-cli](https://github.com/aurelia/cli).

For more information, go to https://aurelia.io/docs/cli/webpack

## Run dev app
Run `npm run` to  install all the packages.
Check the  settings in the config file its in src/config make sure the port number in the url is the same as the one the  API is listening on 
Run `npm start`, then open `http://localhost:8080`


You can change the standard webpack configurations from CLI easily with something like this: `npm start -- --open --port 8888`. However, it is better to change the respective npm scripts or `webpack.config.js` with these options, as per your need.

To enable Webpack Bundle Analyzer, do `npm run analyze` (production build).

To enable hot module reload, do `npm start -- --hmr`.

To change dev server port, do `npm start -- --port 8888`.

To change dev server host, do `npm start -- --host 127.0.0.1`

**PS:** You could mix all the flags as well, `npm start -- --host 127.0.0.1 --port 7070 --open --hmr`

For long time aurelia-cli user, you can still use `au run` with those arguments like `au run --env prod --open --hmr`. But `au run` now simply executes `npm start` command.

## Build for production

Run `npm run build`, or the old way `au build --env prod`.

## Unit tests

Run `au test` (or `au jest`).

To run in watch mode, `au test --watch` or `au jest --watch`.



