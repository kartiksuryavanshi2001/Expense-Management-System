# Expense Management System

This project is an expense management system that consists of a Streamlit frontend application and a FastAPI backend server.

## Project Structure

 **frontend/**: Contains the Streamlit application code.

 **backend/**: Contains the FastAPI backend server code.

 **tests/**: Contains the test cases for both frontend and backend.

 **requirements.txt**: Lists the required Python packages.

 **README.md**: Provides an overview and instructions for the project.

## Setup Instructions

1. **Clone the repository**:

   '''bash

   git clone https://github.com/yourusername/expense-management-system.git

   cd expense-management-system
   '''


2. **Install dependencies:**:

   '''commandline

    pip install -r requirements.txt
   '''


3. **Run the FastAPI server:**:

   '''commandline
   
   uvicorn server.server:app --reload

1. **Run the Streamlit app:**:

   '''commandline

    streamlit run frontend/app.py

# pytest cache directory #

This directory contains data from the pytest's cache plugin,
which provides the `--lf` and `--ff` options, as well as the `cache` fixture.

**Do not** commit this to version control.

See [the docs](https://docs.pytest.org/en/stable/how-to/cache.html) for more information.

