# Django-React Project

This project combines a Django backend with a React frontend using Vite. The Django server handles backend functionalities, while the React app provides a modern frontend experience. Follow the steps below to get the code and run both servers.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Backend Setup (Django)](#backend-setup-django)
- [Frontend Setup (React Vite)](#frontend-setup-react-vite)
- [Running the Servers](#running-the-servers)
- [License](#license)

## Prerequisites

Before you start, ensure you have the following software installed on your system:

- [Python 3.x](https://www.python.org/downloads/)
- [Node.js & npm](https://nodejs.org/)
- [Git](https://git-scm.com/)

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/Ahmaaadm/Django-project.git
    cd Django-project
    ```

## Backend Setup (Django)

1. **Create a Virtual Environment** (Optional but recommended):
    ```bash
    python -m venv venv
    ```

2. **Activate the Virtual Environment**:
    - On Windows:
      ```bash
      venv\Scripts\activate
      ```
    - On macOS/Linux:
      ```bash
      source venv/bin/activate
      ```

3. **Install Backend Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Apply Migrations**:
    ```bash
    python manage.py migrate
    ```

5. **Create a Superuser** (for accessing the admin interface):
    ```bash
    python manage.py createsuperuser
    ```

6. **Run the Django Development Server**:
    ```bash
    python manage.py runserver
    ```

    The server will start at `http://127.0.0.1:8000`.

## Frontend Setup (React Vite)

1. **Navigate to the Frontend Directory**:
    ```bash
    cd frontend  # Change this to your actual frontend directory if different
    ```

2. **Install Frontend Dependencies**:
    ```bash
    npm install
    ```

3. **Start the React Vite Development Server**:
    ```bash
    npm run dev
    ```

    The server will start at `http://localhost:5173`.

## Running the Servers

1. **Start the Django Backend**:
    ```bash
    python manage.py runserver
    ```

2. **Start the React Vite Frontend**:
    ```bash
    npm run dev
    ```

Visit `http://localhost:5173` to view the frontend and interact with the backend.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to open issues or submit pull requests. Contributions are welcome!

---

**Note**: Ensure that both the Django and React Vite servers are running simultaneously for the application to function correctly.
