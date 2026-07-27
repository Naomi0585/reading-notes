# CRUD Basics and CRUD API

When working with web services, **CRUD** corresponds to the HTTP methods, which communicate to a web server how you want to interact with a website. In the case of updating records though an **API** we would use the `put` HTTP method which updates the existing data by replacing it with new data. 
The route for this request would be the following: `/example/:id.`

## REST methods that require an ID parameter: 

- **PUT**
- **DELETE** 

# Speed Coding: Building a CRUD API

**REST** provides the **API** endpoints and HTTP methods that allow you to perfrom **CRUD** operations. **REST** routes can be created using `GET,POST,PUT` and `DELETE` to implement **CRUD** actions. 

- Create ⟶ **POST**
- Read ⟶ **GET**
- Update ⟶ **PUT** 
- Delete ⟶ **DELETE**

## Creating a RESTful API: 
1. Set up the server using `Express` and configure the basic middleware.
2. Create the **REST** routes for the resource.
3. Connect the **API** to a database to store the data. (Ex. MongoDB).
4. Validate incoming data using a schema validation library before creating or updating records. 
5. Implement the **CRUD** operations then test each endpoint. 