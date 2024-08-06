## API Endpoints

- `POST /questions/create`: Create a new question
- `POST /questions/:id/options/create`: Add an option to a question
- `DELETE /questions/:id`: Delete a question
- `DELETE /questions/:questionId/options/:optionId`: Delete an option from a question
- `PUT /options/:questionId/:optionId/add_vote`: Add a vote to an option
- `GET /questions/:id`: Get a question with it

## Installation
- Clone the project locally
- Open the root directory in terminal
- Run the command: `npm install` to install the dependencies
- Run the command: `node server.js` to start the server
- Use 'Postman' to access the routes mentioned above

# Hosted at 
https://polling-system-api-8vz9.onrender.com
