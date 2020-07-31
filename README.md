# Building a website with Node.js and Express
https://www.linkedin.com/learning/building-a-website-with-node-js-and-express-js-3

Similar express app than repository 'Advanced_Express' using ejs template engine (views/) instead of pug.
Similar express app than repository 'Building_Bots_with_Node.js'

## Setting up the project

* In your terminal, create directory `building-website-nodejs-express` and **change into it**.
* Run 
  ```bash
  git clone --bare git@github.com:danielkhan/building-website-nodejs-express.git .git
  git config --bool core.bare false
  git reset --hard
  git branch
  ```
  
Everything else will be discussed in my course.



1. Building a Basic Express Application
- Create an Express server in three minutes
- Building from a HTML page or template
- Serving HTML pages and static content
- Setting up ESLint and Prettier
- Setting up nodemon
2. Template Engines
- Template engines and Express
- Getting to know the EJS template engine
- Rendering the index page with EJS
3. Express Routes and Middleware
- Express middleware and routes
- Modular routes with express.Router
- Creating routes for all subpages
- Add business logic
- Add a session management middleware
4. Professional Templating with Express
- Create a site-wide layout
- Using partials with EJS
- Template variables in more detail
- Looping through lists in templates
- Creating a list page
- Using parameter routes
- Challenge: Partials and lists
- Solution: Partials and lists
5. Handling Errors Gracefully
- How to handle errors in express
- Creating an error page
- Populating the error page
6. Handling Form Data
- Creating a form template
- Handling POST requests
- Validating and sanitizing user input
- Storing data
7. Creating APIs with Express
- A little intro to REST APIs
- Creating and testing an API endpoint
- Add client side JavaScript
- Updating the page from REST
