# Student Grade Calculator

A simple Python application that calculates the average grade of a student
and determines whether the student passes.

#Features

      Calculate the average of a list of grades.

     Check whether a student passes.

     Classify an average into one of four categories:

                      Excellent: 16 or higher

                     Good: from 12 to below 16

                     Average: from 10 to below 12

                     Fail: below 10

#Requirements

         Python 3.11 or a compatible Python version

         pip

#Installation

     1. Clone the repository:

           git clone https://github.com/mariaanfel/grade-calculator.git cd grade-calculator

      2.Install the dependencies:

              python -m pip install -r requirements.txt

#Usage
       The application provides functions in calculator.py.

#Run Tests

         Execute the following command from the project directory:  pytest -v

#Run Linting

        To check code quality with Flake8: flake8 .

#Continuous Integration

         GitHub Actions automatically runs linting and tests when code is pushed to main or         when a pull request targets main.

