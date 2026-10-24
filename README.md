# Hi, I'm Arseniy Myasnik

QA Engineer with 2.5+ years of experience in manual and automated testing of web services, telecom billing flows, API/SOAP integrations, and subscriber-facing products.

## Core Skills

- **Manual testing:** test cases, bug reports, regression testing, functional testing, boundary value analysis
- **UI automation:** Python, Selenium WebDriver, pytest, Page Object Model, Allure Report
- **API testing:** REST API, SOAP, Postman, SoapUI, requests, API Client Pattern
- **Data:** SQL, database validation
- **Tools:** Git, GitHub Actions, Jira, Chrome DevTools

## Featured Projects

### [python-selenium-booking-tests](https://github.com/ArseniyMyasnik/python-selenium-booking-tests)

Automated UI tests for a demo booking website using Python, Selenium, pytest, Allure Report, and the Page Object Model pattern.

Highlights:

- Page Object Model structure with reusable page actions and locators
- Positive, negative, and boundary test scenarios for dates and contact form fields
- Parametrized pytest tests
- Allure steps and screenshots
- Known product defects documented with `xfail`
- GitHub Actions workflow for test collection

### [python-api-booker-tests](https://github.com/ArseniyMyasnik/python-api-booker-tests)

Automated API tests for Restful-booker using Python, pytest, requests, Allure Report, and the API Client Pattern.

Highlights:

- Auth, Health Check, and Booking API coverage
- Positive, negative, combined-filter, and boundary scenarios
- Separate API clients and shared pytest fixtures
- Authentication token handling and automatic cleanup of created test data
- Unique test data generated with UUID
- Manual test cases stored with the automated tests
- Known API defects documented with strict `xfail`
