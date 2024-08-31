# Online Store — [ [RU](README.md) ] [ EN ]

This is an online store project developed using Django and PostgreSQL. It includes functionality for managing departments and products.

## Contents

- [Functionality](#functionality)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)

## Functionality

- Management of departments (categories).
- Adding, editing, and deleting products in departments.
- Viewing the list of departments and their associated products.
- Exported copy of the database for easy transfer.

## Technologies

- Python
- Django
- PostgreSQL
- HTML/CSS
- Bootstrap (for styling)

## Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/your_username/online_store.git
    cd online_store
    ```

2. **Create and activate a virtual environment:**

    ```bash
    python -m venv venv
    .\venv\Scripts\Activate  # For Windows
    source venv/bin/activate  # For Linux/Mac
    ```

3. Install dependencies:
    
    ```bash
    pip install -r requirements.txt
    ```

4. Set up the database:
   Make sure you have PostgreSQL installed and a database created. Update the database settings in the online_store/settings.py file.

5. Apply migrations:

    ```bash
    python manage.py migrate
    ```

6. Run the server:

    ```bash    
    python manage.py runserver
    ```

Now you can open the application in your browser at http://127.0.0.1:8000.
   
## Usage

To manage departments and products, use the interface available at http://127.0.0.1:8000/departments/.
You can add, edit, and delete departments and products through the corresponding buttons.
