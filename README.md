# Portfolio

### by [Girendra Singh](https://github.com/Giru-03)

## About this project

This is a multi-page portfolio web application built using Django. The main aim of this project is to showcase the client's skills, projects, and contact information in a professional manner.

## Features

- **Home Page**: Introduction and a brief overview of the client's profile.
- **About Page**: Detailed information about the client's background, skills, and experience.
- **Resume Page**: A comprehensive resume of the client, including education, work experience, and skills.
- **Services Page**: A list of services offered by the client.
- **Contact Page**: A form to contact the client via email.

## Installation requirements

<b>Framework used:</b> Django

The following dependencies must be installed using pip to run this web application.

<details>
<summary><b>Python dependencies</b></summary>

- Django==4.2.9
- asgiref==3.7.2
- gunicorn==21.2.0
- packaging==23.2
- sqlparse==0.4.4
- tzdata==2023.4

</details>

## Working / Usage instructions

1. Clone the repository:
    ```sh
    git clone https://github.com/your-github-username/portfolio.git
    cd portfolio
    ```

2. Create a virtual environment and activate it:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

4. Apply migrations:
    ```sh
    python manage.py migrate
    ```

5. Run the development server:
    ```sh
    python manage.py runserver
    ```

6. Open your browser and go to `http://127.0.0.1:8000/` to view the portfolio.

## Implementation details

### _**core**_

This folder contains the main application code, including views, URLs, and templates.

- **views.py**: Contains the view functions for rendering the templates.
- **urls.py**: Defines the URL patterns for the application.
- **templates**: Contains the HTML templates for the different pages.

### _**portfolio**_

This folder contains the project settings and configuration files.

- **settings.py**: Contains the project settings, including database configuration and static files settings.
- **urls.py**: Defines the URL patterns for the project.
- **wsgi.py**: WSGI configuration for deploying the project.
- **asgi.py**: ASGI configuration for deploying the project.

### _**static**_

This folder contains all the static files necessary for this web application. This includes the following **CSS files**:

- **style.css**: Main stylesheet for the application.
- **admin/**: Contains the static files for the Django admin interface.

### _**templates**_

This folder contains the HTML templates for all the different routes in this web application.

- **index.html**: Template for the home page.
- **about.html**: Template for the about page.
- **resume.html**: Template for the resume page.
- **service.html**: Template for the services page.
- **contact.html**: Template for the contact page.

### _**db.sqlite3**_

This is the database that is used to store all the user and contact information entered into this web application.

### _**requirements.txt**_

This file contains the names of the required Python dependencies that need to be installed before launching this web application.

## References

- [Django](https://www.djangoproject.com/)