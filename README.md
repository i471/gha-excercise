# gha-learning-app/gha-learning-app/README.md

# GHA Learning App

This project is a simple Python application designed to help you learn about GitHub Actions (GHA). It includes a workflow that checks if the copyright year in the source code is current.

## Overview

The application contains a copyright header in the main Python file, and the GitHub Actions workflow automatically verifies that the year in the header matches the current year.

## Files in the Project

- `src/main.py`: The main application file containing the copyright header.
- `.github/workflows/check-copyright-year.yml`: The GitHub Actions workflow configuration that checks the copyright year.
- `.gitignore`: Specifies files and directories to be ignored by Git.

## How to Run the Application

1. Clone the repository to your local machine.
2. Navigate to the project directory.
3. Run the application using Python:

   ```bash
   python src/main.py
   ```

## GitHub Actions

The GitHub Actions workflow will run automatically on push and pull request events. It checks the copyright year in `main.py` to ensure it is up to date.

## Additional Information

Make sure to keep the copyright year updated in the `main.py` file to avoid workflow failures.