# burgermaster

Welcome to my burger master app, an application that lets the user enter a new burger type, add it to a list of all burgers stored in a database, and also delete burgers in the database. 

Once a burger is created, the user can choose to devour the burger, which moves the burger to the devoured section and changes the status of it in the database.

This application makes use of the MVC file structure, separating out the connections, the orm, the views, the controllers, and making the .handlebars files and CSS files public. 

The technology used in this application are mysql, node.js, express, and express handlebars. 

#Mysql was the database used to store our burgers data in. 

#Express is used to make the requests to and from the database, making use of parseing the data into JSON so it is easily usable. 

#Express handlebars is used to dynamically render the html to the view. 

#Node.js is used to run the CLI as well as console logs all errors and any data pulled from the database. 