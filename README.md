# Joke API - RESTful API with Full HTTP Method Support and API Key Authentication 🎉

Welcome to the **Joke API** project! This API allows you to create, update, retrieve, and delete jokes. It showcases the power of RESTful architecture with full support for all major HTTP methods and API key-based authentication for secure usage.

## Key Features 🔑

-   **Full CRUD Operations:**
    
    -   `GET` jokes
    -   `POST` a new joke
    -   `PATCH` an existing joke
    -   `PUT` a joke
    -   `DELETE` a joke
    
-   **API Key Authentication:**  
    Only authorized users can access the API using their unique API key. This helps ensure data security and protects the API from unauthorized access.To delete all jokes you need this API key and for rest all the method you dont need it.
    
-   **HTTP Methods:**  
    This project utilizes **GET**, **POST**, **PATCH**, **PUT**, and **DELETE** methods, covering the full spectrum of RESTful API operations.
    

## Quick Start 🚀

### Prerequisites

-   **Node.js** installed on your machine
-   **Postman** for API testing (or any other API client)
-   Your personal **API key** (see below for instructions on generating one)

### How to Run the Project Locally

1.  Clone the repository:
    
    bash
    
    Copy code
    
    `git clone [repository-url]
    
2.  Install dependencies:
    
    bash
    
    Copy code
    
    `npm install` 
    
3.  Start the server:
    
    bash
    
    Copy code
    
    `node index.js` 
    
4.  The API will be running locally at `http://localhost:3000`.
    

### API Key Authentication

Every request must include a valid API key to authenticate. You can pass the API key in the request headers as follows:

bash

Copy code

`Authorization: Bearer <4VGP2DN-6EWM4SJ-N6FGRHV-Z3PR3TT>` 

### API Endpoints

-   `GET /jokes` – Retrieve a list of all jokes.
-   `POST /jokes` – Add a new joke (requires API key).
-   `PATCH /jokes/:id` – Update specific fields in a joke by ID.
-   `PUT /jokes/:id` – Replace a joke by ID.
-   `DELETE /jokes/:id` – Delete a joke by ID.

### Example API Usage

Here’s a sample **GET** request to fetch all jokes:

bash

Copy code

`curl -X GET http://localhost:3000/jokes -H "Authorization: Bearer <4VGP2DN-6EWM4SJ-N6FGRHV-Z3PR3TT>"` 

You can test all the endpoints using **Postman** or any other API client. The API provides JSON responses and proper error handling for missing or invalid requests.

## API Documentation 📄

For detailed instructions and parameters, please visit the official [https://documenter.getpostman.com/view/6048123/2s9XxsTv8Yc](#).

## Contributing 🤝

Feel free to fork this repository, submit issues, or contribute enhancements. Collaboration is always welcome!

----------

