# HTTP Status Codes for CRUD APIs

**CRUD** covers the four basic operations on a persistent resource: create, read, update, delete. Each maps cleanly to one HTTP method and a small set of valid status codes.

### Status Codes Based On REST Methods: 

* 100 = **Continue** When the client checks the server s willing to accept the request before sending it. 
* 200 = **OK** This is the default for successful reads. 
* 201 = **Created** The request was successful and a new resource was created. 
* 202 = **Accepted** Request was valid but the resource is loading.
* 300 = **Multiple Choices** When the client has to choose between multiple resources.
* 308 =  **Permanent Redirect** When the resource has moved permanently.
* 400 = **Bad Request** The request is invalid, missig required fields or contains wrong data types. 
* 500 = **Internal Server Error** The server encountered an unexpected problem.

### Additional Codes: 

* 204 = **No content** This status code is used when an update is successful but doesn't return any data to the client.
* 410 = **Gone** This status code indicates that the resource existed in the past but has been deleted or moved, and its new location is unknown. 
* 403 **Forbidden** This status code means the client is authenticated but they do not have permission to access the requested resource. 

## Building REST API With Node.js, Express and MongoDB

To keep sensitive information like the **MongoDB** connection string secure and out of the source code, we need to place our connection string inside our `.env` file. This prevents accidentally exposing it when sharing or ushing your project to *GitHub*. 

 We use `app.use(express.json())` to tell **Express** to automatically parse incoming *JSON* request bodies and store the data in `req.body`, allowing your application to access data sent by the client. 

 `/:id` is a route parameter that represents a dybamic value in the URL, allowing the user to access a specific resource by its ID using `req.params.id`.  

### What is middleware? 
* Middleware is a function that runs before the route handler. It can process requests, perform checks, retrieve data, or modify the request/response before passing control to the next function. 

### What is the difference between **PUT** and **PATCH**? 
- **PUT** replaces the entire resource with new data.
- **PATCH** updates only the fields that are provided, leaving the rest unchanged. 

### How to make a default value in schema: 

```
date: { 
    type: Date,
    required: true,
    default: Date.now
}
```
