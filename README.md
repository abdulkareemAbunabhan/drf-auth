# drf-api

This project is a RESTful API for managing a reading list. It allows users to create, view, update, and delete books in their reading list.

## Installation

To run the Travel Bucket RESTful API, make sure you have Docker installed on your system. Then, follow these steps:

1. Clone the repository:

2. Navigate to the project directory:

   ```bash
   cd drf_api_permissions_postgres
   ```

3. Build the Docker image:

   ```bash
   docker build -t drf_api_permissions_postgres .
   ```

4. Run the Docker container:

   ```bash
   docker run -p 8000:8000 drf_api_permissions_postgres
   ```

5. The API will be accessible at `http://localhost:8000/`.

## API Documentation

1- create element and view the lsit:
    `http://localhost:8000/api/v1/books`

2- Update or delete or show details for specific Item:
    `http://localhost:8000/api/v1/books/<id>`

3- create element and view the lsit of new in markets books:
    `http://localhost:8000/api/v1/books/newinmarkets`

4- Update or delete or show details for specific Item of new in markets books:
    `http://localhost:8000/api/v1/books/newinmarkets/<id>`

## to check tokens

### you need to hit on the api/token/ to get the token number

#### you can login and push posts on either favourites or movies routes

#### if token expired you can use the api/token/refresh/ route posting the token in the body as refresh: "Token" to create a refresh

## Author

Abdulkareem Abunabhan

If you have any questions or feedback regarding the project, you can contact me at zman17881@gmail.com
