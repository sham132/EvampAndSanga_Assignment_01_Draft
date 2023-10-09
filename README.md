# Evamp And Sanga Assignment


Tester needs to upload a csv file : e.g input_01.csv

form-data Endpoint : [localhost:5000/api/v1/rest/csv/task1/upload , localhost:5000/api/v1/rest/csv/task2/upload]

<<<<<<< HEAD
=======
First PlayInventory : Remove Error and fix the Bug in the sheet

>>>>>>> 1ea0863685dafa4cb65df0e690ddc89148e577ec
Assignment 1 Implementation:

Task 1 Curl :

curl --location --request POST 'localhost:5000/api/v1/rest/csv/task1/upload' \
--header 'Cookie: JSESSIONID=1C736720A4010B4A265559EC89CC5C95' \
--form 'file=@"/E:/Test/evampsaanga_integration_engineer_test_assignment 2023/evampsaanga_integration_engineer_test_assignment 2023/input_01.csv"'


Task 2 Curl: 

curl --location --request POST 'localhost:5000/api/v1/rest/csv/task2/upload' \
--header 'Cookie: JSESSIONID=1C736720A4010B4A265559EC89CC5C95' \
--form 'file=@"/E:/Test/evampsaanga_integration_engineer_test_assignment 2023/evampsaanga_integration_engineer_test_assignment 2023/input_01.csv"'


I have touch Task 1 and Task 2 all the checks applied on both the tasks according to the requirement file.


Task 1 Output.json is attached for your review.

In Task 2 the data section is store is in the databse e.g assignmentdb if the action is add or hire data will be added in the tables e.g person and salary_compoment,  if the action is update or change the data will be updated on top of the emloyee_code 


Note: The Assignment is done as per my understanding please feel free to ask for change.

