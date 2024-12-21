## Task Manager

Task Manager is a web application built with Flask that allows users to manage their tasks. Users can create, edit, delete, and mark tasks as complete. The application also supports user authentication and categorization of tasks.

## Features

- User authentication (login, logout, register)
- Create, edit, delete tasks
- Mark tasks as complete or incomplete
- Categorize tasks
- Set priority levels for tasks
- Set due dates for tasks

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/task-manager.git
    cd task-manager
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv .venv
    source .venv/bin/activate 
    ```

3. Install the dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Set up the database:
    ```sh
    flask db upgrade
    ```

5. Run the application:
    ```sh
    flask run
    ```

## Usage

- Visit `http://127.0.0.1:5000/` in your web browser.
- Register a new account or log in with an existing account.
- Start managing your tasks!

## Project Structure

- : The main application file.
- : Contains HTML templates for the application.
  - : The main page where tasks are listed.
  - : The page for editing a task.
  - `login.html`: The login page.
  - `register.html`: The registration page.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.
