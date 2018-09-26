Resolve Callback Hell
Using promise to get rid of callback hell.


Get Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. 

Setup
make sure the node.js environment exits,

$ npm install

Now execute the server.js to start the server, it is not including "express.js" due to requirement.

$ node server.js

Open http://localhost:3600 in any browser and check the output.


Instructions

Click on button "Click Me!", the data will be fetched from server, and display on HTML.
Please check "app.js" to see how to "get" data in ajax call without using "JQuery".

It is a 10-level callback, and executes DOM manipulation in es6&es5.
Wait for 1s, a new column for "Nation" and its informataion, and answer for questions will come out
Above features(written in functions with ".then()") are implement in level 1 to 7.

Based on the data got from previous level, the new levels will be executed.
When click on names, it will alert a box for all the users' information.
When place mouse hover on/out different nations, the information will show/hide on the HTML body.


Built With - Node.js, es5&6
Authors - Lulu(Taylor) Tong
