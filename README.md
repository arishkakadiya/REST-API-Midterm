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

- `student_api.py`: Main Flask application file for handling Student data
- `requirements.txt`: List of Python dependencies
- `student-api.http`: File to test the REST API endpoints using REST Client in Visual Studio Code
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

   Use `student-api.http` to test the REST API using the REST Client extension in Visual Studio Code.

## Deploying to Azure


Key features include:
- **Automatic Scaling**: Adjust resources based on traffic.
- **Continuous Integration/Continuous Deployment (CI/CD)**: Integrate with GitHub, Bitbucket, or Azure DevOps for automated deployments.
- **Custom Domains and SSL**: Secure your apps with custom domains and certificates.
- **Load Balancing**: Handle high-traffic applications with built-in load balancing.
- **Monitoring and Diagnostics**: Access logs and real-time monitoring for troubleshooting.

You can learn more about Azure App Service in the [official documentation](https://learn.microsoft.com/en-us/azure/app-service/).

### Deploying the Student API to Azure

For a step-by-step guide to deploying a Flask app to Azure App Service, follow the [Quickstart Guide](https://learn.microsoft.com/en-us/azure/app-service/quickstart-python?tabs=flask%2Cwindows%2Cazure-cli%2Cazure-cli-deploy%2Cdeploy-instructions-azportal%2Cterminal-bash%2Cdeploy-instructions-zip-azcli). This guide will walk you through deploying a Python web app to Azure, allowing your app to run in a scalable Linux environment.

--- 

This README provides setup, local execution, and deployment guidance for the Student API project. Let me know if you'd like further details or customization!