Flask Todo App: 
This is a simple Todo list web application built using Flask, a micro web framework for Python, and SQLAlchemy, a Python SQL toolkit and Object-Relational Mapping (ORM) library.

Features

~ Add Task: Users can add new tasks to the Todo list.

~ Delete Task: Users can delete tasks from the Todo list.

~ Update Task: Users can update the content of existing tasks.

~ Display Tasks: Tasks are displayed on the main page in chronological order based on their creation date.

File Structure

~ app.py: Contains the main Flask application code.

~ templates/index.html: HTML template for the main page displaying the Todo list.

~ templates/update.html: HTML template for the update task page.

Dependencies

~ Flask

~ Flask-SQLAlchemy

Database: The application uses SQLite as the database management system, with a single table named Todo. This table has the following columns:

~ id: Primary key auto-incrementing integer.
~ content: String content of the task.
~ date_created: Date and time when the task was created.
