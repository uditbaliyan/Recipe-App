
# Recipe App

A Django-based web application that allows users to browse, add, and manage recipes.

## Features

- View a list of recipes.
- Add new recipes with details such as ingredients and instructions.


## Installation

Follow these steps to set up and run the project locally.

### Prerequisites

- Python 3.x
- pip
- Django

### Clone the Repository

```bash
git clone https://github.com/uditbaliyan/Recipe-App.git
cd Recipe-App
```

### Set Up Virtual Environment

It's a good practice to use a virtual environment to manage dependencies. You can create one using `venv`.

```bash
python -m venv env
source env/bin/activate  # On Windows use `env\Scripts\activate`
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Migrations

```bash
python manage.py migrate
```

### Create a Superuser

Create a superuser to access the admin panel.

```bash
python manage.py createsuperuser
```

### Run the Server

```bash
python manage.py runserver
```

Navigate to `http://127.0.0.1:8000` in your browser to see the application in action.

## Usage


1. Add a new recipe by providing the required details.
2. View the list of all recipes.



## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- [Django](https://www.djangoproject.com/)
- [Bootstrap](https://getbootstrap.com/) for front-end design

