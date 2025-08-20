# Gorest_Api_Testing


Files
1. Gorest.postman_collection.json – Postman collection with test scenarios
2. Gorest.postman_environment.json – Environment file with variables (base_url, authToken)

To test:
Scenario 1
   Endpoint: POST https://gorest.co.in/public/v2/users
   Action: Create a new employee entry with:
   name , gender , email , status (active or inactive)
   Validation: The id returned in the response is in numerical format
Scenario 2
   Endpoint: GET https://gorest.co.in/public/v2/users
   Test giving the status anything instead of active or inactive
   Action: Verify that the status for the first entry is only either "active" or "inactive"
