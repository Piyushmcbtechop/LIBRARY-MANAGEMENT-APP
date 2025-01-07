## LIBRARY MANAGEMENT SYSTEM  

Create a Book library management application.


## Link for Visit


[Youtube Video Link](https://www.youtube.com/watch?v=dYm_pImIrZY&t=7s)

## Key Features

1. **Register and Login**:
 
  a. Admin should be able to register with their username and passwords.
  
  b. Users should be able to register with their username and password.
  
  c. Implement login functionality.

2. **Task Management**:
   
  a. After logging in, Admin should be able to Add, View, Update, and Delete Books details.
  
  b. Users can Borrow and Return the books.

3. **Backend**:

  a. Use Node.js and Express to create RESTful APIs for user authentication and task management.

  b. Use MongoDB as the database to store user and task information.

4. **Frontend**:

  a. Use React to create a user interface for the task management application.

  b. Ensure the UI is user-friendly and responsive.




## Tech Stack

### Backend

- **Node.js**: JavaScript runtime environment.
- **Express.js**: Web framework for Node.js.
- **MongoDB**: NoSQL database for storing event data.
- **dotenv**: Module to load environment variables.

### Frontend

- **React.js**: JavaScript library for building user interfaces.
- **react-router-dom**: navigation.
- **Redux**:state management

## Project Setup

### Prerequisites

- Node.js and npm installed
- MongoDB installed and running

### Backend Setup

1. Clone the repository:

   ``` bash
   git clone https://github.com/Anjali9561Gupta/Library-Management-APP.git
   cd frontend
  ``
  
2. Navigate to the backend directory:
   
   `` bash
      cd backend
   ``

3. Install dependencies::
   
   `` bash
      npm install
   ``
   
4. Create a .env file and add the following environment variables:
   
  `` bash
      PORT=8080
      MONGO_URI=your_mongodb_uri
      
   ``
5. Start the backend server:

    `` bash
      npm run server
   ``
   
### Frontend Setup

1. Navigate to the frontend directory:
   
  ``
  cd frontend
  Install dependencies:
  ``

2. Navigate to the backend directory:
   
   `` bash
      cd backend
   ``
   
3. Install dependencies::
   
   `` bash
      npm install
   ``

4. Start the backend server:
   
    `` bash
      npm start
   ``



### Usage
- Navigate to the frontend application in your browser at http://localhost:3000.
- Use the interactive calendar to view, create, update, and delete movies.


