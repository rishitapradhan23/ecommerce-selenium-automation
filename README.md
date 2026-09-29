# E-Commerce Selenium Automation Framework

A Python-based web automation testing framework built using **Selenium WebDriver** and **Pytest**. The framework follows a structured Page Object Model (POM) approach to create maintainable, reusable, and scalable automated tests.

## 🚀 Features

* Automated web UI testing using Selenium WebDriver
* Pytest-based test execution
* Page Object Model (POM)
* Reusable page classes and utilities
* Configuration management
* Test data management
* Explicit waits for reliable test execution
* Pytest fixtures for setup and teardown
* HTML test reporting
* Organized and maintainable project structure

## 🛠️ Technologies Used

* **Python**
* **Selenium WebDriver**
* **Pytest**
* **Pytest-HTML**
* **WebDriver Manager**
* **Git & GitHub**

## 📁 Project Structure

```text
ecommerce-selenium-framework/
│
├── .github/
│
├── config/
│   └── configuration files
│
├── pages/
│   └── Page Object classes
│
├── testdata/
│   └── Test data files
│
├── tests/
│   └── Automated test cases
│
├── utils/
│   └── Reusable utilities
│
├── conftest.py
├── pytest.ini
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation

Clone the repository:

```bash
git clone https://github.com/rishitapradhan23/ecommerce-selenium-automation.git
```

Navigate to the project directory:

```bash
cd ecommerce-selenium-automation
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment on Windows:

```bash
.venv\Scripts\activate
```

Install the required dependencies:

```bash
pip install -r requirements.txt
```

## ▶️ Running the Tests

Run all tests:

```bash
pytest
```

Run tests with verbose output:

```bash
pytest -v
```

Generate an HTML report:

```bash
pytest --html=reports/report.html --self-contained-html
```

## 🧪 Testing Approach

The framework separates test logic from page interaction logic using the **Page Object Model**.

This provides:

* Better code reusability
* Easier maintenance
* Reduced code duplication
* Improved test readability
* Easier expansion of the test suite

## 📊 Test Reports

Test execution can generate HTML reports containing:

* Test execution status
* Passed and failed test cases
* Execution duration
* Detailed test information

## 🔧 Future Improvements

* Add CI/CD integration using GitHub Actions
* Add cross-browser testing
* Add parallel test execution
* Add screenshots for failed tests
* Integrate advanced reporting such as Allure
* Add data-driven testing

## 👩‍💻 Author

**Rishita Pradhan**

GitHub:
https://github.com/rishitapradhan23

````

### Step 2 — Commit the README

After replacing the content, scroll to the bottom.

You'll see **Commit changes**.

Use a message such as:

```text
Improve project README
````

Then click:

**Commit changes**

### Step 3 — Check GitHub

Return to the repository's main page.

Your new README should appear underneath the project files.

**Important:** I included a few standard commands/features in the README, but before we claim things like HTML reporting or specific dependencies, we'll verify that your actual project contains them.

After you've updated the README, tell me **“README updated”**. Then we'll check your actual project and make the README accurately match your implementation.
