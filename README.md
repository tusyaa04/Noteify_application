# Noteify

**Noteify** is a full-stack Notes Application built with the MERN stack (MongoDB, Express.js, React.js, Node.js). It provides a seamless experience for managing your notes with features such as authentication, note creation/editing, pinning important notes, and a search functionality.

## Features

- **User Authentication**: Sign up and log in to securely access your notes.
- **Add/Edit Notes**: Create new notes and edit existing ones.
- **Pin Notes**: Highlight important notes by pinning them.
- **Search Functionality**: Easily find notes with the search feature.

## Technologies Used

- **Frontend**: React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (MongoDB Atlas for cloud-based storage)
- **Authentication**: JWT (JSON Web Tokens)

## Installation

To get started with Noteify locally, follow these steps:

1. **Clone the repository**:
    ```bash
      https://github.com/tusyaa04/Noteify_application.git

https://github.com/user-attachments/assets/a36dce1b-85f1-48be-97e9-82d7ce7ae056


    ```

2. **Navigate to the project directory**:
    ```bash
    cd noteify
    ```

3. **Install dependencies**:

    - For the backend:
      ```bash
      cd backend
      npm install
      ```

    - For the frontend:
      ```bash
      cd ../frontend
      npm install
      ```

4. **Set up environment variables**:
    - Create a `.env` file in the `backend` directory with the following content:
      ```plaintext
      MONGO_URI=your_mongodb_connection_string
      JWT_SECRET=your_jwt_secret
      ```
    - Replace `your_mongodb_connection_string` and `your_jwt_secret` with your actual MongoDB connection string and JWT secret key.

5. **Start the development server**:
    - For the backend:
      ```bash
      cd backend
      npm start
      ```
    - For the frontend:
      ```bash
      cd ../frontend
      npm start
      ```

## Usage

1. Open your browser and navigate to `http://localhost:5173` to access the application.
2. Sign up or log in to access your notes.
3. Use the interface to add, edit, pin, and search your notes.

