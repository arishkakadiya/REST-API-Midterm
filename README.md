# REST-API-Midterm

Here’s a README file tailored for the Student API with similar instructions:

---

This project demonstrates a simple REST API built with Python's Flask framework, designed to manage student data with CRUD (Create, Read, Update, Delete) operations. This API can be tested locally and is prepared for deployment to Azure App Service for cloud hosting.

## Features

- Retrieve all students
- Retrieve a specific student by ID
- Create a new student
- Update an existing student
- Delete a student

## Prerequisites

Before you can run or deploy this app, make sure you have the following installed:

- Python 3.x
- pip (Python package manager)
- Flask (`pip install Flask`)
- gunicorn (`pip install gunicorn`)
- Azure CLI (optional, for deployment)

## Project Structure

- `app.py`: Main Flask application file for handling Student data
- `requirements.txt`: List of Python dependencies
- `test.http`: File to test the REST API endpoints using REST Client in Visual Studio Code
- `README.md`: Documentation for setup and usage

## Running Locally

To run the Flask API on your local machine:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/arishkakadiya/REST-API-Midterm
   ```

2. **Navigate to the project directory:**

   ```bash
   cd REST-API-Midterm
   ```

3. **Install the dependencies:**

   ```bash
   pip install -r requirements.txt
   ```

4. **Run the application:**

   ```bash
   python app.py
   ```

5. **Access the API:**

   The API will be running at `http://127.0.0.1:8000`.

6. **Test the API Endpoints:**

   Use `test.http` to test the REST API using the REST Client extension in Visual Studio Code.

## Deploying to Azure


- Within Azure Portal, created Web App resources 
- Then once service is created, went to Deployment center under Deployment 
- Then in settings connected selected source as GitHub and then selected the REST-API-Midterm repository, clicked on save to start deploying 
- Once deployed it will create .github/workflows folder within Github Repository
