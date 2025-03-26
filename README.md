# TodoContextLocal

A advance Todo application with user authentication using Redux for state management. This project demonstrates how to manage state in a React application and protect routes based on user authentication.

## Features

- User authentication (login/logout) using Redux
- Add, update, delete, and toggle completion status of todos
- Persist todos in local storage
- Protect todo list behind authentication

## Project Structure


src/ ├── components/ │ ├── Login.jsx │ ├── Logout.jsx │ ├── TodoForm.jsx │ ├── TodoList.jsx ├── contexts/ │ ├── index.js ├── App.jsx ├── App.css ├── index.css ├── main.jsx ├── store.js



## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- npm (v6 or higher)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/todocontextlocal.git
   cd todocontextlocal

Install dependencies:
   npm install

Start the development server:
npm start

Open your browser and navigate to http://localhost:3000.

## Usage
Login: Click the "Login" button to simulate user authentication.
Logout: Click the "Logout" button to log out.
Add Todo: Use the form to add a new todo.
Update Todo: Click on a todo to update its content.
Delete Todo: Click the delete button to remove a todo.
Toggle Complete: Click the checkbox to mark a todo as complete or incomplete.


## Contributing
Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
