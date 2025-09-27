# Protect Her Chat-Full-Stack React Web Application 

## Overview
This project developed during a hackathon at AppsFlyer using the React framework.
The application provides parents with vital information on the dangers their children may face online.
## Features
- 🔍 Real-time detection of harmful and dangerous words in chat  
- 🤖 Interactive chatbot that guides parents about online threats  
- 👨‍👩‍👧 Target audience: Parents who want to protect their children online  
The client side is built using **React**, while the server side uses **Express**. The database is powered by **PostgreSQL**, and we use **pgAdmin** for database management.

<img src="scshoot.png" alt="Description of image">

## Technologies
- **Frontend**: React
- **Backend**: Express.js
- **Database**: PostgreSQL with pgAdmin
- **Authentication**: bcrypt (removed in a later version)

## Installation

### Prerequisites
Ensure you have the following installed:
- Node.js
- PostgreSQL and pgAdmin

### Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   cd your-repo
   ```
2. Install dependencies:
   - For the server:
     ```bash
     cd server
     npm install
     ```
   - For the client:
     ```bash
     cd client
     npm install
     ```


## Set up the PostgreSQL database:

1. Create a new database in pgAdmin.
2. Update the database connection configuration in the server's environment file (`.env`).

## Start the development server:

- Start the backend (server):
  ```bash
  npm start
  ```
- Start the frontend (client):
  ```bash
  cd client
  npm start
  ```
## Usage
Once the servers are running, you can access the application in your browser:

- **Frontend**: [http://localhost:3000](http://localhost:3000)
- **Backend**: [http://localhost:5000](http://localhost:5000)


