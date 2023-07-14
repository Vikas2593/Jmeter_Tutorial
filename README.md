# Jmeter_Tutorial
This project include a single .jmx file which includes various functions and capabilities of the Jmeter for the purpose of learning. Also adding the Html Report of the test execution.

**How to Run This Project**

1. Download the "ProjectJmeter.jmx" file
2. Open Jmeter GUI
3. Click on the Open Icon
4. Now open the .jmx which we downloaded
5. Now create a .csv file on your local machine
6. Now go to jmeter -> click on Assertion Results in the project -> In Filename provide path of you csv file
7. Now click on Run icon
8. Once done, click on "Tools" and Select "Generate HTML Report"
9. Provide the details in the pop-up
Result File -> Your .csv you created
user.properties -> Import from Bin folder of the Jmeter
Output directory -> Create an Empty folder and provide the path here

10. Now verify HTML report will be generated in that folder, you can open in Chrome and verify


**Running the File via CMD/Command Line**

Go to the Bin folder of Jmeter else define Jmeter globally

window -> jmeter -n -t C:\Users\HP\Downloads\apache-jmeter-5.6.2\bin\templates\ProjectJmeter.jmx -l C:\Users\HP\Downloads\TESTS.csv

mac -> sh jmeter -n -t C:\Users\HP\Downloads\apache-jmeter-5.6.2\bin\templates\ProjectJmeter.jmx -l C:\Users\HP\Downloads\Test_results.csv


**commands to see options of command line**

windows -> jmeter -h
mac -> sh jmeter -h


**Run and Generate HTML Report Command**

windows -> jmeter -n -t C:\Users\HP\Downloads\apache-jmeter-5.6.2\bin\templates\ProjectJmeter.jmx -l C:\Users\HP\Downloads\TESTS.csv -e -o C:\Users\HP\Downloads\Reports

mac -> sh jmeter -n -t C:\Users\HP\Downloads\apache-jmeter-5.6.2\bin\templates\ProjectJmeter.jmx -l C:\Users\HP\Downloads\TESTS.csv -e -o C:\Users\HP\Downloads\Reports


**Official Documentation and Helpful Links**

https://jmeter.apache.org/usermanual/index.html

https://www.youtube.com/watch?v=SoW2pBak1_Q&t=7s
