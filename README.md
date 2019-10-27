# express_basicRouting
A basic express app that based on the URL, displays different data onto the page.

COMMAND PROMPT

(1) Run the following to navigate to your Desktop: cd Desktop

(2) Create a new folder on desktop: mkdir Express

(3) Navigate to the Express directory: cd Express

(4) Run the following command to install the Express generator globally onto your computer: npm install express-generator -g

(5) Enter the following command to generate the Express starter app. This will set the view to use Handlebars and will name the app express_basicRouting: express --view=hbs express_basicRouting

(6) Once the process is complete, navigate into the express_basicRouting directory: cd express_basicRouting 

(7) Now in the express_basicRouting directory, run the following: npm install

(8) Install Nodemon globally: npm install -g nodemon

(9) Start the server with Nodemon with the following command: nodemon

(10) Open in VS code



VS CODE
(11) Create a 'models' folder at the root level of the project. Then, create a file named users.js where the data is modeled out. Add an array of objects of different "users" in the application

(12) Navigate to the routes/index.js file and update. Need to require the model/users.js file into the routes/index.js: 


(13) Navigate to the views/index.hbs file and update to show the user information: 


WEB BROWSER

(13) In your web browser, navigate to localserver:3000 and look up a specific user id to see changes: 
