# Movie_CRUD_API
A mini Golang project build for understanding the basic workflow of CRUD operations with API using postman. 

API Endpoints:

GET /items: Retrieve all items.
GET /items/{id}: Retrieve a specific item by ID.
POST /items: Create a new item.
PUT /items/{id}: Update an existing item by ID.
DELETE /items/{id}: Delete an item by ID.


Dependencies
Gorilla Mux: A powerful URL router and dispatcher for Golang HTTP handlers.

Steps to follow:
1. Install Golang in your system.
2. Import gorilla mux in your project directory by engtering the following command in your shell : "go get "github.com/gorilla/mux".
3. Copy the above main.go file.
4. Run the file by entering the the following in your power shell : "go run main.go"
5. Follow to the POSTMAN and add the request for basic CRUD operations.
6. Provide the link to fetch the API endpoint : "http://localhost:8000/movies"

Screenshot of shell running on port 8000
![Screenshot (26)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/54561fa0-d8cf-4a17-8157-6ef8ec07e287)


Retrieving all items in our database
![Screenshot (27)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/b9233c74-65ce-496b-88c0-71608e08e012)


