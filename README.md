##Movie_CRUD_API
A mini Golang project build for understanding the basic workflow of CRUD operations with API using postman. We've made the project using golang and made few movie entries with their details and coded accordingly where we can fetch details, update, delete, write, read in postman using API. 

##API Endpoint:  
The application provides API endpoints for CRUD operations on movie details records

1. GET /movies: Retrieve all movie items.
2. GET /movies/{id}: Retrieve a specific movie item by ID.
3. POST /movies: Create a new movie item.
4. PUT /movies/{id}: Update an existing movieitem by ID.
5. DELETE /movies/{id}: Delete an movie item by ID.


##Dependencies
Gorilla Mux: A powerful URL router and dispatcher for Golang HTTP handlers.

##Getting Started
1. Clone the repository:

   ```bash
   https://github.com/shreyaaansh/Movie_CRUD_API
   
   cd Movie_CRUD_API
2. Download Dependencies:

   ```bash
   go get "github.com/gorilla/mux"

3.Build Project
    ```bash
    
    go build

4. Run Project
   ```bash
    go run main.go

6. Open Server
    
    ```bash
    http://localhost:8080/movies

##Steps to follow:
1. Install Golang(https://go.dev/dl/) on your system.
2. Import gorilla mux in your project directory by engtering the following command in your shell : "**go get "github.com/gorilla/mux**".
3. Copy the above **main.go** file.
4. Run the file by entering the the following in your power shell : "go run main.go"
5. Follow to the **POSTMAN** and add the request for basic **CRUD** operations.
6. Provide the link to fetch the API endpoint : "http://localhost:8000/movies"


###UML Diagram for workflow
![Untitled Diagram drawio](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/805dfa7d-3bff-4fcc-95a2-bbaa2b74f17e)



###Screenshot of shell running on port 8000
![Screenshot (26)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/54561fa0-d8cf-4a17-8157-6ef8ec07e287)


###Retrieving all items in our database
![Screenshot (27)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/0fc6c984-2da8-46b2-853a-5202a16a51c7)


###Getting items using ID
![Screenshot (28)](https://github.com/shreyaaansh/Movie_CRUD_API/assets/85485959/f39a92e6-e1c0-4199-a43a-dec38dceea3a)

### Running Tests

- Use the following command to run the tests:

  ```bash
  go test


## Contributing
Feel free to contribute to this project. Fork the repository, make your changes, and submit a pull request.
