# Student CRUD Project

This is a simple Django web application that allows you to perform CRUD (Create, Read, Update, Delete) operations for managing student records.

## Table of Contents
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Contributing](#contributing)
- [License](#license)

## Requirements

- Python 3.x
- Django 3.x or higher

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/G4GIFTEDHANDS/CRUD-PROJECT.git
    cd student_crud
    ```

2. **Create a virtual environment:**

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

3. **Install the dependencies:**

    ```bash
    pip install django
    ```

4. **Apply migrations:**

    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

5. **Run the development server:**

    ```bash
    python manage.py runserver
    ```

6. **Access the application:**

    Open your web browser and go to `http://127.0.0.1:8000/students/`

## Usage

- **List Students:** View the list of all students.
- **Add Student:** Add a new student to the list.
- **Edit Student:** Update the details of an existing student.
- **Delete Student:** Remove a student from the list.

## Features

- A Student model with fields for name, age, email, phone, location, and hobby.
- CRUD views to create, read, update, and delete student records.
- Simple, unstyled HTML templates for each CRUD operation.

## Contributing

1. **Fork the repository**
2. **Create a new branch:**

    ```bash
    git checkout -b feature/your-feature-name
    ```

3. **Make your changes and commit them:**

    ```bash
    git commit -m "Add some feature"
    ```

4. **Push to the branch:**

    ```bash
    git push origin feature/your-feature-name
    ```

5. **Create a pull request**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

