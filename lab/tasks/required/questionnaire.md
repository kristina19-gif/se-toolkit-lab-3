Questionnaire — API Exploration
Fill in each answer below. Replace ___ with the correct value.

Items endpoints
GET /items
HTTP method: GET

Path: /items

Status code (success): 200

Response type (array or object): array

GET /items/{item_id}
Status code (item found): 200

Status code (item not found): 404

POST /items
HTTP method: POST

Status code (created successfully): 201

PUT /items/{item_id}
HTTP method: PUT

Status code (updated successfully): 200

Authentication
What happens when you call an endpoint without the API key? (status code): 401

Where do you set the API key value for Docker Compose? (file name): .env.docker.secret
