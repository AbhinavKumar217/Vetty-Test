# Flask File Viewer

This is a simple Flask application that allows you to view the content of text files. It provides a single endpoint where you can specify the file name and optionally specify start and end line numbers to view only a portion of the file.

## Features

- View the content of text files in the browser.
- Specify start and end line numbers to view a specific portion of the file.
- Handles exceptions gracefully and displays error details in case of errors.

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/AbhinavKumar217/flask-python-jr-test.git
    ```

2. Navigate to the project directory:

    ```bash
    cd flask-python-jr-test
    ```

3. Create and activate a virtual environment:

    ```bash
    python3 -m venv venv
    source venv/bin/activate
    ```

4. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. Run the Flask application:

    ```bash
    python app.py
    ```

2. Open a web browser and go to the prompted localhost URL.

3. You can specify the file name in the URL (e.g., `/file2.txt`) and optionally specify start and end line numbers as query parameters (e.g., `/?start=2&end=3`).

## Project Structure

- `app.py`: Main Flask application file.
- `templates/`: Directory containing HTML templates.
    - `display.html`: Template for displaying file content.
    - `error.html`: Template for displaying error messages.
- `requirements.txt`: List of Python dependencies.
