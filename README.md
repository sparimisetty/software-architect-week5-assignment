# Hello World Django App

This is a simple Django app that returns a JSON object with a Hello World message.

## Prerequisites

- Python 3.x
- Pip
- Virtualenv (optional but recommended)

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/sparimisetty/software-architect-week5-assignment.git
    ```

2. Navigate to the project directory:

    ```bash
    cd helloworld-django-app
    ```

3. Set up a virtual environment (optional but recommended):

    ```bash
    python -m venv myenv
    source myenv/bin/activate
    ```

4. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

5. Apply database migrations:

    ```bash
    python manage.py migrate
    ```

6. Run the development server:

    ```bash
    python manage.py runserver
    ```

The app should now be accessible at [http://127.0.0.1:8000/helloworld/hello/](http://127.0.0.1:8000/helloworld/hello/). You should see a JSON response: `{"Message": "Hello World!"}`.

## Project Structure

- `helloworldproject/`: Django project directory.
- `helloworldapp/`: Django app directory.

## Additional Information

- Customize the app as needed by modifying the views, templates, or static files.
- Add more routes or functionality to suit your requirements.
