# E-Commerce Selenium Automation Framework

A Python-based web automation testing framework using **Selenium WebDriver** and **Pytest**. The project is designed to automate web application test cases using a structured and maintainable framework.

## 🚀 Features

* Web UI automation using Selenium WebDriver
* Pytest-based test execution
* Page Object Model (POM) structure
* Reusable page classes and utilities
* Configuration and test-data management
* Organized test cases
* Maintainable project structure

## 🛠️ Technologies Used

* **Python**
* **Selenium WebDriver**
* **Pytest**
* **Git**
* **GitHub**

## 📁 Project Structure

```text
ecommerce-selenium-framework/
│
├── .github/
├── config/
├── pages/
├── testdata/
├── tests/
├── utils/
│
├── conftest.py
├── pytest.ini
├── requirements.txt
├── .gitignore
└── README.md
```

## ⚙️ Installation

### 1. Clone the repository

```bash
git clone https://github.com/rishitapradhan23/ecommerce-selenium-automation.git
```

### 2. Navigate to the project directory

```bash
cd ecommerce-selenium-automation
```

### 3. Create a virtual environment

```bash
python -m venv .venv
```

### 4. Activate the virtual environment

For Windows:

```bash
.venv\Scripts\activate
```

### 5. Install dependencies

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

## 🧪 Testing Approach

The framework uses the **Page Object Model (POM)** to separate page interaction logic from test cases.

This approach helps with:

* Code reusability
* Easier maintenance
* Reduced code duplication
* Better test organization
* Improved readability

## 🔮 Future Improvements

* Add CI/CD integration using GitHub Actions
* Add cross-browser testing
* Add parallel test execution
* Add automated screenshots for failed tests
* Add advanced test reporting
* Expand data-driven testing

## 👩‍💻 Author

**Rishita Pradhan**

GitHub: https://github.com/rishitapradhan23
