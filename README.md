# Mtask - Task Management System

**Mtask** is a task management system built using the Django framework, designed to help individuals and teams organize, prioritize, and track tasks efficiently. It provides a simple and intuitive interface for managing tasks, collaborating with team members, and keeping track of deadlines.

---

## Features

- **User Authentication**: Secure login and registration system with user-specific access.
- **Task Management**: Create, update, and delete tasks with customizable statuses.
- **Task Assignment**: Assign tasks to team members with specific deadlines and priorities.
- **Task Categories**: Organize tasks into categories for better classification and management.
- **Task Progress Tracking**: Monitor the progress of tasks through various stages.
- **User Roles**: Admins can manage users, while regular users can only manage their own tasks.
- **Team Collaboration**: Share tasks with team members and work collaboratively on projects.
- **Notifications**: Receive alerts for upcoming deadlines and task updates.

---

## Technologies Used

- **Django**: Backend web framework for rapid development.
- **SQLite**: Database used for storing task data (default for Django).
- **Bootstrap**: Frontend framework for responsive design.
- **HTML/CSS/JavaScript**: For structuring and styling the web pages.
- **Django Rest Framework (DRF)**: For implementing APIs (if applicable).
- **Celery (optional)**: For handling background tasks like sending email notifications (if integrated).

---

## Installation

### Prerequisites

1. **Python**: Ensure that Python 3.x is installed on your system.
2. **Pip**: Python's package installer.

### Steps to Install

1. Clone the repository:

```bash
git clone https://github.com/000-dir-wmi-0001/Mtask.git
```

2. Navigate into the project directory:

```bash
cd Mtask
```

3. Create a virtual environment (recommended):

```bash
python3 -m venv venv
```

4. Activate the virtual environment:

   - On Windows:

   ```bash
   venv\Scripts\activate
   ```

   - On macOS/Linux:

   ```bash
   source venv/bin/activate
   ```

5. Install the required dependencies:

```bash
pip install -r requirements.txt
```

6. Apply the migrations to set up the database:

```bash
python manage.py migrate
```

7. Create a superuser to access the admin panel:

```bash
python manage.py createsuperuser
```

Follow the prompts to set up the superuser account.

8. Start the development server:

```bash
python manage.py runserver
```

The application should now be running at `http://127.0.0.1:8000/`.

---

## Usage

1. Open the app in your browser at `http://127.0.0.1:8000/`.
2. Log in using the credentials for the superuser or a regular user account.
3. Navigate to the **Tasks** section to create, view, and manage tasks.
4. Use the **Admin Panel** (available at `http://127.0.0.1:8000/admin/`) to manage users and other administrative tasks.
5. Assign tasks to team members and track their progress through the interface.

---

## Contributing

We welcome contributions! If you'd like to improve **Mtask**, feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create a new branch for your changes
3. Commit your changes
4. Push your branch and open a pull request

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Thanks to the contributors and developers behind the Django framework and all the libraries used in the project.
- Special thanks to the open-source community for their contributions to the tools and packages utilized.

---

### Screenshots
