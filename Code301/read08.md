# APIs

A **RESTful** web API implementation is a web API that employs *Representational State Transfer* (REST) architectural principles to achieve a stateless, loosely coupled interface between a client and service. A web API that is **RESTful** supports the standard HTTP protocol to perform operations on resources and return representations of resources that contain hypermedia links and HTTP operation status codes.

**REST** APIs are designed around a <u>Resource</u>. Resources such as objects, data, or services that can be accessed by the client. 

A **URI** (Uniform Resource Identifier) Identifies a resource. 
* Example: `https://api.contoso.com/orders/1`

**URI**S should be based on *nouns* (resources) rather than *verbs* (actions). 
The HTTP protocol defines many request methods that indicate the action that you want to perform on a resource.

A good **URI** would look like this: `https://api.contoso.com/orders` .

## HTTP Verbs: 
* GET
* POST
* PUT
* PATCH 
* DELETE 

**What does it mean to have a "chatty" web API? Is this a good or a bad thing?** 

*  A "chatty" API requires many separate requests between the client and server to complete an operation. This is generally considered <u>bad</u> because it increases network traffic and can reduce performance. The article suggests reducing chattiness through approaches like bulk operations.


* What status code does a successful GET request return?
 **200 (OK)**
* What status code does an unsuccessful GET request return?
 **404 (Not Found)**
* What status code does a successful POST request return?
 **201 (Created)**
* What status code does a successful DELETE request return?
 **204 (No Content)**