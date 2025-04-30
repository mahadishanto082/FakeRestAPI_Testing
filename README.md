🧪 API Testing Project - Fakerestapi
📝 Overview
This project contains a comprehensive set of API test cases for the Fakerestapi. The goal is to validate CRUD operations on different resources using Postman and Newman for test automation and reporting.

📋 Table of Contents
Introduction

Test Plan

Test Cases

Postman Collections

How to Run

🚀 Introduction
The following Fakerestapi resources are tested:

✅ Activities

✅ Books

✅ Authors

✅ Users

Test cases cover both positive and negative scenarios, using HTTP methods like GET, POST, PUT, and DELETE.

🛠️ Test Plan
The testing process focuses on:

✅ Verifying the functionality of each API endpoint

✅ Ensuring correct HTTP status codes (e.g., 200, 201, 404, etc.)

✅ Checking data accuracy and response format

✅ Testing edge cases and error handling

🧪 Test Cases
Each resource is tested with:

Create

Retrieve

Update

Delete

Invalid data input

Boundary conditions

📂 Postman Collections
The Postman collection used in this project is named Test2Project. You can find it in the /postman folder of this repository.

▶️ How to Run
Clone the repository

Install Newman:

bash
Copy
Edit
npm install -g newman
Run the collection:

bash
Copy
Edit
newman run postman/Test2Project.postman_collection.json -r cli,html
📊 Test Report
Total Assertions: 10

Total Failed Tests: 7

Total Requests: 18

Skipped Tests: 0

Average Response Time: 265 ms

Total Run Duration: 6.2 s

Detailed HTML reports are generated after each run in the newman directory.
