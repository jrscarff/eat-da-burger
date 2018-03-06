# Eat-Da-Burger

A full-stack web application currently without much styling allowing a user to create a burger with whatever name and then eat said burger. The burger will then move to the burgers eaten section using MVC architecture and a server hosted on Heroku using a JawsDB add-in. 

## Getting Started

You can access the functioning application hosted on Heroku at (https://quiet-woodland-82456.herokuapp.com/). You can alo git clone the repository on github and then just run an npm install in terminal while in the cloned folder.

### Prerequisites

From the github repository click on the button on the right to get the clone link and then in terminal run 

```
git clone (paste link here)
```

in the directory you want the application. Then while in the directory in terminal:

```
npm install
```

to get the required packages to run the application. You might have to manually install express-handlebars using npm install express-handlebars and mysql using npm install mysql and if this is the case you will be prompted to after trying to run the application.

## Running the server

To start the server and the application locally run 

```
node server.js
```

to run node in terminal. And then navigate to (http://localhost:3000/) in a web browser.

## Built With

* [mysql](https://dev.mysql.com/doc/) - The Database Management System used
* [Heroku](https://www.heroku.com/home) - The Web Deployment
* [Handlebars](https://www.npmjs.com/package/express-handlebars-sections) - Used to generate html
* [Express](https://www.npmjs.com/package/express-handlebars-sections) - Used to run the server
* [JawsDB](https://elements.heroku.com/addons/jawsdb) - The Heroku add-in to use a database
* [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/) - The CSS Framework included

## Authors

* **Ryan Scarff** - *Initial work* - [Eat-Da-Burger](https://github.com/jrscarff/eat-da-burger)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Thanks to UC Berkeley coding bootcamp for providing the basic code layout in the cat assignment.
