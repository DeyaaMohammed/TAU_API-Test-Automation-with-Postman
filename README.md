# Test Automation University - API Test Automation with Postman

This repository contains resources related to the "API Test Automation with Postman" course at Test Automation University (TAU). Here, you'll find Postman collections and environments, along with my solutions to the course quizzes.

## Table of Contents

- [Introduction](#introduction)
- [Topics Covered](#topics-covered)
- [Directory Structure](#directory-structure)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributions](#contributions)
- [Disclaimer](#disclaimer)

## Introduction

The "[API Test Automation with Postman](https://testautomationu.applitools.com/postman-tutorial/)" course on Test Automation University is a great resource for learning and mastering APIs. From diving into the secrets of RESTful APIs to creating powerful and automated test suites, this course is a great guide for enhancing API testing skills in a way that's both engaging and easy to grasp.\
This repository contains the test collections I created during the course and my solutions to the quizzes presented at the end of every chapter throughout the course.

## Topics Covered
- Installation and Setup
- Importing Tests
- Creating and Running Mocks
- Monitors in Postman
- Postman Workspaces
- Newman Runner
- Postman Reports

## Directory Structure

The repository is organized as follows:

- `Chapter X/`: Each lecture from the course has its own directory.
  - `Chapter X Quiz.txt`: A text file corresponding to the quiz for the lecture. These files contain my solutions to the quiz questions.
- `testResults/`: The directory where HTML Reports are located.
  - `htmlreport.html`:  This HTML file provides a detailed overview of the test execution results.
- `Restful Booker BVT.postman_collection.json`: This file contains a collection of API requests, organized and grouped for testing the Restful-Booker API. It is used to perform various API tests.
- `NASA - Astronomy Picture of the Day (APOD).postman_collection.json`: This file contains a collection of API requests, organized and grouped for testing the NASA's Picture Of the Day API.
- `Production.postman_environment.json`: This file stores the environment-specific variables and configurations used for the production testing environment.

## Getting Started

1. Install Postman: [https://www.postman.com/downloads/](https://www.postman.com/downloads/)
2. Import Collections:
    - Download the entire repository or specific files.
    - In Postman, open `"File"` -> `"Import"` -> `"Select Files"` and choose the downloaded files.
3. Configure Environments:
    - Choose the Production environment file for your testing environment (i.e., "Production.postman_environment.json").
    - Go to `"File"` -> `"Import"` -> `"Select Files"` and select the chosen file.
4. Run Tests:
    - Within the collection, you can run individual requests or the entire collection.
    - For detailed instructions on test execution, refer to the TAU course materials.

## Usage

You can go ahead and explore my collection and quiz solutions by navigating to the specific chapter and associated directories within the repository. Each quiz text file contains my quiz answers.

Feel free to use these collections as reference code, study materials, or review materials to enhance your understanding of Postman. Additionally, you can review my quiz solutions to reinforce your knowledge of the course content.

## Contributions

Contributions to this repository are welcome. If you have alternative code implementations, suggestions for improvements, or corrections to my answers, please consider submitting a pull request. If you encounter any issues with my solutions or have additional insights to share, please open an issue.

## Disclaimer
> This is not the official implementation. The official implementation may be found [here](https://github.com/askherconsulting/explore-with-postman).
