# Securing Passwords 

If I  were to explain hashing to a non-technical friend I would use the example of storing a secret code instead of the actual password. For this I would use a tool called **Bycrypt** to turn the password into a random scrambled code called **hash** and save that hash into the database. When the user logs in, their password is checked against the saved hash to see if it matches, without storing their real password. 

## What  is Bycript and when do we use it? 

Bycript is an adaptive hash function based on the *Blowfish* symmetric block cipher cryptographic algorithm and introduces work factor (or security factor), which allows you to determine how expensive the hash function will be. This work factor value determines how slow the hash function will be, which means different work factors will generate different hash values in different time spans, which makes it extremely resistant to brute force attacks. Bycript might be used to protect passwords by turning them into a secure, scrambled code. This makes it much harder for someone to steal or figure out the original passwords if the database were to be hacked. 


# Basic Authentication

Basic access authentication is a method for an HTTP user agent (like a web browser) to provide a username and password when making a request. A request contains a header field in the form of `Authorization: Basic <<credentials>>`, where `<<credentials>>` is the **Base64** encoding user name and password joined by a single colon `:`.  Basic authentication is typically used in conjunction with HTTPS to provide confidentiality. Because the basic authentication field has to be sent in the header of each HTTP request, the web browser needs to cache credentials for a reasonable period of time to avoid constantly prompting the user for their username and password. 

# OWASP Authentication (Cheatsheet)

**Authentication** is the process of checking that someone is really who they say they are. For example, when you log into a website, it checks your username and password before giving you access to your account. 
Error messages should be simple and general in both HTTP and HTML responses. For example, say “Invalid username or password” instead of explaining exactly which one is wrong.
This helps prevent hackers from learning which usernames or accounts exist and keeps user information more secure.
