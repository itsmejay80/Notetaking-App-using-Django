# Simple Django Note Taking App

Welcome to the Simple Django Note Taking App! This application allows users to create, read, update, and delete notes. It's built using the Django framework, providing a user-friendly interface for managing your notes.

## Features

- User Authentication: Users can register, log in, and log out securely.
- Note Creation: Create new notes with a title and content.
- Note List: View a list of all your notes on the dashboard.
- Note Detail: Click on a note to view its full details.
- Note Update: Edit and update notes at any time.
- Note Deletion: Delete notes you no longer need.

## Installation

1. Clone the repository to your local machine:

   ```bash
   git clone https://github.com/yourusername/simple-django-notes.git
   ```

2. Navigate to the project directory:

   ```bash
   cd simple-django-notes
   ```

3. Create a virtual environment:

   ```bash
   python -m venv venv
   ```

4. Activate the virtual environment:

   - On Windows:

     ```bash
     venv\Scripts\activate
     ```

   - On macOS and Linux:

     ```bash
     source venv/bin/activate
     ```

5. Apply migrations to set up the database:

   ```bash
   python manage.py migrate
   ```

6. Create a superuser account (admin) to access the admin panel:

   ```bash
   python manage.py createsuperuser
   ```

7. Run the development server:

   ```bash
   python manage.py runserver
   ```

8. Access the application in your web browser by navigating to `http://localhost:8000`.

## Usage

1. Register a new account or log in with your existing credentials.
2. Once logged in, you will be directed to the dashboard.
3. Create a new note by clicking the "New Note" button and filling in the title and content.
4. Your notes will be listed on the dashboard. Click on a note to view its details.
5. Edit a note by clicking the "Edit" button on the note detail page.
6. Delete a note by clicking the "Delete" button on the note detail page.
7. Log out when you're done using the app.

## Technologies Used

- Django: A high-level Python web framework for rapid development.
- Bootstrap: A popular front-end framework for building responsive and stylish web pages.
- SQLite: A lightweight and easy-to-use database for development purposes.
