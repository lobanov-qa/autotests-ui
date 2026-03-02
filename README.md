# UI Course Automation Tests
## **English** | **[Russian](docs/README_RU.md)**

This project implements automated tests for
the [UI Course Test Application](https://nikita-filonov.github.io/qa-automation-engineer-ui-course/#/auth/login). The
tests are written using **Python**, **Pytest**, **Allure** and **Playwright**. The test application’s source code is available
on [GitHub](https://github.com/Nikita-Filonov/qa-automation-engineer-ui-course).

[![UI tests](https://github.com/lobanov-qa/autotests-ui/actions/workflows/tests.yml/badge.svg)](https://github.com/lobanov-qa/autotests-ui/actions/workflows/tests.yml) ![Python](https://img.shields.io/badge/python-3670A0?style=flat-square&logo=python&logoColor=ffdd54) ![Playwright](https://img.shields.io/badge/-playwright-%232EAD33?style=flat-square&logo=playwright&logoColor=white) ![Pytest](https://img.shields.io/badge/pytest-%23ffffff.svg?style=flat-square&logo=pytest&logoColor=2f9fe3) ![Git](https://img.shields.io/badge/git-%23F05033.svg?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/github%20actions-%232671E5.svg?style=flat-square&logo=githubactions&logoColor=white) 

## Project Overview

The goal of this project is to automate the testing of the UI Course application. The automated tests verify various
functionalities of the application to ensure its stability and correctness. The project structure follows best practices
for organizing test code with clear, maintainable scripts.

## Getting Started

> ⚠️ **Important:** the project tests the educational [UI Course Test Application](https://nikita-filonov.github.io/qa-automation-engineer-ui-course/#/auth/login) platform, which must be running locally.

### Clone the Repository

To get started, clone the project repository using Git:

```bash
git clone https://github.com/lobanov-qa/autotests-ui.git
cd autotests-ui
```

### Create a Virtual Environment

It's recommended to use a virtual environment to manage project dependencies. Follow the instructions for your operating
system:

#### Linux / MacOS

```bash
python3 -m venv venv
source venv/bin/activate
```

#### Windows

```bash
python -m venv venv
venv\Scripts\activate
```

### Install Dependencies

Once the virtual environment is activated, install the project dependencies listed in `requirements.txt`:

```bash
pip install -r requirements.txt
```

### Additional Playwright Setup (if needed)

If you're running Playwright for the first time, you might need to install the required browsers:

```bash
playwright install
```

### Running the Tests with Allure Report Generation

To run the tests and generate an Allure report, use the following command:

```bash
pytest -m "regression" --alluredir=./allure-results
```

This will execute all tests in the project and display the results in the terminal.

### Viewing the Allure Report

After the tests have been executed, you can generate and view the Allure report with:

```bash
allure serve allure-results
```

This command will open the Allure report in your default web browser.


---

## 📞 Contacts

Looking for an opportunity to start a career in test automation. Ready for test tasks, code reviews, and interviews.

- **GitHub:** [lobanov-qa](https://github.com/lobanov-qa)
- **LinkedIn:** [evgenii-lobanov-qa](https://www.linkedin.com/in/evgenii-lobanov-qa/)
- **Telegram:** [lobanov_e_i](https://t.me/lobanov_e_i)

---

*Project created as part of the ["API Test Automation with Python and Playwright" course](https://stepik.org/course/234842/info) (author — Nikita Filonov).*