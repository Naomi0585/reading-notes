# Intro to JWT(JSON Web Tokens)

JSON Web Tokens (JWT) is an open standard (RFC 7519) that defines a compact and self-contained way for securely transmitting information between parties as a JSON object. JSON Web Tokens are useful for authorization, once the user is logged in, each subsequent request will include the JWT, allowing the user to access routes, services, and resources that are permitted with that token. JWT is also useful for information exchange, as they are a good way of securely transmitting information between parties. Because JWTs can be signed for example, using public/private key pairs you can be sure the senders are who they say they are.  

## JWT Structure: 
* **Header** - contains information about the token and the algorithm being used.
* **Payload** - contains the user's information or claims. 
* **Signature** - verifies that the token has not been changed or tampered with. 

# Security in JWT

JWTs can be either signed, encrypted or both. If a token is signed, but not encrypted, everyone can read its contents, but when you don't know the private key, you can't change it. Otherwise, the receiver will notice that the signature won't match anymore. 
Think of it like sending a package with a special secret seal. The sender uses the message and a secret key to create a unique signature. The receiver knows the secret too, so they can check the signature. If someone changes the message but doesn't know the secret, they cannot create the correct signature, so the receiver knows the message was changed and rejects it.

## Video: JWT Explained: 


JWT is useful for authentication and securely sharing information. After a user logs in, the server can give them a JWT. The user can then send that token with future requests instead of entering their username and password every time. Think of a JWT like a small digital ID card. It is compact, so it is easy and fast to send between a website and a server. It is self-contained because it can hold information about the user inside the token, so the server doesn't always have to look up that information in the database. 
