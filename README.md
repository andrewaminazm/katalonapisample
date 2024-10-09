Katalon API Sample
This repository provides a sample automation framework for testing APIs using Katalon Studio. It serves as a basic guide for API testing, including examples for sending requests, verifying responses, and handling different types of APIs (REST and SOAP).

Table of Contents
Prerequisites
Installation
Project Structure
Test Execution
Customization
Contributing
License
Prerequisites
Before running this project, ensure you have the following tools installed on your machine:

Katalon Studio (version 8.0.0 or above)
Java Development Kit (JDK) 1.8 or later
Installation
Clone this repository to your local machine using:

bash
Copy code
git clone https://github.com/andrewaminazm/katalonapisample.git
Open Katalon Studio.

In Katalon Studio, click on File > Open Project and select the cloned project folder.

Project Structure
Test Cases/: Contains the test cases for API testing.
Object Repository/: Stores API endpoints and their corresponding request/response objects.
Data Files/: Provides any necessary input data for API requests.
Reports/: Contains test execution reports.
Important Files
GlobalVariable.groovy: Holds global variables like base URLs, tokens, and other commonly used parameters.
Test Suite/: Groups multiple test cases to be executed together.
Test Execution
Open Katalon Studio.

Select a test case from the Test Cases folder or run all tests within a test suite located in the Test Suite folder.

To execute a test, right-click on the test case or suite and select Run.

Once the tests are executed, Katalon will generate a detailed report in the Reports folder.

Customization
API Endpoints: You can add or modify API requests in the Object Repository by creating new web service objects.
Variables: Add global or local variables in test cases to reuse across different test scenarios.
Assertions: Katalon Studio provides built-in keywords for response verification. Customize assertions in test cases to fit the expected behavior of your APIs.
Contributing
If you'd like to contribute to this project:

Fork the repository.
Create a new branch (git checkout -b feature-branch).
Make your changes.
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-branch).
Create a new Pull Request.
