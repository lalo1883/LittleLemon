# Little Lemon

Web application built with Django for restaurant reservations

## Requirements

Make sure you have Python and pip installed. You can download Python from [python.org](https://www.python.org/downloads/), and pip comes included with recent Python versions.

## Virtual Environment Setup (Optional but Recommended)

It's recommended to use a virtual environment to manage your project dependencies and avoid conflicts with other applications. Create a virtual environment with the following command:

```bash
python -m venv venv
```

Then, activate the virtual environment:

On Windows:
```bash
venv\Scripts\activate
```

On Unix or MacOS:
```bash
source venv/bin/activate
```

## Installing Dependencies

Install project dependencies using the following command:

```bash
pip install -r requirements.txt
```

## Database Configuration

Perform initial migrations to set up the database:

```bash
python manage.py migrate
```

## Running the Project

Start the development server with the following command:

```bash
python manage.py runserver
```

The server will be available at [http://localhost:8000/](http://localhost:8000/). You can access the application from your web browser.

## Stopping the Server

To stop the server, press `Ctrl + C` in the terminal.

## Contribution

If you want to contribute to this project, follow these steps:

1. Fork the repository.
2. Create a branch (`git checkout -b feature/new-feature`).
3. Make your changes and commit (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature/new-feature`).
5. Create a new Pull Request.

Thank you for contributing!
