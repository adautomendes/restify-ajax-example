# restify-ajax-example

An little example of how to consume a REST API implemented in NodeJS using 'restify' with AJAX calls.

## Dependencies
A MySQL database installed.

## Backend/Middleware
* [Restify](https://www.npmjs.com/package/restify) - REST API NodeJS library
* [MySQL](https://www.npmjs.com/package/mysql) - Database connection

## Frontend
* [jQuery](https://jquery.com/) - Javascript libary
* [MaterializeCSS](https://materializecss.com/) - Stylizing HTML

## Deployment
* Run 'ec021.sql' on MySQL database
* Config the var 'con' in the middleware/index.js file with your database credentials
* On the terminal within middleware directory install the node dependencies 
```
npm install
```
* On the terminal within middleware directory run the index.js file using
```
node index.js
```
* Open the file cards.html or list.html on frontend directory
