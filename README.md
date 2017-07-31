# JSON-SERVER
Fake json server using faker and json-server

Globally install json-server

```
npm install json-server -g  #or yarn global add json-server
```
 Run with `json-server customers.js` or `yarn start`
 
 Change in `package.json` the port value to run on another port
 
 Incase of an error `Error: Cannot find module 'semver'`. Delete `node_modules` with `rm -rf node_modules` and `npm install` again, then run with `npm start` otherwise if you installed packages using `yarn`, run the app with `yarn start`
