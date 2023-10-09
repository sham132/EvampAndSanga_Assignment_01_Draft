# Evamp And Sanga Assignment


The tester is required to upload a CSV file, for example, 'input_01.csv,' using the following form-data endpoints: [localhost:5000/api/v1/rest/csv/task1/upload, localhost:5000/api/v1/rest/csv/task2/upload].

Implementation for Assignment 1 - Task 1 (Curl command):


Task 1 Curl :

curl --location --request POST 'localhost:5000/api/v1/rest/csv/task1/upload' \
--header 'Cookie: JSESSIONID=1C736720A4010B4A265559EC89CC5C95' \
--form 'file=@"/E:/Test/evampsaanga_integration_engineer_test_assignment 2023/evampsaanga_integration_engineer_test_assignment 2023/input_01.csv"'

Task 2 Curl: 

curl --location --request POST 'localhost:5000/api/v1/rest/csv/task2/upload' \
--header 'Cookie: JSESSIONID=1C736720A4010B4A265559EC89CC5C95' \
--form 'file=@"/E:/Test/evampsaanga_integration_engineer_test_assignment 2023/evampsaanga_integration_engineer_test_assignment 2023/input_01.csv"'


I have completed both Task 1 and Task 2, ensuring that all the necessary checks have been applied in accordance with the requirements.

Please find the Task 1 output in the attached Output.json file.

For Task 2, the data section is stored in the database, specifically in the 'assignmentdb.' If the action is 'add' or 'hire,' data will be inserted into the 'person' and 'salary_component' tables. Conversely, if the action is 'update' or 'change,' the data will be updated based on the employee code.

Note: Please note that I have completed the assignment to the best of my understanding. If you have any requests for changes or adjustments, please don't hesitate to let me know.

You can find the Spring Boot project, 'Evamp_Sanga_Assignment,' enclosed within a zip file. 

