1. Project Setup

To set up and run this project, follow these steps:
Requirements:
- A local server like XAMPP or WAMP with PHP support.
- A browser for testing the API via Postman or directly using curl commands.

 Steps:
1. Download or clone the `my_api_gateway` directory.
2. Place the `my_api_gateway` directory inside your web root folder (e.g., `htdocs` for XAMPP).
3. Ensure that Apache is running on your server.
4. Access the API via the following URL: `http://localhost/api-gateway/`.

 2. API Key
For secure access to the API, you need an API key. Implemented API keys:
- API_KEY_1
- API_KEY_2

Include the API key in the request headers for all API calls.

3. Endpoints

 3.1 Get Users
URL: `/api/users`  
Method: `GET`  
Description: Retrieves a list of all users in the system.

Example:
URL: `http://localhost/api-gateway/endpoints/users.php`  
Response:
json
[
    {"id": 1, "name": "Alice"},
    {"id": 2, "name": "Bob"}
]
