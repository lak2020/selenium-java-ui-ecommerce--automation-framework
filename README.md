
# Selenium TestNG E-Commerce Framework

[![GitHub Actions](https://github.com/lak2020/selenium-java-ui-ecommerce--automation-framework/actions/workflows/selenium-tests.yml/badge.svg)](https://github.com/lak2020/selenium-java-ui-ecommerce--automation-framework/actions)
GitHub Actions: https://github.com/lak2020/selenium-java-ui-ecommerce--automation-framework/actions



## 🚀 Overview

Industrial-standard Selenium TestNG hybrid automation framework for [SauceDemo](https://www.saucedemo.com/) with data-driven testing, parallel execution, CI/CD pipeline, and enterprise-level design patterns.

**Repository:** [lak2020/selenium-java-ui-ecommerce--automation-framework](https://github.com/lak2020/selenium-java-ui-ecommerce--automation-framework)

## 📊 Allure Report

View the latest test results: [Allure Report](https://lak2020.github.io/selenium-java-ui-ecommerce--automation-framework/3/index.html)

## 📋 Features

- **Hybrid Framework Architecture**: Page Object Model (POM) + Data-Driven Testing
- **Thread-Safe WebDriver**: ThreadLocal implementation for parallel execution
- **Cross-Browser Support**: Chrome and Edge browsers
- **Data-Driven Testing**: CSV-based test data management
- **Dynamic Test Data**: Random data generation utilities
- **Comprehensive Logging**: Log4j2 integration
- **Rich Reporting**: Allure Reports with screenshots
- **CI/CD Ready**: GitHub Actions workflow with automatic deployment
- **Retry Mechanism**: Automatic retry for failed tests
- **Custom Listeners**: TestNG listeners for enhanced reporting
- **GitHub Pages**: Automated Allure report publishing

## 🏗️ Project Structure

```
selenium-testng-ecommerce-framework/
├── src/
│   ├── main/java/com/seleniumui/
│   │   ├── base/           # Base classes (BasePage, BaseTest, DriverFactory)
│   │   ├── pages/          # Page Object classes
│   │   ├── utils/          # Utility classes
│   │   └── listeners/      # TestNG listeners
│   └── test/java/com/seleniumui/tests/
│       ├── LoginTest.java
│       ├── ProductTest.java
│       ├── CheckoutTest.java
│       └── SessionTest.java
├── .github/workflows/      # CI/CD configuration
├── testng.xml              # TestNG configuration
└── pom.xml                 # Maven configuration
```

## 🛠️ Prerequisites

- Java 11 or higher
- Maven 3.6+
- Chrome or Edge browser

## 🚀 Quick Start

### Clone the repository
```bash
git clone https://github.com/lak2020/selenium-java-ui-ecommerce--automation-framework.git

```

### Run all tests
```bash
mvn clean test
```

### Run tests in headed mode (visible browser)
```bash
mvn clean test -Dheadless=false
```

### Run smoke tests only
```bash
mvn clean test -Psmoke
```

### Generate Allure Report
```bash
mvn allure:report
```

### Open Allure Report
```bash
mvn allure:serve
```

## 📦 Dependencies

| Dependency | Version | Purpose |
|------------|---------|---------|
| Selenium | 4.18.1 | Web automation |
| TestNG | 7.9.0 | Test framework |
| WebDriverManager | 5.7.0 | Browser driver management |
| Log4j2 | 2.23.0 | Logging |
| Allure TestNG | 2.25.0 | Reporting |
| OpenCSV | 5.9 | CSV data handling |

## 🧪 Test Modules

- **LoginTest**: Valid login scenarios
- **ProductTest**: Add to cart, remove, sorting functionality
- **CheckoutTest**: Complete checkout flow with dynamic data
- **SessionTest**: Session validation and security tests

## 🔄 CI/CD Pipeline

The project includes GitHub Actions workflow that:
1. Runs tests on every push/PR
2. Generates Allure Report
3. Deploys report to GitHub Pages

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**lak2020** - [lak2020](https://github.com/lak2020)

---

⭐ **Star this repository** if you find it helpful!
