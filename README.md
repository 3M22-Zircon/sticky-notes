# Sticky Notes Task Manager Application

## Description
This project is a Sticky Notes Task Manager application developed using Django. It implements the Model-View-Template (MVT) architecture and includes CRUD functionality to create, read, update, and delete notes. This project is important for learning how to structure a web application, manage data, and create interactive user interfaces.

## Table of Contents
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/sticky-notes.git
    ```

2. Navigate to the project directory:
    ```bash
    cd sticky-notes
    ```

3. Create and activate a virtual environment:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

4. Install the required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

5. Apply the database migrations:
    ```bash
    python manage.py makemigrations
    python manage.py migrate
    ```

6. Start the development server:
    ```bash
    python manage.py runserver
    ```

## Usage
After starting the development server, open your web browser and navigate to `http://127.0.0.1:8000/`. You can create, read, update, and delete sticky notes using the user interface.

![Screenshot](screenshots/home_page.png)
![Screenshot](screenshots/create_note.png)

## Credits
Developed by Mujahid Hosein
