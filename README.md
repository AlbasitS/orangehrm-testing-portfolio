# OrangeHRM Testing Portfolio

QA Testing Portfolio — OrangeHRM Web Automation Testing using Behavior Driven Development (BDD)

## About
This repository contains automation testing for the OrangeHRM web application's Login feature, built using Selenium WebDriver and Cucumber (BDD) with the Page Object Model design pattern.

## Tools & Technologies
- **Language:** Java 17
- **Automation:** Selenium WebDriver 4.44
- **BDD Framework:** Cucumber 7 (JUnit runner)
- **Design Pattern:** Page Object Model (POM)
- **Driver Management:** WebDriverManager
- **IDE:** IntelliJ IDEA
- **Test Management:** Jira (Kanban board)
- **Build Tool:** Maven

## Test Coverage
**Authentication (Login)**
- ✅ Login with valid credentials
- ✅ Login with invalid password
- ✅ Login with empty fields (required field validation)

## Project Structure
```
src/
└── test/
   ├── java/
   │   ├── pages/       → Page Object classes (locators & actions)
   │   ├── steps/       → Step definitions (Gherkin to Java)
   │   ├── hooks/       → Test setup & teardown (WebDriver lifecycle)
   │   └── runners/     → Cucumber test runner
   └── resources/
       └── features/    → Gherkin feature files
```

## How to Run
Requirements: JDK 17, Chrome browser installed

```bash
mvn test
```
Or run directly from IntelliJ: right-click `TestRunner.java` → Run

## Test Case Management
Test cases tracked via Jira Kanban board: [OrangeHRM Automation Testing Board](https://albasitseptian94.atlassian.net/jira/software/projects/OR/boards/3?filter=&groupBy=none)

## Roadmap
Planned expansion for future iterations:
- Dashboard module testing
- Employee Management (CRUD) testing
