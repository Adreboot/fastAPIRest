# User Management System with FastAPI

## Project Description

In this project, we’ll create a user management system using FastAPI and SQLAlchemy as the object-relational mapping (ORM) to handle database operations.

The user management system will provide a comprehensive set of API endpoints to allow users to perform everyday tasks such as adding a new user, updating user information, fetching user details, and deleting user accounts.

The user management system will be integrated with a DBMS to allow for seamless storage and retrieval of user data. SQLAlchemy will manage database operations, including creating tables, inserting, updating, and deleting records, and querying the database.

## Installation

To install and set up this project, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/Adreboot/fastAPIRest.git
    cd fastAPIRest
    ```

2. Create and activate a virtual environment:
    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. Install the required dependencies using `pip`:
    ```bash
    pip install fastapi SQLAlchemy uvicorn
    ```

## Usage

To start the FastAPI server, use the following command:
```bash
uvicorn main:app --reload
