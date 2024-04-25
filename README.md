# Permalist - Simple To-Do List Application

Permalist is a simple web-based to-do list application built with Node.js, Express.js, PostgreSQL, and EJS. It allows users to create, edit, and delete to-do list items.

## Features

- Add new to-do list items.
- Edit existing to-do list items.
- Delete to-do list items.
- View a list of to-do list items.

## Setup

1. **Clone the Repository:**
   ```bash
   https://github.com/knull23/Permalist-Project.git
   ```
2. **Install Dependencies:**
   ```bash
   install npm init -y
   install express ejs axios
   node index.js
   ```
3. **Set up PostgreSQL:**

- Make sure you have PostgreSQL installed and running on your machine.
- Create a database named `permalist`.
- Execute the SQL commands in the `database.sql` file to create the required tables.

4. **Configure Database Connection:**

- Open `index.js` and modify the database connection parameters (`user`, `host`, `database`, `password`, `port`) in the `db` object to match your PostgreSQL configuration.

5. **Run the Application:**
```bash
npm start
```
6. **Access the Application:**

Open your web browser and go to `http://localhost:3000` to access the application.

## Usage

- On the homepage, you'll see a list of existing to-do list items.
- To add a new to-do list item, enter the item title in the input field and click "Add".
- To edit an existing to-do list item, click on the edit icon next to the item, update the title, and click "Save".
- To delete a to-do list item, click on the delete icon next to the item.

## Contributions
Contributions are welcome! If you find any bugs or want to add new features, feel free to open an issue or submit a pull request.
