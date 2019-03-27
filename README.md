
# beyond-da-burger
This is a "homemade" ORM handlebars restaurant application using Node and MySQL to query and route data flow. This full stack veggie burger-logger web app features the use of Node, Express server, Handlebars for view generation and a homemade ORM.


### Overview

Beyond burgers offers vegan plant-based alternatives in a restaurant style application for logging burger options with MySQL, Node, Express, Handlebars and a homemade ORM (yum!). Following the MVC design pattern; this appication queries and routes data with Node and MySQL,then runs Handlebars to generate HTML.

### Links to view

* Deployed: https://beyond-burger.herokuapp.com/
* Githubrepo: https://shannonruder.github.io/beyond-burger/
* Check out a video walkthrough here: https://drive.google.com/file/d/1m0ghmQTHpQn2Q7UTOU5rRBWpZutcC7V7/view

### Application Overview

* Beyond-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat. Whenever a user submits a burger's name, it will display the burger on the left side of the page -- UNEATEN BURGERS -- waiting to be eaten. Each burger in the waiting area also has a ` EAT THIS!` button. When the user clicks it, the burger will move to the right side of the page --EATEN BURGERS.

* Your app will store every burger in a database, whether devoured or not.

### To run the app

1. Clone the repo.
2. Run npm init and npm install packages:
3. express, express-handlebars, method-override, mysql, mysql2, and body-parser
4. Run the `schema.sql` and `seeds.sql` files into the mysql server from the command line
5. Now you're going to run these SQL files.
   * Make sure you're in the `db` folder of your app.
   * Start MySQL command line tool and login: `mysql -u root -p`.
   * With the `mysql>` command line tool running, enter the command `source schema.sql`. This will run your schema file and all of the queries in it -- in other words, you'll be creating your database.
   * Now insert the entries you defined in `seeds.sql` by running the file: `source seeds.sql`.

     * The app itself is fairly straightforward but the focus here was to practice data flow, routing, view generation, etc., in a full stack design.
