# Job Board Application

This is a very simple job board application built with GraphQL, TypeScript, Node.js, and React.

## Features

* Users can view job details and description.
* Users can post jobs. 

## Technologies

* Frontend: React, TypeScript
* Backend: Node.js with Express, TypeScript
* Database: SQLite (for development)
* GraphQL: for API communication

## Installation

### Prerequisites
- Node.js (version 16 or higher)
- npm or yarn

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/georgiev098/graphql_ts_job_board_app
   cd job-board-app
   ```
2. Install dependencies for both the client and server:
   ```bash
   cd client
   npm install
   cd ../server
   npm install
   ```
3. Start the development servers:
   - **Client**:
     ```bash
     cd client
     npm start
     ```
   - **Server**:
     ```bash
     cd server
     npm start
     ```

# Project Structure
```plaintext
job-board-app/
|-- client/             # Front-end code (React)
|-- server/             # Back-end code (GraphQL, Node.js)
|-- README.md           # Project documentation
|-- package.json        # Project dependencies and scripts
```

## Client Code Structure
The client code is located in the `client` directory and is organized as follows:

```plaintext
client/
|-- public/             # Static files (e.g., index.html, favicon)
|-- src/                # Main source code
    |-- components/     # Reusable React components
    |-- generated/      # Generated GraphQL types and queries
    |-- lib/            # Utility functions and hooks for GraphQL API interactions
    |-- pages/          # Main application pages
```
## Server Code Structure
The server code is located in the `server` directory and is organized as follows:

```plaintext
server/
|-- src/                # Main source code
    |-- resolvers/      # GraphQL resolvers for handling API logic
    |-- schemas/        # GraphQL schema definitions
    |-- models/         # Database models (TypeORM or similar ORM)
    |-- utils/          # Utility functions for server operations
    |-- index.ts        # Entry point for the server
|-- package.json        # Server dependencies and scripts
```
