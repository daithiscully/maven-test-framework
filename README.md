# maven-test-framework
This project contains the following capabilities:
TestNG testing framework
Build tool is Maven
Generates Allure reports into the target/site directory in the project root

To run the tests with an Allure report output:
mvn clean test site -DsuiteXmlFile=tb_func_test_suite_testng.xml
