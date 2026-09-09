# Express, REST and API 

## Review 

**Classes are a template for creating: <u>Objects.</u>**

**Can a class declaration be hoisted?** 

* Not in the same usable way as functions. You must declare the class before you use it. 

**Constructor and `this`:**

* A constructor is like the setup instructions used when creating a new object. `this` means "this specific object" that is currently being created or used.

# Using Express Routing

**Routing** determines how a server responds when a user or application sends a request to a particular URL or endpoint. 

| Route path | Route method |
| ---------- | ------------ |
| URL such as `/users` | HTTP action such as `GET`, `POST`, `PUT` or `DELETE`

**When should you use `next`?**

Use `next` when you want to request to continue to another middleware or route handler. If `next` is passed into your middleware, call `next()` when your middleware is finished and you want processing to continue. 

# Express Router 

An **Express Router** is a way to organize related routes into separate, manageable sections of your application. The way we initialize it is by using: 
```
const router = express.Router();
```
**Route middleware** perfroms actions before the final route handler, such as checking authentication, validating data, logging requests, or handling errors. 
