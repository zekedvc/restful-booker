# Restful Booker API - QA Tester Documentation

![postman-github-logo](https://github.com/zekedvc/restful-booker/assets/67669609/a6cc1a9c-cb3b-4d5d-ad14-ee2c17d230e8)

## Introduction
Welcome to the Restful Booker API QA Tester Documentation. This guide is intended for Quality Assurance (QA) testers responsible for testing the functionalities of the Restful Booker API. The collection is designed to cover various scenarios, allowing thorough testing of the API's endpoints to ensure its reliability.

## Purpose
The Restful Booker API collection serves as a comprehensive set of requests to validate different aspects of the API. QA testers can utilize these endpoints to perform functional testing, ensuring that the API meets specified requirements, and to assess its overall performance and security.

## Key Endpoints
![Restful](https://github.com/zekedvc/restful-booker/assets/67669609/b46c44e6-a4b2-4d16-8d2d-12b9625dddc1)
1. **Booking - Get Booking:** Retrieve details of a specific booking.
2. **Booking - Get Booking IDs:** Obtain a list of booking IDs.
3. **Ping - Health Check:** Ensure the API's health status with a ping request.
4. **Auth - Create Token:** Verify user authentication by creating a token.
5. **Booking - Create Booking:** Test the creation of a booking with specified details.
6. **Booking - Update Booking:** Modify booking details using the PUT method.
7. **Booking - Partial Update Booking:** Partially update booking details with the PATCH method.
8. **Booking - Delete Booking:** Delete a specific booking.


## How to Use
1. Start by reviewing the introduction and purpose to understand the testing objectives.
2. Explore each key endpoint section for specific testing scenarios.
3. Execute the requests using Postman or any preferred API testing tool.
4. Analyze the responses and ensure they align with expected outcomes.
5. Use the provided information to validate the API's functionality, reliability, and security.

## Newman reporter
1. Install Newman Reporter HTMLExtra:
Open your terminal and use the following npm command to install the Newman HTMLExtra reporter globally:
`npm install -g newman-reporter-htmlextra`
2. Execute Newman with HTMLExtra Reporter:
Navigate to the directory containing your Restful Booker API Postman collection JSON file in the terminal. Then, use the following command to run the collection with the HTMLExtra reporter:
`newman run your_collection_file.json -r htmlextra`. Replace your_collection_file.json with the actual filename of your Restful Booker API Postman collection. This will execute your collection using Newman and generate a detailed HTML report using the HTMLExtra reporter. The report will be available in the newman directory within your current working directory.

![image](https://github.com/zekedvc/restful-booker/assets/67669609/4f559794-617c-456a-babc-d522c575bef4)


## Conclusion
This documentation aims to facilitate efficient testing of the Restful Booker API. QA testers are encouraged to contribute to the improvement of test scenarios, report any issues, and collaborate with developers to enhance the overall quality of the API.

Happy Testing! 🚀
