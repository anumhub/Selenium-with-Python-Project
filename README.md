# Selenium with Python E-Commerce Project 🚀

A sample test automation framework built using Selenium WebDriver and Python( pytest is a test runner) 
The project demonstrates Page Object Model (POM), utility modules, test data handling, reporting, and configuration management.

---

## 🗂️ Repository Structure
selenium-python-framework/
├── PythonSel # Shared test scripts (e.g., login, navigation tests)
├── POM/ # Page Object Model classes (one Python class per page)
├── Utils/ # Utility modules (e.g., helpers, wait functions)
├── Data/ # Test data files (e.g.JSON)
├── Reports/ # Test output/reports (HTML, screenshots, logs)
├── config.py # Central configuration (URLs, credentials, browser settings)

## ⚙️ Getting Started

### Prerequisites

- Python 3.8+
- pip installed
- Google Chrome + ChromeDriver (or your preferred WebDriver)

### Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/YourUsername/selenium-python-framework.git
   cd selenium-python-framework
2. Verify config.py values (URL, credentials, browser paths) match your environment

### Usage & Running Tests

Run all tests:
pytest --html=Reports/report.html
Run a specific test:
pytest Common/test_login.py --html=Reports/login_report.html
Results: 
Test reports (HTML) and logs/screenshots, if any, will be generated in the Reports/ folder.

### Folder Descriptions

PythonSel/: Functional test scripts using POM classes for actions and assertions.
POM/: Encapsulates UI interactions per page (locators, methods).
Utils/: Helper modules (waits, config handling, screenshot capture).
Data/: Static test data resources.
Reports/: Output results — HTML reports, logs, failure screenshots.
config.py: Centralizes browser settings, environment properties, login credentials.







