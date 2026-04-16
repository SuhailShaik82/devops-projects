# DevOps CI/CD Pipeline Project

A simple Python Flask application containerized with Docker and integrated with GitHub Actions for continuous integration.

## Problem Statement
Manual testing and deployment take time and can introduce errors. This project demonstrates how to automate testing and build workflows using DevOps practices.

## Solution
Built a lightweight Python web application, added automated testing using pytest, containerized it using Docker, and configured a CI pipeline using GitHub Actions.

## Tech Stack
- Python
- Flask
- Pytest
- Docker
- GitHub Actions

## Project Structure
- `app.py` - main Flask application
- `test_app.py` - test file
- `requirements.txt` - Python dependencies
- `Dockerfile` - container configuration
- `.github/workflows/ci.yml` - CI pipeline workflow

## Features
- Simple Flask app
- Health check endpoint
- Automated test execution
- Docker support
- CI pipeline on every push

## How to Run Locally
```bash
pip install -r requirements.txt
python app.py
