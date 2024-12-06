# 2-Impledge_QA_VasuKumar.postman_collection.json
This exercise demonstrates working with Postman and the EasyPost API to:

Fix failing test cases in the provided collection.
Add a new request to fetch shipment details.
Include additional test cases to verify the response data.
The modified Postman collection is named Impledge_QA_VasuKumar.postman_collection.json and contains:

A fixed Address - Verify request.
A new Get Shipment Details request with the necessary test scripts.
Steps to Complete

Import the Collection:
The provided Impledge_QA_Exercise.postman_collection.json was imported into Postman and renamed to Impledge_QA_VasuKumar.

Fix Failing Test Cases:
The tests in the Address - Verify request were updated to:
Verify that the errors array in the response is empty.
Validate the presence of the ZIP code 06810 in the response.

Add New Request:
A new request, Get Shipment Details, was created with the GET method to fetch shipment details for ID shp_e0b570fd1d7d4b62bd206917eae5881a.
Authorization was set to Basic Auth, using the provided API key.

Add Test Cases:
For the new request, two test cases were added:
Check that selected_rate.retail_rate equals 12.
Verify that selected_rate.retail_rate is greater than list_rate.

Export Updated Collection:
The updated collection was exported as Impledge_QA_VasuKumar.postman_collection.json.

How to Run the Collection
Import the JSON File:
Open Postman and import the file Impledge_QA_VasuKumar.postman_collection.json.
Run the Collection:
Click on the Impledge_QA_VasuKumar collection in the left-hand sidebar.
Select Run Collection and verify all test cases pass successfully.
Verify the Test Results:
Check that the tests in both Address - Verify and Get Shipment Details requests pass as expected.
# i have corrected the code and submitted it firstly
