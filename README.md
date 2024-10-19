# Recipe Management Application

## Description
The Recipe Management Application is a full-stack web app built with React (frontend) and Node.js/Express (backend) that allows users to manage recipes. Users can create, view, edit, and delete recipes, while also searching based on ingredients or cuisine type.

## Tasks
### Task 1: Frontend Development
**Title:** Recipe Management Frontend  
**Description:** Build a responsive and intuitive user interface using React.  
**Requirements:**
- **Components:**
  - Recipe Listing: Displays all recipes with a search bar for filtering based on ingredients or cuisine type.
  - Recipe Detail View: Shows recipe details (title, ingredients, instructions, cook time, cuisine type) with options to edit or delete.
  - Forms: Includes forms for creating and editing recipes with fields such as title, ingredients, instructions, cuisine type, and cook time.
- **Styling:** Tailwind CSS or Bootstrap for modern and responsive design.
- **State Management:** Utilizes React hooks (`useState`, `useEffect`) for managing state.
  
### Task 2: Backend Development
**Title:** Recipe Management Backend  
**Description:** Develop a REST API using Node.js, Express, and MongoDB to manage recipes and user authentication.  
**Requirements:**
- **API Endpoints:**
  - User Authentication: Registration and login with JWT-based authentication.
  - Recipe CRUD Operations: Create, read, update, and delete recipes.
- **Database:** MongoDB schema for recipes including fields for title, ingredients, instructions, cuisine type, author, and timestamps.
- **Error Handling:** Handles invalid requests and server errors gracefully.


## Features
- Recipe CRUD operations (Create, Read, Update, Delete)
- User authentication with JWT
- Search functionality for filtering recipes
- Responsive UI using Tailwind CSS/Bootstrap

## Technologies
- **Frontend:** React, Axios, Tailwind CSS/Bootstrap
- **Backend:** Node.js, Express, MongoDB, JWT Authentication

## Setup Instructions
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/recipe-management-app.git

2. **Backend:**
   
   Navigate to the backend folder:
     ```bash
     cd backend
     ```

   Install dependencies:
     ```bash
     npm install
     ```
    Create a .env file and add the following environment variables:
  
    ```bash
    MONGODB_URI=your_mongodb_uri
    JWT_SECRET=your_jwt_secret
    PORT=5000
    ```

    Start the backend server:
    ```bash
    npm start
    ```

3. Frontend:

    Navigate to the frontend folder:
     ```bash
     cd frontend food-blog-app
      ```
     
    Install dependencies:
     ```bash
     npm install
      ```

    Start the frontend server:
     ```bash
     npm run dev
     ```

## API Endpoints

  POST **/api/auth/register** - Register a new user
  POST **/api/auth/login** - Login an existing user
  POST **/api/recipes** - Create a new recipe (auth required)
  GET **/api/recipes** - Get all recipes
  GET **/api/recipes/:id** - Get a recipe by ID
  PUT **/api/recipes/:id** - Update a recipe (auth required)
  DELETE **/api/recipes/:id** - Delete a recipe (auth required)

     

