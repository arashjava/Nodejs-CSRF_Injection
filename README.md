# Nodejs-CSRF_Injection
To prevent the web sessions being hijacked, we need to pass CSRF token between pages to let the browser validate the right users.
This is just a Nodejs Express small application to show how to set/ pass CSRF token between webpages in Nodejs. 
To be able to do this we need to install couple of packages first:
- npm install csurf --save 
- npm install express-session --save
