# uaming_js

Javascript module to monitor user activity on sites.

To use this module, you have to import the uaming.js to your main page.
For Rails applications, add the uaming.js file to assets/javascript and import using require on application.js.

Before start the application, change the server API REST on line 121. This server will receive all the events and contacts information sent from user. 

Example:
UamingWidget.init("http://uaming-application.herokuapp.com");
