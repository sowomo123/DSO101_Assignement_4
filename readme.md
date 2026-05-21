
# DSO101 — Assignment 4

Repository: https://github.com/sowomo123/DSO101_Assignement_4.git

## Overview

This assignment contains a small Python/Flask application with unit tests using `pytest`. The project demonstrates a simple web service, accompanying tests, and the basic structure to run and verify the app locally.

## Features

- Flask-based web application
- Unit tests with `pytest`
- Minimal dependencies listed in `requirements.txt`

## Requirements

- Python 3.8+
- pip

Install dependencies:

```bash
python -m venv .venv
.venv\Scripts\activate    # Windows
pip install -r requirements.txt
```

## Run the app

From the `DSO101_Assignement_4` directory you can start the app directly (example):

```bash
python app.py
# or, if using the flask subfolder version:
python flask/app.py
```

Then open http://127.0.0.1:5000 in your browser.

## Run tests

Run the test suite with `pytest` from the assignment root:

```bash
pytest -q
```

Test output (example screenshot) is available at `public/images/pytest.png`.

## Project structure

- `app.py` — main application entry (root)
- `flask/` — alternate Flask app and test helper files
- `requirements.txt` — Python dependencies
- `public/images/` — static images (including pytest screenshots)





