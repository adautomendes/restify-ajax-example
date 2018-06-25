# restify-ajax-example

An little example of how to consume a REST API implemented in NodeJS using 'restify' with AJAX calls.

## Backend/Middleware
* [Restify](https://www.npmjs.com/package/restify) - REST API NdeJS library
* [MySQL](https://www.npmjs.com/package/mysql) - Database connection

## Frontend
* [jQuery](https://jquery.com/) - Javascript libary
* [MaterializeCSS](https://materializecss.com/) - Stylizing HTML

## Deployment
<ol>
<li>Run 'ec021.sql' on MySQL database</li>
<li>Config the var 'con' in the middleware/index.js file with your database credentials</li>
<li>
    On the terminal within middleware directory install the node dependencies 
    ```
    npm install
    ```
</li>
<li>
    On the terminal within middleware directory run the index.js file using
    ```
    node index.js
    ```
</li>
<li>Open the file cards.html or list.html on frontend directory</li>
</ol>
