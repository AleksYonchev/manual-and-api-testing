# Manual & API Testing

A practical software testing project covering **manual web application testing** and **REST API testing with Postman**.

The work was completed as part of my **QA Fundamentals and Manual Testing training at SoftUni**, using the educational **Movie Catalog** application and its provided functional and API specifications. I independently created the test cases, documented observed defects, and prepared the Postman requests. This is a personal student project, not an official SoftUni repository.

## Project contents

### Manual web testing

Functional test coverage includes the landing page, user registration and login, profile management, movie creation, and movie management.

The workbook includes test cases with expected and actual outcomes, execution statuses, and recorded bug reports. It illustrates positive and negative scenarios, documentation of observed behavior, and defect tracking.

- [Manual testing notes](Manual-Web-Testing/README.md)
- [Test cases and bug reports (Excel)](Manual-Web-Testing/MovieCatalog_Manual_Testing.xlsx)

### REST API testing with Postman

The Postman collection includes six requests covering user registration, authentication, movie creation, catalog retrieval, movie editing, and deletion. It uses GET, POST, PUT, and DELETE methods, JSON payloads, and variables for environment values and bearer-token authentication.

The collection also contains **basic response checks** for successful HTTP status codes, response time, and JSON validity where applicable. These checks are provided as reusable test scripts; this repository does **not** claim a current successful test run or provide a verified execution report.

- [API testing notes](API-Testing/README.md)
- [Postman collection](API-Testing/MovieCatalogAPI.postman_collection.json)
- [Example Postman environment](API-Testing/MovieCatalogAPI.postman_environment.example.json)

## Skills demonstrated

Manual testing · Functional testing · Positive and negative testing · Test case design · Bug reporting · Defect tracking · REST APIs · Postman · HTTP methods · JSON · Bearer authentication

## Scope and limitations

- The tested application and its requirements were supplied for educational assessment; **I did not develop the Movie Catalog application or its API**.
- Reported defects reflect the tested application and conditions at the time of the original coursework. They have not been independently reverified against a current live version.
- The Postman collection is included for demonstration and review. A working authorized test environment and suitable test credentials are necessary to execute it.
- All API credentials and tokens must remain private; the example environment does not contain real secrets.
