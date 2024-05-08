

# Mobile Automation Testing Framework

This is a mobile automation testing framework built with Appium, Cucumber, Java and Allure as the reporting tool.

## Prerequisites

To run the tests in this framework, ensure that you have the following software installed:

- Java Development Kit (JDK) 8 or higher
- Apache Maven
- Appium
- Android SDK (for Android testing) or Xcode (for iOS testing)
- Allure Command Line (for generating Allure reports)

## Getting Started

1. Clone the repository:

   ```
   git clone https://github.com/your-username/mobile-automation-framework.git
   ```

2. Navigate to the project directory:

   ```
   cd mobile-automation-framework
   ```

3. Install project dependencies:

   ```
   mvn clean install
   ```

## Configuration

Before running the tests, make sure to configure the following settings:

1. Open the `src/test/resources/config.properties` file.
2. Update the desired capabilities and other configuration settings for your specific mobile device or simulator/emulator.
3. Add any additional configuration properties required for your specific setup.

## Running the Tests

To execute the tests, run the following command:

```
mvn clean test
```

The tests will run using the Cucumber framework with Appium integration, and generate test reports in the `target/allure-results` directory.

## Generating Allure Reports

To generate and view Allure reports:

1. Make sure you have Allure Command Line installed on your system.
2. Run the following command to generate the Allure report:

allure serve
allure generate --single-file allure-results --clean -o allure-report
   ```

## Test Reports

This framework utilizes Allure as the reporting tool. After running the tests and generating the Allure report, you can view detailed test reports with rich visual representations, including graphs and statistics.


## Contact

If you have any questions or need further assistance, feel free to contact the project maintainers at [hebanasser996@gmail.com].
