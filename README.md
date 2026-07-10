# QA API Testing Portfolio

This repository contains a hands-on API testing portfolio created in Postman. It demonstrates practical experience with CRUD operations, authentication, environment variables, request chaining, positive and negative testing, pagination, search, response validation, headers, business rules, and JSON Schema Validation.

## Tools and Technologies

- Postman
- REST APIs
- JavaScript assertions
- JSON
- GitHub

## Postman Collections

### 1. JSONPlaceholder API Testing

This collection demonstrates CRUD testing using the JSONPlaceholder API.

Covered requests:

- GET all posts
- GET a single post
- GET a non-existing post
- POST a new post
- PUT a complete resource update
- PATCH a partial resource update
- DELETE a post

Key validations include:

- HTTP status codes
- Response data types
- Required fields
- Response body validation
- Response time
- Positive and negative scenarios

### 2. Authentication API Testing

This collection demonstrates a complete authentication workflow using DummyJSON.

Covered scenarios:

- Successful user login
- Access token and refresh token validation
- Automatic token storage using environment variables
- Authenticated current-user request
- Refresh token workflow
- Current-user validation after token refresh
- Invalid login testing
- Positive and negative test organization
- Collection Runner execution

Environment variables used:

- `baseUrl`
- `username`
- `password`
- `userId`
- `accessToken`
- `refreshToken`

Sensitive environment values are not included in this repository.

### 3. Products API Testing

This collection focuses on product-related API testing using DummyJSON.

Covered scenarios:

- Product pagination using `limit` and `skip`
- Product search and partial matches
- Search with no results
- Get a single product using a path parameter
- Non-existing product validation
- Products by category
- Retrieve all categories
- Request and response header validation
- Response-time validation
- Business-rule validation
- JSON Schema Validation

The JSON Schema checks:

- Required fields
- Data types
- Minimum and maximum values
- String-length rules
- Arrays and minimum items
- URI format validation

## Testing Techniques Demonstrated

- Positive testing
- Negative testing
- Boundary and edge-case testing
- Path parameters
- Query parameters
- Pagination
- Search validation
- Authentication and authorization
- Bearer token usage
- Request chaining
- Environment variables
- Collection Runner
- Header validation
- Business-rule validation
- JSON Schema Validation
- Response-time validation

## How to Run

1. Download or clone this repository.
2. Open Postman.
3. Import the required `.postman_collection.json` files.
4. Create a Postman environment.
5. Add the required environment variables.
6. Select the environment.
7. Run individual requests or use Collection Runner.

For DummyJSON requests, use:

```text
baseUrl = https://dummyjson.com
