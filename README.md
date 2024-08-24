**# Flask E2E Testing Project**

A comprehensive Flask web application project with end-to-end (E2E) testing using Selenium and pytest.

**## Project Overview**

This project demonstrates the creation of a simple web application using Flask and the implementation of end-to-end testing to simulate user interactions. The tests ensure the entire flow from the UI to the backend works as expected.

**## Technologies Used**

- **Flask**: A lightweight WSGI web application framework in Python.
- **Selenium**: A portable framework for testing web applications.
- **pytest**: A framework that makes building simple and scalable test cases easy.
- **HTML/CSS**: For building the front-end interface.

**## Project Structure**

- `app/`: Contains the Flask application code.
- `tests/`: Contains the end-to-end test cases written in Selenium and pytest.
- `templates/`: HTML templates used by Flask to render web pages.
- `static/`: Static files such as CSS and JavaScript.

**## Getting Started**

Follow these steps to get the project up and running on your local machine.

**### Prerequisites**

- Python 3.7 or higher
- pip (Python package installer)
- Git

**### Installation**

**1. Clone the repository:**

    ```bash
    git clone https://github.com/DeepPyLab/Flask-E2E-Testing-Project.git
    cd Flask-E2E-Testing-Project
    ```

**2. Create a virtual environment and activate it:**

    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

**3. Install the required packages:**

    ```bash
    pip install Flask selenium pytest pytest-flask
    ```

**### Running the Application**

```bash
python app.py
```

Open your web browser and navigate to **http://127.0.0.1:5000/** to view the application.

**Contributing**

Feel free to submit issues or pull requests. For major changes, please open an issue first to discuss what you would like to change.

