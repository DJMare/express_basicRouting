# Express_basicRouting
A basic express app that based on the URL, displays different data onto the page.

COMMAND PROMPT

(1) Run the following to navigate to your Desktop: 

    cd Desktop

(2) Create a new folder on Desktop: 

    mkdir Express

(3) Navigate to the Express directory: 

    cd Express

(4) Run the following command to install the Express generator globally onto your computer: 

    npm install express-generator -g

(5) Enter the following command to generate the Express starter app. This will set the view to use Handlebars and will name the app express_basicRouting: 

    express --view=hbs express_basicRouting

(6) Once the process is complete, navigate into the express_basicRouting directory: 

    cd express_basicRouting 

(7) Now in the express_basicRouting directory, run the following: 

    npm install

(8) Install Nodemon globally: 

    npm install -g nodemon

(9) Start the server with Nodemon with the following command: 

    nodemon

(10) Open in VS code: ![open in vs code (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629301-e1af6e00-f830-11e9-9e0f-a5e93e5b64f2.JPG)


VS CODE

(11) Create a 'models' folder at the root level of the project. Then, create a file named users.js where the data is modeled out. Add an array of objects of different "users" in the application: ![create models folder and users js file (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629313-0e638580-f831-11e9-88ee-6c63e066d32d.JPG)

![add an array of objects of different users (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629332-381cac80-f831-11e9-83e5-fe26c3959c62.JPG)


(12) Navigate to the routes/index.js file and update. Need to require the model/users.js file into the routes/index.js: ![open index js file (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629347-73b77680-f831-11e9-97be-6f9d002a74ac.JPG)

![update index js file (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629355-9cd80700-f831-11e9-9f79-ef5f1916c4b0.JPG)


(13) Navigate to the views/index.hbs file and update to show the user information: ![open index hbs file (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629372-c7c25b00-f831-11e9-80f2-ff546d7ea6cc.JPG)

![update index hbs file to show user data (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629380-f17b8200-f831-11e9-80e4-4f42fcd3df3b.JPG)


WEB BROWSER

(13) In your web browser, navigate to localserver:3000 and look up a specific user id to see changes: ![navigate to specific user id in web browser localhost3000 to see user data (express_basicRouting)](https://user-images.githubusercontent.com/35668707/67629400-41f2df80-f832-11e9-9798-2c545404b9d3.JPG)

