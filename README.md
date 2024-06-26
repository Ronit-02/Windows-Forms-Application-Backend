# Backend README

This README provides instructions on setting up and using the backend API developed in Node.js with Express.

## Prerequisites
- Node.js installed on your machine.

## Setup Instructions
1. Clone or download the repository containing the Node.js project.
2. Navigate to the project directory in the terminal.
3. Install dependencies using `npm install`.

## Running the Server
1. Start the server by running `npm run dev`.
2. The server will start running on `http://localhost:8000`.

## API Endpoints
- **GET `/ping`**: Ping to check if the server is running.
- **POST `/submit`**: Submits a new form submission.
- **GET `/read/:id`**: Retrieves the submission with the specified ID.
- **PUT `/edit/:id`**: Edits an existing submission with the specified ID.
- **DELETE `/delete/:id`**: Deletes the submission with the specified ID.
- **GET `/search?email={email}`**: Searches for a submission by email address.

## Data Storage
- Submissions are stored in a JSON file (`db.json`) locally on the server.

## Notes
- This backend is designed to work with the corresponding frontend application developed in VB.NET.
- Ensure the frontend application is correctly configured to communicate with this backend (adjust URLs if necessary).
