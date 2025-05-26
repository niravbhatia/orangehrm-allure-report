# OrangeHRM Selenium Automation Project

This project automates key workflows in the [OrangeHRM](https://opensource-demo.orangehrmlive.com/) platform using **Selenium WebDriver**, **TestNG**, and **Allure Reporting**.

It includes the ability to:
- ✅ Add a fixed employee (Batman with ID `EMP1313`)
- ✅ Verify the employee exists
- ✅ Delete that employee by Employee ID
- ✅ Generate beautiful Allure Reports
- ✅ View reports via GitHub Pages


🚀 Current Live Version: [v3](https://niravbhatia.github.io/orangehrm-allure-report/v3)

🧩 Tech Stack
- Java 21
- Selenium WebDriver 4.32.0
- TestNG 7.9.0
- Allure TestNG 2.24.0
- Maven
- IntelliJ IDEA
- GitHub Pages for Allure report hosting


🧪 How to Run Locally

# Run tests using TestNG suite
mvn clean test -Dsurefire.suiteXmlFiles=testng.xml

# Generate Allure report
allure generate target/allure-results --clean -o target/allure-report

# Serve the report locally
allure serve target/allure-results
