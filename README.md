# testautomation
Magento Automation - Sign Up & Sign In Flow
This project automates the user registration and login process on Magento Test Site using Selenium, Cucumber (BDD), and Page Object Model (POM) design pattern.

🧪 Objective
Automate:

User Sign Up process

User Sign In process

🧰 Tech Stack
Tool/Library	Version
Java	8 or above
Selenium WebDriver	4.19.1
Cucumber	7.14.0
JUnit	4
WebDriverManager	5.8.0
Maven	Project Manager
Eclipse/IntelliJ	IDE

📁 Project Structure
bash
Copy
Edit
src
├── test
│   ├── java
│   │   ├── pages
│   │   │   ├── RegisterPage.java
│   │   │   └── LoginPage.java
│   │   ├── stepDefinitions
│   │   │   └── RegisterLoginSteps.java
│   │   └── runners
│   │       └── TestRunner.java
│   └── resources
│       └── features
│           └── register_login.feature
📝 Feature File
Path: src/test/resources/features/register_login.feature

gherkin
Copy
Edit
Feature: User Registration and Login

  Scenario: Register a new user
    Given I am on the Sign Up page
    When I enter valid user details and submit the form
    Then I should see a success message and be logged in

  Scenario: Login with registered user
    Given I am on the Login page
    When I enter valid credentials
    Then I should see the account dashboard
▶️ How to Run the Project


Clone the repo

bash
Copy
Edit
git clone https://github.com/yourusername/magento-automation.git
cd magento-automation
Build the project with Maven

bash
Copy
Edit
mvn clean install
Run tests using Cucumber JUnit runner

bash
Copy
Edit
mvn test
Open the generated report:
target/cucumber-report.html

📸 Proof of Execution
Attach screenshots or screen recordings in this section, or mention the location:

bash
Copy
Edit
/screenshots/successful_signup.png
/screenshots/login_success.png
✅ Deliverables
 Test cases (Excel)

 Automation Code using Selenium + Cucumber + POM

 GitHub repository with multiple commits

 Proof of execution (screenshot or recording)

📬 Contact
For queries, reach out to:
Nitin Bunkar
📧 bunkar.nitin2017@gmail.com
🔗 LinkedIn

