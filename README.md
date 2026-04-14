OpenCart Automation Framework

This project is a robust test automation framework developed to validate the core functionalities of an OpenCart-based e-commerce application. It is built using Java, Selenium WebDriver, and TestNG, following industry best practices like the Page Object Model (POM) to ensure clean, maintainable, and scalable test code.

📌 Overview

The framework automates key user workflows of an e-commerce system, helping ensure reliability and consistency across application features. It is designed in a modular way so that new test cases and components can be added with minimal effort.

🧱 Framework Design

The project is structured to separate responsibilities clearly:

Page Layer → Contains web element locators and page-specific actions
Test Layer → Includes test scenarios and validations
Utilities → Common reusable methods (if implemented)
Configuration Files → Managed through Maven and TestNG
⚙️ Key Functionalities Covered

The automation suite includes validation of major user journeys such as:

Account Registration
User Login & Logout
Product Search Functionality
Adding Products to Cart
Checkout Workflow
✨ Highlights
✔️ Implements Page Object Model (POM) for better code organization
✔️ Uses TestNG for test execution and management
✔️ Integrated with Maven for dependency handling
✔️ Supports failure analysis using screenshots
✔️ Easy to scale and extend with additional test cases
✔️ Clean and readable code structure
🛠️ Technology Stack
Component	Technology Used
Programming	Java
Automation Tool	Selenium WebDriver
Test Framework	TestNG
Build Tool	Maven
▶️ Execution Steps

To run this project locally:

Clone the repository:
git clone https://github.com/ramyasada/Automation_Testing_on_opencart.git
Open the project in your preferred IDE (Eclipse/IntelliJ)
Execute tests using:
mvn clean test
Alternatively, run the testng.xml file directly as a TestNG suite
📈 Test Reports
Default TestNG reports are generated after execution
Reports can be found in the test-output directory
Screenshots are captured for failed scenarios (if configured)
🚀 Future Enhancements
Integration with CI/CD tools (Jenkins/GitHub Actions)
Advanced reporting (Extent Reports)
Data-driven testing using external files
Cross-browser execution
👩‍💻 Author

Ramya Sada
Computer Science Final Year Student
Interested in Test Automation, Selenium, and Software Testing
