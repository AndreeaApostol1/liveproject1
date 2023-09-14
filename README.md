# liveproject1
# Selenium WebDriver and Java Project

Welcome to my Selenium WebDriver and Java project! This project is a practical demonstration of the skills I've acquired during my Udemy course on Selenium WebDriver and Java. 
In this project, in Eclipse I've built an automation framework using Selenium WebDriver, Java, and TestNG to test various pages of a test store.

## Project Overview

### Framework Structure

- **Maven Project**: This project is organized as a Maven project, making it easy to manage dependencies and build automation.

- **Page Object Model (POM)**: I've implemented the Page Object Model (POM) design pattern to create separate classes for each web page involved. This approach enhances maintainability and reusability.

- **Base Class**: I've created a Base Class that contains reusable methods and configurations, such as setting up the WebDriver, managing browser instances, and handling common actions.

- **Properties File**: Global variables and configurations are stored in a `.properties` file, making it easy to manage and update settings across the framework.

- **TestNG XML Configuration**: The `testng.xml` file is used to control which tests to run, enabling selective test execution and parallel test runs.

### Test Scenarios

I've created test scenarios to simulate user interactions with the test store. These include:

1. **Placing an Order**: Automated tests to place orders on the test store, ensuring a seamless shopping experience.

2. **Adding and Removing Products**: I've reused page objects to test the functionality of adding and removing products from the shopping basket.

3. **Checking the total amount**: I've checked if the total amount after a product has been deleted equals the expected amount by using an assertion.


### Contact Me

If you have any questions or would like to discuss this project in more detail, please feel free to contact me via [email](mailto:andreeaapostol2020@gmail.com).

Thank you for reviewing my Selenium WebDriver and Java project. I hope this demonstrates my skills and expertise in automated testing and test framework development.
