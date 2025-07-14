# Project Management Application

This is a Project Management Application built using Laravel 11 and React. It provides features for managing projects and tasks, including CRUD operations, user assignment, and dashboard views.

## Features

1. **User Authentication**: Registration and login functionality.
2. **Projects Management**:
    - Create, read, update, and delete projects.
    - Sorting, filtering, and pagination for projects.
3. **Tasks Management**:
    - Create, read, update, and delete tasks.
    - Assign tasks to users.
    - Sorting, filtering, and pagination for tasks.
4. **Task Assignment**:
    - Assign tasks to specific users.
    - View tasks assigned to the logged-in user.
5. **Dashboard**:
    - Overview of projects and tasks.

## Installation

Follow these steps to set up the project locally:

1. Clone the repository:

    ```bash
    git clone <repository-url>
    ```

2. Navigate to the project directory:
    ```bash
    cd <project-directory>
    ```
3. Create the `.env` file:
    ```bash
    cp .env.example .env
    ```
4. Install PHP dependencies:
    ```bash
    composer install
    ```
5. Install JavaScript dependencies:
    ```bash
    npm install
    ```
6. Generate the application key:
    ```bash
    php artisan key:generate --ansi
    ```
7. Run database migrations and seed data:
    ```bash
    php artisan migrate --seed
    ```
8. Start the Vite development server:
    ```bash
    npm run dev
    ```
9. Start the Laravel Artisan server:
    ```bash
    php artisan serve
    ```

## Usage

Once the servers are running, open the application in your browser at `http://localhost:8000`. You can register a new user or log in with existing credentials.

## Technologies Used

-   **Backend**: Laravel 11
-   **Frontend**: React
-   **Styling**: Tailwind CSS
-   **Build Tools**: Vite

## License

This project is licensed under the MIT License. See the LICENSE file for details.
