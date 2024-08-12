## Description

`newreqres` is a Python-based testing project designed to validate API endpoints using the ReqRes API. The project includes tests for various HTTP methods including GET, POST, PUT, PATCH, and DELETE requests. It leverages pytest for test execution and Allure for generating detailed test reports.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Configuration](#configuration)
- [Testing](#testing)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Features

- **GET Requests**: Test endpoints for listing users, single user retrieval, and handling delays.
- **POST Requests**: Validate user registration and login functionalities.
- **PUT/PATCH Requests**: Test updating user information.
- **DELETE Requests**: Verify user deletion.
- **Allure Reporting**: Integration for detailed test reports.

## Installation

To set up the project locally, follow these steps:

1. **Clone the Repository**:
    ```bash
    git clone <repository-url>
    cd reqresnew
    ```

2. **Set Up a Virtual Environment** (recommended):
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3. **Install Dependencies**:
    ```bash
    pip install -r requirements.txt
    ```

4. **Install Allure**:
    Follow the [Allure installation guide](https://docs.qameta.io/allure/) to install Allure CLI.

## Usage

### Running Tests

To execute the tests, use the following command:

```bash
pytest --alluredir=allure-results