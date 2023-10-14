# Go Data Engineering Challenge - Simplified

## Overview

Welcome to our simplified Go Data Engineering Challenge! In this challenge, we seek to evaluate your skills in fetching and loading data using Go, which are foundational for the Data Engineer role at our company.

## The Challenge

Your task is to create a Go application that performs the following:

1. **Fetch Data:** Retrieve data from a specified API.
2. **Load Data:** Insert the fetched data into a SQL database.


### Detailed Steps
1. **API Data Fetching**
	* Fetch data from the https://data-engineer-challenge-server-enxjgq2q4q-uc.a.run.app/api/v1 API endpoint. Documentation for the API can be found at  https://data-engineer-challenge-server-enxjgq2q4q-uc.a.run.app.
	* Handle paginated data fetching.
	* Implement basic error handling mechanisms (e.g., retry once after a failed attempt).

2. **Data Loading to SQL Database**
	* Choose any SQL database technology of your preference.
	* Transform the json data into a SQL tables appropriately.
	* Load the fetched data into the database, handling any obvious errors gracefully (e.g., connection issues).
	
### Evaluation Criteria
* **Code Quality:** Organization, readability, and adherence to Go best practices.
* **Error Handling:** Basic robustness against potential errors.
* **Data Handling:** Correctness in data loading to the database.
* **Testing:** Presence and quality of unit tests (e.g., a simple test to check if data is fetched and loaded correctly).

## Submission
Please submit your solution as a zip file which includes:

* The complete source code of the application.
* A README document explaining how to run the application and tests, and any assumptions or additional features you've implemented.
* Any scripts or additional materials needed to run your application.

## Notes
* Ensure to provide clear instructions on how to run your application and tests.
* If you make any assumptions or decisions that are not covered in this document, please explain them in your README.
