# Movie_CRUD_API
A mini Golang project build for understanding the basic workflow of CRUD operations with API using postman. We've made the project using golang and made few movie entries with their details and coded accordingly where we can fetch details, update, delete, write, read in postman using API. 

API Endpoint:  
1. GET /items: Retrieve all items.
2. GET /items/{id}: Retrieve a specific item by ID.
3. POST /items: Create a new item.
4. PUT /items/{id}: Update an existing item by ID.
5. DELETE /items/{id}: Delete an item by ID.


Dependencies
Gorilla Mux: A powerful URL router and dispatcher for Golang HTTP handlers.

Steps to follow:
1. Install Golang(https://go.dev/dl/) in your system.
2. Import gorilla mux in your project directory by engtering the following command in your shell : "**go get "github.com/gorilla/mux**".
3. Copy the above **main.go** file.
4. Run the file by entering the the following in your power shell : "go run main.go"
5. Follow to the **POSTMAN** and add the request for basic **CRUD** operations.
6. Provide the link to fetch the API endpoint : "http://localhost:8000/movies"


**UML Diagram for workflow**
![Golang MiniPro drawio](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/9d660906-128e-462a-b763-101e0a623add)


**Screenshot of shell running on port 8000**
![Screenshot (26)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/54561fa0-d8cf-4a17-8157-6ef8ec07e287)


**Retrieving all items in our database**
![Screenshot (27)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/0fc6c984-2da8-46b2-853a-5202a16a51c7)


Getting items using ID
![Screenshot (28)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/f39a92e6-e1c0-4199-a43a-dec38dceea3a)


