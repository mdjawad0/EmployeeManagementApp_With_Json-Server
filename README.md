# Angular App with JSON Server

This application is built with the Angular framework as the frontend, and it has pages for listing and adding employees, as well as updating employee details. The json-server serves as the backend, and there are testscripts written in Cypress.

###### Tools required: Node v17,  Angular CLI, json-server, and Cypress

To run the project successfully, follow the steps below:

**Step 1:** Install the node modules with the command: 

`npm install`

**Step 2:** Start the Angular project with the command: 

`ng serve`

> **Note:** If you get the ng not found error at this step, run the following command and try again: 

`sudo npm link @angular/cli`

**Step 3:** Run the JSON server in another terminal with the command: 

`json-server --watch db.json`

> **Note:** If you get the json-server not found error, run the following command and try again: 

`sudo npm instal -g json-server`

The application should be functional now.


**Step 4:** Perform the functional testing with Cypress by running the command in another terminal: 

`npx cypress open`
