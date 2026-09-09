# Express, NPM, TDD, CI/CD 

## An Introduction to NodeJS and Express 

A good starting point for this introduction would be to explain what is **Middleware**. **Middleware** is like a checkpoint between a user's request and the application's response. It can check, modify, or process information before allowing the request to continue. 

**What does it mean when it's said that Express is "unopinionated"?**

It means Express does not force developers to organize or build applications in one specific way. Developers have flexibility in choosing their structure, tools, and libraries. 

**What is a module and why is it useful?**

- A modules is a reusable piece of code designed to handle a specific task. Modularity helps developers organize code, reuse functionality, troubleshoot problems, and maintain larger applications more easily. 

# NPM 

**NPM** is a package manager for JavaScript. It allows developers to install, manage, and share packages or libraries that can be used in `Node.js` projects. 
The version that im running on my computer is: **11.18.0**

**How to install `jshint`?**
```
npm install jshint
```
## Test-Driven Development(TDD): 

**TDD** stands for *Test-Driven Development*. It is a development process where you write a test first, see it fail, write enough code to make it pass, then improve the code. 
Testing software is similar to checking that appliances work before using them or buying them. Test help make sure the program does what it's supposed to do and help catch problems before users encounter them. 

```
3 Benefits of testing:
- Finds bugs earlier.
- Makes changing code safer. 
- Helps confrim that the software meets its requirements. 
```
* Common testing pitfals could be individual pitfalls that include forgetting to run tests regularly and writing too many tests at once. Team pitfalls include abandoning tests when deadlines get closer and just poor maintanance of the team's test process. 

# CI/CD 

**3 Benefits of Continuous Integration (CI):**

1. Finds bugs and conflict earlier.
2. Allows developers to integrate their work frequently. 
3. Uses automated testing to improve software quality. 

| Continuous Delivery | Continuous Deployment | 
| ------------------- | --------------------- |
| Code is automatically tested and prepared for release, but the user decides when to release it. | Code that successfully passes the required checks can automatically be released to users. 

**How does GitHub fit into all of this?** 
Think of GitHub as a shared online workspace where developers store and collaborate on their code. When these developers submit changes, GitHub can automatically triggers tests and other checks. If everything passes the code can then move toward being released or deployed.  